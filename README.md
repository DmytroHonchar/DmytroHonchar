# Hi, I'm Dmytro Honchar 👋

I'm a software developer based in Liverpool. I hold bachelor's and master's degrees in law from Odesa Law Academy in Ukraine. For my MSc in Computer Science at the University of Liverpool, I built a system where five language models debate each other's answers.

I also built Manos, an AI assistant that finds local service providers and creates bookings through chat, and launched websites for two restaurant clients. I use Codex and Claude Code in my daily workflow.

I'm looking for a junior or graduate software development role in the UK, particularly in full-stack development, backend engineering or applied AI. I'm open to remote and hybrid work.

[Portfolio](https://getdima.co.uk/) · [LinkedIn](https://www.linkedin.com/in/dmytro-honchar-26b308239/)

## Selected projects

### Multi-Agent Debate Frameworks for Enhanced Truthfulness · MSc dissertation

Can five language models answer more questions correctly after debating with each other? I built a Python framework to test this on 300 MMLU-Pro questions. Each model answered independently, then reviewed the other models' anonymised answers and submitted a second answer.

The group's majority vote went from **245 to 255 correct answers out of 300** (81.7% to 85.0%). The result measures the full second round, including both peer input and the opportunity to reconsider.

The framework handles API calls, answer parsing, voting and scoring. It includes 554 automated tests and a Streamlit viewer for replaying individual debates.

[Code](https://github.com/DmytroHonchar/Dissertation-Multi-Agent-Debates) · [Results report](https://github.com/DmytroHonchar/Dissertation-Multi-Agent-Debates/blob/main/reports/main_experiment_20260923/evaluation_report.md)

### Manos · AI booking assistant

Describe a job in chat and Manos finds nearby plumbers, electricians or cleaners. You can compare providers, make a booking and check its status in the same conversation. The demo uses sample providers.

I built Manos with React, TypeScript and Supabase. Llama 3.3 70B runs through Groq and calls tools to search for providers, create bookings and check their status. Search ranks providers by how closely they match the request and how near they are to the customer.

[Code](https://github.com/DmytroHonchar/hackathonAI)

### Da Gurkha and Momo's · Live restaurant websites

I built and deployed both sites with Node.js and Express on Render. Guests can browse menus and contact either restaurant.

- **Da Gurkha** lets guests send table booking enquiries directly to the restaurant. [Live site](https://dagurkhafinedining.com/) · [Code](https://github.com/DmytroHonchar/DagGurkhaLiverpool)
- **Momo's** gives guests a choice of ordering through Foodbooking or Uber Eats. [Live site](https://momoslvp.com/) · [Code](https://github.com/DmytroHonchar/momosliverpool)

## Tools

- **Languages and web development** · Python, JavaScript, TypeScript, HTML, CSS, React, Flask, Node.js, Express
- **Data and AI** · MySQL, PostgreSQL, SQLite, Supabase, pgvector, OpenRouter, Groq, Ollama, PyTorch, Streamlit
- **Testing and deployment** · pytest, Git, GitHub, AWS, Heroku, Render

## Other projects

- **LunarLander** · Trained DQN and Dueling Double DQN agents in PyTorch. Both reached the solved score in evaluations across three random seeds.
- **Chess agent** · Built an agent that uses rules to shortlist legal moves, then asks a local Llama model running through Ollama to choose one.

[Code for both projects](https://github.com/DmytroHonchar/Lunar_and_chess_ML)

## Customer experience

I've spent several years working directly with guests and colleagues in Liverpool restaurants, handling requests and resolving problems during busy services.
