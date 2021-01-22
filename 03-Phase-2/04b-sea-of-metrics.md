# How to Navigate the Sea of Metrics

## Learning Objectives

By the end of this lesson you will be able to:

* Understand strategies to define metrics
* Identify ways metrics can be improved
* Identify ways metrics can be manipulated

Velocity, Change Failure Rate, Source Lines of Code, Lead Time, Deployment Frequency,  Mean Time to Restore, Latency, Traffic, Saturation- is anyone else’s head swimming?

Are you thinking these are additions to what you are already expected to track programmatically, like obligations, expenditures, schedule, risk?

Don’t worry. Our goal is to provide you with strategies to help define your metrics, and to prioritize effectively. As you begin implementing more Agile and DevSecOps practices, the eventual benefit is that these should be easily collected, i.e. automatically collected- however, we understand that you may not be there yet. Furthermore, starting with strategies to define metrics can help you to show progress.


## Adaptation of User Stories

Think of metrics as a sense of purpose. What’s a good way of bringing in strategies that are used in software development? Start with user stories. User stories are a way to frame value, and can be a great tool to support your metrics. A typical user story follow this format where you replace the text in black:

<p style="color:red; text-align: center; font-size:2em;">As a [<span style="color:black;">type of user</span>],<br>* 
I want [<span style="color:black;">a result/goal-state</span>],<br>* 
So that [<span style="color:black;">a business need is satisfied</span>].</p>

This allows us to answer: **who** we are measuring for, **what** we are measuring and what must be done to achieve the goal state, and **why** we are measuring it across various DoD.

This can be used at a feature, product, or portfolio (program) just to name some ways. Using a feature measure (metric) at a portfolio level wouldn’t make sense, nor would a product measure (metric) at portfolio level. 

#### !callout-secondary

## Note

User stories typically have acceptance criteria associated with them.  This allows you to answer the question, ”How do I know when I have met the user's need?”

#### !end-callout

<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: paragraph
* id: 333642a6-3d46-4f7a-8e90-77c8ba6051aa
* title: Process Improvement
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Using the above format, explain how a current process or product currently part of your role could be improved. This is an opportunity to make recommendations for improvements and for us to learn from you!

##### !end-question

##### !placeholder



##### !end-placeholder

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

##Metric Playbooks

#### !callout-warning

## Tory's Caution

Playbooks are quickly emerging in the DoD, and I have personally helped to author some. But keep in mind - playbooks are not a silver bullet. For example, playbooks are used by all major football teams in the NFL. But each playbook is different, because each team has different players and skills - trying to force a team to use a playbook that isn’t within their capacity to use or understand will not be successful. Giving the playbook for the Chicago Bears to the New England Patriots will not be effective, because the team is unable to support itself using the tool provided.

#### !end-callout

