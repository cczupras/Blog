# Enhancing Workflow with Chat-Modes in Visual Studio Code

Archived: No
Favorite: No
Datum: September 8, 2025

# Summary

The speaker discusses the ease of creating blog articles through voice transcription while exploring efficient workflows using Chat-Modes in Visual Studio Code. They explain different modes like Ask-Mode and Agent-Mode, and how to create custom modes for specific tasks. The ability to link data from Notion and manage context with MCP-Servers for specialized tasks, such as documentation and coding, is emphasized. Future optimizations and the potential to reduce reliance on multiple AI tools for writing are also highlighted.

# Translated Transcript (English)

Yes, well, writing a blog article is super easy today. I'm sitting here in the nature reserve, on the bench, at the beach and I'm currently writing, or rather, I have to pause. I'm currently dictating my article. Yes, what did I do this week or last week to build the perfect workflow for further automation?

Yes, I watched a video about chat modes in Visual Studio Code. You already know that there is the Ask Mode, the Agent Mode, and the Edit Mode. But you can also add custom modes. It's quite simple.

You just add a Markdown file, Chat-Mode. md, to the GitHub directory, in the subfolder Chat-Modes. And Visual Studio Code has a new chat mode. I can set header properties via front matter in the Markdown file.

Then I can provide tools and specify that this agent only has access to the repo or only has access to various MCP servers. So that can be determined. Good practice is to not have too many MCP servers or too many tools, because then obviously too many tokens are used. Just for maintaining the tools to see which tool is the right one.

If I know I only want to use a specific set of tools, I create a dedicated chat mode for that. For example, if I want to document a process flow. Of course, I will then grant access to the repo, and I have the MCP server for Business Central, for the docs, for the documentation, so that the materials can also be referenced. Both combined then enable the chat mode to document efficiently.

In this chat mode, I can of course embed everything as a system prompt that the agent should do. So I can give it a description of what it is doing. Comparable to user stories and personas. I can then create a persona that is assigned to this role, tailored accordingly, and then I can implement it perfectly and provide the best possible chat modes.

This means I can assemble different agents that fulfill various tasks and easily switch between these contexts. For example, I could create a specialist that conducts code reviews. I could create a specialist that writes code, which in turn writes complex code, perhaps knows about interfaces, and I could then connect various sources to it so that it can act very purposefully. And of course, it can also generate output that I can produce.

Yes, these specialists have a very good template from Jeremy Whiska in the New Re-Mentory project, where he has essentially already built it. However, he is pursuing a different approach and incorporates it into the Copilot Instructions so that it can be evaluated accordingly. I tried to keep it in the structure and that in the chat mode only what file he should fetch additionally is included. Unfortunately, that didn't lead to the goal.

So it hasn't worked out. That's why I currently still have to fill the chat mode file completely with the Markdown instructions. Definitely very, very helpful when you know what task you want to do. Whether you want to code or document, that's already a significant difference.

And for that, I can switch to the corresponding mode and select accordingly. This naturally leads me to the idea of whether I can connect an MCP server to my Notion; can I then extract the data that I am currently speaking and transcribing through an automation from Notion? So far, I have been doing this manually by copying and pasting, but maybe I can optimize this and retrieve the data from an MCP server and directly tell the chatbot, okay, create a blog article from this. Based on the examples I provide, that is, based on my writing style, the spoken transcript, of course, doesn't read as smoothly, so it still needs to be rephrased.

I naturally use AI and various models to bring in some variations. But all of this is based on my original blog articles, which I still write by hand to ensure the same language is used, the same writing style, and the same scripting. I sometimes experiment with different instructions, but it would certainly help me a lot more and be significantly faster if I could just use this in Visual Studio Code, in my coding tool, and say, fetch the data from this article, from my Notion database, and write a blog article for this section. And maybe it would even be possible for it not to save the data in a separate file that I then have to manually insert and possibly reformat.

Ideally, I could also send it back directly to Notion. That would be the optimum. One could say that I could also use Notion AI to do this, but I simply don't want to use too many AI tools that I have to pay for. I just need to see how the workflow develops and how it crystallizes.

