# Checklist — real AI uses, prompt not published

These are ways the team actually uses AI. They are not in `publish/` because the prompt text was not available, or because publishing it would mean rewriting a prompt that only works with private names, voice, or numbers.

`prompt_found: false` on every item below.

## Founder-voice long-form video scriptwriter
- What we know: A full system prompt exists for turning notes into a long-form video script in one specific on-camera voice, with private tone and quote files. It cannot be handed to another company without rewriting it.
- Function: content
- Who to ask: Arturo (he maintains it). Sam also has a copy of the doc.
- Questions: What is the current full prompt? When do you run it (new script vs polish)? Claude project or Custom GPT? What do you paste in (title, notes, CTA)? Which lines only work because of private reference files and must stay out?

## Short-form script from a voice note (hook, explain, illustrate, teach)
- What we know: Arturo has a system prompt that turns a raw voice note into a 60–90 second script in that four-part shape. The export cut off before the last instruction, so it was not published.
- Function: content
- Who to ask: Arturo
- Questions: Paste the complete current prompt. When do you use it versus the long-form scriptwriter? Which tool? Is the call-to-action example tied to a private lead magnet that must come out? What does the user paste (transcript only, or links too)?

## Script review
- What we know: Joel noted on Oct 4, 2026 that Arturo has a prompt for script review, and the team was not sure where it is saved. No review prompt text was found, separate from the writing prompt above.
- Function: content
- Who to ask: Arturo
- Questions: Where is the review prompt saved? Paste it. What does “pass” look like? Do you paste the whole script plus notes? What must stay private (voice rules, offer names)?

## Founder-voice copywriter
- What we know: A saved system prompt writes email and social copy in one person’s voice, with that person’s rhythm and mantras. Removing the person removes the prompt.
- Function: content
- Who to ask: Joel
- Questions: Is there a version that says “match the writing samples I paste” instead of naming a person? If yes, paste that. If the only version is the named-voice one, leave it internal. Which tool is it saved in?

## Personalized founder coach
- What we know: A standing system prompt makes the assistant speak and advise as one specific founder, using private frameworks and a private knowledge file. It is not reusable as written.
- Function: leadership
- Who to ask: Dan
- Questions: Is any part of this meant for clients as “build your own coach,” and if so what is the blank version? What tool holds it? What knowledge file must never be copied into a client repo?

## Personal master prompt (content lead)
- What we know: A master prompt exists for one content lead. It includes role, team, pay, and revenue targets. It falls apart if those are removed.
- Function: leadership
- Who to ask: Joel
- Questions: Do you want a blank “interview me and write my master prompt” only (already published), or a sanitized pattern of the sections you use? Do not paste the current doc into the client repo.

## Saved custom GPTs for repeat jobs
- What we know: Public posts say custom GPTs exist for email, content, financial analysis, hiring, and strategy docs. The posts describe the habit. They do not include those five prompts. Hiring prompts from a later talk were published separately. These five were not.
- Function: operations (email), content, finance, people, leadership — one prompt each if they are different
- Who to ask: Dan
- Questions: For each GPT, paste the instructions, when you open it, what you paste, and what is private. If one is only a wrapper around a prompt we already published, say which.

## Content angles from the last week of work
- What we know: Dan described asking AI to read the last 7 days of calendar, messages, email, and meeting recordings, pull moments with a story or lesson, and frame each as a hook plus a format. The message describes the job. It does not include the prompt.
- Function: content
- Who to ask: Dan
- Questions: Paste the prompt you actually run. Which tools are connected? What should the output fields be? What must be stripped (private meetings, client names) before a client could run it?

## Morning verbal dump
- What we know: Dan talks through context and worries into an agent by voice, then sends it. No saved prompt text.
- Function: leadership
- Who to ask: Dan
- Questions: Is there a standing prompt, or do you just talk? If there is a prompt, paste it. Which voice tool and which agent?

## “Anything I need to know?” check-in
- What we know: With notifications off, Dan asks the agent what he needs to know before leaving. No prompt text.
- Function: operations
- Who to ask: Dan
- Questions: Paste the prompt if one exists. What sources does it read? What is it not allowed to send?

## Daily text digest of work in progress
- What we know: A morning text summarizes what he was working on across chats. Described as a system, not a prompt.
- Function: operations
- Who to ask: Dan
- Questions: What is the instruction the job runs? Which chats? What is excluded?

## Redesign the calendar around one goal
- What we know: Dan gave an agent a training load and a race date and had it rebuild the calendar. Different from the published calendar audit, which sorts the current week. No prompt text.
- Function: leadership
- Who to ask: Dan
- Questions: Paste the prompt. What do you attach (calendar, goal, constraints)?

## Where should I shift my time
- What we know: Dan asked Kai to analyze what he was doing and where time should move. No prompt text.
- Function: leadership
- Who to ask: Dan
- Questions: Paste the prompt Kai used. What data did it see? What must stay out?

