# Awesome Azure GenAI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
🔥 A curated list of awesome links to essential info, insights, knowledge, learning, and tooling related to GenAI on Azure.

## Table of Contents
- [Essentials](#essentials)
- [Integration](#integration)
- [Model Services](#model-services)
- [Open source models on Azure](#open-source-models-on-azure)
- [Model Customization](#model-customization)
- [Prompting](#prompting)
- [Applications and Development Tools](#applications-and-development-tools)
- [Prompt flow](#prompt-flow)
- [RAG and Retrieval](#rag-and-retrieval)
- [Copilot](#copilot)
- [Security](#security)
- [Responsibility](#responsibility)
- [Azure OpenAI Performance](#azure-openai-performance)
- [Operations](#operations)
- [Contributing](#contributing)

## Essentials
* [What is Azure OpenAI Service?](https://learn.microsoft.com/en-us/azure/ai-services/openai/overview)
* [Azure OpenAI Service models](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models)
* [What is Azure AI Foundry?](https://learn.microsoft.com/en-us/azure/ai-foundry/what-is-ai-foundry)
* [What is an Azure Landing Zone?](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/)
* [Baseline OpenAI end-to-end chat reference architecture](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/architecture/baseline-openai-e2e-chat)
* [AI workloads on Azure](https://learn.microsoft.com/en-us/azure/well-architected/ai/get-started)

## Model Services
* [Azure Machine Learning model catalog](https://learn.microsoft.com/en-us/azure/machine-learning/concept-model-catalog?view=azureml-api-2)
* [Azure OpenAI Service quotas and limits](https://learn.microsoft.com/en-us/azure/ai-services/openai/quotas-limits)
* [Optimizing Azure OpenAI: A Guide to Limits, Quotas, and Best Practices](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/optimizing-azure-openai-a-guide-to-limits-quotas-and-best/ba-p/4076268)
* [Azure OpenAI Service model deprecations and retirements](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/model-retirements)

## Open source models on Azure
* [Fine Tuning Open Source Large Language Models (PEFT QLoRA) on Azure Machine Learning](https://blog.devgenius.io/fine-tuning-large-language-models-on-azure-machine-learning-358338f4e66a)

## Integration
* [Baseline OpenAI end-to-end chat reference architecture](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/architecture/baseline-openai-e2e-chat)
* [Azure Well-Architected Framework perspective on Azure OpenAI](https://learn.microsoft.com/en-us/azure/well-architected/service-guides/azure-openai)
* [Azure Well-Architected Framework perspective on Azure Machine Learning](https://learn.microsoft.com/en-us/azure/well-architected/service-guides/azure-machine-learning)
* [HAX design library for Human-AI interaction guidelines](https://www.microsoft.com/en-us/haxtoolkit/library/?content_type%5B0%5D=guideline&content_type%5B1%5D=pattern&content_type%5B%5D=example)
* [APIM AI gateway labs](https://github.com/Azure-Samples/AI-Gateway)
* [Manage traffic with spillover for provisioned deployment](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/spillover-traffic-management)
* [AI Hub Gateway Landing Zone solution accelerator for implementing a central AI API gateway](https://github.com/Azure-Samples/ai-hub-gateway-solution-accelerator)
* [Azure OpenAI with APIM scaling special sauce](https://github.com/Azure/aoai-apim/blob/main/README.md)

## Model Customization
* [Customize a model with fine tuning](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/fine-tuning?tabs=turbo%2Cpython&pivots=programming-language-studio)
* [Fine tuning with Azure OpenAI](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/fine-tuning-now-available-with-azure-openai-service/ba-p/3954693)
* [Fine Tuning with Function Calling on Azure OpenAI Service](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/fine-tuning-with-function-calling-on-azure-openai-service/ba-p/4065968)
* [Cost Optimized hosting of Fine-tuned LLMs in Production](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/cost-optimized-hosting-of-fine-tuned-llms-in-production/ba-p/4062192)

## Prompting
* [Write more effective prompts](https://learn.microsoft.com/en-us/training/modules/apply-prompt-engineering-azure-openai/3-write-effective-prompts)
* [Provide context to improve accuracy](https://learn.microsoft.com/en-us/training/modules/apply-prompt-engineering-azure-openai/4-provide-context-to-improve-accuracy?pivots=python)

## AI Foundry
* [Collection of Azure AI Foundry solution examples](https://github.com/corticalstack/azure-ai-foundry-examples)

## Applications and Development
* [Get started with Function Calling through Assistants API on Azure OpenAI](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/get-started-with-function-calling-through-assistants-api-on/ba-p/4093150)
* [Unveiling Generative AI Bulk Processing and Ingestion Pattern](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/unveiling-generative-ai-bulk-processing-and-ingestion-pattern/ba-p/4120777)
* [Choosing the right tool: a comparitive analysis of the Assistants API and Chat Completions API](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/choosing-the-right-tool-a-comparative-analysis-of-the-assistants/ba-p/4140438)
* [Azure OpenAI samples GitHub repo](https://github.com/Azure/azure-openai-samples)
* [Azure-OpenAI-demos GitHub repo](https://github.com/retkowsky/Azure-OpenAI-demos/)
* [ChatGPT + Enterprise data with Azure OpenAI and AI Search](https://github.com/Azure-Samples/azure-search-openai-demo)
* [Azure sample OpenAI end-to-end baseline reference implementation](https://github.com/azure-Samples/openai-end-to-end-baseline)
* [Securely use Azure OpenAI on your data](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/use-your-data-securely)
* [Assistants API to build custom AI assistants with Azure OpenAI Service](https://www.youtube.com/watch?v=CMXtAe5DhXc)
* [Analyze Videos with Azure Open AI GPT-4 Turbo with Vision and Azure Data Factory](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/analyze-videos-with-azure-open-ai-gpt-4-turbo-with-vision-and/ba-p/4032778)
* [Generate embeddings with the Azure AI Vision multi-modal embeddings API](https://techcommunity.microsoft.com/t5/educator-developer-blog/generate-embeddings-with-the-azure-ai-vision-multi-modal/ba-p/4067816)
* [Sentiment Analysis with Durable Functions](https://techcommunity.microsoft.com/t5/apps-on-azure/azure-ai-language-sentiment-analysis-with-durable-functions/m-p/4055341#M825)
* [Unlocking Advanced Document Insights with Azure AI Document Intelligence](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/unlocking-advanced-document-insights-with-azure-ai-document/ba-p/4109675)
* [A collection of Azure AI templates deployed with the Azure Developer CLI](https://learn.microsoft.com/en-us/collections/5pq0uompdgje8d)

## Prompt flow
* [Azure’s PromptFlow: Deploying LLM Applications in Production](https://www.advancinganalytics.co.uk/blog/2023/10/30/azure-machine-learning-prompt-flow-a-comprehensive-guide)
* [Part 1 of Prompt Flow in Azure Machine Learning: Industry-grade prompt management](https://medium.com/productizing-language-models/part-1-of-prompt-flow-in-azure-machine-learning-industry-grade-prompt-management-87b5b6f853d4)
* [Build, benchmark, evaluate and deploy real-time inference endpoint with Prompt Flow](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/build-benchmark-evaluate-and-deploy-real-time-inference-endpoint/ba-p/4056330)
* [Running batches with promptflow](https://learn.microsoft.com/en-us/semantic-kernel/agents/planners/evaluate-and-deploy-planners/running-batches-with-prompt-flow?tabs=gpt-35-turbo)
* [Combine Semantic Kernel with Azure Machine Learning prompt flow](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/combine-semantic-kernel-with-azure-machine-learning-prompt-flow/ba-p/4008981)
* [Troubleshooting prompt flow](https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/tools-reference/troubleshoot-guidance?view=azureml-api-2)
* [Repo with promptflow templates for building LLM-infused apps](https://github.com/microsoft/genaiops-promptflow-template)

## RAG and Retrieval
* [Retrieval Augmented Generation (RAG) in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview)
* [Azure OpenAI RAG workshop](https://github.com/Azure-Samples/azure-openai-rag-workshop)
* [GraphRAG: Unlocking LLM discovery on narrative private data](https://www.microsoft.com/en-us/research/blog/graphrag-unlocking-llm-discovery-on-narrative-private-data/)
* [Elevating RAG and Search: The Synergy of Azure AI Document Intelligence and Azure OpenAI](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/elevating-rag-and-search-the-synergy-of-azure-ai-document/ba-p/4006348)
* [Voice RAG with AI Search and gpt4o-realtime-preview](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/voicerag-an-app-pattern-for-rag-voice-using-azure-ai-search-and/ba-p/4259116)
* [The best retrieval strategies for generative AI. Hint: you need more than just vector search](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/the-best-retrieval-strategies-for-generative-ai-hint-you-need/ba-p/3960601)
* [Building a RAG App with VS Code and Prompt Flow extension](https://www.youtube.com/watch?v=4oCLjQdLMxQ)
* [Blog on building intelligent RAG For multimodality and complex document structure](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/build-intelligent-rag-for-multimodality-and-complex-document/ba-p/4118184)
* [Blog on advanced RAG with AI Search and LlamaIndex](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/advanced-rag-with-azure-ai-search-and-llamaindex/ba-p/4115007)
* [Blog on step-by-step guide to evaluating RAG with Azure AI Search, Azure OpenAI, LlamaIndex, and Tonic AI](https://farzzy.hashnode.dev/step-by-step-guide-to-evaluating-rag-with-azure-ai-search-azure-openai-llamaindex-and-tonic-ai)
* [Learnings from ingesting millions of technical pages for RAG on Azure](https://jakobs.dev/learnings-ingesting-millions-pages-rag-azure/)
* [Load testing RAG based GenAI applications](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/load-testing-rag-based-generative-ai-applications/ba-p/4086993)
* [SuperRAG – How to achieve higher accuracy with Retrieval Augmented Generation](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/superrag-how-to-achieve-higher-accuracy-with-retrieval-augmented/ba-p/4139004)
* [Advanced RAG with Azure AI Search and LlamaIndex](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/advanced-rag-with-azure-ai-search-and-llamaindex/ba-p/4115007)
* [GPT-RAG solution accelerator](https://github.com/Azure/GPT-RAG)
* [Faceted navugation with AI Search](https://learn.microsoft.com/en-us/azure/search/search-faceted-navigation)

## Evaluation
* [Evaluation of generative AI applications](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-approach-gen-ai)
* [Samples evaluating Generative AI output with the *azure-ai-evaluation* SDK](https://github.com/Azure-Samples/azureai-samples/tree/main/scenarios/evaluate)

## Semantic Kernel
* [Blog multi-agent collab with selection and termination strategy blog](https://devblogs.microsoft.com/semantic-kernel/guest-blog-step-by-step-guide-to-building-a-portfolio-manager-a-multi-agent-system-with-microsoft-semantic-kernel-and-azure-openai/)
* [Multi-agent collaboration](https://learn.microsoft.com/en-us/semantic-kernel/frameworks/agent/agent-chat?pivots=programming-language-python)
* [Multi-agent with AI Agent and Semantic Kernel blog](https://devblogs.microsoft.com/semantic-kernel/guest-blog-build-a-multi-agent-system-using-microsoft-azure-ai-agent-service-and-semantic-kernel-in-3-simple-steps/)
* [Semantic Kernal chat completion auto function calling](https://learn.microsoft.com/en-us/semantic-kernel/concepts/ai-services/chat-completion/function-calling/?pivots=programming-language-python)
* [Observability in Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/concepts/enterprise-readiness/observability/?pivots=programming-language-python)
* [Moneta - Semantic Kernel AI-Agentic Assistant for Insurance and Banking](https://github.com/Azure-Samples/moneta-agents)
* [Semantic Kernel python examples](https://github.com/golden-aries/semantic-kernel/tree/ca052ee4793109d8e9bbbd861e46e81c6ab4f854/python/samples)

## Copilot
* [Creating a GenAI Enterprise Co-pilot](https://www.linkedin.com/pulse/genai-enterprise-copilot-serhiy-seletskyi--mprqf/?trackingId=ea1fOd%2BrTXOODIoiZfjNrg%3D%3D)
* [Building smarter Copilots with Copilot Studio and Azure OpenAI integration](https://forwardforever.com/building-smarter-copilots-with-copilot-studio-and-azure-openai-integration/)
* [Microsoft Copilot personal and work experiences explained](https://techcommunity.microsoft.com/t5/microsoft-mechanics-blog/microsoft-copilot-personal-and-work-experiences-explained/ba-p/4067951)
* [Repo for creating copilot enterprise chat API using custom Python code to ground copilot responses in your company data & APIs](https://github.com/Azure/aistudio-copilot-sample)
* [An end-to-end example of a Legal Research Copilot application](https://github.com/Azure-Samples/graphrag-legalcases-postgres)

## Security
* [Azure PyRIT Python Risk Identification Toolkit for red teaming generative AI](https://github.com/Azure/PyRIT)
* [Security Best Practices for GenAI Applications (OpenAI) in Azure](https://techcommunity.microsoft.com/t5/azure-architecture-blog/security-best-practices-for-genai-applications-openai-in-azure/ba-p/4027885)
* [Data Security, Protection and Model Management – with Azure OpenAI](https://www.linkedin.com/pulse/data-security-protection-model-management-azure-kalai-shakrapani-6xq9c/?trackingId=39PX2qsES5SZ7ch0iESB%2Bw%3D%3D)

## Responsibility
* [Responsible AI developer hub](https://azure.github.io/responsible-ai-hub/)

## Azure OpenAI Performance
* [Load testing Azure OpenAI endpoints](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/load-testing-azure-openai-with-jmeter/ba-p/4068117)
* [Azure OpenAI latency](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/latency)
* [Azure OpenAI PTUs (Provisioned Throughput Units)](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/provisioned-throughput)
* [Best practice guidance for PTU](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/best-practice-guidance-for-ptu/ba-p/4152133)
* [Right-size your PTU deployment and save big](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/right-size-your-ptu-deployment-and-save-big/ba-p/4053857)

## Operations
* [Azure OpenAI Best Practices Insights from Customer Journeys](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/azure-openai-best-practices-insights-from-customer-journeys/ba-p/4166943)
* [The LLM Latency Guidebook: Optimizing Response Times for GenAI Applications](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/the-llm-latency-guidebook-optimizing-response-times-for-genai/ba-p/4131994)
* [Calulating business unit chargebacks using shared Azure OpenAI instance](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/calculating-chargebacks-for-business-units-projects-utilizing-a/ba-p/3909202)
* [An Introduction to LLMOps: Operationalizing and Managing Large Language Models using Azure ML](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/an-introduction-to-llmops-operationalizing-and-managing-large/ba-p/3910996)
* [Achieve generative AI operational excellence with the LLMOps maturity model](https://azure.microsoft.com/en-us/blog/achieve-generative-ai-operational-excellence-with-the-llmops-maturity-model/)
* [Elevate Your LLM Applications to Production via LLMOps](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/elevate-your-llm-applications-to-production-via-llmops/ba-p/3979114)
* [Elevate Your LLM Applications to Production via LLMOps and promptflow](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/elevate-your-llm-applications-to-production-via-llmops/ba-p/3979114)
* [LLMOps Using Azure Machine Learning Prompt Flow — NER Task](https://kyleake.medium.com/llmops-using-azure-machine-learning-prompt-flow-ner-task-927d98a9a1a8)
* [LLMOps promptflow template](https://github.com/microsoft/llmops-promptflow-template)
* [Deploy your Azure Machine Learning prompt flow on virtually any platform](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/deploy-your-azure-machine-learning-prompt-flow-on-virtually-any/ba-p/4004307)
* [Enable GPT failover with Azure OpenAI and Azure API Management](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/enable-gpt-failover-with-azure-openai-and-azure-api-management/ba-p/4038233)
* [Blog on Azure OpenAI best practices for production](https://medium.com/@manoranjan.rajguru/azure-openai-best-practices-for-production-b733eca4bde5)
* [Code-first LLMOps](https://www.youtube.com/watch?v=_Mwxukq5_mg)

## Other
* [Azure Solution Accelerator Finder](https://florki610.github.io/accelerator-finder/)
* [Bootstrap the building of an agentic application](https://github.com/Azure-Samples/az-ai-kickstarter)
  
## Contributing
Your contributions are welcome! Please take a look at the [contribution guidelines](https://github.com/corticalstack/awesome-azure-genai/blob/master/CONTRIBUTING.md) first.
