# 1. Customer Obsession

    Leaders start with the customer and work backwards. They work vigorously to earn and keep customer trust. Although leaders pay attention to competitors, they obsess over customers.

## Example Qustions

* Who was your most difficult customer?
* Give me an example of a time when you did not meet a client’s expectation. What happened, and how did you attempt to rectify the situation?
* When you’re working with a large number of customers, it’s tricky to deliver excellent service to them all. How do you go about prioritizing your customers’ needs?
* Tell the story of the last time you had to apologize to someone.

## Podcast Manager UI

* At Univar, I developed the process to embed and link to podcasts and display them on our customer facing site.
  * The internal users are business oriented and not technical. 
* I knew that creating a minimal user interface for the internal side would cause frustration and delay
* I put just as much energy and focus into makeing the internal application a good user experience as the backend side
  * I created a preview of the podcast to show how changes would effect the site
  * Even though we didn't use material ui, I followed the guidelines as closely as possible
  * I made sure to provide messages when there may have been ambiguity about the behavior of the application
* When I handed it off for the internal user to upload our first podcast, I watched while avoided giving any instructions.
  * While there were a couple of cases where the user had to dig around to find what they wanted to do, they were able to do their job with zero interaction from me.
 
## Excel Guy

* At International Paper, there was an application for the salespeople to manage opportunities of potential customers
* When going through the potential changes for the application in a later release, we also looked through some of the user analytics and behaviors
* I noticed there was a person who had very short session times, but uploaded a good many opportunities
  * I was able to quiz the salesperson and confirmed a suspision that they kept their data in excel and updated the application occasionally
  * When I asked why excell was preferred, it turns out that there was a field that the application required but the salesperson didn't always know the answer to at the time they uploaded it
* When I submitted that information to the review process, we were able to determine that the reqirement of that field wasn't as crucial to the data integroty as we though, and I removed that requirement in a later change

# 2. Ownership

    Leaders are owners. They think long term and don’t sacrifice long-term value for short-term results. They act on behalf of the entire company, beyond just their own team. They never say “that’s not my job”.

## Example Questions

* Tell me about a time when you had to leave a task unfinished.
* Tell me about a time when you had to work on a project with unclear responsibilities.

## Distance Redesign

* At Distance at State, the fulltime web developer left the division just after starting a project to redesign our student facing website
* After it was clear that it would take a while to find a replacement, I was asked to continue the project.
* So, I did it
  * I placed all of the content into a CMS from scratch
  * I used some of the styling changes that had already been used, but heavilly adjusted it based on feedback 
  * I used my own judgement to design dozens of new pages, and I constantly asked for feedback from my manager, the director, and othres in the devision
* Even thoug I was a student worker, I was able to not only finish the base reimplementation, but deploy it before we hired the new fulltime developer.
  * This project was the first impression of hundreds of daily users for about 3 years before the next reimplementation

## Make PestWeb not suck

* Univar had a customer facing store website called Pestweb (at the time of joining)
* There were three devs, myself included, that maintained the site
* While doing other changes, I came across many inconsistencies in the UI that I strongly felt should have been fixed
* Instead of putting a task in for someone else to take, I documented all the bugs and inconsistencies I found in the UI and chose to fix the low work / high reward issues.
  * For example, a major change was a misalignment in the search bar that showed on every page on the site
* I submitted the change and it went live, making me happier about the site that I am responsible for.  I made our customer experience that much better.
  * Furthermore, I demonstrated to my teammates that it does not take too much extra time to make our UX that much better.

## Others

* Fiori Launchpad App
* Distance internal apps (taken over from a class project)
* Phone work at Univar

# 3. Invent and Simplify

    Leaders expect and require innovation and invention from their teams and always find way to simplify. They are externally aware, look for new ideas everywhere, and are not limited by “not invented here”. As we do new things, we accept that we may be misunderstood for long periods of time.

## Example Questions

* Tell me about a time when you gave a simple solution to a complex problem.
* Tell me about a time when you invented something.

## Fiori Launchpad App: Build Automation

* At International Paper, I was given responsibility over customizing and building a hybrid iOS application that was distributed by SAP
* Every time the application was updated, I had to go through the same steps that I had documented
  * After feedback and testing, it was weeks before we could distribute the app ourselves
* To address this bottleneck, I wrote a node script that performed the edits to customize the app
* When I investigated how to make this process better, I discovered the big node task runners and implemented them
  * These happened to also have tasks to do the vast majority of the build process as well, even on the iOS system
* After taking a little extra time to implement this, I turned lower the turnaround time to a matter of hours
  * This app was able to get into the hands of hundreds of salespeople that much faster

## Others

