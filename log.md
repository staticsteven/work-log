# 2026
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
