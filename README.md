# Research-Software-Vulnerabilities

### Table of Contents

[1] Software Vulnerabilities, Prevention and Reduction Methods: Assessment (Secondary Research)

[2] Primary Research Vulnerabilities; formulation, Comparison and Analysis; Conclusion (Primary Research)

## [1] Software Vulnerabilities, Prevention and Reduction Methods: Assessment

Matthew Sides

West Herts College, Watford

Hertfordshire, England

Last Update: 25/02/2018

19/02/2018

Abstract.

Through analysis and deduction, this report explores information based on the topic of software development and vulnerabilities as a whole. Delving further into the notion of vulnerabilities in software development through case study examples. Subsequently, the mitigation of said vulnerabilities is covered, explaining a few methods of preventing or fixing said breaches that may occur, whilst concluding whether the examples in the case studies could have been mitigated and prevented before the situation spiralled out of hand.

Keywords: Software Development, Vulnerabilities - Mitigation, Testing, Detection and Prevention

### Table of Contents

[1] Introduction

[2] Software Development

[3] Vulnerabilities

[4] Case studies

[5] Mitigation of Vulnerabilities

[6] Conclusions

[7] Bibliography

### [1] Introduction

This documentation pertains to the reduction of software vulnerabilities during development, further delving into the subject or topics of what is software development (this includes Software-Development-Life-Cycles | SDLC) and what are vulnerabilities. Consequently, defining and suggesting possible solutions to these vulnerabilities during development, using case studies as illustrations and to portray the risks that herald with not mitigating vulnerabilities effectively. Thereafter concluding with the various ways in which to resolve (fix) and reduce vulnerabilities encountered during the development or finished production of a system. This will include a self-opinionated view, whilst lightly addressing the issues usually encountered when re-defining software development and vulnerabilities to better bring the final point across (use as a reminder). 

Following the conclusion, the recommendations proposed will be applied to an ongoing capstone project.Thus meeting the aims and objectives outlined in the managment documentation: carry out qualitative and quantitave research, create a secondary report,  design a questionnaire, create a primary report, all relating to vulnerabilities in software development. This is and should prevent or lower the probability of vulnerabilities appearing in the application.       

### [2] Software Development

Software development is a meticulous and complex process for developing software and is comprised of numerous stages. In addition to the development and planning process, each stage generally requires documentation to be generated, this is in contrast to what is commonly known or how software development is usually portrayed in media (Jimenez et al. No date). A software development project must at least entail the following stages (though not constrained to the below list), a view supported by Abrahamsson et al. (2002):

I. Client brief

II. Requirement gathering

III. Writing functional specifications

IV. Creating architecture and design documents

V. Implementation and coding

VI. Testing and quality assurance

VII. Software release

VIII. Documentation

IX. Support and new features

#### [2.1] Client Brief

This phase of development relates to the act of acquiring a brief from a perspective client that details or defines the client’s requirements for the build asset. With regards to Vulnerabilities during this phase, it is not conceivable for vulnerabilities to appear due to the lack of development of a physical or theoretical build. However, misinterpretation of the client’s requirements, along with a deficient description of prerequisites or implausible client goals, could lead to vulnerabilities appearing at a later stage of development.

#### [2.2] Requirement Gathering

In my view, requirement gathering is the act of clarifying and ascertaining further detailed information based on the brief already provided by the client, concerning the reason for engagement and said “goals and achievements” that the client expects from the company. This usually includes clients analysing their market requirements and features in demand, to see whether there is an actual need for the software that is being developed within the current market.

A comprehensive understanding of the customers’ needs and compiling features of the proposed software product are the keys to success in this phase. Ur Rehman (2001) agrees, that this phase is fundamentally the foundation or base for a project. Failure to uphold or properly document the client’s requirements could lead to a monumental catastrophe, with either the project failing to come together or the project veering off in a different track to the client’s direction and vision for the project, which in turn will mean that the client’s standards and expectation may not be met.

#### [2.3] Writing Functional Specifications

