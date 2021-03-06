# Technical writing rules and tips

This repository is aimed to explain how to write technical documentation for software projects in the best way.

Technical writing is a writing that helps users solve problems with technologies and technical subject matter. The goal of technical writing is to "get" information from the heads of creators (developers) and "put" it in the heads of users in the way that they can use it.

##### Table of Contents  

[I. The writing process](#thewritingprocess)

1. [Plan](#plan)
2. [Research](#research)
3. [Write](#write)
4. [Review](#review)

[II. Writing tips and best practices](#writingtipsandbestpractices)
* [Accuracy](#accuracy)
* [Clarity](#clarity)
* [Conciseness](#conciseness)
* [Tone](#tone)
* [Grammar](#grammar)

[III. Layout and design](#layout)

* [Design principles](#principles)
* [Visual hierarchy](#hierarchy)
* [Page design elements](#elements)

[IV. How to write requirements](#requirements)

* [How requirements should be?](#how)
* [Types of requirements](#types)
* [How to write a good requirement?](#write_requirement)

[V. How to write software architecture document](#architecture)

[VI. Source code document](#source_code)

[VII. Samples and templates for software documentation](#samples)

[VIII. Quality assurance documentation](#quality)

[IX. References](#references)


<a name="thewritingprocess"></a>
## I. The writing process

<a name="plan"></a>
1. Plan
   1. Purpose
      1. Requirements (identify what is to be built and if it meets stakeholders’ expectations) 
      2. Design / architecture  (describe how system will be constructed, critical components and connections) 
      3. Code / documentation (help developers complete their tasks and understand what others do)
      4. Test plans / test cases (describe the approach to be used)
      5. End-user (enable task-completion, provide support)
        * e.g.:
            * Persuade readers to think or act in a certain way (e. g. proposal for funding)
            * Enable them to perform a task
            * Help them understand something (how the code work, to use it)
            * Change their attitude

   2. Audience
      * Can be more than one type: divide for primary (target reader who requested it) and secondary (the one who may be in contact with it but is not an intended reader). Better create separate documents for each.
      * Questions that should be answered at the beginning:
         1. What do they already know?
         2. Why are they reading (e. g. they are getting errors and look for ways to fix them etc.)
         3. What do they need to know right now?

   3. Delivery
   
<a name="research"></a>
2. Research
   * Interview SMEs (Subject Matter Experts)
   * Prepare interview questions
   * Keep them open-ended (e.g. “Please describe how users will interact with feature X”), ask if they have smth to add
   * One question = one feature
   * Tell about main topics before the interview, so they can prepare
   * State goals to a person
   * Review existing documentation
   * Use the software

<a name="write"></a>
3. Write
   1. Organize your content and ideas (e.g. chronological, or simple to complex, or specific to general etc.)
   2. Write the first draft
   3. Review and revise: 
      * Does the document fulfill original purpose?
      * Do you need to add something?
      * To remove something?
      * What questions can the reader have?
      * Is the writing easy to understand?
      * Structure
      
<a name="review"></a>
4. Review / Edit + better ask someone else to do it, too
   1. Adjust and reorganize
   2. Editing for style
   3. Incorporate test results
   4. Print out
   5. Cut unnecessary parts
   6. Usability testing - make a user go through the document line-by-line and do stuff, use a live system, observe the process, ask for think-out-louds
   7. Launch
   8. Coordinate with developers for common release with the software
   9. Create a plan for updates


<a name="writingtipsandbestpractices"></a>
## II. Writing tips and best practices

* Style guides - set of rules for designing documents (also called "style sheets"), may be used as a framework.

* Universal principles for writing documentation:
 
   <a name="accuracy"></a>
   * Accuracy
      * Documental - proper coverage of topics with appropriate detail, should solve a problem
      * Stylistic - meanings are used correctly and are specific enough
      * Technically correct -  SME consultation can help with it

   <a name="clarity"></a>
   * Clarity - ease of understanding
      * Structural
         * Abstracts / Introductions
         * Tables of contents
         * Graphs
         * Headings and titles
      * Stylistic 
         * Be specific (e. g. explain what is “user-friendly”, replace “fast” with “within 2 seconds”)
         * Speak with active voice instead of passive (not “The app is used”, but “A developer uses the app”)
         * Shorten where possible: e.g. “make an assumption” = “assume”, “is a requirement” = “requires”
      * Contextual
         * State the purpose
         * What precedes this document?
         * How does this document relate to others?


   <a name="conciseness"></a>
   * Conciseness

      * Use visuals rather than words
      * Remove unnecessary repetitions (e.g. “maximize as much as possible” = “maximize”, “small in size” = “small”)
      * Never use “In other words”, say it well at the first time
      * Active voice (e. g. “Check A for errors” instead of - “A should be checked for errors”)


   <a name="tone"></a>
   * Tone

      * Be conversational - write the way you talk
      * Be personal - show personality, do not have a tone like it is written by a machine
      * Tense - stay consistent, use present / future

   <a name="grammar"></a>
   * Grammar

      * The most misused words:
         * their / there / they’re
         * its / it’s
         * set up / setup (verb - noun)
         * back up / backup 
         * log in / login
         * i.e. (that is, specifically) / e.g.
         * warning (about smth which can injure of kill a person) / caution (about smth which can cause damage to equipment or loss of data) / note (important, but nothing bad will happen if the user will not read it)
         * backward, toward, forward - no ‘s’ at the end
         * double-click, right-click - always hyphenated
         * website / web site - depends on style guide
         * email / e-mail - same

   * Additional resources:

      * Stunk, White. Elements of style
      * Alred, Brusaw, Oliu. Handbook of Technical writing
      * Hacker, Sommers. A pocket style manual

<a name="layout"></a>
## III. Layout and design

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/a.png)

   * Web-safe fonts: displayed correctly regardless operating system, use only them!

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/b.png)


   * "Courier new" font is commonly used for showing code.

   * Don't use CAPS. Reading the text with CAPS takes 10% more time.

   * Make the text copyable (no text on images).


<a name="principles"></a>
###### Design principles:

* Alignment - placement of the elements along the common rows and columns, or their bodies along a common center.

   * Bad example -> Good example:

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/c.png)

   * Bad example:

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/d.png)


   * Good example:


![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/e.png)



* Proximity

   * Elements which are placed close to each other are perceived more related than the elements which are far apart.

   * Create groups - brain creates shapes around objects and perceives them easier.
   
   Bad example:


![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/f.png)

   * Place the illustations logically (e.g. here the picture should be a part of the solution, not a problem statement). 
   Bad example -> Good example

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/g.png)


<a name="hierarchy"></a>

* Visual hierarchy - create a visual contrast to help users understand what’s important.

   * 3 ways to show contrast:

      1. Color

         * Bad example:

         ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/h.png)


         * Good example:
         
         ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/i.png)


         * Bad:

         ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/j.png)

         * Good:
         
         ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/k.png)



         * Add color to headings:


         ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/l.png)


      2. Shape

         ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/m.png)
         ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/n.png)

         * Before/after adding contrast:
         
         ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/o.png)


         * Size
         
         ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/p.png)
         ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/q.png)





      3. Whitespace - the more white space is around the element, the more important it seems to the reader.


![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/r.png)

<a name="elements"></a>
###### Page design elements

* Table of contents - allows readers to locate information in the document easily
* Place headings and subheadings in the order how they appear in the document
* Make revision history: who made which changes to the document and when
* Headers and footers - page number, the name of section/subsection, date of the document, document path, copyright

* Lists & bullet points: 
   * Include only a piece of information per bullet point, not an entire paragraph
   * Start each bullet in the same way: e.g. a verb or a noun.
   * Capitalize the first word of each bullet
   * Use numbers to show sequence (but use bullets if sequence doesn’t matter)
   * Make specific numbers in sequences for different headings:
 
 ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/s.png)

  
* Captions (descriptions of graphs/tables under them):
   * Specify Figure number
   * Specify the fact which is shown in the graph to help the reader catch it quickly (e. g. “Profit of ABC dropped in 2017”)
   * The caption should be to the left down side of the figure, not in the center down.
   
* Glossary - end of document

* Visuals
   * Screenshots
   ![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/t.png)

   * Underline an important part
   * Icons/symbols - used to highlight, should be simple and easily recognized
   * Tables
   * Line graphs - show trends
   * Bar/column graph - comparison of values
   * Pie chart - show percentage
   * Flow charts - sequence (may be with icons)

<a name="requirements"></a>

## IV. How to write requirements

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/u.png)

Percentage of successful / challenged (completed with extra time/money/sources) / failed software projects:

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/v.png)

Reasons for challenging / failure:

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/w.png)
![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/x.png)


<a name="how"></a>

* How requirements should be?

   * Unitary - one requirement at a time
   * Complete - no missing information, everything is in one place
   * Consistent - doesn’t contradict with any other requirement
   * Atomic:
      e. g. not “Validate Fields A and B”, but: 
      1) Validate field A 
      2) Validate field B
   * Traceable - every requirement can be traced back to some need of the stakeholders and documented
   * Current - it shouldn’t be made obsolete by the passage of time
   * Unambiguous - can be interpreted only in one way, express facts.
   * With specified level of importance - high, medium, low (some requirements are not necessary, but just good to have).
   * Verifiable - can be determined by inspection, demonstration or analysis.

* Two different perspectives for requirements:

   1. User’s perspective
      * Should be written as:
         * User type (The [user class or actor name])
         * Result type (Shall be able to [do something])
         * Object (To [something])
         * Qualifier (response time goal or quality objective) - e. g. “in two clicks”
      
2. System’s perspective
      * Conditions (“When [some conditions are met]”)
      * Result (“the system [shall do something]”)
      * Qualifier (response time goal or quality objective)

* Levels of detail:
   * Use cases - high
   * Traditional (text-based) - medium
   * User stories - low

* Requirement types:
   * Business
   * User (Stakeholder)
   * Functional
   * Non-functional
   * Interface
   
<a name="write_requirement"></a>

* How to write a good requirement?
   * Use terms consistently (not “notification” in one part of the text and “alert” - in the other)
   * Define terms in a glossary
   * Use an active voice
   * Be careful of boundary values (“less than” is different from “less than or equal to”)
   * Avoid negation:
      * Bad example - Users without an account cannot log in to the system
      * Good example - Only users with an account can log in to the system

   * Don’t give names to components of a future system
   * Don’t speculate (never say "usually", "often", "typically")
   * Don’t express possibilities ("can", "probably" etc.)

<a name="types"></a>

* Types of requirements

   * User story - one or more sentence in everyday or a business language describing what a user needs to do:
E. g. - As a <type of user> I want <some goal> for <some reason>
   
![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/y.png)
![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z.png)


   * Use cases (disadvantage - unlikely to use in agile development)
   
![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z1.png)
![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z2.png)
![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z3.png)
![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z4.png)
![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z5.png)


   * Traditional (text-based) writing style - one or more sentences used to specify high-level functionality for business or stakeholders

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z6.png)

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z7.png)

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z8.png)

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z9.png)

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z10.png)

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z11.png)


