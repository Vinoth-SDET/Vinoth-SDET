<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Vinoth%20Marimuthu&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Senior%20QA%20Automation%20Engineer%20%7C%20SDET%20%7C%20Automation%20Architect&descAlignY=58&descSize=16&descColor=a0c4ff" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vinoth-m-qa)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Vinoth-SDET)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vinoth.sdet@outlook.com)
[![Profile Views](https://komarev.com/ghpvc/?username=Vinoth-SDET&color=2c5364&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/Vinoth-SDET)

<br/>

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=4FC3F7&center=true&vCenter=true&width=700&lines=11%2B+Years+Building+Production-Grade+Automation;Enterprise+API+%26+UI+Framework+Architect;AI-Powered+%26+Self-Healing+Test+Systems;CI%2FCD+Quality+Pipeline+Engineer;Shifting+Quality+Left+Since+2013)

</div>

---

## 🧭 About Me — The Automation Architect Mindset

I don't just write tests. I **architect quality systems**.

With **11+ years** in software engineering and test automation, I've moved from writing test cases to designing the infrastructure that enables entire engineering teams to ship confidently. My work sits at the intersection of **software architecture, DevOps, and quality engineering** — building frameworks that are scalable, observable, and treated like production code.

At **Coforge**, I architect and own automation strategy across BFSI and Healthcare platforms — designing BDD-driven frameworks, embedding quality gates into CI/CD pipelines, and mentoring teams to enforce engineering-grade automation standards. More recently, I've been pushing into **AI-assisted testing** — building self-healing frameworks and LLM-powered tools that reduce test maintenance overhead and accelerate QA delivery.

**What separates me from a typical QA engineer:**

- 🏗️ I think in **systems and abstractions** — not just scripts
- 🔁 I treat test code with the same **design principles** as production code (SOLID, DRY, clean architecture)
- 📊 I measure quality through **metrics and observability** — not just pass/fail counts
- 🤖 I actively integrate **AI and intelligence** into test automation tooling
- 🚀 I've consistently delivered **measurable engineering outcomes**: 35% faster regressions, 99% defect detection rates, 25% release throughput improvement

> *"My goal is not to catch bugs — it's to build systems that make bugs impossible to miss."*

---

## 🏗️ What I Build

```
┌───────────────────────────────────────────────────────────────────────┐
│                    ENGINEERING CAPABILITIES                           │
├──────────────────────────┬────────────────────────────────────────────┤
│  🌐 API Automation       │  RestAssured, SOAP UI, contract testing,   │
│                          │  JSON schema validation, auth flows        │
├──────────────────────────┼────────────────────────────────────────────┤
│  🎭 UI Automation        │  Selenium Grid, Playwright, cross-browser  │
│                          │  parallel execution, POM + Factory design  │
├──────────────────────────┼────────────────────────────────────────────┤
│  🤖 AI-Powered Testing   │  Self-healing locators, LLM test gen,     │
│                          │  Applitools visual AI, GitHub Copilot      │
├──────────────────────────┼────────────────────────────────────────────┤
│  🔀 Hybrid Frameworks    │  Unified API + UI + Mobile under one       │
│                          │  framework roof with shared utilities      │
├──────────────────────────┼────────────────────────────────────────────┤
│  🔁 CI/CD Pipelines      │  GitHub Actions, Jenkins, Azure DevOps,    │
│                          │  Docker-based test execution environments  │
├───────────────────────────┼───────────────────────────────────────────┤
│  🛡️ Security Testing     │  OWASP ZAP, Burp Suite, vulnerability      │
│                          │  assessment integrated into QA cycles      │
└──────────────────────────┴────────────────────────────────────────────┘
```

---

## 🚀 Flagship Project — Enterprise API Automation Suite

<div align="center">

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Vinoth-SDET&repo=enterprise-api-automation-suite&theme=tokyonight&hide_border=true)](https://github.com/Vinoth-SDET/enterprise-api-automation-suite)

</div>

> A **production-grade enterprise API automation platform** built to the same engineering standards as a microservices backend. Not a test project — an automation engineering product.

### 🏛️ Framework Architecture

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    ENTERPRISE API AUTOMATION SUITE                      │
│                      Hexagonal / Ports & Adapters                       │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│   ┌──────────────────────────────────────────────────────────────┐      │
│   │                       TEST LAYER                             │      │
│   │  TestNG Suites  │  @Step Annotations  │  Parallel Execution  │      │
│   └──────────────────────────┬───────────────────────────────────┘      │
│                              │                                          │
│   ┌──────────────────────────▼───────────────────────────────────┐      │
│   │                    SERVICE LAYER                             │      │
│   │   UserService  │  OrderService  │  AuthService  │  Contracts │      │
│   └──────────────────────────┬───────────────────────────────────┘      │
│                              │                                          │
│   ┌──────────────────────────▼───────────────────────────────────┐      │
│   │                  REQUEST BUILDER                             │      │
│   │  RequestSpecBuilder │ HeaderFactory │ AuthTokenManager       │      │
│   └──────────────────────────┬───────────────────────────────────┘      │
│                              │                                          │
│   ┌──────────────────────────▼───────────────────────────────────┐      │
│   │                    API CLIENT                                │      │
│   │   RestAssured Core │ RetryFilter │ LogFilter │ ThreadLocal   │      │
│   └──────────────────────────┬───────────────────────────────────┘      │
│                              │                                          │
│   ┌──────────────────────────▼───────────────────────────────────┐      │
│   │              APPLICATION API  (Target System)                │      │
│   │         REST Endpoints │ Auth Server │ Microservices         │      │
│   └──────────────────────────────────────────────────────────────┘      │
│                                                                         │
│   ┌─────────────────┐  ┌───────────────────┐  ┌────────────────────┐    │
│   │  ConfigManager  │  │  Allure Reports   │  │  GitHub Actions CI │    │
│   │  Env Profiles   │  │  ExtentReports    │  │  Multi-job Pipeline│    │
│   └─────────────────┘  └───────────────────┘  └────────────────────┘    │
└─────────────────────────────────────────────────────────────────────────┘
```

### 📐 Architecture Design Decisions

| Layer | Pattern | Why |
|-------|---------|-----|
| **Test Layer** | TestNG + ThreadLocal `BaseTest` | Thread-safe parallel execution with zero state leakage |
| **Service Layer** | Domain-driven service objects | Business logic abstracted from transport; tests read like specs |
| **Request Builder** | Builder pattern + factory | Reusable, composable request construction; eliminates duplication |
| **API Client** | Facade + Chain of Responsibility | Retry, logging, and auth are cross-cutting concerns — not test code |
| **Config** | `ConfigManager` + env profiles | `dev` / `staging` / `prod` switching via environment variables |
| **Reporting** | Allure + ExtentReports dual setup | Rich visual reports for engineers + stakeholder-friendly dashboards |

---

## 📂 Engineering Portfolio

---

### ✅ 1 · Enterprise API Automation Suite
> **Production-grade microservices API testing platform built on Hexagonal architecture**

| Dimension | Detail |
|-----------|--------|
| 🎯 **Purpose** | Scalable API automation for enterprise microservices — contract testing, auth flows, schema validation |
| 🏛️ **Architecture** | Hexagonal design: Test Layer → Service Layer → Request Builder → API Client → Target API |
| 🧪 **Test Coverage** | CRUD flows · Auth token management · Error handling · JSON Schema validation · Retry logic |
| 🔁 **CI/CD** | GitHub Actions multi-job pipeline — build → test → generate Allure report → deploy to GitHub Pages |
| 📊 **Reporting** | Allure Reports (GitHub Pages live) + ExtentReports dual output with request/response capture |
| 📈 **Scale** | ThreadLocal-safe parallel execution · `dev / staging / prod` env profiles via `ConfigManager` |

**Tech Stack:** `Java 21` · `RestAssured 5.4` · `TestNG 7.9` · `Maven` · `Allure 2.x` · `ExtentReports` · `GitHub Actions` · `Docker`

**Repo:** [`Vinoth-SDET/enterprise-api-automation-suite`](https://github.com/Vinoth-SDET/enterprise-api-automation-suite) &nbsp;|&nbsp; **Status:** ✅ Live

---

### 🚧 2 · Enterprise UI Automation Suite
> **Thread-safe, cross-browser UI automation framework with Page Object Model and CI integration**

| Dimension | Detail |
|-----------|--------|
| 🎯 **Purpose** | Scalable UI regression automation across browsers and environments for enterprise web apps |
| 🏛️ **Architecture** | ThreadLocal WebDriver · Page Object Model · Page Factory · TestNG Listeners · Extent Reports |
| 🧪 **Test Coverage** | Login flows · Navigation · Form validation · Cross-browser regression · Data-driven scenarios |
| 🔁 **CI/CD** | GitHub Actions — headless Chrome execution, Extent Report artifacts uploaded post-run |
| 📊 **Reporting** | Extent Reports with failure screenshots · Test execution timeline · Pass/Fail trend tracking |
| 📈 **Scale** | Selenium Grid ready · Parallel browser × environment matrix · WebDriverManager auto-setup |

**Tech Stack:** `Java 21` · `Selenium 4.x` · `TestNG` · `Maven` · `ExtentReports` · `WebDriverManager` · `GitHub Actions`

**Repo:** [`Vinoth-SDET/enterprise-ui-automation-suite`](https://github.com/Vinoth-SDET/enterprise-ui-automation-suite) &nbsp;|&nbsp; **Status:** 🚧 In Progress

---

### 🚧 3 · AI Self-Healing Test Framework
> **Next-generation automation framework that detects broken locators and auto-heals them using AI**

```
  Locator Fails
       │
       ▼
  ┌────────────────────────────────────────────────┐
  │           SELF-HEALING ENGINE                  │
  │                                                │
  │  DOM Snapshot → AI Similarity Scorer →         │
  │  Candidate Locators → Best Match →             │
  │  Auto-Update Locator Registry → Resume Test    │
  └────────────────────────────────────────────────┘
       │
       ▼
  Test Continues ✅  +  Healing Report Generated
```

| Dimension | Detail |
|-----------|--------|
| 🎯 **Purpose** | Eliminate flaky test maintenance by automatically recovering from broken UI locators |
| 🏛️ **Architecture** | Selenium base + DOM diff engine + AI similarity scorer + locator registry with auto-update |
| 🧪 **Test Coverage** | Locator healing for ID · XPath · CSS · text-based selectors across page change scenarios |
| 🔁 **CI/CD** | GitHub Actions pipeline — healing events logged and reported as CI artifacts |
| 📊 **Reporting** | Healing audit log · Allure annotations marking healed steps · Drift detection dashboard |
| 📈 **Scale** | Pluggable healing strategy interface — swap AI model or scoring algorithm without rewrites |

**Tech Stack:** `Java 21` · `Selenium 4.x` · `TestNG` · `OpenAI API / Ollama` · `Maven` · `Allure` · `GitHub Actions`

**Repo:** [`Vinoth-SDET/ai-self-healing-test-framework`](https://github.com/Vinoth-SDET/ai-self-healing-test-framework) &nbsp;|&nbsp; **Status:** 🚧 In Progress

---

### 🚧 4 · AI Test Case Generator
> **LLM-powered pipeline that converts requirements or API specs into structured, ready-to-run test scenarios**

```
  Input: User Story / API Spec / BRD
       │
       ▼
  ┌─────────────────────────────────────────────────┐
  │           AI TEST CASE GENERATOR                │
  │                                                 │
  │  Document Parser → Prompt Engineer →            │
  │  Ollama (Llama 3) / Claude API →                │
  │  Structured Output (Gherkin / TestNG / CSV) →   │
  │  Export to Jira / Excel / GitHub                │
  └─────────────────────────────────────────────────┘
       │
       ▼
  Output: Functional · Edge Case · Negative Tests ✅
```

| Dimension | Detail |
|-----------|--------|
| 🎯 **Purpose** | Cut test case design time by 60%+ using LLMs to auto-generate structured test scenarios |
| 🏛️ **Architecture** | Python Flask API → prompt engineering layer → Ollama (Llama 3) → JSON / Gherkin output |
| 🧪 **Coverage** | Functional · negative · edge case · boundary value scenarios from a single input document |
| 🔁 **Pipeline** | n8n workflow: trigger on doc upload → generate → export to Jira / CSV / Excel |
| 📊 **Output Formats** | Gherkin BDD · TestNG XML · plain CSV · Jira-compatible JSON |
| 📈 **Scale** | Local-first via Ollama (zero API cost) · swappable to GPT-4 or Claude API via config |

**Tech Stack:** `Python` · `Flask` · `Ollama (Llama 3)` · `n8n` · `LangChain` · `GitHub Actions`

**Repo:** [`Vinoth-SDET/ai-test-case-generator`](https://github.com/Vinoth-SDET/ai-test-case-generator) &nbsp;|&nbsp; **Status:** 🚧 In Progress

---

### 🚧 5 · Hybrid Automation Framework
> **Unified test automation framework combining API, UI, and Mobile under a single roof with shared utilities**

```
┌───────────────────────────────────────────────────────────────────┐
│                   HYBRID AUTOMATION FRAMEWORK                     │
├───────────────┬───────────────────┬───────────────────────────────┤
│   API MODULE  │    UI MODULE      │       MOBILE MODULE           │
│  RestAssured  │  Selenium 4.x     │       Appium 2.x              │
│  SOAP UI      │  Playwright       │  iOS · Android · BrowserStack │
└───────┬───────┴────────┬──────────┴──────────┬────────────────────┘
        │                │                     │
        └────────────────▼─────────────────────┘
                  SHARED CORE LAYER
         ConfigManager · TestDataFactory · BaseTest
         ReportingEngine · RetryHandler · LogManager
                         │
                         ▼
              CI/CD · GitHub Actions · Docker
              Allure Reports · GitHub Pages
```

| Dimension | Detail |
|-----------|--------|
| 🎯 **Purpose** | Single framework handling API, UI, and Mobile testing — eliminating 3 separate repo sprawls |
| 🏛️ **Architecture** | Shared core layer with pluggable test modules; each module is independently runnable |
| 🧪 **Test Coverage** | End-to-end cross-channel flows: API → UI → Mobile in a single test orchestration pipeline |
| 🔁 **CI/CD** | GitHub Actions matrix strategy — API, UI, Mobile jobs run in parallel, unified report at end |
| 📊 **Reporting** | Single Allure dashboard aggregating results across all 3 test channels |
| 📈 **Scale** | BrowserStack / Sauce Labs integration ready · Dockerized execution · multi-env config |

**Tech Stack:** `Java 21` · `Selenium 4.x` · `Playwright` · `Appium 2.x` · `RestAssured` · `TestNG` · `Maven` · `Docker` · `Allure` · `GitHub Actions`

**Repo:** [`Vinoth-SDET/hybrid-automation-framework`](https://github.com/Vinoth-SDET/hybrid-automation-framework) &nbsp;|&nbsp; **Status:** 🚧 In Progress

---

## 🧱 Automation Framework Design Principles

```
┌─────────────────────────────────────────────────────────────────────────┐
│               FRAMEWORK ENGINEERING STANDARDS                           │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│  1. MODULARITY        Tests ≠ Framework code. Layers are isolated.      │
│                        Change a locator → zero test rewrites needed.    │
│                                                                         │
│  2. REUSABILITY       Utility classes, builders, base pages and         │
│                        base tests are never duplicated — imported.      │
│                                                                         │
│  3. THREAD SAFETY     ThreadLocal WebDriver / RestAssured context       │
│                        enables true parallel execution without flakes.  │
│                                                                         │
│  4. OBSERVABILITY     Every test run produces structured evidence:      │
│                        logs, screenshots, request/response dumps,       │
│                        Allure step traces — not just pass/fail.         │
│                                                                         │
│  5. CI/CD FIRST       Frameworks are built for pipelines, not just      │
│                        local dev. Headless by default. Env-configurable │
│                        via ENV_VAR — no hardcoded URLs or credentials.  │
│                                                                         │
│  6. MAINTAINABILITY   Every class has a single responsibility. Tests    │
│                        read like English. New team members ramp in      │
│                        hours — not weeks.                               │
│                                                                         │
│  7. SCALABILITY       Framework scales horizontally (more tests) and    │
│                        vertically (more envs) without redesign.         │
│                        Config-driven. Grid-ready. Docker-ready.         │
│                                                                         │
│  8. FAIL FAST         Smart assertions + early exit + retry logic       │
│                        that distinguishes flakiness from real failures. │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

### ⚙️ Automation Tools
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Appium](https://img.shields.io/badge/Appium-662D91?style=for-the-badge&logo=appium&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FF6C37?style=for-the-badge&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=for-the-badge&logo=cucumber&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![Allure](https://img.shields.io/badge/Allure_Reports-FF6B35?style=for-the-badge&logoColor=white)

### 💻 Programming Languages
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### 🌐 API & Web Services Testing
![REST Assured](https://img.shields.io/badge/REST_Assured-43B02A?style=for-the-badge&logo=java&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![SOAP UI](https://img.shields.io/badge/SOAP_UI-6DB33F?style=for-the-badge&logoColor=white)

### 🔧 DevOps / CI-CD Tools
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 🛡️ Security & Performance Testing
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-000000?style=for-the-badge&logo=owasp&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logoColor=white)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apache&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![Vinoth's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Vinoth-SDET&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Vinoth-SDET&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Vinoth-SDET&theme=tokyonight&hide_border=true)

</div>

---

## 🏆 Engineering Impact & Career Highlights

| Domain | Metric | Impact |
|--------|--------|--------|
| ⚡ **CI/CD Automation** | Regression execution time | **↓ 35%** at Coforge via Selenium + GitHub Actions |
| 🚀 **Release Throughput** | Deployment frequency | **↑ 25%** via Jenkins & Azure DevOps pipeline integration |
| 🐛 **Defect Prevention** | Pre-release defect detection | **99% rate** at Phillip Centralized Services (stock trading) |
| 🔒 **Security Engineering** | Vulnerability remediations | **15+ critical CVEs** found via OWASP ZAP & Burp Suite |
| 📋 **Requirement Coverage** | Test case design | **120+ cases**, 100% BRD/FRD traceability at HCL Technologies |
| 👥 **Engineering Leadership** | Team mentoring | **5+ QA engineers** mentored and upskilled at Coforge |
| 📉 **Production Quality** | Post-production defect rate | **↓ 25%** at Trigent Software via shift-left strategy |
| 😊 **Client Delivery** | Satisfaction scores | **↑ 20%** improvement via QA reviews and delivery excellence |

---

## 💼 Engineering Career Timeline

```
 Aug 2013    ┌─────────────────────────────────────────────────────────┐
  – Jul 2014 │  Infosys BPO Limited          │  Process Executive      │
             └─────────────────────────────────────────────────────────┘
 Sep 2014    ┌─────────────────────────────────────────────────────────┐
  – Feb 2015 │  Amrithaa System Pvt. Ltd.    │  Software Engineer      │
             └─────────────────────────────────────────────────────────┘
 Mar 2015    ┌─────────────────────────────────────────────────────────┐
  – Jan 2016 │  HCL Technologies             │  Quality Analyst        │
             └─────────────────────────────────────────────────────────┘
 Jan 2016    ┌─────────────────────────────────────────────────────────┐
  – Jul 2019 │  Consistent Global Solution   │  Senior Quality Analyst │
             └─────────────────────────────────────────────────────────┘
 Jul 2019    ┌─────────────────────────────────────────────────────────┐
  – Apr 2021 │  Trigent Software Pvt. Ltd.   │  Module Lead            │
             └─────────────────────────────────────────────────────────┘
 Aug 2021    ┌─────────────────────────────────────────────────────────┐
  – Jun 2022 │  Phillip Centralized Services │  Senior Test Analyst    │
             └─────────────────────────────────────────────────────────┘
 Jun 2022    ┌─────────────────────────────────────────────────────────┐
  – Present  │  Coforge                      │  Test Specialist  ◀ NOW │
             └─────────────────────────────────────────────────────────┘
```

---

## 🌱 Currently Learning & Growing

```text
🤖  AI-Assisted & Self-Healing Testing     ████████████████░░░░  80%
🎭  Playwright + TypeScript (Advanced)     ██████████████░░░░░░  70%
🐳  Docker · Containerized Test Envs       ██████████████░░░░░░  70%
🔁  n8n Workflow & Test Orchestration      ████████████░░░░░░░░  55%
☁️  Cloud QA · AWS Testing Patterns        ████████░░░░░░░░░░░░  40%
```

---

## 🧠 QA Engineering Knowledge Areas

```
📐 Framework Architecture    │  POM · Factory Pattern · Singleton · Hexagonal / Ports & Adapters
🌐 Domain Experience         │  BFSI · Healthcare · E-commerce · Logistics · Travel · Stock Trading
🛡️ Security & Compliance     │  OWASP ZAP · Burp Suite · 15+ CVE remediations · Audit-ready artifacts
🗄️ Data Layer Testing        │  SQL · Oracle · PostgreSQL · backend validation · DB assertion layers
📊 Test Observability        │  Allure · Extent Reports · TestNG HTML · structured execution evidence
📱 Mobile Automation         │  Appium · iOS & Android · device-matrix regression
🔄 Agile Quality Engineering │  Shift-left · BDD · sprint-integrated testing · release quality gates
🤖 AI-Powered Testing        │  Self-healing locators · LLM test generation · Applitools visual AI
```

---

## 🎓 Education & Certifications

🎓 **B.E. in Electrical and Electronics Engineering**  
Adhiyamaan College of Engineering, Tamil Nadu (2013)

| Certification | Issuer | Year |
|---------------|--------|------|
| 🏅 Building Test Automation Framework using Selenium & TestNG | Coursera Project Network | 2025 |
| 🏅 API Testing Using REST Assured Test Automation Tool | Coursera Project Network | 2025 |

---

## 🤝 Let's Connect

<div align="center">

### Open to **Senior SDET** · **QA Lead** · **Automation Architect** roles — Remote & Global 🌍

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vinoth-m-qa)
[![GitHub Follow](https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Vinoth-SDET)
[![Email Me](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vinoth.sdet@outlook.com)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer&text=Quality%20is%20an%20Architecture%20Decision&fontSize=16&fontColor=a0c4ff&fontAlignY=65" />

</div>

---

<div align="center">

*"Quality is never an accident; it is always the result of intelligent effort."* — John Ruskin

⭐ **If my frameworks or projects helped you, please give them a star — it keeps me building!**

</div>
