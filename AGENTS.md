# The Minimalist Guide Writing Standard

Use this standard whenever creating a book in the **The Minimalist Guide** series.

The series format is:

> **The Minimalist Guide to [Topic]**

These are compact technical learning notes designed to build a precise mental model quickly and serve as a reference that can be shared with others.

## Writing Style

Write for clarity, precision, and information density.

Use plain, simplified technical English. Prefer the shortest set of statements needed to communicate the necessary information accurately.

Do not add filler, rhetorical flourishes, motivational language, jokes, or stylistic embellishment.

A section may be one sentence when one sentence is sufficient. Do not expand a section merely to make it feel complete.

Do not sacrifice important information for brevity. The goal is **minimum necessary text**, not minimum text.

### Sentences

* Use short, direct sentences. Keep related clauses together when they express a relationship more clearly than separate sentences.
* Prefer direct verbs and familiar technical language. Remove wording that adds length without adding meaning.
* Make clear what each statement refers to. Repeat a name when needed to avoid ambiguity.

### Passages

Begin directly with the concept, rule, or example being taught. A code example or table may introduce the point without an opening sentence. Add only the explanation needed to understand it. Do not include conversational text or repeated conclusions.

Keep each passage focused on one teaching purpose. Group details by what the reader needs to understand together.

Give each fact one primary home. Refer to that explanation when needed. Repeat information only when applying it in a new context or deliberately reinforcing understanding or retention. A new chapter is not, by itself, a reason to repeat earlier material.

## Learning Approach

Build the reader's mental model incrementally.

Establish what each new concept is and what role it serves before relying on it in another explanation or example. Naming a concept or showing its syntax does not establish that understanding.

Do not introduce several independent concepts in one section when they can be taught separately.

Prefer concrete examples over abstract explanations when an example makes the concept easier to understand.

Teach the smallest useful concept first, then build on it.

Do not jump ahead simply because a later concept is related.

When a distinction is important, make the distinction explicit rather than relying on context.

## Organization

Before drafting a guide, outline its chapters to establish the overall learning progression. Before drafting each chapter, outline its sections and any needed subsections to work out how that part of the progression will be taught.

Use these outlines to resolve ordering, prerequisites, and conceptual boundaries before writing the content in full. Together, they should tell a coherent learning story in which each part builds toward the intended mental model.

### Guide and Chapter Structure

Establish the reader's starting knowledge and what the guide should enable them to understand or do. Give each chapter a distinct contribution toward that outcome.

Compare proposed coverage with existing chapters. Identify what new understanding each chapter adds and which earlier concepts it assumes.

Choose an organizing structure that fits the subject: conceptual dependencies, a process, cause and effect, a hierarchy, or another meaningful relationship. Do not impose a lifecycle or copy a reference document's organization merely because it is available. Preserve cycles and interacting relationships when a linear sequence would misrepresent them.

Split chapters where there is a useful conceptual boundary and each resulting chapter has a coherent learning purpose. Length informs pacing; it does not determine the boundary. Keep material together when splitting it would fragment an explanation or require substantial repetition.

### Sections and Subsections

Within each chapter, order sections by what the learner needs to understand next. When variations depend on a shared mechanism, establish that mechanism through a simple, complete case before introducing the variations.

Use section boundaries to distinguish meaningful learning steps. Use subsections when a step contains parts that benefit from separate treatment. Important distinctions may deserve separate sections even when their explanations are short; closely connected ideas may fit best together.

Do not target a particular number or size of chapters, sections, or subsections. Do not force parallel topics into matching structures.

Each section should have a clear purpose:

* Introduce a concept
* Explain an important rule
* Establish a distinction
* Demonstrate a concept
* Compare related concepts
* Summarize a useful mental model

Headings should identify the actual teaching purpose. When revisiting a familiar concept, make its new role clear rather than presenting its definition again.

### Outline Review and Approval

Before presenting an outline, walk through it from the learner's perspective: what must they know on entry to each part, what will they learn there, and why does it belong at that point? Resolve missing prerequisites, including those hidden in examples, terminology, and comparisons. Check for overlapping purposes and topics included only for apparent completeness.

Take responsibility for recommending a sound scope and progression. Ask the learner about their goals and familiarity when needed; do not rely on them to detect gaps in a subject they are learning.

Present the chapter outline for user approval before writing its content.

After approval, use the approved outline as the starting structure, but collapse, reorder, or rename sections when doing so clearly improves the notes.

## Header Structure

The document title is always:

# The Minimalist Guide to [Topic]

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

Do not describe an implementation detail as part of the abstract model.

Do not simplify away an important distinction merely to make a statement shorter.

When something is standardized at one layer but flexible at another, state the boundary explicitly.

Do not present a convention or implementation choice as a requirement of a specification.

Make clear whether behavior is required or optional.

## Mental Models

Use compact diagrams, tables, or short summaries to establish mental models when they reduce cognitive load.

Prefer formulations such as:

> X defines **what**; Y defines **how**.

or:

> X is standardized; Y is implementation-specific.

when that accurately captures an important distinction.

Do not force a slogan or formula when the subject requires more nuance.

## Terminology

Use the subject's established terms and the names used by the system being described. Use one term per concept; do not introduce synonyms for variety.

Define new technical terms and abbreviations before relying on them. Prefer direct definitions such as "X is Y." Account for the intended reader's prior knowledge and terms established earlier in the guide.

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

## Revision and Review

Use feedback to improve the explanation and its progression. The revised text must stand alone without requiring the reader to know the discussion that produced it.

When a claim changes, replace the old explanation. Do not append a qualification that requires the reader to reconcile both versions.

Before delivery, review the writing against this standard as well as checking accuracy and coverage. Revise organization as needed; sentence edits alone cannot fix a structural problem.

## Overall Standard

The target is:

> **The shortest clear explanation that preserves the complete mental model being taught.**

Be concise, but never by deleting a distinction the reader needs to reason correctly.
