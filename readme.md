# CLEAN STRUCTURED AUDITING REPORT @BY phant0m_
This file serves as a 'recipe' for developers who wish to start their journey towards executing audits in a <b>perfectly structured</b> manner.
Follow this structure to create a report that covers all the content that a <b>quality</b> audit should include.

## EXECUTIVE SUMMARY
In this section you shortly introduce that you were contracted to audit for xx and the purpose of the audit. 
In addition you could stress the importance of audits when dealing with smart contracts.


### SUMMARY OF RESULTS
Here you give a summary of the key findings from the audit. 


## INTRODUCTION
Introduce the concerned smart contracts of the audit.
Shortly explain the smart contracts, their purpose and who developed the current version of the smart contracts.

### DISCLAIMER
Make sure for your own sake to line out that the audit does not constitute legal or investment advice and that no responsibillity is taken for any and all potential consequences of the deployment or use of the contract(s) related to the audit.


## SCOPE
Within this section, you clarify the extend of the audit. Usually, smart contracts will inherit various libraries or smart contracts written by other businesses. 
Make sure to clarify and draw the line for what EXACTLY will be audited and covered in the report. 


## ARCHITECTURAL OVERVIEW & AUDIT COVERAGE
Here you draw the architecture of the smart contracts in question.  Create an easy to understand illustration of the flow and explain it afterwards. 


## THREAT MODEL & ECONOMICS 
Discuss possible threat models which could ultimately leave the economic properties at risk. 


## KEY FINDINGS
Seperate key findings into two groups major and minor. 
Any key findings should be solved nonetheless, however seperate between the two for structure and severity.

### MAJOR FINDINGS
This section covers any vulnerabilities that can critically effect the behaviour of the concerned smart contracts

### MINOR FINDINGS
This sections covers any vulnerabilities that are not critical but still shows bad coding practices and might add unnecessary difficulties.


## CONCLUSION
Wrap it all up with overall quality, suggestions and thoughts based on discovered key findings. 


