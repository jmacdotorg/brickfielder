# Brickfielder

An opinionated, speech-centric seven-minute workout timer.

## Description

On launch, Brickfielder will immediately begin pacing you through the twelve drills of [the seven-minute workout (7MW)](http://fogknife.com/2015-01-11-seven-minute-workout.html).

Its features include:

* **A minimal, speech-centered UI.** Brickfielder guides you through voice alone (with a simple text transcription in its terminal window).

* **Shuffling the drills a bit beforehand,** optionally, and for variety's sake. While you still get three rounds of aerobic, lower-body, upper-body, and core drills in that order, Brickfielder will randomize the order of the three drills within each category.

    In other words, it will always start with an aerobic drill, but that drill might be step-ups, jumping jacks, or high knees. It will then move on to a lower-body drill. You will always receive all twelve drills exactly once per workout.
    
* **Breaking the side-planks drill into two sub-drills,** separated by a very short pause to allow for switching sides.

* **A no-chair mode** that substitutes other drills when you find yourself in a space (e.g. a hotel room) with no suitably stable chair to exercise with.

## Installation

Brickfielder should run as-is with no dependencies on any reasonably up-to-date Mac or Linux system. Place it wherever you like.

You will need a command-line text-to-speech program installed on your machine that simply speaks whatever argument-string it receives. The default is `say`, which comes with macOS and is [also available for Linux](http://manpages.ubuntu.com/manpages/trusty/man1/say.1.html).

## Usage

Turn up your speakers before running Brickfielder.

Run with `--help` to see a list of all the program's command-line options.

You can pause or unpause the timer as you would any other terminal-based program. Hit Control-Z in its terminal window to pause Brickfielder, and resume it by running the `fg` shell command in that same window. No, that's not ideal, but that's how it is for now.

Note that Brickfielder assumes user familiarity of the twelve 7MW drills, such when it says e.g. "Prepare for wall sit," you will know what to do next.

## Project status

It works as described here. The author does use this program nearly every day, and would like to update it along extremely specific and opinionated directions. The reality of this, of course, remains to be seen.

The author always welcomes pull requests, bug reports, and other feedback.

## Project history and roadmap

There are many, many perfectly good 7MW timers out there. I have used and enjoyed several since discovering the workout in 2013, and finding that it fits very well into my lifestyle. It was only natural that, after several years, I lost patience with all of them for not fitting my own personal preferred execution of 7MW, such that I finally resolved to just make my own.

This is that. I fully expect that Brickfielder will fit me perfectly and slightly chafe literally everyone else who tries to use it, just like every other timer written by any of my fellow 7MW-loving nerds. I will nonetheless endeavor to make something that of at least 80 percent usefulness to people who are not me.

## Notes and bugs

Pausing and resuming the working should be a lot easier than it is.

The project's name comes from [Brickfielder](https://en.wikipedia.org/wiki/Brickfielder), a wind pattern found in southern Australia. I like to name my projects after regional winds, alphabetically; when I started this project I'd still only made it down to the B's.

## Author

Brickfielder was created and is maintained by Jason McIntosh (jmac@jmac.org).