So what are practices we can adopt that will improve the usefulness of our playbooks? The following recommendations are an adaptation of tips and frameworks established by Walmart. We believe this format helps to further define specific metrics, is understandable, and clearly defines the behavior the metric is trying to change: [Dojo Consortium - Metrics Definitions](https://dojoconsortium.org/docs/playbooks/metrics/index.html)

Here are some playbook tips from our industry teammates that we believe are worth adopting.

Playbooks should be focused yet easy to reference by the teams using them.  They should be built in a way that not only coaches teams but enables them to improve how they perform an activity. Consider how a playbook addresses a single pain point or practice.

A playbook can follow the following structure/guidelines:

**Structure**
* Definition of what the playbook is trying to accomplish
* Note who the target audience is
* Recommend actionable practices that have been effective

**Guidelines**
* Consider how you address feedback and continue to improve the playbook
* Keep the playbook short enough that it can be consumed quickly.
* Think 5 minute read, not a novel -- Revise to shorten if required.

Deployment Cycle Time is an example from the Dojo Consortium. This is just one example- the rest of the playbooks are included in the bonus section. You may need to tweak the definitions slightly, but our recommendation is to try to stay as consistent with industry. Our assumption is that this will help to minimize misunderstanding when working with our industry partners:


|Development Cycle Time<br>* CD Execution - Throughput|The average time from starting work until released to production.|
|---|---|
|What is the intended behavior?|Reduce the time it takes to deliver refined work to production to mitigate the effects of priorities changing and to improve value delivery.|
|How is it improved?|* Decompose work so it can be delivered in smaller increments and by more team members.<br>* Identify and remove process waste, handoffs, and delays in the construction process.<br>* Improve testing efficiency for more rapid feedback loops.<br>* Automate and standardize the build and deploy pipeline.|
|How is it gamed?|* Move things to “Done” status that are not in production.<br>* Move items directly from “Backlog” to “Done” after deploying to production.<br>* Split work into functional tasks that should be considered part of development (development task, testing task, etc.).|
|Guardrail Metrics|The following metrics could degrade if not tracked with this metric<br>* Quality decreases as quality processes are skipped.<br>* Change Fail Rate increases.|

##Phases of Metrics
We opened this section by listing several software metrics available to you. As previously stated, there is no one-size-fits-all solution, but we want to provide some possible options.

#### !callout-secondary
## NOTE
The following recommendations are made based on our personal experiences, and may not be right for your situation or scenario.
#### !end-callout

### Starting a Digital Transformation:
Recall,
> <span style="font-size:2em;"><strong>Software is made by  people and for  people, so digital talent matters.</strong></span>
>
> <span style="float:right">2019 Software is Never Done by Defense Innovation Board</span>
>
> <span style="clear:both">&nbsp;</span>

**Enabling your Team**. You already have a head start on this one- this recommendation is what inspired this course! Now it’s your turn to ensure your team has the same opportunity. Training your team with either this course or others will be the best launch point.

**Establishing a repeatable path to production**. Books like _[Ahead in the Cloud](https://www.amazon.com/Ahead-Cloud-Practices-Navigating-Enterprise/dp/1981924310)_ provide details for establishing a repeatable path to production (operations) for a few products. This is the embodiment of start small, then establish feedback loops that include your users.

**Preparing for scale**. While that is ongoing, if you are a modernization program, upgrade or even if you have to interface with additional systems start thinking about architecture and data. 

### Scaling a Digital Transformation:

**Documentation and Repeatable Processes**. This is not only vital for your current team, but also enables scaling.

**On-boarding**. Again, this is vital for both technology and additional personnel. Make sure you are able to use the processes or tools that helped scale your initial team, and work quickly to establish ways to enable others that are verified with feedback.

**Incorporating Software Performance Metrics**. The goal is to automate software performance metrics that are appropriate to support tradeoff decisions as required. This can be accomplished in various ways, whether you are implementing the [DevOps Research and Assessment (DORA) Four](https://cloud.google.com/blog/products/devops-sre/using-the-four-keys-to-measure-your-devops-performance), or [Google’s Golden Signals](https://sre.google/sre-book/monitoring-distributed-systems/#xref_monitoring_golden-signals).

As a preview to Release 3 and 4, there are programmatic metrics that help show that you are de-risking your program. Here are some examples:

* **Team Composition**: Utilizing civilians, military, and vendors across teams, coupled with onboarding to help mitigate known movement of personnel
* **FAR 39.103 Modular Contracting**. Modular contracting is intended to reduce program risk and to incentivize contractor performance, while meeting the government's need for timely access to rapidly changing technology. **Agencies should, to the maximum extent practicable, use modular contracting to acquire major systems (see 2.1010) of information technology**, consistent with the agency's information technology architecture. Agencies may also use modular contracting to acquire non-major systems of information technology.
  * When using modular contracting, an acquisition of a system of information technology may be **divided into several smaller acquisition increments** that:
    * Are **easier to manage individually** than one comprehensive acquisition;
    * Address complex information technology objectives incrementally, in order to **enhance the likelihood of achieving workable systems or solutions** for attaining those objectives
    * Provide for delivery, implementation, and testing of workable systems or solutions in discrete increments, each of which **is not dependent on any subsequent increment in order to perform its principal functions**;
    * Provides an opportunity for subsequent increments to take advantage of any evolution in technology or needs that occur during implementation and/or use of earlier increments; and
    * **Reduces risk** of potential adverse consequences on the overall project by isolating and avoiding custom-designed system components.
    

<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: paragraph
* id: 9e76c3a1-0d69-4745-b0d0-1af80c3e48fc
* title: Your Metrics
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

The instructors have provided some of their thoughts on metrics. What are some software performance metrics that you are currently using to demonstrate progress in your organization? Have these metrics changed your decision processes?

##### !end-question

##### !placeholder


##### !end-placeholder

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
* id: 39706441-5677-411e-aa5e-ecf6a394f8ab
* title: Acquisition Metrics
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Now, what are some software **acquisition** metrics that you currently are using, or planning to use in your organization? Have these metrics changed your decision processes?


##### !end-question

##### !placeholder



##### !end-placeholder

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

## Tying Together: Effectiveness, Efficiency, and Health
We are all in this together. The DoD is most effective when it can leverage the capabilities and skills of multiple individual services as one. We say this because although friendly competition can help improve performance - the real competition is our adversaries. Do not let friendly competition become tearing down other organizations starting (or continuing) this journey. We can support this mission by:
* Recognizing teams who are trying new things, and publishing their results with transparency (successful or not).  
* Establish an environment committed to reducing the amount of duplicate work (unless it’s essential for the DoD’s security posture).  We achieve this by learning from our peers, committing to collaboration, and reusing tools and resources wherever possible. This supports interoperability and improves engagements across programs, PEOs, Services and industry.

Finally, we need to become more efficient, more effective, and retain domain expertise to remain competitive. A few ways we can do this are:

###1.    Efficiency
Finding ways to measure efficiency and tracking the cost of changes, including speed and quality of delivery.
* Focusing on efficiency is the driving force for shrinking critical feedback loops and removing waste.
* As we become more efficient, toil is reduced, and it becomes more economical to run product experiments.
* Speed of change is contextual to what is being delivered, but the goal should always be to find ways to obtain feedback more rapidly tomorrow than today.
* If we are satisfied with our feedback loops, we are too slow.
* Comparing efficiencies across programs leads to negative behavior, **disincentivizing collaboration** and _leading to antipatterns_.
###2.    Effectiveness
Improving efficiency is important, but we need to effectively deliver value.
* Delivering slowly is bad enough. It’s worse if we spend years building something, only to discover our customers don't want it.
* We can identify value goals for each product, and adjust our systems to measure accordingly.
* We can measure user, mission, and overall business satisfaction to detect report trends.
* We need to improve, without degrading efficiency.
###3.    Health
If we are efficient and effective but have heroes keeping our systems stable, we cannot sustain improvement.
* We need to set goals around stability, both in our systems and in our teams.
    * **Are teams happy?**
        * If you think this is a weird question to ask - here are some statistics that may sway you: _“In studies by the Queens School of Business and by the Gallup Organization, disengaged workers had 37% higher absenteeism, 49% more accidents, and 60% more errors and defects. In organizations with low employee engagement scores, they experienced 18% lower productivity, 16% lower profitability, 37% lower job growth, and 65% lower share price over time.”_
    * **Do we have high turnover on teams?**
* Ways to measure the health and happiness of teams include:
  * Product Delivery: Happy teams who have product ownership will deliver better products.
  * Needs Met: Mission and business needs being met will have a positive impact.
  * Overall Satisfaction: Are the team/organization/service/employee feeling satisfied overall?

## Resources:
* ARTICLE: Proof that Positive Work Cultures are More Productive https://hbr.org/2015/12/proof-that-positive-work-cultures-are-more-productive
* BOOK: _Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology_ by Nicole Forsgren, Jez Humble and Gene Kim
* BOOK: _Ahead in the Cloud: Best Practices for Navigating the Future of Enterprise IT_ by Stephen Corban
* BOOK: _Lean Analytics: Use Data to Build a Better Startup Faster_ by Alistair Croll & Benjamin Yoskovitz
* BOOK: _The Startup Way_ by Eric Ries
* WEBSITE: https://dojoconsortium.org/docs/playbooks/index.html
* WEBSITE: [Google’s Golden Signals](https://sre.google/sre-book/monitoring-distributed-systems/)

##Bonus Material: Additional Metric Playbooks


|Commit Frequency<br>CI Execution|The average number of times each developer on a team integrates tested, non-breaking code to trunk / master. Healthy CI practice is at least once per day per developer.|
|---|---|
|What is the intended behavior?|Increase the frequency of code integration:<br>* Reduce the size of each change.<br>* Improve code review processes.|
|How is it improved?|* Break down code changes into smaller units to incrementally deliver features.<br>* Use BDD to aid functional breakdown.<br>* Use TDD to design more modular code that can be integrated more frequently.<br>* Make new code reachable only by the tests or flagged off for other environments with feature flags.|
|How is it gamed?|Meaningless changes integrated into the trunk.|
|Guardrail Metrics|The following metrics could degrade if not tracked with this metric:<br>* Quality decreases when testing is skipped.<br>*Development Cycle Time increases due to additional review overhead.|
|Recommended Practices|* Trunk Based Development<br>* Continuous Integration<br>* Feature Flagging|
