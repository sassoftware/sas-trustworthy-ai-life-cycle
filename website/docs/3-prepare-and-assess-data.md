---
sidebar_position: 4
---

# 3. Prepare and assess data

## 3.1 Individuals affected?
**Model owner**: Indicate whether individuals are represented in the data or affected by the use case.

Are individuals represented in the data or affected by the use case?

* [ ] Yes
* [ ] No

If yes, please provide additional information.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
</br>

## 2.4 Approve data for use?
**Model owner**: Is the quality of the data acceptable?
Has the data been appropriately cleaned?
Does a review suggest data should be approved for use?

Do you approve this data based on the assessment that this use case will not impact individuals?

* [ ] Yes
* [ ] No

If no, please justify your response.

> </br>
> </br>
> </br>
> </br>
</br>

## 2.6 Assess data privacy and bias

### 2.6.1 Assess data privacy

#### 2.6.1.1 Data contains Personally Identifiable Information (PII)?
**Data engineer**: Does the data contain Personally Identifiable Information (PII)?
PII is any information connected to a specific individual that could be used to uncover that individual's identity.
Examples include but are not limited to full name, Social Security number, email address, and phone number.

Does the data contain Personally Identifiable Information (PII)?

* [ ] Yes
* [ ] No

If yes, please provide additional information and justify moving foward with these risks in mind.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.1.2 PII required?
**Model developer**: Is the PII required due to the model use case or performance?

Does this use case require that Personally Identifiable Information (PII) be included in the data?

* [ ] Yes
* [ ] No

