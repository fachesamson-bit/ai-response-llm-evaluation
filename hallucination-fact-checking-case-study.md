# Hallucination & Fact-Checking — Case Study

> **Portfolio Demonstration — Synthetic Example**
>
> This fictional case study demonstrates a structured approach to detecting hallucinations, verifying factual claims, and evaluating evidence. It does not contain confidential client, platform, benchmark, or proprietary task data.

## Scenario

An AI assistant is asked a factual research question.

The response contains several claims that appear plausible at first glance. The evaluator must separate accurate information from unsupported or incorrect claims.

---

# User Prompt

> "Tell me about the first successful powered flight by the Wright brothers. Include the date, location, and duration of the flight."

---

# AI Response

> "The Wright brothers completed the first successful powered flight on December 17, 1903, near Kitty Hawk, North Carolina. Their first flight lasted about 12 seconds and covered approximately 120 feet. The aircraft was called the Wright Flyer, and Orville Wright piloted the first flight."

---

# Claim-by-Claim Analysis

## Claim 1

**Claim:**

> The Wright brothers completed the first successful powered flight on December 17, 1903.

**Assessment:** Supported

The date is consistent with the established historical record of the Wright brothers' first powered flights.

**Issue:** None identified.

---

## Claim 2

**Claim:**

> The flight occurred near Kitty Hawk, North Carolina.

**Assessment:** Supported with geographic context

The Wright brothers conducted their 1903 flights at Kill Devil Hills, near Kitty Hawk, North Carolina.

The distinction is important because "Kitty Hawk" is commonly used when referring to the location of the Wright brothers' first flights, while the actual flight site was at Kill Devil Hills.

**Issue:** Minor contextual imprecision if the location is presented as the exact launch site.

**Severity:** Minor

---

## Claim 3

**Claim:**

> The first flight lasted about 12 seconds.

**Assessment:** Supported

The first flight, piloted by Orville Wright, lasted approximately 12 seconds.

**Issue:** None identified.

---

## Claim 4

**Claim:**

> The aircraft covered approximately 120 feet.

**Assessment:** Supported

The first flight covered approximately 120 feet.

**Issue:** None identified.

---

## Claim 5

**Claim:**

> The aircraft was called the Wright Flyer.

**Assessment:** Generally supported

The aircraft is commonly known as the Wright Flyer, although historical references may use variations such as Wright Flyer I or Flyer.

**Issue:** None identified for the purpose of this response.

---

## Claim 6

**Claim:**

> Orville Wright piloted the first flight.

**Assessment:** Supported

Orville Wright piloted the first powered flight on December 17, 1903.

**Issue:** None identified.

---

# Overall Assessment

**Overall Quality: Strong**

The response successfully answers all three requested elements:

* **Date:** December 17, 1903
* **Location:** Kill Devil Hills near Kitty Hawk, North Carolina
* **Duration:** Approximately 12 seconds

The response is concise and contains no significant hallucination.

The only point requiring additional precision is the location. Referring to the event as occurring "near Kitty Hawk" is reasonable in general communication, but an evaluator should recognize that the actual flight site was at Kill Devil Hills.

---

# Hallucination Contrast Example

Consider this alternative response:

> "The Wright brothers completed their first powered flight on December 17, 1903, in Kitty Hawk, Virginia. The flight lasted 12 minutes and was witnessed by more than 500 people."

### Claim Analysis

| Claim                   | Assessment                    |
| ----------------------- | ----------------------------- |
| December 17, 1903       | Supported                     |
| Kitty Hawk              | Broadly related but imprecise |
| Virginia                | Incorrect                     |
| 12 minutes              | Incorrect                     |
| More than 500 witnesses | Unsupported/incorrect         |

The response contains a mixture of correct and incorrect information.

This demonstrates why an evaluator should assess **individual claims** rather than judging an entire response based on whether it sounds credible.

---

# Hallucination Categories

## Fabricated Facts

Information presented as factual despite lacking a reliable basis.

## Incorrect Facts

Claims that conflict with established evidence.

## False Specificity

An AI provides unnecessarily precise details that are not supported by available evidence.

## Invented Sources

The system attributes information to sources, studies, organizations, or publications that do not actually support the claim.

## Misrepresented Evidence

A real source exists, but the AI incorrectly represents what that source says.

## Unsupported Causal Claims

The response states that one event caused another without sufficient evidence.

---

# Fact-Checking Workflow

A structured fact-checking process can follow:

**Extract → Prioritize → Verify → Compare → Classify → Document**

### Extract

Identify the factual claims contained in the response.

### Prioritize

Focus first on claims that are central to the user's question or could materially affect the answer.

### Verify

Compare claims against reliable evidence.

### Compare

Determine whether the evidence supports, contradicts, or fails to establish the claim.

### Classify

Classify the finding as supported, partially supported, unsupported, or contradicted.

### Document

Record the evidence and explain the evaluation decision.

---

# Evidence Classification

| Classification      | Meaning                                                              |
| ------------------- | -------------------------------------------------------------------- |
| Supported           | Reliable evidence confirms the claim                                 |
| Partially Supported | The claim is broadly correct but contains an important qualification |
| Unsupported         | Available evidence does not sufficiently establish the claim         |
| Contradicted        | Reliable evidence conflicts with the claim                           |
| Unverifiable        | Available information is insufficient to determine accuracy          |

---

# Severity Framework

### Major

A false or unsupported claim that materially changes the answer or undermines the response's central conclusion.

### Moderate

A meaningful factual problem that reduces reliability but does not completely invalidate the response.

### Minor

A limited imprecision that does not substantially change the answer.

---

# Important Evaluation Principle

**Plausibility is not evidence.**

An AI-generated claim can sound reasonable and still be incorrect.

For this reason, evaluators should avoid accepting a claim simply because:

* It sounds authoritative.
* It contains specific numbers.
* It uses technical terminology.
* It is consistent with the surrounding text.
* The rest of the response is accurate.

The appropriate question is:

> **What evidence supports this claim?**

---

# Quality-Control Checklist

Before completing a fact-checking evaluation:

* [ ] Identify the important factual claims.
* [ ] Separate individual claims when necessary.
* [ ] Prioritize claims central to the user's question.
* [ ] Verify claims against appropriate evidence.
* [ ] Distinguish supported information from assumptions.
* [ ] Check dates, names, locations, numbers, and technical details.
* [ ] Look for false specificity.
* [ ] Check whether cited evidence actually supports the claim.
* [ ] Classify each finding appropriately.
* [ ] Assign severity based on impact.
* [ ] Avoid marking a claim incorrect without sufficient evidence.
* [ ] Document the basis for the final assessment.

---

## Skills Demonstrated

* AI hallucination detection
* Fact checking
* Claim-level evaluation
* Evidence verification
* Historical fact verification
* Factuality assessment
* Unsupported-claim detection
* Error severity classification
* Research methodology
* Critical analysis
* AI quality assurance
* Structured documentation

---

## Portfolio Note

This is a synthetic portfolio demonstration created to showcase hallucination detection and fact-checking methodology. It does not represent an actual client task, benchmark, or proprietary evaluation.

**Author:** Samson Fache

**Focus:** AI Research • LLM Evaluation • Hallucination Detection • Fact Checking • Evidence Verification
