<!-- SYNCED COPY: do not edit here. The original is D:\TU Dortmund\MASTER-PLAN.md on the laptop;
     change it there (or note the change under "Cross-course notes" in progress.md) and run
     sync-master-plan.py. -->

# Master Plan · Winter Semester 2026/27

*Version 3 · Sun 11 Oct 2026. Built from the Moodle course pages, every file in the course folders and the module
handbook. Version 3: **Industrial Data Science 1 dropped, German (A2 → B1) added**, gym moved from Wednesday to Friday.
Each course's detailed plan is in its own folder (`semester-plan.md`). **One week numbering for everything: W1 = week of
Mon 12 Oct 2026** (the plan starts that day; first lectures Tue 13 Oct); H1/H2 = the two Christmas weeks. Online
overview with a day view for any date: https://claude.ai/artifact/HWvuvfoN3XtLec2nHMRTa5*

---

## 0. The semester in one minute

- **4 university courses, 26 CP:** NLP 9 · Big Data 9 · Inference 5 · Data Science in Context 3.
  **Plus German** (self-study, A2 → B1, no credits, ~4.5 h/week).
- **Exams:** Big Data **Wed 10 Feb 17:30** · NLP **Fri 12 Feb 9:00** · Inference **March** (date not out yet) ·
  Data Science in Context: multiple choice (date not out yet). Second dates: NLP Mon 8 Mar · Big Data Tue 16 Mar.
- **Every week: about 40 hours of study + 4 gym mornings from home (Mon, Fri, Sat, Sun, ~3 h each)**, in one fixed
  timetable (§3). Sunday afternoon is free.
- **The method:** learn every lecture **on the same day**, test yourself **every week**, fix each mistake until it is
  right twice, never let a gap grow.
- **Where you stand (11 Oct):** Inference is about one week behind (session 1B part 1 done); Python is at level 1 of 5.
  W1–W2 fix both (§5): Inference catch-up and a **5-session Python bootcamp**.

---

## 1. Facts (from Moodle, 11 Oct 2026)

| Course | CP | Classes | Exam | Format |
|---|---|---|---|---|
| **NLP** (Rieger) | 9 | Lectures Tue 8:30–10 (M/E 25) and Wed 8:30–10 (M/E 21), 13 Oct – 3 Feb · tutorial Tue 10:15–11:45 (CDI 121) from 20 Oct | **Fri 12 Feb 9:00–11:00**, HG II/HS 3 · 2nd Mon 8 Mar | written, 60 min theory + 60 min programming (Python) |
| **Big Data** (Bürkner, Marx) | 9 | Lectures Tue 16–17:30 (HG II HS 6) and Thu 14:15–15:45 (Chemistry HS 2) from 13 Oct · tutorial Thu 10–11:30 (CT HS ZE 02) from 29 Oct · voluntary sheets every Wed from 21 Oct | **Wed 10 Feb 17:30–19:30**, HG II HS 1 · 2nd Tue 16 Mar | 120 min; aids/style not announced |
| **Inference** (reading course, Lamberti) | 5 | self-study · exam coaching Mon 16–18 (M/E 21) | **not out yet**; last semester's exam was 10 Sep (end of the break) → expect **March** | written, 56 min, 3 exercises, own cheat sheet |
| **Data Science in Context** | 3 | **Online (Zoom), Mon 14:00–16:00**, guest lectures from **early November** (dates TBA) | not out yet | **multiple choice**, based on the lectures |
| **German** (self-study) | – | Wed 16:45 + Fri 11:00 blocks, 15 min vocabulary daily | B1 exam (telc/Goethe) May–July 2027 | – |
| ~~Industrial Data Science 1~~ | ~~5~~ | dropped on 11 Oct (can be taken in a later semester) | – | – |

**Keep in mind:** Moodle still writes the Big Data exam as "10.02.**26**" (ask in lecture 1) · Inference is an
admission condition and must be passed before the Case Studies (MD 4) · the NLP programming half will be "fundamentally
revised" (format not announced yet).

---

## 2. Priorities and risks