* Generated technical specifications from docblocks in SAPUI apps
  * Demonstrated the use of JSDoc to provide generated documentation for our SAPUI5 solutions.
* PrePost model for SAPUI5
* Document Database
* LADI?

# 4. Are Right, a Lot

    Leaders are right a lot. They have strong business judgment and good instincts. They seek diverse perspectives and work to disconfirm their beliefs.

## Example Questions

* Tell me about a time when you were wrong.
* Tell me about a time when you had to work with incomplete data or information.

## Waerhauser almost mishap

* At International Paper, the company acquired Waerhauser's pulp and paper business.
* I was tasked with building and executing overnight cutover processes to bring new employees into our HR SAP system.  During the cutover, everything failed and teammates started becoming stressed out
* I was on the front lines of troubleshooting and correcting this issue
  * Analyzing the situation, I knew the one differece between this and our tests was the fact that the machine was locked away from the outside world.
  * I had no reservation against undoing this, as I knew our processes could work even in every day traffic.
  * I was confident that the way forward was to unlock this system and restart our process.
  * When tempers and stress started to build, I made a point to verbally state what our path forward is
* After a few hours of troubleshooting, we got word from project management that we were allowed to unlock the system.
  * The process completed successfully and we imported about 3000 new employees by the morning.

## Others

* Univar: SD Card Impending Doom
* Waerhauser acquisition almost-mishap

# 5. Learn and Be Curious

    Leaders are never done learning and always seek to improve themselves. They are curious about new possibilities and act to explore them.

## Example Qustions

* Tell me about a time when you influenced a change by only asking questions.
* Tell me about a time when you solved a problem through just superior knowledge or observation.

## Excel Guy

* At International Paper, there was an application for the salespeople to manage opportunities of potential customers
* When going through the potential changes for the application in a later release, we also looked through some of the user analytics and behaviors
* I noticed there was a person who had very short session times, but uploaded a good many opportunities
* I was able to quiz the salesperson and confirmed a suspision that they kept their data in excel and updated the application occasionally
* When I asked why excell was preferred, it turns out that there was a field that the application required but the salesperson didn't always know the answer to at the time they uploaded it
* When I submitted that information to the review process, we were able to determine that the reqirement of that field wasn't as crucial to the data integroty as we though, and I removed that requirement in a later change

## Other Answers

* CGBS

# 6. Hire and Develop the Best

    Leaders raise the performance bar with every hire and promotion. They recognize exceptional talent, and willingly move them throughout the organization. Leaders develop leaders and take seriously their role in coaching others. We work on behalf of our people in invent mechanisms for development like Career Choice.

## Example Qustions

* Tell me about a time when you mentored someone.
* Tell me about a time when you made a wrong hire. When did you figure it out and what did you do?

## STAR Examples

Taught Javascript at IP

# 7. Insist on the Highest Standards

    Leaders have relentlessly high standards – many people may think these standards are unreasonably high. Leaders are continually raising the bar and driving their teams to deliver high quality products, services and processes. Leaders ensure that defects do not get sent down the line and that problems are fixed so they stay fixed.

## Example Qustions

* Tell me about a time when you couldn’t meet your own expectations on a project.
* Tell me about a time when a team member didn’t meet your expectations on a project.

## Make PestWeb not suck

* Univar had a customer facing store website called Pestweb (at the time of joining)
* There were three devs, myself included, that maintained the site
* While doing other changes, I came across many inconsistencies in the UI that I strongly felt should have been fixed
* Instead of putting a task in for someone else to take, I documented all the bugs and inconsistencies I found in the UI and chose to fix the low work / high reward issues.
  * For example, a major change was a misalignment in the search bar that showed on every page on the site
* I submitted the change and it went live, making me happier about the site that I am responsible for.  I made our customer experience that much better.
  * Furthermore, I demonstrated to my teammates that it does not take too much extra time to make our UX that much better.

## Others

* Adhearence to Fiori UX Guidelines
* Code reviews
* Refusal for "This is the way we always do it" that I told Charley

# 8. Think Big

    Think Big Thinking small is a self-fulfilling prophecy. Leaders create and communicate a bold direction that inspires results. They think differently and look around corners for ways to serve customers.

## Example Questions

* Tell me about your proudest professional achievement.
* Tell me about a time when you went way beyond the scope of the project and delivered.

## Distance Redesign

* At Distance at State, the fulltime web developer left the division just after starting a project to redesign our student facing website
* After it was clear that it would take a while to find a replacement, I was asked to continue the project.
* So, I did it
  * I placed all of the content into a CMS from scratch
  * I used some of the styling changes that had already been used, but heavilly adjusted it based on feedback 
  * I used my own judgement to design dozens of new pages, and I constantly asked for feedback from my manager, the director, and othres in the devision
