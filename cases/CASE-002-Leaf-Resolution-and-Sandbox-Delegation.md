# CASE-002 — Leaf Resolution and Sandbox Delegation

## From Structural Leaf to Policy-Bounded External Computation

**Project:** Generalized Structural Trigger and Computational Growth Intelligence (GST-CGI)
**Case:** CASE-002
**Status:** Canonical Demonstration / End-to-End Runtime Trace
**Version:** 1.0

---

## 1. Purpose

This case demonstrates the runtime transition:

```text
Structural Localization
        ↓
Leaf
        ↓
Leaf Resolution Gate
        ↓
DELEGATE
        ↓
Leaf Sandbox Package
        ↓
External Specialist AI
        ↓
Result + Evidence + Delta
        ↓
Parent Validation
```

The central problem is simple:

> **What should happen when structural localization succeeds, but the resulting leaf is not sufficient for a final decision?**

GST-CGI does not assume:

```text
Leaf
=
Decision
```

Instead:

> **A structural leaf is not necessarily a decision leaf.**

The runtime therefore evaluates the leaf through a **Leaf Resolution Gate (LRG)**.

The LRG may produce:

```text
DECIDE

REFINE

LEFTOVER

DELEGATE
```

This case focuses on the fourth outcome:

```text
DELEGATE
```

The runtime generates a policy-bounded executable structural package and gives it to an external specialist AI for further computation.

The specialist receives computational capability.

It does not receive structural authority.

The governing principle is:

> **Export capability, not authority.**

---

# 2. Scenario

Assume an AI coding runtime is analyzing a proposed software change.

The application requests:

> Determine whether the proposed implementation can safely replace the current implementation.

The structural runtime has access to:

```text
CallingGraph

Type Constraints

Known Runtime Traces

Certified Calling Paths

Test Results

Change Scope

Policy

Historical Structural Memory
```

The candidate change affects:

```text
PaymentService.calculateTotal()
```

and indirectly interacts with:

```text
DiscountService

TaxService

AuditService

OrderRepository
```

---

# 3. Structural Localization

The runtime converts the request into a Generalized Structural Trigger.

Conceptually:

```text
GST
{
    changedFunction,
    callingContext,
    affectedTypes,
    runtimeEvidence,
    testEvidence,
    policyPerspective
}
```

The active perspective is:

```text
SAFE CODE REPLACEMENT
```

The runtime performs structural localization.

---

# 4. CallingGraph Region

The relevant local CallingGraph is:

```text
CheckoutController
        |
        v
PaymentService.calculateTotal()
        |
        +----------------+
        |                |
        v                v
DiscountService      TaxService
        |
        v
AuditService
```

The proposed implementation changes:

```text
PaymentService.calculateTotal()
```

but does not directly modify the downstream services.

---

# 5. Metric Localization

The runtime compares the candidate against known structural patterns.

Relevant metrics may include:

```text
Calling-path similarity

Type compatibility

Parameter compatibility

Return-value compatibility

Side-effect similarity

Test coverage

Runtime-trace similarity
```

The candidate is localized into:

```text
Replacement-Compatible Region
```

This is a successful structural localization.

---

# 6. Two-Way CCC

The local Two-Way CCC evaluates:

```text
Calling Contract Preservation
            /       \
           /         \
     PRESERVED      VIOLATED
```

The candidate matches:

```text
PRESERVED
```

based on:

```text
same public signature

compatible return type

known callers preserved

basic tests passing
```

The runtime therefore reaches:

```text
Leaf:
Calling Contract Preserved
```

---

# 7. The Tempting Mistake

A simplistic runtime may now conclude:

```text
Leaf reached
    ↓
Safe replacement
```

But this is not justified.

The leaf answers:

> **Does the candidate preserve the currently modeled calling contract?**

It does not necessarily answer:

> **Is the replacement safe enough to approve under the active deployment policy?**

These are different questions.

---

# 8. Structural Leaf vs Decision Leaf

The current node is:

```text
Structural Leaf
```

because the mature local CCC has completed its discrimination.

But it may not be:

```text
Decision Leaf
```

because the final decision requires additional evidence.

Therefore:

> **Structural localization completion and decision sufficiency must be evaluated separately.**

---

# 9. Enter the Leaf Resolution Gate

The runtime now invokes:

```text
Leaf Resolution Gate
```

The LRG evaluates:

```text
Structural Match

Supporting Evidence

Counter-Evidence

Uncertainty

Risk

Policy Requirements

Decision Cost

Refinement Availability

Delegation Availability

Resource Budget
```

