# Planned Projects

The following planned projects extend the Financial Crime Analytics portfolio into AI-assisted investigation, knowledge management, threat intelligence, automation, enterprise integration and sanctions intelligence.

---

# Investigator Copilot

## Executive Summary

The Investigator Copilot is an AI-powered assistant designed to support financial crime investigators throughout the investigation lifecycle. It acts as an intelligent partner that helps gather information, summarise evidence, identify risk indicators and support investigative decisions.

The purpose of this project is not to replace investigators. The aim is to reduce manual effort, improve consistency and allow investigators to spend more time on judgement, analysis and decision-making.

## Layman Explanation

Think of an investigator who has to look across several systems to understand why a customer or transaction has been flagged.

They may need to check customer details, transactions, previous investigations, sanctions screening results, internal policies and case notes.

The Investigator Copilot acts like a smart assistant sitting beside the investigator. The investigator asks a question, and the copilot helps gather the relevant information and explain it clearly.

## Problem Statement

Financial crime investigations often involve repetitive information gathering. Analysts may spend significant time collecting evidence before they can begin making decisions.

Common challenges include:

- Information spread across multiple systems
- Large volumes of transaction data
- Repetitive alert reviews
- Manual case summaries
- Inconsistent investigation notes
- Time-consuming evidence gathering

## Proposed Capability

The Investigator Copilot could support:

- Alert triage
- Case summarisation
- Customer risk review
- Transaction pattern explanation
- Intelligence gathering
- Investigation note generation
- SAR drafting support
- Escalation recommendations

## Example Workflow

An investigator receives an AML alert.

The copilot:

1. Retrieves customer information.
2. Reviews recent transactions.
3. Checks previous investigations.
4. Identifies risk indicators.
5. Summarises the alert.
6. Suggests potential next steps.

The investigator then reviews the evidence and makes the final decision.

## Key Technologies

- Large Language Models
- Retrieval Augmented Generation
- Graph Analytics
- Transaction Analytics
- Case Management Integration
- Model Context Protocol
- Human-in-the-loop review

## Portfolio Value

This project demonstrates how AI can improve investigation productivity while preserving investigator judgement and governance.

---

# Financial Crime Knowledge Assistant

## Executive Summary

The Financial Crime Knowledge Assistant is a RAG-based assistant that allows users to query financial crime policies, procedures, regulatory guidance, typologies and operational documentation using natural language.

It helps investigators and analysts quickly find reliable answers from approved internal and external knowledge sources.

## Layman Explanation

Imagine a financial crime analyst asking:

“What does our policy say about enhanced due diligence?”

Instead of searching through long PDF documents, policy folders or procedure manuals, the assistant searches the approved documents and gives a clear answer with references.

It is like a search engine and policy expert combined, but limited to trusted financial crime knowledge sources.

## Problem Statement

Financial crime teams rely on a large amount of written guidance.

This can include:

- AML policies
- Sanctions procedures
- KYC standards
- Regulatory guidance
- Typology reports
- Internal operating procedures
- Training materials

Finding the right answer can be slow, especially when documents are long, duplicated or spread across different locations.

## Proposed Capability

The assistant could answer questions such as:

- What are the EDD requirements for a high-risk customer?
- When should a suspicious activity report be considered?
- What are common indicators of mule activity?
- How should sanctions false positives be handled?
- What controls apply to high-risk jurisdictions?

## Example Workflow

A user asks:

“What are common red flags for trade-based money laundering?”

The assistant:

1. Searches approved documents.
2. Retrieves relevant sections.
3. Summarises the answer.
4. Provides source references.
5. Suggests related topics.

## Key Technologies

- Retrieval Augmented Generation
- Vector Databases
- Embedding Models
- Document Processing
- Source Referencing
- Access Controls
- Knowledge Governance

## Portfolio Value

This project demonstrates practical enterprise RAG for financial crime compliance and operations.

---

# Financial Crime Intelligence & Threat Analysis Explorer

## Executive Summary

