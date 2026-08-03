<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0d1117&height=150&section=header" width="100%" />

<h1 align="center">Rıfat Çakır</h1>

<p align="center">
  <b>Senior Software Engineer</b> &nbsp;·&nbsp; Java &nbsp;·&nbsp; Kotlin &nbsp;·&nbsp; Spring
  <br>
  <sub>Utrecht, Netherlands</sub>
</p>

<br>

## About

I work on backend systems that already carry weight — monoliths that need
splitting, service boundaries drawn too early, test suites slow enough that
people quietly stopped running them. Making systems like that changeable again
is most of the job.

Mostly banking and e-commerce: domains where being correct matters more than
being novel.

For the past few years I've focused on where AI fits inside enterprise JVM
services. The hard problems there aren't prompts — they're determinism,
testability, and what a test suite costs when every run hits a model. That
problem is what `spring-ai-test-tools` exists to solve.

<sub>Backend engineering since 2017 · currently in banking, previously e-commerce and telecom</sub>

<br>

## How I work

**Name the real constraint before choosing anything.** Most architecture
questions arrive dressed as technical ones and turn out not to be. Team size,
release cadence, regulatory review, how much operational maturity actually
exists — these decide more designs than any framework comparison. An elegant
answer to the wrong constraint is just an expensive one, so I'd rather spend the
first week understanding the problem than the next year defending a solution.

**Every decision is a trade. Put the price on the table.** There is rarely a
correct architecture, only one whose costs you've knowingly agreed to pay.
Microservices buy independent deployment and charge you distributed
transactions, new failure modes, and a platform team nobody budgeted for. A
modular monolith buys speed and charges you discipline at the module boundary.
I've led a decomposition into microservices and I build moduliths with Spring
Modulith; neither is a default, and the work is making the invoice visible
before the decision rather than after.

**Design for being wrong.** I assume part of any design is mistaken — I just
don't know which part yet. So the question I care about is which decisions are
reversible. Data models and public contracts are expensive to undo, and they get
the analysis. Frameworks, topology, and internal structure are cheap to change,
and they get a decision and a move on. Tests are the cheapest way to find out
you were wrong; the measure isn't coverage percentage, it's whether people ship
on a Thursday without waiting for someone brave.

**The domain outlives the stack.** Frameworks are rented; the business model is
owned. Domain-Driven Design, Clean Architecture, and ports & adapters are how I
keep that ownership intact — not out of purity, but so that a database
migration, a framework upgrade, or a new channel stays a contained change
instead of becoming a rewrite.

<br>

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=java,kotlin,spring,gcp,azure&theme=dark" />
</p>

**Java · Kotlin · Spring Boot · Spring Modulith · Spring AI** — on Google Cloud and Azure.

<sub>Earlier in my career, and still useful for reading other people's systems: C · C++ · C# · Python</sub>

<br>

## Education

**MSc — Data Science & Machine Learning**<br>
Yeditepe University, Istanbul (2020–2022)

**BSc — Computer Engineering**<br>
Yeditepe University, Istanbul (2013–2017)<br>
<sub>Erasmus exchange in Computer Science — Universitat Politècnica de València (2014–2015)</sub>

<br>

## Open source

> [!IMPORTANT]
> ### Deterministic testing for Spring AI
>
> Creator and maintainer of
> [**spring-ai-test-tools**](https://github.com/rifatcakir/spring-ai-test-tools)
> — file-based record-and-replay (VCR) caching for Spring AI integration tests.
> LLM calls are slow, non-repeatable, and expensive to run in CI; this makes
> them behave like any other test.
>
> Documentation: **https://rifatcakir.github.io/spring-ai-test-tools/**
>
> [![License](https://img.shields.io/badge/License-Apache_2.0-6DB33F?style=flat-square)](https://github.com/rifatcakir/spring-ai-test-tools)
> [![Repo](https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rifatcakir/spring-ai-test-tools)

<br>

## Writing & speaking

Writing is how I work out the arguments I end up making in design reviews. I
publish on [**Medium**](https://medium.com/@rifatcakira) on software
architecture and system design — how to draw boundaries, where transactions stop
protecting you, and what architectural decisions actually cost over time.

I also present regularly to engineering teams on GenAI, the Model Context
Protocol, and software design — most recently *"The Human Side of Technical
Debt."*

<br>

## Elsewhere

<p>
  <a href="https://www.linkedin.com/in/rifatcakir/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://medium.com/@rifatcakira"><img src="https://img.shields.io/badge/Medium-4d4d4d?style=for-the-badge&logo=medium&logoColor=white" /></a>
</p>
