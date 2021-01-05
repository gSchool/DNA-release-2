# Part B Checkpoint

### !callout-info
## Information
* This Checkpoint will ask you to apply what you've learned in this section to a (mostly) real acquisitions scenario. **Don't worry -- this is not a punitive assessment.** Your instructor will be assigning a score for your responses, and will give you constructive feedback.  

* You'll first analyze the scenario according to Design Thinking, Lean, and Agile criteria. Then, you'll issue suggestions for how you would move forward in this scenario.  
### !end-callout






## Part 1: Analyze Past Scenario

The DoD supports many different software intensive systems and capabilities. It is critical that we support both systems in operations (weapon systems and embedded software within) as well as business systems that enable overall processes and information sharing.

For this scenario, we are looking at a business system where the software product being designed is a website that interfaces with multiple current systems (legacy) with established contracts and varying levels of data availability.

The capability was identified in Fiscal Year (FY) 17, and the requirements documents and funding was established starting in FY19. The intended user base is across services because the system being developed is supporting the payment system for defense contractors. Because contractors are paid by all services and their unique funding, the back-end data structure must seamlessly pull information from the Army, Air Force, Navy, Marines, and the Space Force. It also needs to be intuitive to Industry contractors (Note: The easier it is for us to pay and work with industry, the better support we’ll be able to receive moving forward from industry).

The Space Force is the lead service for acquisitions and has an established Program Management Office. Due to strenuous schedules, Army, Air Force, Navy, and Marines can only meet with the Space Force on an annual basis where they review the progress toward a plan, but do not have access to the software application (website) because of the different implementation of security within each service. Industry is unable to have any insight of the changes and they have just been notified that a new system will field in FY23.

<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: paragraph
* id: 5a65ebc5-65b3-4560-9821-890188e06e5f
* title: Analysis 1
* topics: Procurement
* points: 3
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

In the three paragraphs above, list at least two problems you see with this program and implementation (consider this from a Design Thinking, Agile, and Lean perspective).

##### !end-question

##### !placeholder

Your responses here

##### !end-placeholder

#### !explanation
Possible correct answers include:
* Out of date requirements. Capability identified in FY17 and requirements document generated in FY19
* Not engaging with industry when researching solution
* Not modular -- single contract
* Software team can’t actually deploy to Prod bc of no access to Operations.
* Not modernizing requirements given the long the long span of the project: 2017, identified the problem, actually gets field in 2023, but reqs doc hasn’t changed since 2017

#### !end-explanation

#### !rubric
0 points - No answer or no correct answer
1 point - Lists one reason
3 points - Lists two reasons

Possible correct answers include:
* Out of date requirements. Capability identified in FY17 and requirements document generated in FY19
* Not engaging with industry when researching solution
* Not modular -- single contract
* Software team can’t actually deploy to Prod bc of no access to Operations.
* Not modernizing requirements given the long the long span of the project: 2017, identified the problem, actually gets field in 2023, but reqs doc hasn’t changed since 2017

#### !end-rubric
<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

The PMO was handed a requirements document and plan to award a single contract in FY20 so they can achieve a Minimum Viable Product (MVP) within 12 months. The Government has identified a Product Owner that is also the Contracting Officer Representative (COR) who will work with the awarded vendor. Prior to the Request for Proposal (RFP) release, the process of contract development was internal to the government. After RFP release, due to the influx of questions from industry, it took over 6 months to award the final contract.  

Once the contract begins, the vendor starts working to meet the MVP goal within 12 months. Due to requirements of an independent government, the vendor is working in small batches and testing internally but cannot access the operational environment. The Government test of all software developed is scheduled to be 15 days prior to MVP goal timeline.

### !challenge

* type: paragraph
* id: af9950d5-0d96-44ed-82a2-7b6f52735898
* title: Analysis 2
* topics: Procurement
* points: 3
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

In the two paragraphs above, list at least two problems you see with this program and implementation (consider this from a Design Thinking, Agile, and Lean perspective).

##### !end-question

##### !placeholder

Your responses here

##### !end-placeholder

#### !explanation
Possible correct answers include:
* Single contract - high risk because dependent on one contractor or one contractor with subcontractors
* Did not leverage industry, process of awarding contract was internal to government
* Contract award delay due to questions from industry - likely a direct cause from lack of industry engagement during requirements generation
* Testing is at end of process. First operational test is scheduled 15 days prior to MVP fielding date
* Resource impacts delayed the Government's ability to support testing

#### !end-explanation
<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

#### !rubric
0 points - No answer or no correct answer
1 point - Lists one reason
3 points - Lists two reasons

Possible correct answers include:
* Single contract - high risk because dependent on one contractor or one contractor with subcontractors
* Did not leverage industry, process of awarding contract was internal to government
* Contract award delay due to questions from industry - likely a direct cause from lack of industry engagement during requirements generation
* Testing is at end of process. First operational test is scheduled 15 days prior to MVP fielding date
* Resource impacts delayed the Government's ability to support testing

#### !end-rubric

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

Mid-way through the contract, the PO learns that 4th Estate will also need to use this solution, in addition to the original 4 services. The team does not conduct additional research or change their plan.

Due to bugs and defects that arise during independent Government testing, the vendor was unable to meet a release of an operationally-accessible MVP. The PMO is now answering many requests from leadership and stakeholders of the viability of the schedule moving forward and capability delivery in FY23.   




### !challenge

* type: paragraph
* id: 203fd36f-f2e7-474d-846f-3ba0d3aef051
* title: Analysis 3
* topics: Procurement
* points: 3
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

In the two paragraphs above, list at least two problems you see with this program and implementation (consider this from a Design Thinking, Agile, and Lean perspective).

##### !end-question

##### !placeholder

Your responses here

##### !end-placeholder

##### !explanation
Possible correct answers include:
* Not engaging with all stakeholders/users.
* Learned something new along the way (4th Estate is an additional service we didn't know about at the beginning) but did not adjust the plan to incorporate new feedback -- continued with the initial plan.
* Learning is not be incorporated, although Government product owner identifies issues no way to incorporate
* Impact of testing at the end. Unable to meet MVP timeline

##### !end-explanation

#### !rubric
0 points - No answer or no correct answer
1 point - Lists one reason
3 points - Lists two reasons

Possible correct answers include:
* Not engaging with all stakeholders/users.
* Learned something new along the way (4th Estate is an additional service we didn't know about at the beginning) but did not adjust the plan to incorporate new feedback -- continued with the initial plan.
* Learning is not be incorporated, although Government product owner identifies issues no way to incorporate
* Impact of testing at the end. Unable to meet MVP timeline

#### !end-rubric
<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

## Part 2: Next Steps
The Requirements Owner contacts the PMO because a security breach has been identified with the current payments system capability. It's now clear that we must provide an alternate solution to payments system by 2023.   

<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: paragraph
* id: 4ce314e5-d792-4e30-a303-a39357963af5
* title: Back on track
* topics: Procurement
* points: 5
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

As the PMO, how would you move forward within this existing contract set the contractor up for a better chance of success? Think especially about changes to process you would suggest to get this project back on track.

##### !end-question

##### !placeholder

Your responses here

##### !end-placeholder

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->


### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->