---

# 10. Decision Sufficiency

Conceptually:

```text
DS =
f(
    M,
    E+,
    E-,
    U,
    R,
    P,
    Cd,
    Cr,
    D
)
```

where:

```text
M  = Structural Match

E+ = Supporting Evidence

E- = Counter-Evidence

U  = Uncertainty

R  = Risk

P  = Policy

Cd = Cost of Wrong Decision

Cr = Cost of Refinement

D  = Delegation Availability
```

The implementation does not require a learned scalar model.

A rule-based evaluator is sufficient.

---

# 11. Evidence at the Leaf

The current evidence is:

```text
SUPPORTING EVIDENCE

✓ Public signature preserved

✓ Known callers compile

✓ Return type compatible

✓ Basic unit tests pass

✓ CallingGraph structure mostly preserved
```

But counter-evidence exists:

```text
COUNTER-EVIDENCE

! AuditService interaction changed

! One runtime path has no test coverage

! Side-effect ordering is not fully validated

! Historical trace contains one unusual sequence
```

---

# 12. Active Policy

Assume the active policy is:

```text
Production-Safe-Replacement-v3
```

with rules such as:

```text
High-impact payment changes
require side-effect validation.

Uncovered certified paths
cannot be automatically approved.

Known counter-evidence
must be resolved or explicitly bounded.

External simulation is allowed.

External structural mutation is forbidden.
```

The policy therefore prevents immediate approval.

---

# 13. LRG Option 1 — DECIDE?

The runtime evaluates:

```text
DECIDE
```

Question:

> Is current evidence sufficient for the requested production-safe replacement decision?

Answer:

```text
NO
```

Reason:

```text
Side-effect ordering remains uncertain.

One important calling path is insufficiently tested.
```

Therefore:

```text
DECIDE
=
REJECTED BY LRG
```

---

# 14. LRG Option 2 — REFINE?

The runtime evaluates:

```text
REFINE
```

REFINE means:

> A known deeper structural differentiation path already exists and is useful for this decision.

Suppose the local mature runtime does not yet contain a validated CCC for:

```text
Audit Side-Effect Ordering
```

There is no established deeper branch available.

Therefore:

```text
REFINE
=
NOT CURRENTLY AVAILABLE
```

---

# 15. LRG Option 3 — LEFTOVER?

The runtime could return:

```text
LEFTOVER
```

because mature internal structure is insufficient.

This would be valid.

But another capability exists.

A specialized sandboxed code-analysis AI is available.

It can:

```text
simulate local CallingGraph paths

compare side-effect ordering

generate targeted tests

search for counterexamples

propose structural differences
```

Therefore the runtime evaluates the fourth option.

---

# 16. LRG Option 4 — DELEGATE

The question is:

> Can the current leaf be safely converted into a bounded computational package so that an authorized external specialist can continue the analysis?

The answer is:

```text
YES
```

Therefore:

```text
Leaf Resolution
=
DELEGATE
```

---

# 17. Why DELEGATE Is Different from LEFTOVER

The distinction is important.

### LEFTOVER

```text
Need unresolved
+
insufficient mature structure
+
no currently justified computation path
```

### DELEGATE

```text
Need unresolved
+
current structural context is useful
+
authorized external computation path exists
```

Thus:

> **DELEGATE means the runtime knows enough to construct a useful bounded computational handoff, even though it does not know enough to make the final decision.**

---

# 18. Why DELEGATE Is Different from REFINE

REFINE means:

```text
continue inside known structural machinery
```

DELEGATE means:

```text
export a bounded structural computation
to another authorized computational participant
```

Thus:

```text
REFINE
=
Internal Structural Continuation
```

while:

```text
DELEGATE
=
External Bounded Structural Continuation
```

---

# 19. The Raw Leaf Must Not Be Exported

The runtime should not simply send:

```text
Internal Leaf Object
```

to the external AI.

The internal leaf may contain:

```text
unrelated memory

internal identifiers

private policy

unnecessary graph regions

excessive capabilities

mutable references

global structural state
```

Therefore a transformation boundary is required.

---

# 20. Sandbox Compiler

GST-CGI introduces the conceptual:

```text
Sandbox Compiler
```

or:

```text
Structural Package Builder
```

The transformation is:

```text
Internal Leaf
     |
     v
Policy Projection
     |
     v
Context Reduction
     |
     v
Capability Reduction
     |
     v
Evidence Packaging
     |
     v
Resource Bounding
     |
     v
Identity / Version Binding
     |
     v
Leaf Sandbox Package
```

