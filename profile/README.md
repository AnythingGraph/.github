## Hi there 👋

# AnythingGraph

AnythingGraph give your AI the right data — not all of it. 
We connect operational data into a governed graph so humans and AI can act on business reality—with control, clarity, and only the context that matters

## Product overview

Most organizations already have the data they need; it is just spread across tools, folders, and teams. AnythingGraph is a **context layer**: you define the record types and relationships that match how your business actually works, bring data in through uploads or webhooks, and see how accounts, people, orders, and documents link together on a visual graph.

You can install a ready-made playbook, connect your own AI agents, and let them work with linked business data — only the part you choose, with access rules built in.


## Who it is for

- **Operations and business users** who need structured record types (forms), relationships, and light automation without a multi-month IT project
- **Data and integration owners** who want a durable, queryable picture of entities and how they connect across sources
- **Developers and AI assistants** that need reliable APIs and MCP access to read and write the same graph agents and people see in the UI

## Problems it addresses

| Challenge | How AnythingGraph helps |
|-----------|-------------------------|
| Data stuck in PDFs, email, and spreadsheets | Ingest and map into shared **record types** with validation |
| “How is this customer related to that order?” is hard to answer | Model **relationships** between records and explore them visually |
| Every new source needs a custom script | **Playbooks** and **workflows** package repeatable ingest pipelines |
| Business questions wait on engineering for SQL | **Query Studio** (when RDF/SPARQL is enabled) supports natural-language exploration over the graph |

## What you can do

- **Define record types** — Schemas for invoices, accounts, employees, products, or anything specific to your domain.
- **Link records** — Connect rows across types (for example contact → account → opportunity) so navigation follows real business structure.
- **Use playbooks** — Install starter packs with record types, relationships, and workflows you can customize.
- **Ingest documents and files** — Upload or send webhooks (JSON, CSV, PDF, and more); workflows create or update rows and route exceptions to review.
- **Automate with workflows** — Trigger on upload or HTTP, validate and map fields, create relationships, and handle failures explicitly.
- **Explore the graph** — See how types and instances connect—useful for onboarding, audits, and data-quality checks.
- **Work with AI tools** — MCP integration lets agents list entities, rows, and relationships against the same data the dashboard uses.

## Typical use cases

1. **Invoice and document intake** — Pull vendor, amount, and dates from invoices into structured records; link to vendors or cost centers.
2. **Lightweight CRM** — Accounts, contacts, leads, and opportunities with clear links and ingest from spreadsheets or external systems.
3. **Operational hub** — A shared graph of corporations, people, products, or projects that other tools and automations reference.
4. **Integration landing** — Normalize webhook payloads through workflows before records spread to downstream systems.

## Playbook catalog (dashboard)

Install starter packs from **Playbooks** in the dashboard (`dashboard/backend/src/playbook/playbooks/`):

| Section | Playbooks |
|---------|-----------|
| Start here | Organizational graph, CRM relationship graph |
| Integrate data | Reference data alignment, Data quality stewardship, Identity golden record |
| Operations | Invoice records (structured), Procure to pay, Support case management |
| AI & documents | Document registry |
| Advanced | Product composition |

Each playbook includes record types, schema relationships, an ingest workflow, and MCP instructions (`playbook id` in the pack).
