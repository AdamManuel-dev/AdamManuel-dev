# Hi there 👋, I'm just a dev that likes to build


- 🔭 Current Projects
  - Working at [Snappy](https://www.snappy.com/)
  - Building [Synq](https://getsynq.io)
  - New Blog (Moving from unofficial Notion API to the official Notion API)
  - Research Assistant with ChatGPT (Aggregate interesting, well sourced, high reputation academic papers weekly into a report)
  - Generating Changelog generation through Git commits and LLMs
  - Automatic data schema normalization using Agentic LLM Agents, and Heuristics
  - Autonomous Browser Agents (personal assistant and background development qa/test agent)
- 🛠️ Useful Tools I've built/expanded on
  - [Realtime LinkedIn Job Notifications](https://github.com/AdamManuel-dev/LinkedInNotifications)
  - [Planning Poker Webapp](https://github.com/AdamManuel-dev/planning-poker)
  - [Testing Agent](https://github.com/AdamManuel-dev/AutonomousTestingAgent)
  - [Personal Asst Agent](https://github.com/AdamManuel-dev/personal-assistant-agent)
  - [System for generating OpenAPI JSON through Typescript interfaces and OAS generating functions](https://github.com/AdamManuel-dev/OAS-DSL)
  - [Generating commit messages using LLM and git diff](https://github.com/AdamManuel-dev/ai-commit-command)
- 🌌 Checkout my personal spaces
  - [Personal Blog](https://blog.manuel.dev)
  - [Public Resume](https://adam.manuel.dev)
 
----

Based on your GitHub repositories, here's a comprehensive summary:

## Repository Overview
You have 46 public repositories spanning various technologies and domains. Your work demonstrates a strong focus on modern web development, AI/autonomous agents, and developer tooling.

## Key Technology Areas

### AI & Autonomous Agents (8 repos)
- **ai-agent-react-native**: Mobile UI for agent orchestration
- **ai-news-curator**: AI-powered news curation agent
- **explorer-browser-agent**: Browser exploration automation
- **AutonomousTestingAgent**: Automated testing that integrates with Cursor
- **ai-doc-storage-mcp**: AI-first document storage for coding agents
- **claude-code-** projects: Multiple extensions and orchestration tools for Claude Code
- **task-kanban-mcp**: Task management system for AI-driven development

### Web Development Frameworks (12 repos)
- **Svelte/Sapper**: Multiple templates combining Svelte with Tailwind, TypeScript, and various build tools
- **React/Next.js**: Templates with Emotion, Tailwind, Storybook, and TypeScript
- **FastAPI**: Python templates with PyTest and GraphQL support

### Developer Tools & CLIs (8 repos)
- **JSON-Schema-CLI**: Schema generation and version control
- **typescript-cli**: TypeScript utility CLI
- **ai-commit-command**: AI-powered conventional commit message generator
- **Backup-CosmosDB-Script**: Database backup automation
- **LinkedInNotifications**: Job notification automation

### Component Libraries (4 repos)
- **svelte-intl-phone-input**: International phone input component
- **svelte-dragdroplist**: Sortable list component
- **Deltable_CMS_Widgets**: CMS widget collection
- **sveltestrap**: Bootstrap 4 Svelte components

### Personal/Portfolio (5 repos)
- **Portfolio** & **PortfolioDashboard**: Personal website and editor
- **Resume**: Tailwind-based resume template
- **blog** & **next-notion-blog**: Blog implementations
- **AdamManuel-dev**: GitHub profile repository

### API & Backend (9 repos)
- Various GraphQL implementations (TypeGraphQL-Azure, LinkGraph)
- REST API tools (apollo-link-rest)
- Azure Functions templates
- OpenAPI definition generator (OAS-DSL)

## Recent Activity
Your most recent projects (2024-2025) show a strong focus on:
- AI agent development and orchestration
- Claude Code extensions and automation
- Task management systems for AI-assisted development
- Developer productivity tools

## Notable Patterns
- Heavy use of TypeScript across projects
- Preference for modern frameworks (Svelte, React, Next.js)
- Integration with cloud services (Azure, Vercel)
- Focus on developer experience and automation
- Growing emphasis on AI/LLM integration in development workflows

Your repository collection showcases a developer who stays current with modern technologies while building practical tools for productivity and automation, with a recent pivot toward AI-enhanced development workflows.

----
 
# Currently building a few different AI Agents. Here is the current status of each of them

## 📊 Project Progress Summary

### Development Status Overview
- **🟢 Production Ready**: MCP Task-Kanban (85%), Central Multi-Agent Orchestration (85%), Test Running Agent (95%)
- **🟡 Active Development**: Personal Assistant System (69.7%), Browser Explorer (70%), AI News Curator (34.6%)
- **🔴 Planning Phase**: Dev Orchestrator (0%), Doc Storage MCP (0%)
- **✅ Individual Agents**: 5 personal assistant agents fully production-ready (100%+)
- **⚠️ Core Systems**: Personal assistant orchestration needs completion (22.38%)

### Completion Statistics
| Agent System | Progress | Status | Key Achievements |
|--------------|----------|--------|------------------|
| **MCP Task-Kanban** | 85% | 🟢 Production | 500+ tasks complete, 68 API endpoints |
| **Central Orchestration** | 85% | 🟢 Production | All high-priority features complete |
| **Browser Explorer** | 70% | 🟡 Development | Infrastructure done, AI integration pending |
| **AI News Curator** | 34.6% | 🟡 Development | Backend complete, ML features pending |
| **Personal Assistant** | 69.7% | 🟡 Development | 11 agents, 5 production-ready, orchestration pending |
| **Test Running Agent** | 95% | 🟢 Production | Near production-ready, comprehensive feature set |
| **Dev Orchestrator** | 0% | 🔴 Planning | 229 tasks scoped, architecture designed |
| **Doc Storage MCP** | 0% | 🔴 Planning | 518 tasks scoped, enterprise architecture |

## 🏗️ Agent Categories

### 🤖 Development & Code Intelligence Agents

#### [AI News Curator Agent](./ai-news-curator/) - **34.6% Complete**
**Purpose**: Intelligent content discovery and organization for AI/ML topics
- **Discovery**: Aggregates content from 100+ sources across the web
- **Analysis**: 95% accuracy in intelligent tagging and content ranking
- **Insights**: Real-time trend analysis of AI/ML discourse
- **Status**: 64 of 185 tasks complete, infrastructure & core backend done
- **Personalization**: Custom recommendations based on user preferences
- **Tech Stack**: Node.js, TypeScript, PostgreSQL, Redis, Pinecone
- **Key Features**:
  - Multi-source content aggregation (blogs, research repositories, news sites)
  - Hierarchical tag assignment across topic, difficulty, and use case taxonomies
  - Advanced scoring based on relevance, quality, recency, and community engagement
  - Comprehensive monitoring with Prometheus and Grafana
  - Docker deployment with Kubernetes support

#### [Browser Explorer Agent](./browser-explorer/) - **70% Complete**
**Purpose**: AI-powered web browsing and automated test generation
- **Intelligent Crawling**: Systematic website exploration with breadth-first search
- **AI Element Detection**: Hybrid AI + traditional detection for 25+ element types
- **Test Generation**: Automatic Playwright/Cypress/Puppeteer test suite creation
- **Enterprise Features**: Multi-strategy authentication, stealth mode, CAPTCHA handling
- **Tech Stack**: TypeScript, Playwright, Redis, PostgreSQL, Docker
- **Status**: Infrastructure complete, 30% critical AI components remaining
- **Key Features**:
  - Complete infrastructure for crawling and test generation
  - Page Object Model with clean, maintainable test structure
  - Multi-framework support (Playwright, Cypress, Puppeteer)
  - Distributed crawling with Redis-based queue system
  - Advanced anti-bot detection evasion

#### [Central Multi-Agent Orchestration System](./central-multi-agent-orchestration/) - **85% Complete**
**Purpose**: Scalable platform for managing and coordinating multiple AI agents
- **Dynamic Management**: Register, discover, and manage agents at runtime
- **Intelligent Routing**: Semantic search and capability-based agent discovery
- **Workflow Orchestration**: Execute complex multi-agent workflows
- **Enterprise Security**: JWT authentication, RBAC, comprehensive audit logging
- **Tech Stack**: Node.js, TypeScript, Redis, PostgreSQL, WebSocket
- **Status**: High priority 100% complete, medium priority 90% complete
- **Key Features**:
  - Real-time communication with WebSocket and REST API support
  - Multi-tenant support with isolated execution environments
  - Production observability with distributed tracing and metrics
  - Comprehensive API for agent registration and workflow management
  - Kubernetes deployment with auto-scaling

#### [Autonomous Development Pipeline (Dev Orchestrator)](./dev-orchestrator/) - **0% Complete**
**Purpose**: Revolutionary 3-agent system for symbiotic human-AI development
- **Master Orchestrator**: Central intelligence for planning and task routing
- **Development & Quality Agent**: Hybrid human-AI development environment
- **Operations & Security**: Automated git operations and security enforcement
- **Intelligent Orchestration**: 25+ orchestration patterns for different scenarios
- **Tech Stack**: TypeScript, Mastra Framework, Task-Kanban-MCP, Cursor IDE
- **Status**: 229 total tasks planned, foundation phase ready to start
- **Key Features**:
  - 10x faster development velocity with 70% cost reduction
  - Seamless integration with Cursor IDE for enhanced development
  - Multiple orchestration patterns (Sequential Quality Gate, Parallel Quality Check, Fail-Fast)
  - Comprehensive quality pipeline with multi-layer validation
  - Real-time collaboration between human developers and AI agents

#### [Task-Kanban-MCP](./mcp-kanban/) - **85% Complete**
**Purpose**: Headless kanban system designed specifically for AI coding agents
- **Agent-First Design**: Optimizes context windows for AI agents
- **Multi-Agent Coordination**: Prevents conflicts and enables collaboration
- **Task Isolation**: Each task contains complete context for autonomous execution
- **MCP Integration**: Direct integration with Claude Code and other MCP-compatible agents
- **Tech Stack**: Node.js, TypeScript, MCP Protocol, WebSocket
- **Key Features**:
  - Context window optimization for AI agents (50k token tasks)
  - Exclusive task locking and dependency management
  - Real-time collaboration with WebSocket events
  - Agent-optimized task structure with complete context
  - CLI for human supervisors with monitoring capabilities

### 🧪 Testing & Quality Assurance Agents

#### [Test Running Agent](./test-running-agent/) - **95% Complete**
**Purpose**: Intelligent automated test runner with coverage-driven optimization
- **Smart Execution**: Coverage-driven test prioritization and selection
- **Framework Support**: Jest, Cypress, Storybook, Postman, Stagehand
- **Quality Monitoring**: Comprehensive coverage tracking and complexity analysis
- **Development Integration**: Real-time Cursor IDE integration via WebSocket and MCP
- **Tech Stack**: Node.js, TypeScript, Multiple testing frameworks
- **Status**: Near production-ready with comprehensive feature implementation, minor polish needed
- **Key Features**:
  - Complete React debug UI with real-time monitoring
  - Intelligent test selection based on code coverage and critical paths
  - Multi-framework support with parallel execution
  - Extensive integrations (GitHub, JIRA, Git, Environment checks)
  - Advanced analytics with Sentry and PostHog integration

### 📋 Personal Productivity Agents

#### [Personal Assistant Agent System](./personal-asst-agent/) - **69.7% Complete**
**Purpose**: Comprehensive multi-agent system for personal and professional productivity
- **11 Specialized Agents**: Calendar, Gmail, Todo, Weather, Stock, News, etc.
- **Real-time Monitoring**: Interactive debug UI with React and shadcn/ui
- **Natural Language Processing**: Sophisticated NLP for task creation and management
- **Comprehensive Integration**: Gmail, Google Calendar, Notion, financial services
- **Tech Stack**: TypeScript, React, Node.js, Multiple APIs
- **Status**: 5 agents production-ready (100%+), 6 in development (22-86%), orchestration system needs completion
- **Included Agents**:
  - **Calendar Agent** (76.19% coverage): Schedule management and availability
  - **Gmail Agent** (56.41% coverage): Email automation with AI summaries
  - **Todo Agent** (86.3% coverage): NLP-powered task management
  - **Stock Agent** (100%+ coverage): Market analysis with Alpaca integration
  - **Weather Agent** (58.62% coverage): Enhanced weather forecasting
  - **News Agent** (17.77% coverage): AI/LLM news aggregation (LEGACY)
  - **Research Agent** (100%+ coverage): Multi-LLM research capabilities
  - **Financial Agent** (100%+ coverage): Personal finance management with Plaid
  - **Web Analysis Agent** (63.57% coverage): Web scraping with Stagehand
  - **LLM News Agent** (100% coverage): LLM-specific news tracking
  - **Orchestrator Agent** (22.38% coverage): Central coordination

### 📚 Knowledge & Document Management Agents

#### [AI-First Document Storage MCP](./doc-storage-mcp/) - **0% Complete**
**Purpose**: Next-generation document management designed for autonomous coding agents
- **Semantic Understanding**: AI-native storage that understands code relationships
- **Chain of Thought**: Complete reasoning trace for transparent AI decisions
- **Multi-Agent Collaboration**: Shared context and knowledge between agents
- **Real-time Intelligence**: Proactive code analysis and pattern recognition
- **Tech Stack**: Node.js, TypeScript, Weaviate (Vector DB), Mastra Framework
- **Status**: 518 comprehensive tasks planned, enterprise-grade implementation scope
- **Key Features**:
  - Semantic code search beyond keyword matching
  - Intelligent refactoring with semantic-preserving transformations
  - Framework-specific intelligence (React, Vue, Angular, Node.js)
  - Sub-100ms response times with enterprise-grade security
  - Multi-tenant isolation with cryptographic protection

## 🔄 Agent Interconnectivity

### Integration Patterns

#### MCP (Model Context Protocol) Integration
- **Primary Agents**: Task-Kanban-MCP, Test Running Agent, Doc Storage MCP
- **Benefits**: Direct integration with Claude, Cursor, and other MCP-compatible tools
- **Use Cases**: Real-time development assistance, automated testing, knowledge management

#### WebSocket Real-time Communication
- **Supported Agents**: Central Orchestration, Personal Assistant System, Test Runner
- **Benefits**: Live updates, real-time collaboration, instant feedback
- **Use Cases**: Multi-agent coordination, progress monitoring, development workflow

#### RESTful API Orchestration
- **Universal Support**: All agents provide comprehensive REST APIs
- **Benefits**: Easy integration, standard protocols, scalable architecture
- **Use Cases**: Cross-agent communication, external tool integration, enterprise workflows

### Collaborative Workflows

#### Development Workflow
```
Dev Orchestrator → Task-Kanban-MCP → Test Runner → Doc Storage
     ↓                   ↓                ↓            ↓
Intelligent       Context-Aware     Smart Test    Knowledge
Planning          Task Management   Execution     Management
```

#### Research & Analysis Workflow
```
Browser Explorer → AI News Curator → Personal Assistant → Doc Storage
       ↓                 ↓                  ↓              ↓
  Web Crawling      Content Analysis   Knowledge Synthesis  Storage
```

#### Multi-Agent Coordination
```
Central Orchestration System
         ↓
┌────────┼────────┬────────┬────────┐
│        │        │        │        │
Dev    Test    Personal  Browser  Document
Agents Runner  Assistant Explorer Storage
```

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- Docker and Docker Compose
- Git
- API keys for various services (see individual agent documentation)

### Quick Setup
```bash
# Clone the repository
git clone <repository-url>
cd Agents

# Choose an agent to start with
cd <agent-directory>

# Install dependencies
npm install

# Configure environment
cp .env.example .env
# Edit .env with your settings

# Start the agent
npm start
```

### Recommended Starting Points

#### For Development Teams
1. **Dev Orchestrator** - Start with autonomous development pipeline
2. **Task-Kanban-MCP** - Add intelligent task management
3. **Doc Storage MCP** - Add intelligent knowledge management

#### For Personal Productivity
1. **Personal Assistant System** - Begin with todo and calendar agents
   - **Calendar Agent** - Schedule management and availability tracking
   - **Gmail Agent** - Email automation and AI-powered summaries
   - **Todo Agent** - Task management with natural language processing
   - **Weather Agent** - Weather information and forecasting
   - **Stock Agent** - Market analysis and portfolio tracking
   - **Research Agent** - Deep research and multi-LLM analysis
   - **Notion Agent** - Workspace integration and knowledge management
   - **Financial Agent** - Personal finance management and budgeting
   - **Web Analysis Agent** - Web scraping and content analysis
   - **LLM News Agent** - AI/ML news aggregation and curation
   - **Macros Agent** - Nutrition tracking and meal planning
   - **News Agent** - General news aggregation and analysis
2. **Browser Explorer** - Add web automation capabilities
3. **AI News Curator** - Stay updated with AI/ML developments

#### For Enterprise Integration
1. **Central Multi-Agent Orchestration** - Start with agent coordination platform
2. **Doc Storage MCP** - Add intelligent knowledge management
3. **Research Agent** - Deep research and multi-LLM analysis
4. **Financial Agent** - Store the research into sharable knowledge base

## 📊 Agent Comparison Matrix

| Agent | Purpose | Complexity | Coverage | Integration | Status |
|-------|---------|------------|----------|-------------|---------|
| AI News Curator | Content Discovery | Medium | 34.6% | REST/Docker | Development |
| Browser Explorer | Web Automation | High | 70% | MCP/WebSocket | Development |
| Central Orchestration | Agent Coordination | High | 85% | REST/WebSocket | Production |
| Dev Orchestrator | Development Pipeline | Very High | 0% | MCP/IDE | Planning |
| Task-Kanban-MCP | Task Management | Medium | 85% | MCP | Production |
| Personal Assistant | Productivity | Medium | 69.7% | REST/WebSocket | Development |
| Test Runner | Testing Automation | Medium | 95% | MCP/WebSocket | Production |
| Doc Storage MCP | Knowledge Management | High | 0% | MCP | Planning |


📫 Please reach me at adam@manuel.dev