---

# 21. Canonical LSP Equation

Conceptually:

```text
LSP
=
PolicyProjection(
    Leaf,
    Caller,
    Purpose,
    Perspective,
    Budget
)
```

The LSP is therefore not simply a serialized leaf.

It is a policy-governed computational projection.

---

# 22. LSP Contents

For this case, the package may contain six major components:

```text
1. Structural Context

2. Trigger

3. Evidence

4. Behavior

5. Policy

6. Runtime Contract
```

---

# 23. Structural Context

The external specialist receives only the relevant local CallingGraph:

```text
CheckoutController
        |
        v
PaymentService.calculateTotal()
        |
        +----------------+
        |                |
        v                v
DiscountService      TaxService
        |
        v
AuditService
```

It does not receive the entire application graph.

This reduces both:

```text
exposure
```

and:

```text
computational scope
```

---

# 24. Trigger

The LSP includes a projected GST describing the candidate change.

For example:

```text
CodeReplacementTrigger
{
    targetFunction,
    oldImplementationSummary,
    newImplementationSummary,
    localCallingGraph,
    typeConstraints,
    observedSideEffects,
    testEvidence
}
```

The trigger is purpose-specific.

---

# 25. Evidence

The package includes:

```text
Supporting Evidence

Counter-Evidence

Known Uncertainty

Trace References

Relevant Test Results

Relevant Runtime Observations
```

The specialist therefore does not begin from an empty prompt.

It begins from a structured evidence context.

---

# 26. Behavior

The package may authorize functions such as:

```text
compareCallingPaths()

simulateSideEffectOrder()

generateLocalTest()

searchCounterExample()

proposeCandidateDifference()
```

These are executable capabilities.

But they are bounded.

---

# 27. Policy

The LSP may carry a projected policy:

```text
Purpose:
Validate replacement safety

Allowed:
Local simulation
Path comparison
Test generation
Counter-evidence search
Delta proposal

Forbidden:
Production execution
Repository mutation
Global policy modification
Global CCC promotion
Access outside local graph
```

The external AI therefore receives an explicit computational envelope.

---

# 28. Runtime Contract

The package may also specify:

```text
Maximum Unfolding Depth:
4

Maximum Simulation Runs:
100

Maximum Generated Tests:
20

External Network Access:
No

Global Memory Mutation:
No

Package Expiration:
30 minutes

Required Output:
Result + Evidence + Counter-Evidence + Delta

Audit:
Required
```

This makes the sandbox operationally bounded.

---

# 29. Canonical LSP

Conceptually:

```text
LSP
{
    identity,
    purpose,
    structuralContext,
    trigger,
    evidence,
    counterEvidence,
    behavior,
    policy,
    capabilityBoundary,
    resourceBudget,
    outputContract,
    expiration,
    provenance
}
```

This is an executable structural package.

---

# 30. Capability-Bounded Structural Object

The LSP can therefore be described as:

> **A Capability-Bounded Structural Object.**

It contains enough computational intelligence to support useful continuation.

But it intentionally lacks unrestricted authority.

---

# 31. Export Capability, Not Authority

The specialist may:

```text
READ
local structural context

COMPARE
calling paths

SIMULATE
local side effects

GENERATE
bounded tests

SEARCH
counter-evidence

PROPOSE
candidate delta
```

It may not:

```text
WRITE
global structural memory

PROMOTE
new CCC

CHANGE
policy

EXECUTE
production actions

EXPAND
its own capabilities
```

This is the core security boundary.

---

# 32. Delegated Structural Unfolding

The specialist receives the LSP.

The next phase is:

```text
Delegated Structural Unfolding
```

The specialist unfolds the supplied structural world for the specific unresolved question.

---

# 33. External Specialist Analysis

The specialist examines:

```text
PaymentService.calculateTotal()
```

and simulates the local CallingGraph.

It discovers:

```text
Old Implementation:

Discount
   ↓
Audit
   ↓
Tax
```

while the candidate implementation performs:

```text
New Implementation:

Discount
   ↓
Tax
   ↓
Audit
```

The public calling contract is preserved.

But side-effect ordering changed.

---

# 34. Why the Original CCC Missed It

The parent CCC asked:

```text
Calling Contract Preservation?
```

The answer was correctly:

```text
PRESERVED
```

The CCC was not wrong.

Its structural difference was simply too coarse for the final decision.

This demonstrates:

> **A correct structural leaf can still be decision-insufficient.**

---

# 35. Specialist Generates Targeted Tests

