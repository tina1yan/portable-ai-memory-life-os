---
name: independent-research-publishing
description: Develop an original observation into a source-backed, versioned independent research note, publish a verified GitHub manuscript, and optionally submit to Zenodo for a DOI.
---

# Independent Research Publishing Skill

A reusable process for independent practitioners, including first-time writers without a university affiliation. The human owns the original observations and research decisions; AI can assist with literature search, drafting, revision, publishing operations, and evidence checks.

## 1. Explore and protect the idea
- Capture the user's original claim, examples, objections, and desired public byline.
- Separate personal anecdotes from externally verified evidence.
- Anonymize projects, people, employers, identifiable events, and confidential records by default. Confirm before sharing new private ideas publicly.
- Label unsupported generalizations as hypotheses.

## 2. Review prior research
- Search papers, academic-publisher surveys, methods, and official documentation.
- Verify authors, dates, denominators, questions, and references.
- Distinguish literature coverage from proof of originality: “I did not find” does not mean “no one has studied”.
- Include competing mechanisms and findings that could refute the theory.

## 3. Freeze a working-paper version
Write a manuscript with title, author, date/version, abstract, keywords, literature, conceptual model, anonymized case observations, hypotheses, measurement plan, limitations, bibliography, and AI assistance disclosure.
- Never claim to have empirical proof without data or claim peer review for a working paper.
- Decide precisely what is included in the current version before execution; capture later ideas for a future version.
- Verify citations, anonymity, ownership, license and author identity.

## 4. Publish and verify GitHub source
Use an authorized repository or create an explicitly approved research subfolder.
Recommended files:
- README.md: thesis, scope, working-paper status and links
- PAPER.md: full original manuscript
- CITATION.md: proper author, version, repository permalink, DOI only after verified
- METHODS_AND_METRICS.md: research design where applicable
- CHANGELOG.md: dated version history
- LICENSE.md: chosen license
- PDF reader copy when available
Read back the public GitHub pages and ensure files are complete and links work; code repos and journal acceptance are distinct events.

## 5. Zenodo archival deposit (requires user authorization)
Official: https://help.zenodo.org/docs/get-started/quickstart/
- Confirm the authorized logged-in browser context, check existing drafts, prevent duplicates.
- Enter exact creator name, real title, publication/preprint or appropriate type, date, version, description, evidence limitations, keywords, language, license, and related GitHub URL.
- For a new work without another DOI, choose the option to request a DOI.
- Upload the COMPLETE manuscript file in accessible PDF or Markdown format. A link to GitHub is not a replacement for a file attachment.
- Confirm filename and nonzero bytes in the Zenodo Files area. Do not click Publish if file upload or required metadata failed.
- Save draft, preview, check privacy, attribution, references and archive preview.
- If authorized and checks pass, Publish; capture and independently verify the public Zenodo record URL and actual DOI.
- If web automation cannot operate an OS file picker or upload API, do not loop indefinitely or publish a metadata-only shell. Keep the saved draft and clearly report the exact minimum human step required.

## 6. Link and maintain the record
- Put actual verified DOI and Zenodo record URL back into GitHub README and CITATION.md.
- Make a revision through a new Zenodo record VERSION if the deposited file must change. Files of published records are immutable; Zenodo versioning: https://zenodo.org/help/versioning.
- Clearly distinguish versions. Never invent identifiers.
- Optionally build a website as a readable explainer linked to the paper and DOI; a website or SEO indexing is not a DOI.
- Reuse this skill for the next idea instead of spawning another parallel research operating manual.

## Publication gate checklist
[ ] Author name, intended public disclosure and chosen license confirmed
[ ] Literature checked; novelty and causal statements properly qualified
[ ] Complete manuscript and references checked
[ ] Public GitHub source read-back verified
[ ] Logged-in Zenodo session confirmed
[ ] Complete manuscript file attached to Zenodo, correct name and nonzero size
[ ] All required Zenodo metadata saved and validated
[ ] Zenodo public record and DOI verified after publication
[ ] GitHub citation and version files updated
[ ] User informed of actual published state vs draft/blocked state

## Minimal reporting
Paper | Author | Version | GitHub URL | Zenodo draft or public URL | DOI verified or not | File attached Y/N | Blocker.

## AI disclosure sample
"Original examples, hypotheses and interpretive conclusions were proposed and reviewed by the human author. AI tools assisted with research discovery, manuscript organization, editing, and/or technical submission tasks. The human author is responsible for the final claims, references and publication decision."

## Privacy and ethical safeguards
Never upload private chats, individual-level behavioral logs, personal secrets or employer records. An AI-generated statement of completion is not sufficient proof of actual publishing. Do not replace user approval required by the platform.