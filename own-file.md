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
   from. If there is none, make a Word file from the PDF and say so in your note.
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

- **His words**: spelling, wording, order. Correct nothing. If something looks wrong, leave it and say so
  in your note.
- **His pictures, tables of data, equations and symbols.** A subscript or superscript he set stays set.
- **His answers and marks.**

## The shape

```
3 Dynamics                                         Title: the topic's number and name
Introduction                                       Heading 1: what comes before the first sub-topic
  …his introduction, chapter at a glance…
3.1 Momentum and Newton's laws of motion           Heading 1: the sub-topic, as Maktab names it
  Mass and inertia                                 Heading 2: each of his sections, in his own words, no number
    paragraphs, lists, boxes, pictures
    Check your understanding · 3.1.3               a box: one short question, its outcome, its answer
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
  dash is read as after a middle dot. You may leave these as he wrote them.
- **A small icon picture on a label line** is his label's mark: leave it; Maktab shows its own.
- **A two-row table whose top row names no label** (a formula over its key, `F = ma` over `F = resultant force
  / N …`; a law over its note) **gets Maktab's label**: a key equation `Key idea · F = ma`, a law or definition
  `Definition · Newton's first law` (M-455). An empty one is a work space: leave it.
- **A label that means one of Maktab's but uses other words** (`GAP FILLED – WHERE DOES THIS LAW COME
  FROM?`, which is a derivation) **is not read**: put Maktab's label first and keep his words as the
  title, `Derivation · GAP FILLED – WHERE DOES THIS LAW COME FROM?`. When you cannot tell which label
  fits, use `Box · ` and his words, and list it in your note.
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
- **A table of data stays a table**, as he set it.

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
  *Quick check*, filed under that outcome; one with none goes to *Practise*. The outcome may instead be a line
  of its own in the box, `Learning outcome 3.1.3`.
- His worked solution may follow the box, as he wrote it (*Work it out here:*, his empty table, *SOLUTION*,
  then his numbered steps): Maktab leaves out the work space and reads the steps as its working; its
  `Answer:` line is the answer, else its last step.
- **Numbered self-assessment questions** (`SAQ 2.4 …`) in one box, with their answers in a table at the
  end of the file whose rows start with the same `SAQ 2.4`, may stay as he wrote them: Maktab reads them.
  Each follows the same rule: give its outcome after its number and a middle dot, `SAQ 2.4 · 2.2.1 Define the
  term polysaccharide.`, and it goes to the *Quick check*; with none, to *Practise*.
- Every question needs its answer.

### Past-paper questions

1. **Each question starts with its paper reference, and its marks**:
   `Q1(b)   9701/22/M/J/20 Q1(b)   [2 marks]`. The reference is the paper code, the series (`M/J`,
   `O/N`, `F/M`) and year, and the question number.
2. **A multiple-choice question has its answer**: in the answer key, one row per question, or on a line
   after it, `Answer: B`. **A question whose key has no row brings nothing in**, and a booklet whose
   every key row is missing brings nothing at all.
3. **A structured question has its mark scheme**, after it or in his answer section, under the same
   number.
4. **Each question is in one sub-topic only**: the one it mainly tests. If the same question (the same
   paper and number) is in two, keep it in one and list the other in your note.
5. **A picture of the printed question or mark scheme stays where it is, and you add its words under it**: a
   paragraph starting **`Words:`** with what the picture says, as a student would type it (sub- and superscripts
   set as Word's, `[2 marks]` kept). Never replace the picture; a diagram, graph or table drawn in it stays the
   picture, and the words may point to it (*Figure 2.1 shows …*).

### Coursebook pages

A line pointing to a book, `Compare: coursebook Figures 3.3 and 3.5 (pp. 64–66), Ryan & Norris 3e`, is
kept only when the book is the one approved for the course. **Give each sub-topic one line, at its start, where
the student reads it**: `Read: Coursebook Section 2.4, p. 46`. A table of every sub-topic's pages at the chapter's
start becomes those lines, one under each sub-topic's heading, and the table goes. **List every such line in your
note**, so he can check the pages match the edition his students hold.

### Maktab is a website, not a handout: take out what only paper needs

A student reads Maktab on a phone, page by page, with the class's book in her hand and Maktab's own pages around
his (the owner, 28 October 2026). **The copy you hand back is for Maktab**; his own file stays as it is. **Take
out of it** (Maktab leaves these out too, but a clean file comes in cleaner): the cover, a
table of contents, the chapter map, the learning-outcome table, *Covers learning outcomes* lines, AO and
Bloom's level lines, a self-assessment checklist, *Take a break* boxes, *Work it out here* spaces and
*SOLUTION* labels; and a booklet's apparatus for paper: forms to fill in (*Learner's name: ____*, *Teacher's
signature: ____*), *Prepared for … by …* lines and repeated headers and footers, *Linked to* (the syllabus,
the coursebook, Bloom's), *How to use these notes* and *How to read this booklet*, a colour and style code
and its Bloom's and AO tables; a chapter-at-a-glance list of the sub-topics (keep a paragraph
around it that teaches, as the Introduction). **Drop any line that describes the printed booklet** (*answers are at
the end of the chapter*, *the navy banner*, *the last page is your checklist*), since it is untrue online, and list
each in your note.
- **His glossary and his chapter summary go last**, under one Heading 1 **`Summary`** after the last sub-topic,
  wherever he had them: Maktab shows them on the topic's last page.
- **A section headed as a worked example** (`1.3 Worked Example – Run-Length Encoding` over paragraphs) becomes a
  worked-example box, `Worked example · Run-Length Encoding`, his words inside it.

## What Maktab asks of the content

Tell him in your note when his file does any of these; never change his words for them.

- **Ask him to read what came in on Maktab as a student would**, on a phone.

- **The lesson adds to the textbook; it does not repeat it.** His lesson text is what he adds to the
  class's book: his tips, examples, common mistakes and exam pointers.
- **His own material only.** A page copied from a book or another teacher, or a past paper of another
  course or level (an IGCSE paper in an A Level file), stays out: list it ([provenance.md](provenance.md)).

## Check your file before you hand it back

1. His words, pictures, tables of data, equations and answers are all there, unchanged, in his order.
2. Every heading is a Word heading, not a table or bold text.
3. Every Heading 1 is a sub-topic's number and Cambridge title exactly, as the export or the course's skeleton has it, or is
   *Introduction* or *Summary*; every Heading 2 is his own title, with no number or with the number of
   the sub-topic it sits under.
4. Every box is a one-cell table, or a label row over a body row, whose first line is one of the labels
   above, or `Box · ` and his title.
5. Every short question names its outcomes and has its answer.
6. Every past-paper question has its reference, its marks and its answer or mark scheme, and is in one
   sub-topic.
7. Every bulleted list is a Word bulleted list, every numbered list keeps his numbers, and every
   picture is a pasted picture.
8. Nothing only paper needs is left: no cover, form, *How to use*, colour code or chapter map; his glossary and
   summary sit under `Summary` at the end; each sub-topic has its one `Read:` line.
9. Every picture of a question or mark scheme has its `Words:` paragraph under it.
10. Save it as a Word file named as his was, with ` (for Maktab)` before `.docx`.

## The note to the teacher

Short and plain, in this order:

1. **Check these**: each heading you could not place, each box whose label you chose or could not
   choose, each coursebook line, each question in two sub-topics, each missing answer, and anything that
   looks wrong.
2. **Changed**: what you changed, by kind, with a count: *9 headings made Word headings; 4 box labels
   set; 12 bulleted lists made Word lists.*
3. **Taken out for Maktab**: what only paper needs, by kind, and each line describing the printed booklet.
4. **Left out**: anything that is not his own material, with where it came from.

Then he sends the file back, or imports it.
