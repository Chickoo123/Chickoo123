<div align="center">

# Hi, I'm Harshil Desai 👋

### I build evidence-first tools that hold Indian finance to its own rules.

Fintech · public data · privacy-first web apps · applied AI with guardrails

[![GitHub followers](https://img.shields.io/github/followers/Chickoo123?style=flat&logo=github&label=Follow&color=10b981)](https://github.com/Chickoo123)
![Profile views](https://komarev.com/ghpvc/?username=Chickoo123&color=8b5cf6&style=flat&label=Profile+views)

</div>

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🔍 [LoanLens](https://github.com/Chickoo123/loanlens)
**Check a loan offer against RBI's rules before you sign.**

<a href="https://chickoo123.github.io/loanlens/"><img src="https://raw.githubusercontent.com/Chickoo123/loanlens/main/docs/hero.png" alt="LoanLens: advertised APR 34.50% vs recomputed 94.22%"></a>

Recomputes the true APR from a loan's Key Facts Statement using RBI's method (it **reproduces RBI's own worked example, 17.07%**). It flags the malpractices RBI has named, such as interest charged before disbursal, advance EMIs with interest on the full amount, and illegal pre-payment charges, and each finding cites the circular it relies on.

`JavaScript` `IRR / APR maths` `RBI regulation` `18 test suites`
**[▶ Live app](https://chickoo123.github.io/loanlens/)**

</td>
<td width="50%" valign="top">

### 💸 [PaisaTrail](https://github.com/Chickoo123/paisatrail)
**Find the bank charges you can get reversed.**

<a href="https://chickoo123.github.io/paisatrail/?demo"><img src="https://raw.githubusercontent.com/Chickoo123/paisatrail/main/docs/hero.png" alt="PaisaTrail: ₹545 of ₹2,080 in charges can be challenged"></a>

Reads an Indian savings statement, matches every charge to its GST line, and tests it against RBI rules: minimum-balance penalties that pushed the balance negative, ATM fees within the free limit or above the ₹23 cap, online NEFT charges. Each claim shows the statement lines that prove it, and it drafts the dispute. Nothing leaves your browser.

`JavaScript` `Statement parsing` `RBI regulation` `13 test suites`
**[▶ Live demo](https://chickoo123.github.io/paisatrail/?demo)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏥 [BimaBrief](https://github.com/Chickoo123/BimaBrief)
**Indian health-insurance data, explained without guesswork.**

Open public-data explorer built on official IRDAI handbook tables. Every metric carries its source, year and formula. Missing data stays missing instead of being guessed. Automated monthly source checks open review issues.

`Python` `pandas` `Playwright` `GitHub Actions`
**[▶ Live site](https://chickoo123.github.io/BimaBrief/)**

</td>
<td width="50%" valign="top">

### 📈 [IPO Lab](https://github.com/Chickoo123/ipo-reality-lab)
**Understand the issue. Research the issuer. Follow the proceeds.**

Evidence-led IPO research platform that links SEBI/NSE/BSE offer documents to fundamentals and **tracks how IPO proceeds were actually used**, with page-level citations. Includes 27 learning modules and 6 interactive tools.

`JavaScript` `Python validation` `JSON Schema`
**[▶ Live site](https://chickoo123.github.io/ipo-reality-lab/)**

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🤖 [RecoverX](https://github.com/Chickoo123/RecoverX): an AI revenue-recovery agent with hard guardrails
An LLM reads customer replies to understand intent, then **deterministic policy rules decide** what happens: retry, payment link, follow-up, escalate or stop. Disputes, fraud and high-value cases can never be auto-actioned. On a 47-transaction benchmark, it matched rules-only recovery with **lower automated exposure** (48.8% vs 42.7% attempt success). It also keeps a full audit trail. `Python` `Flask` `Groq LLM` `13 safety tests`

</td>
</tr>
</table>

### 🧱 Data structures in C++
| Repo | What it shows |
|---|---|
| [Booking-System-](https://github.com/Chickoo123/Booking-System-) | Generic ring-buffer queue. Fixed a wrap-around bug and a never-reusable-slot bug, each with a regression test. |
| [Flight & Train booking](https://github.com/Chickoo123/Flight-Ticket-booking-Queue-Implementation-using-Linked-List-) | Leak-free `unique_ptr` linked queue and stack with iterative teardown, safe for 1M+ nodes. |

Both are built in CI with g++ and clang++ under `-Werror`, then tested again under **AddressSanitizer and UBSan**.

---

## 🧠 How I build

- **Evidence over vibes.** Every number links to a source, a formula or a test. "Not available" beats a guess.
- **Privacy by construction.** If a tool doesn't need your data on a server, it never sends it there.
- **AI with guardrails.** Models interpret context; deterministic rules make the decisions that matter.
- **Ship it properly.** CI on every push, CodeQL scanning, tests that pin real bugs, and live demos.

## 🛠️ Toolbox

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)
![C++](https://img.shields.io/badge/C++17-00599C?logo=cplusplus&logoColor=fff)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=fff)
![Flask](https://img.shields.io/badge/Flask-000?logo=flask&logoColor=fff)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=fff)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=fff)
![LLMs](https://img.shields.io/badge/LLM_apps-8b5cf6?logo=openai&logoColor=fff)

---

<div align="center">

![Contribution snake](https://raw.githubusercontent.com/Chickoo123/Chickoo123/output/snake-dark.svg#gh-dark-mode-only)
![Contribution snake](https://raw.githubusercontent.com/Chickoo123/Chickoo123/output/snake.svg#gh-light-mode-only)

<sub>Open to internships and collaborations in fintech, data and applied AI. Open an issue on any repo to reach me.</sub>

</div>
