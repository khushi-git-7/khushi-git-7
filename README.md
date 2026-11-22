### Hi, I'm Khushi.

I break software for a living, politely, and before your users do.

By day I'm an AI QA Engineer. I test LLM copilots and RAG pipelines, which mostly means asking a very confident chatbot "are you sure?" until one of us admits it made something up. Usually it's the chatbot.

### Things I've built

**[RAGProbe](https://github.com/khushi-git-7/ragprobe)**: an evaluation and regression harness for RAG/LLM apps. It treats a prompt change like a code change: measure retrieval, check the answer is grounded, compare against a baseline, and fail CI when quality quietly slips. Because "it seemed fine when I tried it once" is not a test plan.

**[TestVerse](https://github.com/khushi-git-7/Saucedemo-playwright-framework)**: an e-commerce UI and API automation framework in Playwright and Pytest. Page objects, data-driven tests, parallel runs, Docker, and CI that keeps screenshots, video and traces of every failure, so nobody has to say "works on my machine".

### Open source

41 pull requests merged into 13 open-source projects so far, each reviewed and accepted by the project's maintainers. A few of them:

- **[Microsoft PyRIT](https://github.com/microsoft/PyRIT)** (an AI red-teaming toolkit): removed four deprecated features at the end of their deprecation window, from legacy `pyrit_scan` flags to an old API field ([#4425](https://github.com/microsoft/PyRIT/pull/4425), [#4428](https://github.com/microsoft/PyRIT/pull/4428), [#4429](https://github.com/microsoft/PyRIT/pull/4429), [#4430](https://github.com/microsoft/PyRIT/pull/4430))
- **[Tracekit](https://github.com/Cygnux-Labs/Tracekit)** (tracing and policy gates for AI agents): 19 PRs, including a CI job that runs the CrewAI example against the real thing instead of quietly skipping it ([#493](https://github.com/Cygnux-Labs/Tracekit/pull/493)) and a garbage-collector setting that took about 4 minutes off a full serial Python 3.12 test run ([#1053](https://github.com/Cygnux-Labs/Tracekit/pull/1053))
- **[Patroni](https://github.com/patroni/patroni)** (PostgreSQL high availability): accepted a Windows drive-letter path as a unix socket directory ([#3787](https://github.com/patroni/patroni/pull/3787))
- **[Deutsche Telekom's Scale](https://github.com/telekom/scale)** and **[ING's Lion](https://github.com/ing-bank/lion)** design systems: a read-only dropdown that could still be opened and changed ([#2568](https://github.com/telekom/scale/pull/2568)), and a button that clicked when a key pressed elsewhere was released on it ([#2973](https://github.com/ing-bank/lion/pull/2973))
- **[ngx-daterangepicker-material](https://github.com/fetrarij/ngx-daterangepicker-material)**: stopped two date pickers from staying open at once ([#625](https://github.com/fetrarij/ngx-daterangepicker-material/pull/625)), added `provideDaterangepicker()` for standalone Angular apps ([#627](https://github.com/fetrarij/ngx-daterangepicker-material/pull/627)), and taught `ng add` to use it ([#631](https://github.com/fetrarij/ngx-daterangepicker-material/pull/631))

My favourite kind of PR comes with a test that fails without it.

### What I work with

Python, TypeScript, Playwright, Pytest, REST APIs, SQL, LLM and RAG evaluation, GitHub Actions, Docker, and a healthy distrust of the green checkmark.

### Say hi

[LinkedIn](https://www.linkedin.com/in/khushipf) or jainkhushibts@gmail.com. Bug reports welcome. Compliments too.
