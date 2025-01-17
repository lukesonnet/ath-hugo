---
title: Uses
date: 2021-09-07
slug: uses
description: Andrew Heiss is working on a bunch of exciting and groundbreaking projects
---

People often ask me what programs I use for my writing and design. In truth, my workflow tends to look like [this](https://xkcd.com/1579/) or [this](https://xkcd.com/1172/), but here's a more detailed list of all the interconnected programs I use.

I try to keep this updated fairly regularly. As of September 7, 2021 this is what I'm using:

## Writing

- I permanently ditched Word as a writing environment in 2008 after starting grad school. I do all my writing in [pandoc-flavored](http://pandoc.org/) [Markdown](https://daringfireball.net/projects/markdown/) (including e-mails and paper-and-pencil writing)—it's incredibly intuitive, imminently readable, flexible, future proof, and lets me ignore formatting and focus on content.
- I live in [Ulysses](http://ulyssesapp.com/). At first I chafed at the fact that it stores everything in its own internal folder structure, since I store most of my writing in git repositories, but exporting a compiled Markdown file from a bunch of Ulysses sheets is trivial (and still easily trackable in version control).
- Ulysses has decent HTML previewing powers, but when I need more editorial tools, I use [Marked](http://marked2app.com/).
- I use [Typora](https://typora.io/) to edit standalone Markdown files, since Ulysses uses its own syntax when using fancy things like footnotes. Typora is my favorite standalone Markdown editor I've found so far because it inherently supports pandoc-flavored Markdown.
- The key to my writing workflow is the magical [pandoc](http://pandoc.org/), which converts Markdown files into basically anything else. I use [my own variation](https://github.com/andrewheiss/Global-Pandoc-files) of Kieran Healy's [Plain Text Social Science workflow](http://plain-text.co/) to convert Markdown to HTML, PDF (through LaTeX), and Word (through LibreOffice).
- I store all my bibliographic references, books, and articles in a [BibTeX](http://www.bibtex.org/) file that I edit with [BibDesk](http://bibdesk.sourceforge.net/).
- I read and annotate all my PDFs with [Skim](http://skim-app.sourceforge.net/) (and [iAnnotate](http://www.iannotate.com/) on iOS), since both export annotations as clean plain text.
- I store all my notes in [Bear](https://bear.app/), which has fantastic support for Markdown and syncs across all my devices through iCloud. I abandoned [Evernote](https://www.evernote.com/) in September 2018 after 9 years of heavy use, given their ongoing privacy controversies and mass layoffs.


## Development

### Science and research

- I post almost everything I write or develop on [GitHub](https://github.com/andrewheiss).
- I use [R](https://www.r-project.org/) and [RStudio](https://www.rstudio.com/) for most of my statistical computing, and I'm a dedicated devotee of the [tidyverse](http://tidyverse.org/). In the interest of full reproducibility and transparency, I make [R Markdown websites](https://rmarkdown.rstudio.com/rmarkdown_websites.html) for each of my projects. I don't typically make full-blown literate documents (like, I have yet to write a full article or book in R Markdown)—instead, I generate figures and tables with R and reference them in my writing. [See a list of these websites](https://stats.andrewheiss.com/).
- I also use [Python](https://www.python.org/) ([3!](http://www.onthelambda.com/2014/05/13/damn-the-torpedoes-full-speed-ahead-making-the-switch-to-python-3/)) pretty regularly, especially for natural language processing (with [nltk](http://www.nltk.org/)) and web scraping (with [Requests](https://requests.readthedocs.io/en/master/) + [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)). Every few months I play with pandas and numpy and Jupyter, but I'm far more comfortable with R for scientific computing.
- I use RStudio for editing R files, but I use [Visual Studio Code](https://code.visualstudio.com/) for everything else.
- I adapted the idea for research haikus [from Kirby Nielsen](https://kirbyknielsen.com/research/).

### Web

- I run my main web server on a [DigitalOcean](https://www.digitalocean.com/) droplet, and [I spin up temporary droplets all the time](https://github.com/andrewheiss/cloud-config-files) to offload scraping scripts, complicated R models, and to create on-the-fly VPNs.
- I normally access my remote files through SSH in a terminal, but for more complicated things, I've found that [Mountain Duck](https://mountainduck.io/) is indispensable.
- My website uses [Pelican](http://blog.getpelican.com/). My teaching websites all use [blogdown + Hugo](https://bookdown.org/yihui/blogdown/).
- I use [Let's Encrypt](https://letsencrypt.org/) for SSL.

### Miscellaneous

- I use a [system-wide hotkey](https://www.iterm2.com/features.html#hotkey-window) (``ctrl + ` ``) to open [iTerm2](https://www.iterm2.com/) from anywhere.
- I use [Homebrew](http://brew.sh/) to install Unix-y programs.
- I'm partial to both [Fira Code](https://github.com/tonsky/FiraCode) and [Consolas](https://en.wikipedia.org/wiki/Consolas) for my monospaced fonts.


## Desktop apps

### Graphic design

- Though I regularly use LaTeX (through pandoc), I adore [InDesign CC](https://www.adobe.com/products/indesign.html) and use it to make fancier academic and policy documents. I also used it for [all the typesetting I did](https://github.com/andrewheiss/maxwell-institute-typesetting/blob/master/books-i-made.md) for [BYU's Neal A. Maxwell Institute](http://mi.byu.edu/).
- I use [Illustrator CC](https://www.adobe.com/products/illustrator.html) all the time to enhance graphics I make in R and to make non-data-driven figures and diagrams.
- I use [Lightroom](https://www.adobe.com/products/photoshop-lightroom.html) and [Photoshop](https://www.adobe.com/products/photoshop.html) too, but less often nowadays.
- Despite my dislike for Word and Excel, I use PowerPoint for all my presentations. It's not my favorite, but in the apocryphal words of Churchill, "PowerPoint is the worst form of slide editor, except for all the others."

### Productivity

- My secret for avoiding the siren call of the internet is [Freedom](https://freedom.to/). I have two blocklists: (1) *antisocial*, which blocks Facebook and Twitter, and (2) *nuclear*, which blocks everything. I have the antisocial blocklist enabled on my laptop and phone from 8:00 AM–6:00 PM and 8:30 PM–11:30 PM. Since I accidentally discovered that it's relatively easy to circumvent the blocking on the Mac, I also use [Focus](https://heyfocus.com/) with the same schedule.
- I use [Vitamin-R](http://www.publicspace.net/Vitamin-R/) as a souped-up Pomodoro timer.
- I was an early convert to [Todo.txt](http://todotxt.com/) and used it for years until my tasks and projects got too unwieldy. I switched to [Taskpaper](https://www.taskpaper.com/) for a while, used [2Do](http://www.2doapp.com/) for a couple years, and now I'm a convert to [OmniFocus](https://www.omnigroup.com/omnifocus).
- [Fantastical 2](https://flexibits.com/fantastical)’s natural language input is a glorious thing.
- I keep a log of what I work on (and occasionally do more traditional diary-like entries) with [Day One](http://dayoneapp.com/) on both iOS and macOS.
- I use [TextExpander](https://smilesoftware.com/textexpander) to replace and expand a ton of snippets, and I use [Keyboard Maestro](https://www.keyboardmaestro.com/main/) to run dozens of little scripts that help control my computer with the keyboard.
- I use [Übersicht](http://tracesof.net/uebersicht/) to show weather, iTunes track information, and my todo lists on my desktop.
- I use [Dropbox](https://www.dropbox.com) religiously and use [Backblaze](https://www.backblaze.com/) to back up all the computers in our house to the cloud.
- With all these little helper apps, I use [Bartender](https://www.macbartender.com/) to keep my menubar clean.


## Hardware

- I use a 2018 15″ MacBook Pro, a 2016 13″ MacBook Pro, a 5th generation iPad, and an iPhone 8.
