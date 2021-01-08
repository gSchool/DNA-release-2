# CALMS, the Three Ways of DevSecOps, and the Seven Principles of Wastes

## Learning Objectives

By the end of this lesson you will be able to:

* Describe the CALMS model in DevSecOps
* Understand the Three Ways of DevSecOps
* Understand the Seven Principles and Wastes


## CALMS

#### !callout-info

##Note
To supplement this lesson, we use part of the Agile Software Training
Program available on Coursera via a DAU/Coursera Partnership. **Current** DoD Acquisition
professionals (civilian and military) can gain access and receive certificates for class/curriculum
completion by contacting [Mr. Dave Pearson](mailto:david.pearson@dau.edu). All three videos
referenced in this section are accessible without a Coursera account.

#### !end-callout

In lesson 2.1.1, we explored what is _not_ considered DevSecOps- now let’s put the spotlight on understanding what _is_ considered DevSecOps, and some underlying frameworks employed by many organizations both inside and outside the DoD.

Please click on the video below to learn more.

[DevOps Culture and Mindset: University of California, Davis](https://www.coursera.org/lecture/devops-culture-and-mindset/defining-devops-FauMQ?utm_source=link&utm_medium=in_course_lecture&utm_content=page_share&utm_campaign=overlay_button)

Recall the CALMS framework from the video (shown below):

![CALMS](../__images/03_01_calms.jpg)

Be advised- as we continue this lesson, the intent is not to repeat what’s been covered in the video. Instead, our goal is to provide context for implementing curriculum knowledge within the DoD.

### <span style="font-size: 2em">C.</span> Culture
_DevSecOps isn’t simply a process, or a different approach to development -- **it’s a culture change**._

That being said, unfortunately:

“You **can’t** directly change culture. But you **can** change behavior, and behavior becomes culture”.
<br><span style="float:right">--Lloyd Taylor VP Infrastructure, Ngmoco</span>

<span style="clear:both"></span>
#### !callout-success

## Definition
Behavior
1. 
   1. the manner of conducting oneself
   1. anything that an organism does involving action and response to stimulation
   1. the response of an individual, group, or species to its environment
1. The way in which someone behaves; also, an instance of such behavior
1. The way in which something functions or operates

#### !end-callout

![Culture is the #1 metric](../__images/03_02_culture.png)

Remember- processes, practices, and tools not only influence but also drive behavior.

For example, the DoD creates functional alignments, placing value on individuals and their functional areas. However, successful implementation of DevSecOps requires collaboration and value placed on the **team**. We need to eliminate function-based teams, and create capability- (or product-) based teams.

Development, quality, acquisitions, product management, requirements, design, operations (and any other function necessary to enable the team) need to come together and work collaboratively towards a shared purpose to deliver valuable capability to the user.

DevSecOps isn’t the responsibility of just one person, or one team, or one specific mission...it’s EVERYONE’S!

### <span style="font-size: 2em">A.</span> Automation

_Automation helps eliminate repetitive manual work, yields repeatable processes, and creates reliable systems._

Automation promotes a system benefiting all functional components of a team, not just developers- the ability to build, test, deploy and provision automation is necessary. Teams new to DevSecOps should run all code changes through a gauntlet of automated tests as part of their practice.

Why is this important?

![The network is more powerful than the node](../__images/03_03_automation.png)

Running code changes through automated tests during development catches bugs and security flaws earlier, eliminating rework and increasing the likelihood of continuously delivering working software within operational systems.

This reduces risk!

The DoD provides military forces with support to deter war and ensure our nation’s security. The software and technology you support directly impacts our ability to achieve that mission. Time delay is not solely a project management issue- but, it is a risk in our ability to meet the mission.

How often do mistakes happen when you are writing in a Word document or entering data in an Excel spreadsheet (or if you can code, when you are coding)? Human errors like these are normal- automated tests help reduce risk.

### <span style="font-size: 2em">L.</span> Lean

_A DevSecOps mindset recognizes opportunities for continuous improvement everywhere._

Continuous improvement occurs when entire teams work to optimize the workflow. That is, teams making use of Lean principles to:
* Eliminate waste, and
* Optimize the value stream by
  * Minimizing work in progress (WIP)
  * Making work visible, and
  * Reducing hand-off complexity/wait times
    
![Failure is a prerequisite for learning...](../__images/03_04_lean.png)

The only true failure is not learning from your mistakes. To learn from your mistakes, you must understand the goal (intent), process (bottlenecks), and success metrics or constantly conduct and document experiments.

#### !callout-warning

##Reminder
Keep in mind an important aspect of these experiments is success and failures (stumbling or roadblocks) occur to the ENTIRE team.
#### !end-callout

**Bottlenecks occur in every workflow.** A learning organization cannot be established when threats of blame or finger-pointing (private or public) are practiced. Google (and other groups) have extensively researched this. [Project Aristotle](https://rework.withgoogle.com/print/guides/5721312655835136/) provides more details.

### <span style="font-size: 2em">M.</span> Measurement

_Metrics are key to organizational improvement._

Without data, any attempt at improvement is fruitless, and like any tool, metrics to secure that data must be used correctly to drive needed improvements. Metrics will be explored more extensively later on, but some metrics questions helping inform software delivery and performance include:
* How long did it take to go from development to deployment?
* How often do recurring bugs or failures happen?
* How long does it take to recover after a system failure?
* How many people are using your product right now?
* How many users did you gain / lose this week?

Remember, the goal is not merely moving fast:

![Direction is so much more important that speed, many are going nowhere fast](../__images/03_05_measurement.png)

Direction is informed by data, which allows for speed to VALUE. We need data and metrics to LEARN FAST.

### <span style="font-size: 2em">S.</span> Sharing

_Responsibility and success go a long way toward bridging the Dev and Ops divide._

Development and operations work more efficiently when they are considered **two halves of a whole, not separate entities**. Because both are necessary to improve the resource chain between business goals and deployment, complete cooperation between the two is necessary (#2 Key Takeaway Phoenix Project).

<span style="font-size:.8em">Source: Kim, Gene. Phoenix Project, 5th Anniversary Edition: a Novel about IT, DevOps, and
Helping Your Business Win. IT Revolution Press, 2018.</span>

The DoD has an opportunity to yield significant benefits by undergoing a DevSecOps transformation. However, this is no small task. As discussed in 2.1.1, there is no one set of philosophies that comprise DevSecOps.

![Every model is wrong, but some are useful](../__images/03_06_sharing.png)

DevSecOps is a blend of practices, cultural philosophies and tools. Breaking down our functional silos will skyrocket the mission value we collectively aim to deliver by increasing trust, faster (but smaller) software releases, and a tight feedback loop within and across DevSecOps teams and the users/mission they serve.

## The Three Ways

[DevOps Principles: The Three Ways - Introducing DevOps Concepts](https://www.coursera.org/lecture/devops-culture-and-mindset/devops-principles-the-three-ways-oVpus)

## The Seven Principles and Wastes

[DevOps Principles: The Seven Principles and Seven Wastes of Lean - Introducing DevOps Concepts](https://www.coursera.org/lecture/devops-culture-and-mindset/devops-principles-the-seven-principles-and-seven-wastes-of-lean-YAy6g)

Now that you know what the Three ways and the Seven Principles and Wastes are, we will address how DevOps can help address each of the following areas of waste:

####1. Partially Done Work
   * **DevSecOps solution**: Work is not ‘done’ until it reaches the hands of the user- this shift in mindset is part of the solution. It also ensures capabilities and team structures are in place enabling people to finish what they’ve started. Reducing dependencies between teams and boosting autonomy within teams is a powerful way to address this.

####2. Extra Unnecessary Features
   * **DevSecOps solution**: An iterative approach to value delivery is fundamental to success in the digital economy. Releasing updates and new features on a ‘little and often’ basis, then making further improvements based on customer feedback as required will ensure product development is closely aligned with actual user needs.

####3. Relearning and Refactoring
   * **DevSecOps solution**: Making work visible is a core tenet of DevSecOps, and one of the most effective ways to reduce relearning waste. Conversations about work become more focused and effective, as do review and approval procedures. [Dominica DeGrandis’ Making Work Visible](https://www.amazon.co.uk/dp/B076BYZ6VN/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1) is a great source of guidance for this.

####4. Handoffs
   * **DevSecOps solution**: Small, multiskilled, product-centric teams are central to DevSecOps ways of working. This eradicates the siloed structure that necessitates multiple handoffs, and fosters better communication and collaboration between the people responsible for different parts of the process.

####5. Delays
   * **DevSecOps solution**: Many organizations have a complex web of interdependencies between different teams and departments. People are reliant on actions or input from others to complete an item of work, so it’s hard to predict – or control – how long any given task will take to complete. Mapping where those dependencies lie, then taking steps to streamline and simplify processes deliver significant improvements here.

####6. Task Switching
   * **DevSecOps solution**: Delays and unplanned work are two of the worst culprits for generating this type of waste. Taking a more sophisticated approach to operations helps here, via developer self-service, automation, reusable templates, and InnerSource models. Check out [this blog](https://www.devopsgroup.com/blog/modern-operations-five-foundational-pillars/) on the topic.

####7. Defects
   * **DevSecOps solution**: With DevSecOps ways of working, a known defect is never passed downstream. This is central to the systems-thinking ethos advocated by DevSecOps pioneers such as Gene Kim. All problems are tackled as they arise, not hidden or passed to others, resulting in lengthy handoffs, delays, and unplanned work.

### How This Applies to Procurement
Strategically acquiring knowledge about how DevSecOps works, especially what it is and what it is not, enables us to develop different acquisitions strategies to better serve the user and mission. If you do not currently have any of these methods employed in your acquisition strategy, consider how you might partner with the vendor to begin adopting DevSecOps methodologies.

## Challenges

<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: multiple-choice
* id: 81132e8c-fbb2-4fba-8f41-8a27496db9f1
* title: Three Ways
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

What are the Three Ways

##### !end-question

##### !options

* The Principles of Flow, The Principles of Feedback, and The Principles of Partially Done Work
* The Principles of Flow, The Principles of Feedback, and The Principles of Continuous Learning
* The Principles of Feedback, The Principles of Defects, and The Principles of Continuous Learning
* The Principles of Flow, The Principles of Feedback and The Principles of Lean

##### !end-options

##### !answer

* The Principles of Flow, The Principles of Feedback, and The Principles of Continuous Learning

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

* type: multiple-choice
* id: 426559fd-e674-4d5f-b63d-78591f4d0663
* title: The Third Way
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

In the 3rd Way, we reward people for failing by introducing faults into the system.

##### !end-question

##### !options

* True
* False

##### !end-options

##### !answer

* True

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

* type: checkbox
* id: 46a87473-581c-46ae-8d01-4b32a22ea0f5
* title: [text, a short question title]
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

What are the Seven Wastes?

##### !end-question

##### !options

* Partially Done Work
* Completely Done work
* Extra/Unnecessary Features
* Relearning and Refactoring
* Technical Debt
* Handoffs
* Delays
* Culture
* Sharing
* Flow
* Task Switching
* Defects
* Multitasking
* Automation
* Lean

##### !end-options

##### !answer

* Partially Done Work
* Extra/Unnecessary Features
* Relearning and Refactoring
* Handoffs
* Delays
* Task Switching
* Defects

##### !end-answer

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

Resources

1. Source: Kim, Gene. Phoenix Project, 5th Anniversary Edition: a Novel about IT, DevOps, and Helping Your Business Win. IT Revolution Press, 2018.
2. [Google re:Work](https://rework.withgoogle.com/print/guides/5721312655835136/) provides more details.
3. Coursera: [DevOps Culture and Mindset: University of California, Davis](https://www.coursera.org/lecture/devops-culture-and-mindset/defining-devops-FauMQ?utm_source=link&utm_medium=in_course_lecture&utm_content=page_share&utm_campaign=overlay_button)