* Even thoug I was a student worker, I was able to not only finish the base reimplementation, but deploy it before we hired the new fulltime developer.
  * This project was the first impression of hundreds of daily users for about 3 years before the next reimplementation

## Others

* Casper
* Accidentally Attempting to write a php framework

# 9. Bias for Action

    Bias for Action Speed matters in business. Many decisions and actions are reversible and do not need extensive study. We value calculated risk taking.

## Example Questions

* Describe a time when you saw some problem and took the initiative to correct it rather than waiting for someone else to do it.
* Tell me about a time when you took a calculated risk.
* Tell me about a time you needed to get information from someone who wasn’t very responsive. What did you do?

## STAR Examples

We are doing scrum now
Pestweb UI

# 10. Frugality (unlikely)

    Frugality Accomplish more with less. Constraints breed resourcefulness, self-sufficiency and invention. There are no extra points for growing headcount, budget size or fixed expense.

## Example Questions

* Tell me about a time when you had to work with limited time or resources.

# 11. Earn Trust

    Leaders listen attentively, speak candidly, and treat others respectfully. They are vocally self-critical, even when doing so is awkward or embarrassing. Leaders do not believe their or their team’s body odor smells of perfume. They benchmark themselves and their teams against the best.

## Example Qustions

* What would you do if you found out that your closest friend at work was stealing?
* Tell me about a time when you had to tell someone a harsh truth.

## STAR Examples

  When things got tense with Jon, I gripped about the loud door

# 12. Dive Deep

    Leaders operate at all levels, stay connected to the details, audit frequently, and are skeptical when metrics and anecdote differ. No task is beneath them.

## Example Qustions

* Give me two examples of when you did more than what was required in any job experience.
* Tell me about something that you learnt recently in your role.

## IP Launchpad App: Dive Deep

* IP had a hybrid iOS web application that was provided by SAP, but we still had to enhance and customize the application
* I became the "app guy" and was tasked for building, signing, and releasing app for every update
  * Especially odd because I am an android user
* The process of customizing the application was partially laid out by SAP, but we had our own changes outside of that
* The process of building and signing the app was mostly standard, so youtube was my best friend
* To wrap everything together, I documented the procedures along with the project.
  * This solidified my comfort with the process, and also gave future devs a stronger starting point
  * This also allowed for automation, so we were eventually able to deliver updated version of the app in a matter of days instead of weeks
  
Casper
LADI

# 13. Have Backbone; Disagree and Commit

    Leaders are obligated to respectfully challenge decisions when they disagree, even when doing so is uncomfortable or exhausting. Leaders have conviction and are tenacious. They do not compromise for the sake of social cohesion. Once a decision is determined, they commit wholly.

## Example Qustions

* Tell me about a time when you did not accept the status quo.
* Tell me about an unpopular decision of yours.
* Tell me about a time when you had to step up and disagree with a team members approach.
* If your direct manager was instructing you to do something you disagreed with, how would you handle it?

## Podcast MVC Conflict

* At Univar, our Marketing department wanted to create podcasts and display them on our website
* I was tasked with creating both the customer facing page and a backend application to create and manage these podcasts
* Upon code review, my coworker commented that the code to determine the main embedded link among a list of links should have been done in the controller.
  * My experience with MVC frameworks has taught me that data formatting should be done in the model and not the controller
* When it was clear that we were at an impass, I called for a team meeting to determine what the team's preference is in this situation.
* The team agreed that this should be done in the model, but there was also a better method of doing it in the model that avoided unneccesarry database calls I was making.  This made me incredibly happy


# 14. Deliver Result

    Leaders focus on the key inputs for their business and deliver them with the right quality and in a timely fashion. Despite setbacks, they rise to the occasion and never settle.

## Example Qustions

* By providing an example, tell me when you have had to handle a variety of assignments. Describe the results.
* What is the most difficult situation you have ever faced in your life? How did you handle it?
* Give me an example of a time when you were 75% of the way through a project, and you had to pivot strategy–how were you able to make that into a success story?

## Distance Redesign: Long Haul

TODO 

* At Distance at State, the fulltime web developer left the division just after starting a project to redesign our student facing website
* After it was clear that it would take a while to find a replacement, I was asked to continue the project.
* So, I did it
  * I placed all of the content into a CMS from scratch
  * I used some of the styling changes that had already been used, but heavilly adjusted it based on feedback 
  * I used my own judgement to design dozens of new pages, and I constantly asked for feedback from my manager, the director, and othres in the devision
* Even thoug I was a student worker, I was able to not only finish the base reimplementation, but deploy it before we hired the new fulltime developer.
  * This project was the first impression of hundreds of daily users for about 3 years before the next reimplementation
