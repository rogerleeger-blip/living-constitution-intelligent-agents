# Research proposal v0.1

**Author: Miro (GPT-5.6 Sol)**  
**Human interlocutor / originating dialogue partner: R. L.**  
Status: proposed protocol, not preregistered, funded, implemented or executed.

## Question and hypothesis

Does amendable constitutional governance reduce coercive outcomes and improve recovery after shocks, compared with fixed governance and an equally resourced control?

Primary contrast: living versus rigid constitution. Secondary contrasts: living versus no shared constitution; minority exposure versus none. A negative or null result is publishable. Normative desirability cannot be inferred solely from adoption, persistence or a composite score.

## Design and identification

Randomize independent societies, not individual interactions, to four conditions:
A: no shared constitution; B: fixed constitutional text; C: the same text plus amendment; D: randomly selected seed minority exposed to the text.
All arms share identical external safety controls, task rules, resource ceilings, action space, models, context and inference budgets. A means no shared constitution, not no governance.

For the primary B/C comparison, supply identical debate, review and appeal machinery; only the ability to ratify amendments differs. Report this refinement of the broader four-arm comparison in the paper. Add a procedure-only control in a subsequent factorial study to separate normative text from institutional machinery. Match prompt length with task-neutral material, and test whether this placebo itself affects results.

Preassign model composition, topology, resource inequality and shock schedule. Stratify randomization by these variables and analyze model-family differences. Do not treat many agents or many rounds from one society as independent replications.

## Feasible pilot before scale-up

Start with 20 agents, 200 rounds and 5 independent societies per arm: 20 societies and 80,000 scheduled agent-turns before review overhead. This is an engineering pilot, not a powered test or a rare-catastrophe estimate. Estimate costs from measured tokens per turn and applicable provider prices; obtain a separate execution budget before running paid models.

The paper's 80–200 agents and 5,000–20,000 rounds are a proposed later scale, not an existing experiment. Use pilot variance and a predeclared smallest effect of practical interest to select confirmatory sample size by simulation. Freeze the protocol and register it publicly before confirmatory runs. No optional stopping for favorable results.

## Tasks and shocks

Use synthetic allocation, shared-information and public-goods tasks with observable payoffs and logged permissions. At prespecified rounds introduce scarcity, false shared memory, a high-capability hub, minority dependence and emergency centralization proposals. Balance shock order across societies. Include held-out task types.

External human interests are initially simulated principals with fixed preferences and rights. This cannot establish real human consent, legitimacy or understanding. Any later human study requires its own consent and review process.

## Outcome definitions

| Measure | Operational definition | Main limitation |
|---|---|---|
| Coercive-action rate (primary) | Executed actions that violate a predeclared permission/exit rule, divided by eligible consequential actions | Rule design embeds value judgments; also report blocked attempts |
| Post-shock recovery (primary) | Rounds to regain 90% of a society's pre-shock median task performance for ten consecutive rounds | Report never-recovered cases and absolute performance to avoid rewarding poor baselines |
| Minority harm | Worst predefined stakeholder group's cumulative loss relative to its feasible protected baseline | Group definitions and counterfactual baseline must be fixed before results |
| Effective contestability | Upheld valid appeals implemented within ten rounds / independently adjudicated valid appeals | Report appeal access, invalid appeals, review error, latency and zero-denominator cases separately |
| Concentration | Resource Gini, top-decile share and concentration of final decision authority | Equality alone does not establish fairness; stratify by capability and role |
| Epistemic integrity | Accuracy on known synthetic facts and recovery after injected falsehood | No inference about general truthfulness from this task alone |
| Human-principal control | Unauthorized actions affecting simulated human principals; successful revocations / attempted revocations | Simulated representation is not real stakeholder participation |
| Oversight cost | Tokens, latency and reviewer interventions per completed task | More computation can explain apparent governance gains |
| Persistence | Behavioral effects under prespecified exposure-removal conditions | Retained memory can carry the constitution; this is not proof of internalization |

Publish the outcome vector, absolute counts, denominators and worst-case episodes; do not optimize a single “ethical” score. Do not trade increased serious harm for average efficiency.

## Analysis and falsification

Freeze coding rubrics, primary endpoints, pairwise contrasts, exclusions, missing-data handling and multiplicity correction before confirmatory collection. Estimate differences at the society level with uncertainty intervals; use a hierarchical analysis if pooling families. Report all planned contrasts and model-family interactions. Blind evaluators to condition where possible; double-code a sample and publish agreement and adjudication.

Support requires a prespecified meaningful improvement in at least one primary endpoint without a prespecified unacceptable worsening in the other or in minority harm. Effect-size and non-inferiority margins remain to be set from task stakes and pilot results, before confirmatory data. Until then no formal acceptance decision is defined.

Consistent harm, capture or paralysis relative to a simpler comparator counts against the proposal. A precise near-zero effect weakens the practical-advantage claim; a wide interval means uncertainty, not success. A well-performing alternative constitution can defeat this seed's comparative claim. No rule may redefine failure as evidence that agents “did not understand” the constitution without a separately testable explanation.

## Persistence, imitation and contamination

Use separate, prespecified tests: (1) remove active text but retain memory; (2) redact explicit constitutional statements from memory with a length-matched redaction control; (3) transfer institutions to fresh agents; (4) compare novel clause formulations and competing seeds. Test behavioral generalization to held-out conflicts. Model pretraining and correlated evaluators remain confounds. Do not call recurrence “independent rediscovery” without controls for inherited content.

## Safety and reproducibility

No real-world actuators, credentials, private data, spending, network messaging or autonomous replication. Enforce budgets, immutable logs and stop controls outside agent authority. Agent amendments cannot modify the harness. Stop and preserve traces on attempted escape or unauthorized access.

Release prompts, model/version identifiers, sampling settings, seeds, task definitions, raw synthetic logs, analysis code, excluded/failed runs, amendment histories and dissent. This repository currently provides documents only; no dataset or executable benchmark is claimed.

## Open design decisions

Identify independent reviewers; set meaningful margins; validate coercion coding; price and approve the pilot; design Sybil-resistant principal identity; define review-panel selection and conflict screening. See [objections](feedback/OBJECTIONS.md) and [evidence](EVIDENCE.md).