| Risk | What the plan does |
|---|---|
| **Programming (Python level 1)**: half of the NLP exam | **Python bootcamp** (5 × 90 min in W1–W2), then a coding drill every week without AI |
| **Big Data maths** (calculus, linear algebra, probability) | Maths foundations every Monday, one week before each topic |
| **Inference behind + admission condition** | Catch-up in W1; it then runs one week late until Christmas, H1 absorbs it |
| **Two exams in three days** (Big Data Wed 10, NLP Fri 12 Feb) | Mocks in W13 and W15; exam-week day plan (§9); decision rule on 25 Jan |
| **Load: 26 CP + German + 12 h gym** | One fixed timetable, Sunday afternoon free, German pauses in exam weeks, minimum-week rule (§10) |

---

## 3. Your weekly timetable

Gym from home, mornings: **Mon, Fri, Sat, Sun**. Tue and Thu you are on campus all day; Wednesday morning is the NLP lecture.
Every day: **15 min German vocabulary** (tablet/phone, e.g. on the train).

**Monday** (home)
| Time | Block |
|---|---|
| 07:30–10:30 | **Gym** |
| 11:00–12:30 | **Inference A** · learn |
| 13:15–14:00 | **NLP** · pre-read this week's slides |
| 14:00–16:00 | **Data Science in Context** (Zoom, from early Nov). Until then: **FLEX** (catch-up) |
| 16:00–16:30 | DSiC: 1-page summary + 10 multiple-choice flashcards (from Nov) |
| 16:30–18:00 | **Big Data** · maths foundations |
| 18:00–18:30 | **Weekly planning** (read the week in this plan; check Moodle) |

**Tuesday** (campus, tablet)
| Time | Block |
|---|---|
| 08:30–10:00 | NLP lecture (M/E 25) |
| 10:15–11:45 | NLP tutorial (CDI 121), from 20 Oct |
| 12:30–13:15 | **NLP same-day review** |
| 13:30–15:00 | **Inference B** · learn + read |
| 15:00–15:45 | Big Data · today's slides / one derivation |
| 16:00–17:30 | Big Data lecture (HG II HS 6) |

