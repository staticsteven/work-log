# 2026
## June 26th
- I've been following along with Handmade Hero (a decade later) and am up to episode 18. I want to start writing a short note after each episode. I'm watching them at 1.5x speed and it can go by quickly, even as I follow along with the code (I'm doing a Mac platform layer instead of win32) so I can't always be sure I get everything. 
- The core of e18 is unifying the keyboard & controller input. Right now we have controller as our primary input, specifically looking at the d-pad (4 directions), 2 shoulder buttons, plus A/B/X/Y (or equivalent). To make the joystick work, we essentially convert the input into the d-pad equivalent (if the average x-offset of the joystick is negative, convert that to just pressing left on the dpad, for example). Then, with the keyboard, we do the same thing. We make WASD map to the dpad as if the play pressed on the controller. By forwarding all the events into a single processing approach we can keep things simpler.

## May 18th
- I am really bad at this, but I'll spend less time apologizing. I'm in the final mile for Inkling (which we all know takes at least as long as the rest of the build), second guessing the UI and implementing animations and polish. I am inching closer, and have set a deadline for the end of the month. I need to actually FOCUS on finishing it. 
- I quickly prototyped 2 other ideas this weekend (god bless Codex), one of which is throwaway but the 2nd is kind of fun. I will refrain from working on it until I finish Inkling.
- I am re-considering having Ads in Inkling and might just have a Pro (or w/e) mode with more of the endless play and other things. Perhaps the Daily mode is available for free.
- The 2nd app I need to finish is Split, my stopwatch app for Swim coaches. It's fairly simple, but focused on solid UX for multi-lane split timing. I've implemented a cool interaction with the volume buttons, but its kind of flakey. I need to refine the implementation and see if I can make it reliable.

## April 24th
- Recorded a Destructomath+ App Preview after a week or so of procrastinating. Of course I learned that I uploaded it at the wrong resolution and need to fix it, it's only appearing on a certain subset of devices right now.
- Trying to do some UI clean up on Streamline which means re-creating things in Figma so I can experiment. Working directly in SwiftUI makes things too slow as the app scales and relies on data. This way I can adjust small things like line height, spacing, etc.
- Very happy with the progress on Inkling, the new game I started ~6-7 weeks ago. It's hangman meets crossword puzzles. I spent a lot of time iterating on the UI and I think it's getting to a good spot. I'm mostly tweaking some polish and working on the tutorial next before I do a wider beta. My goal is to release by June

## March 29th
- Iterating on the new game a lot. Balancing content updates (lots of too hard guessing), UI iteration (trying to find some themes that look good), crashes and feedback from testing, and some game design. It's fun. It feels like it's not too far from being feature complete (maybe another week) but lots of love needed on the polish still.
- Released the update to Streamline. Downloads are super low (1 every couple days) so it will take a few weeks to see if the new onboarding makes a difference.
- For Destructomath+, I made a couple tweaks. I added Posthog for analytics (we had Mixpanel but I never checked it) and I instrumented the onboarding tutorial. I'm curious to see how many people play beyond the tutorial. I also adjusted how the ads present (before it was opt-in but now it's automatic, I think it might actually be better). I submitted that to review this morning so I likely won't see results for another week.

## March 14th
- Ok we have been going ham on the new game, Gallows. It's fun, I've been iterating on the UI and a lot of the content, and am ready to send it to some friends for playtesting this weekend. Spend most of my daily/weekly claude tokens on this. It moved well.
- For streamline, I've been working through some of the UI feedback to get that cleaned up and pared back some of the original scope from this version. I want to get it out this month and don't have much left. Part of what I am improving is the onboarding flow so it's clearer for the core steps (adding a swim meet / best time) but also presenting the optional paywall to see if we get an uptick in trials.

## March 9th
- Been away for a little. Had a baby. I'm off for another week so trying to get through any projects I can while I have small amounts of time and energy (she is still sleeping lots).
- Been ripping through some of the Streamline updates. Getting some help from Dylan on the UI which will be very valuable since it's kind of falling apart (and it's way too early in its life for that)
- I was feeling inspired so I prototyped and built a full iOS game tonight. I'll probably be able to send it to a friend tomorrow and then to a few more friends by the end of the week. It needs lots of UI love, balancing, content, etc. But the core idea is there and time to keep seeing if it's fun.
- The cooking card game is chugging along. I've put together the core loop and am building out small interactions next (discard, hover to preview). It's getting close to be able to do very very early play tests just to see if it's fun.

