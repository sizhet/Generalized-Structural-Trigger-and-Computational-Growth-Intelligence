# GST-CGI-004 — Leaf Resolution: Decide, Refine, Leftover, or Delegate

## From Structural Localization Boundary to Policy-Governed Runtime Resolution

**Project:** Generalized Structural Trigger and Computational Growth Intelligence (GST-CGI)
**Subtitle:** From Two-Way CCC and Leaf Resolution to Delegated Unfolding and AI Computational-System Growth
**Document:** GST-CGI-004
**Status:** Research Note / Core Runtime Framework
**Version:** 1.0

---

## Abstract

Structural search eventually reaches a leaf.

A common implementation assumption is:

```text id="2ndfm3"
Leaf
  ↓
Decision
```

This assumption is convenient but generally too strong.

A structural leaf indicates that the active search structure has reached its current boundary of mature differentiation. It does not necessarily indicate that the current structural resolution is sufficient for the requested decision.

The distinction is fundamental:

> **A structural leaf is not necessarily a decision leaf.**

At a leaf, a structural-intelligence runtime must determine whether the current localization is sufficient, whether further known differentiation is useful, whether the case lies outside mature structure, or whether the localized computation should be delegated to another application or AI.

This article introduces the **Leaf Resolution Gate (LRG)**.

The LRG defines four explicit runtime outcomes:

```text id="slhh45"
DECIDE
REFINE
LEFTOVER
DELEGATE
```

These outcomes separate four fundamentally different situations:

* **DECIDE** — current structure and evidence are sufficient for a decision or recommendation;
* **REFINE** — further known differentiation is decision-relevant and available;
* **LEFTOVER** — current mature structure or evidence is insufficient for reliable resolution;
* **DELEGATE** — the current leaf is useful enough to package as a bounded computational structure for another caller to continue task-specific computation.

The article further introduces **Decision Sufficiency** as a policy-relative criterion for deciding whether structural search should stop.

The central principle is:

> **Further differentiation should be justified by decision relevance, not merely by the existence of additional differences.**

Leaf resolution therefore becomes the boundary between structural localization, decision, structural refinement, Delta Intelligence, and delegated computation.

---

# 1. The Leaf Ambiguity

Consider a structural search:

```text id="13ayb4"
Input
  |
  v
Structural Representation
  |
  v
Metric Localization
  |
  v
Two-Way CCC
  |
  v
Local Difference
  |
  v
Leaf
```

What does reaching the leaf mean?

A naive interpretation is:

```text id="prv7in"
Leaf = Answer
```

or:

```text id="br5vb5"
Leaf = Decision
```

But this mixes two different concepts.

The leaf may indicate only:

> The current structural search has reached the deepest mature differentiation available along this path.

That does not answer:

> Is this differentiation sufficient for the caller's requested decision?

Therefore:

```text id="i19d3m"
Structural Localization
        !=
Decision Resolution
```

This distinction motivates the Leaf Resolution Gate.

---

# 2. Structural Leaf vs Decision Leaf

We define:

## Structural Leaf

> **A structural leaf is the current boundary of mature structural differentiation in the active search structure.**

A structural leaf answers:

> Where has structural localization currently stopped?

It does not necessarily answer:

> Is computation finished?

A **Decision Leaf**, by contrast, is a structural leaf whose current evidence, policy, risk, and resolution are sufficient for the requested decision.

Therefore:

```text id="2dydiu"
Structural Leaf
      |
      +-- may become Decision Leaf
      |
      +-- may require Refinement
      |
      +-- may become Leftover
      |
      +-- may support Delegation
```

This leads to the canonical principle:

> **A structural leaf is not necessarily a decision leaf.**

---

# 3. Why Leaf and Decision Become Confused

The confusion is understandable.

In many conventional trees:

```text id="lwp9sg"
Root
 |
 +-- Branch
      |
      +-- Leaf
           |
           v
         Result
```

