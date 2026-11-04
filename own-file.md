# A teacher's own file, made ready for Maktab

A teacher has his own Word file: lecture notes, worked solutions, or a booklet of past-paper questions,
in his own layout. **Give him back the same file, with its form changed so Maktab can read it, and never
his words.** Maktab then brings it into his class: each part to its sub-topic and place, his boxes as
boxes, his questions as questions.

This is not the topic file. He keeps his own file and sends it again whenever he changes it; you change
only its form. ([bulk-import.md](bulk-import.md) is the other job: a folder of material put into a
Maktab topic file.)

Read [provenance.md](provenance.md) first. **Here it asks less**: his file is his, so remove nothing from it
for where it came from; list in your note anything that looks copied (a page of a book, another
teacher's notes, a paper of another course).

## What you need

1. **His file**, as a Word file (.docx). A PDF is read less well: ask him for the Word file it was made
   from. If there is none, make a Word file from the PDF, and check against the PDF what a conversion gets wrong:
   equations, subscripts and superscripts, tables, and any page that is a scan, read off a picture. List each part
   you rebuilt under `Changes made by AI` at the end of the copy (below), not in your note.
2. **The topic's export from Maktab**, if he gave you one (*Export or import* on the class materials
   page). Its Heading 1 lines are the sub-topics, `3.1 Momentum and Newton's laws of motion`, and its
   Heading 3 lines under *Text* the learning outcomes, `3.1.3 Momentum is mass times velocity`. **Take
   every sub-topic number and outcome code from it.**
3. **With no export, the course's skeleton**: [subjects/](subjects/) has a page for every course Maktab
   holds, `subjects/9702.md`, with each topic, each sub-topic's number and name and each outcome's code, as
   Maktab holds them, and the same list as an empty Word file in this shape, `subjects/9702 skeleton.docx`.
   Take every sub-topic number and outcome code from it. A Cambridge course's page lists each outcome by its
   code only; its wording is in the export and in the syllabus the page links to.

[sample-lecture.docx](sample-lecture.docx) is a short file in the shape below. Open it and copy its
shapes.

## Never change

- **His words**: spelling, wording, order. Correct nothing. If something looks wrong, leave it, mark it as
  below (*Point out what could mislead a student*) and say so in your note.
- **His pictures, tables of data, equations and symbols.** A subscript or superscript he set stays set.
- **His answers and marks.**
- **His teaching, and every heading over it: never delete them.** A part only paper needs is marked, never deleted
  (below).
- **All of his file, every time he sends it again.** Maktab takes his newer file as the new version of what his last
  file of the same name brought in: a part he changed is changed in his class, and a part missing from your copy is taken out of it.
  What he changed on Maktab's page himself stays as he left it.
- **His file's name.** Give your copy the name of the file he gave you: Maktab takes it as the newer version only
  of the file he sent before under that name. A file of another name only adds to what his class has, so two files
  for one sub-topic keep both.

## The shape

```
3 Dynamics                                         Title: the topic's number and name
Introduction                                       Heading 1: what comes before the first sub-topic
  …his introduction, chapter at a glance…
3.1 Momentum and Newton's laws of motion           Heading 1: the sub-topic, as Maktab names it
  Start here                                       Heading 2: what comes before its first part, if any
  Mass and inertia                                 Heading 2: each part, his own title, no number
    paragraphs, lists, boxes, pictures
    Check your understanding · 3.1.3               a box: one short question, its outcome, its answer
  Wrap up                                          Heading 2: its summary and key points, if any
  Past-paper questions                             Heading 2
3.2 Non-uniform motion                             Heading 1
  …
Summary                                            Heading 1: what comes after the last sub-topic
```

### Headings

1. **Every heading is a real Word heading** (Home › Styles): the topic Title, each sub-topic Heading 1,
   each of his sections Heading 2, a smaller heading inside one Heading 3. **Never a table, a shaded
   band or bold text.** A heading set as a table (`01 | Mass, inertia… | 3.1`) becomes a heading:
   `Mass, inertia, and Newton's second law`. The table's other lines (`3.1 – F = ma …`) stay, as a
   paragraph just under the new heading.