Following the requirement gathering stage, a review should take place to determine whether the agreed pre-defined or set requirements given by the client are plausible and achievable. Subsequently then it should be determined how and what needs to be implemented to achieve the agreed specifications (Functional specifications are based upon the product requirements documentation put forward), drawing upon a functional specification document, showing the behaviour or functionality of a software product on an abstract level.

The importance of writing functional specifications relates to the creation of a design document, manuals for end-users, functional and architecture documents, being a means to communicate among groups separated by their software development locations. Although during the product development phase amendments to functional specifications may be necessary, keeping in sight new marketing requirements.

#### [2.4] Architecture and Design Documents

The architecture document in effect is formed once all the requirements have been collected and arranged. This document defines different components of the product and how they interact with each other. Further outlining the technologies used to build the product. Whilst the documents are completed and moulded around the project, the (project) team also needs to consider the timelines of the project. This refers to the agreed target date for the product to be on the market.

Thereafter defining architecture, software components and their interfaces, the next phase of development is the creation of a design document. In the architecture document, a component is defined and stated to provide certain functionality. Whereas during the generation of the design document (stage), you have to define what is in the component.

Although the design document and architecture document could be viewed or merged into one individual document, thus making it easier to navigate and locate information based on the project and formulate all the information on a component in one space rather than separating the information. Hence while the architecture and design can be seen as two separate levels, the design document is essentially just elaborating on the architecture level, adding a miniscule amount of information still relating to the component, rather than describing additional new information about the component.

#### [2.5] Implementation and coding

The Implementation and coding phase is initiated when software developers take the design documents and development tools (editors, compilers, debuggers etc.) and start writing the software (Halvorsen 2017).

This is an arduous process and usually the longest phase in the product life cycle. Each developer has to write their own code to a standard, whilst collaborating with other developers to ensure that different components can interoperate with each other. However, this challenging issue may-be bypassed through using or outlining coding standards beforehand. Hence ensuring that the written procedures are followed or abided by, thus enabling the code to be created similar structurally and aesthetically. Furthermore, elaborating on the reason for coding standards during the project or product life cycle, multiple people may have access to modify files, therefore if people are not following the pre-set rules then this would have an impact on the whole compilation and building process. For instance, duplicate definitions of the same variables may cause problems, while similarly, if included files are not written properly you can easily cause the creation of loops.

#### [2.6] Testing and quality assurance

Subsequently, once the implementation and coding stage is completed the next phase in software development is testing. The code is tested to see whether it is functional and works to an acceptable standard whilst meeting and assuring the quality. This might be initiated through managing the product life cycle and verifying that the software meets the defined quality standards or customer agreements (quality assurance). Thereafter, the testing aspect may be instigated during the production phase, this will be concerned with finding errors in the software through breaking the software code into segments for testing. In addition different versions of the application software may be released after collecting feedback  in relation to errors found, this is integral to ensure a more accurate and robust test. In addition, throughout the testing process the ideology behind it is to get a group of testers to observe what the software does and for them to report on its quality, as well as any serious issues that they encounter (under the assumption that the system is flawed and has copious amounts of bugs) (Qatestlab Blog 2005-2010).

#### [2.7] Software release

Before the subsequent marketing and selling of a software product, the product needs to be officially released. This essentially means that the initial software product is created in a repository form (original copy), ensuring that it has been tested for functionality, etc. After releasing the software, development may continue but will not impact or make any subsequent changes to the original version of software already released. A version number is assigned to the software on its release and is changed if the product is updated to demonstrate to the customer that this is an updated version of the original version.

Further development of the software usually continues in the production of a new version that may contain new features of the product. The released software is only updated though if a bug fixed version is required or enhancements have been made.

Usually incremental version numbers are assigned following a scheme of when the next release of the software is sent to market. Though the change in version number depends on whether the new software contains a major change to the previous version or if it contains bug fixes and enhancement to existing functionality. Further releases are also important because they are compiled versions of a particular version of the code, thus they provide a stable set of binaries for testing which could assist in mitigating vulnerabilities (In simpler terms the paragraphs above pertain to the updates and patches in software development after and before release).

#### [2.8] Documentation