The external AI generates bounded tests around:

```text
AuditService
```

and discovers:

```text
Test 1:
PASS

Test 2:
PASS

Test 3:
FAIL under retry condition
```

The failure occurs because:

```text
Audit event now records
post-tax rather than pre-tax state
```

under a particular retry path.

---

# 36. External Result

The specialist returns:

```text
RESULT

Replacement should not yet be
approved for production.
```

But the result alone is not sufficient.

The package contract requires evidence.

---

# 37. Supporting Evidence

The specialist returns:

```text
EVIDENCE

1. Public signature preserved.

2. Known caller compatibility preserved.

3. Main execution path remains valid.

4. Most generated local tests pass.
```

---

# 38. Counter-Evidence

It also returns:

```text
COUNTER-EVIDENCE

1. Audit ordering changed.

2. Retry path exposes semantic difference.

3. Generated Test #3 fails.

4. Existing Calling Contract CCC
   does not represent side-effect ordering.
```

This counter-evidence is critical.

---

# 39. Candidate Delta

The specialist also returns:

```text
CANDIDATE DELTA

Potential missing structural difference:

Side-Effect Ordering Preservation
        /             \
       /               \
 PRESERVED            CHANGED
```

This is not merely a result.

It is a proposed new computational distinction.

---

# 40. Result and Delta Are Different Objects

The distinction is:

```text
Result
=
Do not approve this replacement yet.
```

while:

```text
Delta
=
The parent runtime may be missing
a reusable Side-Effect Ordering CCC.
```

The Result concerns:

```text
this case
```

The Delta concerns:

```text
future computation
```

---

# 41. External Delta Has No Promotion Authority

The specialist does not install:

```text
Side-Effect Ordering CCC
```

into the parent runtime.

Instead:

```text
External Delta
      |
      v
Candidate Structure
      |
      v
Parent Validation
```

This preserves structural sovereignty.

---

# 42. Parent Validation

The parent runtime receives:

```text
Result

Evidence

Counter-Evidence

Candidate Delta

Delegation Trace
```

It first validates the current-task result.

Questions include:

```text
Was computation inside authorized scope?

Were resource limits respected?

Is evidence reproducible?

Does the failing test reproduce locally?

Is provenance intact?
```

---

# 43. Result Validation

Suppose the parent reproduces:

```text
Generated Test #3
```

and confirms the side-effect ordering change.

The runtime may now resolve:

```text
DECIDE
```

with:

```text
Recommendation:
Do not approve current replacement.
```

The original unresolved decision has been completed.

---

# 44. Decision Authority Remains with Parent Runtime

The external AI provided:

```text
computation

evidence

counter-evidence

recommendation
```

But the parent runtime made the governed resolution.

Thus:

```text
External Intelligence
!=
Final Authority
```

unless policy explicitly says otherwise.

---

# 45. Candidate Delta Enters a Separate Pipeline

The candidate structural difference enters:

```text
Delta Validation
```

rather than being automatically installed.

The pipeline is:

```text
Candidate Delta
      |
      v
Historical Search
      |
      v
Counter-Evidence Search
      |
      v
A/B Validation
      |
      v
Decision-Relevance Test
      |
      v
Policy Gate
      |
      v
PROMOTE?
```

---

# 46. Historical Validation

The parent searches historical replacement cases.

Suppose it finds:

```text
42 comparable code changes
```

Among them:

```text
9
changed side-effect ordering
```

and:

```text
6 of those 9
caused test or runtime differences
```

This suggests that the proposed distinction may be structurally useful.

---

# 47. Counter-Evidence Search

The runtime also searches for cases where:

```text
side-effect ordering changed
```

but:

```text
behavior remained equivalent
```

These cases prevent premature promotion.

The candidate difference may need refinement.

---

# 48. Candidate CCC

After analysis, the system proposes:

```text
Side-Effect Semantic Preservation
             /       \
            /         \
       PRESERVED     CHANGED
```

rather than merely:

```text
Execution Order
   /       \
 SAME     DIFFERENT
```

This is a stronger decision-relevant distinction.

---

# 49. Structural Growth

After validation, policy may authorize local promotion beneath the original leaf.

### Before

```text
Calling Contract Preservation
          /       \
         /         \
   PRESERVED      VIOLATED
       |
       v
      Leaf
```

### After

```text
Calling Contract Preservation
          /       \
         /         \
   PRESERVED      VIOLATED
       |
       v
Side-Effect Semantic Preservation
       /                  \
      /                    \
PRESERVED                 CHANGED
```