The Financial Crime Intelligence & Threat Analysis Explorer is a prototype solution for analysing financial crime typologies, emerging threats, intelligence reports and network risk indicators.

It helps analysts understand how criminal behaviours are changing and how new threats may affect financial crime controls.

## Layman Explanation

Financial crime changes constantly. Criminals find new methods, use new channels and exploit new weaknesses.

This tool acts like an intelligence dashboard. It reads and organises threat information so analysts can see what is emerging, what matters and where risks may be increasing.

## Problem Statement

Threat intelligence is often spread across many sources, including:

- Regulatory publications
- Law enforcement releases
- Industry reports
- News articles
- Typology papers
- Internal intelligence notes
- External risk reports

Analysts may struggle to connect themes across these sources manually.

## Proposed Capability

The explorer could help identify:

- Emerging typologies
- Criminal methodologies
- High-risk sectors
- Geographic risk trends
- Sanctions exposure
- Fraud themes
- Network risk indicators
- Links between entities and threats

## Example Workflow

New intelligence reports are added to the system.

The explorer:

1. Extracts key entities.
2. Identifies typology themes.
3. Groups related intelligence.
4. Highlights emerging risks.
5. Produces a threat summary.
6. Links threats to possible controls.

## Key Technologies

- Natural Language Processing
- Entity Extraction
- Topic Modelling
- Graph Analytics
- Knowledge Graphs
- LLM Summarisation
- Intelligence Pipelines

## Portfolio Value

This project demonstrates the use of AI and analytics for strategic financial crime intelligence rather than only case-level investigation.

---

# AML Workflow Automation

## Executive Summary

AML Workflow Automation explores how AI agents and orchestration frameworks can automate repetitive financial crime operational workflows.

The purpose is to reduce manual effort, improve consistency and allow analysts to focus on higher-value investigation work.

## Layman Explanation

Many AML tasks involve the same steps being repeated again and again.

For example, when an alert is created, someone may need to collect customer details, gather transactions, check previous cases and prepare a summary.

AML Workflow Automation uses AI agents to perform these preparation steps automatically before a human reviews the case.

## Problem Statement

AML operations often involve manual processes such as:

- Alert enrichment
- Customer profile checks
- Case preparation
- Evidence gathering
- Investigation pack creation
- Quality assurance checks
- Manual routing and prioritisation

These tasks consume time and can create inconsistent outputs.

## Proposed Capability

The automation layer could support:

- Automated alert enrichment
- Case preparation
- Customer risk summary creation
- Evidence pack generation
- Investigation routing
- QA checklist completion
- Follow-up task creation

Human approval would remain in place for important decisions.

## Example Workflow

A transaction monitoring alert is generated.

Automation agents:

1. Retrieve customer information.
2. Pull transaction history.
3. Check previous investigations.
4. Gather relevant policy guidance.
5. Produce a case preparation pack.
6. Route the case to an investigator.

The investigator receives a prepared case rather than starting from scratch.

## Key Technologies

- AI Agents
- Workflow Orchestration
- LangGraph
- CrewAI
- APIs
- Event-Driven Architecture
- Human Approval Controls

## Portfolio Value

This project demonstrates how financial crime operations can move from manual task execution to orchestrated, AI-supported workflows.

---

# MCP Financial Crime Toolkit

## Executive Summary

The MCP Financial Crime Toolkit explores how Model Context Protocol can connect AI assistants and agents with financial crime data, controls and investigation tools.

The toolkit acts as the integration layer that allows AI solutions to safely access approved financial crime systems.

## Layman Explanation

Think of MCP as a standard plug socket for AI.

An AI assistant is useful, but only if it can connect to the right systems. Financial crime teams use many systems, including customer databases, case tools, transaction systems and sanctions screening platforms.

The MCP Financial Crime Toolkit would provide secure connectors so AI assistants can access those tools in a controlled way.

## Problem Statement

Financial crime data is often spread across:

