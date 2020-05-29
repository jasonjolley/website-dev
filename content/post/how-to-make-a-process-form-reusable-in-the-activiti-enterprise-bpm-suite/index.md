---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "How to Make a Process Form Reusable in the Activiti Enterprise BPM Suite"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2014-08-12T19:16:41-04:00
lastmod: 2014-08-12T19:16:41-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
![Activiti Editor](091415_0329_Howtomakeap1.jpg)

If you have ever created a process in the Activiti Enterprise BPM Suite, you have probably created forms within that process. If so, you may have run into that painful moment when you realize that the form you built within the process is not reusable to other processes. Luckily, there is an easy remedy, with a little tinkering in the database.

<strong>PLEASE NOTE: This is a useful hack, but a hack nonetheless. Please do not consider this a best practice.&nbsp;You should make every effort&nbsp;to avoid making direct database modifications.</strong>

In short, you need to do the following:
<ol>
 	<li>Find the Form ID, available in the URL address bar on the form page.</li>
 	<li>Find the row in the Activiti 'MODEL' table with that Form ID value in the ID field.</li>
 	<li>Replace the value in the 'REFERENCE_ID' field with a null value.</li>
</ol>
For more detail, I've included a step by step guide.
<h3>Find the Form ID</h3>
Within the process definition, select the task with the desired form. Select the 'Referenced form' value. In this example it is named 'Update Address Form'.

![BPMN Editor](091415_0329_Howtomakeap2.jpg)

Click the 'Open' button.

![Form Reference](091415_0329_Howtomakeap3.jpg)

The form will open on your screen. Look at the browser's URL address bar. Take a note of the last part of the URL. It is the form's ID.

![Form Page](Form-Page-medium-with-box.jpg)
<h3>Find the Row in the MODEL Table in the Activiti Database</h3>
Next, open the Activiti database's 'MODEL' table. Find the record with a matching ID (in this case '2007'). You'll notice a value in the 'REFERENCE_ID' field. This is the ID of the process model to which the form is currently associated. That process model is also in this table and can be seen with the ID 2006.

![Database Table](091415_0329_Howtomakeap5.jpg)
<h3>Update the Database</h3>
Remove the value in the REFERENCE_ID field for your form, leaving a null value in its place. Please note that modifying any system's underlying database comes with some risk. You should understand databases systems if you are going to make this change, and ideally, be in a development environment.

![Update Database](091415_0329_Howtomakeap6.jpg)

That's it! Now, if you navigate to the Forms page in the Kickstart app you will see your form listed as a reusable form.

![Reusable Form](091415_0329_Howtomakeap7.jpg)
