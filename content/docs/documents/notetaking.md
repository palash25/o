+++
title = "Notetaking"
author = ["Hrishikesh Barman"]
date = 2018-11-11T21:49:00+05:30
draft = false
+++

<div class="book-hint warning">

> I've [a huge memory problem](https://www.youtube.com/watch?v=j_DshRUOm-o), i forget everything eventually so to retain information, note-taking is essential. This is a real problem for me, on top of that, years of constant use of social media has affected me in ways that i do not like.
</div>

Some random quotes on memory and notetaking that I like:

<div class="small-text">

> -   _So much of what we call creativity and intelligence is just memory. - Unknown_
> -   _Notes aren’t a record of my thinking process. They are my thinking process. – Richard Feynman_
> -   _What information consumes is rather obvious: it consumes the attention of its recipients. Hence a wealth of information creates a poverty of attention, and a need to allocate that attention efficiently among the overabundance of information sources that might consume it. ~ Herbert Simon_
</div>


## ICCES Loop {#icces-loop}

Let me introduce my very own ICCES loop. tbqh, i just put that abbreviation to sound cool, it's absolute shit. It is specific to how i function. On a regular day, this is happening to me in all kinds of ways so i decided to sort of formally define it here. It's a set of actions that can be applied to certain entities. Part of the reason this works for me is probably because I enjoy using it.

| Action      | Example entities                                              |
|-------------|---------------------------------------------------------------|
| Inspiration | Things that I am curious about, things that excite me         |
| Capture     | Link, Feeling/Moment, Idea/Suggestion/Project, Task, Question |
| Consume     | Link, Idea/Suggestion/Project, Question                       |
| Execute     | Idea/Suggestion/Project, Question, Task                       |
| Share       | Idea/Suggestion/Project, Feeling/Moment                       |

This by definition does not have a start and or end and can occur while reading some section in a book or while taking a shower. One is free to use any technique/tool to do the action on any of the entities.


### Inspiration {#inspiration}

For me curiosity and inspiration are more of less the same thing. They drive action. Without inspiration or curiosity, I can't even get started and if I am not curious about it, why even start.

