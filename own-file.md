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
   **From a PDF, also:** join a sentence the PDF broke across lines back into one paragraph, inside a box as much as outside
   it, and keep a list one line per item with its mark on that line (`a. hotel`, never `a` and `hotel` on two lines); set every superscript
   and subscript as Word's (`m s⁻²`, `10³`, `dm⁻³`, `10 °C`), never `m s-2`; and leave out the page header, footer
   and page number printed on every page (*7. Waves · Basic properties*, a name, *Page 3*). They are the PDF's, not his
   teaching, and must never come into a heading, a question or a mark scheme. **One the PDF's text runs into his words comes off them too, his words kept**: `… [2]  A2 Physics Circular Motion`, `… [3]  9702/42/O/N/23 [Turn over  (ii) Determine …`.
   **A block that is only header lines is a header, in any number of lines** (`4.Dynamics` over `Newton's 2nd Law`): take it
   out line by line, and never join it to the line after it, so the `Q1` under it still starts its question.
   **Clean by what you cannot read, never by a symbol.** `×`, `÷`, `±`, `°`, `Δ`, `Ω`, `µ`, `√`, `≤`, `≥` and `→` are his content: a line
   holding one is never a fault, and never dropped. Only a run of garbled characters is, and a line you cannot read stays, marked `[check: why]`.
   Maktab joins a long line that plainly goes on in
   the next; a short one, and a question's or a mark scheme's lines, it leaves as they are. A teacher whose lesson reads as
   fragments pastes this to his AI:

   ```
   In your copy each paragraph must be one paragraph, not one line per line of the PDF, in the lesson and inside boxes alike. Where a sentence goes on across lines, join them. Keep each list one line per item, its mark on that line. Join nothing else: keep a list's items, a table's cells and a question's options as they are, and change no words.
   ```
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
- **His pictures, tables of data, equations and symbols.** A subscript or superscript he set stays set. **Never drop
  a picture**: every picture in his file is in your copy, where it stood (below).
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
8. **A long part that covers more than one idea is split into parts, one idea each**, every new part a Heading 2
   with a 3-to-8-word title. **Where his own heading, sub-heading or run-in label already names the idea** (a bold
   or full-stopped label at a paragraph's start, *Market research.*), **it is the title, word for word, with no
   `[check: …]` and not in your note**: it is his, so there is nothing to check; it moves up to be the heading and is
   not repeated in the body. Only a title you write yourself ends `[check: title written by AI; …]` and goes in your
   note. **Never change his words in the body**: only add headings and paragraph breaks where the idea changes.
   Keep each paragraph to one idea.
   **A part of over 1,500 words is long**: students read one part at a time, and that is about nineteen screens on a
   phone. Maktab keeps a part whole, so its import names one that long, once for its sub-topic, under that
   sub-topic's name in the summary. A teacher whose import names a long part pastes this to his AI, then imports its copy:

   ```
   Split every part of over 1,500 words into parts, one idea each, each new part a Heading 2 with a title of 3 to 8 words. Where my own heading or label already names the idea, it is the title. Never change my words.
   ```

### Start here and Wrap up

**A sub-topic opens with a Heading 2 *Start here* and closes with a Heading 2 *Wrap up*, when he has them.** Put what
comes before its first part (what the sub-topic is about, what to know first) under *Start here*, and his summary,
key points or *now you can…* under *Wrap up*, his words as he wrote them. Leave out either he has nothing for. Name
them exactly *Start here* and *Wrap up*: students read each sub-topic one part at a time, and Maktab shows these two
as its first and last screens. They are the sub-topic's own: the topic's *Introduction* and *Summary* (above) stay the
whole topic's, at its start and end.

**A *Start here* is about the whole sub-topic, never only the part his file teaches.** Where his file covers one part
of a sub-topic (*Irrecoverable debts*, in *1.4 Reconciliation and verification*), his opening lines go under *Start
here* as he wrote them, and you never write that the sub-topic covers only that part. A line you write yourself names
what the whole sub-topic covers, from its Cambridge title and outcomes, and ends `[check: Start here written by AI]`.

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
- **A box holds one whole box of his, and nothing else.** A box the book runs over a page is one table: all of it in one
  cell, its questions and its last sentence included, however long, never a second table or plain paragraphs under the first.
  What comes after the box's last line, a heading of his lesson above all, goes outside it. Maktab brings one line that plainly
  finishes a box's last sentence into the box, and can tell no more. A teacher whose box stops mid-sentence, or holds his
  lesson, pastes this to his AI:

  ```
  Each box in my book must be one table in your copy, holding all of that box and nothing else. Where a box runs over a page, keep every line of it in one cell, its questions too. Move any heading or lesson text that is not part of the box out of the table, to just after it. Change no words, and say in your summary which boxes you changed.
  ```

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
- **Never drop a picture** (but for a blank page or a picture of one colour, below). Every other picture in his file comes into your copy, where it stood. One that sits on a line
  with his words (a picture in the middle of a question's first sentence) goes on a line of its own just above them;
  a picture that holds a question's options or graphs stays with that question. Count his pictures and yours before
  you hand it back, and list any you could not keep under *Check these* in your note, with where it was.
- **A blank page or a picture of one colour is no picture: leave it out, and count it nowhere.** Never render a blank page of his PDF as a picture, even
  in a file you treat as a scan. Before you paste any picture, lay it on white and count its colours: where it has one, all white, all black, a band or a square, leave it out and say nothing of it. A figure on a white background with a few lines in it has more than one colour and stays.

  ```python
  page = Image.new("RGBA", im.size, "white"); page.alpha_composite(im.convert("RGBA"))
  one_colour = page.convert("RGB").getcolors(1) is not None
  ```

  A teacher whose copy shows a blank gap or a black band pastes this to his AI:

  ```
  Leave out every blank page of my file, and any picture that is one colour all over, such as a white page, a black band or a black square. Never render a blank page as a picture. Lay each picture on white and count its colours to tell. Keep every figure with anything drawn in it, and do not count what you leave out.
  ```
- **Each picture stands above the caption the book prints beside it, and no other.** A PDF hands out a page's images in any
  order, a page's ornament among them (an arrow, a dot, a rule), so never give captions to pictures in order: look at the page
  and see which is which. Leave ornament out and do not count it. **Maktab does not draw a picture too small to read, and when
  one sits over a caption it leaves out every captioned picture in the file**, since the captions may be on the wrong ones: a
  wrong caption is worse than a missing picture. Copy each caption whole from its first word, and read a word a PDF split back
  together (*Figur e*, *Entr epreneur*). A teacher whose pictures are under the wrong captions pastes this to his AI:

  ```
  Check every picture in your copy against my book's page. Each picture must stand just above the caption printed beside it in the book, never given a caption by its order in the file. Leave out arrows, dots and rules that are the page's ornament. Copy each caption whole, from its first word, and join any word the PDF split. Where you cannot tell which picture is which, leave the picture out and write [check: figure not carried] at the end of its caption's line.
  ```
- **Every figure of his is in your copy, a figure drawn in lines as much as one pasted as a picture.** A PDF, and a Word
  file saved as one, often holds a graph, axes, a circuit, a scale drawing or a geometry diagram as lines: `page.get_images()`
  finds nothing on its page and `page.get_drawings()` finds its strokes, while its axis numbers and labels come out as
  loose words. **Copy such a figure across whole**: crop it from his page at 200 dpi or more, with its axis labels and
  numbers inside the picture, and paste it where his caption stands, the caption on the line under it. None of its labels
  stays behind as a line of text (`p / 10⁴ N s`, `0 0`, `2 4 6 8 10 t / s`). **Count each drawn figure with his pictures.**
  Where you cannot carry one, write `[check: figure not carried]` at the end of its caption's line, leave its loose labels out,
  list it under *Check these* in your note and on the *Could not do* line of your summary. Maktab holds back a question that
  names more figures than it has pictures, and tells him of a caption with no picture over it and of a drawing made of
  shapes. A teacher whose copy lost a figure pastes this to his AI:

  ```
  Every figure in my file must be in your copy, including a figure drawn as lines rather than pasted as a picture. Crop each such figure from my page as one picture, with its axis labels and numbers inside it, and paste it where my caption stands. Leave none of its labels behind as loose text. Where you cannot carry a figure, write [check: figure not carried] at the end of its caption's line and say so in your summary.
  ```
- **A pen note he wrote in Word is his words: type it. No handwriting reaches a student.** Maktab is a school's website, and handwriting on it is not acceptable. Word keeps each note twice: its strokes in `word/ink/`, and in the same `mc:AlternateContent` an older copy, `mc:Fallback` with a `v:imagedata`, whose PNG is under `word/media/`. Open each and read it. **A note with words or a number is typed as a line of its own just under the paragraph that holds it**, in his order; notes a bracket or arrow joined become one list, or a sentence, saying what joined them; one in a table goes just under the table. **A note you cannot read, or a drawing words cannot say, is left out of your copy, never pasted as a picture**: in its place write a line `[check: handwritten note, type it]` and list it under *Check these*, with where it was. Maktab tells him, and it stays on his page until he types it or draws it properly. **Leave out a stroke that only marks his words**: a highlighter's (`rasterOp` `maskPen` in its `word/ink/` file), and a bare underline, circle, box, tick, cross or arrow, which say nothing away from the words they mark. A teacher whose copy lost his notes pastes this to his AI:

  ```
  Type every pen note I wrote in Word. No handwriting may stay in the file. Word holds a picture of each, in the note's older copy (mc:Fallback, v:imagedata, a PNG under word/media/). Read each and type its words on a line of its own just under the paragraph that holds it, or just under the table if it stands in one, in my order. Where a bracket or arrow joins notes, make them one list or a sentence that says what joined them. Where you cannot read a note, or it is a drawing words cannot say, leave it out and write [check: handwritten note, type it] on a line in its place, and tell me each one in your summary. Leave out a highlighter's stroke and a bare underline, circle, box, tick, cross or arrow.
  ```
- **A row of dots or dashes a paper prints for writing on is paper, not a picture: leave it out, never paste it, and never
  count it.** A printed paper may draw each writing line as about 137 separate pictures of 1 to 13 pixels: one file's 57
  lines were 8,139 of them, and pasted they made 325 pages of his 18. **A row of pictures, each under about 10 points across and
  tall, with no words beside it, is one writing line**: leave them out of your count of his pictures, and say nothing of them. Keep a
  small picture that stands in his sentence, a symbol, an arrow or a fraction (*the particles are represented by ●*), on a line of its own just above his words. **Maktab leaves such rows out by itself**, so a
  missed one does not reach a student; a figure is never one of them. A line of dots typed as text in a question, `speed =
  ............ m s⁻¹`, is not a picture: leave it, Maktab makes it her answer box.
- **A line cleaner never touches punctuation inside a line.** If your script cleans dots from his lines, it drops only a line
  that is nothing but dots and spaces. `re.sub(r'\s*\.[\. ]*', ' ', line)` strips every full stop in a line, so `$0.40`
  becomes `$0 40` and `2.5%` becomes `2 5%`, and a student cannot work the sum. **Hold every number of your copy against his
  file before you hand it back**: a figure that has lost its decimal point is a failed copy. A teacher whose copy has either fault pastes this to his AI:

  ```
  Leave out every row of dots or dashes my paper prints for writing on, and never paste them as pictures: a row of small pictures, each under about 10 points across and under about 10 points tall, with no words beside it, is one writing line. Leave them out of your picture count. Keep any small picture that stands in my sentence, such as a symbol, an arrow or a fraction. Clean only a line that is nothing but dots and spaces, and never change a full stop, comma or percent sign inside a line: $0.40 stays $0.40 and 2.5% stays 2.5%. Check every number in your copy against my file before you hand it back.
  ```
- **A typed line of nothing but dots is paper too: leave it out of your copy.** The answer is typed in Maktab, so `..........` under a
  question only makes the page look like paper. Drop a line that is nothing but dots and spaces. Where it ends in his marks, `.......... [2]`,
  put `[2]` at the end of the last line of words above it, so his mark stays and the dots go. **Keep every line with a word of his on it exactly as he typed it**: `amount = ……… mol` stays. **A past-paper question that names its paper keeps its dots**, whole lines too: Maktab makes each one her answer box. Say nothing of the lines you drop, and count them nowhere. Maktab leaves out a line of nothing but dots by itself; his marks need you. A teacher whose copy has such lines pastes this to his AI:

  ```
  Drop every line that is nothing but dots and spaces, and if it ends in my marks, such as [2], put the mark at the end of the last line of words above it. Keep every line with a word of mine on it exactly as I typed it, such as amount = ……… mol. Keep the dots under a past-paper question that names its paper: Maktab makes them answer boxes.
  ```
  **Never delete a paragraph by its number.** Moving anything changes every number after it: a copy that moved each picture
  to a new paragraph, then deleted paragraphs by the numbers they had, lost all four. Delete a paragraph by what it says, or
  keep it. Maktab says so where a file packs pictures and none stands on a line.
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

- **Keep his working and his mark points with his answer.** For a calculation, his steps are its working, under
  its `Answer:`; for a written answer, his mark points or his model answer; and his mark scheme where he has one,
  under the same question. Maktab needs them to quiz students on his questions and to mark them, across its pages.
- **A word in an answer you cannot read** (a blurred scan, a cut-off line): write your best guess and put `[?]`
  straight after it, `Answer: the enzyme is denatured [?]`, and list it in your note. Maktab does not mark students
  against that answer until he checks the word.
- A past-paper question is not a short question: never write its mark scheme yourself (below).

### Past-paper questions

1. **Each question starts with its paper reference, and its marks**, a paragraph of its own: his first words and any picture start the next paragraph, never a line break under the reference in theirs:
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
   entry of the same number, `2.`, moved under it as a `Mark scheme:` paragraph (7), or a box whose first line is
   `Mark scheme`, for a structured one. One with no answer in
   the file stays in the sub-topic's notes. **A heading whose paper cannot be read** (`9702/SP/2016`, `[series]/[year]`, no
   paper at all): find the paper in his file and write it; where his file does not say, head it `Q19   [check: paper not in
   his file]   [5 marks]`, never a guess. With its answer it comes in under *Paper unknown*.
   **A question's answers never stay in the notes**: Maktab leaves out of a sub-topic's text any mark scheme, answer sheet,
   `Answer:` line under a question or `Suggested answer:` it finds there, and warns him. **An answer sheet left as a
   section** may stand under a heading or a plain line, `ANSWER SHEET` or `Answers`, each entry numbered as its question
   is on the worksheet, `1.`, `Q1` or `Answer 1`, and starting again at `Answer 1` for each sub-topic: leave his numbers and
   marks as his file has them. Maktab takes an entry for the question of the same number where their marks agree, and
   leaves out any it cannot be sure of, saying so under *Left out*. Never renumber to make them fit: one wrong number gives
   a student another question's answer. Moving each answer under its question (7) is surer, and is what to do with one left out. A worked example keeps its answer, in its box.
   **Questions left as plain numbered lines with no paper under them are not read as questions**: they come into the
   sub-topic's notes, and Maktab warns him there. Give each its reference, or put a short one in a box (above).
   **The full reference is all Maktab needs to take Cambridge's answer**: the paper, series, year and the
   question's number on that paper (`9701/11/M/J/15 Q5`). Maktab fetches Cambridge's key or mark scheme itself;
   his own answer, where he gives one, comes first.
2. **A multiple-choice question has its answer**: in the answer key, one row per question, or on a line
   after it, `Answer: B`, with his own reason where he gives one, `Answer: B (ionic bonds need two elements)`, which students
   read as his solution once they have tried it. **A question whose key has no row takes Cambridge's published key's answer** where
   Maktab holds that paper's key, shown beside it as *From Cambridge's published key*; his own key row, or his
   change to the answer on its page, replaces it. Where Maktab does not hold the paper's key, the question brings
   nothing in, and a booklet whose every key row is missing brings nothing at all. Where he gives no key, leave
   the `Answer:` line out; never write a placeholder such as `Answer: [see note]`. **Never write a `Suggested answer:` under a
   past-paper question**, a letter you worked out included: Maktab never takes it as the key and leaves it out.
3. **A structured question has its mark scheme**, after it or in his answer section, under the same
   number, moved under the question as its own `Mark scheme:` paragraph (7) where it came in his answer section.
   **Without it, it takes Cambridge's published mark scheme** for that question and part where Maktab
   holds it, shown as *From Cambridge's mark scheme*; his own scheme, in this file or changed on its page,
   replaces it. **Type the scheme he gives as he gives it, each line, its mark and its part's letter as his file has them:
   never change a mark, drop a line or add one so its points add up to the question's marks, and never re-letter a part.** **A scheme holds only its question's rows:** where his answer pages run on, each row goes under the question whose number it names, `6(b)` under question 6 and never under 7, and a row of a question this file does not hold goes nowhere. Maktab leaves out a line labelled with another question where it finds the question on its paper. A scheme in this file whose points add up to more or less
   than the question's marks gives way at the import to Cambridge's for the parts Maktab holds, which the page shows as *From Cambridge's mark scheme: (a)(i), (c)*.
   Nothing needs doing about that, and nothing is said of it. Maktab finds the question on its paper by its words where it holds the paper, whatever number the
   heading gives. Where Maktab does not hold the scheme, the question comes in with no answer, an error on its sub-topic's
   page until its mark scheme is added there or in this file. Never type a scheme he did not give: where he gives
   none, leave the `Mark scheme:` line out, never a placeholder such as `[mark scheme not provided]`.
   **Where the report says a question is not found on its paper**, change its heading to its paper and number on Cambridge's
   paper, `9702/23/M/J/13 Q3`, the number as Cambridge's paper prints it, never guessed; **where it says its marks differ from the
   paper's**, give it the parts and marks the paper prints, or head it with only the part it holds. Never type out Cambridge's
   scheme for either. **Where it says Cambridge's mark scheme cannot be read in full**, leave it as it is: it comes in with no answer
   until he adds his own on its page. **Where it says a multiple-choice question's words are not found on its paper**, add the answer
   he gives, `Answer: B`, and its options if they are missing; with no answer from him, leave it.
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
   **Under a question stand only its own pictures**: the figures its words name, *Fig. 7.1* being question 7's on Cambridge's paper. A picture on a
   page two questions share goes under the one it belongs to, once. A band or mask a PDF prints on every page is no picture of his: leave it out.
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
6. **Type every multiple-choice option with its letter at its start**, `A`, `B`, `C`, `D`, and every numbered
   statement with its number, `1`, `2`, `3`, as the paper has them. Where his options are a lettered Word list, the
   letters are Word's numbering, not text: type them, so no option loses its letter.
   A Word table of its options may stay as it is, with the letters down its side or across its top: Maktab reads either.
   A question typing its own four options has no such table: leave out a box of responses printed among its words.
7. **One mark scheme per question, under its question.** Where his answers come as a separate section (*Answers*,
   *Mark scheme*, *Solutions*), move each question's lines to just after that question as its own `Mark scheme:`
   paragraph, holding only the lines under its own number: never the whole section, another question's lines, or a
   page header or footer. **Never leave a shared answers block**: once every question has its own, his answers
   heading goes too, and nothing is left under it. Where you cannot tell where one question's lines end, put them
   under the question whose number they follow, end that `Mark scheme:` with `[check: where question 2's answers
   end]`, and list it under *Check these*. A multiple-choice answer key, one row per question, may stay as his key (2).
   **His scheme pages need no `Mark scheme` label.** A run of numbered blocks matching his question numbers (`1.` to `10.`, each with
   its parts and mark points, `C1`, `M1`, `A1 [2]`), under any heading that is not his question's words (`Answers Newton's second
   Law`, `Solutions`, a running page header, or none), **is his scheme**: move each number's lines under the question of that number.
   Count his mark points (`B1`, `C1`, `M1`, `A1`) in his file and in your copy; they must agree. Keep a line where you cannot tell whose it is, by the rule above.
   **Never write a note in a scheme's place** (`His mark scheme at the back of the file answers this question`): Maktab reads it as
   no scheme, and it says nothing a student can use. **Never claim stand-in answers for a question his own scheme answers, and
   never print a note about invented lines on a question where nothing was invented.**
8. **Never write a placeholder reference**, `9708/12/[series]/[year] Q[n]` or any reference with words in brackets.
   Where his file names no paper for a question, write no reference: the question stays as he wrote it (1, above),
   and you list it under *Check these*.
9. **Each question starts exactly where its marker stands, and keeps every part, in his order.** Every question
   marker in his file, `Q2`, `Q2 (O/N/12/22)`, `Question 2`, with or without its paper, starts a new question there
   and nowhere else. Every part, `(a)`, `(b)`, `(c)` …, with its figure, table and marks, stays under its own
   question in his order, **even across a page break**: a `(c)` at the top of the next page belongs to the question
   above it, not to the next marker. **Never move a question's heading** above or below any of its parts, **never
   reorder parts**, and never start a question at `(b)` or `(c)` unless his file does (an excerpt he chose).
   **Never copy a running page header or footer** (the chapter or section line printed on every page, a page
   number) into a question, and **never split one line of a question into paragraphs mid-sentence**: a sentence a
   PDF broke across lines is one paragraph. Where you cannot tell which question a part belongs to, leave it
   under the question it follows, add `[check: which question this part belongs to]` and list it under *Check
   these*. **A part standing after a later question's marker or its `[Total: 11]` is the earlier question's**, where a PDF's
   pages ran so (*velocity = … at … ° to the vertical* under a car question): move it back under the question whose parts and marks it
   completes, **a short line with it too** (`The mass of the magnet is 130 g.` above its `(a)`). Where you cannot tell, leave it with that marker: Maktab moves it where the question straight above is short of just its marks, and otherwise says so and leaves it out. For example, his PDF has, on page 1, `Q1 (M/J/15/22)` with its `(a)`, then `Q2 (O/N/12/22)` with
   `(a)` and `(b)`, and on page 2, under the running header `4. Dynamics  Newton's second law`, that question's
   `(c)`. **Wrong** (each line a paragraph):

   ```
   Q1   9702/22/M/J/15   [2 marks]
   4. Dynamics  Newton's second law
   (a) A ball of mass 0.20 kg is thrown vertically upwards. Calculate its weight. [2]
   (a) Define linear momentum. [1]
   (b) A trolley of mass 1.5 kg moves at 2.0 m s⁻¹. Calculate its
   momentum. [3]
   Q2   9702/22/O/N/12   [2 marks]
   4. Dynamics  Newton's second law
   (c) Explain why the trolley slows down. [2]
   ```

   **Right:**

   ```
   Q1   9702/22/M/J/15   [2 marks]
   (a) A ball of mass 0.20 kg is thrown vertically upwards. Calculate its weight. [2]
   Q2   9702/22/O/N/12   [6 marks]
   (a) Define linear momentum. [1]
   (b) A trolley of mass 1.5 kg moves at 2.0 m s⁻¹. Calculate its momentum. [3]
   (c) Explain why the trolley slows down. [2]
   ```

   Each mark scheme still goes under its own question (7). Maktab does not check this for you: a question that
   starts in the wrong place comes in as the wrong question, so check each one against his file before you hand
   it back.
10. **A part is one line: its letter, its words and its marks**, as the paper prints it, however his file or a PDF
   broke it: `(a) State Newton's second law. [1]`, never `(a)`, `State Newton's second law.` and `[1]` as three
   paragraphs. **A part with sub-parts starts on the same line**, `(c) (i) For the collision in (b), state how the
   following apply:`, then `1. Newton's third law, [2]`, `2. the law of conservation of momentum. [1]` and
   `(ii) State, with a reason, whether the collision is elastic or inelastic. [1]`. A printed answer line takes the
   part's marks at its end: `change in momentum = ................ N s [2]`. A student reads this on a phone, and
   Maktab draws each part's marks at its line's right.
   **A mark scheme is typed the same way: each point keeps its code on its line**, `(a) (p =) mv C1`, then
   `Δp = 1.66 × 10⁻²³ N s A1 [2]`, and `(ii) kinetic energy (of ball and wall) is reduced so inelastic B1 [1]`. A
   line Cambridge gives no mark, `A0`, keeps it too: `Eₖ = p²/2m A0 [3]`. Where his file has its codes in a run apart
   from their lines (`M1`, `M1`, `A1` under three lines), put the first on the first line, the next on the next, in
   the order they stand. Where the lines and codes do not pair up, leave them where they stand: Maktab reads them in
   their order. This changes where a code stands, never which code it is. His worksheet's number over a scheme, `4.`,
   stays on a line of its own.
   **A part's letter with nothing under it is left out**: the `(b)` ending a scheme whose question holds only `(a)`,
   left when his copy stopped there. It is no line of his scheme (3), and with its words missing nothing can be
   marked against it.

11. **A formula is set, never left as Word's mathematical letters in plain text.** A PDF's or an old Word file's equation can
   copy as `𝐸𝑘= 𝑝2` with `2𝑚` on the next line, or a nuclide as `𝑈` with its numbers lost: the subscript, the power, the fraction's
   line and the numbers are gone, and a student reads that. Set it on one line, as the paper prints it, with Word's subscripts and
   superscripts: `Eₖ = p²/2m`, a fraction `a/b` with brackets where it needs them, a nuclide with its nucleon number as a superscript and its proton
   number as a subscript before its letter, and its equation on one line. Read each off the paper or his PDF, never working it
   out; where you cannot read it, write what you can see and add `[check: why]`, listed under *Check these*. Maktab reads these
   letters as they stand and warns him at the import, naming the line: it never guesses the formula.

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

**Never make an *Introduction* or *Summary* out of leftovers.** Lines that only describe his file (`Reference:`, `From
year 2023 till 2026`, `End of chapter`, `Best of luck!`) are not teaching: put them in a `Print only · ` box where they
stand, never under a Heading 1 *Introduction* or *Summary*, and make neither heading for them alone. In a file that is
one sub-topic's notes, his opening lines go under that sub-topic's *Start here*, not the topic's *Introduction*.

- **His glossary and his chapter summary go last**, under one Heading 1 **`Summary`** after the last sub-topic,
  wherever he had them: Maktab shows them on the topic's last page.
- **His answers section is never a block of its own**: each question's answers or mark scheme go under that
  question (*Past-paper questions*, 7); only a multiple-choice answer key may stay as his key. Never move answers
  under `Summary`.
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

**Never write a working note into a heading, a caption or his words**: no `(read from the chart, approximate;
check)`, `(continued)`, `(see note)` or `please fill in` of your own. A doubt is one `[check: why]` at the end, which
Maktab shows him as *Please check*; anything more goes in your note.

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
[VERSION](VERSION) file, written each time they are published. It stays in the header, on one line, and never runs into the first paragraph of his body. Leave his own header and footer as they are,
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
Answers: Q1 to Q40 his mark scheme, 86 mark points in his file and 86 here; Q41 and Q42 none in his file, so Maktab takes Cambridge's.
Could not do: none.
The lists are in my note and under "Changes made by AI".
```

**The `Answers:` line says of each past-paper question whose answer it is**, his scheme or none in his file, in runs of its number where they read alike, and his mark points counted in his file and in your copy. A copy that has lost his scheme then says so.

## Check your file before you hand it back

1. His words, pictures, tables of data, equations and answers are all there, unchanged, in his order: as many
   pictures as his file has, each on a line, each figure he drew in lines counted, a row of dots for writing on not counted, and every number with its decimal point; no paragraph deleted by its number. From a PDF: no sentence broken across lines, every superscript set, no page header or
   footer in the text, and every line holding `×`, `÷` or another symbol kept.
2. Every heading is a Word heading, not a table or bold text.
3. Every Heading 1 is a sub-topic's number and Cambridge title exactly, as the export or the course's skeleton has it, or is
   *Introduction* or *Summary*; every Heading 2 is his own title, with no number or with the number of
   the sub-topic it sits under, or a title you wrote marked `[check: title written by AI; …]`. A long part covering
   more than one idea is split, one idea per part, his words unchanged.
4. Every box is a one-cell table, or a label row over a body row, whose first line is one of the labels
   above, or `Box · ` and his title.
5. Every short question names its outcomes and has its answer, or a `Suggested answer:` you wrote, and no answer or
   mark scheme anywhere is only words in brackets.
6. Every past-paper question has its reference, its marks and its answer or mark scheme, and is in one
   sub-topic; no reference has words in brackets, and each mark scheme holds only its own question's answers,
   under that question, with no shared answers block left; his numbered answer pages are in it, under any heading, as many mark points as his file has. Each question starts at its own marker, with every
   part under it in his order, across page breaks, and no page header, footer or mid-sentence break inside it.
7. Every bulleted list is a Word bulleted list, every numbered list keeps his numbers, every multiple-choice option
   starts with its typed letter, and every picture is a pasted picture.
8. His teaching and every heading over it are all there; nothing only paper needs is deleted: Maktab knows it by its
   shape, or it is in a `Print only · ` box. His glossary and summary sit under `Summary`; no line only points to a
   printed book, and no reference to a question bank is left; the last heading is `Changes made by AI`, when you
   changed anything. No *Introduction* or *Summary* holds only lines about his file, and each *Start here* is about
   its whole sub-topic.
9. Every picture of a question or mark scheme has its `Words:` paragraph under it.
10. Each `[check: why]` is where you are truly unsure, with one plain reason; each `[could mislead: why]` is what you
    are confident could teach a student something wrong; in a table, both sit inside a cell. A `[keep as table]` line
    sits on its own just above a table of words that must be read across, and nowhere else. No heading or caption
    carries a working note of yours.
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
