# The Shortcut - Azure Fundamentals learning path

The Shortcut in collaboration with Microsoft present the Azure Certification Course.

The program consists of a 4 week training in which participants will be coached with the goal of getting certified in Azure Fundamentals (AZ-900).

Training sessions will be held each Tuesday from 17:00-20:00 (April 9 - May 28)

## Schedule

Date | Topic | Presenter
---------- | ---- | ----
09/04/2019 | Cloud Concepts | Drazen Dodik
16/04/2019 | Core Azure Services | Denis Cepun
23/04/2019 | Architecture, networking, security and governance | Denis Cepun
30/04/2019 | Vappu eve |
07/05/2019 | ARM Templates, Azure Pipelines and Cognitive Services | Drazen Dodik
14/05/2019 | Prep for exam |
21/05/2019 | Prep for exam |

## Learning portals

- [Microsoft Docs](http://docs.microsoft.com/) the home of Microsoft documentation for end users, developers and IT professionals. It contains quickstars, API references, tutorials and code examples.
- [Microsoft Learn](http://docs.microsoft.com/learn/) module based learning content that will help you develop your skills through theory and hands-on experience.
- [Future-Proof](http://future-proof.net) structured learning content based on paths and modules, great for preparing for a certification and going deeper into structured learning.

## #1 Cloud Concepts

### Learning objectives #1

- Define cloud computing and review types of service offered and deployment models available
- Explain cloud computing evolution and development of enabling technologies
- Understand how cloud computing is utilized and why it is gaining popularity and momentum

### Materials #1

- [Introduction to cloud computing](https://github.com/DrazenDodik/theShorcut_AzureAcademy/blob/master/presentations/Session1__CloudComputing_TheShortcut.pptx) -presentation
- **Complete during session**
  - Go to [http://azure.com/free](http://azure.com/free) to create your free account
    - You need a credit-card for validation purposes
    - You will not be billed for any of the resources you have on Azure. You would have to manually go and update your subscription to pay-as-you-go
    - You will need a Microsoft Account. If you don’t have one, head over to https://outlook.com to register your account
  - Create a Virtual Machine on Azure
    - Quickstart: [Create a Windows virtual machine in the Azure Portal](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-portal)
    - [Quickstart: Create a Linux virtual machine in the Azure Portal](https://github.com/MicrosoftDocs/azure-docs/blob/master/articles/virtual-machines/linux/quick-create-portal.md)

- **Continue on your own pace**
  - Complete the following courses on Microsoft Learn
    - [Principles of cloud computing](https://docs.microsoft.com/en-gb/learn/modules/principles-cloud-computing/index)
    - [Manage services with the Azure Portal](https://docs.microsoft.com/en-gb/learn/modules/tour-azure-portal/index)
    - [Create an Azure Account](https://docs.microsoft.com/en-gb/learn/modules/create-an-azure-account/index) *Note, you don't need to do the "Exercise - Create an Azure Account" if you already created one earlier*
    - **Extra:** [Understand the evolving world of data](https://docs.microsoft.com/en-us/learn/modules/evolving-world-of-data/)
  - Read [What to think about when you’re thinking of selecting your cloud service providers?](https://azure.microsoft.com/en-us/overview/choosing-a-cloud-service-provider/)
  - Also check the [cloud computing terms](https://azure.microsoft.com/en-us/overview/cloud-computing-dictionary/) list
  - Branch out, explore more with:
    - [5 things about Visual Studio Code](https://channel9.msdn.com/Shows/5-Things/Episode-8-Five-Things-About-Visual-Studio-Code)

## #2 Core Azure Services

### Learning objectives #2

- Explain availability, SLAs and how to design for reliability
- Understand the value of different Azure Compute and Storage options
- Use the Azure CLI and ARM-templates

### Materials #2

- [Introduction to Azure architecture, service guarantees and core cloud services (compute and storage)](https://github.com/DrazenDodik/theShorcut_AzureAcademy/blob/master/presentations/Session2_AvailabilityComputeStorage.pptx)-presentation

- **Complete during the session**
  - [Azure Virtual Machine and Compute Lab](https://handsonlabs.microsoft.com/handsonlabs/SelfPacedLabs?storyId=story://content-private/content/iai/azure100/azure100experience2/1_story_virtual_machines_compute)
- **Continue at your own pace**
  - [Azure architecture and service guarantees](https://docs.microsoft.com/en-gb/learn/modules/explore-azure-infrastructure/index)
  - [Azure compute options](https://docs.microsoft.com/en-gb/learn/modules/intro-to-azure-compute/index)
  - [Azure data storage options](https://docs.microsoft.com/en-gb/learn/modules/intro-to-data-in-azure/index)
  - [Decission tree for Azure compute services](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree)
  - [Choose the right data store](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-overview)
  - [Kubernetes for the 'klueless'](https://channel9.msdn.com/events/Connect/Microsoft-Connect--2018/T110)

- **Extra reading**
  - [Ten design principles for Azure applications](https://docs.microsoft.com/en-us/azure/architecture/guide/design-principles/)
  - [Five Reasons Why You Should Check Out Cosmos DB](https://channel9.msdn.com/Shows/5-Things/Five-Reasons-Why-You-Should-Check-Out-Cosmos-DB)
  - [Kubernetes core concepts for Azure Kubernetes Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/concepts-clusters-workloads)
  - [Introduction to microservices architectures](https://docs.microsoft.com/en-us/azure/architecture/microservices/introduction)
  - [Five Things About Azure Functions](https://channel9.msdn.com/Shows/5-Things/Five-Things-About-Azure-Functions?term=serverless)

## #3 Architecture, networking, security and governance

### Learning objectives #3

- Explain common architecture styles for cloud apps
- Understand Azure networking, security and identity
- Understand on a high-level Azure governance

### Materials #3

- [Architecture, networking, security and governance overview](https://github.com/DrazenDodik/theShorcut_AzureAcademy/blob/master/presentations/Session3_ArchitectureNetworkingSecurity.pptx)-presentation

- __Complete during the session__
  - [Azure Networking Concepts hands-on lab](https://handsonlabs.microsoft.com/handsonlabs/SelfPacedLabs?storyId=story://content-private/content/iai/azure100/azure100experience1/2_story_networking_concepts)
  - [Capture and view page load times in your Azure web app with Application Insights](https://docs.microsoft.com/en-gb/learn/modules/capture-page-load-times-application-insights/)

- __Continue__
  - [Azure networking options](https://docs.microsoft.com/en-gb/learn/modules/intro-to-azure-networking/index)
  - [Security, responsibility and trust in Azure](https://docs.microsoft.com/en-gb/learn/modules/intro-to-security-in-azure/index)
  - [Apply and monitor infrastructure standards with Azure Policy](https://docs.microsoft.com/en-gb/learn/modules/intro-to-governance/index)
  - [Manage secrets in your server apps with Azure Key Vault](https://docs.microsoft.com/en-gb/learn/modules/manage-secrets-with-azure-key-vault/)
  - [Predict costs and optimize spending for Azure](https://docs.microsoft.com/en-gb/learn/modules/predict-costs-and-optimize-spending/)
  - [Control and organize Azure resources with Azure Resource Manager](https://docs.microsoft.com/en-us/learn/modules/control-and-organize-with-azure-resource-manager/)

- __Extra reading__
  - [Top 5 security items to consider before pushing to production](https://docs.microsoft.com/en-gb/learn/modules/top-5-security-items-to-consider/)
  - [Azure Management - Governance](https://docs.microsoft.com/en-us/azure/governance/)

## #4 ARM Templates, Azure Pipelines and Cognitive Services

### Learning objectives #4

- Define and setup Azure Resource Manager Templates
- Setup a simple CD/CI pipeline with Azure Pipelines
- Use Cognitive Services APIs

### Materials #4

- [ARM Templates, Azure Pipelines, IoT and Cognitive Services overview](https://github.com/DrazenDodik/theShorcut_AzureAcademy/blob/master/presentations/Session4_ARMTemplatesPipelinesCognitive.pptx)-presentation

- __Complete during the session__
  - Complete the [Build Azure Resource Manager templates](https://docs.microsoft.com/en-us/learn/modules/build-azure-vm-templates/)
  - Start on the [Identify faces and expressions by using the Computer Vision API in Azure Cognitive Services](https://docs.microsoft.com/en-us/learn/modules/identify-faces-with-computer-vision/)

- __Continue__
  - Read through [What is Azure Pipelines?](https://docs.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines?toc=/azure/devops/pipelines/toc.json&bc=/azure/devops/boards/pipelines/breadcrumb/toc.json&view=azure-devops)
  - Complete [Microsoft Azure IoT strategy and solution](https://docs.microsoft.com/en-us/learn/modules/azure-iot-strategy-and-solutions/)
  - Read [What is Azure Internet of Things (IoT)?](https://docs.microsoft.com/en-us/azure/iot-fundamentals/iot-introduction)
  - Complete [Microsoft Azure Artificial Intelligence (AI) strategy and solutions](https://docs.microsoft.com/en-us/learn/modules/azure-artificial-intelligence/)
  - [Compare Machine Learning products at Microsoft](https://github.com/DrazenDodik/theShortcut_AzureAcademy)

- __Read more__
  - [Create your first pipeline](https://docs.microsoft.com/en-us/azure/devops/pipelines/get-started-yaml?view=azure-devops) with a sample repo
  - [Load test Azure web apps by using Azure DevOps](https://docs.microsoft.com/en-us/learn/modules/load-test-web-app-azure-devops/)
  - [Quickstart: Send telemetry from a device to an IoT hub and read it with a back-end application (Node.js)](https://docs.microsoft.com/en-us/azure/iot-hub/quickstart-send-telemetry-node)
  - Complete the Azure Fundamentals practise exam from Future-Proof.net
