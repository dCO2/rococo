---
layout: project
title: "Project Mnemosyne: Augmenting Memory with Anki [#utility]"
feature-image: /assets/images/author-image.png
permalink: /:year/:month/:day/:title
tags: 
---

`project begin date: March 07, 2021`  
`project end date: Indefinite`  
`completion rate: 80%`  
`success rate: 70%`  
`remarks: work in progress`  

<details>
  <summary><h2>> List of Content</h2></summary>
  <ol>
    <li><a href="/2022/08/17/project-mnemosyne#1-intro">Intro</a></li>
      <ul style="margin-top:0; margin-bottom:0;">
        <li>What is Spaced Repetition?</li>
        <li>What is Anki?</li>
      </ul>
    <li><a href="/2022/08/17/project-mnemosyne#2-how-i-use-anki">How I use Anki</a></li>
      <ul style="margin-top:0; margin-bottom:0;">
        <li>Principles for thinking about Anki and other SRS systems</li>
        <li>Principles for writing good Anki notes</li>
      </ul>
    <li><a href="/2022/08/17/project-mnemosyne#3-attempts-at-using-anki-for-various-information-media">Attempts at using Anki for various Information media</a></li>
      <ul style="margin-top:0; margin-bottom:0;">
        <li>Using Anki to read the <b>Bitcoin paper</b>.</li>
        <li>Using Anki to learn a <b><i>Financial Markets</i></b> course.</li>
        <li>Using Anki to watch the <b><i>Avatar (2009)</i></b> movie.</li>
        <li>Using Anki to learn novels/stories</li>
        <li>Using Anki to read online articles</li>
        <li>Using Anki to learn music</li>
        <li>Using Anki to master exercises and movement.</li>
        <li>Using Anki to read books</li>
        <li>Using Anki to gain self-knowledge.</li>
        <li>Using Anki to learn history</li>
        <li>Using Anki to learn a language</li>
        <li>Using Anki to learn drawing.</li>
        <li>Using Anki to watch youtube videos</li>
      </ul>
    <li><a href="/2022/08/17/project-mnemosyne#4-miscellaneous-notes">Miscellaneous notes</a></li>
    <li><a href="/2022/08/17/project-mnemosyne#5-philosophying">Philosophying</a></li>
  </ol>
</details>

