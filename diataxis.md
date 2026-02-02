# Diátaxis Framework

**Status:** Draft  
**Type:** Explanation  
**Scope:** Documentation methodology

## What Is Diátaxis?

**Diátaxis** is a documentation framework that organizes technical content into four distinct types, each serving a different user need:

- **Tutorials**
- **How-To Guides**
- **Explanations**
- **Reference**

The core idea is simple:  
> Different documentation goals require different kinds of writing.

Mixing these goals leads to confusing, ineffective documentation. Diátaxis avoids this by keeping each type clearly separated.

---

## The Four Documentation Types

### Tutorials
**Purpose:** Learning  
**Audience mindset:** “I’m new — teach me.”

Tutorials are **end-to-end, guided learning experiences**. They walk the reader through a complete workflow in a structured, sequential way.

Characteristics:
- Assumes minimal prior knowledge
- Focuses on successful completion
- Explains *what to do* and *why* along the way

Example:
- Onboarding a new client
- Building a complete ETL pipeline

---

### How-To Guides
**Purpose:** Accomplishing a task  
**Audience mindset:** “I already know the basics — I just need to do this.”

How-tos are **task-focused and outcome-driven**. They solve a specific problem or show how to perform a discrete action.

Characteristics:
- Assumes some prior knowledge
- Narrow in scope
- Step-by-step, but not instructional in tone

Example:
- Troubleshoot offline agents
- Run a specific transformation step in a pipeline

---

### Explanations
**Purpose:** Understanding  
**Audience mindset:** “Help me understand how this works.”

Explanations provide **conceptual context**. They explain systems, tradeoffs, architecture, and relationships between components.

Characteristics:
- No step-by-step instructions
- Focus on *why* and *how things fit together*
- Supports tutorials and how-tos indirectly

Example:
- N-central vs N-sight
- RMM vs EDR vs MDR
- ETL pipeline architecture patterns

---

### Reference
**Purpose:** Lookup  
**Audience mindset:** “I just need the facts.”

Reference material is **authoritative, precise, and concise**. It exists to be consulted, not read end-to-end.

Characteristics:
- Structured for scanning
- Minimal narrative
- Facts, definitions, tables, codes

Example:
- Terminology glossaries
- Status codes
- Configuration options

---

## Why Use Diátaxis?

Diátaxis helps:
- Reduce confusion in documentation
- Improve usability for different reader goals
- Scale documentation across large projects
- Make documentation easier to maintain and extend

By separating concerns, documentation becomes clearer, more intentional, and more professional.

---

## How This Framework Is Used

Repositories that reference this document are intentionally structured into directories that map directly to the four Diátaxis content types.

Each directory serves a distinct purpose and should not overlap in intent with the others.

