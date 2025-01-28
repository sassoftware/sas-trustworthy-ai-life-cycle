---
sidebar_position: 5
---

# 3. Document project

## 3.1 Model owner prepares documentation

### 3.1.1 Document purpose and usage
**Model owner**: Document the purpose of the modeling project, including model usage, scope, assumptions, limitations, and potential benefits and harms in accordance with the *NIST AI RMF Playbook* guidelines in Map [1.1](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%201.1), [3.2](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%203.2), and [3.3](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%203.3).

### 3.1.2 Document end users
**Model owner**: Document end users and their expected usage in accordance with the *NIST AI RMF Playbook* guidelines in Map [1.1](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%201.1).

### 3.1.3 Document baseline metrics
**Model owner**: Document the baseline metrics or processes used to measure the success of the current decisioning system.
A decisioning system can be a model, a database, or a process of communication and knowledge sharing.
Consult the *NIST AI RMF Playbook* guidelines in Map [3.1](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%203.1).

### 3.1.4 Document feedback strategy
**Model owner**: Document the feedback strategy.
The strategy should outline how users of the AI system will provide feedback to developers and deployers of the AI system in accordance to the *NIST AI RMF Playbook* guidelines in Map [5.2](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%205.2).

### 3.1.5 Document performance metrics
**Model owner**: Document preferred performance metrics, including fit statistics.
Fit statistics are statistical values that assess how well a model fits a set of data.
Metrics are used to evaluate model performance.

### 3.1.6 Approve documentation?
**Model owner**: Review documentation supplied by the model owner.

Did the model owner provide all necessary documentation?

* [ ] Yes
* [ ] No

Please justify your response.

## 3.2 Model risk owner prepares documentation

### 3.2.1 Document potential negative impacts
**Model risk owner**: Document the model's potential negative impacts, costs, and legal risks in accordance with the *NIST AI RMF Playbook* guidelines in Map [1.1](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%201.1), Map [4.1](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%204.1), and Measure [3.1](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Measure#Measure%203.1).
Negative impacts include potential reduction in the well-being or financial security of individuals, communities, organizations, society, and the planet.
Legal risks might include risks of infringement for a third party's intellectual property or other rights.

### 3.2.2 Document organizational risk tolerance
**Model risk owner**: Document the organization\'s risk tolerance and criteria for action in accordance with the *NIST AI RMF Playbook* guidelines in Map [3.2](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%203.2).
Risk tolerance defines how acceptable various types of risk are according to the organization's goals and strategy.
Risk types include financial risk, reputational risk, and potential harm to individuals present within the data or subject to the AI system.
Criteria for action describe thresholds or events that would lead to an organization taking risk management measures, including changes to the model or the decision to deploy the model.

### 3.2.3 Approve documentation?
**Model owner**: Review documentation supplied by the model risk owner.

Did the model risk owner provide all necessary documentation?

* [ ] Yes
* [ ] No

Please justify your response.

## 3.3 Model engineer prepares documentation

### 3.3.1 Document processes
**Model engineer**: Document data processes throughout the AI life cycle.
This could include how data is prepared to be passed to the AI system, how data is passed to the system, and how the output is returned and used by other systems in accordance with the *NIST AI RMF Playbook* guidelines in Map [1.1](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%201.1) and [1.2](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%201.2).

### 3.3.2 Document the deployment location
**Model engineer**: Document the deployment location and external connections.

### 3.3.3 Approve documentation?
**Model owner**: Review documentation supplied by the model engineer.

Did the model engineer provide all necessary documentation?

* [ ] Yes
* [ ] No

Please justify your response.

## 3.4 Data engineer prepares documentation

### 3.4.1 Document bias assessment variables
**Data engineer**: Document variables that will be used to identify or assess bias in the data or models.

### 3.4.2 Document the time period covered
**Data engineer**: Document the time period covered for both the collection and creation of the data.

### 3.4.3 Document data limitations
**Data engineer**: Document any known limitations of the data, including issues arising during data collection, selection, labeling, cleaning, and analysis, in accordance with the *NIST AI RMF Playbook* guidelines in Map
[2.3](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%202.3).

### 3.4.4 Document private variables
**Data engineer**: Document variables that might be considered private according to organizational guidelines and applicable regulations.
Consider whether the unintended use of private data might expose people to harm or legal action and document a mitigation strategy in accordance with the *NIST AI RMF Playbook* guidelines in Measure [2.10](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Measure#Measure%202.10).

### 3.4.5 Approve documentation?
**Model owner**: Review documentation supplied by the data engineer.

Did the data engineer provide all necessary documentation?

* [ ] Yes
* [ ] No

Please justify your response.

## 3.5 Model developer or data engineer prepares documentation

### 3.5.1 Document metadata
**Model developer or data engineer**: Document model and project metadata, including the name of the model owner, timestamps, statistical analysis tools and the version used, model performance at training time, and any other relevant information.
This information is automatically compiled for models developed in Model Studio but can be compiled via sasctl packages for Python or R models or macros for SAS code models.

### 3.5.2 Document testing strategy
**Model developer or data engineer**: Document the model testing strategy in
accordance with the *NIST AI RMF Playbook* guidelines in Measure
[1.1](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Measure#Measure%201.1).
Consider the following questions when developing the testing strategy.
Note that answers to the questions do not need to be explicitly documented in the testing strategy.
Rather, the questions can guide the development of the strategy itself, which should be documented in this step.

1. Are there systemic differences in representativeness, missing data, input data distributions, or output data distributions between data used to train the model, data used to test the model, and data for the population or setting into which the AI system will be deployed?
2. Should the model be tested in out of distribution samples?
3. How does the model behave when encountering values not included in the training data? 
4. Are training and testing samples independent? What method was used to create the training and testing data sets?

### 3.5.3 Document thresholds
**Model developer or data engineer**: Document threshold values for the preferred model performance metric.

### 3.5.4 Document protected classes
**Model developer or data engineer**: Document relevant protected classes and their expected proportions among individuals impacted by the AI system in accordance with the *NIST AI RMF Playbook* guidelines in Map
[5.1](https://airc.nist.gov/AI_RMF_Knowledge_Base/Playbook/Map#Map%205.1).
Protected classes are groups of people who are legally protected from discrimination based on a shared characteristic.
Classes can include age, ancestry, disability, ethnicity, gender, gender identity or expression, genetic information, HIV/AIDS status, military status, national origin, pregnancy, race, religion, sex, sexual orientation, and veteran status.
Legally defined protected classes can vary by country or region.

### 3.5.5 Approve documentation?
**Model owner**: Review documentation that was supplied by the model developer or data engineer.

Did the model developer or data engineer provide all necessary documentation?

* [ ] Yes
* [ ] No

Please justify your response.
