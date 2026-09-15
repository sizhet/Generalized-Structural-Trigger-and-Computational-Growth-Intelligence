# GST-CGI-005 — Leaf Sandbox Package and Delegated Structural Unfolding

## From Answer-as-a-Service to Policy-Bounded Structural-Computation-as-a-Service

**Project:** Generalized Structural Trigger and Computational Growth Intelligence (GST-CGI)
**Subtitle:** From Two-Way CCC and Leaf Resolution to Delegated Unfolding and AI Computational-System Growth
**Document:** GST-CGI-005
**Status:** Research Note / Delegated Runtime Architecture
**Version:** 1.0

---

## Abstract

GST-CGI-004 introduced the Leaf Resolution Gate and four explicit outcomes:

```text
DECIDE
REFINE
LEFTOVER
DELEGATE
```

The first three remain primarily inside the structural runtime.

The fourth opens a different computational model.

When a localized leaf contains useful structural context but is not itself sufficient for the caller's final task, the runtime may package a policy-approved projection of that leaf and allow another application, specialized AI, or computational service to continue computation.

This article introduces the **Leaf Sandbox Package (LSP)**.

An LSP is not a serialized copy of an internal leaf.

It is a deliberately constructed, bounded, evidence-bearing, policy-governed computational package derived from a leaf for a specific delegated task.

Conceptually:

```text
LSP
=
Structural Context
+
Generalized Trigger
+
Evidence
+
Permitted Behavior
+
Policy
+
Capability Boundary
+
Runtime Contract
```

The central security and governance principle is:

> **Export capability, not authority.**

The delegated caller may receive sufficient local structure to perform useful computation without receiving unrestricted authority over the parent CCC, global structural memory, Policy Control Plane, structural promotion process, or unrelated runtime resources.

This creates **Delegated Structural Unfolding**:

```text
Folded Structural Memory
        ↓
Localization
        ↓
Leaf
        ↓
Policy Projection
        ↓
Leaf Sandbox Package
        ↓
External AI / Application
        ↓
Local Unfolding
        ↓
Result + Evidence + Delta
        ↓
Parent Runtime
```

The architecture moves structural intelligence beyond Answer-as-a-Service toward **Structural-Computation-as-a-Service**.

More importantly, delegated computation can return new evidence, counter-evidence, candidate differences, and computational structures. These outputs can later participate in Delta Intelligence and policy-governed structural promotion.

Thus the LSP is not merely an interoperability mechanism.

It is a bridge from localized structural intelligence to distributed computational growth.

---

# 1. The DELEGATE Branch

GST-CGI-004 established:

```text
                    LEAF
                      |
                      v
             Leaf Resolution Gate
                      |
       +--------------+--------------+--------------+
       |              |              |              |
       v              v              v              v
    DECIDE         REFINE         LEFTOVER       DELEGATE
```

`DELEGATE` is appropriate when:

> The current leaf contains useful localized structural knowledge, but another authorized computational system is better positioned to continue the task.

This creates an immediate question:

> What exactly should be delegated?

The answer should not be:

```text
the entire parent runtime
```

Nor should it generally be:

```text
the internal leaf object itself
```

Instead, the parent runtime constructs a bounded computational artifact:

> **Leaf Sandbox Package.**

---

# 2. Internal Leaf Is Not Exported LSP

This distinction is foundational:

> **Internal Leaf ≠ Exported LSP**

An internal leaf may contain:

```text
private runtime state

internal references

parent pointers

global memory handles

administrative metadata

policy internals

mutable structures

unrelated evidence

privileged behavior
```

Those should not automatically cross the delegation boundary.

Instead:

```text
Internal Leaf
     |
     v
Policy Projection
     |
     v
Capability Reduction
     |
     v
Evidence Selection
     |
     v
Behavior Selection
     |
     v
Sandbox Construction
     |
     v
Exported LSP
```

Thus an LSP is a **derived computational projection**, not a raw serialized node.

---

# 3. Why Return More Than an Answer?

Traditional AI services usually expose:

```text
Request
   |
   v
Model / Runtime
   |
   v
Answer
```

This is useful but limited.

The caller receives the product of computation but not necessarily the local computational structure that produced it.

GST-CGI introduces another possibility:

```text
Request
   |
   v
Structural Runtime
   |
   v
Localization
   |
   v
Leaf
   |
   v
LSP
   |
   v
Caller Continues Computation
```

The runtime can therefore return not only:

```text
What I concluded
```

but potentially:

```text
The bounded local structural machinery
with which you may continue computing.
```

This is a significant change in the AI service model.

---

# 4. Answer-as-a-Service vs Structural-Computation-as-a-Service

The distinction can be summarized as:

```text
Answer-as-a-Service

Input
  |
  v
AI
  |
  v
Result
```

versus:

```text
Structural-Computation-as-a-Service

Input
  |
  v
Structural Localization
  |
  v
Relevant Leaf
  |
  v
Leaf Sandbox Package
  |
  v
Caller-Specific Computation
  |
  v
Result
```

The second model gives the caller more computational agency while preserving structural boundaries.

This is particularly useful when the parent runtime possesses strong localization knowledge but the caller possesses superior task-specific computation.

---

# 5. Canonical LSP Model

A conceptual LSP can be represented as:

```text
LSP = <C, T, E, B, P, K, R>
```

where:

```text
C = Structural Context

T = Generalized Structural Trigger

E = Evidence Bundle

B = Permitted Behavior

P = Policy Projection

K = Capability Boundary

R = Runtime Contract
```

Optionally:

```text
I = Identity / Provenance
X = Expiration / Validity
Q = Resource Quota
A = Audit Contract
```

may also be included.

A richer representation is therefore:

```text
LSP+
=
<C, T, E, B, P, K, R, I, X, Q, A>
```

Again, the notation is conceptual.

The important point is that delegation exports an explicit contract.

---

# 6. Structural Context

The first LSP component is the local structural context.

This answers:

> Where in the structural system did this package come from?

It may contain:

```text
Local CCC identity

Relevant parent difference

Current leaf identity

Local structural neighborhood

Selected context

Applicable constraints

UTN / structural naming information

Version information
```

But it should not automatically expose the entire parent tree.

Conceptually:

```text
Global Structural Memory
          |
          v
      Localization
          |
          v
        Leaf
          |
          v
   Local Projection
          |
          v
Structural Context
```

This preserves locality.

---

# 7. Generalized Structural Trigger

The LSP may contain a projected Generalized Structural Trigger.

Recall:

```text
GST
=
Structural State
+
Comparison
+
Behavior
+
Evidence
+
Policy Perspective
```

The exported version may be reduced.

For example:

```text
Internal GST
   |
   +-- compare()
   +-- mutate()
   +-- queryGlobalMemory()
   +-- promote()
   +-- explain()
```

may become:

```text
Exported GST
   |
   +-- compare()
   +-- explain()
```

The package therefore exports only the behavior necessary for the delegated task.

---

# 8. Evidence Bundle

An LSP should normally carry enough evidence to make the delegated computation meaningful.

Possible components include:

```text
positive evidence

counter-evidence

comparison traces

structural matches

known conflicts

uncertainty

provenance

validation state
```

This avoids forcing the delegated caller to treat the package as an unexplained oracle.

Conceptually:

```text
Leaf
 |
 +-- Structural Result
 |
 +-- Why
 |
 +-- Why Not
 |
 +-- What Is Unknown
 |
 v
Evidence Bundle
```

This is particularly important when the external caller may generate further structural conclusions.

---

# 9. Permitted Behavior

An LSP may contain behavior.

But only selected behavior.

Examples:

```text
compare local candidate

evaluate local constraint

calculate structural metric

simulate bounded local outcome

query included evidence

generate explanation

test candidate difference
```

The package should not automatically permit:

```text
modify parent tree

modify global memory

change policy

create unrestricted network actions

promote itself

change capability boundary

access unrelated nodes
```

This produces the principle:

> **Delegation exports computation, not unrestricted execution.**

---

# 10. Export Capability, Not Authority

This is the central LSP principle:

> **Export capability, not authority.**

Capability answers:

> What computation may this package perform?

Authority answers:

> What system state may this package control or modify?

These are different.

For example:

```text
Capability:
    compare candidate trajectories

Authority:
    modify global trajectory memory
```

The first may be delegated.

The second may remain with the parent runtime.

Likewise:

```text
Capability:
    test code against local CallingGraph constraints

Authority:
    certify the modified production system
```

The first may be exported.

The second should remain governed separately.

---

# 11. Capability Boundary

An LSP should therefore define an explicit capability boundary.

For example:

```text
LSP Capabilities
 |
 +-- READ_LOCAL_CONTEXT
 |
 +-- READ_EVIDENCE
 |
 +-- COMPARE
 |
 +-- COMPUTE_METRIC
 |
 +-- SIMULATE_LOCAL
 |
 +-- EXPLAIN
 |
 +-- PROPOSE_DELTA
```