The tree is designed in advance so that every terminal node corresponds to a result.

But a growing structural-intelligence system is different.

Its structure may be:

* incomplete,
* evolving,
* policy-relative,
* evidence-relative,
* application-relative,
* context-relative.

Therefore the same leaf may be sufficient for one task and insufficient for another.

Example:

```text id="1g4fw8"
Leaf:
"High-Volatility Market Regime"
```

For the question:

```text id="5wp00d"
Is current volatility high?
```

the leaf may be sufficient.

For the question:

```text id="8r8wse"
Should Stock X be purchased now?
```

the same leaf may be far too coarse.

Thus:

> **Leaf sufficiency is task-relative.**

---

# 4. Infinite Differentiation Is Always Possible

A second problem appears when deciding whether to refine.

Almost any structural object can be differentiated further.

For example:

```text id="lj5myw"
Leaf
 |
 +-- Difference A
      |
      +-- Difference B
           |
           +-- Difference C
                |
                +-- ...
```

If the runtime asks only:

> Can another difference be found?

the answer may almost always be yes.

That is not a useful stopping rule.

The correct question is:

> **Would another structural difference materially improve the requested decision under the active policy?**

This changes the stopping condition from:

```text id="hrdiyq"
Difference Exists?
```

to:

```text id="1w35b1"
Decision-Relevant Difference Exists?
```

This is the foundation of **Decision Sufficiency**.

---

# 5. Decision Sufficiency

Decision Sufficiency asks:

> **Is the current structural localization sufficient for the requested decision under the active evidence, policy, risk, and cost constraints?**

Conceptually:

```text id="4gn70n"
Decision Sufficiency
=
f(
    Structural Match,
    Evidence,
    Counter-Evidence,
    Uncertainty,
    Risk,
    Decision Cost,
    Refinement Cost,
    Expected Refinement Value,
    Policy,
    Caller Intent
)
```

This does not require a universal numeric score.

In an MET implementation, Decision Sufficiency may simply be a set of rules.

For example:

```text id="tnowg7"
IF
    evidence is sufficient
AND
    counter-evidence is acceptable
AND
    risk is within policy
AND
    current granularity supports the request
AND
    expected refinement value is low
THEN
    DECIDE
```

The framework may later replace or augment such rules with learned or domain-specific mechanisms.

---

# 6. The Leaf Resolution Gate

The **Leaf Resolution Gate (LRG)** is the runtime checkpoint executed when structural search reaches a leaf or leaf-like local boundary.

Its canonical form is:

```text id="zihqvt"
                       LEAF
                         |
                         v
                LEAF RESOLUTION GATE
                         |
        +----------------+----------------+
        |                |                |
        |                |                |
        v                v                v
     DECIDE           REFINE          LEFTOVER
        |
        |
        +-------------------------------+
                                        |
                                        v
                                    DELEGATE
```

A clearer four-way representation is:

```text id="tq1s0i"
                       LEAF
                         |
                         v
                Leaf Resolution Gate
                         |
       +-----------------+-----------------+-----------------+
       |                 |                 |                 |
       v                 v                 v                 v
    DECIDE            REFINE           LEFTOVER          DELEGATE
```

Every leaf resolution should terminate in one explicit runtime outcome.

---

# 7. Outcome 1 — DECIDE

`DECIDE` means:

> The current structural localization and evidence are sufficient under the active policy for the requested decision.

The result may be:

```text id="x40f8a"
DECIDE
  |
  +-- ACTION
  |
  +-- RECOMMENDATION
  |
  +-- CLASSIFICATION
  |
  +-- RANKING
  |
  +-- STRUCTURAL RESULT
```

The distinction between Action and Recommendation is important.

A Policy Control Plane may permit:

```text id="rjty7f"
Current Leaf
    |
    v
Decision Sufficient
    |
    v
Autonomous Action
```

or require:

```text id="p2fdck"
Current Leaf
    |
    v
Decision Sufficient
    |
    v
Recommendation
    |
    v
Human / External Approval
```

Thus:

> **Decision Sufficiency does not automatically imply action authority.**

---

# 8. Decision and Action Authority Are Separate

This separation should remain explicit:

```text id="17l6ad"
Can the runtime determine
what it recommends?
        |
        v
Decision Authority
```

is different from:

```text id="7gbpfv"
Can the runtime execute
the recommended action?
        |
        v
Action Authority
```

A runtime may have:

```text id="yt6g7j"
Decision Authority = YES
Action Authority   = NO
```

This produces:

```text id="5z3ac8"
RECOMMENDATION
```

rather than autonomous action.

This is especially important for high-impact applications.

---

# 9. Outcome 2 — REFINE

`REFINE` means:

> The current localization is valid, but the current structural granularity is insufficient for the requested decision, and a known differentiation path is available.

Example:

```text id="nzw4eq"
Leaf:
High Volatility
```

Current question:

```text id="mhvd3a"
Continuation or reversal?
```

If a known structural difference exists:

```text id="zxf9yl"
High Volatility
      |
      v
Event Structure
      |
     / \
    /   \
Continuation
    vs
Reversal
```

then the runtime may refine.

The important point is:

> **REFINE is not failure.**

The previous localization remains useful.

It simply needs more local differentiation.

---

# 10. Leaf-to-Root Transformation

REFINE creates a particularly important structural operation.

A current leaf may become the root of a new local CCC.

Before:

```text id="lx0yyv"
Root
 |
 +-- A
 |
 +-- Leaf-B
```

After refinement:

```text id="uyobvl"
Root
 |
 +-- A
 |
 +-- B
      |
      +-- B1
      |
      +-- B2
```

Thus:

> **Today's leaf can become tomorrow's local root.**

This is one of the simplest mechanisms of structural growth.

---

# 11. Known Refinement vs New Structural Discovery

REFINE should be distinguished from structural discovery.

REFINE means:

```text id="f74t9j"
Known Need
+
Known Differentiation Mechanism
+
Available Evidence / Trigger
```

For example:

```text id="cmhsmm"
Leaf
  |
  v
Known Comparator
  |
  v
Known CCC
  |
  v
More Specific Leaf
```

If the runtime knows that more differentiation is needed but does not possess a mature mechanism for performing it, the result should not be `REFINE`.

It should normally become `LEFTOVER`.

---

# 12. Outcome 3 — LEFTOVER

`LEFTOVER` means:

> The current mature structural runtime cannot reliably resolve the case, and no sufficiently validated refinement path is currently available.

Possible causes include:

```text id="77f99j"
insufficient evidence

conflicting evidence

unknown structural region

missing comparator

unsupported perspective

policy restriction

novel structural difference

insufficient confidence

out-of-envelope input

unavailable required context
```

The correct runtime behavior is not to force:

```text id="0tvl8k"
A
```

or:

```text id="8zvcqg"
B
```

It is to preserve the unresolved case explicitly.

---

# 13. REFINE vs LEFTOVER

This distinction should be canonical.

```text id="i0z0xs"
REFINE
=
Current localization is insufficient
+
A mature differentiation path exists
```

while:

```text id="11wyxc"
LEFTOVER
=
Current localization is insufficient
+
No sufficiently mature differentiation path exists
```

Or more compactly:

> **REFINE means “we know how to look deeper.”**

> **LEFTOVER means “we know that the current structure is not enough, but we do not yet possess a trusted deeper structure.”**

This distinction prevents uncontrolled recursive search.

---

# 14. Why LEFTOVER Is Not REFINE-Forever

Without explicit Leftover, a structural runtime may fall into:

```text id="ndztwp"
Not enough evidence
      |
      v
Search deeper
      |
      v
Still not enough
      |
      v
Search deeper
      |
      v
...
```

This is not structural intelligence.

