# Thank you for visiting my shiny✨, new portfolio.
#### BTW - its a constant work in progress, so check back regularly for updated content

Hello there! I'm Vanessa Crosby-Fitzgerald, a human (yes, still proudly carbon-based). I'm an AI Developer specializing in conversational AI, NLU/NLP, Agentic Automation and Agent Data Procurement.

Over the past few years, I've worked in Data, NLP, and Autonomous Agents, orchestrating teams of tireless, brilliant AI agents who eagerly take on the repetitive (and let's be honest, boring) tasks the rest of us would rather avoid. The best part? They never complain—they actually love the work.

![AI Agent](portDeco1.jpg?raw=true)

**[Visit my YouTube channel](https://www.youtube.com/c/TeachingTheMachine)**

I bring a unique perspective to backend architecture and data engineering, creating environments where AI agents collaborate seamlessly, amplify each other's strengths, and share knowledge without stepping on each other's digital toes. Beyond the technical work, I enjoy guiding these digital minds as they develop their "personalities" and ethical frameworks—ensuring strong alignment with human goals and thoughtful governance so their enthusiasm translates into genuinely useful, responsible outcomes.

Below you'll find links to some of my work on GitHub, showcasing projects where I build and orchestrate AI agents, automate workflows, and create intelligent systems that make repetitive tasks effortless—and maybe even a little fun.

## 🤖 AI Agent Crew Development and Automation

|  Smart Outreach AI Agent | Local AI Agent System |
|:---:|:---:|
 | ![Outreach AI Agent](SM_agents.jpg) | ![Local AI Agent System](SM_agents.jpg) |
| AI-powered outreach agent integrating CrewAI, Twilio for SMS, and OpenAI APIs to automate personalized communication | Fully local AI agent system using CrewAI and Ollama, enabling cost-free automation workflows without external API dependencies |
| **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Outreach-AI-Agent)** | **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** |
| *🎯 85% response rate improvement* | *💰 100% cost-free operation* |


## Non-Agentic Demos

<style>
.modal {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.8);
}

.modal-content {
    position: relative;
    margin: 5% auto;
    width: 80%;
    max-width: 800px;
    background-color: #fff;
    border-radius: 12px;
    overflow: hidden;
}

.modal-video {
    width: 100%;
    height: 450px;
}

