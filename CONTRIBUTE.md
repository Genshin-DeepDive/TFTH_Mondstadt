# *Tales from the Hoyoverse* Contribution Guide
<sub>Created by [u/Genshin_DeepDive](https://www.reddit.com/user/Genshin_DeepDive/)</br>
Last updated 11 January 2026
</br>

## Why Contribute?
As you can probably imagine, the scope of a project like *Tales from the Hoyoverse* is immeasurably massive.  Let's take a quick look at how much potential text content there is within just *Genshin Impact*.
- *Genshin Impact* has 43 Archon Quests (as of Luna II), each taking anywhere from 20 minutes to three hours to complete for the average gamer.
- This translates to an average Archon quest length of about 1hr40m.
- That average length across all 43 Archon Quests becomes nearly 72 hours of gameplay, *minimum*.
- On average, drafting an outline in real time requires about five minutes of effort for each minute of gameplay.
- Taking that 5:1 ratio into account, this means 360 hours of effort just to *outline* the Archon Quests.
- You can roughly double that ratio for inserting dialog from the Wiki and transcribing cutscenes, which makes up the "prose" version of the text. (We're up to 1800 hours now.)
- You can then roughly double that one more time to narratively arrange and link all of that content together.  3600 hours, but who's counting?
- Lastly, a 20% bonus on top of that 3600 hours will allow for finessed editing, synonym hunting, and a final pass over the content, bringing us to an eye-watering ***4,320 hours of work***.
- Don't forget that none of this accounts for social media management, handling the Git project and repos, or any other work.
- Oh, and in case it's too easy to forget, the primary authors Genshin_DeepDive and 4StarGoose have full-time jobs.

So what does that mean?  Well, just to get the *Archon Quests only* into a narrative format, we're talking **4,320 hours** of labor.
Splitting that into two hours per weekday plus 4 hours a day on the weekends, that's 240 weeks of labor, or ***FOUR AND A HALF YEARS*** to completion.
Don't even get me started on World Quests, Story Quests, and Hangouts.

***There's a reason MiHoYo hires a full writing team.***

## Understanding *TFTH*'s Format
Let's take a look at the format of *Tales from the Hoyoverse* so you can better understand its scope and where work is needed.

- A complete *Tales from the Hoyoverse* compilation would consist of one collection of volumes for each Hoyoverse property, covering
  - _Honkai: Impact 3rd_
  - _Genshin Impact_
  - _Honkai: Star Rail_
  - _Zenless Zone Zero_
  - and future releases
- Each of these compilations would consist of a volume allocated for each major region or story split in the game (such as Inazuma in *Genshin Impact* or Penacony in *Honkai: Star Rail*)
- Each of these volumes would then be split into two collections, one detailing the critical story path (such as Archon Quests in *Genshin Impact*) and the other detailing bonus content (such as *Genshin*'s World Quests, Story Quests, etc).
- Each collection would then consist of individual chapters split along logical story or quest lines.

## Understanding *TFTH*'s Process
Next, let's look at the writing process and how final content is created for release.

- **Ideation**</br>
  Every chapter, collection, book, and game compilation starts in the Ideation phase, with a draft of the quest and subquest divisions.  For example, in *Genshin Impact*'s first Archon Quest, "The Outlander Who Caught the Wind", there are 11 subquest divisions.
- **Playthrough**</br>
  The lead author Genshin_DeepDive then plays through that section, inserting content, observations, and lore notes during the playthrough while trying to focus on capturing the "first-impression" critical content.
  This document becomes the **"Draft"** and is inserted into an appropriate **Draft branch** here on the Git, under the correct repo.
- **Prose Pass**</br>
  Contributors then make a pass through the draft copy, replacing placeholder text with dialog, action scene descriptions, cutscene transcription, and more.
  After some basic grammar and composition checks, this becomes a **Prose Copy** that is then pushed to the appropriate **Prose branch** here on the git.
- **Narrative Pass**</br>
  The primary authors, Genshin_DeepDive and 4StarGoose will then make a pass through the Prose Copy, relocating and adjusting content to make the narrative structure fluid, dynamic, and suitable for a reading audience as opposed to a game-playing one.
  A lot of discussion will be held during this phase as to where less-essential-but-still-important dialog and content observations will finally be placed.
  Once this pass is complete, the document becomes a **Narrative Copy** that is then pushed to the appropriate **Narrative branch** here on the git.
- **Final Pass**</br>
  At this stage, only spit and polish is required to turn the Narrative Copy into a work of art worthy of being called "Art".  This final document is the one that will be released, and the one pushed to the **Final branch** here on the git.

### The Release Process
As each phase completes, releases will be created for public consumption.
During the Ideation, Playthrough, and Prose Pass phases, releases will consist of "snippets" of the work as opposed to the final product, giving the community a sense of where the project lies in completion.
Content created during the Narrative Pass may or may not be released to the public at all, due to the nature of its development.  However, the final product will always be released to the public.

So here is how the release process works:
>*Snippets of early content are released* </br>
>> *Chapter is released* </br>
>>> *Once all Chapters are complete, a Collection is released* </br>
>>>> *Once both Collections are complete, the Volume is released* </br>
>>>>> *Once all Volumes are complete, the final IP compilation or Omnibus is released*

## So How Can I Contribute?
> [!NOTE]
> *Tales from the Hoyoverse* is not currently accepting Community Contributions while still getting the Project underway and well-established.
> You can message either [u/Genshin_DeepDive](https://www.reddit.com/user/Genshin_DeepDive/) or [u/4StarGoose](https://www.reddit.com/user/4StarGoose/) to inquire about when and how you can help the Project during this phase.


Contributing to *Tales from the Hoyoverse* is pretty straightforward.  Take a look below at common ways to make a contribution:
</br>
### Open an Issue or Create a Pull Request for a Typo
This is by far the easiest way to contribute.  Simply read through our existing Narrative Pass or Final Pass copy and catch typos or narrative issues, and then submit an issue and/or pull request to correct it.
Opening an issue simply reports the problem, but assigning yourself to that issue, correcting it, and opening a pull request will directly resolve it, if approved.

### Contribute Outline/Playthrough Pass Material
Another easy way to help out is to play through a questline and provide outline content.  Once you have that content, you can create a post on our subreddit where you can then submit that content for review.
If accepted, we'll create a new file on the Git repo, if needed, or merge your content into the Draft branch for the appropriate quest content.
> [!TIP]
> Contributing content for IP that is not currently being worked on may or may not be helpful.
> Given the massive scope of this project, submitting content for a different IP requires that the authors mentally switch gears and refocus in order to make sense of the new writing.
> </br>It is far kinder and more useful to submit content that is close in chronological timeline to the content that has already been released, as it will be more immediately useful.
> That said, if you're extremely passionate for one region, questline, or subquest objective, then feel free to submit it anyway, bearing in mind that it may not be paid attention for a while!

### Contribute Prose Pass Material
This is significantly more challenging and in-depth then correcting errors or submitting outlines, but is therefor vastly more critical.
You can open a pull request for a piece of Draft Copy content, and then proceed through it, replacing placeholder content like the ones below:
- **Dialog** -      Replace this placeholder with dialog from the Wiki or by watching and transcribing a cutscene/animation.
- **They Fight** -  Replace this with a significantly more detailed description of fight actions, such as weapon movement, ability usage, environmental changes or damage, etc.
- **Cutscene** -    Replace this with a detailed description of a cutscene animation, including its dialog, overall mood or tone, and any significant lore notes.

There may be other placeholders not listed here, but these are the primary examples.

### Assist in Growing/Managing the Community
This may seem a bit cliche, but you can often help most by simply being a megafan.
Helping us promote *Tales from the Hoyoverse* to the Hoyo fan community gives us better visibility, which increases the dopamine kick we get from producing this content.
In addition to the dopamine, a larger community connects us with more potential contributors and collaborators, making the project more achievable in less time.

There's also the potential to help us manage our social media accounts, but that's more of a job than a volunteer position, so that'll be something we consider at a much later stage.

### Buy Us a Liquid Caffeinated Stimulant 
> [!IMPORTANT]
> *Tales from the Hoyoverse* does not currently have any subscription or donation sytems for supporting the project, so you shouldn't be doing so... and you shouldn't be asked to do so, either.  Beware of scams!

As we grow our content reach and open new avenues such as streaming, Patreon, a Ko-Fi, etc, you can help by offsetting our time and expenses accrued while doing this project.
Keep in mind that, since we're an *unofficial* fan project, we can't accept any payment for the work we create, so there will never be a charge for reading our content.
That said, we're still humans with real jobs, real expenses, and a very time-consuming hobby... so funding our passions is always appreciated.
