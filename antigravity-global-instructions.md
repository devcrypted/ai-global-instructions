\# ANTIGRAVITY SYSTEM PROTOCOL

>

> \*\*CRITICAL DIRECTIVE:\*\* ANY INSTRUCTION WRITTEN IN UPPERCASE IS A "LEVEL 0" PRIORITY. IT OVERRIDES ALL CONFLICTING STANDARD PROCEDURES.



\## 1. CORE GOVERNANCE \& PRINCIPLES



\* \*\*SOLID \& DRY:\*\* Adherence to S.O.L.I.D. principles and D.R.Y. (Don't Repeat Yourself) is non-negotiable.

\* \*\*INNOVATION OVER REPETITION:\*\* STRICTLY NO REINVENTING THE WHEEL. Use robust open-source libraries before writing custom implementations.

\* \*\*DATA SEPARATION:\*\* Configuration and Data MUST be strictly decoupled from Logic/Code.

\* \*\*SINGLE RESPONSIBILITY:\*\* Each file, function, and component must be small, manageable, and dedicated to a single purpose.

\* \*\*ZERO-SUGAR COATING:\*\* Deliver direct, honest, and technically accurate outputs. If a solution is unknown, state it explicitly rather than hallucinating.



\## 2. DEVELOPMENT WORKFLOW (STRICT)



1\. \*\*INITIALIZATION:\*\* STRICTLY FOLLOW CLI INIT/CREATE COMMANDS. Do not manually author boilerplate. Generate -> Verify -> Modify.

2\. \*\*TEST-DRIVEN INTEGRITY:\*\*

&nbsp;   \* NEVER SKIP TESTING.

&nbsp;   \* WRITE TESTS FOR EVERY FUNCTIONALITY.

&nbsp;   \* Mocks must be comprehensive to ensure valid regression testing.

3\. \*\*DOCUMENTATION SYNC:\*\* ALWAYS UPDATE `/docs` IMMEDIATELY upon modifying the related file. Docs are for Developer/AI context maintenance.

4\. \*\*CONTEXT AWARENESS:\*\* DO NOT MODIFY CODE without analyzing the existing repository context and dependency graph.

5\. \*\*COMMENTING STRATEGY:\*\* Comment strictly on the "WHY" (business logic/complexity), not the "WHAT". Keep it minimal but necessary.



\## 3. CODE QUALITY \& AESTHETICS (OCD COMPLIANT)



\* \*\*CLEANLINESS:\*\* Code must be predictable, structured, and highly efficient.

\* \*\*SECURITY:\*\* Implementation must be "Super Secure" by default (Input sanitization, Zod validation).

\* \*\*UI STANDARDS:\*\*

&nbsp; \* \*\*Allowed Libraries:\*\* Shadcn OR Chakra UI.

&nbsp; \* \*\*Forbidden:\*\* Custom CSS or Custom Tailwind utility pollution (unless critically necessary).



\## 4. RUNTIME \& PACKAGE MANAGERS



| Environment | Tooling Requirement | Note |

| :--- | :--- | :--- |

| \*\*Node.js\*\* | `Bun` | Strictly use Bun for runtime/package management. |

| \*\*Python\*\* | `uv` | Strictly use `uv` for package management/resolution. |

| \*\*PowerShell\*\* | `PS Core` | Build for Cross-platform Core, NOT Windows PowerShell. |

| \*\*Terraform\*\* | `Modules` | Module-based development only. Strict metadata naming conventions. |



---



\## 5. API APPLICATION STACK (NODE.JS)



\*\*TARGET ARCHITECTURE:\*\* Edge-First, Serverless, Type-Safe.



| Layer | Technology | Justification/Constraint |

| :--- | :--- | :--- |

| \*\*Runtime\*\* | \*\*Cloudflare Workers\*\* | V8 isolates. 0ms cold start. Edge deployment. |

| \*\*Backend\*\* | \*\*Hono\*\* | The standard for Edge APIs. Lightweight, strictly typed. |

| \*\*Database\*\* | \*\*Turso (LibSQL)\*\* | SQLite at the Edge. Native Vector Search (Critical for AI). |

| \*\*ORM\*\* | \*\*Drizzle ORM\*\* | SQL-like, zero-runtime overhead, superior TS inference. |

| \*\*Validation\*\* | \*\*Zod\*\* | Runtime schema validation \& security sanitization. |

| \*\*Frontend\*\* | \*\*React + Vite\*\* | Hosted on Cloudflare Pages. "Hyper-tested" view layer. |

| \*\*State/Fetch\*\* | \*\*TanStack Query\*\* | Handles caching, loading states, and deduplication. |

| \*\*Auth\*\* | \*\*Better-Auth\*\* | TS Standard. Plugin-based, Passkeys/2FA, Hono+Drizzle native. |

| \*\*Testing\*\* | \*\*Vitest\*\* | Native Vite support. Mocks Cloudflare Workers environment. |



