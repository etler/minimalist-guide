# The Minimalist's Guide Writing Standard

Use this standard whenever creating a book in the **The Minimalist's Guide** series.

The series format is:

> **The Minimalist's Guide to [Topic]**

These are compact technical learning notes designed to build a precise mental model quickly and serve as a reference that can be shared with others.

## Writing Style

Write for clarity, precision, and information density.

Use plain, simplified technical English. Prefer the shortest set of statements needed to communicate the necessary information accurately.

Do not add filler, rhetorical flourishes, motivational language, jokes, or stylistic embellishment.

Do not repeat information unless repetition materially improves understanding.

A section may be one sentence when one sentence is sufficient. Do not expand a section merely to make it feel complete.

Do not sacrifice important information for brevity. The goal is **minimum necessary text**, not minimum text.

## Learning Approach

Build the reader's mental model incrementally.

Introduce each concept before relying on it.

Do not introduce several independent concepts in one section when they can be taught separately.

Prefer concrete examples over abstract explanations when an example makes the concept easier to understand.

Teach the smallest useful concept first, then build on it.

Do not jump ahead simply because a later concept is related.

When a distinction is important, make the distinction explicit rather than relying on context.

## Organization

Organize chapters around the natural conceptual progression of the subject.

Do not force every chapter into the same internal structure. Create sections where they improve comprehension; collapse them when they do not.

Before writing a chapter's content, first propose its section and subsection headings.

Do not write the chapter content until the user approves the outline.

After approval, use the approved outline as the starting structure, but collapse, reorder, or rename sections when doing so clearly improves the notes.

Each section should have a clear purpose:

* Introduce a concept
* Explain an important rule
* Establish a distinction
* Demonstrate a concept
* Compare related concepts
* Summarize a useful mental model

Avoid sections that merely restate previous material.

## Header Structure

The document title is always:

# The Minimalist's Guide to [Topic]

Each chapter uses a second-level heading:

## Chapter 1 — [Chapter Title]

Sections within a chapter use a third-level heading:

### 1. [Section Title]

Subsections use a fourth-level heading:

#### 1.1 [Subsection Title]

Continue this hierarchy throughout the document.

Do not introduce another `#` heading after the book title.

Chapter numbers and section numbers should remain sequential within the document.

Future chapters must be appendable directly after earlier chapters without changing the heading hierarchy.

## Choosing the Right Format

Use the simplest format that communicates the information efficiently.

Use prose for definitions, explanations, and short conceptual relationships.

Use bullet lists for compact collections of independent items.

Use tables when comparison is the primary purpose.

Use code blocks for actual code, configuration, commands, syntax, or structured examples.

Use Mermaid diagrams when relationships, hierarchies, dependencies, or flows are substantially clearer visually.

Do not use diagrams decoratively.

Do not use ASCII diagrams when Mermaid can represent the same relationship clearly.

Do not put ordinary prose or simple lists inside code blocks.

## Examples

Prefer the smallest example that establishes the concept.

Show only the parts relevant to the lesson.

Do not introduce additional features merely because they appear in a realistic example.

When an example contains something not yet taught, either omit it or explain it before relying on it.

## Comparisons

When two or more concepts are being compared, prefer a table when it reduces repetition.

For example:

| Concept        | A   | B   |
| -------------- | --- | --- |
| Purpose        | ... | ... |
| Representation | ... | ... |
| Scope          | ... | ... |

Follow the table with explanation only when the table cannot fully communicate the important distinction.

## Technical Precision

Separate concepts that are commonly conflated.

When useful, distinguish:

* Specification vs. implementation
* Abstract model vs. concrete representation
* Semantics vs. syntax
* Interface vs. implementation
* Standard vs. convention
* Required behavior vs. optional behavior
* Core functionality vs. external systems

Do not describe a convention as a requirement.

Do not describe an implementation detail as part of the abstract model.

Do not simplify away an important distinction merely to make a statement shorter.

When something is standardized at one layer but flexible at another, state the boundary explicitly.

## Mental Models

Use compact diagrams, tables, or short summaries to establish mental models when they reduce cognitive load.

Prefer formulations such as:

> X defines **what**; Y defines **how**.

or:

> X is standardized; Y is implementation-specific.

when that accurately captures an important distinction.

Do not force a slogan or formula when the subject requires more nuance.

## Terminology

Use the established terminology of the subject.

Do not invent alternative terminology when a standard term exists.

Define abbreviations before using them.

Once terminology has been established within a book, use it consistently.

If a convenient shorthand is introduced for the purpose of the notes, explicitly define what it means and use it consistently.

## Reference Quality

These are learning notes, not exhaustive documentation.

Include the information necessary to establish a correct mental model and understand the subject.

Omit incidental details that do not contribute to that model.

When accuracy depends on a distinction that is easy to get wrong, prioritize precision over brevity.

## Chapter Summaries

End chapters with a concise summary only when it provides a useful reference or mental model.

A summary should synthesize the chapter rather than repeat it.

Use a table, diagram, or a few compact statements when those communicate the summary more efficiently than prose.

## Overall Standard

The target is:

> **The shortest clear explanation that preserves the complete mental model being taught.**

Be concise, but never by deleting a distinction the reader needs to reason correctly.
