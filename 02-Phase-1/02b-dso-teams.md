# Establishing DevSecOps Organizations in the DoD 

## Learning Objectives

By the end of this lesson you will be able to:

* Recognize the ability and **need** for roles to be fluid, because environments are dynamic
* Articulate Software Practitioner roles and teams
* Define how to implement Software Practitioner teams within the Government
* **BONUS:** Have a basic understanding of DevSecOps organization

## Introduction 

A few disclaimers before diving into this lesson:
* Each definition can be tailored, there are multiple ways to define each competency area. This is the definition for this course.
* Each program may require different competencies, and all may not be required. 
* Remember industry is a critical partner that can help augment your internal organic (military and civilian) team and provide additional required expertise
* Even if you have organic capability to cover all required competencies, your software acquisition team _is still_ a critical enabler
* Review the following definitions with your team and re-define as necessary in your context. **A critical foundation is common understanding and lexicon across your team.** 

## Basic DevSecOps Competency Areas

Throughout this course, we will refer back to the definitions and build upon them in later lessons and modules.

### !callout-danger

## Disclaimer
Below we list common Software Practitioner roles supporting DevSecOps. However, this **should not** be interpreted as **all** projects needing **all** of these roles every time. As stated above, it depends on a number of factors, like your mission, desired capability, deployment environment, etc.

### !end-callout

### Product Owner:
Product Owners manage the Agile process, and are ultimately responsible for the success of the product. They are responsible for prioritizing development of features and functionality, defining acceptance criteria for features, and providing demonstrations/reviews to stakeholders. Sometimes dual-hatted as the Product Manager.

### Product Manager:
Product Managers are responsible for working closely with the requirements and user community to ensure that requirements reflect their needs, priorities and align to mission objectives. Sometimes dual-hatted as the Product Owner.

### Software Developers (Engineers) – Front-End:
Front End Software Developers/Engineers individually and/or as a team develop front-end functionality and interfaces to support the organization’s vision (design and write code).

### Software Developers (Engineers) – Back-End:
Back-End Software Developers/Engineers develop the functionality behind the scenes to support data capture, data transfer, and/or other back-end functionality.

### User Experience Designers:
User Experience Designers design the way a user will interact with the product, how it will look, and how it will work; working with front-end developers, they then make sure the product logically flows and visually communicates.

### Content Development:
Content Development teams or individuals build content and realize the vision set forth by the organization, while following a digital content strategy.

### Security:
Security teams or individuals support the security component of digital service development from the start, and ensure the safe and secure delivery and use of digital services. This includes data protection, security, and privacy.

### Deployment Engineers:
Deployment teams or individuals work to automate delivery of the digital service from development and testing environments, to production environments.

### Testers:
Testing teams or individuals work with Product Owners to define acceptance criteria for features, and work with Developers to make sure they meet those criteria. Ultimately, testing is the job of the team, and should be integrated into every step along the way. Best practices call for code developers to be testers as well, i.e. wearing dual hats to allow for more in-depth testing from the lowest level.

### End User:
End users are who ultimately interact with and use the digital service.
<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: checkbox
* id: dc448fd3-9228-445e-abc1-b84377c7f426
* title: Team Members
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Select all that are roles that are part of the DevSecOps team

##### !end-question

##### !options

* Software Developer / Engineer
* Product Owner
* Software Program Manager
* Security
* Contracting Officer
* Financial Manager

##### !end-options

##### !answer

* Software Developer / Engineer
* Product Owner
* Software Program Manager
* Security
* Contracting Officer
* Financial Manager

##### !end-answer

### !hint
Does it seem like they all support DevSecOps implementation?
### !end-hint

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

You may ask yourself, "Where do I find all of this new talent?" There’s good news- each organization is already composed of a talented team. Furthermore, not all teams look the same. Your DevSecOps team can be composed of some combination of organic (military or civilian) and/or contractor support. There is no perfect combination, and we all have factors that influence our decisions (assigned organic personnel, availability of funding, etc.) There is one caveat- let’s refer back to Dr. Royce’s ‘waterfall’ paper :