**Wednesday**
| Time | Block |
|---|---|
| 08:30–10:00 | NLP lecture (M/E 21) |
| 10:15–11:00 | **NLP same-day review** (on campus), then home |
| 11:45–12:30 | **Big Data review** of Tuesday's lecture |
| 13:15–14:45 | Big Data sheet, part 1 (new sheet every Wednesday from 21 Oct) |
| 15:00–16:30 | NLP sheet / coding, part 1 |
| 16:45–18:15 | **German grammar 1** (the week's topic) |

**Thursday** (campus, tablet)
| Time | Block |
|---|---|
| 08:15–09:45 | **Inference C** · drill |
| 10:00–11:30 | Big Data tutorial (CT HS ZE 02), from 29 Oct. Before: Big Data maths foundations |
| 11:30–12:15 | Big Data: fix what the tutorial showed |
| 13:00–14:00 | **FLEX** (tablet): whatever is behind; otherwise the Inference error log |
| 14:15–15:45 | Big Data lecture (Chemistry HS 2) |
| 16:00–16:45 | **Big Data same-day review** |

**Friday** (home)
| Time | Block |
|---|---|
| 07:30–10:30 | **Gym** |
| 11:00–12:30 | **German grammar 2** (practice, writing, listening) |
| 13:15–14:45 | NLP sheet / coding, part 2 |
| 15:00–16:30 | Big Data sheet, part 2 |
| 16:45–17:30 | **Inference D** · weekly test (timer, paper) |

**Saturday**
| Time | Block |
|---|---|
| 08:00–11:00 | **Gym** |
| 11:30–12:30 | **Inference E** · recap and repair |
| 13:30–15:00 | **Weekly quizzes**, closed book: NLP 40 min + Big Data 40 min + German 10 min |
| 15:15–16:45 | **Coding block:** NLP drill without AI + Python practice (Python bootcamp in W1–W2) |
| 16:45–17:15 | **Wrap-up:** say "Wrap up" in each repo you used this week |

**Sunday**
| Time | Block |
|---|---|
| 08:00–11:00 | **Gym** |
| rest of the day | **free** · only if you are behind: FLEX 17:00–18:30 |

| Hours per week | In class | Self-study | Total |
|---|---|---|---|
| NLP | 4.5 | ~8.5 | ~13 |
| Big Data | 4.5 | ~8.5 | ~13 |
| Inference | – | ~6.5 | ~6.5 |
| Data Science in Context (from Nov) | 2 | ~0.5 | ~2.5 |
| German | – | ~4.5 | ~4.5 |
| Planning, FLEX | – | ~2 | ~2 |
| **Study total** | **~11** | **~30** | **~41** |
| **Gym** | | | **12** |

**Rules:** (1) **Same-day reviews** are the most important blocks: never skip them. (2) A missed block goes to the next
**FLEX** (Thursday 13:00; Monday 14:00 until DSiC starts; Sunday 17:00 only if needed). (3) A lost gym morning moves
to the next free morning, not to the evening. (4) Sleep 7–8 hours; no study after 19:00.

**Before all classes run:**
| Slot | W1 (12–18 Oct) | W2 (19–25 Oct) | W3 (26 Oct–1 Nov) | from W4 |
|---|---|---|---|---|
| Mon 14:00–16:00 | FLEX: Inference 1C | FLEX: Python bootcamp 4 | FLEX: Inference Gate 1 | DSiC Zoom (once it starts) |
| Tue 10:15–11:45 | Inference 1D test + 1E | NLP tutorial | NLP tutorial | NLP tutorial |
| Thu 10:00–11:30 | Big Data F03 | Big Data F05 | Big Data tutorial | Big Data tutorial |
| Wed 13:15 / Fri 15:00 (BD sheet) | Big Data L1 + F03 start / Inference 2C | sheet 1 | sheet 2 | sheets |
| Wed 15:00 / Fri 13:15 (NLP sheet) | Python bootcamp 1 / 2 | NLP sheet | NLP sheet | NLP sheet |

---

## 4. The semester calendar

**Inference runs one week behind its own plan until Christmas**; holiday week H1 absorbs the shift, and from W11 (4 Jan)
it is back on its original dates.

| Week | Dates | Inference | NLP | Big Data | German | DSiC · checks |
|---|---|---|---|---|---|---|
| **W1** | 12–18 Oct | **catch-up:** 1B part 2 → 2E (derivatives, distributions, E/Var) | L1–L2: intro, data, regex · Python bootcamp 1–3 | L1–L2: intro to ML · F01 check, F03 | level check + G01 sentence structure | Tue 13: first lectures · quizzes start Sat 17 |
| **W2** | 19–25 Oct | max/min, normal tables, CLT | L3–L4: preprocessing, POS, NER · tutorial from Tue 20 · bootcamp 4–5 | L3–L4: big data in R/Python · sheet 1 Wed 21 · F04, F05 | G02 present tense | Plan review #1 (Mon 19) |
| **W3** | 26 Oct–1 Nov | **Gate 1 (Mon 26)** · ch. 1 + bias | L5–L6: tf-idf, Zipf, n-gram LMs, perplexity, PMI | L5–L6: supervised · tutorial from Thu 29 · F06 | G03 Nominativ, Akkusativ | DSiC pre-reading (optional) |
| **W4** | 2–8 Nov | MSE, BLUE | L7–L8: metrics, Naive Bayes, feature selection | L7–L8: supervised → optimisation | G04 Dativ | **DSiC starts (early Nov)** · NLP Checkpoint 1 (Sat 7) · Thu 5 Nov: Claude cloud credit ends |
| **W5** | 9–15 Nov | consistency · Self-test 1 · **Gate 2** (Fri 13) | L9–L10: clustering, SVD/LSA, pLSA, LDA | L9–L10: optimisation · F07 eigenvalues | G05 prepositions | BD Checkpoint 1 (Sat 14) · Plan review #2 (Mon 9) |
| **W6** | 16–22 Nov | MLE (regular cases) | L11–L12: topic-model evaluation, STM; neural nets | L11–L12: unsupervised · F08 SVD/PCA | G06 Perfekt | – |
| **W7** | 23–29 Nov | non-regular MLE, method of moments · Self-test 2 | L13–L14: word2vec, GloVe, fastText, benchmarking | L13–L14: unsupervised → information theory · F09 | G07 Präteritum, modal verbs | NLP Checkpoint 2 (Sat 28) |
| **W8** | 30 Nov–6 Dec | estimation at speed · **Gate 3** (Fri 4) | L15–L16: RNN, LSTM, attention | L15–L16: information theory → regularisation · F10 | G08 adjective endings I | BD Checkpoint 2 (Sat 5) · Plan review #3 (Mon 30 Nov) |
| **W9** | 7–13 Dec | Z-test, errors, interpretation | L17–L18: transformer | L17–L18: regularisation → Bayesian · F11 | G09 adjective endings II | – |
| **W10** | 14–20 Dec | p-value, power, binomial test | L19–L20: transformer by hand; BERT | L19–L20: Bayesian inference · F12 | G10 A2 review test | NLP Checkpoint 3 (Sat 19) |
| **H1** | 21–27 Dec | **asymptotic tests · Self-test 3 · mid-semester mock** (~6 h) | L21 Tue 22 Dec; consolidation | consolidation | vocabulary + 1 review | 4 gym mornings, rest otherwise |
| **H2** | 28 Dec–3 Jan | light; cheat sheet v2 | cumulative test (Sat 2 Jan) | cumulative test (Sat 2 Jan) | vocabulary + 1 review | rest days around New Year |
| **W11** | 4–10 Jan | CIs, test ↔ CI duality · Self-test 4 · **Gate 5** (back on plan dates) | L22 Wed 6 Jan: LLMs, Adam, dropout | L21–L22: Bayesian → deep learning · F13 | G11 subordinate clauses | Plan review #4 (Mon 4) |
| **W12** | 11–17 Jan | LR and UMP tests · **Gate 6** | L23–L24: fine-tuning, annotation, few/zero-shot, PET, SetFit | L23–L24: deep learning · F14 | G12 relative clauses | – |
| **W13** | 18–24 Jan | χ², t, F; one-sample t-test | L25–L26: PEFT, LoRA, quantization | L25–L26: self-supervised · F15 | G13 reflexive verbs, verbs + prepositions | **BD Mock 1 (Fri 22, 13:15)** · **NLP Mock 1 (Sat 23, 13:30)** |
| **W14** | 25–31 Jan | variance and two-sample tests | L27–L28: AdaSent, PETapter, DPO, evaluation | L27–L28: kernels, Gaussian processes | G14 zu-infinitive | **Exam-date decision Mon 25 (§9)** · Plan review #5 |
| **W15** | 1–7 Feb | light: "which test when", Self-test 5 | last lecture Wed 3 · **Mock 2 Wed 3, 13:15** | last lectures · **Mock 2 Sat 6, 13:30** | pause (vocabulary only) | – |
| **W16** | 8–14 Feb | maintenance only | **EXAM Fri 12, 9:00** | **EXAM Wed 10, 17:30** | pause | exam week (§9) |
| **W17** | 15–21 Feb | **Mock B** (Mon 15) · **official example exam** (Thu 18) | exam view Wed 17 | – | G15 Konjunktiv II · book the B1 exam | Inference full-time |
| **W18** | 22–28 Feb | Mocks D and E · coaching | – | – | G16 passive | – |
| **W19** | 1–7 Mar | short mock · **exam (expected March)** | – | – | G17 time connectors | – |
| **W20** | 8–14 Mar | – | 2nd date Mon 8 Mar (if needed) | – | G18 Genitiv | – |
| **W21** | 15–21 Mar | – | – | 2nd date Tue 16 Mar (if needed) | G19 connectors | – |

NLP and Big Data lecture topics are forecasts; each course plan says how to shift them when the real lectures differ.

---

## 5. The next two weeks, day by day

**The plan starts Mon 12 Oct.** Install in Monday's planning slot (18:00–18:45):
`pip install pandas scikit-learn nltk spacy gensim jupyter`.

### W1 · 12–18 Oct · first lectures + catch-up

| Day | Time | Block | Say / do |
|---|---|---|---|
| **Mon 12** | 07:30–10:30 | Gym | |
| | 11:00–12:30 | **Inference 1B part 2:** derivatives, chain rule, maximum, Q4 | Inference repo → "Let's continue" |
| | 13:15–14:00 | NLP: skim slides 1–43 (intro, data, regex) | `NLP/materials/last_year.pdf` |
| | 14:00–15:30 | **Inference 1C:** discrete distributions (FLEX) | "Let's continue" |
| | 16:30–18:00 | Big Data: F01 check (30 min) + ISLP ch. 2 (60 min) | BigData repo → "Foundations F01" |
| | 18:00–18:45 | Weekly planning + install the Python packages | |
| **Tue 13** | 08:30–10:00 | **NLP lecture 1** · ask the exam questions (NLP plan §8) | |
| | 10:15–11:45 | **Inference 1D test** (30 min) + 1E recap (45 min) | tablet |
| | 12:30–13:15 | NLP same-day review L1 | NLP repo → "Lecture review L1" |
| | 13:30–15:00 | **Inference 2A:** densities, integrals | |
| | 15:00–15:45 | Big Data: skim today's slides if online | |
| | 16:00–17:30 | **Big Data lecture 1** · ask: exam year/date, format, aids | |
| **Wed 14** | 08:30–10:00 | **NLP lecture 2** | |
| | 10:15–11:00 | NLP same-day review L2 (on campus) | "Lecture review L2" |
| | 11:45–12:30 | Big Data review L1 | "Lecture review L1" |
| | 13:15–14:45 | Big Data: re-derive L1 + start F03 | |
| | 15:00–16:30 | **Python bootcamp 1:** values, types, strings, print | NLP repo → "Python bootcamp 1" |
| | 16:45–18:15 | **German: level check** + G01 | German repo → "German: let's continue" |
| **Thu 15** | 08:15–09:45 | **Inference 2B:** Uniform, Exponential, Normal | |
| | 10:00–11:30 | **Big Data F03:** linear regression in matrix form | "Foundations F03" |
| | 11:30–12:15 | Big Data: F03 exercises | |
| | 13:00–14:00 | FLEX (tablet): Inference error log (Σ c = N·c, finishing proofs) | |
| | 14:15–15:45 | **Big Data lecture 2** | |
| | 16:00–16:45 | Big Data same-day review L2 | |
| **Fri 16** | 07:30–10:30 | Gym | |
| | 11:00–12:30 | **German practice** (G01) | "German practice" |
| | 13:15–14:45 | **Python bootcamp 2:** lists, loops, conditions | |
| | 15:00–16:30 | **Inference 2C:** E/Var of sums, X̄, partial derivatives | |
| | 16:45–17:15 | **Inference 2D test** (30 min) | |
| **Sat 17** | 08:00–11:00 | Gym | |
| | 11:30–12:30 | **Inference 2E** recap + error log | |
| | 13:30–15:00 | **Quiz 1:** NLP (T01–T03) + Big Data (intro ML, F01–F02) + German | "Weekly quiz" in each repo |
| | 15:15–16:45 | **Python bootcamp 3:** dictionaries, Counter, functions | |
| | 16:45–17:15 | Wrap-up | |
| **Sun 18** | 08:00–11:00 | Gym · then free | |

After W1: Inference's two catch-up topic weeks are done; it is exactly one week behind its plan (absorbed in H1).

### W2 · 19–25 Oct · everything runs except the Big Data tutorial

| Day | Time | Block |
|---|---|---|
| **Mon 19** | 07:30–10:30 | Gym |
| | 11:00–12:30 | **Inference A:** distribution of max/min of a sample |
| | 13:15–14:00 | NLP pre-read slides 44–73 |
| | 14:00–15:30 | **Python bootcamp 4:** files, string methods, list comprehensions (FLEX) |
| | 16:30–18:00 | **Big Data F04:** gradients |
| | 18:00–18:30 | **Plan review #1** + weekly planning |
| **Tue 20** | 08:30–11:45 | NLP lecture 3 + **first NLP tutorial** |
| | 12:30–13:15 | NLP review L3 |
| | 13:30–15:00 | **Inference B:** normal distribution, all tables |
| | 15:00–17:30 | Big Data pre-read + lecture 3 |
| **Wed 21** | 08:30–11:00 | NLP lecture 4 + review L4 |
| | 11:45–12:30 | Big Data review L3 |
| | 13:15–14:45 | **Big Data sheet 1**, part 1 (out today) |
| | 15:00–16:30 | NLP sheet / coding, part 1 |
| | 16:45–18:15 | **German G02:** present tense, separable verbs |
| **Thu 22** | 08:15–09:45 | **Inference C:** CLT + drill |
| | 10:00–11:30 | **Big Data F05:** logistic model, cross-entropy |
| | 11:30–12:15 | Big Data: re-derive L3 |
| | 13:00–14:00 | FLEX (tablet) |
| | 14:15–16:45 | Big Data lecture 4 + review |
| **Fri 23** | 07:30–10:30 | Gym |
| | 11:00–12:30 | German practice (G02) |
| | 13:15–14:45 | NLP sheet, part 2 |
| | 15:00–16:30 | Big Data sheet 1, part 2 |
| | 16:45–17:30 | **Inference D:** weekly test |
| **Sat 24** | 08:00–11:00 | Gym |
| | 11:30–12:30 | Inference E: recap |
| | 13:30–15:00 | **Quiz 2:** NLP + Big Data + German |
| | 15:15–16:45 | **Python bootcamp 5:** `re` basics + a small text task |
| **Sun 25** | 08:00–11:00 | Gym · then free |

From W3 on, every day follows the timetable in §3 with the week's topics from §4. The overview page shows any date.

**Admin (Monday planning blocks of W1–W2):**
- [ ] BOSS: exam registration and **de**registration deadlines (Big Data, NLP, Inference, DSiC) → phone calendar.
      Don't register for Industrial Data Science 1.
- [ ] Exam regulations: attempts per exam; can a passed exam be improved?
- [ ] Student council Discord: old exams / memory notes for NLP, Big Data, Inference.
- [ ] German: choose a grammar book; set up a vocabulary app; check the TU language centre for a DaF course on Friday mornings.
- [ ] Watch Moodle: Inference exam date; DSiC first lecture date.

---

## 6. Foundations track (maths and programming, just in time)

| Week | Maths (Inference toolkit + Big Data foundations) | Programming |
|---|---|---|
| W1 | Inference catch-up: derivatives, distributions, E/Var · F01 check, F03 | **Python bootcamp 1–3** |
| W2 | Inference: max/min, normal, CLT · F04 gradients, F05 logistic model | **Python bootcamp 4–5** (incl. regex basics) |
| W3 | F06 convexity, Taylor, gradient descent | P03 preprocessing, P04 numpy/pandas |
| W4 | (F06 practice) | bigram LM, Naive Bayes from scratch |
| W5 | F07 **eigenvalues**, PSD, covariance | P05 scikit-learn pipeline |
| W6 | F08 **SVD**, PCA, multivariate normal | P06 gensim LDA |
| W7 | F09 entropy, KL, mutual information | P06 Word2Vec |
| W8 | F10 norms, ridge, lasso | P07 attention in numpy |
| W9 | F11 posterior, conjugacy, Monte Carlo | P07 self-attention from scratch |
| W10 | F12 backpropagation | P07 masks, P08 debugging |
| W11 | F13 variational inference (ELBO) | P07 Hugging Face |
| W12 | F14 kernels, Gaussian conditioning | P07 fine-tuning workflow |
| W13–W14 | F15 kernel ridge, GP posterior | LoRA counts, quantization; P08 timed tasks |

---

## 7. Learn once, use in several courses

| Idea | Inference | NLP | Big Data |
|---|---|---|---|
| Maximum likelihood, log-likelihood | W6–W8 (core) | n-gram, Naive Bayes estimates (W3–W4) | logistic regression, mixtures/EM |
| Bias, variance, MSE | W3–W5 | – | bias–variance, regularisation |
| Derivatives, chain rule, gradients | W1 | neural nets, word2vec | optimisation, backprop |
| Bayes' theorem | – | Naive Bayes (W4) | Bayesian inference (W9–W11) |
| Entropy, mutual information, KL, χ² | χ² tests (W13–W14) | feature selection (W4), DPO | information theory (W7–W8) |
| Clustering, PCA/SVD | – | clustering, LSA (W5) | unsupervised learning (W6–W7) |
| Precision, recall, errors | type I/II errors (W9) | classifier evaluation (W4) | model evaluation |
| Gradient descent, Adam, dropout | – | W11 | W4–W5, W12 |
| Masked modelling, contrastive learning | – | BERT (W10) | self-supervised learning (W13) |

---

## 8. How you study

- **Test yourself instead of re-reading** (retrieval practice and spacing have the strongest research support:
  Dunlosky et al., 2013). That's why every week ends with closed-book quizzes and old mistakes come back.
- **Same-day review** beats a long weekend session.
- **Write by hand** for theory; **type the code yourself** for programming (no AI while drilling).
- **Gym helps learning**: better sleep and focus. Keep it in exam weeks too.
- **One Claude session per study block** in that course's repo: start with **"Let's continue"** (or the session name
  in §5), end with **"Wrap up"**. Ask any repo "What's my plan today?".