while excluding:

```text
MODIFY_PARENT_MEMORY

CHANGE_POLICY

PROMOTE_STRUCTURE

ACCESS_UNRELATED_CONTEXT

AUTHORIZE_ACTION

EXPAND_CAPABILITY

DISABLE_AUDIT
```

The boundary itself should be part of the package contract.

---

# 12. Policy Projection

The parent Policy Control Plane may contain far more information than the delegated caller needs.

Therefore the LSP should carry a **Policy Projection**, not necessarily the full policy system.

Conceptually:

```text
Global Policy Control Plane
            |
            v
      Policy Projection
            |
            v
            LSP
```

The projection may specify:

```text
allowed operations

forbidden operations

evidence requirements

resource limits

privacy constraints

decision limits

delegation limits

expiration

return requirements
```

This permits local execution without exporting global governance authority.

---

# 13. Runtime Contract

The LSP also needs a Runtime Contract.

The contract answers:

```text
What inputs are accepted?

What outputs are expected?

What behavior is permitted?

What evidence must be returned?

What resource limits apply?

What constitutes failure?

What must remain immutable?

When does the package expire?
```

A conceptual contract may resemble:

```text
RuntimeContract
 |
 +-- Input Schema
 +-- Output Schema
 +-- Allowed Operations
 +-- Evidence Return Requirement
 +-- Resource Quota
 +-- Timeout
 +-- Side-Effect Policy
 +-- Audit Requirement
```

This turns the package into a well-defined computational object.

---

# 14. Sandbox Means Isolation

The word **Sandbox** is important.

An LSP should execute within an isolation boundary appropriate to its capability.

Conceptually:

```text
Parent Runtime
      |
      |  Export
      v
+-------------------------+
|       LSP Sandbox       |
|                         |
|  Structural Context     |
|  Trigger                |
|  Evidence               |
|  Permitted Behavior     |
|  Policy Projection      |
|  Capability Boundary    |
|                         |
+-------------------------+
      |
      v
External Caller
```

The caller can operate inside the permitted local world.

It does not automatically gain access to the parent world.

---

# 15. A Local Computational World

This suggests a useful interpretation:

> **An LSP is a small policy-bounded computational world generated from a structural leaf.**

It contains enough:

```text
structure

context

evidence

behavior

rules
```

to perform a specific local computation.

But it deliberately omits unrelated authority.

This creates a powerful balance:

```text
Useful Local Intelligence
          +
Strong Boundary
```

rather than:

```text
Full Runtime Export
```

---

# 16. LSP Generation

The package should be generated dynamically from:

```text
Leaf
+
Caller
+
Task
+
Policy
+
Current Evidence
```

Thus:

```text
LSP
=
Package(
    Leaf,
    Caller,
    Task,
    Policy,
    Evidence
)
```

The same leaf may produce different packages for different callers.

Example:

```text
                    Same Leaf
                       |
          +------------+------------+
          |                         |
          v                         v
      Caller A                   Caller B
          |                         |
     Policy A                    Policy B
          |                         |
          v                         v
       LSP-A                     LSP-B
```

This prevents the leaf from being treated as a static downloadable executable object.

---

# 17. Caller-Specific Projection

Suppose a leaf contains:

```text
Market Structural Context
```

A portfolio optimizer may receive:

```text
trajectory structure

risk evidence

correlation evidence

scenario behavior
```

A visualization tool may receive:

```text
trajectory structure

structural labels

evidence references

explanation behavior
```

A learning process may receive:

```text
candidate differences

counter-evidence

unresolved cases
```

The source leaf is the same.

The exported computational projection differs.

Thus:

> **Delegation should be task- and caller-relative.**

---

# 18. Delegated Structural Unfolding

Once an LSP is exported, another system may continue computation.

This process is **Delegated Structural Unfolding**.

```text
Folded Structural Memory
        |
        v
Structural Localization
        |
        v
Leaf
        |
        v
LSP
        |
        v
External AI
        |
        v
Local Structural Unfolding
        |
        v
Task-Specific Result
```

The external AI does not begin from raw global information.

It begins from a structurally localized computational package.

This can substantially reduce the search space.

---

# 19. Folding and Delegated Unfolding

The architecture creates a natural relationship:

```text
Historical Experience
       |
       v
Structural Folding
       |
       v
Folded Structural Memory
       |
       v
Localization
       |
       v
Leaf
       |
       v
LSP
       |
       v
Delegated Unfolding
       |
       v
New Computation
```

Thus structural memory can serve as a source of task-specific computational packages.

This is stronger than ordinary retrieval.

The system retrieves not only information but a local computational structure.

---

# 20. Retrieval vs Structural Delegation

Traditional retrieval resembles:

```text
Query
  |
  v
Retrieve Documents / Records
  |
  v
Caller Computes
```

Structural delegation resembles:

```text
Query
  |
  v
Structural Localization
  |
  v
Retrieve Local Structure
  +
  Evidence
  +
  Behavior
  +
  Policy
  |
  v
Caller Computes
```

Therefore:

> **LSP delegation is closer to retrieving a bounded computational structure than retrieving a passive record.**

This distinction is central to GST-CGI.

---

# 21. Delegated Unfolding and AI Agents

An LSP may be especially useful to an AI agent.

Instead of giving the agent:

```text
entire database

entire repository

entire structural memory

unrestricted tools
```

the runtime may provide:

```text
Relevant Structural Context
+
Relevant Evidence
+
Allowed Operations
+
Local Constraints
+
Specific Objective
```

Conceptually:

```text
Large Environment
       |
       v
Structural Localization
       |
       v
Minimal Relevant LSP
       |
       v
Agent
```

This can improve both efficiency and governance.

---

# 22. Example: AI Coding LSP

Consider a coding task.

The structural runtime localizes the request to:

```text
CallingGraph Leaf
```

The LSP may contain:

```text
Target Function

Relevant Callers

Relevant Callees

Required Calling Paths

Type Constraints

Certified Structural Invariants

Local Tests

Runtime Evidence

Permitted Files

Permitted Mutation Scope
```

The coding agent receives:

```text
LSP
   |
   v
Generate Candidate Patch
   |
   v
Run Permitted Tests
   |
   v
Return:
    patch
    evidence
    test results
    structural delta
```

The coding agent does not automatically receive authority to:

```text
merge

deploy

change certification policy

modify unrelated code
```

This is a concrete example of:

> **Export capability, not authority.**

---

# 23. Example: Market Analysis LSP

Suppose the structural runtime localizes a market condition to:

```text
High-Volatility
Event-Driven
Positive-Momentum
Leaf
```

An LSP for a portfolio AI may contain:

```text
Relevant trajectory

Event context

Pattern neighborhood

Positive evidence

Counter-patterns

Risk constraints

Allowed scenario simulations

Position-size limits
```

The external AI may calculate:

```text
candidate allocation

scenario sensitivity

expected risk

counterfactual result
```

But the package may prohibit:

```text
placing trades

changing risk policy

accessing unrelated accounts

changing structural memory
```

Again:

```text
Computation
!=
Authority
```

---

# 24. Example: Scientific Structural LSP

A scientific structural runtime may localize a candidate phenomenon near:

```text
Known Structural Family
```

The LSP may expose:

```text
relevant measurements

candidate structural model

known supporting cases

counterexamples

comparison metrics

permitted simulations
```

A specialized scientific model may perform:

```text
parameter search

simulation

counter-example generation

hypothesis comparison
```

and return new evidence.

The parent runtime can then decide whether any new structure should be accepted.

---

# 25. Evidence Return Is Mandatory for Growth

A delegated caller should not merely return:

```text
Result
```

A richer return contract is:

```text
DelegatedResult
 |
 +-- Result
 |
 +-- Supporting Evidence
 |
 +-- Counter-Evidence
 |
 +-- Trace
 |
 +-- Uncertainty
 |
 +-- Candidate Delta
```

This is especially important if delegated computation may later contribute to structural growth.

Thus:

> **Delegated computation may propose structural knowledge, but it should return the evidence needed to evaluate that proposal.**

---

# 26. Result vs Candidate Delta

The external caller may produce two different kinds of output.

### Task Result

For example:

```text
recommended patch

portfolio recommendation

simulation result

classification
```

### Candidate Structural Delta

For example:

```text
new structural difference

new counter-example

new metric relationship

new local CCC candidate

new behavioral trigger candidate
```

These should not be treated identically.

A task result may be immediately useful.

A candidate structural delta requires validation before entering shared structural memory.

---

# 27. External Delta Does Not Equal Structural Truth

This principle should be explicit:

```text
External AI Output
        !=
Structural Promotion
```

Instead:

```text
External AI
    |
    v
Candidate Delta
    |
    v
Evidence
    |
    v
Validation
    |
    v
Policy Review
    |
    v
Promotion / Rejection / Leftover
```

This preserves the parent runtime's structural authority.

---

# 28. Delegation Return Loop

The full loop becomes:

```text
Parent Runtime
      |
      v
     Leaf
      |
      v
     LSP
      |
      v
External AI
      |
      v
Delegated Unfolding
      |
      v
Result + Evidence + Delta
      |
      v
Parent Validation
      |
      +-- Accept Result
      |
      +-- Reject Result
      |
      +-- Request Refinement
      |
      +-- Store Leftover
      |
      +-- Candidate Structural Promotion
```

This turns delegation into a controlled two-way computational relationship.

---

# 29. LSP Provenance

An LSP should ideally carry provenance.

Possible fields include:

```text
Parent Structural Version

Leaf Identity

Policy Version

Trigger Version

Evidence Version

Generation Time

Caller Identity

Task Identity
```

Why?

Because structural systems evolve.

An LSP generated from yesterday's structural memory may not remain valid after significant changes.

Thus delegated computation should be attributable to a particular structural state.

---

# 30. LSP Expiration

An LSP should not necessarily remain valid forever.

Possible expiration conditions include:

```text
time limit

parent structure changed

policy changed

evidence changed

caller authorization changed

task completed

resource quota exhausted
```

Conceptually:

```text
LSP
 |
 +-- Valid
 |
 +-- Expired
 |
 +-- Revoked
```

This becomes important in dynamic systems.

---

# 31. Revocation

Policy governance should allow an LSP capability to be revoked where the runtime architecture supports it.

Reasons may include:

```text
policy update

security concern

new counter-evidence

structural invalidation

caller authorization change

resource exhaustion
```

This reinforces:

> **Delegation is a bounded grant of computation, not a permanent transfer of authority.**

---

# 32. Resource Quotas

A sandbox package may also define resource limits:

```text
CPU / compute budget

memory budget

model-call budget

token budget

tool-call budget

network access

storage limit

execution time
```

This is important because behavioral triggers and delegated agents may otherwise expand computation without bound.

A bounded package therefore includes both:

```text
Semantic Boundary
```

and:

```text
Resource Boundary
```

---

# 33. Side-Effect Boundary

The runtime should distinguish between:

```text
Pure / Read-Only Computation
```

and:

```text
Side-Effecting Computation
```

A simple LSP may permit only:

```text
read

compare

simulate

explain
```

A stronger LSP may permit controlled side effects.

But those should be explicit.

For example:

```text
Allowed:
    write temporary sandbox file

Forbidden:
    modify parent repository
```

The principle is:

> **Side effects must be capabilities, not assumptions.**

---

# 34. LSP and User Plugins

Generalized Structural Trigger plugins fit naturally inside LSP.

A user may define:

```text
Domain Trigger

Domain Comparator

Evidence APIs

Domain Behavior
```

The parent runtime can package only the relevant portions.

Thus:

```text
Expert Knowledge
      |
      v
GST Plugin
      |
      v
Structural Localization
      |
      v
Leaf
      |
      v
Policy-Bounded LSP
      |
      v
External AI
```

This creates a path for expert knowledge to become reusable AI computational structure.

---

# 35. From Expert Knowledge to AI Infrastructure

Traditionally, expert knowledge may enter AI as:

```text
documents

labels

rules

prompts

examples
```

GST-CGI adds another form:

```text
Executable Structural Knowledge
```

through:

```text
Trigger
+
Comparator
+
Evidence APIs
+
Behavior
+
Policy Contract
```

When such knowledge can be localized and packaged into LSPs, it begins to function as reusable computational infrastructure.

This is an important expansion of the role of human expertise.

---

# 36. Structural Service Composition

Multiple structural services may compose.

For example:

```text
Structural Service A
        |
        v
      LSP-A
        |
        v
Structural Service B
        |
        v
      LSP-B
        |
        v
Specialized AI
```

Or:

```text
Market Structure Service
          +
Risk Structure Service
          +
Policy Service
          |
          v
Composite LSP
          |
          v
Portfolio AI
```

This suggests a future ecosystem of composable structural computation.

---

# 37. Composite LSPs

A future runtime may construct an LSP from several structural sources.

Conceptually:

```text
Leaf A
  +
Leaf B
  +
Leaf C
  |
  v
Compatibility Check
  |
  v
Policy Composition
  |
  v
Composite LSP
```

