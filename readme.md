# phant0ms_ Auditing Recipe

This file serves as a 'recipe' for developers who wish to perform an audit in a perfectly structured manner.
Follow this structure to create a report that covers all the content that a quality audit should consist of.

## Due Diligence

Start of by stating the importance of performing due diligence to participants of the business proposition in question.<br>
Make sure that the readers of the audit are aware of the types of phishing and scamming attempts circulating in the crypto space and that they are informed that this audit report covers the source code presented in the audit report and nothing else. <br>

This means that the readers should be encouraged to check if the source code on etherscan matches the one present in the audit report and that any published addresses on media channels by the business in question, should be identical to the ones declared in the audit report for the reader to be safe.


## Limitations
Next, make sure to state that the Audit report focuses solely on the source code related to the business and that it shares no opinion regarding the business proposition in question or the individuals involved in the operating business. 


## Overview of audit
Start of by declaring the practitioner/author of the audit and the time of execution. <br>
Following above should be an overview of all the smart contracts in question. <br>
Make sure to touch upon the purpose of the miscellaneous smart contracts and a link to their existence. 


## Recommendations
This section is where recommendations are given on any discovered vulnerabilities or problems within the code. <br>
For the sake of structure, divide the discoverables into categories based on their severity level: <br>
A general guideline to figuring the characteristics of categorizing a vulnerability to a severity level is described below: <br>

#### Critical 
Exploits targeting this vulnerability leads to value and/or system compromise. <br>
Coding errors that leads to system/value compromise

#### High
Exploits targeting this vulnerability leads to value compromise. <br>
Coding errors that leads to value compromise

#### Medium
Exploits targeting this vulnerability leads to functionality compromise. <br>
Coding errors that leads to function compromise

#### Low / Informational
Coding errors that works but does not follow best practices. <br>
Coding errors that leads to increased gas costs.


## Line by line comments
During this section you go through every line of code and highlight the code based on whether the line(s) passed or not <br>
If the line(s) of code passed then you mark them with green color. <br>
If the line(s) of code failed then you mark them with red color. 


## Vulnerabilities
In this section you present any failed line(s) of code from the previous section and describe the vulnerabilities found in the related line(s) of code. Recommendations on how to fix the discovered vulnerabilities and their level of severity is given in one of the earlier sections.


## Risks
Explanation of the risks associated with the smart contracts in question. <br>
Make sure the business are aware of the consequences associated with writing logic in a certain way.

## Tests
Make sure that tests has been done of the code and that if there are any associated tests of the code in question that those work as they are supposed to do. <br> If no tests present, create full test coverage of the smart contracts and place emphasis on tests passing <b>NOT</b> failing.


## Summary of contracts and conclusion
Conclusively round up by describing the overall quality of the smart contracts and thoughts of proceeds. 
