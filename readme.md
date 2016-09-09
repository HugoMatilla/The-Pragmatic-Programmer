#Chapter 1. A Pragmatic Philosophy
**Tip 1: Care About Your Craft**

**Tip 2: Think! About Your Work**

##1.-The Cat Ate My Source Code
**Tip 3: Provide Options, Don't Make Lame Excuses**

Instead of excuses, provide options. Don't say it can't be done; explain what can be done to salvage the situation.

###Challenges
How do you react when someone such as a bank teller, an auto mechanic, or a clerk—comes to you with a lame excuse? What do you think of them and their company as a result?

##2.-Software Entropy
One broken window, left unrepaired for any substantial length of time, instills in the inhabitants of the building a sense of abandonment—a sense that the powers that be don't care about the building. So another window gets broken. People start littering. Graffiti appears. Serious structural damage begins. In a relatively short space of time, the building becomes damaged beyond the owner's desire to fix it, and the sense of abandonment becomes reality.    

**Tip 4: Don't Live with Broken Windows**   

Don't mess up the carpet when fixing the broken window.

###Challenges

* Help strengthen your team by surveying your computing "neighborhood." Choose two or three "broken windows" and discuss with your colleagues what the problems are and what could be done to fix them.
* Can you tell when a window first gets broken? What is your reaction? If it was the result of someone else's decision, or a management edict, what can you do about it?

##3.-Stone Soup and Boiled Frogs
It's time to bring out the stones. Work out what you can reasonably ask for. Develop it well. Once you've got it, show people, and let them marvel. Then say "of course, it would be better if we added…."

_People find it easier to join an ongoing success._

**Tip 5: Be a Catalyst for Change**   

Most software disasters start out too small to notice, and most project overruns happen a day at a time. 
 
If you take a frog and drop it into boiling water, it will jump straight back out again. However, if you place the frog in a pan of cold water, then gradually heat it, the frog won't notice the slow increase in temperature and will stay put until cooked.

Don't be like the frog. Keep an eye on the big picture. 

**Tip 6: Remember the Big Picture**   

###Challenges
Can you determine whether you're making stone soup or frog soup when you try to catalyze change? Is the decision subjective or objective?

##4.-Good enough soup
The scope and quality of the system you produce should be specified as part of that system's requirements.

**Tip 7: Make Quality a Requirements Issue**

Great software today is often preferable to perfect software tomorrow. **Know When to Stop**

###Challenges

* Look at the manufacturers of the software tools and operating systems that you use. Can you find any evidence that these companies are comfortable shipping software they know is not perfect? As a user, would you rather (1) wait for hem to get all the bugs out, (2) have complex software and accept some bugs, or (3) opt for simpler software with fewer defects?
* Consider the effect of modularization on the delivery of software. Will it take more or less time to get a monolithic block of software to the required quality compared with a system designed in modules? Can you find commercial examples?

##5.-Your Knowledge Portfolio
_An investment in knowledge always pays the best interest._

* 1. Serious investors invest regularly—as a habit.
* 2. Diversification is the key to long-term success.
* 3. Smart investors balance their portfolios between conservative and high-risk,high-reward investments.
* 4. Investors try to buy low and sell high for maximum return.
* 5. Portfolios should be reviewed and rebalanced periodically


###Building Your Portfolio
* Invest regularly
* Diversify
* Manage risk
* Buy low, sell High
* Review and rebalance

**Tip 8: Invest Regularly in Your Knowledge Portfolio**

###Goals
* Learn at least one new language every year.
* Read a technical book each quarter.
* Read nontechnical books, too. 
* Take classes. 
* Participate in local user groups. 
* Experiment with different environments. 
* Stay current.
* Get wired.

You need to ensure that the knowledge in your portfolio is accurate and unswayed by either vendor or media hype. 
**Tip 9: Critically Analyze What You Read and Hear**

###Challenges
* Start learning a new language this week. 
* Start reading a new book (but finish this one first') If you are doing very detailed implementation and coding, read a book on design and architecture. If you are doing high-level design, read a book on coding techniques.
* Get out and talk technology with people who aren't Involved in your current project.

##6.-Communicate
* Know what you want to say. Plan what you want to say. Write an outline. 
* Know your audience. (WISDOM acrostic)
  * What they **Want**?
  * What is their **Interest**?
  * How **Sophisticated** are they?
  * How much **Detail** they want?
  * Who do you want to **Own** the information?
  * How can you **Motivate** them to listen)
* Choose your moment:  Understanding when your audience needs to hear your information.
* Choose a style:  Just the facts, large bound reports, a simple memo.
* Make it look good: Add good-looking vehicle to your important ideas and engage your audience.
* Involve your audience:  Get their feedback, and pick their brains. 
* Be a listener: Encourage people to talk by asking questions.
* Get back to people: Keep people informed afterwards.
**Tip 10: It's Both What You Say and the Way You Say It**

###Challenges
* There are several good books that contain sections on communications Try to read some of them.
* The next time you have to give a presentation, or write a memo advocating some position, try working through the wisdom acrostic before you start. See if it helps you understand how to position what you say. If appropriate, talk to your audience afterward and see how accurate your assessment of their needs was.

