# Maktab's directions for AI agents

Maktab is the learning site of Barkat International College. Teachers export a topic as a Word file,
change it, and import it back. **That Word file is an interface**, and these are its directions: for
an AI agent helping a teacher bring her own material into Maktab.

## Start here

| You are asked to… | Read |
|---|---|
| Make a teacher's own lecture notes, worked solutions or past-paper booklet ready for Maktab, in his own layout | [own-file.md](own-file.md), with [sample-lecture.docx](sample-lecture.docx) |
| Put a folder of a teacher's notes, worksheets and slides into Maktab | [bulk-import.md](bulk-import.md) |
| Find a course's sub-topic numbers and outcome codes | [subjects/](subjects/): one page and one empty Word file per course, `subjects/9702.md` and `subjects/9702 skeleton.docx` |
| Change or add to an exported file in any other way | [topic-file.md](topic-file.md) |
| Decide whether a piece of material may go in at all | [provenance.md](provenance.md): read it every time |

**[topic-file.md](topic-file.md) is the format**, and every task but [own-file.md](own-file.md) follows it: that one keeps the teacher's own file. **The file you are
given always wins**: where it and these directions differ, follow the file and tell the teacher.

## For the teacher

Export the topic on the class materials page (**Export or import**), put the file in your folder,
and tell your AI agent:

> Make Maktab files from this folder, following github.com/Bhatti-Foundation/maktab-directions.

Then import what it gives back with **Export or import**. Maktab shows every change before anything
is added, and names any line that is not in the right shape.

To keep your own file and your own layout, attach the file, and the topic's export if you have one, and
tell your AI agent:

> Make this file ready for Maktab, following github.com/Bhatti-Foundation/maktab-directions.

It gives back the same file with its form changed, never your words, and a note of what to check.

## How these grow

- **One file per task**, all resting on [topic-file.md](topic-file.md). A new kind of job (a whole
  subject at once, a new topic) is a new task file, not a longer one.
- **A course's page, `subjects/<code>.md`**, and its skeleton are generated from Maktab's syllabus data;
  a subject's own rules (units, notation, a board's style) go on its page when it needs them.
- **Their version is the one line in [VERSION](VERSION)**, written each time they are published (the day and
  the commit: several publishes a day). An AI names it in the stamp it puts in a teacher's file
  ([own-file.md](own-file.md), *Stamp the copy*).
- **Every change is a line in [CHANGELOG.md](CHANGELOG.md)**, dated. A change to the format says
  which exports it applies to.
- These directions are kept in Maktab's own repository beside the code that reads the file, and
  published here.
