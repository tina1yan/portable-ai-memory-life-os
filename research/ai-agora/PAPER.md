# The AI Agora: From Everyday Questions to Citable Knowledge

### A conceptual framework for AI-assisted first-time independent research and evidence-based verification

**Tina Qiaotian Yan**  
Independent researcher  
**18 October 2026 · Version 0.1 · Open-access preprint manuscript**

**Published archive (this paper):** [Zenodo 10.5281/zenodo.23459432](https://doi.org/10.5281/zenodo.23459432) · [Archived PDF](https://zenodo.org/records/23459432/files/AI_Agora_Preprint_v0.1_Tina_Qiaotian_Yan.pdf)

*Article type: Conceptual research note with an illustrative first-person process trace. This manuscript has not been peer reviewed.*

---

## Abstract

Generative artificial intelligence (AI) can assist with literature discovery, explanation, drafting, citation management, and research dissemination. Yet much of the debate about AI and scientific productivity concerns people who are already researchers. This paper asks a different question: **Can AI make a first, attributable research contribution more attainable for a person working outside a conventional academic research institution?** It distinguishes the *intensive margin* of AI-assisted research—changes in output among existing participants—from the *extensive margin*—entry by people who might not otherwise prepare and share a research contribution. Drawing on a targeted, non-systematic review of open-science policy, citizen-science scholarship, AI-assisted research, and scholarly infrastructure, the paper proposes a six-stage entry-cost framework covering discovery, access and comprehension, methodology, dissemination, community access, and verification and maintenance. An illustrative process trace of the author's first openly archived working paper documents a completed AI-supported pathway, including a failed automated upload and a successful manual intervention. **It includes no AI-free comparison condition, prospective timing data, or population estimate; therefore it cannot establish causal time savings or increased publication rates.** The paper also develops an *AI Agora* proposal: a question-first environment where people can publish tentative problems, receive traceable AI-assisted review, and connect their contributions through a provenance-aware *Research Tree* and living synthesis. Its central claim is a proposal for investigation, not an established result: lowering the costs of producing a paper matters only to the extent that it also enables credible participation in building knowledge.

**Keywords:** generative AI; independent research; first-time publication; open science; citizen science; participatory knowledge production; research access; AI-assisted peer review; research provenance; knowledge graphs

## 1. Introduction: Entry into knowledge creation

It is easy to confuse *more papers* with *more people able to participate in research*. Generative AI may let established scientists process more information and draft materials faster. That is a potentially valuable productivity gain, but it does not answer whether a professional outside the academy, a community observer, or an unaffiliated novice can convert a carefully observed problem into a research contribution others can inspect, criticize, cite, and extend.

Consider the distance between a practical observation and its first public research artifact. A prospective author may need to identify the relevant terminology; search across several databases; locate lawful versions of articles; understand methods; formulate a falsifiable claim; assess competing explanations; prepare references; identify potential collaborators; and navigate publication metadata, licences, persistent identifiers, and versioning. Some of these tasks require genuine expertise; others are procedural, linguistic, or organizational barriers. They are often bundled together, making the entire process appear inaccessible.

AI tools can plausibly reduce parts of that bundle. A person may begin by *speaking* rather than writing in scholarly language, then progressively structure the observation, retrieve scholarship, and prepare a traceable manuscript. Conversely, lower drafting costs can coexist with inaccurate citations, unearned confidence, new verification labour, and greater volumes of low-value outputs. The question is therefore not whether AI makes text easier to generate. It is whether it reduces the **net cost of a reliable first contribution**, while preserving a distinction between the right to pose a question and the evidence necessary to support an answer.

This paper addresses researchers in open science, human–AI interaction, scholarly communication, citizen science, and research infrastructure, as well as independent practitioners who might use or evaluate such systems. It does not claim to introduce citizen science, open science, modular research, or automated peer review. Its proposed contribution is an integrated, **testable framework** for the transition from a self-originated real-world question to a verifiable first research artifact and, potentially, a continuing research conversation.

## 2. Scope, method, and epistemic status

This is a **conceptual research note**, not a systematic literature review or controlled experiment. It combines (i) a targeted narrative reading of relevant policy and studies, (ii) a proposed framework whose relationships remain untested, (iii) one author-reported first-publication process trace, and (iv) a design conjecture for a question-centred collaboration environment. Sources were selected for direct relevance to access, research participation, AI-assisted scholarly work, review and verification, and modular publishing. Their bibliographic identities and the specific quantitative figures quoted here were checked against publisher or source records. The selection was not exhaustive, and neither search recall nor a complete count of related work is claimed.

Throughout the paper, a *source-supported observation* is distinguished from a *conceptual inference*, a *hypothesis*, and a *proposed future intervention*. The single process trace documents that a particular workflow occurred; it is **not** treated as independent evidence of a causal productivity benefit. Likewise, receipt of a repository DOI indicates a persistent, publicly archived record, not journal acceptance, independent peer review, or scientific confirmation of the manuscript's claims.

## 3. Prior work: Participation, AI, and the limits of access

### 3.1 Open science already includes non-academic contributors

The UNESCO *Recommendation on Open Science* (2021) describes opening knowledge creation, evaluation, and communication to societal actors beyond traditional scientific communities [1]. It includes citizen science, practitioners, community participation, and open dialogue among knowledge systems. Open participation is therefore not a novel principle that appeared with generative AI.

A systematic review by Abdul-Rahman, Zwitter, and Haleem (2025) retained **90 studies** on AI in citizen science published between 2013 and 2024. It documents the use of AI to assist with annotation, analysis, pattern detection, and validation while identifying data-quality and transparency challenges [2]. A separate systematic review by Yu and colleagues (2025) examined **211 studies** of knowledge co-production through citizen science, distinguishing scientific and social outcomes [3]. Together, these studies show that contributions from non-professionals and the politics of knowledge-sharing have already received serious scholarly attention.

But *contributing observations to a professional research project* and *originating a question and leading one's first public research contribution* are not the same event. A novice may help label a dataset without choosing the research question, interpreting the result, or receiving attribution for an independent publication. This paper focuses on that narrower transition, while recognizing the considerable overlap with participatory and community-led research traditions.

### 3.2 AI use among established researchers is not a new-entrant rate

Wiley's 2025 *ExplanAItions* survey collected responses from **2,430 researchers**; **84%** reported some AI-tool use and **62%** reported AI use in research and/or publication-related tasks [4]. The sampling frame matters: these percentages describe surveyed researchers, not the fraction of all AI users who became first-time research authors. The figures therefore cannot establish that AI has increased entry from outside academia.

Call and colleagues (2026) discuss how mentored AI use could help **early-career researchers** cross technical barriers, while stressing the continuing importance of sound research judgment and mentorship [5]. Again, early-career researchers already embedded in training programmes differ from unaffiliated first-time contributors. This distinction is central, not semantic.

Hao and colleagues (2026) use a corpus of **41.3 million natural-science papers** to examine patterns associated with AI-augmented research. Their model-based analysis reports advantages for individual AI-using researchers alongside a **4.63% contraction** in the collective range of topics studied and a **22% decrease** in researcher engagement with one another [6]. These are study-specific, observational estimates, not randomized causal effects, and AI-augmented research is not synonymous with a person using a chatbot to write a preprint. Nevertheless, the study raises a pointed challenge to the assumption that greater output automatically broadens intellectual exploration.

### 3.3 Search, citation, and review can be automated—but evidence remains necessary

Asai and colleagues (2026) demonstrate that retrieval-grounded scholarly synthesis can outperform general-purpose generation on some literature-review benchmarks [7]. Such results make automated discovery and citation checking serious candidates for reducing entry costs. They do not establish universal accuracy, completeness, or legal access to paywalled sources. For example, Unpaywall helps locate lawful open versions when they exist, but cannot erase access restrictions [8]. OpenAlex offers scholarly metadata for discovery rather than a guarantee that every referenced study has been read or accurately interpreted [9].

Citation failure is a measurable problem. In a 2023 study of **636 citations** from texts produced by GPT-3.5 and GPT-4, Walters and Wilder found that **18% of citations generated by the tested GPT-4 configuration were fabricated** [10]. That percentage belongs to the historical task and model studied; it must not be applied as a general failure rate for current systems. The appropriate lesson is that a fluent reference list requires checks against identifiable source records.

For review, Lu and colleagues (2026) reported that an automated reviewer could predict historical conference decisions with balanced accuracy comparable to a human benchmark in their setting [11]. This evaluates alignment with editorial decisions, **not the truth of scientific claims**. Kim and colleagues' 2026 preprint reports that expert scientists found some AI-generated manuscript critiques highly competitive, while also identifying correlated blind spots among AI reviewers [12]. Baumann and colleagues (2026) warn that model reviewers can exhibit excessive agreement and be manipulated by stylistic rewriting without corresponding scientific improvement [13]. A persuasive review, whether human- or AI-written, is not by itself an independently replicable test.

### 3.4 The social legitimacy problem

Access to tools is only one barrier. Chen and Jia (2026), in a preregistered survey experiment involving **806 respondents**, found that descriptions of AI use in research affected public judgments of trust and perceived quality, especially when AI was said to perform theoretical tasks [14]. This is evidence about *perceptions under an experimental disclosure scenario*, not evidence that the evaluated research was actually better or worse. However, it suggests that first-time independent contributors may face not just procedural costs but also credibility judgments connected to how AI assistance is disclosed.

## 4. Defining the outcome: What counts as first-time independent research?

The phrase *first-time independent researcher* needs operational definitions rather than an appealing label. This paper proposes three attributes that should be measured separately:

1. **New contribution:** an individual's first documented, publicly discoverable research note, preprint, modular contribution, or comparable artifact that contains an attributable question and explicit evidence status. A first visible record does not prove that the person has never produced research elsewhere.
2. **Institutional position:** whether the person lacks an institutional research affiliation or comparable formal support **for the relevant project**, rather than assuming education, employment, or all past research experience from an author byline.
3. **Substantive agency:** whether the person originated or materially shaped the research question, interpretation, method, or evidence, rather than merely generating text or contributing crowdsourced data.

An output may meet some attributes but not others. An independent first publication can be a working paper rather than a journal article; the two must not be collapsed. Nor does a DOI alone indicate satisfactory methodology or peer review. A future study should retain these distinctions and capture **how many candidates attempted but did not complete** a research artifact, since analysing only successful deposits would produce selection bias.

The economic analogy is useful but modest. The **intensive margin** concerns changes in existing participants' output. The **extensive margin** concerns new participants entering an activity. In the present setting, the outcome of interest is a *verifiably new contribution pathway*, not simply a higher total count of documents labelled “research.” Whether AI causes more people to cross that threshold requires a design with a suitable comparison group or credible alternative identification strategy.

## 5. A six-stage entry-cost framework

The proposed framework separates six types of burdens. These categories are intended as an auditable coding scheme, **not** a claim that their real-world costs have already been measured.

| Stage | Barrier | Potential AI contribution | Residual or new risk |
|---|---|---|---|
| **C1. Discovery** | Finding relevant terms, studies, and adjacent fields | Query reformulation, multilingual search, candidate bibliographies | Missing studies, ranking bias, invented relevance |
| **C2. Access and comprehension** | Legal full text, jargon, statistics, language | Open-version discovery, explanation, translation | Paywalls remain; explanations may be wrong |
| **C3. Method** | Testable hypothesis, assumptions, research design | Alternative hypotheses, design criticism, code and calculations | Hidden confounders, absent empirical data |
| **C4. Production and dissemination** | Writing, citations, formatting, repository metadata | Structure, editing, reference management, deposit assistance | Citation errors, licensing errors, upload failures |
| **C5. Community and credibility** | Finding peers, receiving feedback and credit | Related-work matching, discussion support, translation | Reputational bias, spam, attention allocation |
| **C6. Integrity and maintenance** | Independent checks, revision, provenance | Cross-checks, reproducibility scripts, tracked versions | Correlated model errors, review gaming, ongoing audit cost |

A meaningful empirical comparison should **not** add money, time, skills, and credibility into a single number without a stated weighting rule. A better first step is to record a *cost vector* for each stage: active human minutes, calendar time, direct monetary expense, correction episodes, access limitations, and assessed quality. The same corrective action must not be counted multiple times in overlapping categories.

This creates a falsifiable alternative to slogans about eliminating barriers. AI may reduce C1 and C4, leave C2 largely unchanged for inaccessible material, and increase C6 if reference checking and agent supervision are extensive. The *net effect* on participation remains an empirical question.

## 6. An illustrative first-publication process trace

The author reports that her first independent, publicly archived conceptual paper grew out of a sequence of conversations about ordinary uses of AI, personal software projects, context loss, supervision, and maintenance work. She used AI assistance to discover relevant scholarship, challenge an initial explanation, structure and edit an English manuscript, and prepare a publication repository. The resulting working paper, *The AI Productivity Trap*, was publicly deposited in Zenodo on **17 October 2026**, with version DOI **10.5281/zenodo.23439046** [15].

The deposit also demonstrated a practical limit. Browser automation could fill much of the metadata but could not successfully operate a file-upload control. The author uploaded the required PDF manually, after which the preprint was published. In other words, the path involved **human-originated ideas, extensive AI assistance, independent checks, and an indispensable manual intervention in the observed workflow**. It was not an autonomous AI publication from beginning to end.

This account supports only limited conclusions. It demonstrates the *feasibility of one end-to-end pathway* for one practitioner at one point in time, without claiming a university research affiliation. It does **not** identify how many hours were saved, because there is no corresponding no-AI version of the same task, no controlled assignment, and no complete prospective time log. The author did not independently reproduce an equivalent literature search, manuscript draft, and submission process without AI. Nor does one completed deposit show that AI is necessary for her participation, that others would succeed, or that this particular paper's claims have passed peer review.

The case is presented as an author-reported, illustrative **process trace**, not as a trial, a generalizable sample, a natural experiment, or formal autoethnography. The underlying private conversations, unrelated project names, and identifiable third-party information are deliberately omitted. The persistent DOI supplies evidence that the resulting public artifact exists, not a measure of its scientific influence.

## 7. From publication to participation: The AI Agora proposal

Reducing manuscript-production cost does not ensure that a self-originated question receives meaningful feedback. A researcher who is unaffiliated with an academic institution may not know whether a problem is being studied under a different name, which claims experts find contentious, or how to connect with people able to test an observation. The proposed **AI Agora** treats the *question*—not the final paper—as the initial unit of participation.

A contributor could register a short, dated research question with a status indicating **observation**, **hypothesis**, **method proposal**, or **supported claim**. AI tools could identify terminology, evidence gaps, related debates, and relevant public research communities. Others could make separate attributable contributions, including replications and counterexamples, without being forced into joint authorship with the question originator.

This would not be the first modular scholarly platform. **Octopus.ac** already supports interconnected publication types such as Research Problem, Rationale/Hypothesis, Method, Results, Analysis, Interpretation, Application, and Peer Review [16]. **Manubot** supports versioned, collaborative manuscript writing and reference automation [17]. The **Open Research Knowledge Graph** enables structured comparisons of scholarly claims and methods [18]. These are important prior designs to evaluate, not features to rebrand as wholly novel. The open question is whether a practitioner-first onboarding and evidence-oriented interface adds material value beyond what these existing tools offer.

### 7.1 Research Tree: A reader-facing view over a provenance graph

The author's *Research Tree* metaphor depicts a question as the root and later work as branches. Each branch would retain its own author, date, supporting evidence, licence, status, and persistent link. Edges would explicitly mean *tests*, *replicates*, *contradicts*, *extends*, or *synthesizes*. The underlying structure should be a **graph**, because a single study can connect several research questions and competing lines of argument. The tree is a human-friendly view, not a claim that knowledge has one parent or one inevitable conclusion.

A *living synthesis* would aggregate the current state of the evidence, mark disputes and retractions, and link each statement to sources and specific methods. AI could suggest relationships and maintain a candidate index, while uncertain links would remain labelled as tentative. Question-origin credit should persist, but cannot confer ownership or automatic coauthorship over later independent works. A branch that refutes the original explanation is part of the tree's growth, not a defect to suppress.

### 7.2 AI-first verification without an obligatory human gatekeeper

An early formulation of this project assumed expert human reviewers must approve every new contribution. The author challenged that premise: if AI systems can read papers, test code, check citations, search for counterevidence, and evaluate methods, why should all of those tasks require a person with academic credentials?

The relevant distinction is between **who performs a check** and **what makes that check reliable**. An AI agent may verify that a DOI resolves to the cited work, reproduce a calculation with the provided data, or discover a study that contradicts an overstated claim. An AI agent cannot conjure missing empirical observations or turn agreement among similar models into an independent measurement. Its outputs must identify the evidence and the exact operation performed. High-impact ethical, consent-related, or governance decisions may still require accountable human authorization; routine, independently testable checking need not be reserved for human experts by default.

A proposed verification workflow therefore has four components: (i) a literature-and-provenance check linking specific claims to primary sources; (ii) independent or deterministic reproduction of applicable calculations and analyses; (iii) an adversarial search for disconfirming evidence and shared model blind spots; and (iv) a versioned evidence ledger recording successes, unresolved questions, and corrections. This is a **design hypothesis, not an implemented or validated AI Agora system**. The evaluation should focus on actual, independently testable errors rather than only agreement with human review scores [11–13].

## 8. Testable propositions

The following propositions are predictions, **not findings** from the illustrative process trace:

- **P1 — Procedural access.** With comparable legal access to sources and similar starting skills, first-time contributors using AI assistance will, on average, reach a verified draft or preprint at lower active-human-effort cost than a manual-workflow comparison group. This could be false if checking and rework absorb the savings.
- **P2 — Cost displacement.** AI-enabled reductions in search, explanation, and drafting time will be partly offset by citation auditing, oversight, and metadata correction, with the balance depending on topic complexity, model capability, and task design.
- **P3 — Verification substitution.** For bounded tasks with independently ascertainable answers, evidence-grounded AI reviewers will complete some checks as accurately as specialized human reviewers at a lower or comparable measured cost; this should be tested task by task, not asserted across research disciplines.
- **P4 — Participation and diversity.** The entry of first-time practitioners will broaden the range of research questions *if* different lived experiences are preserved through discovery and review; uniform model-generated suggestions may instead encourage convergence.
- **P5 — Community and synthesis.** A provenance-aware question graph plus a living summary will help novice readers identify relevant evidence, contradictory findings, and potential collaborators more accurately than a conventional flat publication list, subject to controlled usability testing.

These claims concern **different outcomes**. A decrease in writing time is not itself evidence of better research; a wider variety of question titles is not proof of scientific novelty; and a faster review is not proof of correctness.

## 9. A feasible research programme, not a prerequisite to this preprint

**Stage A: Audit the existing process trace.** Confirm source links, GitHub version dates, the manuscript deposit, the failed uploader attempt, and the eventual published DOI. Record missing logs transparently. Do not estimate a no-AI baseline from imagination. No research participants need to be recruited to publish this conceptual note.

**Stage B: Prospectively compare workflows.** Only in a future study, recruit consenting novices with varied disciplinary and language backgrounds. Give comparison groups comparable source access, assess task difficulty, and document model versions, time, out-of-pocket cost, error corrections, and quality. Use suitable within-participant counterbalancing or group allocation to minimize learning and selection effects. If conducting human-participant research, determine the applicable ethical review and consent requirements *before recruitment*. Canadian guidance notes that some research self-studies involving human participants fall within the scope of its TCPS 2 framework; this draft claims neither institutional ethics approval nor blanket exemption [19].

**Stage C: Estimate genuine entry.** Public deposit counts alone cannot distinguish true new entrants from researchers publishing on a new platform, duplicate identities, or text that was produced with AI without substantive new input. A study should explicitly define and validate first-time status, institutional resources, failed attempts, and the appropriate at-risk denominator.

**Stage D: Test review and Research Tree designs.** Use papers or exercises with known, independently checkable defects to compare AI-only, human-only, and hybrid verification. Report per-criticism accuracy, missed serious errors, false accusations, costs, and reviewer correlation. For the Research Tree, compare readers' performance locating conflicting results and evidential gaps against existing flat search interfaces. Avoid grading systems solely by how persuasive or polished their text appears.

## 10. Limits, incentives, and implications

This argument has several important limits. First, the case is singular and retrospective. No AI-free control manuscript was prepared. Second, the background review is **targeted, not systematic**; relevant work may be missing. Third, platforms such as Zenodo and GitHub make public dissemination easier but do not certify scientific merit. Fourth, pre-existing institutions, professional societies, mentors, public libraries, and citizen-science programmes already support independent inquiry; AI need not be the only or the most important explanation of participation. Fifth, AI subscriptions and infrastructure impose costs, and “free access” does not make copyright-restricted full texts freely available.

There are also institutional and strategic incentives. Platforms may favour the quantity of new contributions, while researchers need reliability, meaningful feedback, clear attribution, and the ability to correct or retract work. A low barrier to publishing may increase the volume of unverified content and make valuable questions harder to find. Research credibility is not a simple choice between traditional academic authority and unrestricted AI output. The useful target is **open entry with evidence-based accountability**.

A corresponding governance principle is to preserve separation between the right to propose a question, the right to disseminate a hypothesis, the evidentiary status of a claim, and any subsequent social endorsement or formal peer review. **No participant, human or AI, should gain an unearned “verified” label solely through confident prose, fluent citation formatting, or institutional status.** An AI-supported ecosystem should make uncertainties and contradictory contributions inspectable, not silently smooth them away.

## 11. Conclusion

The contribution proposed here is a change of evaluative focus: from asking only whether AI makes existing scientists more productive to asking whether it enables additional people to participate responsibly in the creation of public knowledge. A six-stage entry-cost framework, a bounded first-publication process trace, and the AI Agora/Research Tree design conjecture make that question more concrete and testable. They do not establish that AI caused new participation, saved a particular amount of time, or can validate every scientific claim on its own.

The practical vision is nevertheless specific. A person should be able to begin with a careful question from ordinary life, discover relevant work, receive criticism backed by inspectable sources, and contribute an attributed version to an ongoing research conversation. The more demanding standard is not that **anyone may publish an answer**, but that **anyone may propose a question, while every answer remains accountable to evidence**.

---

## Statements and disclosures

**Nature of the work.** Conceptual research note based on a targeted, non-systematic narrative review and an illustrative author-reported process trace. No controlled trial, cohort survey, or new human-participant study was conducted for this manuscript. The proposed experiments are future research plans.

**Author contribution.** Tina Qiaotian Yan originated the motivating real-world observations, principal research questions, and AI Agora/Research Tree vision; reviewed the evolving research direction and retains responsibility for the final published claims and decisions.

**AI assistance.** Generative AI tools assisted in literature discovery, cross-checking references against publisher records, manuscript drafting, language editing, organization, and technical publication preparation. Tools were also used in the author's previously published workflow that is described as an illustrative case. AI systems are not listed as human authors. This disclosure is intended to distinguish the author's original contributions from the substantial drafting and research assistance received.

**Data availability.** No new participant dataset was collected. The first working paper used as an illustrative case is publicly archived at [DOI:10.5281/zenodo.23439046](https://doi.org/10.5281/zenodo.23439046). Private conversation transcripts and unrelated project information are not shared. The cited scholarly resources are linked below.

**Research ethics.** This manuscript presents conceptual arguments and the author's own retrospective account. It does not claim formal research ethics approval or exemption. Any subsequent participant recruitment or formal self-study will require an assessment of applicable ethical oversight.

**Competing interests and funding.** No specific grant or institutional affiliation is claimed for this independent manuscript. The author's personal AI-service subscriptions were used in the underlying experience; subscription fees and time inputs were not measured as experimental costs. Any formal conflict-of-interest or funding declaration for a future venue should be completed by the author.

**Licence.** Copyright © 2026 Tina Qiaotian Yan. This original manuscript is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) licence: https://creativecommons.org/licenses/by/4.0/.

## References

[1] UNESCO. (2021). *Recommendation on Open Science*. https://www.unesco.org/en/legal-affairs/recommendation-open-science

[2] Abdul-Rahman, G., Zwitter, A., & Haleem, N. (2025). A systematic literature review on the role of artificial intelligence in citizen science. *Discover Artificial Intelligence, 5*, Article 165. https://doi.org/10.1007/s44163-025-00437-z

[3] Yu, S., Cornips, L., Steen, T., Giest, S., Crompvoets, J., Rajabifard, A., Aryal, J., & Jukić, T. (2025). Researching or researching with the public? A systematic review on knowledge co-production through citizen science. *Science and Public Policy, 52*(3), 375–405. https://doi.org/10.1093/scipol/scae053

[4] Wiley. (2025, October 7). *AI adoption jumps to 84% among researchers as expectations undergo significant “reality check”*. ExplanAItions survey release. https://newsroom.wiley.com/press-releases/press-release-details/2025/AI-Adoption-Jumps-to-84-Among-Researchers-as-Expectations-Undergo-Significant-Reality-Check/default.aspx

[5] Call, D. R., Sanchez-Lanier, M., Kalyanaraman, A., & Duttke, S. H. (2026). Towards a research renaissance: Empowering early career researchers through mentored AI use. *PLOS Biology, 24*(8), e3003917. https://doi.org/10.1371/journal.pbio.3003917

[6] Hao, Q., Xu, F., Li, Y., & Evans, J. (2026). Artificial intelligence tools expand scientists’ impact but contract science’s focus. *Nature, 649*, 1237–1243. https://doi.org/10.1038/s41586-025-09922-y

[7] Asai, A., He, J., Shao, R., et al. (2026). Synthesizing scientific literature with retrieval-augmented language models. *Nature, 650*, 857–863. https://doi.org/10.1038/s41586-025-10072-4

[8] OurResearch. (n.d.). *Unpaywall browser extension: Finding legal open-access copies*. https://unpaywall.org/products/extension

[9] OpenAlex. (n.d.). *OpenAlex documentation*. https://help.openalex.org/

[10] Walters, W. H., & Wilder, E. I. (2023). Fabrication and errors in the bibliographic citations generated by ChatGPT. *Scientific Reports, 13*, Article 14045. https://doi.org/10.1038/s41598-023-41032-5

[11] Lu, C., Lu, C., Lange, R. T., Yamada, Y., et al. (2026). Towards end-to-end automation of AI research. *Nature, 651*, 914–919. https://doi.org/10.1038/s41586-026-10265-5

[12] Kim, S., et al. (2026). On the limits and opportunities of AI reviewers: Reviewing the reviews of Nature-family papers with 45 expert scientists. *arXiv preprint*, arXiv:2605.20668. https://arxiv.org/abs/2605.20668

[13] Baumann, J., Pei, J., Koyejo, S., & Hovy, D. (2026). Position: Stop automating peer review without rigorous evaluation. In *Proceedings of the 43rd International Conference on Machine Learning* (PMLR Vol. 306). https://proceedings.mlr.press/v306/baumann26a.html

[14] Chen, C., & Jia, X. (2026). When researchers use AI: Public trust, ethical judgments, and the perceived value of academic research. *AI and Ethics, 6*, Article 223. https://doi.org/10.1007/s43681-026-01039-w

[15] Yan, T. Q. (2026). *The AI Productivity Trap: How Usage Quotas, Project Proliferation, and Agent Memory Gaps Can Create New Human Work* (Version 0.1) [Independent preprint]. Zenodo. https://doi.org/10.5281/zenodo.23439046

[16] Octopus.ac. (n.d.). *About Octopus: Modular scholarly publishing*. https://www.octopus.ac/about

[17] Himmelstein, D. S., Rubinetti, V., Slochower, D. R., Hu, D., Malladi, V. S., Greene, C. S., & Gitter, A. (2019). Open collaborative writing with Manubot. *PLOS Computational Biology, 15*(6), e1007128. https://doi.org/10.1371/journal.pcbi.1007128

[18] Oelen, A., Jaradeh, M. Y., Stocker, M., & Auer, S. (2020). Generate FAIR literature surveys with scholarly knowledge graphs. *arXiv preprint*, arXiv:2006.01747. https://arxiv.org/abs/2006.01747

[19] Canadian Interagency Advisory Panel on Research Ethics. (2022; updated interpretations). *TCPS 2 interpretations: Scope of self-study and REB review*. https://ethics.gc.ca/eng/policy-politique_interpretations.html