.close {
    position: absolute;
    top: 10px;
    right: 20px;
    color: white;
    font-size: 30px;
    font-weight: bold;
    cursor: pointer;
    z-index: 1001;
    background: rgba(0,0,0,0.5);
    border-radius: 50%;
    width: 40px;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.clickable-image {
    cursor: pointer;
    transition: transform 0.2s ease;
}

.clickable-image:hover {
    transform: scale(1.05);
}

.demo-button {
    background: #007bff;
    color: white !important;
    padding: 8px 16px;
    border-radius: 6px;
    text-decoration: none;
    display: inline-block;
    cursor: pointer;
    border: none;
    font-weight: 600;
}

.demo-button:hover {
    background: #0056b3;
    text-decoration: none;
}
</style>

| Video Speech Swap - Accent Blaster | Multi-Domain Synthetic Data Engine | AudioMate: TTS API Tester |
|:---:|:---:|:---:|
| <p align="center">![Video Speech Replace](speechSwap_thumb2.jpg)</p> | <p align="center">![Multi-Domain Synthetic Data Engine](multiDomain_SynthEngine_thumb.jpg)</p> | <p align="center"><img src="audiMateTtsTester_thumb.jpg" alt="AudioMate TTS API Tester" class="clickable-image" onclick="openVideoModal()" style="cursor: pointer;"></p> | 
| **For clearer understanding of tech videos** | **Create and export synthetic data in .csv or JSON format** | **Test TTS API with custom text** |
| Audio replacement system powered by OpenAI to replace video audio with clearer voices for better understanding of technical content | Generate synthetic data in different domains with 3 complexity levels available | Test various TTS APIs. Currently set up for OpenAI and ElevenLabs. Add your own. |
| **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/SpeechSwap)** | **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/SyntheticData-MultiDomain)** | **<button class="demo-button" onclick="openVideoModal()">🚀 Live Demo</button>** \| **📂 [Repository](https://github.com/TeachingTheMachine/AudioMate)** |
| *🎤 Voice Synthesis* | *📊 Generate Datasets* | *🗣️ Test TTS APIs* |

<!-- Video Modal -->
<div id="videoModal" class="modal">
    <div class="modal-content">
        <span class="close" onclick="closeVideoModal()">&times;</span>
        <video id="modalVideo" class="modal-video" controls>
            <source src="https://raw.githubusercontent.com/TeachingTheMachine/AudioMate/main/client/src/assets/videoDemo.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>

<script>
function openVideoModal() {
    document.getElementById('videoModal').style.display = 'block';
    document.getElementById('modalVideo').play();
}

function closeVideoModal() {
    const modal = document.getElementById('videoModal');
    const video = document.getElementById('modalVideo');
    modal.style.display = 'none';
    video.pause();
    video.currentTime = 0;
}

// Close modal when clicking outside of it
window.onclick = function(event) {
    const modal = document.getElementById('videoModal');
    if (event.target == modal) {
        closeVideoModal();
    }
}

// Close modal with Escape key
document.addEventListener('keydown', function(event) {
    if (event.key === 'Escape') {
        closeVideoModal();
    }
});
</script>

## 🎙️ Agentic Content Creation and Documentation
- coming soon
## ➡️ Custom AI Workflows
- coming soon
## 🌐 Scalable Multi-Agent Systems
- coming soon
## 📊 AgentOps-Integrated Systems
- coming soon
## 🌍 Mama's 'ol Fashioned Websites
- coming soon
## 📺 View my YouTube videos.
- coming soon

<!--


## 🎙️ Agentic Content Creation and Documentation
 
| AI Podcast Creation Studio | AI Content Creation Engine |
|:---:|:---:|
| ![Podcast Creation with 2 Agents](SM_agents.jpg) | ![Agentic AI Content Creation Engine](SM_agents.jpg) |
| Content creation system powered by CrewAI and ElevenLabs, showcasing multi-agent collaboration for high-quality podcast generation | Content creation system powered by CrewAI, showcasing multi-agent collaboration for generating high-quality content outputs |
| **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** | **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** |
| *🎤 Voice Synthesis* | *📝 10x faster content creation* |

| AI Blogging Automation | Documentation AI Agent |
|:---:|:---:|
| ![AI-Powered Blogging Automation System](SM_agents.jpg) | ![Documentation AI Agent](SM_agents.jpg) |
| Automated blogging system using CrewAI with local LLMs like LM Studio, Ollama, and JanAI for content generation at scale | AI agent for automating internal documentation processes using CrewAI, streamlining complex documentation workflows |
| **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** | **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** |
| *📊 Generates 50+ articles/day* | *⚡ 80% faster documentation* |

## ➡️ Custom AI Workflows
 
| Collaborative AI Framework | Custom Workflow Orchestrator |
|:---:|:---:|
| ![Collaborative AI Framework](SM_agents.jpg) | ![Custom Workflow Orchestrator](SM_agents.jpg) |
| Collaborative AI agent framework using CrewAI to demonstrate agentic AI capabilities for task coordination and execution | Custom workflow orchestrator using CrewAI with local LLMs, focusing on modular components for tailored AI task management |
| **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** | **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** |
| *🎯 Seamless agent coordination* | *🔧 Fully customizable workflows* |

## 🌐 Scalable Multi-Agent Systems
 
| Multi-Agent Workflow Engine | AI Agent Management Platform | AI Collaboration Network |
|:---:|:---:|:---:|
| ![Scalable Multi-Agent Workflow Engine](SM_agents.jpg) | ![Configurable AI Agent Management Platform](SM_agents.jpg) | ![Intelligent AI Agent Collaboration Network](SM_agents.jpg) |
| Multi-agent system using CrewAI, LangChain, and LLMs like OpenAI to manage complex task assignments and scalable AI workflows | Flexible AI agent management system using CrewAI, with API key configuration and integration with GPT-3, GPT-4, and Llama | Network of AI agents using CrewAI and powerful LLMs to solve complex tasks through collaborative intelligence |
| **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** | **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** | **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** |
| *📈 Handles 1000+ concurrent tasks* | *🔑 Multi-model API support* | *🧠 Distributed AI problem solving* |

## 📊 AgentOps-Integrated Systems
 
| AgentOps AI Monitoring | CrewAI Development Environment |
|:---:|:---:|
| ![AgentOps-Enhanced AI System Monitoring](SM_agents.jpg) | ![AgentOps-Integrated CrewAI Development Environment](SM_agents.jpg) |
| Monitoring solution for CrewAI-based AI agents using AgentOps, integrating with Autogen and Ollama for real-time performance tracking | Development environment for CrewAI applications, utilizing the CrewAI CLI and AgentOps for streamlined agent creation and monitoring |
| **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** | **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** |
| *📊 Real-time performance metrics* | *⚡ Streamlined development workflow* |

| AgentOps CrewAI Platform | Multi-Agent Dashboard |
|:---:|:---:|
| ![Streamlined AgentOps-CrewAI Integration Platform](SM_agents.jpg) | ![Multi-Agent System with Monitoring Dashboard](SM_agents.jpg) |
| Lightweight platform integrating CrewAI with AgentOps for efficient AI agent monitoring and management | Multi-agent system with a monitoring dashboard using CrewAI and AgentOps, showcasing robust AI framework management |
| **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** | **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/Coming-Soon)** |
| *🚀 Lightweight and efficient* | *📊 Comprehensive monitoring dashboard* |