## Forcing functions around goals
- What we know: Dan tells people to ask AI for forcing-function ideas around their goals. The line is a description, not a saved prompt.
- Function: leadership
- Who to ask: Dan
- Questions: Paste the exact prompt if you have it saved. What do you paste in with it?

## Who still owes me a reply
- What we know: Twice a week, an agent lists messages where he asked for something and got no reply. No prompt text.
- Function: operations
- Who to ask: Dan
- Questions: Paste the prompt. Which inboxes? How far back? What must it never chase (personal, legal, money)?

## Reply in chat as me
- What we know: With chat open in the browser, he tells the agent to read the thread and draft a reply as him. No saved prompt.
- Function: operations
- Who to ask: Dan
- Questions: Paste the prompt. Is send always manual? How does it learn the voice?

## Only what the CEO needs from the week’s messages
- What we know: A Friday pass that reads team messages “through the lens of the CEO” and returns only what he needs. The published team x-ray looks for overload and broken communication. This one is a personal briefing. The wording we have is a meeting note, not a saved prompt.
- Function: leadership
- Who to ask: Dan
- Questions: Paste the Friday prompt. Which channels? What should never be included?

## Context before a conversation
- What we know: Before picking up a thread or walking into a meeting, he has an agent search mail and build a short dossier on the person. No saved prompt.
- Function: operations
- Who to ask: Dan
- Questions: Paste the prompt. What do you paste (a name, a thread)? What private history must not be in a client version?

## Background check before a partnership
- What we know: Dan described a large saved prompt that flags issues to raise on a call. The prompt itself was not in the note.
- Function: leadership
- Who to ask: Dan
- Questions: Paste the prompt. What sources does it use? What must a client not copy (paid people-data tools, private notes)?

## Learn a topic from recent videos
- What we know: Recent videos on a topic go into NotebookLM, then he asks it to teach what it learned. Workflow, not a pasted prompt.
- Function: leadership
- Who to ask: Dan
- Questions: What exact question do you ask after the sources are loaded? How do you choose videos? Any prompt saved?

## Recency-locked research
- What we know: He asks a model that can see video to use only videos from the last 7 days. Described, not saved as a prompt file.
- Function: leadership
- Who to ask: Dan
- Questions: Paste the exact instruction. Which tool?

## Partnership or product background from the “best in the world”
- What we know: A described move: ask how the strongest platform in the world would solve this, or only consider tools from the last 7 days. Not a saved prompt.
- Function: leadership
- Who to ask: Dan
- Questions: Paste the prompt you actually use. What do you attach?

## Non-obvious insider tips
- What we know: A meeting note quotes a short ask for three nuanced insider tips. It was compiled as a hack, not stored as a prompt file, so it was not published.
- Function: leadership
- Who to ask: Dan
- Questions: If that sentence is the whole prompt, confirm it and say what you paste for the topic. If a longer version exists, paste that.

## Demand check before building
- What we know: Before committing, he asks what the market is looking for and wants a demand score. The note names an internal product. No generic prompt text.
- Function: marketing
- Who to ask: Dan
- Questions: Is there a prompt a client can run without that internal product? Paste it. What inputs (offer, audience, competitors)?

## Analytics questions
- What we know: He connects AI to site analytics and asks for the reports. No prompt.
- Function: marketing
- Who to ask: Dan
- Questions: Which reports do you ask for, in what words? What account access must stay private?

## “Should we do this?” from a social video
- What we know: He pastes a video link and asks whether the team should do it. The agent pulls the transcript and can scope a first version. No saved prompt.
- Function: content
- Who to ask: Dan
- Questions: Paste the prompt, including the line that stops it from scoping a huge build. What do you paste besides the link?

## Stories from memory
- What we know: He asks for stories about a theme that teach a lesson, short and sourced. No saved prompt.
- Function: content
- Who to ask: Dan
- Questions: Paste the prompt. Which memory or transcript store? What must not be published (private client stories)?

## Pure-give outreach, three options
- What we know: He asks for three outreach messages that feel like a gift, for someone who has a stage. Described, not saved.
- Function: sales
- Who to ask: Dan
- Questions: Paste the prompt. What do you include about the person? What must stay out?

## Fix this bottleneck
- What we know: He describes a workflow and the bottleneck and asks for options, then picks one. Meeting note, not a prompt file.
- Function: operations
- Who to ask: Dan
- Questions: Paste the prompt if saved. What do you attach (a loom, a doc, a list of steps)?

## Ask how, don’t assign the task
- What we know: Before a task, he states the goal and asks the model how to accomplish it, instead of prescribing the steps. Described as a habit.
- Function: prompting
- Who to ask: Dan
- Questions: Is there a saved sentence, or only the habit? If saved, paste it.

## If we started from scratch
- What we know: He asks how the work would look if AI did it first, or if he bought the company and started over today. Described, not saved.
- Function: leadership
- Who to ask: Dan
- Questions: Paste the prompt you use. What context do you attach?