![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z12.png)

* UML - unified modelling language - diagrams

* Software requirements specification (SRS) - description of the software system to be developed.


<a name="architecture"></a>

## V. How to write software architecture document

Software architecture design documents include the main architectural decisions. Focus on the most relevant and challenging ones. An effective design and architecture document comprises the following information sections:

* Software design document template. Discuss and form a consensus with stakeholders regarding what needs to be covered in the architecture design document before it has been created and use a defined template to map architectural solutions.

* Architecture & Design Principles. Underline the guiding architecture and design principles with which you will engineer the product. For instance, if you plan to structure your solution using microservices architecture, don’t forget to specifically mention this.

* User Story description. Connect user stories with associated business processes and related scenarios. Try to avoid technical details in this section.

* Solution details. Describe the contemplated solution by listing planned services, modules, components, and their importance.

* Diagrammatic representation of the solution. Identify the diagrams that need to be created to help understand and communicate the structure and design principles.

<a name="source_code"></a> 

## VI. Source code document

A source code document is a technical section that explains how the code works. While it’s not necessary, the aspects that have the greatest potential to confuse should be covered. The main users of the source code documents are software engineers.

Source code documents may include but are not limited to the following details:

 * HTML generation framework and other frameworks applied
 * Type of data binding
 * Design pattern with examples (e.g. model-view-controller)
 * Security measures
 * Other patterns and principles

