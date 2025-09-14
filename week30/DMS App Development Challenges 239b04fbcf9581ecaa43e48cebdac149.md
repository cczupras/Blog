# DMS App Development Challenges

Archived: No
Favorite: No
Datum: July 23, 2025

# Summary

The speaker discusses challenges faced while developing a Document Management System (DMS) app, including the need to add functionality for handling attachments alongside main documents. This required significant rework and breaking changes to existing interfaces, though the app is still in testing. The speaker is optimistic about refactoring for better structure and potential optimization assistance from code copilots.

# Transcript

Some weeks ago, I wrote about that DMS app that I'm building for a customer and I had the first release candidate done and we've published it into the test system or deployed it into the test system and Yeah, I mean it worked, it worked fine. There were here some little things that that I missed in the testing like normal so we fixed that and Yeah, I'm pretty happy with how it how it works and now there's a there's another requirement Not just to send the main document But also attachments so having multiple documents per BC purchase invoice, for example And I knew that from the beginning that there will be attachments And then I created I didn't implement it in the concept In total because I thought it's just another document to upload Yeah, then now having finished the app and having used quite a lot of interfaces well, I love interfaces and then I don't love interfaces because they are like contracts and You're not allowed to break contracts And now that I have to implement the functionality for the attachments that I need to send them over I need to do some breaking changes and rework almost the complete app To have that pass for the attachments also, so be able to distinguish between

a main document and multiple attachments Yeah, that was quite a mental challenge to think through this thing and I Think I figured it out now what to do, but I broke every every single interface and Actually now that I have implemented more procedures into the interfaces Which is which is better so I'm refactoring the app for better and luckily this app is not Yet in production interface and yet not yet in production Environment so I can bend the rules a bit and do breaking changes Without doing all the stuff that so that's the part where I don't love the interfaces when you did a mistake It's kind of bit of a work to do an interface version 2 or a new interface and Then rework that all through and make sure that you don't break something data-wise Yeah, but I'm lucky here so I can do this Yeah, and I think before I'm done I have now Refactored quite a lot of procedures. I might ask the copilot to see If it can help me Optimizing the interface usage optimizing the procedures Just curious what what it what it will do and if that helps Let's see I will I will let you know

# Additional Info

## Main Points

- The DMS app has progressed to a release candidate and is deployed in the test system.
- New requirements include handling multiple attachments per document, necessitating rework.
- Implementing required changes led to breaking existing interfaces, which the speaker finds challenging.
- The speaker is optimistic about opportunities for improvement and refactoring.
- There’s potential for the copilot to assist in optimizing the interface usage.

## Potential Action Items

- [ ]  Refactor the app to accommodate the new attachment requirements before moving to production (2025-07-30).
- [ ]  Explore using a copilot for optimizing interface usage and procedures (2025-07-30).
- [ ]  Document changes made to interfaces to maintain clarity and track modifications.

## Follow-Up Questions

- What specific challenges did you face while implementing attachment functionality?
- How did the interface changes impact the overall app structure?
- What optimizations do you expect from the copilot?

## Arguments and Areas for Improvement

<aside>
⚠️ These are potential arguments and rebuttals that other people may bring up in response to the transcript. Like every other part of this summary document, factual accuracy is not guaranteed.

</aside>

- Reworking interfaces may lead to longer development times and potential bugs.
- Breaking changes can affect integration with existing systems.
- Relying on copilots might introduce dependencies on external tools.

## Related Topics

- document management systems (dms)
- interface design and management
- refactoring code
- software development methodologies
- testing in software development