2. **Each sub-topic is a Heading 1 that is exactly the Cambridge sub-topic's number and title**, as the
   export or the course's skeleton writes it: `3.1 Momentum and Newton's laws of motion`, never his own
   words after the number. Use only sub-topics the export or the skeleton has. A section that teaches two
   goes under the one it teaches most.
3. **His own titles are his sections' Heading 2, with no number**: `Mass, inertia, and Newton's second
   law`, `Section A: Multiple choice solutions`, under the Heading 1 they teach. This is the shape to make.
   **His own numbering** that is not a sub-topic's comes off: `3. Client–Server Model` becomes
   `Client–Server Model` under `2.1 Networks including the internet`, since Maktab reads a number at the
   start of a heading as a Cambridge sub-topic.
4. **A file that already numbers his sections by their sub-topic also comes in**, once it has the exact
   Heading 1 above them: under `3.1 Momentum and Newton's laws of motion`, his Heading 2s `3.1 Mass,
   inertia, and Newton's second law` and `3.1 Weight and the acceleration of free fall` are sections of
   3.1, his words their headings, in his order. When his file has this shape, add only the missing
   Heading 1s and leave his numbered Heading 2s as they are. **A file with no heading that is a
   sub-topic's number and title exactly is checked heading by heading**: there `3.1 Mass, inertia, and
   Newton's second law` is read as another subject's 3.1 and left out.
5. **What sits before the first sub-topic** (his introduction, *Chapter at a glance*) goes under a Heading 1
   *Introduction*, when there is any besides his front matter (below); **what sits after the last** (his summary, glossary,
   key terms) under a Heading 1 *Summary*. Maktab puts them on the topic's own first and last pages.
6. **If you cannot tell which sub-topic a section teaches, do not guess.** Leave its heading as it is
   and list it in your note.
7. **Every part of a sub-topic has a real title**: each Heading 2 says in 3 to 8 words what its part teaches,
   *Testing for reducing sugars*, never *Part A* or *Section 2*. Students see one part at a time, and its title is
   all they see of where they are. **Where his heading already says it, it is the title**, word for word. Where it
   does not, write one and end it with `[check: title written by AI; his heading was "Part A"]`, so his words are
   kept and he sees what you wrote; list it in your note.

### Start here and Wrap up

**A sub-topic opens with a Heading 2 *Start here* and closes with a Heading 2 *Wrap up*, when he has them.** Put what
comes before its first part (what the sub-topic is about, what to know first) under *Start here*, and his summary,
key points or *now you can…* under *Wrap up*, his words as he wrote them. Leave out either he has nothing for. Name
them exactly *Start here* and *Wrap up*: students read each sub-topic one part at a time, and Maktab shows these two
as its first and last screens. They are the sub-topic's own: the topic's *Introduction* and *Summary* (above) stay the
whole topic's, at its start and end.

**Common mistakes come only from his misconception boxes** (his *Common mistake*, `⚠ COMMON MISCONCEPTION`). A
*Common mistake* box under *Wrap up* copies one of them word for word, and you write none yourself. His *Examiner's
advice* and *Top tip* boxes are tips, never common mistakes, even when they name a mistake: they often hold the
right answer (*Insoluble, so it does not affect water potential.*), and a student reading it as a common mistake
learns that it is wrong.

### Boxes

A box is a table of **one row and one cell**, or of **one column and two rows**: a label row over a body
row, as his boxes may be (`COMMON MISTAKE` in the top row, his words in the one under it). **Its first line
is its label**, alone or followed by its title after a middle dot (`·`):

```
Definition · Momentum
The momentum of a body is the product of its mass and its velocity.
```

The labels Maktab has: **Key idea, Definition, Derivation, Top tip, Examiner's advice, Common mistake,
Real-world link, Think about it, Memory trick, Practical skills link, Syllabus link, Teacher's note**,
and **Worked example**; and **Check your understanding**, for a short question (below). A box of his that
is none of these starts **`Box · `** and his own title, so it stays a box with his title:
`Box · GRAPH CHECK`; a box with no title starts with `Box` alone.

- His own style of label is read: `✎ DEFINITION – learn it word for word · Electronegativity` is a
  Definition, `⚠ COMMON MISCONCEPTION` a Common mistake, `☰ TEACHER'S CORNER` a Teacher's note, and
  `WORKED EXAMPLE - A ROCKET IN FLIGHT` a worked example titled *A rocket in flight*: his title after a
  dash is read as after a middle dot. **Keep such a label line exactly as he wrote it**: never move his words
  from the label into the title or from the title into the label. `✎ DEFINITION – learn it word for word ·
  Metallic bonding` stays that line; `Definition · learn it word for word` over a title `Metallic bonding` makes
  his instruction a label and his title a line of its own.