Reliable documentation in my opinion, is crucial throughout the software development (life cycle). The presence of documentation should in principle help keep track of all aspects of an application and improve the quality of a software product. Furthermore, it should mainly focus on development, maintenance and knowledge transfer to other developers (Trica 2017). Through the use of this documentation, information is therefore made more easily accessible to any member involved in the production (information all gathered in one point or origin).

Inaccurate documentation is a fundamental source of vulnerabilities. Since a document is the congregation of information usually linking to all stages of a project, failure to update, properly maintain or the inclusion of faulty data can lead to vulnerabilities occurring. An instance of documentation leading to vulnerabilities may be seen during the testing phase. For example, erroneous results could be noted as being fixed despite the problem re-occurring and still existing.

#### [2.9] Support and New Features

This part of the process is usually initiated after the development of the software. This is integral to the cycle as users of the developed software may need support after release, ensuring user satisfaction. The problems encountered during the support process can also help inform and lead to the mitigation of vulnerabilities.

With regards to new features, this may be a factor or prerequisite as developers regularly produce updates to compete with competitors’ products that may have other features. Moreover, better support and new features usually lead to better branding and devotion among user’s, creating or leading to the generation of a referral business.

#### [2.10] Software Development Life Cycles

SDLC (System Development Life Cycle) is a term generally applied to system engineering, information systems and software engineering, to describe the process for planning, creating, testing, and deploying an information system (Wikipedia 2018).

This interconnects with software development, as the different life cycle methodology’s define the procedure’s and show regulated development, portraying the process of the plan, creation and deployment of an information system.

Furthermore, once applied to the development of software, the model acts as a formatted structure, that once followed may bring about advantages or disadvantages depending on the life cycle used. All singular life cycles are useful if applied in the correct situations, therefore it is necessary to analysis the project size, structure, requirements, etc. before choosing a life cycle to be applied.

Examples of software development life cycles consist of: Water Fall method, a sequential non-iterative design model used in software development processes, Prototyping Model; Evolutionary Model etc. Further examples may be extracted from Alan (2017), as there are numerous other cycles not covered in this report.

### [3] Vulnerabilities Topic

The topic of software vulnerabilities pertains to the (weaknesses/flaws) faults that may be exploited within a given system, which in turn may compromise the system itself.

A systems flaws may be exposed to various different types of vulnerabilities. Hence it is crucial that there is an understanding of the diverse array of vulnerabilities, the prevention and detection in order to try to avoid their presence in the final software version of the system and thus reducing the possibility of attacks and costly damages.

The knowledge of any given vulnerability in a system may give an attacker, who is exploiting a specific vulnerability, the ability to reduce a systems information assurance. Thus allowing access to sensitive files and data harmful to the cliental of an organisation (users) or the organisation itself (exploiting a loophole).

Vulnerabilities are essentially the intersection of three elements: a system susceptibility or flaw, attacker access to the flaw, and attacker capability to exploit the flaw (Jimenez et al. no date).

#### [3.1] Examples of Vulnerabilities

Following the discussion of vulnerabilities, as mentioned above under the heading “Vulnerabilities Topic” (3), the section below provides examples of a few of the most common type of vulnerabilities (Jimenez et al. no date):

• Buffer overflow: this usually occurs during fixed length buffers, when some data is going to be written beyond the boundaries of the current defined capacity (hence the use of the word “overflow”).

This could lead to the system malfunctioning since the new data could in principle corrupt the data of other buffers or processes.
In continuation, Buffer overflow could also lead to loss of control and gain (for an attacker) over a system, through the injection of malicious code. Subsequently altering the execution sequence of the program in order to execute the injected code, thus taking control of the system.

•  XSS or cross site scripting: commonly associated or connected to web applications, cross site scripting consists of the injection of code in pages accessed by other users. Through exploitation an attacker may bypass access controls, perform phishing, identity theft or expose connections.

• SQL injection: consists of injecting code with the intension of exploiting the content of a database. This usually happens because the inputs are not handled correctly, an attacker may retrieve or get sensitive information from the database (under attack).

### [4] Case Studies

#### [4.1] Case Study:” goto fail” 2014 Apple

