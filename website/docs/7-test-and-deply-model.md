---
sidebar_position: 9
---

# 7. Test and deploy model

## 7.2 Test model

### 7.2.1 Prepare test data

**Data engineer**: Prepare the data to test the model against documented criteria from the testing strategy outlined in step `3.5.2 - Document testing strategy`.

### 7.2.2 Run tests
**Model developer**: Once the data engineer has prepared the test data, test the model according to the testing strategy defined in the Document Project step by the model developer or data engineer.

### 7.2.3 Document test steps
**Model developer**: Document the steps that you took to test the model.

### 7.2.4 Tests passed?
**Model developer**: Did the model pass the tests outlined in the testing strategy?

Did the model pass the tests as documented in the testing strategy?

* [ ] Yes
* [ ] No

Please justify your response.

### 7.2.5 Testing results unsatisfactory. What next?
**Model owner**: If you found the testing results to be unsatisfactory, what should be done next?

What should be done about the testing results?

* [ ] Retrain models
* [ ] Set a new champion model
* [ ] Document the project
* [ ] End the workflow
* [ ] Modify or update data
* [ ] Move forward with the model

### 7.2.6 Modify or update data
**Data engineer**: If you have chosen to modify or update the data due to issues discovered with your original data set, re-evaluate the data set chosen for the models.
Make appropriate changes to the existing data set or select an alternative data set.

### 7.2.7 Justify moving forward
**Model owner**: If you discovered that the testing results were unsatisfactory, but you have decided to move forward with the model, provide justification.

### 7.2.8 Retrain models
**Model developer**: If you chose to retrain your model, retrain models to identify a model that will pass according to the testing strategy.
If you decided to retrain the model using modified settings, ensure that the new model generates bias metrics that are within the established thresholds.
Document results in the Assess Model Bias tasks.

### 7.3 Model approved for production?
**Model owner**: Is the model approved for production?

Is the model approved for production?

* [ ] Yes
* [ ] No

Please justify your response.

## 7.4 Publish model

### 7.4.3 Publishing test passed?
**Model engineer**: The model was published. Run a publishing validation
test.

*Did the model pass the publishing validation test?*

* [ ] Yes
* [ ] No

Please justify your response.

### 7.4.4 Incorporate model into existing processes
**Model engineer**: Incorporate the model in your organization's existing processes.
Provide any relevant notes about the incorporation of the model into existing processes.

## 7.5 Which areas need additional review?
**Model owner**: If the model was not approved for production, which areas need additional review?

Which areas need additional review?

* [ ] Document the project
* [ ] Assess data privacy and bias
* [ ] Re-evaluate models
* [ ] Move forward with the model
