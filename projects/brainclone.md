# OSS Knowledge Platform (BrainClone) - Multi-Agent RAG Portal

**Duration**: June 2025 - Present (Ongoing)  
**Status**: Phase 1 Operational, Continuous Improvement  
**Role**: Tech Lead (Full-Stack & AI Platform)  
**Demo**: [Watch Demo Video](https://www.youtube.com/watch?v=ZQj75tLnvwk)

---

## Overview

OSS Knowledge Platform (BrainClone) is an organizational knowledge digitalization platform based on a multi-agent RAG portal. The system addresses critical productivity issues including 18-month onboarding time for new employees and 2-3 hour incident response times. It models company OSS system documentation, operational knowledge, and incident history using a Neo4j-based knowledge graph, implements Agentic/Graph RAG-based knowledge search, and serves as a common cognitive foundation for other AI services.

## Problem Statement

- **18-month onboarding time** for new employees to become independent
- **2-3 hour incident response times** leading to missed golden time windows
- **Tacit knowledge** trapped in individual experts' minds
- **Fragmented knowledge** across multiple systems and documents
- **No 24/7 access** to expert knowledge

## Solution Architecture

### Multi-Layered Knowledge Structure

The system integrates three complementary knowledge representation systems:

1. **Vector Database (Qdrant)**: Semantic similarity search for finding relevant documents and content
2. **Graph Database (Neo4j)**: Relationship modeling for cross-domain knowledge connections
3. **Memory System (mem0)**: User profiling and personalization for customized responses

### Agentic/Graph RAG Implementation

- **Vector Search**: Semantic similarity matching using embeddings
- **Graph Traversal**: Relationship-based knowledge discovery
- **Cross-Domain Retrieval**: Combining both approaches for comprehensive knowledge access

### Multi-Agent System

- **Intent Classification Agent**: Understands user queries and routes to appropriate agents
- **Task Planning Agent**: Breaks down complex queries into manageable steps
- **Knowledge Retrieval Agents**: Specialized agents for different knowledge domains
- **Response Generation Agent**: Synthesizes information from multiple sources

### AI-Expert Hybrid Approach

- **80% LLM Automation**: Fast, scalable knowledge graph construction
- **20% Expert Verification**: Ensures accuracy and quality
- **Continuous Learning**: System improves over time with expert feedback

## Key Features

### 1. Intent Classification & Task Planning

- Automatically classifies user intent from natural language queries
- Decomposes complex tasks into sequential steps
- Routes queries to appropriate specialized agents

### 2. Personalized Responses

- Uses mem0 for user profiling and context tracking
- Provides customized responses based on user role and history
- Learns from user interactions to improve relevance

### 3. Explanatory Search

- Transparent knowledge retrieval process
- Shows reasoning path and source attribution
- Builds user trust through explainability

### 4. 24/7 Access

- Always-available knowledge portal
- No dependency on human experts for basic queries
- Escalates complex issues to experts when needed

## Technical Implementation

### Frontend
- **Vue 3** with TypeScript
- Real-time streaming responses
- Interactive knowledge graph visualization

### Backend
- **Spring Boot** for enterprise services
- **FastAPI** for AI/ML endpoints
- Microservices architecture

### Data Layer
- **Neo4j**: Knowledge graph storage and traversal
- **Qdrant**: Vector embeddings and similarity search
- **PostgreSQL**: Traditional relational data
- **mem0**: User memory and personalization

### AI/ML Stack
- **Azure OpenAI**: GPT-4.1-mini for reasoning, text-embedding-3-large/small for embeddings
- **Custom Prompt Engineering**: Optimized prompts for intent classification and task planning
- **Function Calling**: Structured tool use for knowledge graph operations

### Infrastructure
- **Azure Kubernetes**: Container orchestration
- **ArgoCD**: GitOps-based deployment
- **Jenkins**: CI/CD pipelines
- **GitLab**: Source code management

## My Role & Contributions

As Tech Lead, I was responsible for:

1. **Architecture Design**: Designed the multi-layered knowledge structure integrating vector, graph, and memory systems
2. **System Integration**: Implemented the integration of Qdrant, Neo4j, and mem0
3. **Agent Development**: Built the multi-agent system with intent classification, task planning, and knowledge retrieval agents
4. **RAG Implementation**: Developed the Agentic/Graph RAG system combining vector search with graph traversal
5. **Personalization**: Implemented mem0-based user profiling system
6. **Production Rollout**: Led the technical implementation from PoC → Beta → Phase 1 production

## Challenges & Solutions

### Challenge 1: Integrating Multiple Knowledge Systems

**Problem**: Vector DB, Graph DB, and memory systems each have different strengths and query patterns. Integrating them into a cohesive architecture was complex.

**Solution**: Designed a unified knowledge layer that:
- Uses vector search for semantic similarity
- Uses graph traversal for relationship discovery
- Uses memory system for personalization
- Combines results intelligently based on query type

### Challenge 2: Accuracy vs. Scalability

**Problem**: Manual knowledge graph construction is accurate but doesn't scale. Automated construction is fast but may have errors.

**Solution**: Implemented AI-Expert Hybrid approach:
- 80% automated construction using LLMs
- 20% expert verification for critical nodes
- Continuous improvement through feedback loops

### Challenge 3: Reducing Onboarding Time

**Problem**: New employees take 18 months to become independent, relying heavily on senior colleagues.

**Solution**: Created 24/7 accessible knowledge portal that:
- Provides instant answers to common questions
- Shows step-by-step procedures
- Links related knowledge automatically
- Tracks learning progress

## Results & Impact

### Business Impact
- **Reduced onboarding time**: New employees become productive faster
- **Faster incident response**: Enabled golden time response (within critical time windows)
- **Expert time freed**: Experts can focus on complex issues instead of repetitive questions
- **Knowledge preservation**: Tacit knowledge is now digitized and accessible

### Technical Achievement
- Successfully executed **PoC → Beta → Phase 1** operational rollout
- Established platform as **common cognitive foundation** for other AI services
- Demonstrated **scalability** and **reliability** in production environment

### Organizational Impact
- **Digitalized tacit knowledge** into reusable assets
- **24/7 expert access** for all employees
- **Increased employee satisfaction** through easier knowledge access
- **Improved customer satisfaction** through faster issue resolution

## Technologies Used

**Frontend**: Vue 3, TypeScript  
**Backend**: Spring Boot, FastAPI, Python  
**Databases**: Neo4j (Graph DB), Qdrant (Vector DB), PostgreSQL, mem0  
**AI/ML**: Azure OpenAI (GPT-4.1-mini, text-embedding-3-large/small)  
**Infrastructure**: Azure Kubernetes, ArgoCD, Jenkins, GitLab  
**Protocols**: MCP (Model Context Protocol)

## Key Learnings

1. **Multi-Agent Systems**: Deep understanding of agent communication, task decomposition, and coordination
2. **Graph RAG**: Combining vector and graph approaches for superior knowledge retrieval
3. **Knowledge Graph Modeling**: Best practices for modeling organizational knowledge
4. **Enterprise AI Platforms**: Building production-grade AI systems with reliability and scalability
5. **Technical Leadership**: Leading complex projects from conception to production

## Future Enhancements

- A2A (Agent-to-Agent) protocol integration for external agent connectivity
- Enhanced personalization using more sophisticated memory models
- Real-time collaboration features for expert knowledge sharing
- Advanced analytics for knowledge usage patterns

---

## Links

- [Demo Video](https://www.youtube.com/watch?v=ZQj75tLnvwk)
- [Back to Portfolio](../README.md)

