# Technical writing rules and tips

This repository is aimed to explain how to write technical documentation for software projects in the best way.

Technical writing is a writing that helps users solve problems with technologies and technical subject matter. The goal of technical writing is to "get" information from the heads of creators (developers) and "put" it in the heads of users in the way that they can use it.

##### Table of Contents  
[I. The writing process][1]
[II. Writing tips and best practices](#ii.writingtipsandbestpractices)


Examples of technical documents:

* Case studies
* Descriptions
* Emails
* Letters
* Instructions and procedures
* Memos
* Press releases
* Proposals
* Resumes
* Specifications
* Technical reports
* White papers
* Websites


## I. The writing process

1. Plan
   1. Purpose
      1. Requirements (identify what is to be built and if it meets stakeholders’ expectations) 
      2. Design / architecture  (describe how system will be constructed, critical components and connections) 
      3. Code / documentation (helps developers complete their tasks and understand what others do)
      4. Test plans / test cases (approach)
      5. End-user (enable task-completion, provide support)
        * e.g.:
         * Persuade readers to think or act in a certain way (e. g. proposal for funding)
         * Enable them to perform a task
         * Help them understand something (how the code work, to use it)
         * Change their attitude

   2. Audience
      * Can be more than one type: divide for primary (target reader, requested it) and secondary (may contact with it but                                                      are not intended readers). Better create separate documents for each.
      * Questions that should be answered at the beginning?
         1. What do they already know?
         2. Why are they reading (getting errors etc.)
         3. What they need to know right now?

   3. Delivery
   
   
2. Research
   * Interview SMEs (Subject Matter Experts)
   * Prepare interview questions
   * Keep them open-ended (e.g. “Please describe how users will interact with feature X”), ask if they have smth to add
   * One question = one feature
   * Tell about main topics before the interview, so they can prepare
   * State goals to a person
   * Review existing documentation
   * Use the software

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

4. Review / Edit  + better ask someone else to do it too
   1. Adjust and reorganize
   2. Editing for style
   3. Incorporate test results
   4. Print out
   5. Cut unnecessary parts
   6. Usability testing - make a user go through the document line-by-line and do stuff, use a live system, observe the process, ask for think-out-louds
   7. Launch
   8. Coordinate with developers for common release with the software
   9. Create a plan for updates



## II. Writing tips and best practices

* Style guides - set of rules for designing documents (also called style sheets), may be used as a framework.

* Universal principles for writing documentation:
 
   * Accuracy
      * Documental - proper coverage of topics with appropriate detail, solves a problem
      * Stylistic - meanings are used correctly and are specific enough
      * Technically correct -  (SME consultation can help)

   * Clarity - ease of understanding
      * Structural
         * Abstracts/Introductions/ 
         * Tables of contents
         * Graphs
         * Headings and titles
      * Stylistic 
         * Be specific (e. g. explain what is “user-friendly”, replace “fast” with “within 2 seconds”)
         * Speak with the active voice instead of passive (not “The app is used”, but “The developer uses the app”)
         * Shorten where possible: e.g. “make an assumption” = “assume”, “is a requirement” = “requires”
      * Contextual
         * State the purpose
         * What precedes this document?
         * How does this document relate to others?


   * Conciseness

      * Use visuals rather than words
      * Remove unnecessary repetitions (e.g. “maximize as much as possible” = “maximize”, “small in size” = “small”)
      * Never use “In other words”, say it well at the first time
      * Active voice (e. g. “Check A for errors” instead of - “A should be checked for errors”)


   * Tone

      * Be conversational - write the way you talk
      * Be personal - show personality, do not have a tone like it is written by a machine
      * Tense - stay consistent, use present / future

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


## III. Layout and design

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/a.png)

   * Web-safe fonts: displayed correctly regardless operating system, use only them!

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/b.png)


   * Courier new font is commonly used for showing code.

   * Reading the text with CAPS takes 10% more time.

   * Make the text copyable (no text on images).



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

   * Create groups - brain creates shapes around objects and perceives them easier. Place the illustations logically (e.g. here the picture should be a part of the solution, not a problem statement).
   
   Bad example:


![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/f.png)

Bad example -> Good example

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/g.png)


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



## IV. How to write requirements

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/u.png)

Percentage of successful / challenged (completed with extra time/money/sources) / failed software projects:

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/v.png)

Reasons for challenging / failure:

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/w.png)
![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/x.png)


* How requirements should be?

   * Unitary - one requirement at a time
   * Requirement should be complete - no missing information, everything is in one place
   * Consistent - doesn’t contradict with any other requirements
   * Atomic:
      e. g. not “Validate Fields A and B”, but: 
      1) Validate field A 
      2) Validate field B
   * Traceability - every requirement can be traced back to some need of the stakeholders and documented
   * Current - it shouldn’t be made obsolete by the passage of time
   * Unambiguous - can be interpreted only in one way, express facts.
   * Specify level of importance - high, medium, low (some requirements are not necessary, but just good to have).
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


* Types of requirements:

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z8.png)

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z9.png)

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z10.png)

![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z11.png)


![alt text](https://github.com/YaKsenia/technical_writing_tips/blob/master/images/z12.png)

* UML - unified modelling language - diagrams

* Software requirements specification (SRS) - description of the software system to be developed.

## V. References

This article was written based on the online course ["Technical Writing: Documentation on Software Projects" on Pluralsight](
https://www.pluralsight.com/courses/technical-writing-software-documentation) by Amber Israelsen. 