This requires difficult future research:

```text
policy compatibility

evidence provenance

conflicting structures

capability intersection

identity

versioning

resource composition
```

But the possibility follows naturally from the LSP model.

---

# 38. LSP as a Structural API

Another useful interpretation is:

> **LSP is a runtime-generated structural API.**

Traditional APIs expose predefined functions:

```text
GET /price

POST /order

search(query)
```

An LSP may instead expose a task-specific local structural interface:

```text
compareCandidate()

queryEvidence()

testConstraint()

simulateLocal()

proposeDelta()
```

The interface is generated from the current structural location and policy.

Thus the API itself may be structurally localized.

---

# 39. Static API vs Structural API

Traditional API:

```text
Designed once
    |
    v
Same interface
for many calls
```

Structural API:

```text
Runtime Localization
        |
        v
Leaf
        |
        v
Policy Projection
        |
        v
Task-Specific Interface
```

This creates the possibility of **on-the-fly computational interfaces**.

The interface is not arbitrary.

It is derived from folded structural knowledge.

---

# 40. LSP as a Computational Capsule

A useful conceptual name for the LSP is:

> **Computational Capsule**

because it packages:

```text
what is known

what can be computed

what evidence exists

what is uncertain

what is permitted

what must not be touched
```

into one bounded runtime object.

The capsule can travel farther than an internal node without carrying the entire system with it.

---

# 41. Structural Compression Before Export

The parent runtime may also compress an LSP before export.

For example:

```text
Rich Leaf
   |
   v
Policy Projection
   |
   v
Structural Compression
   |
   v
Compact LSP
```

This may use:

```text
DNA

UTN

structural hashes

metric summaries

local graph fragments

selected evidence
```

Thus the same principles developed for GST encoding apply again at the package level.

---

# 42. Minimal LSP

A Minimal Experimental Tool may start with a very small package:

```text
Minimal LSP
 |
 +-- Leaf ID
 +-- Local Context
 +-- Trigger
 +-- Evidence
 +-- Allowed Operation
 +-- Return Schema
```

For example:

```java
public interface LeafSandboxPackage<T, R> {

    String leafId();

    T context();

    EvidenceSet evidence();

    CapabilitySet capabilities();

    R execute(
        SandboxRequest request
    );
}
```

This is sufficient to demonstrate the architecture without building a complete distributed sandbox platform.

---

# 43. Rich LSP

A more mature implementation may include:

```text
LeafSandboxPackage
 |
 +-- Identity
 +-- Provenance
 +-- Structural Context
 +-- GST Projection
 +-- Evidence Bundle
 +-- Counter-Evidence
 +-- Permitted Behavior
 +-- Policy Projection
 +-- Capability Set
 +-- Resource Quota
 +-- Runtime Contract
 +-- Audit Contract
 +-- Expiration
 +-- Revocation Handle
 +-- Return Contract
```

The framework can evolve progressively from the minimal form.

---

# 44. Delegated Unfolding Is Not Autonomous Structural Growth

This boundary must remain explicit.

Delegated unfolding means:

```text
Use existing structural knowledge
to perform bounded new computation.
```

Structural growth means:

```text
Modify or extend the mature structural knowledge itself.
```

Therefore:

```text
DELEGATE
!=
PROMOTE
```

An external AI may discover something important.

It still returns a candidate.

The parent structural-growth process decides whether that candidate becomes mature structure.

---

# 45. Delegated Computation as Evidence Generation

This leads to another interpretation.

An LSP is not merely a way to obtain an answer.

It can be a way to deliberately generate evidence.

For example:

```text
Leaf
 |
 v
LSP
 |
 v
External Simulation
 |
 v
Evidence
 |
 v
Parent Runtime
```

The parent may delegate specifically because:

> More evidence is needed before structural resolution or growth.

Thus delegation can support both:

```text
Decision Computation
```

and:

```text
Evidence Generation
```

---

# 46. Delegation Can Feed Counter-Evidence

A delegated system should also be able to return evidence against the parent hypothesis.

For example:

```text
Parent Leaf:
Candidate resembles Branch A
```

The LSP may ask an external process to test:

```text
Can you find conditions
under which Branch A fails?
```

The result may be:

```text
Counter-Evidence
```

This connects Delegated Unfolding directly with Counter-Evidence Intelligence.

---

# 47. Delegation Can Feed Delta Intelligence

Repeated delegated computations may reveal a stable distinction.

For example:

```text
LSP Run 1 → Delta X
LSP Run 2 → Delta X
LSP Run 3 → Delta X
LSP Run 4 → Delta X
```

The runtime may detect:

```text
Repeated Candidate Difference
```

which becomes an input to:

```text
Delta Intelligence
```

and eventually:

```text
Candidate Two-Way CCC
```

Thus external computation can contribute to internal structural growth without directly controlling it.

---

# 48. From Structural Delegation to Computational Growth

The growth path now becomes visible:

```text
Experience
    |
    v
Structural Folding
    |
    v
Structural Memory
    |
    v
Localization
    |
    v
Leaf
    |
    v
LSP
    |
    v
Delegated Computation
    |
    v
Result + Evidence + Delta
    |
    v
Validation
    |
    v
New Structural Difference
    |
    v
New Computational Structure
```

This is the bridge toward **Computational Growth Intelligence**.

---

# 49. AI Serving AI

The architecture also creates a different AI ecosystem.

Instead of:

```text
Human
  |
  v
AI
  |
  v
Answer
```

we may have:

```text
Human / Application
        |
        v
Structural AI
        |
        v
       LSP
        |
        v
Specialized AI
        |
        v
Result / Evidence / Delta
        |
        v
Structural AI
```

Or even:

```text
AI-A
 |
 v
LSP
 |
 v
AI-B
 |
 v
LSP
 |
 v
AI-C
```

AI systems can therefore serve other AI systems with localized structural computation.

---

# 50. Why This Is More Than Agent Tool Use

An agent calling a tool usually invokes a predefined capability.

GST-CGI delegation adds structural localization before capability exposure.

The sequence is:

```text
Context
  |
  v
Structural Search
  |
  v
Relevant Leaf
  |
  v
Policy Projection
  |
  v
Generated Computational Package
  |
  v
Agent
```

Thus the available computational structure itself may depend on where the request is localized.

This is more dynamic than a fixed tool registry.

---

# 51. The Parent Runtime Remains the Structural Authority

Despite this flexibility, the architectural boundary remains:

```text
External Caller
      |
      v
Local Computation
      |
      v
Proposal / Evidence
```

while:

```text
Parent Runtime
      |
      v
Validation
      |
      v
Policy
      |
      v
Structural Authority
```

Therefore:

> **Delegated intelligence may expand computation without automatically expanding authority.**

This allows the system to become more capable while retaining explicit control boundaries.

---

# 52. Canonical LSP Principles

The architecture can now be summarized through a set of principles.

## Principle 1 — Internal Leaf Is Not Exported LSP

> **An LSP is a policy-derived projection of an internal leaf, not a raw serialization of the leaf.**

---

## Principle 2 — Export Capability, Not Authority

> **Delegation grants bounded computational capability without automatically transferring structural or action authority.**

---

## Principle 3 — LSP Is Task-Relative

> **The same leaf may produce different LSPs for different callers, tasks, and policies.**

---

## Principle 4 — Evidence Travels with Computation

> **Delegated structural computation should carry sufficient evidence and uncertainty context for meaningful downstream use.**

---

## Principle 5 — Behavior Is Explicitly Bounded

> **Only explicitly permitted behavior should cross the sandbox boundary.**

---

## Principle 6 — Policy Is Projected, Not Surrendered

> **The LSP receives the policy constraints required for local execution without receiving control of the parent Policy Control Plane.**

---

## Principle 7 — Side Effects Are Capabilities

> **External effects must be explicitly granted rather than implicitly available.**

---

## Principle 8 — Delegated Output Is Not Structural Truth

> **External results and deltas remain candidates until validated and promoted by the governed parent runtime.**

---

## Principle 9 — Delegation Can Generate Evidence

> **An LSP may be used not only to produce decisions but also to generate supporting evidence, counter-evidence, and candidate structural differences.**

---

## Principle 10 — A Leaf Can Become a Computational Service

> **A structurally localized leaf may serve as the source of an on-the-fly, policy-bounded computational interface.**

---

# 53. Canonical Delegated-Unfolding Architecture

The complete architecture developed in this article is:

```text
                 POLICY CONTROL PLANE
                         |
                         v
                 Structural Runtime
                         |
                         v
                 Metric Localization
                         |
                         v
                    Two-Way CCC
                         |
                         v
                        LEAF
                         |
                         v
                Leaf Resolution Gate
                         |
                         v
                      DELEGATE
                         |
                         v
                  LSP GENERATOR
                         |
          +--------------+--------------+
          |              |              |
          v              v              v
      Context         Evidence       GST Projection
          |              |              |
          +--------------+--------------+
                         |
                    Policy Projection
                         |
                    Capability Boundary
                         |
                    Runtime Contract
                         |
                         v
              LEAF SANDBOX PACKAGE
                         |
                         v
                External AI / Caller
                         |
                         v
               Delegated Unfolding
                         |
                         v
        Result + Evidence + Counter-Evidence
                         +
                  Candidate Delta
                         |
                         v
                   Parent Runtime
                         |
             +-----------+-----------+
             |           |           |
             v           v           v
          Accept      Leftover    Validate Delta
                                     |
                                     v
                              Structural Growth
```

---

# 54. From Answer to Computational Structure

The progression can now be stated clearly.

### Stage 1

```text
AI returns data.
```

### Stage 2

```text
AI returns an answer.
```

### Stage 3

```text
AI returns a recommendation.
```

### Stage 4

```text
AI returns evidence.
```

### Stage 5

```text
AI returns a bounded computational structure.
```

At Stage 5, the caller can continue computation rather than merely consume the parent's conclusion.

This is a qualitatively different service boundary.

---

# 55. From Computational Structure to Computational Growth

The deeper consequence appears when delegated computation feeds structural evolution.

```text
LSP
 |
 v
External Computation
 |
 v
Evidence / Delta
 |
 v
Validation
 |
 v
New CCC
 |
 v
New Trigger
 |
 v
New Leaf
 |
 v
New LSP
```

The system is no longer only reusing fixed computational structures.

It can potentially grow the structures from which future computation is delegated.

This is the bridge from:

> **Structural Computation**

to:

> **Computational Growth Intelligence.**

---

# 56. Conclusion

The `DELEGATE` branch of the Leaf Resolution Gate creates a new structural-intelligence service model.

A leaf does not need to terminate computation.

It can become the source of a bounded computational package.

That package is the **Leaf Sandbox Package**:

```text
LSP
=
Structural Context
+
Generalized Trigger
+
Evidence
+
Permitted Behavior
+
Policy Projection
+
Capability Boundary
+
Runtime Contract
```

The LSP is not the internal leaf itself.

It is a caller-, task-, and policy-specific projection.

The parent runtime exports only what is necessary for useful delegated computation.

The governing principle is:

> **Export capability, not authority.**

The delegated caller may compare, simulate, test, explain, generate evidence, or propose structural deltas.

It does not automatically receive authority to mutate the parent structural memory, change policy, promote its own conclusions, or expand its own capabilities.

The complete loop becomes:

```text
Folded Structural Memory
        |
        v
Structural Localization
        |
        v
Leaf
        |
        v
Leaf Sandbox Package
        |
        v
Delegated Structural Unfolding
        |
        v
Result
+
Evidence
+
Counter-Evidence
+
Candidate Delta
        |
        v
Governed Parent Runtime
```

This moves the architecture beyond:

```text
Answer-as-a-Service
```

toward:

```text
Structural-Computation-as-a-Service
```

and creates the possibility of:

```text
AI
serving
AI
with
localized computational structure
```

But an even larger question now appears.

If Leftover cases and delegated computations repeatedly expose new differences, how should those differences become mature structural components?

How does:

```text
unresolved experience
```

become:

```text
new difference
```

and then:

```text
new CCC
```

and eventually:

```text
new computational structure?
```

That is the subject of:

**GST-CGI-006 — From Leftover and Delta Intelligence to Structural Growth.**

---

## Project Reading Path

```text
GST-CGI-001
From DNA Trigger to
Generalized Structural Trigger
        |
        v
GST-CGI-002
Generalized Structural Trigger:
Evidence, Behavior, and Policy
        |
        v
GST-CGI-003
Two-Way CCC with
Generalized Structural Triggers
        |
        v
GST-CGI-004
Leaf Resolution:
Decide, Refine, Leftover, or Delegate
        |
        v
GST-CGI-005
Leaf Sandbox Package and
Delegated Structural Unfolding
        |
        v
GST-CGI-006
From Leftover and Delta Intelligence
to Structural Growth
        |
        v
GST-CGI-007
Computational Growth Intelligence
        |
        v
GST-CGI-008
From Computational-Structure Growth
to AI Computational Ecosystems
```

---

**GST-CGI — Generalized Structural Trigger and Computational Growth Intelligence**

**From Two-Way CCC and Leaf Resolution to Delegated Unfolding and AI Computational-System Growth**
