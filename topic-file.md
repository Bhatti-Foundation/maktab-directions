# The topic file

One Word file (.docx) holds one topic of one class's materials. The teacher exports it from Maktab;
you change it; she imports it. **You cannot make one from nothing**: its first line proves which
class and which version it came from. Ask for her export if you were not given one.

## Never change

1. **The grey first line**, character for character. It begins `Downloaded on` and ends
   `· stamp …`. Keep the file's custom document properties too.
2. **A sub-topic heading** (Heading 1, `4.1 Turning effects of forces`): never add, rename,
   renumber or remove one. Sub-topics are changed on the class materials page.
3. **A place heading** (Heading 2): the six below, in their order.
4. **The yellow *How to edit this file* box**, and the *For an AI agent* box at the end of the file.

**Add; never remove.** What the file already holds stays as it is, even where it breaks a rule
below. The grey *Add questions here…* line in an empty place may stay or go when you add a
question there.

## The shape

```
Downloaded on … · stamp …                      grey first line
4 Forces, density and pressure                 Title
[How to edit this file]                        yellow box
4.1 Turning effects of forces                  Heading 1, one per sub-topic
  Text                                         Heading 2
    4.1.2 The moment of a force                Heading 3: a learning outcome's code, then words
    paragraphs, and boxes
  Lesson video                                 Heading 2, a table
  Textbook                                     Heading 2, a table
  Past papers                                  Heading 2, a table
  Practise                                     Heading 2, questions
  Quick check                                  Heading 2, questions
4.2 …
```

## Text

- **A Heading 3** starts with the learning outcome's code: `4.1.2 The moment of a force`. Use only
  the outcomes of the sub-topic it sits in. Add material under the heading for its outcome, after
  what is there. A new Heading 3 only for an idea no heading in that sub-topic covers.
- **A paragraph** is a Normal paragraph, one idea.
- **A box** is a table of one row and one cell, shaded, whose first paragraph names its kind in the
  *Box label* style, bold:

  | Kind | What it holds | Shading |
  |---|---|---|
  | `Worked example` | A problem with its working | `DEEAF6` |
  | `Lab` | A practical or experiment | `E2EFDA` |
  | `Teacher's note` | A remark for teachers; **students never see it** | `FCE4D6` |
  | `Figure` | A picture pasted into the box, and its caption as the box's words | `F2F2F2` |
  | `Video` | Its title, then its link (`https://…`, YouTube or Vimeo) on a line of its own | `F2F2F2` |
  | `Reading` | Its title, then its link (`https://…`) on a line of its own | `F2F2F2` |

  A title for the box, if it has one, is a plain paragraph just under its label. If the file has no
  box of that kind to copy, copy the yellow *How to edit this file* box, change its label and words,
  and set the shading above. Leave an empty paragraph after each box, so two boxes stay two.
- **A picture** comes in where it stands in a sub-topic's *Text*: on a line of its own between
  paragraphs, or in a *Figure* box to give it a caption. Paste the picture itself (PNG or JPEG); a
  chart, a shape or a linked picture does not come in. A *Figure* box with no picture is refused. A
  picture anywhere else (before the first sub-topic, in a table, in a question) stays out.
- **A video or a reading** is a *Video* or *Reading* box under the heading it belongs to. A box with
  no link is refused. A figure, video or reading that is already in the file stays as it is: never
  paste a picture into a *Figure* box that was there.

## Lesson video, Textbook, Past papers

Tables whose first row is the header: *Title · Link · Opens at*, *Title · Link · From*,
*Paper · Questions · Link*.

**Today a file changes a row that is there, but cannot add a row.** A new video, reading or past
paper goes in your note to the teacher, with its title and link, to add on the sub-topic's page.

- **Link** starts with `https://`.
- **Opens at** is minutes and seconds (`24:13`), or empty for the beginning. YouTube's `t=1453s` is
  `24:13`.
- **Questions** are numbers only: `3, 7`.
- One video is one row: the same YouTube video at another start time is not a new video.

## Practise and Quick check

```
Question 13 · 4.1.3, 4.1.4       Heading 3: Question, its number, ·, its outcomes, comma-separated
The question, as paragraphs. Parts (a), (b) are paragraphs of one question.
Answer: 0.48 N m                  one line; parts' answers together: (a) …; (b) …
Working:
torque = F × d                    one line each, in the Working style
= 12 × 0.040
Marks: 3                          a whole number, the total; leave empty if she gives none
```

Number new questions on from the last in that place. Use only the outcomes of the sub-topic the
question sits in. **Practise** holds full questions; **Quick check** a few short ones that check
understanding.

## Making the changes

Edit the exported .docx itself and copy the shapes in it. **python-docx's table API fails on this
file** (its tables have no `w:tblGrid`); copy table and paragraph elements at the XML level.

## Check your file before you hand it back

1. The first line and the custom properties are unchanged.
2. Every Heading 1 and Heading 2 is the same, in the same order.
3. Nothing that was there is gone.
4. Every new link starts with `https://`; every *Opens at* and *Questions* is in the shape above.
5. Every outcome code you wrote belongs to the sub-topic it is in.
6. Every box's first line is one of the kinds above, spelt exactly.
7. Every new picture is pasted as a picture, and every new *Video* or *Reading* box has its link.
