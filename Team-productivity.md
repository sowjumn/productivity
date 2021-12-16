While every engineering organization has their own practices, here are a few I find most helpful in driving productivity and build successful teams. These opinions are my own and do not represent my current or past employers.

**1) Onboarding plan for new people on your team:**

We all have heard that notorious saying ‘We just dive into the code’. This thought process makes a new person's life on the team miserable and decreases productivity. Way too many times companies/teams get away with new employees working overtime to build up on the tools needed for the job. This also adds bias to the performance evaluation as well. A person who is single and with no kids might find time to put in extra hours, a person who has commitments to care for their loved ones feels left behind. So yes, if you expect the team member to work on a new language or tool, give them some time to learn the skills on the job. Give them detailed documented instructions on how to install various tools/software to keep their machine up to date, list the tools and languages they need to ramp up, and how to ramp up so they can start contributing. In other words, have a onboarding plan for new people on your team documented. This also adds consistency of using the same tools across the team and in turn improves productivity

**2) Code guidelines:**

If you are an engineer reading this, you know you can implement a system in many languages and you can write code in many styles. To have consistency across code and for better readability have documented code styles and guidelines. You may ask, how does this improve productivity? Having specific code styles and guidelines avoids multiple people having conflicting opinions on the pull request about the style of code. This adds to faster approval of the code and shorter iterations. If you don’t know where to start about coding styles/guidelines, here are a few open source code guidelines

Ruby style guide: https://github.com/airbnb/ruby 

Javascript style guide https://github.com/airbnb/javascript

**3) Code reviews:**

We all know code reviews are important. I think code reviews are essential. If you are an engineering leader, please have it as a requirement that any code merge happens only after another person on the team reviews and approves it. This strict requirement helps reduce errors and improve productivity.

**4) README:**

A README for a system helps understand the system on what it does at a high level. It helps people onboard faster and start contributing. Since we all know that a picture is worth a thousand words, a README should at least have an architectural diagram of what the system does. The README should also:

- Describe in words what other systems or services this service communicates with and how it communicates.
- Enlist which datastore the system(if it's stateful) uses and how to set up one locally.
- Have detailed instructions on how to set up the development environment of the system and should enlist links to staging and production apps.
- Have links to the metrics dashboards that show the health of the system.
- Enlist the different software languages and tools the system uses and is implemented in and which version of the software the system uses. For example docker, terraform and such.
- Provide detailed instructions and commands on how to deploy the service, the permissions needed to deploy and where to find the logs.
- Enlist the testing languages the system uses.

**5) Documentation**

Code is not documentation. Documentation helps people who are on-call to quickly reference and refresh systems in the middle of the night. It helps management to understand the systems as they tie business objectives to engineering problems and new employees to get onboarded faster. As such every code repository needs a docs folder that describes what each component of your system is doing and how to do a high level maintenance of your system. It should also have playbooks for on call people to quickly resolve any errors and keep the service up and running. If you are an engineering leader, I hope you make documentation as a requirement to a delivery checklist before finishing the feature.

**6) Retrospectives**

Retrospectives are as important as planning meetings. They say you learn more from failures so you don’t repeat them. Even though it’s uncomfortable, it is vitally important to list what went wrong and what you could do better. During these retrospectives, try not to assign blame to a person (mistakes happen) but rather create action items. In addition to listing what went wrong and what could be done better, make sure you take time to list and discuss things that went great. As important it is to have reflection, it is also important to acknowledge our successes and build upon them. I have found that gratitude exercises among team members boost team morale and happiness.

**7) No Deploy Fridays:**

We all need to recover and refresh and that is what weekends are for. Try to not deploy code changes on Fridays and if you have a continuous deployment system, then don't merge your code on Fridays. Of course there are exceptions. Unless the change resolves a downtime, it can wait till Monday morning when everyone on the team is ready to tackle any downtime.

**8) Let your team members sleep:**

Believe in your team and build a healthy relationship with your colleagues. We all have seen that micromanager or that toxic coworker which caused attrition. If a leader believes and trusts the team members, and the team members trust each other, then it’s less likely the team members have anxiety and more likely that they sleep better. In addition having a good work life balance gives one enough time to sleep. Sleep is often very underrated and studies have shown that better sleep adds to productivity and helps facilitate a happier and healthier lifestyle. If you are an engineering leader, having an OKR that focuses on sleep will add to the productivity of the team.

I hope you have enjoyed reading this article and thank you for making it this far! Beyond these 8 practices of productive engineering teams, what other practices have worked for you?
