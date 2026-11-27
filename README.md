## Hi, I'm Dmytro Honchar

I'm a software developer based in Liverpool. I build web applications with Python and JavaScript. My recent work includes an AI booking concierge, a Python framework for evaluating language models and websites for restaurant clients.

I'm looking for junior and graduate software roles across the UK, including Manchester, in Python, full-stack or applied AI development, and I'm open to remote or hybrid work.

[Portfolio](https://getdima.co.uk) · [LinkedIn](https://www.linkedin.com/in/dmytro-honchar-26b308239/)

**Background:** I studied Computer Science at the University of Liverpool for my MSc (2025–2026). I also hold bachelor's and master's degrees in law, and I spent several years working in customer-facing hospitality.

**Main tools:** Python · TypeScript · JavaScript · React · Node.js/Express · SQLite · PostgreSQL (Supabase) · pytest · Streamlit · LLM APIs (OpenRouter, Groq)

---

### Multi-Agent Debate Frameworks for Enhanced Truthfulness (MSc dissertation)

I built a Python pipeline to compare majority-vote accuracy before and after five language models reviewed one another's answers. Each model first answered 300 MMLU-Pro questions alone, then answered again after seeing the others' anonymous answers. The pipeline handles the API calls, answer parsing, voting, storage and offline scoring against a separate answer key. It has 554 automated tests.

Group accuracy rose from 81.7% to 85.0% on the 300 questions. Round two also gives every model a second attempt, so the gain reflects the whole two-round system, not debate alone.

[Code](https://github.com/DmytroHonchar/Dissertation-Multi-Agent-Debates) · [Results report](https://github.com/DmytroHonchar/Dissertation-Multi-Agent-Debates/blob/main/reports/main_experiment_20260923/evaluation_report.md)

### Manos: AI concierge for local services

Booking a plumber, electrician or cleaner usually means comparing listings and chasing replies. In Manos, you describe the job in a chat. The concierge (Llama 3.3 70B on Groq) uses tool calls to search providers, show details, create a booking and check its status. Search ranks providers by pgvector similarity and distance. I built it with React, TypeScript and Supabase (Postgres, auth and edge functions). The providers are demo data.

[Code](https://github.com/DmytroHonchar/hackathonAI)

### Restaurant websites: Da Gurkha and Momo's

I built and deployed two live restaurant websites in the Liverpool area with Node.js and Express, hosted on Render with custom domains.

- **Da Gurkha:** a QR ordering flow with email notifications. A table QR code opens a time-limited order page, and each order is emailed to the restaurant, with an optional confirmation for the guest. The site also takes table booking requests. [Live site](https://dagurkhafinedining.com) · [Code](https://github.com/DmytroHonchar/DagGurkhaLiverpool)
- **Momo's:** menu, contact form and a delivery page that links to Foodbooking and Uber Eats. [Live site](https://momoslvp.com) · [Code](https://github.com/DmytroHonchar/momosliverpool)

### Other projects

From one reinforcement learning module ([Code](https://github.com/DmytroHonchar/Lunar_and_chess_ML)):

- **LunarLander-v3:** DQN and Dueling Double DQN agents in PyTorch. Both reach the "solved" score in greedy evaluation on three seeds.
- **Chess agent:** rules reduce each position to a short list of candidate moves, and a local LLM (Llama 3.1 8B through Ollama) picks one.
