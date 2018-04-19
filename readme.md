## AUDIT SMART CONTRACTS WITH CONFIDENCE 
This file serves as a 'recipe' to other developers, who wish to start their journey in the world of smart contract auditing. It is a template/skeleton which aims to get any developer started <b>easily</b> and in a <b>structured way.</b> 
Follow this structure to build an in-depth report that covers all the important content which a <b>quality</b> audit should  consist off.

### 1. INTRODUCTION
In the introduction section, a short description is given about the scope, general info, and a summary of the results which is the key findings discovered from auditing the smart contracts of concern.  

#### 1.1 DISCLAIMER
Add a disclaimer for your own sake and peace of mind. Outline that the audit does not constitute legal or investment advice and that no responsibillity is taken for any and all potential consequences from using/deploying the smart contract(s) related to the audit report.

##### SCOPE
Within this section, you clarify the extend of the audit. Usually, smart contracts will inherit various libraries or smart contracts written by other businesses. 
Make sure to clarify and draw the line for what EXACTLY will be audited and covered in the report. 

### 2. SECURITY ISSUES
Touch upon the issues found in the source code, go through the well known attack vectors and comment on whether any of them were apparent in the smart contract(s) of concern. If it is the case that smart contract(s) are vulnerable to any of the attack vectors, then make sure to also state suggestions on how to fortify against the exposed vulnerabiltiies. 


### 3. OBSERVATIONS
This section, is less about security issues and more related to areas such as coherence, execution behavior, modularity, readability, visibility and optimization. Make sure to comment on all of the previously mentioned key words as they are critical to explore to ensure that the smart contract(s) of concern are of high quality. 

### 4. TESTING 
Always test/suggest testing of the smart contract(s) - unit tests should be done on smart contracts always and a code coverage percentage(branches, lines etc.) accompanied with the results (basically, the summary of passing unit tests) is very good to include.

### 5. ABOUT
Conclusively end the report by introducing your company or yourself, nonetheless the subject in charge of providing an audit to the company of concern. 