But that would be the approach. So, a few action points for me to research. A little something that you can perhaps take away as a learning. Chat modes, MCP tools, selection, to further enlarge the context window, because the more tools you use, the less context you have for the output, and the more limited the model is.

# Transcript (German)

Ja, also, Blogartikel verfahren ist heute ja super einfach. Ich sitze hier im Naturschutzgebiet, an der Bank, am Strand und schreibe gerade, bzw. muss ich parieren. Ich spreche gerade meinen Artikel ein.

Ja, was habe ich in dieser bzw. in der letzten Woche gemacht, um mir den perfekten Workflow zu bauen, um weiter zu automatisieren. Ja, ich habe ein Video gesehen über Chat-Modes im Visual Studio Code. Ihr wisst ja schon, es gibt den Ask-Mode und es gibt den Agent-Mode und es gibt den Edit-Mode.

Aber man kann auch Custom-Modes hinzufügen. Das funktioniert ganz einfach. Man fügt einfach eine Markdown-Datei, Chat-Mode. md, in das Github-Dateinis ein, in den Unterordner Chat-Modes.

Und Visual Studio Code kennt, ah, da gibt es einen neuen Chat-Mode. Ich kann über Front-Matter in der Markdown-Datei Header-Properties setzen. Und dann entsprechend Tools zur Verfügung stellen und sagen, dieser Agent hat Zugriff auf nur das Repo oder hat nur Zugriff auf verschiedene MCP-Server. Das kann man also bestimmen.

Gute Praxis ist, man sollte auch nicht zu viele MCP-Server, zu viele Tools haben, weil dann natürlich viel zu viele Tokens genutzt werden. Allein schon nur fürs Vorhalten der Tools, um zu gucken, welches Tool das richtige ist. Wenn ich weiß, ich möchte nur ein bestimmtes Set an Tools nutzen, mache ich dafür einen eigenen Chat-Mode. Als Beispiel, ich möchte einen Prozessablauf dokumentieren.

Natürlich gebe ich dann Zugriff auf das Repo und ich habe dann den MCP-Server für Business Central, für die Docs, für die Dokumentation, dass man die Sachen auch heranziehen kann. Beides kombiniert ermöglicht dann dem Chat-Mode, effizient zu dokumentieren. In diesem Chat-Mode kann ich natürlich alles als System-Prompt hinterlegen, was der Agent tun soll. Also ich kann ihm eine Beschreibung geben, was er tut.

Vergleichbar mit User-Stories und Personas. Ich kann dann halt entsprechend eine Persona kreieren, die zugeordnet ist, die entsprechend auf diese Rolle zugeschnitten ist und dann kann ich das perfekt umsetzen und kann dann bestmögliche Chat-Modes zur Verfügung stellen. Das heißt, ich kann mir verschiedene Agenten zusammensuchen, zusammenbasteln, die verschiedene Aufgaben erfüllen und kann dann einfach zwischen diesen Kontexten switchen. Das heißt, ich könnte mir einen Spezialist bauen, der Code Reviews macht.

Ich könnte mir einen Spezialisten bauen, der Code schreibt, der komplexen Code schreibt, der vielleicht Interfaces kennt und könnte denen dann verschiedene Quellen anbauen, dass die einfach sehr zielgerichtet darauf agieren. Und natürlich auch Output erzeugen, den ich dann herstellen kann. Ja, diese Spezialisten, da gibt es eine sehr gute Vorlage von Jeremy Whiska an dem New Re-Mentory-Projekt, wo er das im Prinzip schon aufgebaut hat. Er verfolgt allerdings einen anderen Weg und gibt das in die Copilot Instructions rein, dass das entsprechend evaluiert werden soll.

Ich habe versucht, das so zu behalten in der Struktur und dass in dem Chat-Mode nur drin steht, welche Datei er noch dazu holen soll. Das hat aber leider nichts im Ziel geführt. Das hat also nicht geklappt. Deswegen muss man aktuell noch die Chat-Mode-Datei komplett füllen mit den Markdown Instructions.

