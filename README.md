[![fmSyntaxColorizer logo][fmSyntaxColorizer logo]][fmSyntaxColorizer home]

# fmSyntaxColorizer
[See What You Mean!]

A tool for FileMaker developers from MrWatson to put color in your scripts and meaning into your life.

Copyright © 2021 MrWatson of www.mrwatson.de ([LICENSE](LICENSE))

## Welcome

Welcome to the new OPEN SOURCE version of fmSyntaxColorizer from MrWatson of www.mrwatson.de and fmworkmate.com

Did you say OPEN SOURCE?

- Yes, fmSyntaxColorizer is now OPEN SOURCE :D
- It's licenced under a GNU GPLv3 licence
- That means you have full access to the file, can change it to your needs, 
  and you can - indeed are heartily invited to - contribute back to the project!

What has changed?

- fmSyntaxColorizer is now a separate project to fmWorkMate
- Support for dark mode - at last!
- Collections - to quickly add/remove a bunch of syntax colors
- *and* - as of version 1.2 - you can now change colors with the right-click > Text Color menu
- See the [CHANGES](Changes.md) file for more

One thing, however, won't change...

- fmSyntaxColorizer is a mac-only tool. Sorry win-guys

Happy FileMaking!

MrWatson 2021-09-16

[![mrwatson.de][mrwatson.de logo]][mrwatson.de]

## Links

- [fmSyntaxColorizer home][fmSyntaxColorizer home]
- [fmSyntaxColorizer repo][fmSyntaxColorizer repo]


## Get Started

1. Install:
   - Download the [latest release](https://github.com/mrwatson-de/fmSyntaxColorizer/releases) of fmSyntaxColorizer from the [fmSyntaxColorizer repo][fmSyntaxColorizer repo]
   - Copy the fmSyntaxColorizer folder to your machine, wherever you want, or...
     - Applications folder (recommended)
     - Note: If you want to start fmSyntaxColorizer from [fmWorkMate|(https://www.fmworkmate.com)
       place the fmSyntaxColorizer folder next to the fmWorkMate folder, 
       or put the fmSyntaxColorizer file in the fmWorkMate folder!
   - Make Sure you have the latest [MBS-Plugin][MBS-Plugin] installed and registered
2. Use:
   - Open fmSyntaxColorizer in the FileMaker of your choice.
   - On the right enable all the [MBS Developer extras] you desire (and there may well be more in FileMaker Pro > Preferences > Plugins > MBS-Plugin > Configure ...Christian Schmitz develops faster than I can breathe!)
     - Note: I highly recommend using the [Script Variable Checking](https://www.mbs-plugins.com/archive/2015-07-23/Checking_Variable_Declarations/monkeybreadsoftware_blog_filemaker) extra to catch all those typos in variable names!
   - Choose the Collections that you want to colorize (just the Core collection will do for most people ... we may introduce a minimal collection later :-) ... you can also define your own)
   - Choose a different color pallette, if you wish (for example for dark mode)
   - Press the [Colorize] button
3. See the colo(u)rs:
   - Open the script editor
   - Enjoy your colorful scripts(*)
   - If the colors don't look right please read the section below on light/dark mode.

It's a colorful life! :)

(*) Not enjoying? Let me know, feedback, contribute!





## Light mode / dark mode troubleshooting

You only need to run fmSyntaxColorizer once to get colored scripts every time you open your Script Workspace or calculation editor.

If, however, you switch between light and dark mode (manually or automatically), the colors DON'T change!

*FileMaker, fmSyntaxColorizer & MBS-Plugin do not currently support automatic color switching.*

So, **if you switch between light and dark mode**:

- reopen fmSyntaxColorizer and select the relevant dark/light color palette to switch fmSyntaxColorizers colors

And **if the colors still don't look right**:

- Reset the FileMaker Script Workspace colors:
   - Script Workspace > Edit > Script Workspace Preferences > Syntax Coloring > [Reset to Default]

=> Note: To avoid this problem you might prefer to NOT choose automatic light/dark mode switching in your system preferences.

## Get in!

SO, you are interested in how it all works?

To open fmSyntaxColorizer in developer mode:

- Hold [ALT] [[SHIFT] on Windows) as you open fmSyntaxColorizer
- Login using "the secret admin/admin password” ;-)
- You're in - take a look around! (Note: It's not all nice on the inside :-] )


## Get Involved

Please do help make fmSyntaxColorizer better!

Maybe we can make a better dark mode palette?
Or add automatic dark/light palette selection?

See the [CONTRIBUTING](CONTRIBUTING.md) file

## Tips & Tricks

You can define your own color palette or syntax if you like.

Take a look at the GBS syntax - for example, we use a zzz prefix to mark unused stuff, so we color it to warn if it is still in use.

If you need to highlight a particular phrase, you can use the minimised mode to color up to four phrases dynamically as you need.

You can define syntax entries for your GUI language - just enter the phrase in your langauge in the second column! (If anyone can automate this please let me know!)

## Get More

MrWatson has a bunch of other stuff, check out [fmworkmate.com], [mrwatson.de], or check out my repositories [@mrwatson-de on github][github/mrwatson.de]

## Known Issues & Limitations

- It's not possible to define colors which automatically change for light & dark mode
- fmSyntaxColorizer does not automatically choose the correct color palette for the current light/dark mode
- See the github issues page for more...


[fmSyntaxColorizer home]:https://www.fmworkmate.com/fmsyntaxcolorizer
[fmSyntaxColorizer repo]:https://github.com/mrwatson-de/fmSyntaxColorizer
[fmSyntaxColorizer logo]:fmSyntaxColorizer_Logo_256_sm.png
[mrwatson.de logo]:www.mrwatson.de_neon_128.png
[mrwatson.de]:http://www.mrwatson.de
[MBS-Plugin]:https://www.monkeybreadsoftware.com/filemaker/
[github/mrwatson.de]:https://github.com/mrwatson-de
[MBS Developer extras]:https://www.monkeybreadsoftware.com/filemaker/SyntaxColoring/