The original leaf has become an internal structural node.

---

# 50. The Delegation Changed Future Computation

Before this case:

```text
Calling Contract Preserved
        ↓
Decision Insufficient
        ↓
DELEGATE
```

After structural growth:

```text
Calling Contract Preserved
        ↓
Side-Effect Semantic Preservation
        ↓
PRESERVED / CHANGED
```

Future similar cases may be resolved locally.

Thus delegated computation has contributed to:

> **Computational-Structure Growth.**

---

# 51. Expensive Reasoning Becomes Folded Structure

Initially, the system required:

```text
External Specialist

Simulation

Generated Tests

Counter-Evidence Search
```

After repeated validation, part of that reasoning can be folded into:

```text
New CCC

New Trigger State

New Evidence Requirement
```

Future computation may therefore become cheaper.

---

# 52. Folding the Delegated Discovery

The process is:

```text
Expensive Delegated Analysis
          |
          v
Repeated Structural Difference
          |
          v
Evidence Validation
          |
          v
Structural Promotion
          |
          v
Folded CCC
```

This is an important Computational Growth pattern:

> **Expensive external reasoning can become cheap internal structural discrimination after sufficient validation.**

---

# 53. The Next Similar Case

Later, another code replacement arrives.

The runtime localizes:

```text
Calling Contract
=
PRESERVED
```

and immediately continues into:

```text
Side-Effect Semantic Preservation
```

Suppose it resolves:

```text
PRESERVED
```

with sufficient evidence.

The LRG may now choose:

```text
DECIDE
```

without external delegation.

The system has changed how it computes.

---

# 54. Delegation as a Growth Mechanism

This demonstrates that DELEGATE has two potential outputs.

### Immediate Output

```text
Current-task result
```

### Long-Term Output

```text
Candidate structural growth
```

Therefore delegation is not merely outsourcing.

It can become a structural-learning mechanism.

---

# 55. Delegation Is Not Always Growth

However:

```text
DELEGATE
```

does not automatically imply:

```text
GROW
```

The external AI may return:

```text
Result
```

without discovering a reusable difference.

That is perfectly valid.

Only decision-relevant, reusable, validated Deltas should enter structural promotion.

---

# 56. Avoiding Structural Bloat

Suppose the external specialist proposes:

```text
17 candidate differences
```

The parent should not create:

```text
17 new CCCs
```

automatically.

Instead it should ask:

```text
Which differences recur?

Which affect decisions?

Which survive counter-evidence?

Which reduce future computation?

Which are worth structural cost?
```

This preserves structural economy.

---

# 57. Decision Relevance

A difference may be real but not worth folding.

For example:

```text
Method local variable renamed
```

may distinguish two implementations.

But if it does not affect:

```text
behavior

risk

policy

calling contract

evidence
```

it should not become a structural branch.

Thus:

> **Further differentiation is justified by decision relevance, not merely by the existence of additional differences.**

---

# 58. Why the LRG Is Necessary

Without the LRG, the system has two poor choices.

### Choice A

```text
Leaf
↓
Always Decide
```

This creates premature decisions.

### Choice B

```text
Leaf
↓
Always Search Deeper
```

This creates potentially endless refinement.

The LRG provides a controlled stopping and continuation mechanism.

---

# 59. The Four Outcomes Revisited

The case clarifies all four outcomes.

### DECIDE

```text
Current structure and evidence
are sufficient.
```

### REFINE

```text
Current structure is insufficient,
but a known internal differentiation
path exists.
```

### LEFTOVER

```text
Current structure is insufficient
and no justified continuation path exists.
```

### DELEGATE

```text
Current structure is insufficient,
but it can be transformed into
a bounded external computation package.
```

---

# 60. Canonical LRG Decision Table

| Condition                                                  | Resolution |
| ---------------------------------------------------------- | ---------- |
| Evidence sufficient and policy satisfied                   | DECIDE     |
| More decision-relevant internal structure is available     | REFINE     |
| No sufficient structure or justified continuation exists   | LEFTOVER   |
| Authorized external computation can continue from the leaf | DELEGATE   |

This table can support a simple MVP implementation.

---

# 61. Low-End User Configuration

A low-end user should not need to implement the entire LRG.

The framework may expose simple controls such as:

```text
Decision Policy:
Conservative

Refinement Budget:
Medium

Unknown Handling:
Defer

Delegation:
Approved Specialists Only
```

The runtime maps these preferences into detailed structural policy.

---

# 62. Expert Configuration

An expert may configure:

