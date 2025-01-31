# SAS Trustworthy AI Life Cycle

> [!IMPORTANT]
> This is a pre-release (preview) version of the SAS Trustworthy AI Life Cycle.
> It contains unfinished and incomplete sections.
> Please open issues and pull requests to identify areas in need of development.

## Overview
The SAS Trustworthy AI Life Cycle outlines steps for evaluating and deploying a more trustworthy AI system.
It aims to make the U.S. National Institute of Standards and Technology's (NIST) recommendations, standards, and best practices for [AI risk management](https://airc.nist.gov/AI_RMF_Knowledge_Base/AI_RMF) easier to adopt and follow.

The life cycle helps organizational stakeholders specify individual roles and expectations, gather required documentation, and outline factors for consideration.
As a result, teams can produce documentation to support the assertion that the organization has done its due diligence to provide evidence that the model is fair and their processes do not cause harm.

The SAS Trustworthy AI Life Cycle is a stepwise process organized into sections.
Many tasks in the life cycle reflect guidelines put forth by the [NIST AI Risk Management Framework Playbook](https://www.nist.gov/itl/ai-risk-management-framework) as it appeared in October 2023.

## Prerequisites
Using the SAS Trustworthy AI Life Cycle requires no additional resources.
However, teams can automate their use of the life cycle with a platform or tool of their choosing.

For example, a version of the SAS Trustworthy Life Cycle is available as a [sample workflow](https://github.com/sassoftware/model-management-resources/tree/main/samples/Workflow_Integration/Trustworthy_AI_Life_Cycle) that is compatible with [SAS® Workflow Manager](https://support.sas.com/en/software/workflow-manager-support.html).
This workflow can help users orchestrate trustworthy model creation and management in [SAS® Model Manager](https://www.sas.com/en_us/software/model-manager.html).

> [!NOTE]
> Although the [Trustworthy AI Life Cycle sample workflow](https://github.com/sassoftware/model-management-resources/tree/main/samples/Workflow_Integration/Trustworthy_AI_Life_Cycle) does not mirror this life cycle document in every respect, improvements to this document can result in enhancement requests for the Trustworthy AI Life Cycle sample workflow.

## Getting Started
The Trustworthy AI Life Cycle is designed for teams who collaborate to create, test, and implement models.
Though titles can differ from one organization to another, the process requires input from the following roles:

* **model owner** who is the decision-maker
* **data scientist** who develops the model
* **engineer** familiar with deployment
* **risk owner** who identifies, manages, and documents risks associated with the model
* **data engineer** who selects and prepares data for the model
* **domain expert** who can address business and domain-specific questions. 

> [!NOTE]
> Any other organizational roles that are associated with modeling could also provide valuable contributions.

Users should be generally familiar with these model management steps:

* data processing
* model creation
* testing
* documentation
* risk management
* deployment
* monitoring

## Contributing
Maintainers are accepting patches and contributions to this project.
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details about submitting contributions to this project.

## License
Materials in this repository are licensed under the [Apache 2.0 License](LICENSE).
Materials in the `/website/docs` folder are licensed under the [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/).
For more information, see the [license](website/docs/LICENSE.md) in the `/website/docs` folder.

## Additional Resources

* [Enforce responsible AI best practices: Trustworthy AI Life Cycle Workflow Available](https://communities.sas.com/t5/SAS-Communities-Library/Enforce-Responsible-AI-Best-Practices-Trustworthy-AI-Life-Cycle/ta-p/912717)
* [SAS adds to its trustworthy AI offerings with model cards and AI governance services](https://www.sas.com/en_us/news/press-releases/2024/april/trustworthy-ai-governance-model-cards.html)
* [How SAS drives technology innovation ethically & responsibly](https://www.sas.com/en_us/company-information/innovation/responsible-innovation.html)