Try to keep the document simple by making short sections for each element and supporting them with brief descriptions.

<a name="samples"></a>

## VII. Samples and templates for software documentation

Here are sources of documentation templates:

* [ReadTheDocs](https://software-documentation-template.readthedocs.io/en/latest/readme.html) is an all-in-one template made with ReadTheDocs platform, providing instructions on writing each type of document you may need, from architecture and UML diagrams to user manuals.

* [ReadySET](http://readyset.tigris.org/nonav/templates/frameset.html) is a large library of software documentation templates in HTML that include planning documents, architecture, design, requirements, testing, and many more.


<a name="quality"></a>

## VII. Quality assurance documentation

There are different types of testing documents in agile. The most common ones are:

 * Quality management plan. A quality management plan is an analog of a requirement document dedicated to testing. This document sets the required standard for product quality and describes the methods to achieve this level. The plan helps to schedule QA tasks and manage testing activity for product managers, but, it is mainly used for large-scale projects.
 
 * Test strategy. A test strategy is a document that describes the software testing approach to achieve testing objectives. This document includes information about team structure and resource needs along with what should be prioritized during testing. A test strategy is usually static as the strategy is defined for the entire development scope.
 
 * Test plan. A test plan usually consists of one or two pages and describes what should be tested at a given moment. This document should contain:
   * The list of features to be tested
   * Testing methods
   * Timeframes
   * Roles and responsibilities (e.g. unit tests may be performed either by the QA team or by engineers)
   
 * Test case specifications. A test case specifications document is a set of detailed actions to verify each feature or functionality of a product. Usually, a QA team writes a separate specifications document for each product unit. Test case specifications are based on the approach outlined in the test plan. A good practice is to simplify specifications description and avoid test case repetitions.

 * Test checklists. Test checklist is a list of tests that should be run at a particular time. It represents what tests are completed and how many have failed. All points in the test checklists should be defined correctly. Try to group test points in the checklists. This approach will help you keep track of them during your work and not lose any. If it helps testers to check the app correctly, you can add comments to your points on the list.


<a name="references"></a>

## IX. References

This article was written based on:
* The online course ["Technical Writing: Documentation on Software Projects" on Pluralsight](
https://www.pluralsight.com/courses/technical-writing-software-documentation) by Amber Israelsen
* The article ["Technical Documentation in Software Development: Types, Best Practices, and Tools"](https://www.altexsoft.com/blog/business/technical-documentation-in-software-development-types-best-practices-and-tools/)


