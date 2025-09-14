# My Technical Learnings This Week: From Handy Extensions to AI-Workflows

It’s been a turbulent week, but one filled with technical discoveries and experiments. I want to share a few things I’ve been working on, from a new favorite tool to some deeper dives into automated testing and AI-powered documentation.

## My New Favorite Tool: Markdown to PDF

I’ve been creating a lot of Markdown files lately for newsletters and short documentation. While Markdown is fantastic for writing, I often need to share these documents in a more polished, portable format. That’s when I stumbled upon a fantastic VS Code extension: **Markdown to PDF**.

It’s simple, effective, and does exactly what it says. With a quick command, I can convert my Markdown files into beautifully formatted PDFs, ready to be emailed or shared. It even handles the Mermaid diagrams I’ve been embedding in my notes, which is a huge plus. You can also output to PNG or JPEG, which is useful for smaller snippets.

Even though the extension is no longer actively developed, it works flawlessly for my needs.

## A Spark of an Idea: Embedding Docs in Business Central

This new tool sparked an idea: what if I could embed these PDFs directly into a Business Central app? Imagine having a setup guide or detailed documentation available with a single click from within the application.

This could be a much richer experience than relying on tooltips alone. For customer-specific apps, where hosting public documentation isn't an option, embedding a PDF resource could be a clean and effective solution. It’s just an idea for now, but one I’m excited to explore further.

## Diving Deeper: The Challenge of Automated Testing

I also continued my journey with page scripting, trying to generate test code units from a YAML file. I have to be honest: I quickly learned that I’m not as deep into the topic of automated testing as I need to be.

This is a clear to-do for me for next week. I plan to dig into the Business Central Test Toolkit to properly understand how to generate automated tests from my YAML files. My goal is to get into a test-driven development (TDD) workflow. I’m convinced that writing tests as I go will not only improve the quality and maintainability of my code but also save me time in the long run when I need to make changes.

## Automating the Boring Stuff: From Voice to Scope Documents

The most exciting thing I’ve been tinkering with is a new workflow for creating scope documents from requirements. The core idea is to get from a requirement to a developer-ready task as quickly as possible.

We can often explain complex ideas much faster by speaking than by writing. So, why not use that to our advantage?

My experiment looks like this:
1.  Record a conversation (with a customer or consultant) where we discuss the required functionality and processes.
2.  Extract the audio and generate a transcript.
3.  Use a custom AI prompt to transform that transcript into a structured document, like a Product Requirement Document (PRD), user story, or feature request.

I’ve already tried a few different prompts and formats and gathered feedback from my colleagues. The initial results are promising, but there’s still work to do.

## The Art of the Prompt: A Lesson in Refining AI Output

The main feedback I received was that the output was often too long, with too much "fluff" and repetition. This highlights a crucial lesson in the world of AI: the quality of the output is directly tied to the quality of the prompt.

My next step is to refine the structure of my prompts to create more concise and useful documents. It’s a time-consuming process of trial and error, but it’s a fascinating challenge. Getting this right could significantly speed up our workflow from idea to implementation.

## What Are Your Thoughts?

These are the ideas and challenges that are occupying my mind right now. I hope sharing my process gives you some inspiration for your own workflows.

Have you experimented with similar tools or automation? Do you have any tips for getting started with automated testing in Business Central? Let me know in the comments!
