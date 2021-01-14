# Understanding Technology’s Role

## Learning Objectives
* Understand technology choices are made to realize architectural and design goals/needs
* Define technical debt and understand its needs
* Understand tech stack diversity, how individual technologies need to complement each other, and different stack pros/cons
* Recognize the value of baselining technology choices as late as possible
* Understand the value of abstraction and virtualization
* Investigate alternative tech stack implementations

## Acquisitions + Technology

Before continuing this course, or even this module, we need to talk. Perhaps we should have said something a bit earlier, but we decided that posing and answering this question after talking about technology for a while was the best way to go. Why are we focusing so much on technology?  

You may be thinking, “I have specifically never studied technology before - stop making me study it now!” But, advancements in technology and threats from our adversaries REQUIRE you to understand this world, so we can meet a need.   

>“the thread that runs through all of our programs and all that we do is software...”  HON Ellen Lord, Undersecretary of Defense for Acquisition and Sustainment

In Fiscal Year 2018, the DoD budget was $668B. Based on a GAO report, $358.3B of that was contracted, meaning we are contracting **58%** of our budget. Contracts are created and managed in large part by acquisition professionals. Hopefully this makes clear the impact we as a professional community have. [Federal Government Contracting for Fiscal Year 2018](https://blog.gao.gov/2019/05/28/federal-government-contracting-for-fiscal-year-2018-infographic/)

### !callout-secondary
## Disclaimer
This section may be tech heavy for some. If not, you may just have the makings of becoming a software practitioner! Either way, the information included in this module explains how certain concepts influence your role as a software acquisition professional, and their impact. These lessons will also still be available to you after the course concludes, to serve as a continued guide and information resource.
### !end-callout

## Technology Choices Realize Design and Architecture
In the last module, you learned:
* The paramount importance design and architecture play in successful system implementation
* That capability will be either delivered directly, or by hardware and/or software, and
* How to partition capability delivery to different components, whether hardware or software


This is called design.  

Now, the process shifts to assign technologies to system components, in order to fulfill required capabilities. Teams may have already discovered and/or declared several required capabilities in the design process.  

For example, nearly every software-intensive system needs identity and access management (IdAM) capability. IdAM is exactly what it sounds like - it ensures that individuals accessing the system should be accessing the system by creating unique identities, then managing and limiting access based on those identities. While IdAM systems concepts are an entire lesson on their own, you can start learning more here: [IdAM in a Nutshell – DoD Cyber Exchange](https://public.cyber.mil/idam/idam-in-a-nutshell/).

**How this can apply to acquisitions:** if procuring a system, a secure IdAM will most likely need to be included as part of the system or developed. That is, how can this be incorporated into your contract?    

Other than an IdAM, a plethora of other technologies also need to be decided on.   

Do you need to persist data? You’ll need to decide how to do that. Persisting data also requires security, access, encryption at rest, key management, backup, and resilience strategies.   

Your software needs fast, reliable, and secure access to your data. You’ll need to make a choice of database technologies as well. SQL, NoSQL, in memory, row-based, column-based, etc.?  

So many technical details must all work together to meet your system capability needs and key performance parameters!  

* Don’t sweat the small stuff though- instead, “keep calm and carry on”:
* Capture these needs in a backlog
* Prioritize them
* Assign a few quick analysis of alternatives (AoAs) to your technical staff, and
* Make selections based on your analysis   

Don’t be afraid to make choices and move on! Keep in mind, there is rarely a single optimal technology choice to satisfy a need- many options will usually be “good enough”. When choosing technology, it's worthwhile to remember that Voltaire once said, “Perfect is the enemy of good.” Similarly, Robert Watson-Watt, the developer of Britain's early warning radar in WWII said "Give them the third best to go on with; the second best comes too late, the best never comes."   

For those less comfortable with technology decisions, that’s the benefit of a DevSecOps team- other members are there to support you! With that said, it’s important to provide some insight into the different types of technology tradeoff decisions you and your team might make. Release 3 and 4 will go into more detail.  

Attempting perfection in every choice defers delivery indefinitely. Instead, have a thorough understanding of the choices you make, and be ready to reevaluate them. Then prepare to potentially exchange underlying technology in your design when more effective or modern alternatives emerge, or if you need capability that you don’t currently have available. These recommendations lead us next to our discussion - technical debt.  

## Technical Debt
What exactly is technical debt? Ward Cunningham, one of the original 17 authors of the Agile Manifesto, coined the term. Simply put, technical debt is like credit card interest. Technical debt, like credit card debt, accrues over time. While your project is in development stages, it might seem worthwhile to choose “easy”, over “better, but time consuming”. But just like credit card debt, the more you accumulate, the harder it is to “pay off”, or implement any changes.   

Oftentimes we might make compromises in the technical elegance of an implementation in order to save resources (time and/or money), adding to the balance of technical debt. This is not wrong, is often required for delivery capability within a relevant timeline.   

For a more concrete examples, let’s look at tech debt in two ways:

* **Technical debt in code elegance:** Writing a string of code is like writing a sentence: that’s why we call them coding “languages”. Much like writing a clear and concise paragraph, writing clean, elegant code can sometimes be difficult. Because of that initial difficulty, teams often choose an easier, but often more lengthy and “hard-coded” method of execution. As scenarios change, failures occur because the code was written for specificity, not flexibility. A rule to remember: the more code there is, the more expensive it is to maintain, and the greater the risk for failure.

* **Technical debt in aging products or hardware:** Technology is constantly evolving. A new computer today is soon superseded by next year’s more efficient model, featuring larger data storage, greater processing power, improved graphics, etc. Time also creates vulnerabilities often exploited by hackers. The longer your system is available, the greater the likelihood of hackers attempting breach its security. Just like your personal technology, advantages exist with upgrading an outdated system that is increasingly unreliable or prone to hacking.

This leads us to two critical aspects of technical debt that you need to be mindful of:

### !callout-warning
## 1. It’s not always possible to know technical debt has been created.  
System failures are replete with examples of unrecognized technical debt. However, mindfulness when making design and implementation choices can help projects recognize when technical debt is accruing, and minimize the surprise of technical debt.
### !end-callout

### !callout-warning
## 2. Make paying down technical debt a part of your overall strategy.
Budgeting and planning for paying off technical debt is essential. Dedicating a percentage of each sprint, or allocating a specific sprint for paying off technical debt works best. An example cadence is every 5th or 10th sprint, freeze all new feature development and instead focus on paying down technical debt. Remember: technical debt isn’t about fixing implementation errors or defects- instead, resolving technical debt is more about finding and mitigating choices made in favor of speed or completion over elegance. Implementation errors or defects prevent capability delivery, and are best solved as soon as they are discovered.
### !end-callout

For an in-depth look at technical debt, a good place to start is here [TechnicalDebt](https://martinfowler.com/bliki/TechnicalDebt.html#:~:text=Technical%20Debt%20is%20a%20metaphor,interest%20paid%20on%20the%20debt.) or here [Technical Debt: The Ultimate Guide – BMC Blogs](https://www.bmc.com/blogs/technical-debt-explained-the-complete-guide-to-understanding-and-dealing-with-technical-debt/).  

**How this can apply to acquisitions:** As shown above, technical debt should be baked into all acquisition and contracting strategies (tech refresh is common in every Work Breakdown Structure). Use the information above to continue to defend this funding.

## Technology Stacks and Development Pipelines Defined
First, we have to define and understand the differences between a technology stack (commonly known as a “tech stack”) and a development pipeline. Both are necessary and interrelated. First let’s discuss tech stacks.   

### Tech Stacks Defined
To get a better understanding of what a tech stack entails, take a look at this diagram (this should look pretty familiar). See how various technologies are “stacked”, creating a foundation of sorts?

**A tech stack is the collection of tools you choose to build a fully-operational system or application**

In addition to making technology choices for each layer, teams will need to decide if they intend to manage each of those tools, or if they want to outsource to another entity or vendor who offer management “as a service”. Outsourcing is common, but may require accepting whatever the vendor allows. For example, vendors like Oracle, Microsoft Azure, Google Cloud, and Amazon Web Services (AWS) allow some choices at each layer, but choices made at one layer may limit your options at other layers. Likewise, it’s important to consider vendor lock-in when making technology choices at each layer. Many vendors support open standards in their offerings, but also encourage teams to use their proprietary offerings or extensions instead. Making this choice may gain the team greater capability or ease of implementation, but can accrue technical debt later if you decide to change vendors later.  

These are not necessarily bad choices. However, all of these choices must be documented and remembered for future reference. Even when choosing open-standards based components, technology and/or vendor lock-in may still occur. Frankly, every choice results in some kind of lock-in, and the best way to approach it is to acknowledge that fact and plan for an inevitable future where that choice must be reevaluated. Chasing technology is a never ending pursuit.   

**How this can apply to acquisitions:** Ensure that your contracts include well-documented use of proprietary software and data storage. Furthermore, require documented, standardized (if applicable) Application Programming Interfaces (APIs) to minimize long-term lock-in. Adhering to these two rules will help your program be better enabled when moving between vendors.   

Another thing to remember: Teams must choose supporting technology products for multiple tech stacks to run:
* Development environments
* Testing environments
* Simulation environments
* Integration & test environments
* Staging environments, and
* Production environments   

Ideally, teams would choose a common solution for all six environments, but this is not always possible.   

For example, if your system is going to be a Cloud-accessed ERP (Enterprise Resource Planning system (e.g. personnel, supply, financial management), a common tech stack would make a great deal of sense for all environments.   

If however, you’re developing software for an integrated hardware and software embedded weapon system, hosting your development, unit testing, and simulation environments in an appropriately secured cloud can still make a lot of sense. **However, your integration & test, staging, and production (operational) environments will need to all be the same.** That is, the integration and test environment is probably a hardware in the loop integration lab, staging would be a developmental or operational test platform (e.g. “yellow wire aircraft”), and your production environment is the actual weapon system hardware.  

**How this can apply to acquisitions:** If you are relying on a vendor to support capability development ensure your contracts have the text in bold as a requirement, this is referred to as platform drift and can wreak havoc on the ability to frequently deliver capability to operations.  Before moving onto the development pipeline, let’s discuss an example of the possible choices for technology solutions at each layer in the above generic computing stack. From bottom up:  
* Networking is first. Choices you have here are base connectivity using things like MILSTD-1553, Ethernet, or Fiber Channel; copper wiring vs. fiber optics vs. wireless, etc.
* Moving up a bit, but still in networking, you’ll have to decide on protocols like IP, and TCP/UDP/Multicast, etc. Your most important decision at this layer may be related to your system. How much bandwidth do you need, what are your latency requirements, and perhaps most importantly, how stringent are your timing requirements (i.e. is your system a safety critical real time system)?
* Next up the stack is storage. Can you put everything in the cloud? Should you leverage the widely adopted, but AWS specific S3 Storage API?   

Remember with both networking and storage, you’ll probably want to encrypt everything in transit and at rest, respectively. Uh-oh, now which encryption protocols should I use? How do I do key management? So much complexity.  

Considering servers, what vendor do I go with (Dell, HP, etc.), what chip architecture (x86, ARM, etc.). Can I make a choice that doesn’t matter? There are choices and considerations like this at every level, and the further up the stack you move, the more the technologies are pure software, and the more choices you have. When you cross the threshold to virtualization and operating systems, all the technology choices are software. For a taste of the complexity here, check out the Cloud Native Computing Foundation’s (CNCF) technology landscape here: [CNCF Cloud Native Interactive Landscape](https://landscape.cncf.io/). If you didn’t take a few minutes to click that link and investigate, please do. It is worth getting a sense of the complexity and diversity of technological choices available. Again though, don’t despair. Don’t let the overwhelming amount of choice spiral into paralysis by analysis. Also for those immediately seeing that volume and thinking oh my contracting, the software on the site is available open-source, thus does not require contract actions, security actions yes - but contracting professionals can take a sigh of relief on at least this part.   

There are few bad choices available, especially amongst those that are certified to meet their claimed capabilities by a non-profit, industry association like the CNCF. The challenge is finding the right combination of technologies that can meet the needs of your program and deliver the right capabilities. Also, the right combination that works properly in combination. Not all of the “lego blocks” are compatible.  

**How this can apply to acquisitions:** These technical decisions have to be made and frequently evaluated and updated. Whether the government is leading these decisions or partnering with a vendor or solely relying on a vendor or anywhere in between the contracts need to be flexible to allow for the technical decisions to change. The types of decisions that need to be made listed above may be a useful launching pad for organization of your contract(s).   

<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: checkbox
* id: 40c07558-eef5-4232-938e-3d95bbd68afc
* title: [text, a short question title]
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

As acquisitions, when thinking through choices that are made with technical design and architecture, technical debt and tech stack, the following are applicable:

##### !end-question

##### !options

* [Option 1]
* [Option 2]
* [Option 3, etc]

##### !end-options

##### !answer

* [Option 2]
* [Option 3 (the correct answer set)]

##### !end-answer

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->