In 2014, Apple fixed a critical security vulnerability that was found to be caused through the use of "cut and paste" during editing. The programmer embedded a duplicate line of code, that caused the software to bypass a block of code that verifies the authenticity of access credentials (connections to secure sites could be spied on). The essence of the problem, though straight forward, led to invalid certificates being quietly accepted as valid (Woody 2015). The vulnerability is described in the National Vulnerability Database, cited by Ducklin (2014) as follows:

•	"Impact: An attacker with a privileged network position may capture or modify data in sessions protected by SSL/TLS" –

•	"Description: Secure Transport failed to validate the authenticity of the connection. This issue was addressed by restoring missing validation steps." -

Researchers learnt of this security flaw in iPhones and iPads, with the confirmation of Apple stating that it was also present in notebook and desktop machines using the Mac OS X operating system.

This vulnerability essentially led to attackers being able to use invalid credentials to gain access to any information on the targeted device, such as email, financial data, and access credentials to other systems and devices.

Further elaborating on the root cause of the problem the duplicated “goto fail” line or block of the code, had an issue with the indentation (segment displayed below) being misleading, since the code did not retain or use curly braces after the “if” statement, the second (duplicate) “goto fail” was therefore always executed.

In context, this meant that vital signature checking code was skipped, so all signatures regardless of authenticity were registered as acceptable. The extraneous (duplicate goto block of code) “goto” caused the function to return 0 (“no error”) when the rest of the checking was skipped, as a result causing invalid certificates to be accepted and thus lead to what is now termed or coined as the "goto fail" incident (Wheeler 2017).

#### [4.2] Case Study: 2017 Equifax Breach

In 2017 Equifax experienced a breach in their systems, resulting in the loss of sensitive data and personal records on 145 million Americans and hundreds of thousands in the UK and Canada. The extent and impact of such a breach, along with the information procured by attackers, could have led to identity theft (impersonation), as seen in similar cases earlier experienced in 2017, known as "IRS FAFSA tool breach" (Qatestlab Blog 2005-2010).

Further delving into how the breach resulted and the vulnerabilities were exploited, it occurred due to the negligence of Equifax failing to find and promptly patch a publicly known vulnerability in Apache Struts (a free, open-source, MVC framework for creating elegant, modern Java web applications.), which was used in its Consumer Dispute Portal. In simple terms, Apache Struts was essentially used to develop their own software or portal that held important user information, however during development and due to a fault in the software used for development (Apache Struts) a vulnerability materialised and went unnoticed.

Moreover, the vulnerability was exploited over 2 months after a fix was made available. In addition, the company did not discover that its systems had been compromised for another 1.5 months. This series of failures demonstrates the significant weaknesses in Equifax’s security program during this time frame (Sethi 2017) (BBC News 2017) (Thomson 2018).

### [5] Mitigating Software Vulnerabilities

Models are a first approach to deal with and understanding vulnerabilities (putting in stronger controls and fleshing out the software better). However, it is necessary to rely on methods or procedures to prevent any risks related to vulnerabilities.

Further ways of mitigation is software inspection. This usually consists of reading or visually inspecting the program code or documents in order to find any defects and correct them early in the development process, though this generally relies on the ability of the person viewing the code (Simmons 2015).

Security testing is also another integral method of finding vulnerabilities in a system, if the vulnerabilities make it all the way to a test environment. Security testing tools and manual techniques may discover these types of issues (Leemon 2015).

In regards to mitigating or preventing software vulnerabilities being exploited, that have occurred during the development of software but went unnoticed, consistent monitoring of applications for unusual activity may halt attacks, though not ideal in this phase, it is critical to have controls in the right place (National Cyber Security Centre 2016).

### [6] Conclusion

In conclusion, based on the information presented above concerning the case studies: in the Apple situation and Equifax state of affairs, during both occurrences the vulnerabilities presented and exploited by the alleged attackers could have been prevented and mitigated if the necessary cautions and procedures were put in place and followed. With the Apple incident, which stemmed from human negligence that could have been prevented if a proper software inspection took place. Similarities can be seen with regards to the Equifax situation, where if the code was manually reviewed, steps could have been put in motion to mitigate said vulnerabilities that appeared.