- **After every lecture**, put the slides into that course's `materials/` and push (GitHub "Add files via upload" works on the tablet).

---

## 9. The exam period

**Default: write both first dates:** Big Data Wed 10 Feb (17:30), NLP Fri 12 Feb (9:00), then Inference in March.
A first date is an extra chance; the second dates (NLP 8 Mar, Big Data 16 Mar) are the repair. If you skip a first date
and fail the second, there is no other attempt this semester, and both courses run once a year.

| Day | Plan |
|---|---|
| Wed 3 Feb | 13:15–15:15 **NLP Mock 2** |
| Sat 6 Feb | Gym · 13:30–15:30 **Big Data Mock 2** |
| Sun 7 Feb | Gym · rest |
| Mon 8 Feb | Gym · 11:00–17:00 Big Data review (derivation list, error log, one timed set) |
| Tue 9 Feb | 09:00–15:00 Big Data final review · early to bed |
| **Wed 10 Feb** | light Big Data review in the morning · **Big Data exam 17:30–19:30** |
| Thu 11 Feb | 09:00–16:00 NLP review (error log, formula summary, two short timed sets) · early to bed |
| **Fri 12 Feb** | **NLP exam 9:00–11:00** · rest |
| Sat 13 – Sun 14 | Gym · rest. From Mon 15 Feb: Inference full-time, German restarts |

