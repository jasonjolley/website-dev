---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "How to Create a High Performance Alfresco Development Team"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2015-09-25T12:45:06-04:00
lastmod: 2015-09-25T12:45:06-04:00
featured: true
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

![Alfresco Summit Lightning Talk](small-lightning-talk.jpg)

{{% alert note %}}
This article was written in September 2014. It stays true even today. One difference is that instead of coding with Share, I recommend focussing on Alfresco's ADF framework.
{{% /alert %}}

Creating a high performance Alfresco development team does not happen by accident. You need to build a team of professional developers, with a consistently adopted development methodology.
<h2>People First</h2>
Hiring good teammates is the riskiest part of building a development team. Mistakes here are costly, with their ill-effects long reaching. Define the profile of the person you would like to hire. For a developer, some common traits are:
<ul>
 	<li>Problem Solver</li>
 	<li>Continuous Learner</li>
 	<li>Professional Work Ethic</li>
 	<li>Good Communicator</li>
 	<li>Team Player</li>
 	<li>Community Contributions</li>
 	<li>Technology Experience</li>
</ul>
In general, most software developers are not employed in jobs that promote good coding principles. Look for people who have always sought to increase their skills and learn new things, outside of the scope of their current position. Even the most senior developers may not adopt the level of professionalism that you require from your teammates. In hiring, you need to make sure potential candidates have the drive and ability to perform well. Your team will create the culture of craftsmanship that helps new team members aspire to be better than they are today.
<h2>The Interviews</h2>
Phone interviews are a must for getting a base level of confidence in a candidate's abilities. While there is no particular list of technical skills that a candidate must have, it is useful if the candidate can profess knowledge on the following areas:
<ul>
 	<li>Core Java</li>
 	<li>Familiarity with Java web servers (i.e. Tomcat)</li>
 	<li>Object Oriented Knowledge</li>
 	<li>Restful Web Services</li>
 	<li>HTML</li>
 	<li>JavaScript, JSON, jQuery</li>
 	<li>Unit Testing</li>
 	<li>Dependency Injection</li>
 	<li>Ability to program in additional languages (Ruby, C#, Groovy, etc.)</li>
</ul>
If successful with the phone screen, an in-person interview should be held. You should have several people involved in this interview. During an active recruitment cycle, many in-person interviews can create time constraints on the interviewers. This is unavoidable. The interview team needs to accept that the time commitment is necessary, and plan their time appropriately.

In preparation for the in-person interview, there should be a workstation ready for the candidate to use during a coding exercise. It is critical that you have the candidate write code during the interview. This is one of the best ways to get insight on the candidate's capabilities.

Even with all the technical criteria satisfied, you still need to ensure that the candidate is a good fit for the team. Are they a constant learner? Do they enjoy working with other people? Can they put their ego aside to learn from everyone? Do they aspire to be greater than they are? When you are looking to hire people start by using your network. '<a href="http://www.whothebook.com/">Who: The A Method for Hiring</a>' by Geoff Smart and Randy Street is a fantastic book on the method for hiring good people.

Remember that this is your big chance to avoid a costly mistake. Every time you hire a new team member there is the potential that you may have to fire them if it doesn't work out. It is better to have a tough interview process then to later fire a poor-performing team member for issues that could have been vetted in the interview process.
<h2>You're Hired! Now What?</h2>
Before starting Alfresco project development, all team members need to be on the same page regarding the best practices to which they are held accountable. As a profession, Software Development is in its infancy. Accountants, Doctors, and Engineers all have standards and codes to which they are held accountable. Software Developers do not have such widely accepted and enforceable standards. If you'd like to have a highly successful development team, you need to establish a set of standards that ensure your team's professionalism.

You need to have a developer code of conduct that provides clear language on those expectations. The developer code of conduct enforces a level of professionalism and craftsmanship not typically seen in software development. If you don't have something like this in place, I highly recommend you start by viewing a presentation titled '<a href="http://vimeo.com/54025415">The Reasonable Expectations of your CTO'</a> by 'Robert Martin'. Building on the code of conduct, it is also useful to have a set of standard operating procedures in relation to how your code is written, and your development methodology. Again, if you're starting from scratch, I recommend you start by providing all new hires the following three books:
<ul>
 	<li><a href="http://www.amazon.com/Clean-Coder-Conduct-Professional-Programmers/dp/0137081073/ref=sr_1_1?ie=UTF8&amp;qid=1411744400&amp;sr=8-1&amp;keywords=the+clean+coder">The Clean Coder</a> by Robert C. Martin</li>
 	<li><a href="http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882/ref=sr_1_1?ie=UTF8&amp;qid=1411744441&amp;sr=8-1&amp;keywords=the+clean+code+handbook">The Clean Code Handbook</a> by Robert C. Martin</li>
 	<li><a href="http://www.amazon.com/Agile-Samurai-Software-Pragmatic-Programmers/dp/1934356581/ref=sr_1_1?ie=UTF8&amp;qid=1411744473&amp;sr=8-1&amp;keywords=the+agile+samurai">The Agile Samurai</a> by Jonathan Rasmusson</li>
</ul>
Now, let's look at Alfresco. Alfresco is a fairly complex product that leverages a broad spectrum of tools. A new developer is challenged with learning how to configure and customize Alfresco. Here is a sample learning path:
<ul>
 	<li>An Alfresco Architecture Overview</li>
 	<li>Alfresco Tutorials (Start with Jeff Potts' tutorials on <a href="http://www.ecmarchitect.com">http://www.ecmarchitect.com</a>)</li>
 	<li>An Alfresco Bootcamp. This can be Alfresco provided training, or a home grown bootcamp based on your in-house skill set and project needs.</li>
</ul>
<h2>Your Operating Tools</h2>
Every developer needs to have an awesome computer, preferably a laptop. You should leverage free and open source tools where possible. For commercial tools, <a href="http://www.jetbrains.com/idea/">IntelliJ</a> and <a href="http://zeroturnaround.com/software/jrebel/">JRebel</a> provide a great return on investment in terms of software quality and developer efficiency.

Other tools that should be part of your infrastructure are:
<ul>
 	<li>A virtualized server environment. If you have the ability to do this on your own bare metal that's great. Otherwise, there is a plethora of cloud options available (Azure, Amazon, etc.)</li>
 	<li>Source Control Server (Subversion, Git)</li>
 	<li>Continuous Build Server (Jenkins)</li>
 	<li>A Maven Repository (Sonatype Nexus)</li>
 	<li>Local Code Analysis (IntelliJ &amp; Visual Studio have good tools)</li>
 	<li>Centralized Code Analysis Server (Sonar)</li>
 	<li>Issue Tracking (JIRA)</li>
</ul>
These tools should be integrated together. A source code change should launch a build in the continuous build server. That build should trigger code analysis, and possibly a release build to be stored in the Maven repository. Ideally, all source code changes should have a mechanism to integrate with an issue tracking system. You can do this by having a pre-commit hook to enforce a JIRA ticket be entered with each code check-in.
<h2>Let's Get Coding with Alfresco</h2>
The easiest way to start developing with Alfresco is to leverage the <a href="http://wiki.alfresco.com/wiki/Maven_Alfresco_SDK">Alfresco Maven SDK</a>. For more information, a great resource is <a href="http://mindthegab.com/">Gabriele Columbro's blog</a>. By leveraging maven, new team members can quickly get a local development environment up and running.
<h3>Bootstrap Everything!</h3>
Alfresco has a wonderful mechanism to bootstrap your customizations into a custom module, called an AMP. This makes it easy to create a specialized deployment for Alfresco, without repeating deployment steps for each new environment. Common items for bootstrapping are:
<ul>
 	<li>Metadata Model</li>
 	<li>Folders</li>
 	<li>Rules</li>
 	<li>Users</li>
 	<li>Groups</li>
</ul>
For more advanced development teams, you can also build customizations to bootstrap:
<ul>
 	<li>Sites</li>
 	<li>Data Lists</li>
 	<li>Re-usable Access Control Lists</li>
</ul>
<h3>Basic Configuration</h3>
Virtually every Alfresco project has a set of core configurations that need to be implemented.
<ul>
 	<li>Custom Metadata</li>
 	<li>Share Details Page(s)</li>
 	<li>Share Search Page(s)</li>
 	<li>Basic Branding</li>
 	<li>User, Group Integration [This is often an integration and synchronization with a LDAP user directory]</li>
</ul>
<h3>Common API Customization</h3>
Once you get past basic configuration, you'll need to write some custom code to implement additional features. <a href="http://ecmarchitect.com/alfresco-developer-series">Jeff Potts' tutorials</a> are an excellent place to look for technical direction. Typically, these customization include:
<ul>
 	<li>Custom Service classes. These will be the base implementation of your custom logic.</li>
 	<li>Actions. Typically ActionExecutor classes. These will expose your service classes' functionality to Alfresco's Action framework, making them available for use in Rules, JavaScript, Java, etc.</li>
 	<li>Web Scripts. Essentially a RESTful API exposing your action and service classes.</li>
</ul>
<h3>Workflow</h3>
Alfresco leverages Activiti as its core BPMN 2.0 compliant workflow engine. A custom workflow typically involves the following customizations:
<ul>
 	<li>Custom Model</li>
 	<li>BPMN Diagram</li>
 	<li>Share Task Screens</li>
 	<li>Custom Task Listeners.</li>
</ul>
Most Alfresco samples use JavaScript for the Task Listeners. This is great for simple cases. For anything more complex, I recommend the use of Java based Task Listeners. This provides greater reuse, more testing flexibility, and better code analysis options.
<h2>Go Team!</h2>
As a high performing Alfresco development team, you need to be accountable for the quality of your deliverables. Unit testing should be pervasive within your application. All task should be estimated, and have their actual effort recorded for traceability. Code analysis tools should display zero violations, high coverage, and few duplications.

While everything discussed above may not be easy, it is a roadmap for defined and repeatable success. It provides your team with clearly outlined guidelines on behavior, and provides the necessary tools for team accountability.

If you have any questions, please feel free to email me at <a href="mailto:jason@jasonjolley.com">jason@jasonjolley.com</a>.