-   🎵 : Podcasts before sleeping are great for inspiration. I use them as a proxy to get into hard and new topics. Pick some podcast where they do casual talk about some hard topic, makes me feel like huh, I can do that too(obviously I can't). But that kicks in the inspiration.
-   📚 : Casual reading of random topics
-   🍞 : Letting my mind just frolic into things.


### Capture {#capture}

Because we want to make unified operations, we will avoid application level capture. In other words, we want to **avoid** using twitter bookmarks, HN saved, browser bookmarks etc. Capture most of the time would be a secondary activity when you're doing something else. We would also want to link new captures to existing notes. When we take notes, we should ask: _“In what context do I want to see this note again?”_ when setting **tags**.

-   🖥 : org-capture, org-mode notes, org-roam.
-   🏃 : telegram dump channels(Journal `2d`, Links `1w`, Memes `1w`, TIL/TIFU `1w`), camera, screenshots
-   🐉 : multimedia into respective google drive
-   🔔 : prioritize at entry

<div class="book-hint info">

> note:
>
> -   plan to make a hybrid-image-board which should move my dependency on google drive
> -   till we don't have a good visual-board/image-board solution built, pinterest is a good substitute
</div>


### Consume {#consume}

Before consumption it is important to re-organize/re-order information for consumption. When consuming, it should be the primary activity. We also re-prioritize things at this step because it's the only sane way to decide what to work on.

-   📅 : periodically re-view, re-think, re-organize, re-prioritize captures.
-   🐝 : place information where it will be easily accessible while executing. eg. put things into anki.
-   ⚒ : build tools to help re-organize captures.
-   🍲 : actually consume, study, think, summarize. recurse.


### Execute {#execute}

Execution is the most important part. Creating content out of your notes is natural spaced repetition.

-   🍎 : apply what you consumed to something useful
-   👉 : take it the next level/form of it. write that post, ask that question, ship that project.

<div class="book-hint small-text info">

> Some ways to execute:
>
> Conversations • Essay • Recorded video • Mind map • Specialty document (PDF) • Pitch deck • Presentation • Talk / lecture • Group discussion • Product strategy • Object • Poem • Song • Memoir • Theater • Apparrel • Monologue • Video (AV) • Printed design • Zine • Culinary • Architecture • Interior design • Photography / art direction • Image • Token • Currency • Business • Syllabus • Interactive experience
>
> [jvns knows what's up](https://jvns.ca/blog/2023/04/19/new-playground-integer-exposed/)
</div>


### Share {#share}

Sharing is caring, share the good energy as much as you can.

-   🎷 : talk to people about what they are doing, learn from them. share your ideas.
-   📜 : share what you feel freely in which ever medium you prefer.


## Taking study notes {#taking-study-notes}

These apply to everything(lectures, papers, online articles, youtube videos etc)

```nil
┌───────────┐    ┌────────────┐   ┌────────────────────┐
│           │    │            │   │                    │
│   info    ├───►│ water down ├──►│  store in org-roam │
│           │    │            │   │                    │
└───────────┘    └────────────┘   └────────────────────┘
water down example:
These basically can keep changing and is sort of variable.
- Usage of snipd to take easy notes for podcasts
- Taking screenshots, I fr miss firefox screenshotGo
- Usage of hypothesis to do on-page highlighting/annotation
```

-   Whenever I study anything, it'll go to [the wiki](https://mogoz.geekodour.org/)(`org-roam`) in the end.
-   Whenever I study I should have access to 6 spaces:
    1.  Notes(topic 🐸) : The `org-roam` node
    2.  Notes(non-topic 🐣): `doom:scratch`
    3.  Questions(topic 🐸) : A section in the `org-roam` node
    4.  Questions(non-topic 🐣) :  `doom:scratch`
    5.  Feelings/rants/frustrations : `org-journal` / telegram journal which will be reflected at [diary](https://diary.geekodour.org/)
    6.  If anything is exciting enough, it can go to TILs(org/telegram) which then will be reflected at [todayi](https://ti.geekodour.org/) .
-   If taking physical written notes, can use Google Keep to convert them into digital notes which would later go into `org-roam`.


## Spaced repetition {#spaced-repetition}

With amazing search engines we do discover things quickly but as fast as the speed of thought? idk about that. Occasional resurfacing of concepts is super important for me. I DO NOT trust my memory at all. It betrayed me countless times, now my only best friend is spaced repetition.

My biggest weakness is probably the fact that I cannot survive in an unstructed world and real world is mostly unstructed. I tend to re-shape things my way before I even begin to work. So it took me a while(way longer than ideal simply because I never gave it more importance) to find an ideal spaced repetition flow.

{{< figure src="/ox-hugo/me_sleeping.jpg" >}}

Me at 18. Used to make sticky notes that I revised each morning and evening. Only later when I was lacking I realized how effective they were but they were hard to manage and everything. After a couple of years, I came across Anki and used it on and off. Eventually I started using emacs with org-mode and it had a very nice integration with Anki which made me re-consider for the long run this time.

-   I am using [org-anki](https://github.com/eyeinsky/org-anki) and I have AnkiDroid on my phone. (tip: don't use spaces in deck names)
    -   The actual anki application should be running for it work from emacs.
    -   Files are stored at `~/notes/org/anki`, each file is a deck.
    -   I want to keep these files version controlled, so if you update any Anki deck from somewhere else, make sure to import that deck first in emacs before making any changes to it.


## Context switching {#context-switching}

-   Lot of my time **and energy** actually goes into context switching.
-   Now that'll I'll be doing different things throughout the day, I need something that will ease up the switch. That clears up my mind for the new tasks, that removes any [zombie thoughts](https://www.uwb.edu/business/faculty/sophie-leroy/attention-residue) from the previous task.
-   Internet suggests batching similar tasks together and performing some ritual if it's a hard switch so that the brain realizes it's time to switch.
-   My ritual for hard switches: Wash face and legs, sit comfortably, listen to [gravity falls theme song(40s)](https://www.youtube.com/watch?v=X2DUpDxFJyg), mini stretch, get started.
-   If coming home from outside, first thing you do is put house clothes on and wash yourself. **This is very important for me.** Otherwise I am stuck in some loop.


## Resources {#resources}

-   Systems of other people
    -   [Ask HN: What is your system for learning new things? | Hacker News](https://news.ycombinator.com/item?id=34771415)
    -   [How To Remember Anything Forever-ish](https://ncase.me/remember/)
    -   [Designing a self-directed learning network](https://winnielim.org/experiments/learning/designing-a-self-directed-learning-network-work-in-progress-v0-1/)
    -   [About these notes](https://notes.azlen.me/g3tibyfv/)
    -   [JD](https://johnnydecimal.com/)
    -   [How I Build](https://pketh.org/how-i-build.html)
    -   [Timeful Texts](https://numinous.productions/timeful/)
    -   [The Information That Won’t Fit Inside Your Head](https://howaboutthis.substack.com/p/the-information-that-wont-fit-inside)
    -   [The Danger of Journaling IS Introspection](https://www.bramadams.dev/202302092341/)
    -   [The PARA Method](https://fortelabs.com/blog/para/)
-   References
    -   [§Note-writing systems](https://notes.andymatuschak.org/%C2%A7Note-writing_systems)
    -   [The Cornell Note Taking System – Learning Strategies Center](https://lsc.cornell.edu/how-to-study/taking-notes/cornell-note-taking-system/)
    -   [Mentat Wiki: Home Page](https://www.ludism.org/mentat/HomePage) : Lots of memory techniques here that I find too extra but whatever.
-   Others
    -   [25+ Years of Personal Knowledge Management.](https://www.dsebastien.net/2022-04-03-25-years-of-personal-knowledge-management/)
    -   [Literate programming is much more than commenting code](https://www.jmeiners.com/literate-programming/#bsubsets.js:77)
