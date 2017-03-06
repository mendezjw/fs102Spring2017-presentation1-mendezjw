# fs102Spring2017-presentation1-mendezjw

This repository contains the HTML source code and additional resources for a presentation that I, [Jonathan Mendez](http://www.mendezjw.github.io), gave during a classroom session. The presentation's source code uses the
[reveal.js](https://github.com/hakimel/reveal.js/) framework to control the display of each slide.  I have developed a
custom theme for the slides that manages the formatting, color scheme, and the use of full-screen photographs on the
backgrounds.

You are welcome to use these slides as inspiration for your own presentation. If you find this example useful, could I
trouble you to star this repository and then acknowledge it in your own presentation slides?

Are you interested in previewing the presentation without having to download the code and resources from the GitHub
site? Well, you can! Please view [It's a Trap!](https://rawgit.com/mendezjw/fs102Spring2017-presentation1-mendezjw/master/seke2015_panel.html).

## Installation Instructions

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/gkapfham/seke2015-panel-presentation.git
```

Please note that the presentation uses local fonts so that it can be displayed at a conference on a laptop that either
may not have access to the Internet or may only have unreliable Internet access. Some browsers may disallow the loading
of local fonts due to security reasons. However, it should be possible for you to view the presentation correctly when
using Chrome or Chromium on the Ubuntu operating system &mdash; this is my primary development environment and the one
that I used to give the presentation. However, I anticipate that the presentation slides should display correctly on a
wide variety of operating systems and browsers.

I have found that some versions of Chrome and Chromium do not quickly load the full-screen images that I use as
backgrounds. If you notice this problem as well, then I would encourage you to "serve" the presentation with a local Web
server, such as the Ruby-based one available at [jlong/serve](https://github.com/jlong/serve). If you adopt this
approach, then you should type the following command:

```shell
serve 4100
```

Now, you can navigate to the Web site `http://localhost:4100/seke2015_panel.html` and view the presentation.  Ultimately,
if you are unable to get the presentation to display correctly in your own web browser, then please open a new issue and
I will attempt to resolve your concerns.
