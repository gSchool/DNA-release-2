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
      Source: Pflaeging, Niels. Organize for Complexity: How to Get Life Back into Work to Build the High-Performance Organization. BetaCodex Publishing, 2014.
      DevOps consists of multiple levels:

      Values → Principles → Methods → Practices → Tools.

###4.    It’s Not (Just) Dev and Ops
      All participants creating a product or system should collaborate from the beginning. This is an umbrella term, meant to represent a collaborative approach.

###5.    It’s Not (Just) a Job Title
      Implementation cannot be achieved through rebranding a team as ‘DevOps’ or an individual by changing their job title to ‘DevOps Engineer’.

      Again, DevOps consists of multiple levels:

      Values → Principles → Methods → Practices → Tools.

###6.    It’s Not Everything
      Be careful not to water down DevOps in an attempt to apply to a larger context. The intent is to apply DevOps concepts in order to achieve working systems that meet user needs.

##DevOps and DoD Integration
<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: paragraph
* id: c8f655bd-5f7c-45ed-a5c2-6691b6a760c7
* title: [text, a short question title]
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
<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: paragraph
* id: 1d032f67-c3e9-4ad0-a35f-176aa62239e7
* title: [text, a short question title]
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

[markdown, your question]

##### !end-question

##### !placeholder

[text, placeholder text for input field]

##### !end-placeholder

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->