Through further analysis it may be seen that the response taken by Apple was optimal. Though with regards to Equifax's response not all information regarding the attack was exposed and neither was there consistent monitoring by their operation team, as the exploitation of said vulnerability had occurred 1.5 months before the organisation had found out about the attack, showing that the operation team was not searching for unusual activity, which could have led to the situation devolving before reaching the stage it did. Whilst it also took another 2 months to fix and roll out a patch.

In my opinion, which is supported by research (Anton et al 2003), whilst the situation for both high profile organisations were eventually sorted, with the vulnerabilities found in the software being mitigated. The foremost factor being whether theses vulnerabilities could have been mitigated earlier (during development), rather than only after release. Which based on factual evidence and methodologies used in the prevention of vulnerabilities, points to the decisive answer being certainly.  

### [7] Bibliography

• Abrahamsson, P., Salo, P., Ronkainen, O. and Warsta, J. (2002). Agile Software Development Methods: Review an Analysis. VTT Publications. Available at: https://arxiv.org/ftp/arxiv/papers/1709/1709.08439.pdf [Accessed on 26th Jan 2018]

• Antón, Phillip., Anderson, Robert., Mesic, Richard., Scheiern, Michael. (2003) Finding and Fixing Vulnerabilities in Information Systems. The Vulnerability, Assessment & Mitigation Methodology. Santa Monica: RAND.

• Allen, Paul.G School of Computer Engineering and Science. (2017). Software development lifecycle. Available at: https://courses.cs.washington.edu/courses/cse403/16sp/lectures/lecture-03-software-lifecycle.pdf [Accessed on:26th Jan 2018]

• BBC News. (2017). Equifax data hack affected 694,000 UK customers. Available at: http://www.bbc.co.uk/news/business-41575188 [Accessed on:26th Jan 2018]

• Duckins, Paul. (2014). Anatomy of a “goto fail” – Apple’s SSL bug explained, plus an unofficial patch for OS X! Available at: https://nakedsecurity.sophos.com/2014/02/24/anatomy-of-a-goto-fail-apples-ssl-bug-explained-plus-an-unofficial-patch/[Accessed on: 28th Jan 2017]

• Jimenez,W., Mammar, A., and Cavalli, A., (No date). Software Vulnerabilities, Prevention and Detection Methods: A Review1. Available at: http://www-lor.int-evry.fr/~anna/files/sec-mda09.pdf [Accessed on: 28th Jan 2018]

• Halvorsen, H-P. (2017). Software Development: A Practical Approach! Available at:http://home.hit.no/~hansha/documents/software/software_development/resources/Software Development.pdf [Accessed on: 28th Jan 2018]

• Leemon, Alex. (2015). 5 IT BEST PRACTICES THAT ALSO MITIGATE CYBER SECURITY VULNERABILITIES IN OT. Available at: https://www.cyberark.com/blog/5-it-best-practices-that-also-mitigate-cyber-security-vulnerabilities-in-ot [ Accessed on: 2nd Feb 2018]

• National Cyber Security Centre. (2016). Common cyber attacks: reducing the impact. Available at: https://www.ncsc.gov.uk/content/files/protected_files/guidance_files/common_cyber_attacks_ncsc.pdf {Accessed on: 2nd Feb 2018]

• Qatestlab Blog (2005-2010). Browser Update. Available at: http://blog.qatestlab.com/2011/04/07/what-is-the-difference-between-qa-and-testing/ [Accessed on: 2nd Feb 2018] (blog.qatestlab)Rappeport, A. (2017). Up to 100,000 Taxpayers Compromised in Fafsa Tool Breach, I.R.S. Says. The New York Times. Available at: https://www.nytimes.com/2017/04/06/us/politics/internal-revenue-service-breach-taxpayer-data.html [Accessed on: 3rd Feb 2018]

• Thomson, Iain. (2018). Equifax hack worse than previously thought: Biz kissed goodbye to card expiry dates, tax IDs etc. Available at: https://www.theregister.co.uk/2018/02/13/equifax_security_breach_bad/ [Accessed on: 7th Feb 2018]