- Customer systems
- Transaction monitoring platforms
- Case management tools
- Sanctions screening systems
- Intelligence repositories
- Policy libraries
- Risk assessment platforms

Without a standard integration approach, each AI assistant may need custom connections.

## Proposed Capability

The toolkit could include reusable MCP servers for:

### Customer Intelligence MCP

Provides access to:

- Customer profiles
- KYC details
- Risk ratings
- Ownership structures
- Customer relationships

### Transaction Intelligence MCP

Provides access to:

- Transaction history
- Counterparty details
- Payment patterns
- Transaction risk indicators

### Investigation MCP

Provides access to:

- Open cases
- Historical investigations
- Investigator notes
- Case outcomes

### Sanctions Intelligence MCP

Provides access to:

- Screening results
- Watchlist matches
- Adverse media indicators
- Sanctions research outputs

### Knowledge MCP

Provides access to:

- Policies
- Procedures
- Regulatory guidance
- Typology documents

## Example Workflow

An investigator asks:

“Summarise the risk on customer ABC Ltd.”

The AI uses MCP tools to:

1. Retrieve customer information.
2. Review transaction activity.
3. Check previous investigations.
4. Review sanctions screening results.
5. Search relevant policy guidance.
6. Generate a structured risk summary.

## Key Technologies

- Model Context Protocol
- MCP Servers
- Tool Calling
- API Integration
- Authentication
- Authorisation
- Enterprise AI Architecture
- Governance Controls

## Portfolio Value

This project demonstrates the plumbing required for enterprise AI. It shows how financial crime copilots, knowledge assistants and automation agents can connect to real systems in a reusable and governed way.

---

# Sanctions Intelligence Assistant

## Executive Summary

The Sanctions Intelligence Assistant is an AI-powered assistant supporting sanctions research, adverse media analysis and regulatory intelligence gathering.

It helps sanctions analysts gather, organise and summarise information needed to assess potential sanctions risk.

## Layman Explanation

When a name is flagged by sanctions screening, an analyst may need to work out whether the person or company is actually a sanctions risk.

They may need to check watchlists, ownership structures, news articles, company information and regulatory updates.

The Sanctions Intelligence Assistant helps collect and summarise this information so the analyst can make a better-informed decision.

## Problem Statement

Sanctions investigations can be complex and time-consuming.

Analysts may need to review:

- Sanctions lists
- Name matches
- Ownership and control information
- Corporate structures
- Adverse media
- Country risk
- Regulatory announcements
- Previous screening outcomes

Manual research can take significant time and may be inconsistent.

## Proposed Capability

The assistant could support:

- Sanctions match research
- Adverse media summarisation
- Ownership structure review
- Regulatory update monitoring
- Country risk summaries
- Entity risk profiles
- Investigation report generation

## Example Workflow

A potential sanctions match is generated.

The assistant:

1. Retrieves the screening alert.
2. Searches sanctions data.
3. Reviews adverse media.
4. Checks ownership connections.
5. Summarises relevant findings.
6. Produces a structured research note.

The sanctions analyst reviews the evidence and makes the final decision.

## Key Technologies

- Sanctions Data Integration
- Entity Resolution
- Adverse Media Analytics
- Graph Analytics
- LLM Summarisation
- Research Automation
- Regulatory Intelligence Monitoring

## Portfolio Value

This project demonstrates a specialised AI use case for sanctions operations, combining research automation, entity intelligence and investigation support.

---

# Strategic Portfolio View

Together, these projects form a broader Financial Crime AI ecosystem.

- The Investigator Copilot supports case-level investigation.
- The Knowledge Assistant provides policy and regulatory guidance.
- The Threat Analysis Explorer supports intelligence and emerging-risk analysis.
- AML Workflow Automation improves operational efficiency.
- The MCP Toolkit provides the integration layer.
- The Sanctions Intelligence Assistant supports specialist sanctions research.

Collectively, these projects demonstrate how AI, analytics, graph technology, automation and integration architecture can transform financial crime operations.