## Feb 28
- We are mostly done the new version of Streamline. It's primarily UI updates with a couple small enhancements (the ability to set a goal time per event and support for a new set of time standards). I'll try to finish this in March (trying to be realistic here)
- I have been iterating on the card game here and there, trying to find at the least the core loop. I'm stuck in a refactor phase right now because the code base was a mess after following a couple different tutorials that weren't the best from a code quality standpoint. 
- Lastly, built a couple small new brushes for Inkbit. Still focused on going as wide as possible before figuring out what actually fits with the vibe. I added a "glitchy" brush, a paw prints one, a new type of audio one. I am overdue for another brainstorming session to build up the backlog of what else it could be.

## Feb 23
- I recently became inspired to revisit the UI for [Streamline](https://staticloop.co/streamline). Over the weekend I mostly focused on trying to follow the Liquid Glass updates more closely and tweak the app icon. It's fun to have it feeling a bit better (though I might just be biased by a few apps I'm drawing inspiration from), and good to just get back to writing a tiny bit of annoying SwiftUI code.
- I've been doing a little bit of tweaking to the more recent brushes in Inkbit (working title) to make them look and feel a bit more nicer. I need to let the app stew for a bit as I think about the project more.

## Feb 18
- Life has been busy but the baby still isn't here. Instead I've been ripping through new brush prototypes. I added: mirrored brush, marching ants, clouds, alphabet, new rainbow style, eyeballs, snowflakes. It's been fun seeing how quick some of these can come together. Brand/art direction still needs a lot of work.
- I've still been going through my game prototype. I described it to a friend like so: Trying a card-style approach where you have a deck of ingredients that you are trying to combine to satisfy a guest’s craving (ex: looking for something sweet, preferably with fruit in it) and in your hand you have like eggs, dough, pork, strawberry, corn, garlic, whipped cream. Still tweaking the core loop to find the fun. There will be some other secondary systems but for right now, serving a guest needs to feel better.
  
## Feb 6
- Been slowly iterating on new brushes for MagicMarker, which I've renamed to Inkbit for now. I prefer that name. I've added a flower brush (needs work), a striped brush, a fun clear the screen, a translucent brush. I started playing with the dripping style but still can't get one that doesn't suck. Also trying to play with blend modes but I'm not sure a good approach for this. I will need to consult a friend who understands colours and layers.
- And, of course, 4 days before the baby is set to arrive, I've started another game prototype. I start them as fast as I abandon them. This one is written in GDScript. I started trying to use AI to code it but wasn't happy with the direction (more so game design than output) so I decided to code it myself. So far just getting core mechanics set up and using imagegen tools to get placeholder art in place.

## Jan 27
- I've started testing out the Linear <> Codex integration. I'm not really a big git user (solo dev + bad iCloud habits) but am trying to get into it so I can have agents do development from the phone.

## Jan 25
- Crazy amounts of progress this weekend. We added so many new brush types to Magic Marker and I've started thinking of a better name (I don't like MM). We have an audio recording brush (different than before), fire, spiral, paint splatter, and a new AI stamp box that will generate stamps based on a voice command. 

## Jan 22
- Slower on the builds since I used my Claude Code weekly limit lol.
- Added multi-touch support to Magic Marker. I was testing it with Serena yesterday and it didn't go well when her hand was all over the screen.
- Finished up to Section 5 of the C text editor (it's got full, basic functionality now). Cool to see it come together. I think I will do a short write up of things I have learned just so I can remember. Spoiler: It's not a ton.
- My app analytics tool got approved for TestFlight so I need to finish some of the core stuff before sending that to some friends. The Onboarding could definitely use some love since it's a bit of a hassle getting your API key onto your phone (there's no OAuth style option & I made it mobile only)

