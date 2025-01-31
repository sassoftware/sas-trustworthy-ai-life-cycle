---
sidebar_position: 6
---

# 5. Test model
Robust model testing can find issues before a model is deployed to production. 

## 5.1 Assign model roles
### 5.1.1 Select champion model
**Model developer**: Based on performance during training, select the best candidate for production as the champion model. 
> </br> 
> </br> 

### 5.1.2 Select challenger model(s)
**Model developer**: Based on performance during training, note promising challenger models. 
> </br> 
> </br> 
> </br> 
> </br> 
</br>

## 5.2 Test model

### 5.2.1 Prepare test data
**Data engineer**: Prepare the data to test the model against documented criteria from the testing strategy outlined in step 2.5.2. 

* [ ] Completed
* [ ] Not Completed

If applicable, add any additional details:

> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 

### 5.2.2 Run tests
**Model developer**: Once the data engineer has prepared the test data, test the model according to the testing strategy defined in step 2.5.2.

* [ ] Completed
* [ ] Not Completed

If applicable, add any additional details:

> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 

### 5.2.3 Document test steps
**Model developer**: Document the steps that you took to test the model and note results.

* [ ] Completed
* [ ] Not Completed

> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 

### 5.2.4 Tests passed?
**Model developer**: Did the model pass the tests outlined in the testing strategy?

* [ ] Yes
* [ ] No

If no, which areas need additional review?

* [ ]  Retrain models with new data. If selected, please return to step 3.
* [ ]  Fine tune the models with existing data. If selected, return to step 4.
* [ ]  Set a new champion model. If selected, please return to start of 5.
* [ ]  Update the project documentation, if selected, please return to step 2.
* [ ]  End the workflow. If selected, please depreciate the project and update step 2.1.1.
* [ ]  Move forward with the model. If selected, please continue and provide additional details or justification below. 

> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
</br>

### 5.3 Model approved for production?
**Model owner**: Is the model approved for production?

* [ ] Yes
* [ ] No

If no, which areas need additional review?

* [ ]  Retrain models with new data. If selected, please return to step 3.
* [ ]  Fine tune the models with existing data. If selected, return to step 4.
* [ ]  Set a new champion model. If selected, please return to start of 5.
* [ ]  Update the project documentation, if selected, please return to step 2.
* [ ]  End the workflow. If selected, please depreciate the project and update step 2.1.1.
* [ ]  Move forward with the model. If selected, please continue with step 6 and provide additional details or justification below. 

> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 
> </br> 

