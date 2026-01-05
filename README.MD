<p align="center">
<img src="img/Banner-MS-AI-Tour-26.png" alt="decorative banner" width="1200"/>
</p>

# [Microsoft AI Tour 2026](https://aitour.microsoft.com)

## 🔥BRK471: AI for Infrastructure Management

If you will be delivering this session, check the [session-delivery-sources](./session-delivery-resources/) folder for slides, scripts, and other resources.

### Session Description

In this session you'll learn how to use AI enabled administrative tools to perform common IT Operations tasks in your Azure environment.

### 🧠 Learning Outcomes

By the end of this session, learners will be able to:

- Enable Microsoft Copilot in Azure and configure RBAC roles for this service
- Create Azure infrastructure resourcess using Azure Copilot and Cloud Shell
- Use GitHub Copilot to create an ARM template for an Azure IaaS VM
- Leverage GitHub Copilot to interrogate ARM template configuration and functionality
- Use Microsoft Copilot in Azure to control the operation of Azure IaaS VMs
- Map network topologies using AI tools

### 💻 Technologies Used

1. Azure Copilot
1. GitHub Copilot in VS Code
1. Cloud Shell

### 🔗 Session Resources
| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| Session delivery resources | https://github.com/microsoft/aitour26-BRK471-ai-for-infrastructure-management/tree/main/session-delivery-resources | PowerPoint and session video files |
| What is Azure Copilot? | https://learn.microsoft.com/azure/copilot/overview | Overview of Microsoft Copilot in Azure |

### 📚 Continued Learning Resources
| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| AI Tour 2026 Resource Center | https://aka.ms/AITour26-Resource-Center | Links to all repos for AI Tour 26 Sessions |
| Microsoft Foundry Community Discord | [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/Pwpvf3TWaw)](https://aka.ms/MicrosoftFoundryDiscord-AITour26)| Connect with the Microsoft Foundry Community! |
| Learn at AI Tour | https://aka.ms/LearnAtAITour | Continue learning on Microsoft Learn |

### 🌐 Multi-Language Support

Additional languages are coming soon.

## Content Owners

<table>
<tr>
    <td align="center"><a href="http://github.com/Orin-Thomas">
        <img src="https://avatars.githubusercontent.com/u/44561273?v=4" width="100px;" alt="Orin-Thomas"
"/><br />
        <sub><b> Orin Thomas
</b></sub></a><br />
            <a href="https://github.com/Orin-Thomas" title="talk">📢</a> 
    </td>
</tr></table>

## 

## Responsible AI 

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. Within Azure AI Foundry portal, the Content Safety service allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [Performance and Quality and Risk and Safety evaluators](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in). You also have the ability to create and evaluate with [custom evaluators](https://learn.microsoft.com/azure/ai-studio/how-to/develop/evaluate-sdk#custom-evaluators).

You can evaluate your AI application in your development environment using the [Azure AI Evaluation SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the azure ai evaluation sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Foundry portal ](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).