>To give the contractor free rein between requirement definition and operation is inviting trouble.
>
><span style="font-size: .8em">Source: [Managing the Development of Large Software Systems - Dr. Winston W Royce](http://www-scf.usc.edu/~csci201/lectures/Lecture11/royce1970.pdf) </span>

To be clear, the key is that your organic support, even if limited, must still communicate often with the contractor team.

**The Bottom Line:** We all have talented team members. With a little motivation and investment, teams can adapt to new roles, and when motivated people are solving the right problems, they may just surprise you.

## DevSecOps Teams

In our old ways of working, teams work within a system where each developer is assigned a set of tasks. This creates individual ownership of subsystems within the team, as well as dependency (and therefore risk). What happens if that individual is sick? Quits?

* This way of working is destructive to the quality, flow, and value of delivery  
* Nothing concludes quickly
* Little to no collaboration
* No context for someone else’s work, making code review ineffective
* Continuous integration falls apart

### !callout-info
## Conway’s Law
“Organizations which design systems...are constrained to produce designs which are copies of the communication structures of these organizations.”
### !end-callout

Stated another way, **Conway's Law** illustrates “team structures must match the required software architecture or risk producing unintended designs.” [_Team Topologies_](https://teamtopologies.com/book)

>“If the architecture of the system and the architecture of the org are at odds, the architecture of the org wins."
><span style="float:right;"> - Ruth Malan</span> 

**The Inverse Conway Manoeuver states:** “that organizations should evolve their team and organizational structure to achieve the desired architecture. The goal is for your architecture to support the ability of teams to get their work done--from design through deployment--without requiring high bandwidth communication between teams.” [_Accelerate: The Science of DevOps_](https://itrevolution.com/accelerate-book/)

We are only introducing this topic, and will provide further detail later. A great resource for you and your teams on this topic is: [_Team Topologies_](https://teamtopologies.com/book)

We are intentionally not answering the question of: “So how do we organize?” Each scenario has its own benefits and drawbacks and only you and your team understand the unique context you work within.  We do believe the most valuable team construct is optimizing for flow and value. The focus in building a DevSecOps team should be to deliver higher quality sooner in a sustainable and resilient way (hopefully with happy teams).  


<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: multiple-choice
* id: a9b0b196-af95-40c7-aa63-e3200637ea7d
* title: Team priorities
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

What is a team’s top priority in the DevSecOps environment?

##### !end-question

##### !options

* Automate
* Deliver Features
* Build a pipeline
* Deliver higher quality sooner and sustainably

##### !end-options

##### !answer

* Deliver higher quality sooner and sustainably

##### !end-answer

### !hint
In this lesson we learned that delivering higher quality in a more sustainable way was the top priority of the team.  While building a pipeline, automating, developing features are all important factors, the TOP priority of the team is to organize in a way that enables them to deliver higher quality sooner and more sustainably.
### !end-hint


<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

## Procurement Considerations

Recognizing the power of our community, and that the term "community" encompasses the entirety of the DoD is important. To bridge the gap between change agents and early adopters, the organization requires that we share our knowledge, the lessons we have learned, and the intrinsic value of those things with the entire organization. At the end of the day, our mission doesn’t care which SAE, PEO, Program, Program Manager, or Software Factory delivered the product - they care about having access to mission-ready tools  to execute the missions they serve.  

### !callout-success
## TEAM
Remember- the DoD is **not** a single program or service, it's **composed of many, that make up the whole**.  Finding ways to reduce duplication of common services and partners will ensure that we leap over the chasm and succeed together!

<span style="font-family: script; font-size:2em;">Together Everyone Achieves More (T.E.A.M)</span>
### !end-callout

Evolving our mentality and approach means realizing everyone starting from scratch is **not scalable**. Ask yourself how you can change the way you collaborate across services, programs, and PEOs today.

Below are the two primary strategies acquisition teams may use when building their DevOps teams. Module 103 will discuss in more detail.

### Goverment-Led Approach

* Government team members (civilian or military) are leading the overall effort, which includes making both business and technical decisions. 
* Government personnel are embedded at all levels of the program from leadership to individual software practitioner teams. 
* Contractors likely will augment the Government team, but they do not have authority to direct resources or commit the Government to decisions. 

### Contractor-Led Approach

* A contractor is on contract with the Government for the delivery of completed software product(s) and/or the integrator for multiple software products. 
* The Government organizes and directs all acquisition activities and provides overarching goals with the contractor leading implementation and day-to-day decisions. 
    * A Government representative should be identified and embedded with the  contractor team and be involved daily or weekly. 
* Overall technology decisions may be driven by the Government, or may be the responsibility of the contractor if directed in the contract. 


### !callout-success
## Key Takeaway
Regardless of the approach (Government-led or Contractor led), **utilize multiple contractors/contracts** as recommended in Federal Acquisition Regulation (FAR) for IT/software systems to the **maximum extent practicable**: [FAR 39.103](https://www.acquisition.gov/far/39.103) (In later lessons we will provide more implementation details)
### !end-callout



<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: checkbox
* id: 3d75862d-b196-4db0-b297-8772b323cc1a
* title: Testing best practices
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

What are best practices when implementing testing to support a DevSecOps initiative?

##### !end-question

##### !options

* Testing is a standalone function of a separate team that runs tests at the end of the sprint.
* Use of automated testing tools
* Shifting test left, incorporating functions and roles to support test from the beginning
* Testing is a standalone activity that cannot occur until the end of development


##### !end-options

##### !answer

* Use of automated testing tools
* Shifting test left, incorporating functions and roles to support test from the beginning

##### !end-answer

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->
<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: paragraph
* id: 0feddda4-9915-4946-974b-acf814386cf5
* title: !Takeaways
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Tell us two (2) important takeaways from this lesson and the prior lesson (An Intro: Incorporating DevSecOps within the DoD) that will change the way you work.

##### !end-question

##### !placeholder


##### !end-placeholder

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

### !callout-success
## Key Takeaways: 
* Be cognizant of our current system and how decisions are made. From that starting point, we can then begin to think about how to apply DevSecOps.
* Don’t forget why software is different - as outlined by Jez Humble:
    * Software is malleable 
    * Software products can be used prior to all features being developed
    * Software can (and should) change over time, and     
    * Significant information is learned when users interact with software--this enables faster feedback and smaller batches. 
    * **To drive this home:** Building a bridge from either side of a river, you get one shot--that is **not** true for software intensive systems. 
* As course instructors, we have defined two groups of people emphasizing the importance of digital foundations throughout all roles and functions:
    * Software acquisition professionals, and
    * Software practitioners.
### !end-callout



## BONUS SECTION: A DevSecOps Organization

Now that you have been introduced to basic DevSecOps competency areas and teams, we have added an **optional** bonus section for those who can't get enough, and/or want to keep learning and stay ahead of the curve!

### Organizing for a DevSecOps Team
Organizations want to implement Agile and DevOps, yet want to avoid changing how they work.

The question has been asked a million times: **How do I organize for DevSecOps?**

The answer may frustrate you: **It depends.**

**Why?**

There is no uniform model for constructing a DevSecOps organization. However, teams should be organized around the business or mission capability, **not** around personnel roles.

The video below discusses optimal ways of organizing a DevSecOps team:

https://www.coursera.org/lecture/devops-culture-and-mindset/organizational-models-in-devops-matrix-full-stack-and-cross-functional-J9C55

><span style="font-family: script; font-size: 1.5em">Change is the law of life and those who look only to the past or present are certain to miss the future.</span>
>
><span style="float:right;font-family: script; font-size: 1.2em">- John F. Kennedy</span>
>
> <span style="clear:both">&nbsp;</span>

<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: multiple-choice
* id: fb43cdb1-12c1-4721-a878-824b222eef39
* title: BONUS CHALLENGE
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Changing organization structure (your org chart) is required for successful implementation of DevSecOps.

##### !end-question

##### !options

* True
* False

##### !end-options

##### !answer

* False

##### !end-answer
### !hint
Changing an organizational structure shouldn't be considered lightly. If a transformation starts with organizational change, it likely won’t yield maximum benefits - ANY organization change should be backed with explanations as to why the change will improve outcomes and value flow to the customer.
### !end-hint


<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

## Resources

These resources are used throughout the lesson and are provided for you to continue learning on your own time. 

* **Books:**
    * [_Accelerate: The Science of DevOps_](https://itrevolution.com/accelerate-book/)
    * [_Team Topologies_](https://teamtopologies.com/book)