#Chapter 2. A Pragmatic Approach

##7.-The Evils of Duplication
The problem arises when you need to change a representation of things that are across all the code base.       
Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.   

**Tip 11: DRY—Don't Repeat Yourself**

Types of duplication:

* **Imposed duplication** Developers feel they have no choice—the environment seems to require duplication.
* **Inadvertent duplication** Developers don't realize that they are duplicating information.
* **Impatient duplication** Developers get lazy and duplicate because it seems easier.
* **Interdeveloper duplication** Multiple people on a team (or on different teams) duplicate a piece of information.

**Tip 12: Male it easy to reuse**

##8.-Orthogonality

Two or more things are orthogonal if changes in one do not affect any of the others. Also called *cohesion*.

**Tip 13: Eliminate Effects Between Unrelated Things**

Benefits:

* Gain Productivity
	* Changes are localized
	* Promotes reuse
	* M x N orthogonal components do more than M x N non orthogonal components
* Reduce Risk
	* Diseased sections or code are isolated
	* Are better tested
	* Not tied to a product or platform
* Project Teams: Functionality is divided 
* Design: Easier to design a complete project through its components
* Toolkits and Libraries: Choose wisely to keep orthogonality
* Coding: In order to keep orthogonality when adding code do:
	* Keep your code decoupled
	* Avoid  global data
	* Avoid similar functions
* Testing: Orthogonal systems are easier to test.
* Documentation: Also gain quality

###Challenges

* What feels better a large GUI-oriented tools or a small but combinable command line utilities. Which is easier to use? Which set is easier to combine?

*  Multiple inheritance, multiple interfaces. What impact does it have in orthogonality? What is the difference between using multiple inheritance and multiple interfaces? Is there a difference between using delegation or inheritance?

##9.-Reversibility
Be prepared for changes.

**Tip 14: There are no Final Decisions.**

##10-Tracer Bullets
In new projects your users requirements may be vague. Use of new algorithms, techniques, languages, or libraries unknowns will come. And environment will change over time before you are done.   
We're looking for something that gets us from a requirement to some aspect of the final system quickly, visibly, and repeatably.

**Tip 15: Use Tracer Bullets to Find the Target**

Advantages:

* Users get to see something working early
* Developers build a structure to work in
* You have an integration platform
* You have something to demonstrate
* You have a better feel for progress

###Tracer Bullets Don't Always Hit Their Target
Tracer bullets show what you're hitting. This may not always be the target. You then adjust your aim until they're on target. That's the point.


### Tracer Code versus Prototyping
With a prototype, you're aiming to explore specific aspects of the final system.    
Tracer code is used to know how the application as a whole hangs together.   

Prototyping generates disposable code.   
Tracer code is lean but complete, and forms part of the skeleton of the final system.

##11.-Prototypes and Post-it Notes
We build software prototypes to analyze and expose risk, and to offer chances for correction at a greatly reduced cost.   

Prototype anything that: 

* carries risk
* hasn't been tried before
* is absolutely critical to the final system
* is unproven 
* is experimental
* is doubtful

Samples:

* Architecture
* New functionality in an existing system
* Structure or contents of external data
* Third-party tools or components
* Performance issues
* User interface design   


**Tip 16: Prototype to Learn**


Avoid details:

* Correctness
* Completeness
* Robustness
* Style

Prototyping Architecture:

* Are the responsibilities of the major components well defined and appropriate?
* Are the collaborations between major components well defined?
* Is coupling minimized?
* Can you identify potential sources of duplication?
* Are interface definitions and constraints acceptable?
* Does every module have an access path to the data it needs during execution?

**Never deploy the prototype**

##12.-Domain Languages

**Tip 17: Program Close to the Problem domain**

##13.-Estimating
**Tip 18: Estimate to Avoid Surprises**

###How Accurate Is Accurate Enough?
**First:** Do they need high accuracy, or are they looking for a ballpark figure?

**Second:** Scale time estimates properly

| Duration   	| Quote estimate in                    	|
|------------	|--------------------------------------	|
| 1-15 days  	| days                                 	|
| 3-8 weeks  	| weeks                                	|
| 8-30 weeks 	| months                               	|
| 30+ weeks  	| think hard before giving an estimate 	|

###Where Do Estimates Come From?
Ask someone who's been in a similar situation in the past.

* Understand What's Being Asked
* Build a Model of the System
* Break the Model into Components
* Give Each Parameter a Value
* Calculate the Answers
* Keep Track of Your Estimating Prowess

###Estimating Project Schedules
The only way to determine the timetable for a project is by gaining experience on that same project.
Practice incremental development, repeating the following steps: 

* Guess estimation
* Check requirements
* Analyze risk
* Design, implement, integrate
* Validate with the users
* Repeat

The refinement and confidence in the schedule gets better and better each iteration

**Tip 19: Iterate the Schedule with the Code**

###What to Say When Asked for an Estimate
**"I'll get back to you."**

###Challenges
Start keeping a log of your estimates. For each, track how accurate you turned out to be. If your error was greater than 50%, try to find out where your estimate went wrong.


#Chapter 3. The Basic Tools
