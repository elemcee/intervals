# Intervals
Simple tool for visualizing intervals on the guitar fretboard. The fretboards are pure HTML and CSS (using the [Bulma CSS framework](https://bulma.io/) as the base. JavaScript is used for the toggle function.


## Basic Info
The hider buttons at the top toggle all instances of each interval (except roots, which are always visible) to allow you to focus on one or more intervals at a time. This is helpful for learning the positions of single intervals relative to the root, intervals relative to other intervals, or arpeggios/chord tones.

The interface includes the major scale, major pentatonic scale, dominant seventh arpeggios, minor scale, and minor pentatonic scale.


## Live Version
See it [in action](https://elemcee.com/intervals/).


## FAQ
Q. Why aren't there individual hider buttons for each fretboard?

A. I find I'm only really focusing on one fretboard at a time, so it's not necessary, though this feature may be added in the future.

***

Q. Why only these scales/arpeggios?

A. They cover the most common cases. Major/minor arpeggios can be viewed by hiding the twos, fours, sixes, (and sevens for triads). The dominant seventh arpeggio is included separately since it uses both major and minor intervals. Different scales/arpeggios can be added in your own version by copying one of the existing tables and inserting the appropriate intervals. Intervals must have the correct class in order to be controlled by the hider buttons.

***

Q. What is the significance of the colors?

A. Not much. Each numbered interval (regardless of quality) has a consistent, but completely arbitrary, color: roots are red, seconds are orange, thirds are yellow, fourths are green, fifths are blue, sixths are purple, and sevenths are dark grey.

***

Q. Is there a monochrome/high-contrast version/setting available?

A. Not yet, but possibly in the future. You can change all colors of the interval classes in the CSS to black or dark grey to accomplish this. The interval numbers would then appear as white on a dark background (like the sevenths in the original version).

***

Q. Where are the fretboard markers?

A. The scales/arpeggios are moveable anywhere on the fretboard, so fretboard markers are unnecessary and potentially confusing.

***

Q. Why separate fretboards for the pentatonics? Can't you just hide intervals to see those?

A. Yes, but I find it's useful for comparing the pentatonic to the full scale.

***

Q. Does this work on mobile?

A. Sort of. It should work pretty well on a tablet, and in my (limited) testing, it works okay in landscape on a phone screen.

