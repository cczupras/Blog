# When DMS App Development Forces You to Break Your Own Rules

Some weeks ago, I wrote about a Document Management System (DMS) app I've been building for a customer. I was quite excited to share that I had completed the first release candidate and deployed it to the test system. And you know what? It worked – it actually worked fine! Sure, there were a few minor issues that I missed during testing (as is always the case), but we quickly fixed those, and I was genuinely happy with how everything was functioning.

## When Requirements Evolve Mid-Development

Then came the twist in the story – a new requirement emerged. The system now needed to handle not just the main document but also attachments. We're talking about managing multiple documents per Business Central purchase invoice, for example.

Here's the frustrating part – I knew from the beginning that attachments would eventually be part of the system. But in my initial concept, I didn't fully implement this functionality because I naively thought, "It's just another document to upload, right?" Wrong. Very wrong.

## The Love-Hate Relationship with Interfaces

Having finished the app and implemented quite a lot of interfaces (which I generally love), I've come to realize something: interfaces are like contracts, and you're not allowed to break contracts. That's where my relationship with them becomes complicated.

Now that I need to implement functionality for attachments, I'm facing the reality that I need to make some breaking changes and rework almost the entire app. I need to create a path for the attachments and add the ability to distinguish between a main document and multiple attachments.

This has been quite the mental challenge to work through, I'll admit. After thinking it through, I believe I've figured out a solution – but it means breaking every single interface I created.

## Refactoring for the Better

The silver lining here is that I'm actually implementing more procedures into the interfaces, which is ultimately better for the architecture. I'm essentially refactoring the app to make it stronger and more robust.

Fortunately, this app isn't yet in a production environment, which means I have some flexibility. I can bend the rules a bit and make breaking changes without going through the usual rigorous processes. This is precisely the part where I don't love interfaces – when you make a mistake, it requires significant work to create an interface version 2 or a completely new interface, then rework everything to ensure you don't break anything data-wise.

But in this case, I'm lucky. I can make these changes without too much fallout.

## Exploring AI Assistance for Optimization

Before I wrap up this project, I'm considering asking Copilot to help me optimize the interface usage and procedures. I've already refactored quite a lot of procedures, but I'm curious to see what an AI assistant might suggest and whether those suggestions will actually improve the codebase.

Will the copilot spot patterns I've missed? Will it suggest more elegant solutions to my interface challenges? I'm genuinely intrigued by what might come from this experiment, and I promise to share the results once I have them.

## The Lesson Learned

If there's one thing I'm taking away from this experience, it's to be more thorough in my initial concept development – especially when I already know certain features will be needed down the line. Interfaces are powerful tools in development, but they require careful planning to avoid the exact situation I'm in now.

What about you? Have you ever found yourself having to break your own architectural rules mid-development? How did you handle it? I'd love to hear your experiences in the comments below.