Auf jeden Fall sehr, sehr hilfreich, wenn man weiß, was man für eine Task machen möchte. Ob man jetzt coden möchte oder ob man dokumentieren möchte, ist das schon ein deutlicher Unterschied. Und dafür kann ich dann halt in den entsprechenden Mode setzen und auch entsprechend auswählen. Was mich natürlich zu der Idee führt, kann ich auch einen MCP-Server an meinen Notion anbinden, kann ich dann die Daten, die ich gerade einspreche hier und transkipiere über eine Automation, kann ich die aus dem Notion rausholen.

Bisher mache ich das einfach manuell per Copy und Paste, aber vielleicht kann ich hier auch noch optimieren und mir die Daten über einen MCP-Server holen und in den Chat-Bot direkt sagen, okay, mach mir daraus einen Blog-Artikel. Anhand dieser Beispiele, die ich vorgebe, also anhand meines Schreibspiels, ist das eingesprochene Transkript, das liest sich natürlich nicht so flüssig, das muss noch umformuliert werden. Da nehme ich mir natürlich KI zu Hilfe und verschiedene Modelle, um auch mal Variationen reinzubringen. Aber das alles basiert natürlich auf meinen ursprünglichen Blog-Artikeln, die ich noch per Hand geschrieben habe, damit die gleiche Sprache benutzt wird, das gleiche Sprachstil, das gleiche Scripting.

Ich probiere manchmal mit verschiedenen Instructions, aber es würde mir natürlich sehr viel mehr helfen und es wäre deutlich schneller, wenn ich das einfach in Visual Studio Code, in meinem Coding-Tool nutzen könnte und sagen könnte, hol dir die Daten aus diesem Artikel, aus meiner Notion-Datenbank und schreibe dazu einen Blog-Artikel für die und die Section. Und vielleicht ist es dann sogar möglich, dass er die Daten nicht in eine extra Datei speichert und ich sie wieder manuell einfügen muss und eventuell noch umformatieren muss. Vielleicht kann ich es auch direkt wieder zurückgeben ins Notion. Das wäre natürlich das Optimum.

Man kann jetzt sagen, ich könnte auch Notion AI nutzen, um das zu tun, aber ich möchte einfach nicht zu viele AI-Tools, für die ich bezahle, nutzen. Da muss man halt mal schauen, wie dann der Workflow ist, wie sich das herauskristallisiert. Aber das wäre der Ansatz. Also, ein paar Action-Punkte für mich zur Recherche.

Ein bisschen was, was ihr mitnehmen könnt vielleicht als Learning. Chat-Modes, MCP-Tools, Selektion, um das Kontextfenster noch zu vergrößern, denn je mehr Tools ihr anwendet, desto weniger Kontext habt ihr natürlich für den Output, desto beschränkter ist das Modell.

# Additional Info

## Main Points

- Creating blog articles through voice transcription can enhance productivity.
- Visual Studio Code supports various Chat-Modes, including custom modes for specific tasks.
- Proper management of MCP-Servers can optimize access to relevant tools.
- Integrating data from Notion can streamline the process of writing blog articles.
- Reducing the number of AI tools used can simplify the workflow and improve efficiency.

## Potential Action Items

- [ ]  Research ways to link MCP-Servers to Notion for automation (2025-09-09).
- [ ]  Explore additional resources on optimizing Chat-Modes and their applications (2025-09-15).
- [ ]  Implement a custom Chat-Mode for coding tasks to streamline workflow (2025-09-10).

## Follow-Up Questions

- What specific tasks can be improved with customized Chat-Modes?
- How can the integration of Notion and coding tools enhance the writing process?
- What challenges are there in managing multiple AI tools effectively?

## Arguments and Areas for Improvement

<aside>
⚠️ These are potential arguments and rebuttals that other people may bring up in response to the transcript. Like every other part of this summary document, factual accuracy is not guaranteed.

</aside>

- Relying on custom Chat-Modes might create a steep learning curve for new users.
- There may be limitations in the integration capabilities of existing tools.
- Using too many specialized Chat-Modes can complicate the workflow rather than simplify it.

## Related Topics

- ai-assisted writing tools
- automation in documentation
- integration of notion with development tools
- visual studio code customization
- workflow optimization techniques