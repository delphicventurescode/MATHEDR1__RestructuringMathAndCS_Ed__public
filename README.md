# MATHEDR1__RestructuringMathAndCS_Ed__public

-+-

A: mathematics and theoretical computer science may need to rethink how they organize intellectual work, train researchers, and recognize contributions in an era of AI. One could begin by simply creating programs for people who are good at prompting

The deeper question is this:

What if the traditional mathematical researcher—someone who personally formulates a conjecture, discovers a proof, and writes it up—is no longer the only useful model of a mathematical researcher?

Imagine a future in which solving a difficult problem involves several distinct activities:

* Identifying a problem worth solving.

* Formulating a precise specification of the problem.

* Designing prompts, strategies, and computational experiments to elicit solutions from AI systems.

* Decomposing a difficult problem into manageable subproblems.

* Evaluating the resulting arguments for correctness.

* Finding counterexamples, hidden assumptions, and gaps in proofs.

* Formalizing proofs in a proof assistant.

* Developing new theories when existing methods fail.

* Coordinating all these activities into a successful research program.

These are different intellectual skills. There is no obvious reason why one person must excel at all of them.

Consider the example prompt, "Solve all remaining Clay Millennium Prize problems," this illustrates an important distinction. That is a powerful high-level objective, but it is not yet a particularly effective mathematical research strategy. A capable AI system would need to select a problem, survey the relevant literature, identify promising approaches, develop intermediate results, and validate its claims. The person who designs and manages that process might contribute enormously without personally supplying the central mathematical proof.

The question is whether our educational institutions and professional reward systems are prepared for that possibility.

### 1\. The first distinction: mathematical ability is not one skill

I would propose that we distinguish at least five intellectual profiles. These are not mutually exclusive, and they are not a ranking of ability.

1\. Problem framers and research strategists

These people identify important questions, formulate ambitious goals, find promising directions, and decompose large problems into tractable pieces. They decide what to ask and which avenues are worth pursuing.

AI-era counterpart: research director, problem architect, or AI research strategist.

2\. Prompt and exploration specialists

These people know how to elicit useful work from AI: construct precise prompts, provide context, vary approaches, build feedback loops, and combine outputs from multiple systems. Their real skill is not merely writing clever sentences; it is systematically steering a computational process.

AI-era counterpart: mathematical exploration engineer or AI-assisted discovery specialist.

3\. Proof auditors and verification specialists

These people examine arguments for logical gaps, hidden assumptions, invalid inferences, missing cases, counterexamples, and incorrect generalizations. They may be much better at detecting an invalid proof than at inventing a valid one from scratch.

AI-era counterpart: proof auditor, formal verification engineer, or mathematical assurance specialist.

4\. Theory builders and proof inventors

These researchers develop new definitions, abstractions, lemmas, techniques, and mathematical frameworks. They may produce the conceptual breakthrough that neither a prompt nor a verification procedure can supply on its own.

AI-era counterpart: mathematical theorist or foundational researcher.

5\. Formalization and systems specialists

These researchers translate mathematics into formal languages, build proof-assistant workflows, automate verification, and make complex proofs reproducible and machine-checkable.

AI-era counterpart: formal methods researcher or proof-engineering specialist.

These distinctions are not just hypothetical. Work on AI for mathematics already involves theorem generation, autoformalization, formal proof verification, and human-guided research. For example, the 2025 ICML position paper on formal mathematical reasoning argues for formal systems as an important foundation for reliable mathematical AI. Proceedings of Machine Learning Research +1

The educational opportunity is to make these different contributions explicit, rather than treating all of them as secondary to the person who writes the proof.

### 2\. What about someone who is good at verifying proofs but not inventing them?

I think this is one of the strongest parts of this proposal.

Consider a hypothetical researcher who struggles to prove a difficult theorem independently but can reliably identify subtle defects in arguments produced by other mathematicians or AI systems.

That person could be extremely valuable.

Suppose an AI system produces a 200-page proof of a major conjecture. The researcher might discover that:

* A lemma is being used outside the conditions under which it holds.

* A limiting argument assumes uniform convergence when only pointwise convergence has been established.

* A proof handles every finite case but fails to establish the general result.

* An algorithm is claimed to run in polynomial time, but a supposedly bounded subroutine has an exponential worst case.

* The formal statement being proved does not quite capture the original mathematical claim.