It is uncontrolled search.

The runtime needs an explicit point where it can say:

> The current mature structure ends here.

That point is Leftover.

Leftover therefore acts as both:

```text id="ulxk31"
Knowledge Boundary
```

and:

```text id="aavq7w"
Computation Boundary
```

---

# 15. LEFTOVER and Delta Intelligence

Leftover is not the end of the system lifecycle.

It is the beginning of another process:

```text id="cf7u0x"
LEFTOVER
    |
    v
Evidence Accumulation
    |
    v
Case Comparison
    |
    v
Candidate Difference
    |
    v
A/B Validation
    |
    v
Policy Review
    |
    v
Structural Promotion
```

This leads to:

> **Leftover creates a natural input stream for Delta Intelligence.**

A runtime can therefore separate:

```text id="23lsif"
Online Resolution
```

from:

```text id="7n5n9i"
Structural Learning / Growth
```

without losing the unresolved cases that make future growth possible.

---

# 16. Outcome 4 — DELEGATE

The fourth outcome opens a new application space.

`DELEGATE` means:

> The current leaf contains useful localized structure, but the caller or another specialized AI is better positioned to continue task-specific computation.

Instead of returning only:

```text id="6x1dpz"
Answer
```

the runtime may return:

```text id="a8l0ga"
Bounded Structural Computation Package
```

Conceptually:

```text id="o0hy5j"
Leaf
  |
  v
Policy Projection
  |
  v
Sandbox Packaging
  |
  v
External Application / AI
  |
  v
Further Computation
```

This transforms the leaf from a terminal node into a possible **computational handoff point**.

---

# 17. DELEGATE Is Not Failure

DELEGATE should not be interpreted as:

```text id="1r0hru"
The framework could not solve the problem.
```

It may instead mean:

> The framework successfully localized the relevant structural region and produced the right computational context, but another caller possesses better task-specific capability.

For example:

```text id="s5h0ct"
Structural Service
      |
      v
CallingGraph Leaf
      |
      v
DELEGATE
      |
      v
Coding Agent
```

The Structural Service may be excellent at localization.

The Coding Agent may be excellent at generating and testing code.

Delegation composes the two capabilities.

---

# 18. Internal Refinement vs External Delegation

REFINE and DELEGATE are related but distinct.

```text id="v89l1p"
REFINE
=
Framework continues computation internally.
```

while:

```text id="hzfp0u"
DELEGATE
=
Framework exports a bounded local computational structure
for another caller to continue computation.
```

Thus:

```text id="h7ax4j"
Leaf
 |
 +-- REFINE
 |      |
 |      v
 |   Internal Unfolding
 |
 +-- DELEGATE
        |
        v
   External / Delegated Unfolding
```

This distinction becomes central to the next GST-CGI article.

---

# 19. Decision Sufficiency vs Computation Sufficiency

DELEGATE suggests another useful distinction.

A leaf may be insufficient for a final decision but sufficient for useful delegated computation.

Therefore:

```text id="8jbdcm"
Decision Sufficiency
!=
Computation Sufficiency
```

A leaf may have:

```text id="jolpef"
Decision Sufficiency = LOW

Computation Sufficiency = HIGH
```

Example:

```text id="ps2s57"
The framework cannot yet decide
which code modification is best.

But it can provide:

local CallingGraph,
constraints,
certified paths,
runtime evidence,
and permitted mutation scope.
```

That may be enough for a coding agent to continue.

This is a major reason to support DELEGATE explicitly.

---

# 20. A Leaf Resolution Decision Table

The four outcomes can be summarized as:

| Condition                                                                            | Mature Decision? | Known Refinement? | Useful Exportable Structure? | Outcome  |
| ------------------------------------------------------------------------------------ | ---------------: | ----------------: | ---------------------------: | -------- |
| Evidence and policy sufficient                                                       |              Yes |        Irrelevant |                   Irrelevant | DECIDE   |
| Decision insufficient, known deeper structure available                              |               No |               Yes |                     Optional | REFINE   |
| Decision insufficient, no mature deeper structure                                    |               No |                No |            No / insufficient | LEFTOVER |
| Decision insufficient or externally specialized, but bounded useful structure exists |    No / Optional |          Optional |                          Yes | DELEGATE |

This is not intended as a universal hard-coded table.

It is a conceptual runtime guide.

---

# 21. Policy-Relative Leaf Resolution

The same structural leaf may resolve differently under different policies.

Consider:

```text id="0t9vrf"
Leaf-X
```

Under Policy A:

```text id="wpj97i"
Evidence sufficient
Risk low
Action reversible

→ DECIDE
```

Under Policy B:

```text id="dtnrqv"
Evidence marginal
Risk high
Known deeper comparator available

→ REFINE
```

Under Policy C:

```text id="b5mz0s"
Required evidence unavailable
No mature refinement

→ LEFTOVER
```

Under Policy D:

```text id="25ylac"
Specialized external AI authorized
Local structural package sufficient

→ DELEGATE
```

Therefore:

> **Leafhood is structural; leaf resolution is policy-relative.**

This is another canonical GST-CGI principle.

---

# 22. Policy Is More Than a Threshold

Policy should not be reduced to:

```text id="a6tyct"
if score > 0.8:
    decide
```

A Policy Control Plane may govern:

```text id="6q8wjx"
required evidence

counter-evidence tolerance

risk tolerance

refinement budget

latency budget

resource budget

decision authority

action authority

delegation permission

sandbox capability

caller identity

audit requirement
```

Therefore, Leaf Resolution is naturally a Control Plane operation.

---

# 23. A Conceptual Leaf Resolution Contract

A conceptual runtime interface might resemble:

```java id="b0ul7p"
public interface LeafResolutionGate {

    LeafResolution resolve(
        StructuralLeaf leaf,
        DecisionRequest request,
        EvidenceSet evidence,
        RuntimePolicy policy,
        RuntimeContext context
    );
}
```

with:

```java id="6hd80s"
public enum LeafResolution {

    DECIDE,
    REFINE,
    LEFTOVER,
    DELEGATE
}
```

A richer result may contain:

```text id="qofcqe"
LeafResolutionResult
 |
 +-- outcome
 +-- rationale
 +-- evidence
 +-- counter-evidence
 +-- active policy
 +-- active perspective
 +-- confidence
 +-- refinement plan
 +-- delegation contract
 +-- trace
```

Again, the exact API is secondary.

The explicit four-outcome contract is the important part.

---

# 24. A Minimal Runtime Algorithm

A simple MET-oriented algorithm may look conceptually like:

```text id="36gx1c"
function resolveLeaf(leaf, request, policy):

    evidence = collectEvidence(leaf, request)

    if decisionSufficient(
        leaf,
        evidence,
        request,
        policy
    ):
        return DECIDE

    if matureRefinementExists(
        leaf,
        request,
        policy
    ):
        return REFINE

    if delegationUsefulAndAllowed(
        leaf,
        request,
        policy
    ):
        return DELEGATE

    return LEFTOVER
```

The order may itself be policy-controlled.

For example, a low-latency policy may prefer delegation before expensive internal refinement.

A privacy policy may prohibit delegation entirely.

---

# 25. Resolution Order Can Be Policy-Controlled

There is no universal ordering such as:

```text id="r7vgzm"
DECIDE
then REFINE
then DELEGATE
then LEFTOVER
```

Different applications may prefer different paths.

For example:

### Local-First Policy

```text id="fjtm2v"
DECIDE
  ↓
REFINE
  ↓
DELEGATE
  ↓
LEFTOVER
```

### Specialist-First Policy

```text id="zmm71e"
DECIDE
  ↓
DELEGATE
  ↓
REFINE
  ↓
LEFTOVER
```