## Jan 19
- Built the brush config tools so that I can iterate on the look and feel in real-time. A quick play around with that interface and I think I need to expose more properties -- I'm not actually sure what/how to tweak things yet to have them feeling better.
- Changed how bubbles are rendered. Apparently Metal has a limitation of ~511px for point/vertex shaders so we need to use quads now. Now they can stretch to the full size. Added a little bit of distortion as well so they feel slightly more bubbly.
- Started on a new dripping brush as well.

## Jan 18
- Guess the prompt was boring. Killing that project.
- Debugged the neon brush. I'm going to expose some "level editor" like tools for the shaders soon so I can tweak values easier directly on the ipad. Right now rebuilding and testing is really slow to iterate on specific values. I want to build up maybe 20 different brush/shader types before starting to test the idea out with friends.

## Jan 17
### Magic Marker
- Serenditously came up a cool 3d looking brush type while trying to get the glow in the dark brush to work. I decided to save it as a new option.
- Still struggling with the shader for the neon brush.
### Other Projects
- This was supposed to be the year I take writing more seriously and instead I find myself full of energy to put towards building instead. I started hacking on a quick "guess the image prompt" game. I'll try to finish it tomorrow and share it with some friends. It might be totally un-fun.
- Lastly, I randomly decided to start [this tutorial](https://viewsourcecode.org/snaptoken/kilo/) about building a terminal-based text editor in C lol. I don't even know C (only elements from Obj-C and dabbling in C#) but it's fun to follow along.

## Jan 16
### Aardvark
- Submitted a TestFlight build for Aardvark so I can start that approval process. I spent a little bit of time tweaking the data syncing process so we aren't making too many unnecessary API calls
- I also generated a new iOS icon that better matched the new dark mode aesthetic. 
### Magic Marker
- I made some refinements to the audio brush to make it, it's kind of fun. The way it works right now is twofold - based on the sounds you make while drawing it will appear differently (stroke width + colours). Then once it's drawn, if you speak or make noise the strokes will react to the sound as well. The colours are ugly and we can refine here, but it's more fun. I want to update this to be a bit _more_ like perhaps spawning some flair while drawing depending on the sound.
- I also prototyped a new glow-in-the-dark brush that is a bit like a neon sign. It's partially working.

## Jan 15
- Did some design in Figma for Aardvark (apple analytics app) with some new custom typefaces I bought. This will be the first time I release an app using a non-Apple typeface which is definitely something new for me. Also used the Figma MCP to actually implement this in the app and it did a great first pass. 
- Updated the Aardvark widgets as well to match the new design system.
- Prototyped the first version of the audio brush in magic marker. It changes colours in response to sound while drawing, but it's kind of crap. Need to iterate on this still and increase sensitivity.

## Jan 13
- Followed [this tutorial](https://www.createwithswift.com/creating-a-live-audio-waveform-in-swiftui/) to build an animated waveform. It's super slow right now so need to debug. The goal is to turn this into a shader for the Magic Marker project
- Also built this new log page :D
  
## Jan 10
  - Started up MagicMarker again - incorporated Fal.ai for some realtime, LCM kind of. It doesn't look good.
  - I need to actually design a placeholder UI for MagicMarker since the LLM isn’t good at it so far.

## Dec 1
  - no new update. But been moving and sick. Applied to the Dwarkesh job.
  
## Nov 23
  - Submitted the holiday version of D+ for review
  - Revising writing for my Knife post. But more of a family day.

## Nov 22

- PowerLink:
  - Built in undo capabilities
  - Built in value checking + level components to increase/decrease charge
  - Built in walls, arena, a prototype level. Big progress today.

## Nov 21

- What's new pop up in D+ submitted to be featured
- Fixed date switching and timeline view in Sleepy. New TestFlight build.
- Started prototype for powerlink - Godot tutorials. I'm going to build it for desktop and mobile. We got the base functionality working and can design levels now.

## Nov 20

- Fixing a bug with dates for Sleepy
- Tweaks to Zen Mode implementation (better UX)
- Updates to Streamline's "Season Summary" feature

## Nov 19

- Decided on freemium model for Zen mode for D+
- Built the Streamline website & pushed live ([staticloop.co/streamline](https://staticloop.co/streamline))

## Nov 18

- Copywriting for Streamline website

## Nov 17

- Built Zen mode for Destructomath+
- Built the "season summary" feature for Streamline