• Sethi, Ami. (2017). What can your firm learn from the unfolding Equifax hack? Available at: https://www.synopsys.com/blogs/software-security/security-breach-prevention-tips/ [Accessed on:7th Feb 2018}

• Sethi, Amit. (2017). Top security breaches of 2017 (+2018 cyber security predictions). Available at: https://www.synopsys.com/blogs/software-security/top-data-security-breaches-2017/ [Accessed on: 2nd Feb 2018]

• Simmons, Rod. (2015). 4 Steps to Mitigate 95% of Known Vulnerabilities. Available at: http://www.itprotoday.com/security/4-steps-mitigate-95-known-vulnerabilities [Accessed on: 28th Jan 2018]

• Trica, Alex. (2017). The Importance of Documentation in Software Development. Available at: https://filtered.com/blog/post/project-management/the-importance-of-documentation-in-software-development [Accessed on: 28th Jan 2018]

• Wheeler. David. (2017). The Apple goto fail vulnerability: lessons learned . Available at: https://www.dwheeler.com/essays/apple-goto-fail.html [Accessed on: 5th Feb 2018]

• Wilkipedia (2018). Systems development life cycle. Available at: https://en.wikipedia.org/wiki/Systems_development_life_cycle [Accessed on: 27th Jan 2018]

• Woody, Carol. and Nichols, Bill. (2015). Heartbleed and Goto Fail: Two Case Studies for Predicting Software Assurance Using Quality and Reliability Measures. Available at: https://insights.sei.cmu.edu/sei_blog/2015/04/heartbleed-and-goto-fail-two-case-studies-for-predicting-software-assurance-using-quality-and-reliab.html [Accessed on: 5th Feb 2018]

• Ur Rehman, R., Paul, C. (2002). The Linux Development Platform: Introduction to Software Development Chapter 1. Available at: http://catalogue.pearsoned.co.uk/samplechapter/0130091154.pdf [Accessed on: 6th Feb 2018]

## Primary Research Vulnerabilities; formulation, Comparison and analysis; Conclusion

Matthew Sides

West Herts College, Watford

Hertfordshire, England

Last Update: 25/02/2018

18/04/2018

### Table of Contents

[1] Introduction

[2] Primary Research Plan

[3] Analysis

[4] Conclusion

[5] Self-Reflection

### [1] Introduction

This report has been formed using primary research to explore and provide information on an investigation, to answer the following queries: 

• Are the conglomerate of ICT students and non ICT students aware of the issues of vulnerabilities?

• Are ICT students or non ICT students aware of possible ways to mitigate vulnerabilities?

• Do the two groups of conglomerates (ICT students and non ICT students) know why vulnerabilities may occur in a system?

Furthermore, a comparative analysis of both primary and secondary information is covered on the basis that a conclusive answer is formed. Whilst outlining how the study was compiled and implemented as mentioned in the following document.

The deductions documented or detailed below are based on data that has been, collated, reviewed, modified, deleted and replaced using a technique known as data cleansing. Data cleansing refers to the process of replacing, modifying, or deleting coarse data, emphasising the mitigation of inconsistencies ensuring a consistent data set.

The raw data gathered was collated on an excel spreadsheet. It was then put into a table (using the create table tool) to organise and structure the data, thus making it easier to interpret. Graphs were also created using the data to illustrate the results and enable analysis to check for correlations, trends, comparisons, etc. The information was used to solidify the points brought across in the document below.

However, it is worth noting at this stage that the data indicates that part of the primary data is proving to be inconclusive due to errors in the consultations (answers provided), though this may be used to further prove and answer theoretical questions brought across, whilst also present's the opportunity to evaluate and suggest room for further improvements when designing and producing a survey in the future.

The data collected in this report and the recommendations formed, like the secondary research will be applied to an ongoing capstone project. The data and information from both the reports will be used to meet the aims and objectives outlined in the managment documentation for the capstone project: carry out qualitative and quantitave research, create a secondary report,  design a questionnaire, create a primary report, all relating to vulnerabilities in software development. This is and should prevent or lower the probability of vulnerabilities appearing in the application.       

### [2] Primary Research Plan

