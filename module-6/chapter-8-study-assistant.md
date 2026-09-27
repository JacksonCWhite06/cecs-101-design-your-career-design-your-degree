# Chapter 8 AI Note-Taker and Study Assistant
## Preparation pack for the 48-Hour Tool Adoption Challenge

**Status:** Prepared with AI assistance; not evidence of student use or completion. The student has said they have not used the tool before. No study sessions, quiz results, or personal reflections are claimed here.

**Tool:** NotebookLM (Google's current help pages call it Gemini Notebook).
**Project:** Use the tool as an AI note-taker and study assistant, rather than train a new AI model.
**Source:** Student-supplied `chap 8.pdf`, 82 PDF pages. Author, edition, and exact chapter title have not been verified; do not label it Ciampa without checking the textbook.
**Scope:** Access control, authentication, firewalls, remote access, and VPNs. PDF pages 1–4 contain preceding material; the module introduction begins on PDF page 5 (printed page 295).

## First session
1. Open [Google's notebook tool](https://notebook.google.com/). Use an available free account; do not purchase an upgrade for this activity.
2. Record the real start date and time in the assignment, then calculate the end exactly 48 hours later.
3. Create a notebook named **CYBR 101 Chapter 8 Study Assistant**.
4. Add your Chapter 8 source for private study. The supplied PDF has no extractable text layer; check whether the tool can read it correctly. If it cannot, use your own typed notes from the chapter as the source and record this workaround.
5. Start with the source-check prompt below. Compare its response with the actual PDF before generating more material.
6. Keep the notebook private. Add only your original notes and results to the public GitHub repository, not the textbook PDF or page images.

Google's [getting-started instructions](https://support.google.com/gemininotebook/answer/16206563?hl=en) describe notebooks, source uploads, chat, study guides, and quizzes. Consult those instructions if the interface differs.

## Model behavior
Source material -> concise notes -> citation checks -> active-recall questions -> student answers -> corrections -> targeted review.

The assistant should identify its source, distinguish source facts from invented examples, admit when the source is unreadable, and wait for the learner's answer before showing quiz solutions.

## Copy-and-paste prompts

### 1. Check the source
> Use only my Chapter 8 source. Identify the module's learning objectives and the sections covering access control, authentication, firewalls, remote access, and VPNs. Exclude the preceding personnel-security exercises at the start of the PDF. Give source citations. State clearly if any page or diagram is unreadable. Do not guess the author, edition, chapter title, or page numbers.

### 2. Create notes
> Act as my CYBR 101 note-taker. Make a concise study guide with headings, definitions in plain English, and one original example per major topic. Cover identification, authentication, authorization, accountability, discretionary and nondiscretionary access control, authentication factors, firewall types and architectures, and VPNs where the source supports them. Cite each factual section. Mark your examples as invented examples. Keep historical technologies distinct from present-day recommendations.

### 3. Make flashcards
> Create 10 question-and-answer flashcards using only the source. Focus on distinctions I could confuse, especially authentication versus authorization, access-control MAC versus networking MAC, and firewall processing modes versus architectures. Include a source citation for every answer. Do not invent missing information.

### 4. Quiz me
> Give me a 10-question practice quiz based only on the source, mixing definitions with short scenarios. Ask one question at a time and wait for my answer. Then explain whether my answer is correct, cite the source, and keep my score. At the end, identify three topics I should review. Do not answer questions for me before I attempt them.

### 5. Fix a weak result
> Revise this specific answer: [paste the answer]. The problem I found is [describe the problem]. Check it against the source, correct only what the source supports, and explain what changed. If the source does not resolve it, say so.

## Reference sheet for checking outputs
These are AI-prepared paraphrases of selected, visually checked pages, not a complete chapter summary or an output from NotebookLM.

| Concept | Check the AI output against this distinction | PDF location |
|---|---|---|
| Access control | Determines a subject's permitted access to and use of an object or resource. | p. 7, Introduction to Access Controls |
| Discretionary control | A user can grant others access to resources under that user's control. | p. 8 |
| Nondiscretionary control | A central organizational authority manages access. | p. 9 |
| Identification | Presents an identity label; that label alone does not prove identity. | pp. 10–11 |
| Authentication | Checks a claimed identity. The chapter groups factors as something known, possessed, or inherent to the person. | p. 11 |
| Authorization | Determines what the identity may do. | p. 10 |
| Accountability | Makes activity traceable through tracking and monitoring. | p. 11 |
| Biometric errors | A false acceptance admits an unauthorized person; a false rejection excludes a legitimate person. CER is where the two rates meet. | p. 20 |
| Packet filtering | Evaluates packet-header information against configured rules. | p. 30 |
| PAT | Maps multiple internal communications to an external address using ports to distinguish them. | p. 40 |
| Tunnel-mode VPN | The illustrated gateway encrypts and encapsulates traffic; the remote gateway reverses this before delivery. | p. 70, Figure 8-20 |

**Original practice scenario:** A student enters a username, proves control of an account, is allowed to read one course folder, and has the access recorded. Label the four stages before checking: identification, authentication, authorization, accountability. This is an invented teaching example.

## Suggested 48-hour schedule
The session lengths below are suggestions, not completed time logs.

| When | Activity | Evidence to save |
|---|---|---|
| Day 1, opening session, 20–30 minutes | Check source readability; generate first notes; compare three claims with the PDF. | First prompt, output, three checks, journal 1 |
| Later on Day 1, 20–30 minutes | Try flashcards; identify a confusing result; revise the prompt and compare outputs. | Before/after wording, correction, journal 2 |
| Day 2, before the deadline, 20–30 minutes | Attempt the quiz without notes, review misses, and finalize the study guide. | Actual score, corrected answers, final notes, journal 3 |
| At or after the 48-hour end | Write the 8–12 sentence reflection using actual observations. | Reflection and completed checklist |

## Verification and evidence
Save your own outputs as `chapter-8-my-study-guide.md`, `chapter-8-my-flashcards.md`, and `chapter-8-my-quiz-results.md` alongside this pack after using the tool.

For at least three generated claims, record:

| Generated claim | Source page/section | Correct, incorrect, or unsupported? | My correction |
|---|---|---|---|
| Pending actual output | | | |
| Pending actual output | | | |
| Pending actual output | | | |

Record the real quiz result: **not attempted yet**. Record a prompt revision only if you actually make one. Do not claim this preparation pack as evidence that you learned NotebookLM or completed the 48 hours.

## Attribution
Preparation, prompts, and the reference sheet were drafted by Codex from the user's requested study-assistant concept and selected pages of the supplied PDF. The student must personally use the new tool and provide the journal, observed results, and reflection.