**Decision rule (Mon 25 Jan, after BD Mock 1 and NLP Mock 1):** both ≥ 60% → keep both first dates. One < 60% → move
that course to its second date (deregister in BOSS before the deadline). Assumes at least three attempts per exam:
check the exam regulations.

---

## 10. Plan reviews, red flags, and the minimum week

**Plan reviews** (Monday planning block): W2 (19 Oct) · W5 (9 Nov) · W8 (30 Nov) · W11 (4 Jan) · W14 (25 Jan, with the
exam decision) · W17 (15 Feb).

| Signal | What happens |
|---|---|
| A weekly test < 60% in any course | That course's next block becomes a repair session |
| One course red two weeks in a row, another ≥ 85% | Move 1.5 h/week from the green course to the red one for 3 weeks |
| Blocks missed | They go to the next FLEX; if FLEX is full, use that course's cut list (German's Friday block can be FLEX once a month) |
| Less than 30 study hours two weeks in a row | Plan review: what is blocking? |
| Ill, overloaded, or sleeping < 7 h most nights | **Minimum week** for one week |

**Minimum week (~22 h study):** all lectures and tutorials · all same-day reviews · Inference A and D · one sheet per
course · Saturday quizzes · German Wednesday block only · **3 gym mornings**.

---

## 11. Open questions

