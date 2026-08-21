# Ashutosh Suman

Product Lead — UX & Web Experience at Detect Technologies (officially titled Software Engineer). Ex-founder, twice. I build products end-to-end using AI-assisted development, and I make the product and architecture decisions myself.

Most people landing here are evaluating whether I can actually build the things I claim to. So — plainly:

### The real one

**[dhandost](https://github.com/ashutoshsuman/dhandost)** — an AI personal-finance decision coach for Indian salaried professionals. ~570 commits, multi-user, running against real transaction data.

Its central design decision is a constraint: **the language model proposes strategy in words, but deterministic TypeScript computes every rupee the user sees.** A hallucinated number in a finance product isn't a bad answer — it's real financial harm. So I removed the model from the arithmetic path structurally rather than hoping it behaves. A separate code-level layer strips named financial products from output, because a system prompt is a request and a code path is a guarantee.

React/Tailwind · Supabase (Postgres, edge functions, RLS) · OpenAI · built with Lovable.
[Try it live →](https://dhandost.lovable.app/) · [Read the case study →](https://ashutoshsuman.dev/dhandost/)

### Learning projects

These are exercises, not production software, and I'd rather label them that way than let you find out.

- **[langGraphLoanApp](https://github.com/ashutoshsuman/langGraphLoanApp)** — a LangGraph agent with typed shared state, a bounded refinement loop, and human-in-the-loop re-entry. Built to understand where agent loops need hard iteration caps.
- **[promptQualityAgent](https://github.com/ashutoshsuman/promptQualityAgent)** — a LangChain pipeline with Pydantic-structured output and `RunnableBranch` routing to an improvement chain. Built to understand why structured output is what makes conditional routing possible.
- **[RAGexp](https://github.com/ashutoshsuman/RAGexp)** — retrieval-augmented generation end to end.
- **[agentSwarm](https://github.com/ashutoshsuman/agentSwarm)** — multi-agent orchestration and task handoff.

### What I'm actually for

I'm a product person, not an engineer. I build because a spec you've implemented is a spec you understand — you find the self-transfers, the malformed UPI strings, and the failure modes that never show up in a PRD.

Case studies, including the ones where things didn't work: **[ashutoshsuman.dev](https://ashutoshsuman.dev)**

[LinkedIn](https://linkedin.com/in/ashutoshsuman) · ashutoshsuman4@gmail.com
