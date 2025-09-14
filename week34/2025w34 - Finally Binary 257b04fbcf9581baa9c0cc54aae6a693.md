# 2025w34 - Finally Binary

Date: August 24, 2025
Cover Picture: IMG_20250824_165907.jpg

# #1 Personal ✒️

## Personal Note

This week I’m back in the rhythm of publishing on a Sunday. I just came back from my first Road bike group ride. It was a blast. There is more to it but I will not tell you more about it now. May be a bit later. As currently is vacation time it is natural that there is less meetings and less new ideas by people. This week showed my I have more energy when I can focus on things for longer and do not get interrupted too often. I should really make it a habit to block time to focus in my calendar.

This weeks highlight was a project and a blog series that Jeremy Viska made public. It is a project and a series on a new way of working, integrating AI into the full workflow in development and solution teams. Really insightful and a lot to learn. As my old NAV trainer would say I will “copy with pride” as much as I can and adapt to my needs. Within my company we are also on the AI road and I can relate to so many topics and situations. I also realized there is a lot more to learn.

**Enjoy reading and don’t forget to leave some feedback.**

# #2 Tech 💻

## More productive with protocols and tools

Finally binary - for those of you who follow my blog will hopefully realize the analogy? For those new here go back to [2025w23 - I don’t speak binary](https://www.notion.so/2025w23-I-don-t-speak-binary-208b04fbcf9580e48cb5cf59039f89ee?pvs=21).

It just took me 11 (eleven) weeks to get there. Well not really speaking binary now but at least I’m getting close to it.

After reading a lot this week about AI workflows, especially while digging into https://nubimancy.com/ - I realized that I should have a closer look at MCP servers and their integration into development workflows. In my company I am sort of recognized as the “API guy”. Whenever there is an API involved and questions arise somehow my name gets into play.

Strange though that I have not tinkered around with MCP earlier. This week I found some time to do so an I also tried to learn and understand what is behind this technology - see section [#4 Inside AI 🤖](https://www.notion.so/4-Inside-AI-257b04fbcf958177ad2ada6e6aa750da?pvs=21) for more details.

So what did I actually do? Well one thing I have done already without really realizing was using the Microsoft Docs MCP Server when handing over coding tasks to the GitHub Copilot in vscode. I sometimes add “use docs” in my prompts to get input from the actual documentation without the need to actively search and browse it. The coding agent will do that for me (time saved).

Next thing I explored was the Azure DevOps MCP Server and I was quite impressed. It can read the wiki pages and work items, create branches and helped me with the commit. So what does that mean? Does it mean if a consultant creates a requirement specification document in the wiki and links it to a work item that I can then ask my Copilot to draft me a concept or help me with implementation of the task? → Yes, exactly. Great - I will tinker around a bit more and see if I can roll this workflow out to my team - which means less copy and paste around - clearer instructions and if there are questions during implementation the Copilot can formulate those and add comments to the task which the consultant can then answer if time allows. Questions can be in a specific format - depending on the instructions given to Copilot - which will it make easier to answer and then of course react on in the implementation.

The DevOps MCP is still in an early phase but it looks really promising. Hopefully the creation of wiki pages will soon be part of the toolset.

**What do you think? Is that something you could and would integrate into your team workflow?**

# #3 Sports, Food & Health 🏋️🚴🥦

## **A Sporty Week: Garden Work, Competition Prep, and the Breathing Hack**

This week was a mix of productive garden work, regular sporting activities, and intensive preparation for a new athletic challenge. A special aid, which I already know, has once again proven surprisingly helpful.

- **Garden work is also Training**
This week was quite a bit of **garden work**, which brings a surprising amount of physical activity and strengthening.
- **Preparation for the First 10-Mile Competition**
I am currently spontaneously preparing for a **10-mile run** – this is my first competition over this distance. It's an exciting goal, as I had planned to tackle this distance for some time. Although I don't take it too seriously, my Garmin tracker continued to show that I am only in shape and not evolving in training. The competition will take place next Saturday in a nature reserve, and I am curious how it will go. I will keep you posted next week.
- **Equipment in Focus: My Nasal Dilator in Practice**
This week, I noticed again how much equipment I use during training. Besides proven aids like my heart rate chest strap and Garmin watch, good running shoes and socks, and a sweatband, this week I also had my Shokz Open Run Pro 2 Bluetooth headphones with me. However, I particularly want to highlight the **nasal dilator** – a small insert for the nose that I have been using for a while.
    
    This "nose fan" has proven to be a **real game-changer for my breathing**. In the summer, I suffer from mild pollen allergies, which often clog my nose during exertion. With the dilator, my nose stays more open, I get **easier and more air**, which means **more oxygen**. This leads to **improved endurance**; I can last longer. My heart rate is also a bit lower when solely breathing through the nose. For **high-intensity sessions**, this is a great help. I am very grateful to my friend Sven for this recommendation.
    
    When cycling, however, I find the nasal dilator less practical, as blowing my nose on the go is difficult.
    
- **Sporty Week and Outlook**
Overall, it was a very sporty and successful week. Small aids like the nose fan can indeed make a difference. I look forward to telling you about my competition next week.

# #4 Inside AI 🤖

## MCP - the Model Context Protocol

Invented and established by Anthropic - https://www.anthropic.com/news/model-context-protocol - this protocol is simple and effective at the same time.

The idea is simple - your tech stack has a lot of different data sources - which today all have a sort of an API to retrieve data by a different application. But how should AI know all these different API’s and how to use them. Even for advanced engineers it is somehow difficult to connect two world together. Just because the schema is different, responses are not aligned and handover of parameters is wild.

MCP (Model Context Protocol) standardizes how AI systems connect to external data sources and tools, eliminating the need for custom integrations and reducing development overhead. The protocol provides secure, bidirectional communication through JSON-RPC 2.0 over multiple transport layers (stdio, HTTP, WebSocket), enabling AI assistants to safely access databases, APIs, and execute functions in real-time. By creating a universal interface between AI models and external resources, MCP significantly expands AI capabilities while maintaining security through proper sandboxing and permission models.

From my point of view (the API guy) that will be the future for integrations. No more hassle with different API’s - the vendor of the API understands their API best - so why not simply the query for the outside world. API’s will still be relevant - to serve the MCP servers or where speed is needed. But for simple data queries especially when it is documentation or text MCP and its connection versatility will be the game changer.

**Are you already looking into using MCP? What is your experience so far?**

# #5 Media of the week 🎶📺

This week I circled back to this playlist a lot. I have created this with songs that I really like and brighten up my mood - today I share this list with you. Enjoy:

[Happy Place](https://open.spotify.com/playlist/2DaH4qzjiLXYzC8Tvv0Qs8?si=w72Y5AehSJmwnPgwaY0fOQ)

# Feedback 📣

Here you can give me feedback, send ideas or just connect with me. Just leave a comment.

[https://tally.so/embed/waKjo9?alignLeft=1&hideTitle=1&transparentBackground=1&dynamicHeight=1&week_hidden=2025w34](https://tally.so/embed/waKjo9?alignLeft=1&hideTitle=1&transparentBackground=1&dynamicHeight=1&week_hidden=2025w34)

---

[Untitled](Untitled%20257b04fbcf95811ab6bdedf66bc9c642.csv)

---

©️ Christian Czupras - 2025