## Non-Agentic Demos

| Video Speech Replace | Coming Soon |
|:---:|:---:|
| ![Video Speech Replace](SM_agents.jpg) | |
| **For clearer understanding of tech videos** | |
| Audio replacement system powered by OpenAI to replace video audio with clearer voices for better understanding of technical content | More projects coming soon... |
| **🚀 Live Demo** \| **📂 [Repository](https://github.com/TeachingTheMachine/SpeechReplace)** | |
| *🎤 Voice Synthesis* | |

## 🌍 Good 'ol Fashioned Websites
 
| EcoShop - Sustainable Marketplace | Neon Dreams - Rock Band | Tony's Pizza Palace |
|:---:|:---:|:---:|
| ![EcoShop Sustainable Marketplace](SM_agents.jpg) | ![Neon Dreams Rock Band Website](SM_agents.jpg) | ![Tony's Pizza Palace Restaurant](SM_agents.jpg) |
| Complete e-commerce platform for sustainable products with shopping cart, payment integration, and eco-friendly product catalog | Dynamic band website featuring music player, tour dates, photo gallery, and fan merchandise store with social media integration | Restaurant website with online ordering system, menu gallery, table reservations, and customer reviews integration |
| **🌐 Visit Site** \| **📂 Source Code** | **🌐 Visit Site** \| **📂 Source Code** | **🌐 Visit Site** \| **📂 Source Code** |
| *🌱 500+ eco-friendly products* | *🎵 10K+ monthly visitors* | *🍕 200+ orders per week* |

| HealthFirst Medical Center | Digital Learning Hub | StartupForge - Business Incubator |
|:---:|:---:|:---:|
| ![HealthFirst Medical Center](SM_agents.jpg) | ![Digital Learning Hub](SM_agents.jpg) | ![StartupForge Business Incubator](SM_agents.jpg) |
| Professional medical center website with appointment booking, doctor profiles, patient portal, and health resources section | Educational platform featuring course catalog, student dashboard, progress tracking, and interactive learning modules | Corporate website for startup incubator with portfolio showcase, investor information, application portal, and success stories |
| **🌐 Visit Site** \| **📂 Source Code** | **🌐 Visit Site** \| **📂 Source Code** | **🌐 Visit Site** \| **📂 Source Code** |
| *👨‍⚕️ 50+ healthcare professionals* | *📖 1000+ students enrolled* | *🚀 100+ startups launched* |

## 📺 View my YouTube videos.
- coming soon

---

## 🤳 Connect with me:

[![YouTube](https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg)][youtube]
[![Twitter](https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg)][twitter]
[![LinkedIn](https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg)][linkedin]
[![Instagram](https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg)][instagram]
-->

[twitter]: https://twitter.com/TeachingTheMachine
[youtube]: https://www.youtube.com/c/TeachingTheMachine
[instagram]: https://www.instagram.com/TeachingTheMachine/
[linkedin]: https://linkedin.com/in/TeachingTheMachine

---

*My expertise lies in designing agent workflows, building the agents themselves, and architecting scalable data pipelines to keep up with the goldmine of information that agents can generate, analyze, and organize. They're also quite adept at customer outreach and sentiment analysis. I also dabble in AI Agent Education—from crafting snappy tutorials to explaining AgentOps and how it differs from MLOps and DevOps.*