## Sensors that text when something breaks
- What we know: He wants a weekly alert when a business number looks wrong, with a guessed cause and an offer to message someone. No prompt.
- Function: operations
- Who to ask: Dan
- Questions: Paste the instruction. Which metrics? Who is it allowed to message, and what needs a yes first?

## Compare models and cost
- What we know: He asks to run one task on several models and compare cost against result. No saved prompt.
- Function: operations
- Who to ask: Dan
- Questions: Paste the prompt. Which models? What task did you last use it on?

## Fix a screen from a screenshot
- What we know: He pastes a screenshot and asks for a visual fix. No saved prompt.
- Function: operations
- Who to ask: Dan
- Questions: Is the ask always one line, and if so what is the line? What design rules do you add?

## Write the agent identity file
- What we know: He does not hand-write an agent identity file. He describes the job and tells the model to create one, then edits. No template prompt.
- Function: prompting
- Who to ask: Dan
- Questions: Paste the sentence you use. What do you want in the file (name, job, limits)?

## Short-form hook patterns as custom instructions
- What we know: Spencer had a model study hook examples and added the patterns to a short-form ideation project. The note lists the patterns. It does not include the instruction block he saved.
- Function: content
- Who to ask: Spencer
- Questions: Paste the custom instructions. What examples did you feed it? Which tool is the project in?

## Yes Man prompt
- What we know: A public lead magnet called the Yes Man prompt is a gated doc. The prompt text was not in Slack or Notion.
- Function: content
- Who to ask: Spencer
- Questions: Paste the prompt. What is it for? What do people paste in? Strip any offer names before it goes in the repo.

## Human writing prompt
- What we know: A gated “human writing” prompt doc is used as a lead magnet. The text was not in Slack or Notion.
- Function: content
- Who to ask: Spencer
- Questions: Paste the prompt. When should someone use it? What must stay out?

## Customer-development prompt
- What we know: A gated customer-development doc is used as a lead magnet. The text was not in Slack or Notion.
- Function: sales
- Who to ask: Spencer
- Questions: Paste the prompt. Is it interview questions, a research plan, or both? What do you paste (offer, audience, transcripts)?

## Stack of personal agents (inbox, tasks, admin, analyst)
- What we know: Aubtin described five agents: a unified inbox that filters, a project manager for priorities, an admin for scheduling, and an analyst over the company systems. No prompts.
- Function: operations
- Who to ask: Aubtin
- Questions: For each agent, paste the instructions, the schedule, the inputs, and the hard limits. Which pieces only work because they are wired to private company tools?

## Rebuild chat layout from how you actually work
- What we know: Dan sent a prompt, plus a setup file and a hotkey note, that tells an assistant on your computer to study your chat app and simplify it. The search result cut off inside the prompt, and the attachment was not opened.
- Function: operations
- Who to ask: Dan
- Questions: Paste the full prompt and say which files must go with it. What is it allowed to change? What must it never post or delete?

## Daily AI briefing for a leadership role
- What we know: Nic asked Dan for the system prompt behind a daily AI update based on a role from leadership training. The prompt was not in the thread.
- Function: leadership
- Who to ask: Dan
- Questions: Paste the prompt. What does it read each morning? What should it refuse to include?

## Receipt inbox
- What we know: A finance page describes an inbox agent that matches receipts to card charges. The steps are a human process plus “ask the agent.” No reusable prompt.
- Function: finance
- Who to ask: Whoever owns that finance page (not named in the section that was read)
- Questions: Paste the agent instructions. Which card and bookkeeping tools does it assume? What must a client version not include?

## Onboarding plan from a sales call
- What we know: Chris described an agent that reads a sales call or a questionnaire and builds a first plan: top trainings, then a roadmap tied to goals. No prompt. The note is tied to private program names.
- Function: customer-success
- Who to ask: Chris
- Questions: Paste the prompt with program names removed. What do you paste (transcript, form)? What does the output look like?

## Follow-up questions for a book interview
- What we know: A book-interview template says follow-up questions are generated by a prompt, then edited by a person. The prompt text was not on the page that was found.
- Function: content
- Who to ask: Whoever owns the book interview template (not named in the search hit)
- Questions: Paste the generator prompt. What do you paste (prior answers, chapter goal)? What must it not invent?

## Research prompts for product ideas
- What we know: Dan posted a system prompt in an internal build channel for a researcher who proposes software products from market tailwinds, and a second custom-GPT prompt for an AI product architect. Only the openings were captured, not the full text.
- Function: leadership
- Who to ask: Dan
- Questions: Paste both full prompts. Which parts assume a venture studio (funds, internal product names) and must come out? If they only work inside that studio, say so and we will leave them off.

## Daily model of “how I want outputs”
- What we know: Posts tell people to set custom instructions for short bullets, no fluff, and a ban list of stock AI words. They do not include the actual instruction text.
- Function: prompting
- Who to ask: Dan
- Questions: Paste the custom instructions you actually use. Which tool? What word list do you ban?