### Privacy-Restricted Policy

```text id="kivb5w"
DECIDE
  ↓
REFINE
  ↓
LEFTOVER

DELEGATE = prohibited
```

This reinforces:

> **Leaf Resolution is a policy-governed runtime process, not a fixed tree convention.**

---

# 26. Refinement Budget

Further differentiation has a cost.

Therefore, REFINE should be governed by a **Refinement Budget**.

The budget may include:

```text id="2mbs9s"
maximum depth

maximum comparisons

maximum runtime

maximum token/model calls

maximum external queries

maximum evidence requests

maximum monetary cost

maximum latency
```

A refinement may be structurally possible but economically unjustified.

Thus:

> **Possible refinement does not imply justified refinement.**

---

# 27. Expected Refinement Value

A useful future concept is **Expected Refinement Value (ERV)**.

Conceptually:

```text id="mfnrve"
ERV
=
Expected Decision Improvement
-
Refinement Cost
-
Additional Risk
```

This need not initially be numerical.

A rule-based runtime can ask:

```text id="7d67jy"
Will another differentiation
materially change the decision?

Will it reduce important uncertainty?

Will it uncover relevant counter-evidence?

Is the cost acceptable?

Is the decision reversible?
```

If not, DECIDE may be preferable.

---

# 28. Low-End User Flow

For a low-end application user, the framework should hide most of this complexity.

A simple configuration might expose:

```text id="7pfq28"
Decision Policy:
    Conservative
    Balanced
    Aggressive

Refinement Budget:
    Low
    Medium
    High

Unknown Handling:
    Recommend
    Defer
    Leftover

Delegation:
    Disabled
    Trusted Only
    Enabled
```

The runtime converts these settings into detailed policies.

The user does not need to understand every internal CCC.

---

# 29. Expert User Flow

An expert user may define:

```text id="cqwd0h"
Custom Decision Sufficiency

Custom Evidence Requirement

Custom Counter-Evidence Rule

Custom Refinement Policy

Custom Leftover Policy

Custom Delegation Policy

Custom Sandbox Capability

Custom Audit Contract
```

Both low-end and expert users still pass through the same Leaf Resolution Gate.

This preserves a stable runtime architecture.

---

# 30. Example: Market Decision

Suppose structural localization reaches:

```text id="k25c0p"
Leaf:
High-Volatility,
Event-Driven,
Positive-Momentum Regime
```

The caller asks:

```text id="quapfy"
Should the system recommend
a long position?
```

Possible resolutions:

### DECIDE

```text id="3ohh1p"
Evidence strong
Counter-evidence weak
Risk within policy
Current structure sufficient

→ RECOMMEND
```

### REFINE

```text id="f3d8xf"
Need to distinguish:

temporary event spike
vs
persistent regime shift

Known comparator exists

→ REFINE
```

### LEFTOVER

```text id="xczs38"
Novel event interaction
Conflicting historical patterns
No validated deeper structure

→ LEFTOVER
```

### DELEGATE

```text id="v4nqj9"
Local structural context is useful
External portfolio optimizer authorized

→ package leaf
→ DELEGATE
```

The same leaf therefore supports four fundamentally different runtime paths.

---

# 31. Example: AI Coding

Suppose CallingGraph localization reaches:

```text id="rdu50r"
Leaf:
Certified Local CallingGraph Region
```

The caller asks:

```text id="eky5qz"
How should Function X be modified?
```

The structural runtime may not itself generate code.

But it may know:

```text id="f0i5fc"
relevant callers

relevant callees

type constraints

certified paths

runtime evidence

forbidden mutations
```

This may not be enough for DECIDE.

But it may be enough for:

```text id="qvf71b"
DELEGATE
```

to a coding agent.

Thus:

> **A leaf may be computationally sufficient even when it is not decision sufficient.**

---

# 32. Example: Policy Changes Resolution

Suppose the same coding leaf is evaluated under two policies.