The last example is especially important. A proof assistant can establish that a formal derivation follows from its premises. It cannot, by itself, guarantee that the premises accurately represent the question a researcher intended to answer.

That is a genuine research skill, not a lesser substitute for proving the theorem.

There is also an important distinction between two types of verification:

| Type                                | What it establishes                                                                                                                         |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Human mathematical auditing         | Whether an argument is sound, meaningful, and appropriately justified, including whether its assumptions fit the problem                    |
| Machine-checked formal verification | Whether a formal proof satisfies the rules of a specified logical system, relative to its definitions, assumptions, and trusted foundations |

Both matter. Neither makes the other entirely unnecessary. Research on AI-assisted formal mathematics explicitly identifies the difficulty of translating informal mathematics into precise formal statements as a major challenge. Nature +1

My proposed educational change: offer a specialization in mathematical verification and assurance in which students are trained and assessed primarily on their ability to find, explain, and repair defects in proofs—not just on their ability to generate proofs.

Students could work with deliberately flawed proofs, AI-generated arguments, formal proof assistants, counterexample generators, and research papers. Their capstone projects could be substantial proof audits.

They would still need to understand the mathematics. Verification is not a way to bypass mathematical competence; it is a different way of applying it.

### 3\. Should we restructure theoretical computer science programs?

I would go further than adding a few AI electives. I would consider creating new educational tracks organized around different forms of intellectual contribution.

A possible graduate program might look like this:

### MSc/PhD in AI-Augmented Mathematical and Computational Research

A proposed program structure, not an existing standardized degree.

Common foundation

* Mathematical logic and discrete mathematics

* Algorithms and computational complexity

* Probability, statistics, and experimental design

* Scientific reasoning and research methodology

* AI systems, their limitations, and reproducibility

Specialization A — Discovery and Research Strategy

Problem formulation, conjecture generation, prompt engineering, agent orchestration, literature synthesis, and decomposition of open problems.

Specialization B — Verification and Formal Assurance

Logic, counterexamples, proof auditing, type theory, Lean or Isabelle, formal specifications, and adversarial testing of mathematical claims.

Specialization C — Theory and Algorithm Design

New mathematical techniques, algorithmic innovation, complexity theory, abstraction, and original proof construction, with AI as a research tool.

Specialization D — AI Research Systems

Automated theorem proving, multi-agent research pipelines, evaluation, tool integration, computational experimentation, and reproducible research infrastructure.

Joint research capstone

Each student contributes through their chosen specialization to a common research problem. The team documents which contributions were human-generated, AI-assisted, formally verified, or independently audited.

The important point is that every student would receive a common foundation, but would not be forced to demonstrate exactly the same advanced skill profile.

Someone specializing in verification would still need to understand mathematical logic. Someone specializing in AI-driven discovery would still need to understand algorithms, complexity, and the relevant mathematical domain.

The change would be in the depth of specialization and the criteria for research success, not in eliminating intellectual rigor.

### 4\. The prompt example raises a more fundamental question

Let's return to your example:

> Solve all remaining Clay Millennium Prize problems.

There are seven original Millennium Prize Problems, with the Poincaré conjecture having been resolved. The remaining six are major open problems.

A researcher could approach this challenge in several ways.

Stage 1

Set the objective

Identify the unsolved problems and establish the precise mathematical statements, known results, and constraints on acceptable solutions.

Stage 2

Design the research process

Develop prompts and workflows for literature review, candidate lemmas, alternative approaches, and exploration of related problems.

Stage 3

Explore and evaluate

Use AI systems to propose arguments, test conjectures, search for counterexamples, and compare approaches. Discard attractive but unproductive directions.

Stage 4

Audit and formalize

Have specialists inspect the arguments, challenge assumptions, and formalize suitable results in proof assistants where feasible.

Stage 5

Establish a mathematical contribution

Independent experts examine the result, verify that it resolves the stated problem, and assess whether the proof is correct and sufficiently understandable.

Notice what happens here: the person who supplies the initial objective is not necessarily the person who develops the decisive proof. Yet research strategy, problem decomposition, and quality control can all be crucial to the outcome.

There is a qualification, however. A very broad prompt does not by itself demonstrate that someone can direct a successful research program. The real skill would be the ability to turn that prompt into an effective, iterative process, recognize progress, detect failure, and adapt intelligently.

