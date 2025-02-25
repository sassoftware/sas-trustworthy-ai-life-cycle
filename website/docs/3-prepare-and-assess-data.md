---
sidebar_position: 4
---

# 3. Prepare and assess data
Prepare and assess data for future model training. 

## 3.1 Collect and prepare analytical base table
**Data engineer**: Collect and prepare an analytical base table to be used in model training. 

* [ ] Completed
* [ ] Not completed

If applicable, add any additional details:

> <br></br> 
> <br></br> 
> <br></br> 
> <br></br> 
> <br></br> 
> <br></br> 
> <br></br> 
> <br></br> 

## 3.2 Are individuals affected?
**Model owner**: Indicate whether individuals are represented in the data or affected by the use case.

Are individuals represented in the data or affected by the use case?

* [ ] Yes. If selected, continue to next step. 
* [ ] No. If selected, move to [step 3.5](#35-approve-data). 

If yes, please provide additional information.

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
<br></br>


## 3.3 Assess data privacy

### 3.3.1 Does data contain Personally Identifiable Information (PII)?
**Data engineer**: Does the data contain Personally Identifiable Information (PII)?
PII is any information connected to a specific individual that could be used to uncover that individual's identity. Examples include but are not limited to full name, Social Security number, email address, and phone number.

Does the data contain Personally Identifiable Information (PII)?

* [ ] Yes. If selected, continue to next step. 
* [ ] No. If selected, move to [step 3.3.5](#335-data-privacy-risk-approval).

If yes, please provide additional information. 

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

### 3.3.2 Is PII required?
**Model developer**: Is the PII required due to the model use case or performance?

Does this use case require that Personally Identifiable Information (PII) be included in the data?

* [ ] Yes. If yes, move to [step 3.3.4](#334-document-variables-and-risks).
* [ ] No. If no, continue to next step. 

If applicable, please provide additional information. 

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

### 3.3.3  Remove or mask PII
**Data engineer**: If the PII is not required for the use case, remove PII, or mask (anonymize) to protect the privacy of individuals within the data.
Describe the steps taken to remove PII or mask the data.

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

### 3.3.4 Document variables and risks
**Model developer or data engineer**: Document variables of concern or those that introduce privacy risks, and describe the risks of their inclusion in accordance with the *NIST AI RMF Playbook* guidelines in Measure [2.7](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Measure#Measure%202.7).

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

### 3.3.5 Data privacy risk approval
**Model owner**: Do you approve the assessment and documentation of privacy risks?

* [ ] Yes
* [ ] No

If no, please justify your response and reassign step 3 for completion.

> <br></br>
> <br></br>
> <br></br>
> <br></br>
<br></br>

## 3.4 Assess data bias

### 3.4.1 Document data-quality-related biases
**Model developer or data engineer**: Document potential biases introduced due to data quality.
Consider how data quality issues can result in unwanted biases. For example, do patterns in missing or incomplete data correspond to any protected classes, like individuals of a specific demographic group? If so, document this bias.

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

### 3.4.2 Are protected classes or proxy variables included?
**Model developer or data engineer**: Indicate whether the data includes information relating to protected classes or proxy variables for protected classes.
Protected classes are groups of people who are legally protected from discrimination based on a shared characteristic, like disability, sexual orientation, or race.
Proxy variables are not themselves protected classes but are statistically related to protected class variables. For example, a ZIP code might reveal information about an individual's race or age due to a high concentration of residents from that group.

Does the data include information relating to protected classes or proxy variables for protected classes?

* [ ] Yes. If selected, continue to the next step. 
* [ ] No. If selected, move to [step 3.4.7](#347-data-representative-of-population). 

### 3.4.3 Are variables included as inputs for the model?
**Model developer**: Indicate whether the model inputs include variables that contain information about protected classes or proxy variables for protected classes. If so, document the protected class or proxy variables that are to be included in the model.


Do the model variables include information relating to protected classes or proxy variables for protected classes?

* [ ] Yes. If selected, continue to the next step. 
* [ ] No. If selected, move to [step 3.4.7](#347-data-representative-of-population).  

### 3.4.4 Are protected classes or proxy variables required?
**Model developer**: Are protected classes or proxy variables included in the model required, given the use case or model performance?

* [ ] Yes. If selected, document why these variables are required and continue to next step.
* [ ] No. If selected, move to [step 3.4.6](#346-remove-variables-from-model). 

If applicable, add any additional details:
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

### 3.4.5 Document risks and justification
**Model developer**: Document data bias risks and variables associated with bias risk. Provide justification for their inclusion.

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

### 3.4.6 Remove variables from model
**Model developer**: If there are unnecessary protected classes or proxy variables in the model, remove them from the model.

* [ ]  Completed
* [ ]  Not completed

If applicable, add any additional details:
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

### 3.4.7 Is data representative of the population?
**Model developer or data engineer**: Indicate whether the data represents the population to which the model will be applied.
Representativeness indicates whether the individuals present in the data mirror the intended population and reflect all essential properties of the population in an accurate way. In other words, a data set or sample is representative if all the elements in a population have the same chance to be part of the sample on which data was collected.

Does the data represent the population to which the model will be applied?

* [ ] Yes. If selected, provide evidence that the data is representative, and move to [step 3.4.13](#3413-data-bias-approval). 
* [ ] No. If selected, continue to next step. 

If applicable, add any additional details:
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

### 3.4.8 Is representative data available?
**Model developer or data engineer**: If there is evidence that the data used to train the model is not representative, indicate whether representative data is available.

Is representative data available?

* [ ] Yes. If selected, move to [step 3.4.12](#3412-use-representative-data). 
* [ ] No. If selected, continue to next step. 

### 3.4.9 Do alternative strategies exist?
**Model developer or data engineer**: If representative data is unavailable, do other strategies for handling the nonrepresentative data exist?
If so, document those strategies and implement them.

Do alternative strategies exist?

* [ ] Yes. If selected, document strategy. Then move to [step 3.4.12](#3412-use-representative-data) to implement strategy. 
* [ ] No. If selected, continue to next step.

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

### 3.4.10 Document data bias risks and implications
**Model developer or data engineer**: Document data bias risks and any implications that could arise as a result. Consider risks that might arise from availability bias, recall bias, exclusion bias, pre-processing bias, measurement bias, time-interval bias, historical bias, selection bias, attrition bias, or other forms of bias.

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

What should be done about the nonexistent alternative strategies?

* [ ] End the workflow. If selected, depreciate the project and update [step 2.1.1](2-document-project.md).
* [ ] Modify or update data. If selected, return to [step 3.1](#31-collect-and-prepare-analytical-base-table).
* [ ] Move forward with the data. If selected, continue to next step. 

### 3.4.11 Provide justification for moving forward
**Model owner**: If you have decided to move forward with using the data even though issues were identified, provide justification for moving forward with the data. 

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

Move to [step 3.4.13](#3413-data-bias-approval).

### 3.4.12 Use representative data
**Model developer or data engineer**: Use identified representative data, if available, or use the alternative strategy that was documented in [step 3.4.9](#349-alternative-strategies-exist).

* [ ] Completed
* [ ] Not completed

If applicable, add any additional details:

> <br></br> 
> <br></br> 
> <br></br> 
> <br></br> 
> <br></br> 
> <br></br> 
> <br></br> 
> <br></br> 

### 3.4.13 Data bias approval
**Model owner**: Do you approve the assessment and documentation of bias risks?

* [ ] Yes
* [ ] No

If no, please justify your response and reassign step 3 for completion.

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>

## 3.5 Approve data
**Model owner**: Is the quality of the data acceptable? Has the data been appropriately cleaned? Does a review suggest data should be approved for use?

* [ ] Yes
* [ ] No

If no, please justify your response and reassign step 3 for completion.

> <br></br>
> <br></br>
> <br></br>
> <br></br>
> <br></br>
