## CLEAN STRUCTURED AUDITING REPORT ◈  phant0m_(ファントム)
This file serves as a 'recipe' for developers who wish to start their journey towards executing audits in a <b>perfectly structured</b> manner.
Follow this structure to create a report that covers all the content that a <b>quality</b> audit should include.

### 1. EXECUTIVE SUMMARY
In this section you shortly introduce that you were contracted to audit for xx and the purpose of the audit. 
In addition you could stress the importance of audits when dealing with smart contracts.


##### 1.1 SUMMARY OF RESULTS
Here you give a summary of the key findings from the audit. 


### 2. INTRODUCTION
Introduce the concerned smart contracts of the audit.
Shortly explain the smart contracts, their purpose and who developed the current version of the smart contracts.

##### 2.1 DISCLAIMER
Make sure for your own sake to line out that the audit does not constitute legal or investment advice and that no responsibillity is taken for any and all potential consequences of the deployment or use of the contract(s) related to the audit.


### 3. SCOPE
Within this section, you clarify the extend of the audit. Usually, smart contracts will inherit various libraries or smart contracts written by other businesses. 
Make sure to clarify and draw the line for what EXACTLY will be audited and covered in the report. 


### 4. ARCHITECTURAL OVERVIEW & AUDIT COVERAGE
Here you draw the architecture of the smart contracts in question.  Create an easy to understand illustration of the flow and explain it afterwards. 


### 5. THREAT MODEL & ECONOMICS 
Discuss possible threat models which could ultimately leave the economic properties at risk. 


### 6. KEY FINDINGS
Seperate key findings into two groups major and minor. 
Any key findings should be solved nonetheless, however seperate between the two for structure and severity.

##### 6.1 MAJOR FINDINGS
This section covers any vulnerabilities that can critically effect the behaviour of the concerned smart contracts

##### 6.2 MINOR FINDINGS
This sections covers any vulnerabilities that are not critical but still shows bad coding practices and might add unnecessary difficulties.


### 7. CONCLUSION
Wrap it all up with overall quality, suggestions and thoughts based on discovered key findings. 


