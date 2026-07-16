# Hi, I'm Bruno Costa

**Backend Developer focused on Laravel · Computer Science student at Universidade Federal Fluminense (UFF), expected to graduate in December 2026**

[GitHub](https://github.com/bcosta19) · [LinkedIn](https://www.linkedin.com/in/bruno-costa-899aa01bb/) · brpassos19@gmail.com · Maricá, RJ

Backend Developer focused on PHP and Laravel, with professional experience building and maintaining public-sector applications. I work with automated testing, static analysis, relational databases and CI pipelines to deliver reliable and maintainable systems. I am also studying LLM agents and optimization algorithms.

**English: Intermediate (B1)** — comfortable reading technical documentation and communicating in writing about software development.

---

## Professional work

### Laravel & PHP

I develop and maintain Laravel applications for municipal government programs. My development approach emphasizes automated testing and continuous verification. I use PHPStan for static analysis and enforce consistent code quality across the team.

- **CNH Para Todos** — Management platform for a municipal driver's license assistance program. Multi-cycle candidate registration with document upload, administrative analysis, appeals, and Excel report generation. The test suite covers unit and feature tests with custom lean-schema test cases, including concurrency-safe CFC vacancy selection verified through `pcntl_fork`-based race condition tests.

- **Internal task management platform** — Scrum/Kanban board with drag-and-drop, sprint tracking, employee management, and analytics (Laravel, Bootstrap, Chart.js).

**How I work:**
- Every feature ships with corresponding tests — I implement, test, verify, rerun, repeat.
- Custom `TestCase` subclasses provide fast, self-contained database schemas per test class.
- Concurrency risks are exercised with real process-forking tests.
- Static analysis (PHPStan level 6) runs on every push via CI, alongside SAST scanning (Semgrep), secret detection (Gitleaks), and dependency audits.

---

## Side projects & study

### AI agents & LLMs

- **[Mini Local Document Agent](https://github.com/bcosta19/mini-agent)** — A zero-dependency Python agent framework I built to understand how tool-calling agents work from the inside. Implements a tool loop (`list_documents`, `read_document`) with interactive human-in-the-loop permission gates, workspace sandboxing with path traversal prevention, and support for both Ollama local models and OpenAI-compatible APIs. Includes multi-turn chat, verbose tracing, and structured JSON output.

### Full-stack & mobile

- **[Planner de Tarefas](https://github.com/bcosta19/planner_tarefas)** — Full-stack Flutter task management app with SQLite persistence, user authentication, task boards, and upcoming-task views.

- **[Desweb (Loja de Pesca)](https://github.com/bcosta19/desweb)** — Full-stack fishing e-commerce. Java 21 + Spring Boot 3 backend (JPA/Hibernate, MySQL) paired with a React 19 + TypeScript frontend (Vite, TanStack React Query, React Hook Form + Zod, Bootstrap 5).

- **[SDC Front (App de Caronas)](https://github.com/ES-2024-1-SDC/sdc-front)** — Flutter carpooling application frontend, developed as a team project for Software Engineering II at UFF.

- **[Onda Mídia](https://agenciaondamidia.com.br)** — Promotional website for an audio services agency. Refactored from a monolithic HTML page into a multi-page static site deployed on Cloudflare Pages, with component-based CSS architecture and schema.org structured data.

- **[Task Console](https://github.com/bcosta19/task-list)** — Keyboard-driven task queue GUI purpose-built for i3wm floating windows. Tkinter app with subtask management, segmented progress bars, and atomic JSON persistence.

### Academic — in progress

- **TCC — University Course Timetabling via Metaheuristics** — Modeling and solving the curriculum-based timetabling problem at UFF using OptFrame/pyoptframe (C++/Python) with Simulated Annealing, ILS, and VNS. Collecting real-world timetables from 2023–2025 through web scraping and comparing the generated solutions with UFF's actual schedules.

---

## Tech stack

| Category | Technologies |
|---|---|
| **Backend** | Laravel, PHP, Java (Spring Boot) |
| **Frontend** | React, TypeScript, Blade, Tailwind CSS, Bootstrap |
| **Mobile** | Flutter (Dart) |
| **AI/ML** | Python, Ollama, OpenAI API, Gensim/Word2Vec, NLTK, agent architectures |
| **Databases** | PostgreSQL, MySQL, SQLite |
| **Testing** | PHPUnit, unittest, flutter_test |
| **Static analysis** | PHPStan (level 6), Larastan, Laravel Pint |
| **Infrastructure** | Docker, Git, Linux, Redis |
| **Optimization** | OptFrame (C++), pyoptframe (Python), Simulated Annealing, ILS, VNS, CPLEX |

---

## Contact

:email: brpassos19@gmail.com
