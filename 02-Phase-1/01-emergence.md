# The Emergence and Origin Story of DevOps and Applicability 

## Learning Objectives

By the end of this lesson you will be able to:
* Define in greater detail the term ‘DevOps’
* Explain the evolution and alignment of Agile and DevOps
* Understand how DevOps has improved software delivery
* Recognize how DevOps and DoD Acquisitions integrate

## Lesson Content

### !callout-info

## A Note About This Lesson
We are extensively discussing the definition of DevOps to provide two key items:

* A common definition of DevOps to start from
* A deeper understanding of DevOps before diving into implementation and DoD examples.

### !end-callout
**Disclaimer:** This section heavily references the article ‘What is DevOps?’ for content and overall structure. For more information please visit the original source at:
 [The Agile Admin: What is DevOps?](https://theagileadmin.com/what-is-devops/)

## DevOps Defined
First, let's define ‘Dev’ and ‘Ops’. Both should be thought of as blanket terms:

* **Dev** is all the people involved in developing a product.
  * _**Some**_ example roles include: product managers, software developers/software engineers, quality assurance, and business managers (acquisition roles and requirements owner in DoD)
* **Ops** is all the people involved in fielding a product in the operational environment.
  * _**Some**_ example roles include: systems engineers, system administrators, release engineers, security professionals, network engineers, and database administrators (DBAs)

## The Evolution and Alignment of Agile and DevOps
### The DevOps Timeline Continued
We are bringing back the timeline, and you may be asking yourself, “Why now?”

**The answer:** these concepts are constantly evolving and building upon one another:

![DevOps Timeline](images/01_devops_timeline.png)

The term DevOps emerges from the combination of two related trends:

1. Adoption of Agile Methodologies in Software Development and (IT/Software) Operations, and
2. Acknowledging the Value of Collaboration

Why focus on DevOps and not DevSecOps?

**The answer:** DevOps and DevSecOps **should not** be thought of as separate methodologies, encompassing only two or
three roles. Rather, _DevSecOps emphasizes the importance of security_, and _**is not**_ an elimination of other roles and functions that enable DevOps (DevSecOps).

###DevOps as a Concept
DevOps is a complex methodology that requires some nuance to fully understand. DevOps is structured on the foundation of these concepts:

**Mindset → Values → Principles → Methods → Practices → Tools**

Here is a graphic version of how those concepts work together:

![Mindset Circles](images/02_learning_org.png)

Referring back to Agile methodologies, you can see there are similarities:

![Mindset to Practices](images/03_mindset_practices.png)

The final addition to this graphic is ‘Tools’, not shown. This is where Agile tools, or tools specifically created and engineered to support Agile, are used to support implementation of Agile practices (i.e. Jira).

It is important to note that unlike the Agile Manifesto and Agile Principles, there is no one agreed-upon list for DevOps. The key difference is DevOps focuses on **working systems** versus working software. Think of this as a further distinction of the environment the working software exists within (i.e. operational environment accessible by users).

As DevOps becomes more widespread, practitioners also leverage new technologies (i.e. tools) as they become available. Common areas that may use commercial and open source tools include:
* Automated testing
* Monitoring
* Virtualization
* Configuration management


<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: checkbox
* id: 2cfef4fd-7cd5-49bf-929a-9feda2119ce0
* title: "Ops"
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Select all roles that are included in the umbrella term ‘ops’:

##### !end-question

##### !options

* System Administrator
* Security Professionals
* Product Managers
* Database Administrator
* Network Engineers
* User Experience(UX)/User Interface (UI) Designers

##### !end-options

##### !answer
* System Administrator
* Security Professionals
* Database Administrator
* Network Engineers

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

* type: ordering
* id: acb2f930-ea89-45b6-864c-96685b1ac648
* title: Digital Transformations
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Place the following terms in order from less powerful (but often easy to adopt) to most powerful and drives digital transformations:

##### !end-question

##### !answer

1. Tools
1. Practices
1. Principles
1. Values
1. Mindset

##### !end-answer

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

##What is _**NOT**_ DevOps
Now let’s further define DevOps by discussing what it is _**not**_.

###1.    It’s Not NoOps
Automation is a practice of DevOps - that is, to automate predictable, routine, and well-known/understood tasks. But implementing DevOps will not take away your job. What it will take away, are the barriers preventing you from leveraging your talent and critical thinking skills in other areas.

###2.    It’s Not (Just) Tools
DevOps (and Agile) tools are useful, but if you don’t know how or why you are using them, your results will be similar to an untrained pilot attempting to land a plane.

###3.    It’s Not (Just) Culture
Culture is undoubtedly important- but think of culture as a shadow. it is observable, but not controllable. Culture is neither a barrier to change, nor does it encourage change- but it can provide hints to what an organization must learn.

<span style="font-size:.8em">Source: Pflaeging, Niels. Organize for Complexity: How to Get Life Back into Work to Build the High-Performance Organization. BetaCodex Publishing, 2014.</span>

### !callout-info
DevOps consists of multiple levels:

Values → Principles → Methods → Practices → Tools.
### !end-callout

###4.    It’s Not (Just) Dev and Ops
All participants creating a product or system should collaborate from the beginning. This is an umbrella term, meant to represent a collaborative approach.

###5.    It’s Not (Just) a Job Title
Implementation cannot be achieved through rebranding a team as ‘DevOps’ or an individual by changing their job title to ‘DevOps Engineer’.

### !callout-info
Again, DevOps consists of multiple levels:

Values → Principles → Methods → Practices → Tools.
### !end-callout

###6.    It’s Not Everything
Be careful not to water down DevOps in an attempt to apply to a larger context. The intent is to apply DevOps concepts in order to achieve working systems that meet user needs.

##DevOps and DoD Integration

What It Feels Like to Live in a DevOps World
>“Imagine living in a DevOps world, where business managers (acquisition professionals and requirements owners), product owners, Development, Quality Assurance, Operations, Security and Test work together relentlessly to help each other and the overall organization win. They are enabling fast flow of planned work into production (e.g., performing tens, hundreds, or even thousands of code deploys per day), while preserving world-class stability, reliability, availability, and security.
>
>Instead of the upstream Development groups causing chaos for those in the downstream work centers (e.g. QA, Operations, and Security and Test), Development is spending twenty percent of its time helping ensure that work flows smoothly through the entire value stream.”
>
><span style="font-size:.8em">Source: Kim, Gene. Phoenix Project, 5th Anniversary Edition: a Novel about IT, DevOps, and
Helping Your Business Win. IT Revolution Press, 2018.</span>

Further key themes:
* **Fast feedback loops** - Established to prevent problematic code from going into operations (production)
* **Automated understood routine, predictable tasks** (e.g. tests)
* **Value placed on Team** - everyone values each other’s time and contributions and dedicated to putting lessons learned to practice
* **Hypothesis-Driven Culture** -- taking no assumptions for granted and doing nothing without measuring
* **Routine** - Performing code deployments becomes boring, without most people even noticing

Don’t forget about the Cloud, environments, and the technology we discussed in Release 1. These ‘tools’ are critical enablers for many DevOps initiatives.

<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: paragraph
* id: c8f655bd-5f7c-45ed-a5c2-6691b6a760c7
* title: Acquisitions Integration into DevOps
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question
DevOps should not be interpreted as everyone must be involved during all parts of the workflow. What are some ways that acquisitions teams can integrate and work with others in DevOps roles?

##### !end-question

##### !placeholder

Think about articulating decisions and information flow that should involve acquisition professionals, and why their involvement brings value.

##### !end-placeholder

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !explanation
* Feedback on current team requirements (additional services and products)
* A frequent check-in to discuss syncing of backlogs across all roles (weekly or biweekly)
* Scheduled feedback on existing contract status (funding and performance)

### !end-explanation

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

###DoD Acquisitions and Contracting Applications

A hallmark of DevOps is everyone within the value stream working together to achieve a common goal. Below we define DevOps (DevSecOps) in the DoD context.

The Program Management Office (PMO) _**is PART OF**_ the value stream.
* **Dev**: A PMO supports Dev as part of the overall business management team (composed of PMO and requirements owners), ensuring the products delivered support the mission and vision of DoD as outlined in the National Defense Strategy (NDS).
  * Activities performed by PMO in direct support: acquisition strategy, contracting strategy, and contracts awarded
* **Ops**: A PMO supports Ops as through implementation of acquisition and contracting strategies. A PMO is responsible for valuable capability delivery, which occurs when made available to users and supported from both a system and monetary perspective
  * Activities performed by PMO in direct support: acquisition strategy, contracting strategy, and contracts awarded

### !callout-warning
_Real Impact_: Contracting actions performed by PMOs have large impacts. In a [2018 GAO report](https://blog.gao.gov/2019/05/28/federal-government-contracting-for-fiscal-year-2018-infographic/), the DoD contracted
$358.3M for goods and services. The FY18 DoD budget was $668M. Our contracts across the DoD represent:

**<center><span style="font-family:script; font-size:3em">54% of DoD Spending</span></center>**

### !end-callout
Contracts are influenced by acquisition strategies, and directly impact and drive results- think about contract incentives, deliverables, and requirements. The importance and critical role of acquisition professionals as part of ‘Dev’ and ‘Ops’ when supporting the development of capabilities our warfighters love cannot be overstated.

<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: paragraph
* id: 1d032f67-c3e9-4ad0-a35f-176aa62239e7
* title: DevOps Strategies
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

What helpful strategies have you implemented that align to the goals of DevOps?

##### !end-question

##### !placeholder



##### !end-placeholder
### !explanation
* The recognition that software is delivered by more than a single team or function and required collaboration and common practices and understanding must extend to multiple teams
* Leveraging technological advancements using software to support automation and easily integrate into multiple environments
* Speed of feedback allows the team to focus on most valuable and impactful features or bugs
* Code deployment becomes a nonevent

### !end-explanation

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

##Final Thoughts

Moving forward, we will use DevSecOps to refer to the values, principles, methods, practices and tools discussed in this lesson. The DoD DevSecOps Reference Design promotes DevSecOps as the preferred implementation and way to reference this way of working. 

##Resources
* ARTICLE: Basis of lesson:  https://theagileadmin.com/what-is-devops/
* BOOK: The Phoenix Project: a Novel about IT, DevOps, and Helping Your Business Win by Gene Kim
* DoD DOCUMENT: https://dodcio.defense.gov/Portals/0/Documents/DoD%20Enterprise%20DevSecOps%20Reference%20Design%20v1.0_Public%20Release.pdf?ver=2019-09-26-115824-583
* VIDEO: Do you prefer videos? Here is a short video that explains the concepts of DevOps: https://www.youtube.com/watch?v=_I94-tJlovg
  * Ignore specific references to products, the overall video re-emphasizes the concepts above
* WEBSITE: https://software.af.mil/