1. **Inference exam date** → watch Moodle (expected March).
2. **Big Data:** exam year, format, aids → lecture 1 (Tue 13 Oct).
3. **NLP:** aids, sheets/bonus, format of the new programming half → lecture 1 / tutorial 1.
4. **DSiC:** lecture dates, speakers, MC exam date → Moodle.
5. **Exam regulations:** attempts per exam; grade improvement?

---

## 12. Where everything is

| Folder (GitHub repo) | Main files |
|---|---|
| `NLP/` (sorsicd7/NLP) | `syllabus.md` (T01–T29, P01–P08) · `semester-plan.md` · `progress.md` |
| `BigData/` (sorsicd7/BigData) | `syllabus.md` (T01–T12, F01–F15) · `semester-plan.md` · `progress.md` |
| `Inference/` (sorsicd7/Inference) | `semester-plan.md` (gates, mocks) · `syllabus.md` · `progress.md` |
| `DataScienceInContext/` (sorsicd7/DataScienceInContext) | `syllabus.md` · `semester-plan.md` · `progress.md` |
| `German/` (sorsicd7/German, **to be created on github.com**) | `syllabus.md` (G00–G20) · `semester-plan.md` · `progress.md` |
| `IndustrialDataScience/` (sorsicd7/IndustrialDataScience) | dropped on 11 Oct; kept as an archive for a later semester |
| this folder | `MASTER-PLAN.md` (this file). Every repo has a synced copy `master-plan.md`; after changing this file run `python sync-master-plan.py`. Course sessions log changes under "Cross-course notes"; say "update the master plan" on the laptop to fold them in. Online: **[semester overview page](https://claude.ai/artifact/HWvuvfoN3XtLec2nHMRTa5)** |
