# DevSecOps Organizations, Competencies and Teams

## Learning Objectives

By the end of this lesson you will be able to:

* Recognize the ability/need for roles to be fluid, because environments are dynamic
* Articulate Software Practitioner roles and teams
* Define how to implement Software Practitioner teams within the Government
* **BONUS:** Have a basic understanding of DevSecOps organization


## Basic DevSecOps Competency Areas

First, let’s create a common language to talk about different roles, teams and organizations executing their mission using DevSecOps.

### !callout-danger

## Disclaimer
Below we list common Software Practitioner roles supporting DevSecOps. However, this **should not** be interpreted as **all** projects needing **all** of these roles every time. As stated above, it depends on a number of factors, like your mission, desired capability, deployment environment, etc.

### !end-callout

### Product Owner:
Product Owners represent the organization, and are responsible for working with the Digital Services Development team. Some responsibilities include prioritizing development of features and functionality, defining acceptance criteria for features, and providing demonstrations and reviews to the organization’s stakeholders. The Product Owner is ultimately accountable for the success of the digital service.

### Product Manager:
Product Managers work closely with the user community to ensure that the requirements reflect the needs and priorities of the user community, and align to mission objectives.

### Software Developers (Engineers) – Front-End:
Front-End Software Developers/Engineers work individually and/or as a team with User Experience Designers (specifically Interaction Designers) to develop front-end functionality and user interfaces supportive of the vision set forth by the organization.

### Software Developers (Engineers) – Back-End:
Back-End Software Developers/Engineers develop the functionality behind the scenes to support data capture, data transfer, and/or other back-end functionality.

### User Experience Designers:
User Experience Designers are individuals who focus on making intuitive design choices relating to visual design, interaction design, and user interface design. User Experience Designers work with Front-End Software Developers to support front-end functionality and a user interface consistent with the vision set forth by the organization.

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

In our old ways of working, teams work within a system where each developer is assigned a set of tasks.

* This creates individual ownership of subsystems within the team, as well as dependency (and therefore risk). What happens if that individual is sick? Quits?
* This way of working is destructive to the quality and value of delivery  
* Nothing concludes quickly
* Little to no collaboration
* No context for someone else’s work, making code review ineffective
* Continuous Integration falls apart

Some mistakes that can be made when standing up a DevSecOps Team is to create features or projects.  This can create issues in the following ways:

* **Feature teams:** Have no ownership of the outcomes
* **Project teams:** Will disband after the project

However, aligning teams to work around business or mission capability enables teams to have ownership and problem solving ability. Software development teams are all about the talent of the team, and their ability to execute the process with maximum efficiency. The goal for that team is to produce working software that meets user, warfighter and mission needs.

The focus in building a DevOps team should be to deliver higher quality sooner in a sustainable and resilient way.  

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

##Procurement Considerations

Recognizing the power of our community, and that the term "community" encompasses the entirety of the DoD is important. To bridge the gap between change agents and early adopters, the organization requires that we share our knowledge, the lessons we have learned, and the intrinsic value of those things with the entire organization. At the end of the day, our mission doesn’t care which SAE, PEO, Program, Program Manager, or Software Factory delivered the product - they care about having access to the tools necessary to execute their mission as they are charged to do.

### !callout-success
## TEAM
Remember- the DoD is not a single program or service, it's **composed of many that make up the whole**.  Finding ways to reduce duplication of common services and partners will ensure that we leap over the chasm and succeed together!

<span style="font-family: script; font-size:2em;">Together Everyone Achieves More (T.E.A.M)</span>
### !end-callout

Evolving our mentality and approach means realizing everyone starting from scratch is **not scalable**. Ask yourself how you can change the way you collaborate across services, programs, and PEOs today.

Below are a few strategies acquisitions teams may use when building their DevOps teams. Release 3 will discuss in more detail.

###DIGITAL SERVICES DEVELOPERS - (ORGANIC)

_When an organization has already built a team_ to support digital service development, they call in seasoned product managers, engineers, and UX/UI designers to develop those services. Personnel involvement is predicated on the scope and type of digital services rendered (architects, security pros, testers, deployment engineers are all possible roles as well).

###DIGITAL SERVICES DEVELOPERS - (Professional Service Vendors)

_When an organization requires outside assistance_, acquisitions teams work in conjunction with private and/or government sector organizations to understand how to evaluate third-party technical competencies, so organization members are paired with vendors who are competent with both building and delivering effective digital services.

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
* title: Takeaways
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

## Reading Resources

https://www.dhs.gov/sites/default/files/publications/2019_sw_it-cast_proceedings_0.pdf