```text
Decision Sufficiency Rules

Evidence Thresholds

Counter-Evidence Rules

Risk Model

Refinement Policy

Delegation Policy

Allowed LSP Capabilities

Resource Budget

Delta Promotion Policy
```

Thus the same architecture supports both low-end and advanced users.

---

# 63. Java-Oriented Resolution Model

A minimal conceptual API may begin with:

```java
public enum LeafResolution {
    DECIDE,
    REFINE,
    LEFTOVER,
    DELEGATE
}
```

and:

```java
public interface LeafResolutionPolicy<T> {

    LeafResolution resolve(
            LeafContext<T> leaf,
            EvidenceReport evidence,
            ResolutionPolicy policy);
}
```

---

# 64. Leaf Context

Conceptually:

```java
public final class LeafContext<T> {

    private final String leafId;
    private final T trigger;
    private final StructuralPath path;
    private final Perspective perspective;
    private final StructuralMatch match;

    // constructor / accessors
}
```

The exact implementation is application-specific.

---

# 65. Delegation Eligibility

A separate contract may determine:

```java
public interface DelegationPolicy<T> {

    boolean canDelegate(
            LeafContext<T> leaf,
            EvidenceReport evidence);

    CapabilitySet allowedCapabilities(
            LeafContext<T> leaf);

    ResourceBudget resourceBudget(
            LeafContext<T> leaf);
}
```

This keeps delegation policy explicit.

---

# 66. Sandbox Builder

Conceptually:

```java
public interface LeafSandboxBuilder<T> {

    LeafSandboxPackage build(
            LeafContext<T> leaf,
            EvidenceReport evidence,
            DelegationPolicy<T> policy);
}
```

The builder performs:

```text
projection

reduction

packaging

bounding
```

rather than raw serialization.

---

# 67. Delegated Result Contract

The external specialist may return:

```java
public final class DelegatedResult<R> {

    private final R result;
    private final Evidence supportingEvidence;
    private final Evidence counterEvidence;
    private final CandidateDelta delta;
    private final DelegationTrace trace;

    // constructor / accessors
}
```

This makes Result and Delta separate first-class outputs.

---

# 68. Parent Runtime Contract

The parent then performs:

```text
validateResult()

validateEvidence()

validateDelta()

resolveCurrentTask()

considerStructuralPromotion()
```

The external system does not bypass these steps.

---

# 69. Full Runtime Trace

The complete case trace is:

```text
[01]
Application Request
"Can this implementation safely replace the current one?"

        ↓

[02]
Generalized Structural Trigger

        ↓

[03]
CallingGraph / Metric Localization

        ↓

[04]
Two-Way CCC
Calling Contract Preservation

        ↓

[05]
PRESERVED

        ↓

[06]
Structural Leaf Reached

        ↓

[07]
Leaf Resolution Gate

        ↓

[08]
DECIDE?
No — evidence insufficient

        ↓

[09]
REFINE?
No — no mature internal branch

        ↓

[10]
DELEGATE?
Yes — authorized specialist exists

        ↓

[11]
Sandbox Compiler

        ↓

[12]
Leaf Sandbox Package

        ↓

[13]
External Code Specialist

        ↓

[14]
Delegated Structural Unfolding

        ↓

[15]
Side-Effect Ordering Difference Found

        ↓

[16]
Targeted Test Generated

        ↓

[17]
Counterexample Confirmed

        ↓

[18]
Return:
Result
+
Evidence
+
Counter-Evidence
+
Candidate Delta

        ↓

[19]
Parent Validation

        ↓

[20]
Current Task:
DECIDE — Do Not Approve Yet

        ↓

[21]
Candidate Delta Validation

        ↓

[22]
Candidate CCC:
Side-Effect Semantic Preservation

        ↓

[23]
Policy-Governed Promotion

        ↓

[24]
New Mature Structural Branch

        ↓

[25]
Future Similar Cases
Can Be Resolved More Locally
```

This is the canonical CASE-002 runtime path.

---

# 70. What Grew?

The immediate task produced:

```text
a safer decision
```

But the larger system potentially gained:

```text
new structural difference

new CCC

new evidence requirement

new local test pattern

new runtime path
```

Therefore the growth object is not merely experience.

It is computational structure.

---

# 71. Growth Ladder Interpretation

The case spans several CGI levels.

### Experience Growth

```text
New code case

New runtime evidence

New failing test
```

### Performance Growth

```text
Safer replacement evaluation
```

### Computational-Structure Growth

```text
New Side-Effect Semantic Preservation CCC
```

Potentially, repeated use could later support:

### Computational-System Growth

```text
Permanent relationship
between parent structural runtime
and code-analysis specialist
```

---

# 72. The Delegation Edge Can Also Become Structure

Suppose repeated cases show that:

```text
Calling Contract Preserved
+
Side-Effect Evidence Incomplete
```

should reliably invoke:

```text
Code Side-Effect Specialist
```

The delegation relationship itself may be folded:

```text
Leaf Pattern
     |
     v
Certified Delegation Path
     |
     v
Specialist AI
```

Now not only the local CCC has grown.

The computational system has grown.

---

# 73. From Structural Growth to System Growth

The progression becomes:

```text
New Difference
    ↓
New CCC
    ↓
New Delegation Rule
    ↓
New Certified Computational Path
    ↓
Computational-System Growth
```

This directly connects CASE-002 to GST-CGI-008.

---

# 74. Audit Trace

A production-quality implementation should preserve:

```text
Task ID

Leaf ID

Structural Path

GST Version

Policy Version

Evidence

Counter-Evidence

LRG Decision

Delegation Reason

LSP ID

Capabilities Granted

Resource Budget

External Runtime Identity

External Result

External Delta

Parent Validation

Final Decision

Promotion Decision
```

This allows reconstruction of the complete computational chain.

---

# 75. Why Audit Matters

The runtime should be able to answer:

```text
Why did we delegate?

What exactly was exported?

What was the specialist allowed to do?

What evidence did it return?

Why was the final decision changed?

Did its Delta become mature structure?

Who authorized that promotion?
```

Without these answers, delegated structural intelligence becomes difficult to govern.

---

# 76. Failure Case — Specialist Returns Unsupported Result

Suppose the external AI returns:

```text
SAFE TO REPLACE
```

but provides no evidence.

The parent contract requires:

```text
Result
+
Evidence
```

Therefore:

```text
Delegated Result
=
INVALID
```

The runtime may produce:

```text
LEFTOVER
```

or delegate elsewhere.

This demonstrates that external intelligence does not automatically receive trust.

---

# 77. Failure Case — Specialist Exceeds Capability

Suppose the specialist attempts:

```text
modify repository
```

but the LSP allows only:

```text
simulation
```

The runtime rejects the operation.

Conceptually:

```text
Requested Capability
        |
        v
Capability Gate
        |
    +---+---+
    |       |
 ALLOW    DENY
```

The package boundary is enforced.

---

# 78. Failure Case — Delta Fails Validation

Suppose the proposed:

```text
Side-Effect Semantic Preservation CCC
```

does not generalize historically.

Then:

```text
Candidate Delta
      |
      v
Validation
      |
      v
REJECT
```

The current task result may still remain useful.

Thus:

```text
Valid Result
```

does not imply:

```text
Valid Structural Delta
```

This separation is essential.

---

# 79. Failure Case — Policy Changes

Suppose the same structural leaf appears in a development environment.

Policy:

```text
Development-Experiment-v1
```

may allow:

```text
DECIDE
```

or:

```text
REFINE
```

without external specialist analysis.

Under:

```text
Production-Safe-Replacement-v3
```

the runtime may require:

```text
DELEGATE
```

Thus:

> **The same structural leaf can resolve differently under different policies.**

---

# 80. Leafhood Is Structural, Resolution Is Policy-Relative

This case gives a concrete example of:

> **Leafhood is structural, but leaf resolution is policy-relative.**

The structural fact:

```text
Calling Contract Preserved
```

does not change.

What changes is whether that fact is sufficient for the requested decision.

---

# 81. Delegation as Structural Continuation

The deeper interpretation is:

```text
DELEGATE
```

is not merely:

```text
call another AI
```

It is:

> **Continue structural unfolding across a controlled computational boundary.**

This is why the term:

> **Delegated Structural Unfolding**

is appropriate.

---

# 82. LSP as a Computational Handoff Point

The leaf becomes more than:

```text
endpoint
```

It becomes a possible:

```text
computational handoff point
```

The runtime can transform localized intelligence into a bounded executable package.

This substantially enlarges the role of a structural leaf.

---

# 83. From Answer-as-a-Service to Structure-as-a-Service

Traditional architecture:

```text
Caller
   |
   v
AI
   |
   v
Answer
```

GST-CGI delegation:

```text
Structural Runtime
       |
       v
Localized Leaf
       |
       v
LSP
       |
       v
External Intelligence
       |
       v
Further Computation
```

The runtime provides structure rather than only answers.

---

# 84. Canonical Principles Demonstrated