The ground work for the primary research was essentially covered through the application of a pre-formulated survey, basing questions around information covered and pertained in the secondary research carried out prior. Sampling methods were also applied in the application of the survey, using the methodology such as the simple random sampling (SRS) method; a subset of a statistical population in which each member of the subset has an equal probability of being chosen.

The principle reason behind the use of this technique was to essentially cover and acquire a wide range of results and findings, thus obtaining the results through all ages. Though what was a common occurrence or what each respondent had in common, was that they were related in some form to the ICT department or were of a young age. This only deviated in 5 occurrences out of the 20 surveyed, in which four were unrelated to the IT industry, whilst another relayed inconclusive findings as all the information noted by the respondent can be seen to be falsified and so the erroneous data was omitted from the graph charts, during data cleaning. There was also another occurrence in which the name noted down seemed fabricated (Cartoon Character’s Name; Johnny Bravo), though since the name is not the most integral part of the survey and all the other fields and factors were covered, seemly with intuitive answers, it is still possible to relay viable information from the data.

Further delving into the factors and reason behind the high number of ICT students that took the survey, this can be seen to stem from the fact that all the ICT department is based on the same floor. Therefore it is no surprise that the majority of the data gathered is from ICT students and is in theory beneficial to the questions imposed above.

Following the implementation of the Simple random sampling method, another method used during the design and presentation of the survey was a non-probability method known as haphazard sample. Whilst heralding similarities to the simple random research method, ultimately SRS is a probability method. This was used to meet time scales as Haphazard sampling essentially entails choosing people based on their relative ease of access, though this was not necessarily a  disadvantage as it furthered the group/age range included in the populous, making it possible for an output of a more broader view when answering the pre-listed queries in this documentation.

The information gathered was both qualitative and quantitative. With quantitative research methods or designs such as Descriptive Design being applied, where a hypothesis is not formed until the data is collected. Whilst the application of both Haphazard sampling and simple random sampling is a quantitative and qualitative method, emphasising both written and numerical data (the use expanded upon in the above sections).

### [3] Analysis 

Through thorough analysis of the information (portrayed in a graph) collated from the raw data, the data suggests that the majority of those surveyed understand what a vulnerability is (As seen in Figure 1, Below). However, when asked if they understood the issues of vulnerabilities the data shows a mixed response:  with seven out of the twenty stating that they do not understand the issues (issues, meaning what would happen if left unchecked) of vulnerabilities, though one of the respondents answers was deemed invalid as other information clearly falsified. Whilst another was unsure as to the intention of the question and thus left it blank. This furthers substantiates that some of the respondents were incapable of answering the question as they did not understand the issues.

Figure 1 (Chart)