### Development Policy

```text id="lrf2mi"
Sandbox execution allowed
Tests available
Mutation reversible

→ DELEGATE
```

### Production Emergency Policy

```text id="mqqj9u"
External mutation prohibited
Only certified changes allowed

→ LEFTOVER
```

or:

```text id="q9htgc"
→ REFINE
```

if an internal certified refinement path exists.

The structure did not change.

The resolution policy did.

---

# 33. Leaf Resolution and Structural Growth

LRG also clarifies how structural growth begins.

```text id="i6s2b1"
Leaf
 |
 +-- DECIDE
 |      |
 |      v
 |   Runtime Result
 |
 +-- REFINE
 |      |
 |      v
 |   Existing Structural Expansion
 |
 +-- LEFTOVER
 |      |
 |      v
 |   Delta Intelligence
 |
 +-- DELEGATE
        |
        v
   External Computation
        |
        v
   Evidence / External Delta
```

Thus all four outcomes can contribute information to future structural memory.

But they do so differently.

---

# 34. REFINE and Structural Growth Are Not Identical

REFINE may use structure that already exists but was not yet unfolded.

For example:

```text id="9bwyge"
Folded Structure
      |
      v
Current Leaf
      |
      v
REFINE
      |
      v
Known Local CCC
```

This is structural unfolding.

Structural growth, by contrast, creates or promotes a new mature structure:

```text id="o3cmxz"
LEFTOVER
   |
   v
New Difference
   |
   v
Validation
   |
   v
New CCC
```

Therefore:

```text id="2fym9l"
REFINE
!=
GROW
```

although refinement may later expose the need for growth.

---

# 35. DELEGATE and Structural Growth Are Also Distinct

DELEGATE does not authorize an external caller to modify the parent structural memory.

Instead:

```text id="awpffz"
DELEGATE
   |
   v
External Computation
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
Return to Runtime
```

Only after validation and policy review may external findings influence structural growth.

This preserves the distinction between:

```text id="hnxdzp"
External Intelligence
```

and:

```text id="7kfqpm"
Structural Authority
```

---

# 36. The Leaf as a Structural Handoff Point

The introduction of DELEGATE changes the conceptual meaning of a leaf.

Previously:

```text id="7v8gyc"
Leaf = End
```

Then:

```text id="2ykf1i"
Leaf = Decision Candidate
```

Now:

```text id="w4bgmy"
Leaf
=
Structural Resolution Point
+
Possible Computation Handoff Point
```

This is an important transition.

A leaf may terminate one structural search while initiating another computation.

---

# 37. Canonical Leaf Resolution Principles

The framework can now be summarized through a set of principles.

## Principle 1 — Structural Leaf Is Not Decision Leaf

> **A structural leaf is not necessarily a decision leaf.**

---

## Principle 2 — Leaf Means Current Structural Boundary

> **A leaf represents the current boundary of mature structural differentiation, not necessarily the end of computation.**

---

## Principle 3 — Decision Sufficiency Is Task- and Policy-Relative

> **The same leaf may be sufficient for one request and insufficient for another.**

---

## Principle 4 — Differentiate for Decision Relevance

> **Further differentiation is justified by decision relevance, not merely by the existence of additional differences.**

---

## Principle 5 — Every Leaf Has an Explicit Runtime Resolution

> **Leaf resolution terminates in DECIDE, REFINE, LEFTOVER, or DELEGATE.**

---

## Principle 6 — REFINE Requires a Mature Path

> **REFINE means the runtime knows how to look deeper.**

---

## Principle 7 — LEFTOVER Preserves Structural Honesty

> **LEFTOVER means the current mature structure is insufficient and no trusted deeper resolution is presently available.**

---

## Principle 8 — DELEGATE Is a Positive Computational Outcome

> **DELEGATE means the current leaf is useful enough to become a bounded computational handoff to another caller.**

---

