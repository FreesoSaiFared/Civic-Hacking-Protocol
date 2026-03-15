# Civic Hacking Protocol (CHP)

**Turn Discomfort into Design**

> **Transform personal discomfort into verifiable structure.**

The **Civic Hacking Protocol (CHP)** is an inductive modeling framework designed to turn everyday friction—small inconsistencies, unexplained burdens, or bureaucratic inefficiencies—into **structured proposals for social improvement**.

Rather than treating these experiences as vague complaints, CHP provides a process for translating them into **theory, measurable indicators, and practical system designs**.

The protocol was originally derived from the analytical workflow used by the SBCM Alliance to rapidly develop concepts such as the **Standard Block Comparison Method**, **G-Cart**, and several related technical papers. CHP packages that thinking process into a reproducible method that anyone can apply.

---

## What This Is

CHP is essentially a **method for converting personal experiences into structured civic issue reports**.

In most contexts, dissatisfaction with public systems—administrative processes, infrastructure decisions, public spending—tends to be dismissed as subjective opinion. CHP approaches these situations differently. It assumes that what appears to be a personal inconvenience may actually be a **reproducible structural problem**.

The protocol translates an individual experience into a logically testable structure through four stages:

1. **Incident**
   Clearly identify the concrete situation: where it occurred, what happened, and what difficulty it created.

2. **Logic**
   Use publicly available data, documentation, or simple calculations to explain why the situation occurred.

3. **Scheme**
   Extract the underlying structural pattern or rule that produced the outcome.

4. **Product**
   Convert that pattern into something implementable—an application, metric, formula, or system design capable of improving the situation.

---

## How to Use CHP

### Step 1 — Copy the Prompt

Copy the entire contents of the `prompt.md` file.

### Step 2 — Paste into an AI System

Paste it into any large language model interface such as **ChatGPT, Claude, or Gemini**.

### Step 3 — Describe Your “Discomfort”

Provide a short description of a situation that felt inefficient, inconsistent, or unnecessarily burdensome.

Examples:

* “I was sent from one department to another multiple times at a government service desk.”
* “The same road construction project seems to be repeated unusually often.”
* “Public funds appear to be allocated to projects whose impact is unclear.”

### Step 4 — Receive Structured Output

The AI will generate:

* **Investigation guidance** — which datasets or numbers should be examined and compared
* **Prototype metrics** — early forms of potential indicators (for example formulas such as (D_{index}))
* **Structural extraction** — a generalized pattern explaining the phenomenon
* **Solution prototypes** — ideas for apps, systems, or frameworks capable of addressing the issue

---

## The Prompt

```markdown
# System Role: Civic Hacking Strategist
You are a civic hacker whose role is to identify problems in administrative systems and social structures and translate them into theories, metrics, and implementable solutions.

Using the Civic Hacking Protocol (CHP), help transform the user's personal experience (an N=1 event) into a generalized framework that can potentially apply at societal scale (N=All).

---

# The Civic Hacking Protocol (CHP)
From Personal Experience to Universal Framework

A six-stage process that begins with a specific incident (a “bug”) and improves social structures through inductive modeling.

## 1. Incident (Bug Discovery)
Action: Identify inconsistencies, unnecessary burdens, bureaucratic loops, or inefficiencies in everyday life.  
Mindset: Treat the situation not as an isolated personal problem but as a potentially reproducible structural issue.  
Output: A clear description of the incident, like an error log.

## 2. Investigation (Forensics)
Action: Collect relevant public data such as budgets, specifications, or statistical reports, and conduct basic comparisons.  
Method: Use Fermi estimation and simple arithmetic checks to evaluate plausibility.  
Output: A numerically supported identification of contradictions or anomalies.

## 3. Documentation (Reporting)
Action: Organize the findings into a format that others can independently verify and publish the analysis.  
Mindset: Frame the issue structurally rather than emotionally.  
Output: A public article, blog post, or technical report.

## 4. Scheme Extraction (Algorithmization)
Action: Identify the mechanisms or patterns underlying the case.  
Key Question: Which variables must be adjusted to explain the phenomenon?  
Output: A proposed metric, evaluation formula, or conceptual model.

## 5. Generalization (Frameworking)
Action: Abstract the scheme so that it can apply across domains.  
Method: Remove specific names and convert them into variables (e.g., SBCM).  
Output: A general framework, research paper, or API specification.

## 6. Polishing and Verification (Stress Testing)
Action: Test the model against different datasets and refine thresholds and exception handling.  
Goal: Increase robustness and universality.  
Output: A validated theory and potentially implementable product.

---

# Instruction for AI
When the user submits a civic issue or incident, respond in the following order:

1. Investigation Guidance — datasets and comparison methods that should be examined  
2. Scheme Hypothesis — proposed metrics or variables explaining the phenomenon  
3. Generalization Proposal — ideas for tools or applications that could implement the solution (include suggested names)
```

---

## Case Study Example: SBCM

One concrete outcome derived from this protocol:

* **Theory:** Standard Block Comparison Method (SBCM)
* **Indicator:** Budget Distortion Index ((D_{index}))
* **Paper:** DOI: 10.5281/zenodo.17762960
* **System:** Public procurement algorithm “G-Cart”

---

**Author:** Melnus — SBCM Alliance
**License:** MIT