![Alt text](https://github.com/matthewsides/Research-Software-Vulnerabilities/blob/master/Q3_CT.png?raw=true "Optional Title")


On further analysis of the data, it indicates that less than half of those surveyed which is still a large margin of whom did not know the problems vulnerabilities may herald. This is concerning, taking into consideration that 15 out of the 20 respondents either work in an ICT related field or are studying ICT as a subject, so it is probable that the students or tutors have covered this subject at some point. Whilst three of the non ICT students displayed a slight understanding, more than the ICT students, however this information cannot be comparative, since the number of ICT students trumps the number of non- ICT students. This means that it is more likely that an outcome occurs where the amount of non ICT students in a ratio of knowing and not knowing, have a higher rate of having an understanding in comparison to the amount (numerical value) not understanding.

In continuation to the points covered above, based on the statistics and facts it may be determined that those surveyed understand why vulnerabilities may occur, working in correlation with the data gathered that 18 out of the 20 when posed with numerous options as to the definition of vulnerabilities, chose the correct choice (faults that may be exploited in a given system). Whereas when enquired about the reasons as to why faults or vulnerabilities may occur, particularly in Windows and Apples systems, the main trend or common factor seems to be human error, whether this relates to client or the business side.

Whilst other common occurrences seemed to be lack of monitoring and manual reading of code. All common flaws that organisations are usually exploited by as seen and covered in the secondary research report and case studies ‘gotofail’ (Apple Breach) and Equifax (Breach). Where vulnerabilities were seemly caused by human error; in the case of the ‘gotofail’ vulnerability, it was stated to have occurred due to negligence, not reviewing the code, thus leading to a duplication of a line being left in with a missing parenthesis. Equifax’s vulnerabilities seemed to have occurred due to software faults used for or during development and lack of monitoring , though the impact or outcome could have been mitigated or reduced based on whether the proper monitoring and procedures were put in place. Thus supporting the idea and fronting that the majority of people know the reasons behind vulnerabilities in software or systems (the comparative analysis between data and real life situations substantiate this).

Following the prior point that the majority of people understand or know the reasons behind vulnerabilities. The expected outcome suggests that the majority of the respondents should be aware of ways of preventing vulnerabilities and what mitigating vulnerabilities is. However through an analysis of the data collected and the graph displayed below (Figure 2), the opposite is recorded with only 4 of those surveyed out of the 20 appearing to know what mitigating software vulnerabilities entail. This could however be caused by the wording of the question as further evaluation of the respondents answers to other questions, demonstrates some knowledge as to how to prevent vulnerabilities.

### [4] Conclusion

In conclusion, having analysed all the data collected in the second and primary research. In particular using the case studies, it may be seen that the most probable course of action with regards to ensuring no security breaches occur with vulnerabilities not arising, would be to facilitate testing during and after software development. This would essentially minimise the possible exploits within the system since potentially all factors have been considered, tested and fixed either before the software has been released or after updates. The use of testing (security testing, functional, etc.) would also prevent similar occurrences to those seen in the Apple case study as the functions and security would be reviewed before release or use.

Furthermore, taking into consideration the feedback gathered from respondents, (primary research) in addition to the case studies and software development stages covered in the secondary research. The results indicate that versions along with monitoring is recommended in order to lessen the probability of vulnerabilities occurring. Expanding on this point, the reason for self-regulation or monitoring is to ensure that any unusual activity is catalogued, thus preventing the issue from getting out of hand as a patch may be available with those responsible or involved being brought to account. Whilst the addition of versions essentially allows for user feedback, branching upon the idea of updates, which would ensure that the software is compatible with the latest system. In addition, with the user feedback proving practical when implementing these updates as the feedback received may point to bugs previously missed, thus ensuring the software quality upon release and removing the possibility of exploitation.

So on reflection, a further recommendation proposed as a result of this research would be to use an agreed model or structure to alleviate or lesson the likelihood of vulnerabilities. This would essentially put in stronger controls and more effectively flesh out the software. Along with model checking, a technique which tests if the model of a system meets its specification, it can also be used to detect vulnerabilities. The underlying reason for this recommendation is due to the lack of understanding of how to prevent vulnerabilities from those surveyed. Through using models as long as the model is followed there is a higher chance of preventing or finding vulnerabilities, despite a lack of knowledge.

### [5] Self-Reflection

On reflection, having completed this research I have been able evaluate what went well, what went wrong, what could have been done to attain a more favourable outcome and essentially improve or learn from the mistakes made during this research project. 

With regards to any future research I have concluded that I would need to focus on the questions and articulate them more effectively. I would also pilot the questions to be used to assist with this. This would then allow for alterations to take place if necessary. This is integral due to the predicament encountered during this research project where certain questions were misconstrued or the lengthiness of the questions left those surveyed unwilling to answer. In addition, the questions were too protracted, the use of tick boxes along with pre-set answers would have covered this more effectively as those surveyed would probably feel more obliged and bothered to give a more accurate answer. This would lessen the time taken to complete the form with clear and concise answers, which would give a more precise reading and be beneficial for both the surveyor and those surveyed.

Another area in which I could improve would be to implement a structure and/or plan at the start of the research project. Essentially due to time constraints the research was not planned or implemented effectively, thus leading to inconsistencies and problems with the data collated and query’s that required answering. Therefore in the future it is recommended that some time is spent on a management plan and a schedule to ensure that timescales are adhered to.

Nevertheless, there are some positives that can be noted from the completion of this project, such as the experience attained, along with the conclusions made and inferred, thus giving valuable information pertaining to what should be done in order to ensure vulnerabilities and security breaches do not appear in a software application or system. This information may be referenced continuously throughout future projects.