## Principle 9 — Decision Authority Is Not Action Authority

> **A runtime may be permitted to decide or recommend without being permitted to execute the resulting action.**

---

## Principle 10 — Leaf Resolution Is Policy-Governed

> **Leafhood is structural; leaf resolution is policy-relative.**

---

# 38. Canonical GST-CGI Runtime at the Leaf Boundary

The larger runtime now becomes:

```text id="35knwe"
                  POLICY CONTROL PLANE
                         |
                         v
                Generalized Trigger
                         |
                         v
                Evidence / Counter
                         |
                         v
                   Two-Way CCC
                         |
                         v
              Structural Localization
                         |
                         v
                        LEAF
                         |
                         v
                LEAF RESOLUTION GATE
                         |
        +----------------+----------------+----------------+----------------+
        |                |                |                |
        v                v                v                v
     DECIDE           REFINE          LEFTOVER         DELEGATE
        |                |                |                |
        v                v                v                v
    Action /         Internal          Delta          Leaf Sandbox
 Recommendation     Unfolding       Intelligence        Package
        |                |                |                |
        |                |                |                v
        |                |                |          External AI /
        |                |                |          Application
        |                |                |                |
        +----------------+----------------+----------------+
                         |
                         v
                  Evidence / Result
                         |
                         v
                 Structural Memory
```

This is the bridge between structural localization and computational growth.

---

# 39. From Leaf Resolution to Delegated Unfolding

The most novel branch of the LRG is:

```text id="cvqgpp"
DELEGATE
```

because it changes what the AI runtime can return.

Instead of only:

```text id="pmrzf9"
Answer
Decision
Recommendation
```

the runtime may produce:

```text id="uvg8sw"
Executable
Policy-Bounded
Evidence-Bearing
Local Structural Computation
```

This requires a new artifact:

> **Leaf Sandbox Package (LSP)**

The package must not expose unrestricted parent-runtime authority.

It must be projected, bounded, auditable, and policy-controlled.

That leads directly to the next GST-CGI article.

---

# 40. Conclusion

Structural localization and decision resolution are different operations.

A Metric Differential Tree may locate a structural region.

A Two-Way CCC may discriminate increasingly local differences.

A Generalized Structural Trigger may contribute state, comparison, behavior, evidence, and policy-relative perspective.

But eventually structural search reaches a boundary.

That boundary is the leaf.

The leaf should not automatically mean:

```text id="vskx1h"
Return answer.
```

Instead:

```text id="6jwr6e"
Leaf
  |
  v
Evaluate Decision Sufficiency
  |
  v
Leaf Resolution Gate
  |
  +-- DECIDE
  |
  +-- REFINE
  |
  +-- LEFTOVER
  |
  +-- DELEGATE
```

This resolves several important ambiguities.

`DECIDE` means current structure is sufficient.

`REFINE` means a mature deeper differentiation path exists.

`LEFTOVER` means current mature structure is insufficient.

`DELEGATE` means the leaf itself can become a bounded computational structure for another caller.

The central principles are:

> **A structural leaf is not necessarily a decision leaf.**

> **Further differentiation should be justified by decision relevance, not merely by the existence of additional differences.**

> **Leafhood is structural; leaf resolution is policy-relative.**

And, with the introduction of delegation:

> **A leaf need not be the end of computation. It can become a policy-governed computational handoff point.**

This last transition opens a new structural-intelligence model.

The runtime can move from:

```text id="9p80q7"
Answer-as-a-Service
```

toward:

```text id="rm6wr1"
Structural-Computation-as-a-Service
```

The next article therefore asks:

> **How can a localized leaf be safely packaged and transferred so that an external application or AI can continue structural computation without receiving unrestricted authority over the parent runtime?**

That is the subject of:

**GST-CGI-005 — Leaf Sandbox Package and Delegated Structural Unfolding.**

---

## Project Reading Path

```text id="cfhqeu"
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
