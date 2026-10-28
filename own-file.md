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
  3.1 Mass and inertia                             Heading 2: each of his sections, sub-topic number first
    paragraphs, lists, boxes, pictures
    Check your understanding · 3.1.3               a box: one short question, its outcome, its answer
  3.1 Past-paper questions                         Heading 2
3.2 Non-uniform motion                             Heading 1
  …
Summary                                            Heading 1: what comes after the last sub-topic
```

### Headings

1. **Every heading is a real Word heading** (Home › Styles): the topic Title, each sub-topic Heading 1,
   each of his sections Heading 2, a smaller heading inside one Heading 3. **Never a table, a shaded
   band or bold text.** A heading set as a table (`01 | Mass, inertia… | 3.1`) becomes a heading:
   `3.1 Mass, inertia, and Newton's second law`. The table's other lines (`3.1 – F = ma …`) stay, as a
   paragraph just under the new heading.
2. **Every Heading 1 and Heading 2 starts with the Cambridge sub-topic number it teaches**, then his
   own words: `3.1 Mass and inertia`, `4.1 Section A: Multiple choice solutions`. Use only numbers the
   export or the course's skeleton has. A section that teaches two goes under the one it teaches most.
3. **Take off his own numbering**: `3. Client–Server Model` becomes `2.1 Client–Server Model`;
   `1.1 What Is a Computer Network?` in a 9618 file becomes `2.1 What Is a Computer Network?`. Maktab
   reads a number at the start of a heading as a Cambridge sub-topic, so his own 1.1 would be read as
   another sub-topic.
4. **What sits before the first sub-topic** (his introduction, *Chapter at a glance*, *How to use these
   notes*) goes under a Heading 1 *Introduction*, when there is any besides a cover and a contents page; **what sits after the last** (his summary, glossary,
   key terms) under a Heading 1 *Summary*. Maktab puts them on the topic's own first and last pages.
5. **If you cannot tell which sub-topic a section teaches, do not guess.** Leave its heading as it is
   and list it in your note.

### Boxes

A box is a table of **one row and one cell**. **Its first line is its label**, alone or followed by its
title after a middle dot (`·`):

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

A worked example he set as a table of several rows may stay: Maktab reads it. Pictures inside it come
in with it. **His solution may follow the box**, as he wrote it (after a *SOLUTION* line, his steps
indented): Maktab reads it as the example's working, up to its last step. Leave it where it is.

**His work spaces** (an empty table or *Work it out here* for a printed copy) stay as they are; Maktab
leaves them out. **A picture inside a work space, or inside any table that is not a box, does not come
in**: when it belongs to the solution, move it to a line of its own just after the table.

### Lists, pictures, tables

- **A bulleted list is a Word bulleted list** (Home › Bullets), never typed dashes or `•` at the start of
  a paragraph.
- **A numbered list keeps the numbers he typed** (`1.`, `(a)`, `Step 1`): leave them as text, and never
  make them Word numbering. Maktab keeps a typed number. A number Word draws can be lost (21 step numbers
  in a test on 28 October 2026), and a letter or roman numeral Word draws always is.
- **A picture is pasted as a picture** (PNG or JPEG), on a line of its own, its caption the line just
  under it. A chart, a drawing made of shapes, or a linked picture does not come in: paste a picture of it.
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

- A question with its outcome goes to the sub-topic's *Quick check*, exactly where he meant; one with
  none is placed by guesswork, so always write it.
- His worked solution may follow the box, as he wrote it; its last line is then the answer.
- **Numbered self-assessment questions** (`SAQ 2.4 …`) in one box, with their answers in a table at the
  end of the file whose rows start with the same `SAQ 2.4`, may stay as he wrote them: Maktab reads them.
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
5. **A picture of the printed question** is fine: Maktab reads it into words and keeps the picture.

### Coursebook pages

A line pointing to a book, `Compare: coursebook Figures 3.3 and 3.5 (pp. 64–66), Ryan & Norris 3e`, is
kept only when the book is the one approved for the course. Keep it as he wrote it, and **list every
such line in your note**, so he can check the pages match the edition his students hold.

### Left out by Maktab, so leave them as they are

Maktab already shows these another way and skips them; do not remove them from his file: the cover, a
table of contents, the chapter map, the learning-outcome table, *Covers learning outcomes* lines, AO and
Bloom's level lines, a self-assessment checklist, *Take a break* boxes, *Work it out here* spaces and
*SOLUTION* labels.

## What Maktab asks of the content

Tell him in your note when his file does any of these; never change his words for them.

- **The lesson adds to the textbook; it does not repeat it.** His lesson text is what he adds to the
  class's book: his tips, examples, common mistakes and exam pointers.
- **His own material only.** A page copied from a book or another teacher, or a past paper of another
  course or level (an IGCSE paper in an A Level file), stays out: list it ([provenance.md](provenance.md)).

## Check your file before you hand it back

1. His words, pictures, tables of data, equations and answers are all there, unchanged, in his order.
2. Every heading is a Word heading, not a table or bold text.
3. Every Heading 1 and Heading 2 starts with a sub-topic number the export or the course's skeleton has, or is *Introduction* or
   *Summary*; no heading keeps his own numbering.
4. Every box is a one-cell table whose first line is one of the labels above, or `Box · ` and his title.
5. Every short question names its outcomes and has its answer.
6. Every past-paper question has its reference, its marks and its answer or mark scheme, and is in one
   sub-topic.
7. Every bulleted list is a Word bulleted list, every numbered list keeps his typed numbers, and every
   picture is a pasted picture.
8. Save it as a Word file named as his was, with ` (for Maktab)` before `.docx`.

## The note to the teacher

Short and plain, in this order:

1. **Check these**: each heading you could not place, each box whose label you chose or could not
   choose, each coursebook line, each question in two sub-topics, each missing answer, and anything that
   looks wrong.
2. **Changed**: what you changed, by kind, with a count: *9 headings made Word headings; 4 box labels
   set; 12 bulleted lists made Word lists.*
3. **Left out**: anything that is not his own material, with where it came from.

Then he sends the file back, or imports it.