![](https://bucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com/public/images/23f25a7d-6375-4d45-bdaf-9a325b3cf5e8_3000x1625.jpeg)
_Silence of the Sea_ by Bang Hai Ja, 2005

## <a href="/2022/08/17/project-mnemosyne#" style="text-decoration: none;">1. Intro</a>
I began actively working on ways to improve my memory when I realized I could not learn anything properly and longterm without a kind of external structure—somewhere to "put" the many concepts I was learning, and something to help revisit them. The precise history of events escape me but reading <a href="https://andymatuschak.org/prompts/">Andy Matuschak's article</a> inspired me to actually begin work on the project I had been postponing.

The idea of human memory augmentation is a very broad and interesting one. Methods for improving memory can be medical as with the use of [Nootropics](https://en.wikipedia.org/wiki/Nootropic). Or creative as with the use of Mnemonics. Or even technological as with the use of systems that afford spaced repetition. The methods are various and the history is rich.

The history of improving memory with technology goes back a long way. From Douglas Engelbart in [Augmenting Human Intellect](http://augmentingcognition.com/assets/Engelbart1962.pdf) (1962) to Ted Nelson in [Complex information processing: a file structure for the complex, the changing and the indeterminate](https://dl.acm.org/citation.cfm?id=806036) (1965) to Tim Berners-Lee in [Information Management: a Proposal](https://w3.org/History/1989/proposal.html) (1989) to Piotr Wozniak and so on. If interested in a brief overview of this history, read Michael Nielsen's big and brilliant essay, <a href="http://augmentingcognition.com/ltm.html">Augmenting Long-term Memory</a>.

### What is Spaced Repetition?
Modern personal memory systems exploit the fact that if a piece of information is assimilated and then periodically retrieved/recalled at expanding intervals, then that information is likely to be assimilated for long-term, spanning years. This 'process' of 'recalling at ever expanding intervals' is termed spaced repetition. See [Spaced Repetition for Efficient Learning](https://www.gwern.net/Spaced-repetition) by Gwern for an indepth and almost academic look into the concept--The essayish article is also as <i>briglliant</i> as Michael Nielsen's.

This particular 'essay', on the other hand, is an index into the various thoughts I had while involved with the project of exploiting this fact. It should not be read as a thorough guide but a personal and impressionistic take (and experiment) on SRS systems.

There are now many technologies (apps and softwares and routines) that seriously expand on the idea of spaced repetition. One of them is Anki. It is an app. There is a mobile version and a desktop version. Another is [Orbit](https://withorbit.com/) currently in development by Andy Matuschak. This will really bring about big and important changes to the SRS space. Yet another is Space, Mnemosyne, SuperMemo, and so on.

For various reasons that will be explained in this essay, I chose to work with Anki--The mobile and desktop client.

### What is Anki?
[Anki is basically a todo-app on steroids](). This, though, is an oversimplification. (Pray the program engineers don't come for my head.) Anki helps schedule 'tasks' which are displayed as flashcards to the user. A task in this sense is the actual act of repeatedly recalling something. If, for example, you need to remember the name of an obscure animal you just discovered, you can create a 'task' that has a picture of the animal and regularly asks you—daily or weekly or specified by some deterministic formula—what its name is. Your job then is to provide the name by trying to recall it. A task is not limited to recall though. It could be a physical action you must perform such as an exercise. (We want to think about the concept of SRS systems unrestrictedly)

## <a href="/2022/08/17/project-mnemosyne#" style="text-decoration: none;">2. How I use Anki</a>

When you newly install the Anki desktop client, this is what you see:

![](/assets/images/anki-new-desktop.jpg)

The decks are like folders you use to separate groups of notes. In the image above, there is one deck and it is the ‘default’ deck.

A note is basically a question and answer pair. You provide both the question and the answer where, during review sessions, the answer is hidden and you are meant to recall it.

You provide a question. Like so:
![](/assets/images/anki-card-example-image-to-concept.jpg)

And an answer. Like so:
![](/assets/images/anki-card-example-image-to-concept-answer.jpg)

The above images were grabbed from my review session days ago. Depending on how easy it was to recall an answer, you choose from the `Again`, `Hard`, `Good`, `Easy` options which specify when next you want to see that question-note. See [Using Anki feedback options to make ideas salient]().

I could go on and give step-by-step instructions on how to create a card, how to create decks (and so on) but that's ineffective. There is an online [Anki manual](https://docs.ankiweb.net/) that documents how to use Anki in detail. What I'd do instead is give principles on how best to create a question/answer note and how best to organize Anki decks. (If interested in reading only the parts of the Manual that are immediately useful, See [Getting started with Anki - the bare minimum](/2022/08/31/getting-started-with-anki).)

After 1+ year of many organic changes, this is the current look of my Anki decks. It is unlike the deck in a newly installed Anki app. It has become stable for now:

![](/assets/images/anki-current.jpg)

I find that, on one level, separating decks into _‘Buffer’_ and _‘Limbo’_ helps differentiate the nature of things I'm learning. I named the first _‘Buffer’_ because the deck represents the group of notes I made for things I'm currently learning. _‘Limbo’_ on the other hand represents the group of things I plan on—but haven't started—learning.
The separation is important because Anki (and other space repetition softwares) are essentially _[a stream of urgent todos]()_. It is a stream because the various notes in the Buffer deck are always systematically moved into my attention-space. But if there are "notes/courses" you plan learning but don't have the time for yet, then they should go into Limbo. Limbo is where nothing happens. The notes there are not in my attention space yet. See [Anki is a pipe](/2021/12/20/anki-is-a-pipe).

The subdecks in the Buffer deck are separated by months because that way, I can decide to focus on just the notes I created when I learnt a specific thing for that month. It is also like a journal. I can reimagine the headspace I was in that month. See [How should anki decks be organized](/2021/12/20/how-should-anki-decks-be-organized).


### Principles for thinking about Anki and other SRS systems
- [Anki use is a skill]().
- [Anki helps you plant a thought](),
- [Anki as catalyst for habitual thought](), 
- [Anki as stream of urgent todos](), 
- [Anki is a bucket, not a pipe](),
- [Anki as hook for scaling steep learning curves]().
- [Anki as journal]().
- [Anki as a liquid library]().
- [Review sessions with Anki should be creative sessions]().
- [Anki helps move from an old thought to a recent thought so that moving from a recent thought to an old one becomes easier]()
  - In my review session today—29th August 2022, I was shown a particular note for a concept I had been thinking about. I created the note on the 7th of July 2022. This was before I had a conversation around the topic of the note with a friend recently—August 27th 2022. My mind did not think about the note when we had the conversation. I guess the note had been infrequent during my review sessions. But on seeing the note today, and meditating on it, my mind was reminded of the conversation I had had with my friend. This is basically a kind of serendipity, a salience of ideas--Anki fosters serendipitous living.
  - In this case, the old thought is actually old because it was "ankified".

### Principles for writing good Anki notes
See [A gallery of various personal notes](/2022/08/31/gallery-of-various-personal-notes).
- [a note should be atomic]() (focused or atomic)
- [a note should not be vague]()
- [a note should be tractable]()
- [a note should be effortful]()
- [make many fleeting notes]()
- [tag your notes by topic]()
- [a note should contain images where possible]()
- [create notes when you must]() (Do not learn if you do not [want to] understand)
- [refactor or delete notes that are big or stale]()


## 3. Attempts at using Anki for various information media

### [Using Anki to read the bitcoin paper]().
### [Using Anki to learn a course]().
<h3 style="display:inline;">Using Anki to remember movies</h3> See <a href="/2021/03/07/anki-remember-movies">Using Anki to remember movies</a>

### [Using Anki to gain self-knowledge]().
Using Anki to remember questions to yourself you might answer in the future
### [Using Anki to master exercises and movement]().
### [Using Anki to read books]()
### [Using Anki to read articles]()
### [Using Anki to learn history]()
### [Using Anki to learn novels/stories]()
### Using Anki to learn a language
### Using Anki to learn drawing.
### Using Anki to learn music
### Using Anki to watch youtube videos


## 4. Miscellaneous notes
- [Getting started with Anki - the bare minimum](/2022/08/31/getting-started-with-anki)
- [promised benefits of SRS systems]()
  - [useful for programmers and knowledge workers]()
  - [knowledge can accrete and you can learn more and become more productive]() Richard Hamming: "What Bode was saying was this: “Knowledge and productivity are like compound interest⁠.” Given two people of approximately the same ability and one person who works 10% more than the other, the latter will more than twice outproduce the former. The more you know, the more you learn; the more you learn, the more you can do; the more you can do, the more the opportunity - it is very much like compound interest. I don’t want to give you a rate, but it is a very high rate. Given two people with exactly the same ability, the one person who manages day in and day out to get in one more hour of thinking will be tremendously more productive over a lifetime. I took Bode’s remark to heart; I spent a good deal more of my time for some years trying to work a bit harder and I found, in fact, I could get more work done."
- [Anki vs. Readwise]()
- [Anki laziness]()
- [interacting with anki automatically schedules the hierarchy of difficulty when learning a linear course]()
- [create notes in anki first before refactoring them into obsidian when doing light/new research]()
- [create notes in obsidian first before refactoring them into anki when doing heavy/old research]()

## 5. Philosophying
- Is infinite memory desirable?
- Is long-term memory desirable? What even are the benefits?
- Can a case be made for forgetting?
- Can a case be made for forgetfulness?
- What might the future of SRS systems look like?