- **A small icon picture on a label line** is his label's mark: leave it; Maktab shows its own.
- **A two-row table whose top row names no label** (a formula over its key, `F = ma` over `F = resultant force
  / N …`; a law over its note) **gets Maktab's label**: a key equation `Key idea · F = ma`, a law or definition
  `Definition · Newton's first law` (M-455). An empty one is a work space: leave it.
- **A label that means one of Maktab's but uses other words** (`GAP FILLED – WHERE DOES THIS LAW COME
  FROM?`, which is a derivation) **is not read**: put Maktab's label first and keep his words as the
  title, `Derivation · GAP FILLED – WHERE DOES THIS LAW COME FROM?`. When you cannot tell which label
  fits, use `Box · ` and his words: Maktab asks him to check its type.
- **A box with no label line**, which Maktab types by its shading alone, and a `Box · ` box with his title, each
  come in as a *Please check* for him to confirm its type. A box you labelled comes in with none.
- **An *Examiner's advice* or *Top tip* box keeps its label**: never make it a *Common mistake*, even when it warns
  of one, since it often gives the right answer.
- A *Teacher's note* is for teachers; students never see it.
- Leave an empty paragraph after each box, so two boxes stay two.

### Worked examples

A worked example is a box whose first line is **`Worked example`**, and its title after a middle dot:

```
Worked example · A rocket in flight
Paper: 9702/12/M/J/21 Q5                 only when it is a past-paper question; its reference
A rocket of mass …                       the problem, as he wrote it
Step 1 …                                 his working, in his order, one step to a line
```

A worked example he set as a table of several rows may stay: Maktab reads it, a label row over the problem
included (`WORKED EXAMPLE - A ROCKET IN FLIGHT` over its words). Pictures inside it come in with it, his
label row's icon aside. **A picture on a line of its own just after the box** is the example's picture.
**His solution may follow the box**, as he wrote it: a *SOLUTION* line, then his steps, each starting with
its number (`1.`, `2.`), a run-on line indented under its step. Maktab reads them as the example's working,
each a step, up to the next box, table, heading or line that is not a step. Leave it where it is.

**His work spaces** (*Work it out here:* and an empty table under it, for a printed copy) and his
*SOLUTION* label stay as they are; Maktab leaves them out, and its report says how many. **A picture
inside a work space, or inside any table that is not a box, does not come in**: when it belongs to the
solution, move it to a line of its own just after the box.

### Lists, pictures, tables

- **A bulleted list is a Word bulleted list** (Home › Bullets), never typed dashes or `•` at the start of
  a paragraph.
- **A numbered list keeps its numbers as he has them** (`1.`, `(a)`, `iv.`, `Step 1`), typed or Word's own
  numbering: leave them as they are. Maktab brings both in, and draws a line that starts with its number as
  a numbered list.
- **A list may have levels**: a point under a point is Word's next list level (Tab in Word), up to three
  levels; Maktab draws each level indented under the point above it. Leave his levels as they are; a deeper
  one comes in at the third level.
- **A line that introduces the points under it ends with a colon** (`Advantages:`), and may be a bullet at
  the first level with its points a level down: Maktab reads such a bullet as a plain line, its points as the
  list under it. A bullet a level down that ends with a colon stays a bullet, its points under it, and a
  numbered point with points under it keeps its number.
- **A picture is pasted as a picture** (PNG or JPEG), on a line of its own, its caption the line just
  under it, starting with its name and number: `Diagram 2.1  A mass spectrum shows each isotope and its
  abundance.` (*Figure*, *Fig.*, *Diagram*, *Graph*, *Chart*, *Photo* or *Picture*). Maktab brings the
  picture in as a figure where it stands, that line its caption; a line under it that starts any other way
  stays his text. A chart, a drawing made of shapes, or a linked picture does not come in: paste a picture of it.
- **Save every old Word drawing (EMF or WMF) as a PNG picture**, where it stands, its size and caption kept: no
  browser shows an EMF or WMF. In the file they are the pictures under `word/media/` ending `.emf` or `.wmf`; an
  older Word file often holds most of its diagrams so, a chemistry booklet above all. Maktab converts any that still
  arrive, so a missed one still comes in.
- **A table of data stays a table**, as he set it.
- **On a phone, Maktab draws a wide table whose rows each describe one thing in words as a card per row** (the row's
  first cell its title, each other cell under its column's header); every other wide table scrolls sideways. Maktab
  decides this from the cells, so leave tables unmarked. Only where a table of words must be read across, its rows
  compared column by column, put the line `[keep as table]` on its own just above the table (under its heading, if
  it has one): Maktab then keeps it a table that scrolls on a phone, and the line is never shown to students.

### Short questions: Check your understanding, self-assessment

**Each short question is a box of its own**, under its sub-topic: its first line `Check your
understanding`, a middle dot and **the learning outcome it tests**; then the question; then its answer
on a line of its own starting `Answer:`.

```
Check your understanding · 3.1.3
A 0.50 kg ball moves at 8.0 m s⁻¹. What is its momentum?
Answer: 4.0 kg m s⁻¹
```

- **Every short question names the outcome it tests.** A question with its outcome goes to the sub-topic's
  *Quick check*, filed under that outcome; one with none goes to *Practise*, filed under no outcome until
  *Clean up with AI* gives it one. The outcome may instead be a line of its own in the box, `Learning
  outcome 3.1.3`.
- **The outcome is one of the sub-topic the question sits in**: a question under `3.3` names a `3.3.…` code,
  never one of `3.2`, even when it tests something taught there. Maktab files a code of another sub-topic under
  no outcome, and the question goes to *Practise*.
- **The code alone is enough.** Take it from the sub-topic's own list, in the export (its Heading 3 lines) or
  on the course's page in [subjects/](subjects/), which lists each code without its wording. Where you have no
  wording, choose the code by the sub-topic's name, the section the question sits in and the syllabus the page
  links to; if you still cannot tell, name the sub-topic's code you think likeliest. **Your choice stands**: do
  not mark it and do not list it in your note. Never leave the outcome off for want of its wording.
- His worked solution may follow the box, as he wrote it (*Work it out here:*, his empty table, *SOLUTION*,
  then his numbered steps): Maktab leaves out the work space and reads the steps as its working; its
  `Answer:` line is the answer, else its last step.
- **Numbered self-assessment questions** (`SAQ 2.4 …`) in one box, with their answers in a table at the
  end of the file whose rows start with the same `SAQ 2.4`, may stay as he wrote them: Maktab reads them.
  Each follows the same rule: give its outcome after its number and a middle dot, `SAQ 2.4 · 2.2.1 Define the
  term polysaccharide.`, and it goes to the *Quick check*; with none, to *Practise*.
- **Every question needs its answer.** Where he gave none, write the one you think right on a line starting
  **`Suggested answer:`** in place of `Answer:`. Never leave it empty, and never write your own answer as `Answer:`,
  as if it were his. **Never write a placeholder**, an answer that is only words in brackets (`[see note]`, `[not
  provided]`, `[answer not provided in source file]`): Maktab reads it as no answer. Where you cannot work the answer
  out, leave the `Answer:` and `Suggested answer:` lines out entirely; Maktab then says the question has no answer. Maktab keeps it apart from his answer; until he gives the answer, students are not asked the
  question.

  ```
  Check your understanding · 3.1.3
  A 0.50 kg ball moves at 8.0 m s⁻¹. What is its momentum?
  Suggested answer: 4.0 kg m s⁻¹
  ```

- **A word in an answer you cannot read** (a blurred scan, a cut-off line): write your best guess and put `[?]`
  straight after it, `Answer: the enzyme is denatured [?]`, and list it in your note. Maktab does not mark students
  against that answer until he checks the word.
- A past-paper question is not a short question: never write its mark scheme yourself (below).

### Past-paper questions

1. **Each question starts with its paper reference, and its marks**:
   `Q1(b)   9701/22/M/J/20 Q1(b)   [2 marks]`. The reference is the paper code, the series (`M/J`,
   `O/N`, `F/M`) and year, and the question number where his file gives it. **Marks are a number**: add its parts' `[2]`s
   up, once, so the heading and the words print the same total; keep every part's `[2]` in its words; never `[marks as printed]` or `[marks]`. Maktab adds them up where you do not, and Cambridge's paper settles the mark where Maktab holds it; where nothing can, it takes the words and asks the teacher to check. **Write every reference in full**,
   `9701/11/M/J/15 Q5`, a multiple-choice question's too: where he wrote a short one, `M/J-15-11` (the series, the year, the paper and its
   variant), write it out with his subject's code, the paper and variant after the code. Maktab reads a short one
   too, but only the full one says the subject.
   **Leave the question number off when his file does not give it**: under a question he numbered for his worksheet,
   `Q2.`, with only `M/J-15-11` under it, the reference is `9701/11/M/J/15`, never `9701/11/M/J/15 Q2`. His
   worksheet's number is not the paper's, and Maktab never guesses it. Such a question keeps his worksheet's number
   at its start and its paper alone on the line under it, written in full (`9701/11/M/J/15`, not at its start); a
   question you head yourself has the paper in full and no number after it, `Q1   9702/22/M/J/15   [2 marks]`. Maktab
   brings it in under its paper with no question number, when the file has its
   answer: a row of his answer key or a line after it, `Answer: B`, for a multiple-choice question; his answer sheet's
   entry of the same number, `2.`, or a `Mark scheme:` paragraph after it (or a box whose first line is `Mark scheme`),
   for a structured one. One with no answer in
   the file stays in the sub-topic's notes. **A heading whose paper cannot be read** (`9702/SP/2016`, `[series]/[year]`, no
   paper at all): find the paper in his file and write it; where his file does not say, head it `Q19   [check: paper not in
   his file]   [5 marks]`, never a guess. With its answer it comes in under *Paper unknown*.
   **A question's answers never stay in the notes**: Maktab leaves out of a sub-topic's text any mark scheme, answer sheet,
   `Answer:` line under a question or `Suggested answer:` it finds there, and warns him. An answer sheet goes under a
   heading of its own, `Answers`, never a plain line. A worked example keeps its answer, in its box.
   **Questions left as plain numbered lines with no paper under them are not read as questions**: they come into the
   sub-topic's notes, and Maktab warns him there. Give each its reference, or put a short one in a box (above).
2. **A multiple-choice question has its answer**: in the answer key, one row per question, or on a line
   after it, `Answer: B`, with his own reason where he gives one, `Answer: B (ionic bonds need two elements)`, which students
   read as his solution once they have tried it. **A question whose key has no row takes Cambridge's published key's answer** where
   Maktab holds that paper's key, shown beside it as *From Cambridge's published key*; his own key row, or his
   change to the answer on its page, replaces it. Where Maktab does not hold the paper's key, the question brings
   nothing in, and a booklet whose every key row is missing brings nothing at all. Where he gives no key, leave
   the `Answer:` line out; never write a placeholder such as `Answer: [see note]`. **Never write a `Suggested answer:` under a
   past-paper question**, a letter you worked out included: Maktab never takes it as the key and leaves it out.
3. **A structured question has its mark scheme**, after it or in his answer section, under the same
   number. **Without it, it takes Cambridge's published mark scheme** for that question and part where Maktab
   holds it, shown as *From Cambridge's mark scheme*; his own scheme, in this file or changed on its page,
   replaces it. Where Maktab does not hold it, the question comes in with no answer, an error on its sub-topic's
   page until its mark scheme is added there or in this file. Never type a scheme he did not give: where he gives
   none, leave the `Mark scheme:` line out, never a placeholder such as `[mark scheme not provided]`.
   **A case study, or any question whose parts share a passage, figure or insert**: keep each part's own header,
   `Q1(a)   9708/23/M/J/23 Q1(a)   [2 marks]` to `Q1(f) … [6 marks]`, one after another, and put the shared passage
   and figure **right after the first header**, then start the part's own words with its letter, `(a) Using the data in
   Fig. 1.1, calculate …`. Never put the passage before the first header or under a heading of its own. Maktab joins
   the parts into one question, the passage first, each part with its own answer box and marks; a file that brought
   the parts in one by one before, imported again, has the joined question take their place.
4. **Each question is in one sub-topic only**: the one it mainly tests. They go to that sub-topic's **Past
   papers tab**. If the same question (the same paper and number) is in two, keep it in one and list the other
   in your note.
5. **A picture of the printed question or of its mark scheme stays where it is, and you add its words under it**,
   for both: a
   paragraph starting **`Words:`** with what the picture says, as a student would type it (sub- and superscripts
   set as Word's, `[2 marks]` kept). Never replace the picture; a diagram, graph or table drawn in it stays the
   picture, and the words may point to it (*Figure 2.1 shows …*).
   **`Words:` holds the words**, never a note: no `[diagram for Q3]`, `[see picture above]` or *see the original PDF*. Where you
   have none, write `Words: [check: why]`.
   **Do not type a table from the picture into `Words:`**, neither as rows nor with `|` between its cells: the picture
   shows it, so write only its title, *Table 1.1*, where it stands, and go on with the words after it.
   **A multiple-choice question needs no `Words:`**: Maktab shows its pictures and leaves their words out, so a
   student never reads its statements or options twice. Keep its own lines and its options as the file types them.
   **Copy a question's words exactly as his file has them**, a slip included, and do not retype one from memory.
   Where Maktab holds that Cambridge paper it uses Cambridge's own words, so nothing depends on your copy being perfect.
   **A mark scheme's `Words:` are its words exactly as printed**: keep each `;` and `/`,
   its notes (`R`, `A`, `I`, `AW`, `ecf`, `max`), its brackets and its marks, and underline every word it
   underlines. Maktab reads them into points, so a word changed or an underline lost changes how an answer is marked.

### Lines pointing to a book or a question bank: leave them out

**Delete every line that only points to a printed book**: `Coursebook: Ryan & Norris, Chemistry Coursebook 3e, Section 4.2
Ionic bonding (p. 111)`, `Read: Coursebook Section 2.4, p. 46`, `Textbook reading: …`, `Compare: coursebook Figures 4.4 –
4.6 (pp. 112 – 113)`, and a table of every sub-topic's pages at the chapter's start. **A sub-topic's opening line that
names its syllabus page and its coursebook pages** (`Syllabus: 9701 Syllabus 2025–2027, p. 19   Coursebook: …`) **is
deleted whole**, the syllabus half too: only his heading under it comes forward. Maktab shows the class's books beside
each sub-topic and opens each at that sub-topic's page by itself, so a page number in the lesson is not needed and may not
match the copy a student holds. A sentence of his teaching that mentions the book stays. **Delete too every reference
to a question bank or a set of questions students do not have**, `(Application: 3.3 bank Q112.)`, `See bank Q40–45.`:
the line when it is only that, else just the reference, his sentence around it kept. **List what you deleted in your
note**, in one line.

### Maktab is a website, not a handout: mark what only paper needs

A student reads Maktab on a phone, page by page, with the class's book in her hand and Maktab's own pages around
his (the owner, 28 October 2026). **The copy you hand back is for Maktab**; his own file stays as it is.

**You mark; Maktab leaves out. Never delete his teaching, a heading over it, or a part only paper needs.**

**Put each part only paper needs inside a box marked Print only**: a table of one row and one cell whose first line
is **`Print only · `** and what it is, his words under it as he had them, a table of his inside it too:

```
Print only · Take a break
Stand up, stretch, and drink some water before Part C.
```

Use it for the cover, the colour key and its Bloom's and AO tables, *How to use these notes* or *How to read this
booklet*, a form to fill in (*Learner's name: ____*), a *Take a break* box, a line that describes the printed booklet
(*answers are at the end of the chapter*, *the last page is your checklist*), and anything else true only on paper.
Maktab leaves each box out, *Marked for print only.*

**A table or a numbered list of the sub-topics, and a line to fill in, need no mark**: Maktab knows them by their shape.
So too, should a mark be missed, the cover (his opening lines naming the college), *Linked to*, the colour key (*What
you see | What it means*), a Bloom's table (*Bloom's level | …*), an AO table (*AO | …*), the key to his boxes (*Box |
Use it for*), *How to use these notes* with its list, and the lines under his keys that say how his questions are marked (*Note: Questions marked ⚠ …*, *How the tags are assigned: …*, a key to multiple-completion answers), before the first sub-topic; and his learning-outcome tables
(*LO* beside a Bloom's level) and *Covers learning outcomes 2.1.1 L1 REMEMBER …* lines, wherever they sit: the
sub-topic's page shows them. The heading and notes over a sub-topic's past-paper questions (*Exam practice 2.1 · real Cambridge past-paper
questions*, *Paper 1 · Multiple choice (6 questions)*, *All 6 Paper 1 questions … are included.*), wherever they sit:
the questions under them go to its Past paper questions tab.

Anything else before the first sub-topic comes in, to the topic's Introduction: his *Chapter at a glance*, *Before you start*, a paragraph that teaches. Maktab leaves out
by itself his *Work it out here* spaces and *SOLUTION* labels, his self-assessment checklist and the page header and
footer.

- **His glossary and his chapter summary go last**, under one Heading 1 **`Summary`** after the last sub-topic,
  wherever he had them: Maktab shows them on the topic's last page.
- **Leave his answers section where it is** (*ANSWERS – Chapter 3*, his SAQ answers, answer key and mark schemes),
  under its own heading, and do not move it under `Summary`: Maktab gives each answer to its question.
- **A section headed as a worked example** (`1.3 Worked Example – Run-Length Encoding` over paragraphs) becomes a
  worked-example box, `Worked example · Run-Length Encoding`, his words inside it.

### Say what you are unsure of: [check: why]

**Only where you are truly unsure** of something you made (a value you read from a blurred scan, a table you rebuilt
from a picture, a label you chose between two), put `[check: ` and **one plain reason** `]` at the end of its
paragraph, box line, heading, picture's caption or table cell; not in a worked example or a short question, where
it is not read, so list those in your note:

```
The bond angle in water is 104.5°. [check: the scan cut off its last digit]
```

**In a table, the marker goes inside the cell it is about**, never on a line after the table's last row: there it is
a paragraph of its own, away from what it is about.

Maktab takes the marker out of what students read and shows him the reason as **Please check**: a nod he gives with
*Looks right*, or an edit. Use `[check: why]` only for what you think is **probably right**. Anything you think is
**likely wrong**, or could not do, goes in your note under *Check these*, not as a marker. A `[check]` on a heading
is counted too. Never mark what you are sure of: each one is something he must check.

### Point out what could mislead a student: [could mislead: why]

Some things could teach a student something wrong. Point each one out; **never change his words to fix it**. Put
`[could mislead: ` and **one plain reason** `]` at the end of the paragraph, caption, table cell or question (in a
table, inside the cell, as above), and list it in your note under *Check these*, quoting the exact sentence:

- **A diagram or picture whose explanation may not match it**: *[could mislead: the text says the left graph rises,
  but in the picture it falls]*.
- **A question that depended on a picture but is now only text**, so it may not make sense without it: *[could
  mislead: the question asks about "the graph above", which is not in the file]*.
- **A sentence that may be factually wrong.** Flag only what you are **confident** is wrong by standard AS & A Level
  science, from your own knowledge: a wrong formula, swapped units, a label that contradicts the text, *mitochondria
  make glucose*. Give a one-line reason: *[could mislead: glucose is made in photosynthesis, not by mitochondria]*. It
  is a suggestion only: **never claim a source** (no *according to the syllabus*, *the textbook says*), and never flag
  style, emphasis or a matter of judgement. Keep the bar high: a wrong flag insults a subject expert and teaches him
  to ignore the rest. If you find nothing, flag nothing.

Do not check his file against the syllabus or a coursebook. `[check: why]` is for what *you* made and are unsure of;
`[could mislead: why]` is for what could teach a student something wrong.

### Say what you changed: Changes made by AI

**End the copy with a Heading 1 `Changes made by AI`**, last of all (after `Summary` where his file has a glossary or
chapter summary; never add an empty `Summary` to put it after), and under it a bulleted list of what you
could not keep as he had it, one change a line (not the headings, labels and lists you set, which are the shape):

```
Changes made by AI
• Converted from PDF to Word.
• Rebuilt the table of reacting masses in 2.4 from a picture of it.
• Split the paragraph under Part B into two at its numbered steps.
```

Maktab keeps the list with the import, shows it to the teacher before his
file, and leaves it out of every lesson page. If you changed nothing, leave the heading out.

### Stamp the copy

**Put one line in the copy's page header** (Insert › Header), so Maktab knows which AI prepared it, when, and from
which directions:

```
Prepared for Maktab by Claude Opus 5.5, 29 October 2026, following the directions 2026-10-29-afdf76f
```

Your name and model, the day you made it, and the directions' version: the one line in their
[VERSION](VERSION) file, written each time they are published. Leave his own header and footer as they are,
beside it. Maktab keeps the stamp with the import and never shows it on a lesson page.

## What Maktab asks of the content

Tell him in your note when his file does any of these; never change his words for them.

- **Ask him to read what came in on Maktab as a student would**, on a phone.

- **The lesson adds to the textbook; it does not repeat it.** His lesson text is what he adds to the
  class's book: his tips, examples, common mistakes and exam pointers.
- **His own material only.** A page copied from a book or another teacher, or a past paper of another
  course or level (an IGCSE paper in an A Level file), stays out: list it ([provenance.md](provenance.md)).

## Say how far you have got

A long chapter takes a while. Never go quiet. Say all of this where he watches you work, in the terminal or the chat,
not only in the file.

- **Name each chapter as you start it**: its number among the documents he gave you, how many there are, and its
  title as his file has it, *Chapter 3 of 7: Chemical bonding*.
- **Name each document when you begin it**, *Starting ch02-processed.docx*, and when you finish it, *Finished
  ch02-processed.docx*.
- **Write a start or end time only if your chat app gives you the current time.** Otherwise leave times out. Never
  guess a time or a date.
- **Report in small batches**, naming the item each time, not only a count: every 3 items when there are up to 20,
  every 5 up to 60, every 10 above that. *Part 1 of 6: Testing for reducing sugars*; *Diagram 12 of 160: Flowchart
  2.1*.
- **When something fails, keep going.** Finish the rest, then list each failure at the end. **Never stop the run**
  for a missing answer, an unreadable word, a picture-based question or anything else you notice: do what you can,
  mark it as above, and list it in your note.
- **Say each problem plainly, with where it is in his file**: *The section that begins "Part B · Ionic bonding…"
  (about page 4): its table could not be read.* Then what he can do: try again, send that section on its own, or ask
  Maktab for help. Never show him a raw error such as *chunk 5: Expecting "," delimiter*.
- **End each document with a short summary**, straight after its *Finished* line: a count on each line, with at most
  one short reason, and *none* where there is nothing to count. The lists stay in your note and under `Changes made
  by AI`.

```
Finished ch03-processed.docx. Prepared by Claude Opus 5.5.
Made: 7 sub-topics, 31 parts, 12 worked examples, 48 past-paper questions (20 multiple choice), 64 diagrams, 9 tables.
Removed: 14 lines that point to the printed book.
Wrote myself: 31 part titles and 22 suggested answers, each marked for you to check.
Could not do: none.
The lists are in my note and under "Changes made by AI".
```

## Check your file before you hand it back

1. His words, pictures, tables of data, equations and answers are all there, unchanged, in his order.
2. Every heading is a Word heading, not a table or bold text.
3. Every Heading 1 is a sub-topic's number and Cambridge title exactly, as the export or the course's skeleton has it, or is
   *Introduction* or *Summary*; every Heading 2 is his own title, with no number or with the number of
   the sub-topic it sits under, or a title you wrote marked `[check: title written by AI; …]`.
4. Every box is a one-cell table, or a label row over a body row, whose first line is one of the labels
   above, or `Box · ` and his title.
5. Every short question names its outcomes and has its answer, or a `Suggested answer:` you wrote, and no answer or
   mark scheme anywhere is only words in brackets.
6. Every past-paper question has its reference, its marks and its answer or mark scheme, and is in one
   sub-topic.
7. Every bulleted list is a Word bulleted list, every numbered list keeps his numbers, and every
   picture is a pasted picture.
8. His teaching and every heading over it are all there; nothing only paper needs is deleted: Maktab knows it by its
   shape, or it is in a `Print only · ` box. His glossary and summary sit under `Summary`; no line only points to a
   printed book, and no reference to a question bank is left; the last heading is `Changes made by AI`, when you
   changed anything.
9. Every picture of a question or mark scheme has its `Words:` paragraph under it.
10. Each `[check: why]` is where you are truly unsure, with one plain reason; each `[could mislead: why]` is what you
    are confident could teach a student something wrong; in a table, both sit inside a cell. A `[keep as table]` line
    sits on its own just above a table of words that must be read across, and nowhere else.
11. The page header has your stamp, `Prepared for Maktab by …, …, following the directions …`.
12. Save it as a Word file named as his was, with ` (for Maktab)` before `.docx`.

## The note to the teacher

Short and plain, in this order:

1. **Check these**: everything he should look at, so he can fix it while he has his file open: each heading you
   could not place, each box whose label you chose or could not choose, each question in two sub-topics, each part
   title you wrote yourself, each suggested answer, each word marked `[?]`, each `[could mislead: …]` with the
   sentence quoted and your reason, each question that depended on a picture, each piece that failed with where it
   is, and anything else that looks wrong. The learning outcomes you chose are not listed.
2. **Left out**: anything that is not his own material, with where it came from, and the lines pointing to a printed
   book and the question-bank references you deleted.

What you changed is in the file itself, under `Changes made by AI`, not in the note.

Then he sends the file back, or imports it.
