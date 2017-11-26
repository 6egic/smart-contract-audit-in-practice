# phant0ms_ Auditing Recipe
This file serves as a 'recipe' for developers who wish to start their journey towards executing audits in a <b>perfectly structured</b> manner.
Follow this structure to create a report that covers all the content that a <b>quality</b> audit should include.

## Due Diligence
Start of by stating due diligence to the readers interested in the concerned business proposition.<br>
Make sure that the readers of the audit are <b>AWARE</b> of the types of phishing and scamming attempts circulating in the crypto space and that they are <b>INFORMED</b> that this audit report covers <b>JUST</b> the smart contracts presented in the overview section and <b>NOTHING</b> else. <br>

This means that the readers should be <b>ENCOURAGED</b> to check if the source code of the included smart contracts <b>MATCHES</b> the ones on etherscan. In addition, that any contract addresses published on media channels by the concerned business, is <b>IDENTIcAL</b> to the ones declared in the audit report, this is to maximize the <b>SAFETY</b> of the reader.


## Limitations
Next, make sure to state that the Audit report focuses <b>SOLELY</b> on the source code of the smart contracts and that you as an auditor express <b>NO OPINION</b> of concerned the business proposition or the individuals involved in the operating business. 


## Overview of audit
Start of by declaring the practitioner/author of the audit and the time of execution/delivery. <br>
Notice the reader about the <b>INTENTS</b> of the audit, which is to highlight any discovered weaknesses and that you cannot <b>GUARANTEE</b> a completely bugfree code. <br>
Next should be an overview of the smart contracts which will be audited. <br> 
This is accomplished by giving a summary of their purpose and a link to their existence on etherscan.  


## Recommendations
This section is where recommendations are given on any discovered vulnerabilities or problems within the source code of the smart contract(s). <br>
For the sake of structure, the auditor should seperate the discoverables into classes  based on their severity level: <br>

#### Critical 
Recommendations on how to fix any critical vulnerability if any is discovered.<br>

#### High
Recommendations on how to fix any high vulnerability if any is discovered.<br>

#### Medium
Recommendations on how to fix any medium vulnerability if any is discovered.<br>

#### Low / Informational
Recommendations on how to fix any low/information vulnerability if any is discovered.<br>


## Line by line comments
During this section you go through every line of code, highlight by color and optional comments. <br> 
The auditor should either highlight the code with green or red color based on the whether the line(s) pass or fail. <br>
If the line(s) of code <b>passed</b> then you mark them with <b>green color.</b> <br>
If the line(s) of code <b>failed</b> then you mark them with <b>red color.</b> 


## Vulnerabilities
In this section you focus on any failed line(s) of code from the previous section and describe the vulnerabilities found in the related line(s) of code. Make sure to be as detailed as possible in the description.<br> Classify the vulnerabilties based on severity for the sake of clarity. <br> A general guideline to figuring the characteristics to classify a vulnerability based on severity level, is described below: <br>

#### Critical 
Exploits targeting this vulnerability leads to <b>value</b> and/or <b>system compromise.</b> <br>
Coding errors that leads to system/value compromise

#### High
Exploits targeting this vulnerability leads to <b>value compromise.</b> <br>
Coding errors that leads to value compromise

#### Medium
Exploits targeting this vulnerability leads to <b>functionality compromise.</b> <br>
Coding errors that leads to function compromise

#### Low / Informational
Coding errors that works but <b>does not follow best practices.</b> <br>
Coding errors that leads to increased gas costs.


## Risks
This section should contain an explanation of the risks associated with covered smart contracts of the audit. <br>
Make sure <b>EXPOSE</b> the consequences associated with writing any logic in certain way and why it's a risk.

## Tests
One of the less attractive things to do is testing, however it is very <b>IMPORTANT</b> and many projects rely too much on boiler code. Make sure that tests has been conducted of the included smart contracts. If any tests are already present, make sure that those actually pass based on the functionality and are written properly. <br> If no tests are present, then <b>YOU</b> as an auditor should create a <b>FULL</b> test coverage section making sure <b>EVERY</b> box ticks out. When testing make sure <b>EMPHASIS</b> is placed upon tests <b>PASSING</b> and not failing, this is general best practices of unit testing. 


## Summary of contracts and conclusion
Conclusively round up by describing the overall quality of the smart contracts and thoughts of proceeds. 