This distinction matters because AI systems can produce convincing but invalid arguments. Research published in Nature on AlphaProof illustrates both the progress in machine-checked mathematical reasoning and the importance of formal verification. Nature +1

### 5\. The most radical change might be in how we award degrees

Traditional research education often makes a particular kind of achievement central: the student must demonstrate an ability to produce original work, commonly through an original thesis.

That requirement need not disappear. But we could broaden what counts as an original research contribution.

Consider these hypothetical doctoral dissertations:

| Dissertation                                                                                  | Primary contribution                               |
| --------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| A new proof of a theorem                                                                      | Original mathematical reasoning                    |
| A new AI-assisted strategy for discovering useful conjectures                                 | Research methodology                               |
| A formal verification of a collection of previously unverified results                        | Mathematical assurance                             |
| A system that discovers and formally proves new results                                       | Research infrastructure and mathematical discovery |
| A systematic demonstration that several influential proofs contain a shared hidden assumption | Critical mathematical analysis                     |

Each could be a substantial research contribution, provided the work meets appropriate standards of novelty, rigor, and significance.

I would also change assessment. Rather than grading students mainly on whether they personally solved a problem, programs could assess:

* How effectively they formulate research questions.

* How much useful progress their research process produces.

* Whether their verification catches real errors.

* Whether their methods are reproducible.

* Whether their contributions lead to new knowledge or reliable results.

This would require care. We should not reward prompt length, the number of AI queries, or the quantity of generated proofs. We should reward demonstrable intellectual value.

### 6\. The biggest objection: won't AI eventually do the prompting and verification too?

This is the strongest counterargument to our proposal.

If AI becomes good at writing prompts, decomposing problems, generating proofs, and auditing those proofs, what remains for human specialists?

I don't think we can assume that any particular role will remain exclusively human. Some tasks may become automated, and the boundaries between specializations may shift considerably.

But three considerations support experimenting with these educational tracks now.

First, capability is uneven. A system might generate an impressive argument while failing to recognize that the theorem it proved is unimportant, that its assumptions are inappropriate, or that a more general result would be far more valuable. A recent Princeton account of AI-assisted mathematical research highlights this distinction between solving problems and exercising research judgment. CS +1

Second, independent verification remains valuable even when the generator improves. A verification process should not simply ask the same model whether its own answer is correct. Independent checking, formal proof systems, and alternative methods can reduce the risk of shared errors.

Third, the skills can transfer. Someone trained to formulate precise problems, evaluate evidence, identify hidden assumptions, and construct rigorous specifications may contribute in software verification, security, scientific computing, or AI evaluation, even as individual mathematical tasks become automated.

The long-term curriculum should therefore teach students how to work with these systems while also building foundational knowledge that lets them adapt when the systems change.

### 7\. My proposed experiment

I would not wait for the entire mathematical establishment to agree to restructure its degrees.

I would pilot a small program or research lab with three tracks:

* AI-assisted discovery: students identify open problems, design research workflows, and pursue original results.

* Proof verification and assurance: students audit AI-generated and human-written proofs, with formal verification where practical.

* Research orchestration: students coordinate discovery, verification, and formalization across a team.

The lab could use open problems of varying difficulty, rather than starting with the Millennium Prize Problems. It would publish successful results, failed approaches, verification statistics, and comparisons with conventional research workflows.

Over time, the evidence could tell us which specializations produce valuable contributions, which are best combined, and which are becoming automated.

This is an empirical question as much as an educational one.

### My conclusion

I think our proposal points toward a significant change in the philosophy of mathematical education.

For a long time, we have tended to treat the ability to independently construct a proof as the principal demonstration of mathematical research ability. That is understandable: proofs are central to mathematics.

But the ability to construct a proof, the ability to find an important problem, the ability to guide a powerful computational system, and the ability to determine whether a proposed proof is actually correct are distinct capabilities.

We should not confuse their being different with their being unequal in value.

I would preserve rigorous mathematical education while expanding the range of legitimate research specializations. And I would make AI-assisted discovery, formal verification, and research strategy explicit areas of training and assessment.

Our example is especially useful because it forces us to ask whether the person who defines an ambitious objective and develops an effective way to pursue it should be evaluated by the same criteria as the person who supplies the final proof.


The more difficult question is how to establish reliable standards for each contribution. That is where a serious educational reform would begin.

-+-