If yes, please provide additional information and justify moving foward with these risks in mind.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.1.3 Remove or mask PII
**Data engineer**: If the PII is not required for the use case, remove PII, or mask (anonymize) to protect the privacy of individuals within the data.
Describe the steps taken to remove PII or mask the data.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.1.4 Document variables and risks
**Model developer or data engineer**: Document variables of concern or those that introduce privacy risks, and describe the risks of their inclusion in accordance with the *NIST AI RMF Playbook* guidelines in Measure [2.7](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Measure#Measure%202.7).

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

### 2.6.2 Approve data privacy risks?
**Model owner**: Approve the data privacy risks?

Do you approve the assessment and documentation of privacy risks?

* [ ] Yes
* [ ] No

If no, please justify your response.

> </br>
> </br>
> </br>
> </br>
</br>

### 2.6.3 Assess data bias

#### 2.6.3.1 Document data-quality-related biases
**Model developer or data engineer**: Document potential biases introduced due to data quality.
Consider how data quality issues can result in unwanted biases.
For example, do patterns in missing or incomplete data correspond to any protected group classes, like individuals of a specific demographic group?
If so, document this bias.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.3.2 Protected classes or proxy variables?
**Model developer or data engineer**: Indicate whether the data includes information relating to protected classes or proxy variables for protected classes.
Protected classes are groups of people who are legally protected from discrimination based on a shared characteristic, like disability, sexual orientation, or race.
Proxy variables are not themselves protected classes but are statistically related to protected class variables.
For example, a ZIP code might reveal information about an individual\'s race or age due to a high concentration of residents from that group.

Does the data include information relating to protected classes or proxy variables for protected classes?

* [ ] Yes
* [ ] No

If yes, please provide additional information and justify moving foward with these risks in mind.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.3.3 Data representative of population?
**Model developer or data engineer**: Indicate whether the data represents the population to which the model will be applied.
Representativeness indicates whether the individuals present in the data mirror the intended population and reflect all essential properties of the population in an accurate way.
In other words, a data set or sample is representative if all the elements in a population have the same chance to be part of the sample on which data was collected.

Does the data represent the population to which the model will be applied?

* [ ] Yes
* [ ] No

If no, please provide additional information and justify moving foward with these risks in mind.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.3.4 Provide evidence data is representative
**Model developer or data engineer**: Provide evidence that the data is representative. Evidence might include relevant demographic statistical information about the population, especially demographics related to the model use case.
For example, a data set's demographic distribution and other statistics should closely mirror the population's demographic distribution.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.3.5 Document data bias risks and implications
**Model developer or data engineer**: Document data bias risks and any implications that could arise as a result. Consider risks that might arise from availability bias, recall bias, exclusion bias, pre-processing bias, measurement bias, time-interval bias, historical bias, selection bias, attrition bias, or other forms of bias.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.3.6 Are variables inputs to model?
**Model developer**: Indicate whether the model includes information about protected classes or proxy variables for protected classes.
If so, document the protected class or proxy variables that are included in the model.
Protected classes are groups of people who are legally protected from discrimination based on a shared characteristic, like disability, sexual orientation, or race.
Proxy variables are not themselves protected classes but are statistically related to protected class variables.
For example, a ZIP code might reveal information about an individual's race or age due to a high concentration of residents from that group.

Does the model include information relating to protected classes or proxy variables for protected classes?

* [ ] Yes
* [ ] No

If yes, please provide additional information and justify moving foward with these risks in mind.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
'
#### 2.6.3.7 Protected classes or proxy variables required?
**Model developer**: Are protected classes or proxy variables included in the model required, given the use case or model performance?

Are protected classes or proxy variables included in the model required, given the use case or model performance?
If so, document why these variables are required.

* [ ] Yes
* [ ] No

If yes, please provide additional information and justify moving foward with these risks in mind.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.3.8 Document risks and justification
**Model developer**: Document data bias risks and associated variables and provide justification for their inclusion.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.3.9 Remove variables from model
**Model developer**: If there are unnecessary protected classes or proxy variables in the model, remove them from the model.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.3.10 Representative data available?
**Model developer or data engineer**: If there is evidence that the data used to train the model is not representative, indicate whether representative data is available.

Is representative data available?

* [ ] Yes
* [ ] No

If no, please provide additional information and justify moving foward with these risks in mind.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.3.11 Use representative data
**Model developer or data engineer**: Use identified available representative data.

#### 2.6.3.12 Alternative strategies exist?
**Model developer or data engineer**: If representative data is unavailable, do other strategies for handling the nonrepresentative data exist?
If so, document those strategies and implement them.

Do alternative strategies exist?

* [ ] Yes
* [ ] No

If no, please provide additional information and justify moving foward with these risks in mind.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
#### 2.6.3.13 Document data bias risks and implications
**Model developer or data engineer**: Document any additional data risks.
Consider and document risks that might arise from other sources of bias like availability bias, recall bias, exclusion bias, pre-processing bias, measurement bias, time-interval bias, historical bias, selection bias, and attrition bias.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

##### 2.6.3.14 Alternative strategies do not exist. What should be done next?
**Model developer or data engineer**: If representative data is not available and there are no alternate strategies to address the data, what should be done next?

What should be done about the nonexistent alternative strategies?

* [ ] End the workflow
* [ ] Modify or update data
* [ ] Move forward with the data

#### 2.6.3.16 Justify moving forward
**Model owner**: If you have decided to move forward with using the data even though issues were identified, provide justification for moving forward with the data.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

#### 2.6.4 Approve data bias?
**Model owner**: Approve the levels of data bias?

Do you approve the assessment and documentation of risks arising from data bias?

* [ ] Yes
* [ ] No

If no, please justify your response.

> </br>
> </br>
> </br>
> </br>
</br>

## 2.7 Approve data for use?
**Model owner**: Is the quality of the data acceptable?
Has the data been appropriately cleaned?
Does a review suggest data should be approved for use?

Do you approve this data based on the assessment that this use case will not impact individuals?

* [ ] Yes
* [ ] No

If no, please justify your response.

> </br>
> </br>
> </br>
> </br>
</br>

## 2.9 Modify or update data
**Data engineer**: If you have chosen to modify or update the data due to issues discovered with your original data set, re-evaluate the data set chosen for the models.
Make appropriate changes to the existing data set or select an alternative data set.

## 2.10 Justify moving forward
**Model owner**: If you have decided to move forward with using the model even though data issues were identified, provide justification for moving forward with the model.

> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>
> </br>