This case demonstrates the following principles.

## Principle 1

> **A structural leaf is not necessarily a decision leaf.**

## Principle 2

> **Further differentiation is justified by decision relevance, not merely by the existence of additional differences.**

## Principle 3

> **Leafhood is structural, but leaf resolution is policy-relative.**

## Principle 4

> **DECIDE, REFINE, LEFTOVER, and DELEGATE represent distinct runtime semantics.**

## Principle 5

> **REFINE means a known internal structural continuation exists; LEFTOVER means sufficient structural support is absent.**

## Principle 6

> **DELEGATE means a bounded external continuation is justified.**

## Principle 7

> **An internal leaf should be projected into an LSP rather than exported raw.**

## Principle 8

> **Export capability, not authority.**

## Principle 9

> **External Result and External Delta are separate computational objects.**

## Principle 10

> **External Delta requires local evidence validation and policy-governed promotion.**

---

# 85. The Complete Case in One Map

```text
APPLICATION REQUEST
       |
       v
GENERALIZED STRUCTURAL TRIGGER
       |
       v
STRUCTURAL LOCALIZATION
       |
       v
TWO-WAY CCC
       |
       v
STRUCTURAL LEAF
       |
       v
LEAF RESOLUTION GATE
       |
       +-------- DECIDE
       |
       +-------- REFINE
       |
       +-------- LEFTOVER
       |
       +-------- DELEGATE
                    |
                    v
              POLICY PROJECTION
                    |
                    v
              SANDBOX COMPILER
                    |
                    v
         LEAF SANDBOX PACKAGE
                    |
                    v
           EXTERNAL SPECIALIST AI
                    |
                    v
       DELEGATED STRUCTURAL UNFOLDING
                    |
                    v
        RESULT + EVIDENCE + DELTA
                    |
          +---------+---------+
          |                   |
          v                   v
 CURRENT-TASK           DELTA VALIDATION
 VALIDATION                   |
          |                   v
          v              CANDIDATE CCC
       DECIDE                  |
                              v
                         POLICY GATE
                              |
                              v
                          PROMOTION
                              |
                              v
                    NEW MATURE STRUCTURE
                              |
                              v
                     FUTURE COMPUTATION
```

---

# 86. Final Case Summary

CASE-002 begins after structural search has already succeeded.

The runtime has reached a valid leaf:

```text
Calling Contract Preserved
```

But the active production policy requires more evidence.

Rather than treating the leaf as an automatic decision, GST-CGI invokes the:

```text
Leaf Resolution Gate
```

The runtime determines:

```text
DECIDE
=
insufficient

REFINE
=
no mature internal path

LEFTOVER
=
possible but unnecessary

DELEGATE
=
appropriate
```

It therefore converts the leaf into:

```text
Leaf Sandbox Package
```

through:

```text
Policy Projection

Context Reduction

Capability Reduction

Evidence Packaging

Resource Bounding
```

The external specialist performs:

```text
Delegated Structural Unfolding
```

and returns:

```text
Result
+
Evidence
+
Counter-Evidence
+
Candidate Delta
```

The parent runtime validates the result and completes the current decision.

Separately, it validates the candidate Delta.

If the Delta survives:

```text
historical evidence

counter-evidence

decision relevance

policy
```

it may be promoted into a new Two-Way CCC.

Thus:

```text
Leaf
    ↓
DELEGATE
    ↓
External Computation
    ↓
Delta
    ↓
Validation
    ↓
New Structure
```

becomes a concrete mechanism of Computational Growth Intelligence.

The external AI did not take over the parent runtime.

It contributed bounded computation.

The parent retained structural authority.

The final principle is therefore:

> **A leaf can be an endpoint, a refinement point, an unknown boundary, or a computational handoff point.**

And when it becomes a handoff point:

> **The AI does not merely ask another AI for an answer. It gives that AI a policy-bounded structural world in which useful computation can continue.**

---

## Related GST-CGI Documents

```text
GST-CGI-004
Leaf Resolution:
Decide, Refine, Leftover, or Delegate

GST-CGI-005
Leaf Sandbox Package and
Delegated Structural Unfolding

GST-CGI-006
From Leftover and Delta Intelligence
to Structural Growth

GST-CGI-007
Computational Growth Intelligence

GST-CGI-008
From Computational-Structure Growth
to AI Computational Ecosystems
```

---

**GST-CGI — Generalized Structural Trigger and Computational Growth Intelligence**

**From Two-Way CCC and Leaf Resolution to Delegated Unfolding and AI Computational-System Growth**
