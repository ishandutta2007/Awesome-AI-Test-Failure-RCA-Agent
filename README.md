# Awesome-AI-Test-Failure-RCA-Agent

# Awesome-AI-Test-Failure-RCA-Agent

**Top AI Test Failure RCA Agent (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Root Cause Analysis, Failure Categorization, Flaky Test Detection & Self-Hosted Test Intelligence*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Test Failure RCA Agents**. These tools enable QA and engineering teams to move beyond pass/fail dashboards—automatically correlating logs, screenshots, and history to classify failures as product bugs, automation issues, or environment problems, and suggesting fixes before engineers spend hours digging.



**Examples** include BrowserStack Test Failure Analysis Agent, Sauce Labs Failure Analysis, Datadog CI Visibility, ReportPortal, Allure TestOps, Launchable, SeaLights, Develocity (Gradle Enterprise), Sentry Seer, and Gremlin Foresight (the category leaders in commercial and open-source space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted RCA, failure classification, and open test analytics. **Critical note**: The open-source landscape is anchored by **ReportPortal**—the most mature Apache 2.0 test analytics platform with ML-based Auto-Analyzer for failure reasons , and **CrashLab**—a newer Python library for deterministic replay and divergence detection in AI agent testing . No open-source project matches BrowserStack's one-click RCA with 95% faster analysis or Launchable's predictive test selection, but for self-hosted test intelligence, the options are production-capable.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **BrowserStack Test Failure Analysis Agent**

  **One-click AI root cause analysis** within BrowserStack Test Reporting & Analytics. **Features**: **Automated RCA**—correlates logs, screenshots, stack traces, and test metadata; **failure categorization**—classifies as production bug, automation issue, environment issue, or custom defect; **bulk apply** categorization to similar failures; **AI-recommended fixes** and next-best actions; **natural language follow-up** to dig deeper into RCA; sends details to Jira, Asana, GitHub, Slack, and more . Claims **95% faster failure analysis** . **Fair Usage Policy**: **30 test failures analyzed per 1,000 TRA test executions/month** (Test Reporting & Analytics and Test Management); **1,000 failures analyzed per parallel/month** (Automate and App Automate) . **Pricing**: Bundled with BrowserStack AI; requires enabled AI and Owner/Admin permissions . **Free tier**: No free tier for AI agent; trial available. **Best for**: teams already on BrowserStack wanting one-click RCA integrated with their automation dashboard—**trade-off**: FUP limits analysis volume; requires BrowserStack subscription.



- **Sauce Labs Failure Analysis**

  **AI-powered failure diagnosis** within Sauce Labs. **Features**: **Error analytics** for diagnosing root causes; **Sauce Error Reporting** for production failure analysis; enterprise governance (SSO, audit logs, SOC 2 evidence export); correlates test failures with live user errors . **Pricing**: **Live Testing from $199/month**; **Automated Testing from $199/month**; **Enterprise custom** . **Free tier**: Trial available. **Best for**: enterprises needing production error analytics alongside test runs—**trade-off**: **inflexible pricing model** noted by reviewers, challenging for smaller organizations; Error Reporting as standalone add-on evaluated separately .



- **Datadog CI Visibility**

  **CI/CD pipeline and test monitoring** within Datadog. **Features**: Monitors job failures and performance; collects pipeline job logs; test settings configuration; integrates with existing Datadog observability . **Pricing**: **Priced per committer**—may affect Datadog bill . **Free tier**: Limited trial. **Best for**: teams already on Datadog wanting CI visibility alongside infrastructure and APM—**trade-off**: **failure analysis is CI-focused**, not deep test RCA; per-committer pricing scales with team size .



- **Allure TestOps**

  **Test management with AI-assisted triage**. **Features**: Manual and automated tests share one data model; **defect linking** and **regex-based grouping** for failures; two-way CI integration; **MCP server (public beta, v26.1.1)** with **13 tools**—8 writing tools including create/delete test cases and **muting failures**; analytics via Allure Query Language; enterprise controls (SSO, RBAC, audit logs) . **Pricing**: **Cloud from $39/user/month** (60 GB storage); on-premise quote-based . **Free tier**: No free tier; trial available. **Best for**: teams with structured manual QA alongside automation wanting a unified system of record—**trade-off**: **ML failure classification is regex-based grouping**, not deep AI RCA; MCP may incur future fees .



- **Launchable**

  **Predictive test selection and flaky test detection**. **Features**: **ML model identifies tests with highest probability of failing** based on code and test metadata; **predictive test selection** builds subsets for faster feedback; **flaky test insights**—test session duration, frequency, failure ratio; test entropy measurement . **Pricing**: **Starting at $12,000/year**; usage-based . **Free tier**: Trial available. **Best for**: teams wanting to run fewer tests while catching failures early—**trade-off**: **predictive selection, not RCA**—it tells you what to run, not why something failed.



- **SeaLights**

  **Continuous quality intelligence** with test impact analysis. **Features**: **Test Impact Analysis (TIA)**—identifies which tests to run based on code changes; **test gap analysis**—flags untested code changes; comprehensive coverage data; quality trends; PR integration showing testing status of changed code . **Pricing**: Paid; tiered by **lines of code** . **Free tier**: None. **Best for**: teams wanting to optimize test execution and identify coverage gaps—**trade-off**: **dynamic analysis, not failure RCA**—it prevents failures by testing the right code, not diagnosing failures after they occur.



- **Develocity (Gradle Enterprise)**

  **Toolchain observability and build acceleration**. **Features**: **Failure analytics** for builds and tests; **test acceleration**; **shared build cache**; observability from local builds through CI; enforces performance and reliability standards at scale . **Pricing**: Commercial; quote-only. **Free tier**: None. **Best for**: enterprises using Gradle/Maven/Bazel wanting build and test failure analytics—**trade-off**: **build-system focused**, not framework-agnostic test RCA.



- **Sentry Seer**

  **AI debugging agent** for runtime errors. **Features**: Uses **runtime context** (errors, spans, logs, metrics) to debug during local development, in PRs, and in production; explains what broke and suggests fixes; **flat pricing $40/active contributor/month for unlimited use** (active = 2+ PRs in connected repo/month) . **Pricing**: **$40/active contributor/month**; 14-day free trial for GitHub/GitHub Enterprise users . **Free tier**: Trial only. **Best for**: teams wanting AI debugging integrated with error monitoring—**trade-off**: **runtime errors, not test failures**—it diagnoses production issues, not CI test failures.



- **Gremlin Foresight**

  **AI reliability testing and RCA**. **Features**: **Analyzes system**, predicts what could go wrong, identifies risks, runs tests to validate, interprets results, explains why it failed, provides fix diff or code snippet, and **re-runs to prove the fix**; built on millions of experiments and tens of thousands of Fortune 100/1000 systems . **Pricing**: **Per team**, with high usage limits (no token-based billing) . **Free tier**: Beta with existing Gremlin customers. **Best for**: teams wanting closed-loop reliability testing with human-in-the-loop—**trade-off**: **reliability testing focus**, not CI test suite RCA; newer product (6–8 weeks beta at time of interview) .



## Open-Source GitHub Projects



- **ReportPortal**

  **AI-powered test automation dashboard** (Apache 2.0) — **the most mature open-source test analytics and failure analysis platform**, with **1,700+ companies** including **40+ Fortune 500** using it, processing **85M+ launches/year** . **Features**: **Real-time analytics**—investigate failure reasons immediately after test completion; **Machine Learning Auto-Analyzer**—analyzes failure reasons based on ML, detecting patterns and predicting future results; **AI-assisted failure triage**—assists manual review of logs and new failure patterns; **Automated Quality Gates**—decision-making for release pipelines; **Dashboards & History**—visualize trends and detect patterns . **Tech stack**: Java, Docker/Kubernetes . **Deploy**: Self-hosted (Apache 2.0, Docker/K8s) or cloud. **Trade-off**: **Report-first platform with ML labels**—not an autonomous agent; requires test result ingestion; UI can feel dated compared to SaaS platforms . **Best for**: teams wanting a proven, self-hosted test analytics platform with ML-based failure classification—especially those already using ReportPortal for test reporting.



- **CrashLab**

  **Deterministic replay and divergence detection for AI agents** (PyPI) — **the most focused open-source tool for diagnosing AI agent test failures**, addressing a gap that traditional test RCA tools miss . **Features**: **Records every LLM and tool call**—normalizes OpenAI and Anthropic conversations to stable request hashes; redacts API keys, auth headers, and token-like strings before writing; stores SQLite index plus JSONL cassettes per run . **Strict offline replay**—re-runs recorded entry point with every LLM and tool call served from cassette; no API key, no network; tools never run (side_effects=True tools cannot fire); matches by step order plus normalized hash; raises DivergenceError with step, differing fields, and diff . **Fork at step N with patch**—re-runs with steps before N from cassette and step N onwards live, with typed patches (SystemPromptPatch, ToolResultPatch, ModelParamPatch); side_effects=True tools never run live . **Outcome oracles**—`@crashlab.check("agent-name")` functions determine pass/fail; runtime checks emit typed findings (step_repetition, tool_error_streak, bad_tool_args, suspicious_tool_result, budget, length_cutoff) . **Tech stack**: Python . **Deploy**: `pip install crashlab`; local store `.crashlab/` . **Trade-off**: **AI agent testing only**—not for traditional test suites; newer project with limited validation. **Best for**: developers testing AI agents wanting deterministic replay and divergence diagnosis—especially those building agentic workflows where failures are non-deterministic and hard to reproduce.



### Additional Strong Open-Source Options



- **No mature open-source equivalent to BrowserStack's one-click RCA exists.** BrowserStack, Sauce Labs, Launchable, SeaLights, Develocity, Sentry Seer, and Gremlin Foresight are proprietary. **ReportPortal** provides ML-based failure classification but not autonomous RCA agents. **CrashLab** addresses AI agent testing, not traditional CI failures. For production-grade autonomous RCA, commercial platforms are required.



**Frameworks for building custom systems**: **ReportPortal** provides the test analytics and ML classification foundation; **CrashLab** provides deterministic replay for AI agent failures. **Neither matches BrowserStack's one-click RCA with 95% faster analysis or Launchable's predictive test selection.**



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Test failure RCA platforms handling test data and application telemetry must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "one-click RCA agent" vs. "failure analytics platform" vs. "predictive test selection" vs. "AI agent replay" distinction is critical.** **BrowserStack Test Failure Analysis Agent** is a **one-click RCA agent**—it analyzes failed tests, categorizes failures, and recommends fixes with natural language follow-up . **Sauce Labs Failure Analysis, Datadog CI Visibility, and ReportPortal** are **failure analytics platforms**—they provide dashboards and ML classification but not autonomous agent-style RCA . **Launchable and SeaLights** are **predictive test selection**—they optimize what to run, not diagnose failures after the fact . **CrashLab** is **AI agent replay**—it diagnoses non-deterministic failures in AI agents . **Sentry Seer** is **runtime error debugging**—not test failures . **Choose based on whether you need autonomous RCA, analytics dashboards, test selection, agent replay, or runtime debugging.**

- **BrowserStack's Fair Usage Policy limits analysis to 30 failures per 1,000 TRA executions/month**—or **1,000 per parallel/month** on Automate/App Automate . **For high-volume test suites, model your failure rate against these limits** .

- **Sauce Labs' pricing is noted as inflexible** by reviewers, challenging for smaller organizations . **Error Reporting as a standalone add-on should be evaluated if production defect rate justifies it** .

- **Launchable starts at $12,000/year** and provides **predictive test selection, not RCA**—it tells you which tests to run, not why one failed . **Do not confuse test selection with failure diagnosis.**

- **SeaLights is test impact analysis, not RCA**—it identifies which tests to run based on code changes and flags untested code . **The trade-off**: dynamic analysis prevents failures; it does not diagnose them.

- **Sentry Seer is for runtime errors, not test failures.** It uses production error context to debug issues—not CI test suite failures . **The trade-off**: $40/active contributor/month for unlimited use is attractive for production debugging, but it is not a test RCA tool .

- **ReportPortal is the most mature open-source test analytics platform**—Apache 2.0, 1,700+ companies, 85M+ launches/year, with ML Auto-Analyzer for failure classification . **The trade-off**: report-first with ML labels; not an autonomous agent; requires test result ingestion.

- **CrashLab is the only open-source tool for diagnosing AI agent test failures**—deterministic replay, divergence detection, and typed patches . **The trade-off**: AI agent testing only; newer project with limited validation. **For teams building agentic workflows where failures are non-deterministic, it fills a real gap.**

- Self-hosted open-source solutions require proper infrastructure (Java/Docker for ReportPortal, Python for CrashLab), security hardening, and ongoing maintenance. **Test failure data includes application logs and stack traces**—ensure your deployment meets your organization's security and compliance requirements before ingesting production test results.



---



**Made for QA engineers, test automation leads, and organizations building transparent test intelligence solutions.**

Let's make AI Test Failure RCA Agents more open, data-driven, and debugging-friendly.
