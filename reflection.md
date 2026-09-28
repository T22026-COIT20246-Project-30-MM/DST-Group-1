# Project Reflection

## GitHub Commits  
![Commits Screenshot](./images/total_Commits.png)  
  
![Commits Screenshot](./images/Graham_Commits.png)  
  
![Commits Screenshot](./images/Hans_Commits.png)  
  
## List of Tasks
  
Harden - Hans did 100%  
Network - Hans did 80%, Graham did 20%  
Plan - Hans 50%, Graham 50%  
Risk Assessment - Graham did 80%, Hans did 20%  
Security controls - Graham did 100%  
Reflection - Graham did 50%, Hans did 50%  
Presentation - Graham did 50%, Hans did 50%  


## Reflection on Commits and Tasks

**Hans:** Looking at the commit split (45 commits from me, 62 from Graham, per the graphs above), I trust that this reflects our agreed task allocation. Graham broke the project requirements down by week early on, and I volunteered for the sections I wanted to tackle. My workflow was to complete the bulk of a week's work before committing, so I have fewer commits and larger net change (793 additions to 211 deletions), while Graham's higher commit count includes many smaller, incremental saves to the same file. For example, `security.md` alone picked up 17 separate commits in a single day. Fewer, larger commits versus many smaller ones are just two different ways of working, not a measure of who contributed more.

On the commit history itself: the earliest few commits (under the `PASsword71` account) are the unit coordinator's, not a third group member. Dr Mohammad provided the initial project structure, including the folders, the template Markdown files, and the risk assessment spreadsheet, before either of us started committing our own work.

Commits happened across six consecutive weeks, with both Graham and I committing every week. Given the division of work set out in `plan.md`, I think this pace was sufficient. I understood what I needed to complete and commit by the end of each week for the project to stay on schedule. My own commits are heaviest around Weeks 7–9, which lines up with when I was working on the lab network setup and firewall rules, and the commit graph for that period confirms it.

## Reflection on Group Work

**Hans:** Our weekly Friday-night sync over Google Chat, with CQU Gmail for anything that came up in between (updates, questions, rescheduling), worked well in practice and not just on paper. A good example was our first call, where Graham broke the whole project down into weekly chunks. I volunteered for the sections I wanted. Something that would likely have taken much longer to negotiate over email got worked out in a single call.

One real issue I hit was around referencing my own AI use. During a call on 20 September, Graham asked me to provide links to the resources I'd used to complete the `network.md` and `harden.md` sections, and at that point I hadn't documented this anywhere in the project. Given the project specification's requirement (Section 5.3) to acknowledge AI as a source when it provides key knowledge, leaving this undocumented could have cost the group marks on an integrity requirement, not just a formatting one. After reviewing the spec, I put together a proper disclosure of my AI use in `ai-assistance-log.md`, and added acknowledgement lines in `network.md` and `harden.md` pointing back to it.

That same review turned up a more specific problem worth describing on its own: one paragraph in `network.md`'s OpenWRT/VirtualBox setup section had originally come from an AI-drafted planning document and been committed almost word-for-word. To fix it properly, I broke the paragraph down into the individual facts it made, answered each one myself in my own words, and went through several rounds of review before they were accurate, catching, among other things, a wrong MAC address and a backwards explanation of how NAT was (or wasn't) involved. Only once every fact checked out did I combine my own answers into the final paragraph now in `network.md`. This is documented in full in `ai-assistance-log.md`.

Based on that experience, I'd recommend that group members track the resources they use to complete their assigned tasks as they go, whether that's lecture notes, websites, or AI, rather than reconstructing it after the fact. Noting sources at the point of use, directly in the write-up for that section, would have avoided the scramble to reconstruct an AI-use history a few weeks later.

On task allocation: I think the division of work recorded in the project plan gave us clear, non-overlapping ownership of tasks from early on, and I wouldn't change how that was split.
