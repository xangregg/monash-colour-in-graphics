# The use of colour in graphics. A journey through the body & mind to the screen
<!-- NETLIFY BADGE SHOULD GO HERE-->

# Abstract

Data is everywhere, and we typically make sense of it in the form of data visualisation. But how do we know what we see is the same as everyone else? It turns out not everyone is the same, and colour vision deficiencies (such as colourblindness) are not uncommon. This talk unpacks some of the physiology of the human visual system, so that we can understand how to better visualise data. Specifically, in this talk I explain how:  

* Colourblindness actually works  
* We can evaluate existing colour palettes or images
* Create better ones that are accessible to all

# Slide available [here](https://bit.ly/njt-monash-colour)

# Take home messages 

- Colour choice matters
- Choosing colours is hard
- We can use Hue / Chroma / Luminance to describe colour
- See established palettes: colorspace / viridis / scico
- Assess colours with `colorspace::specplot()`
- Assess colourblindness with `colorspace::cvd_emulator()`
- Evaluate your own colour palettes at `hclwizard.com`
- Choose colour palettes with 
  - `colorspace::choose_palette()`
  - `colorspace::choose_color()`
  - `colorspace::hcl_color_picker()`
  - `colorspace::hcl_wizard()`

# Thanks

# Resources

# Colophon

  - Slides made using [xaringan](https://github.com/yihui/xaringan)
  - Extended with
    [xaringanthemer](https://github.com/gadenbuie/xaringanthemer)
  - Colours taken + modified from [lorikeet theme from
    ochRe](https://github.com/ropenscilabs/ochRe)
  - Header font is **Josefin Sans**
  - Body text font is **Montserrat**
  - Code font is **Fira Mono**

# Bio

Dr. Nicholas Tierney (PhD. Statistics, BPsySci (Honours)) is a Lecturer in Business Analytics and Statistics at Monash University, working with Professors
[Dianne Cook](http://dicook.org/) and [Rob Hyndman](https://robjhyndman.com/). His research aims to improve data analysis
workflow, and make data analysis more accessible. Crucial to this work is producing high quality software to
accompany each research idea. Mostly recently, Nick's work is focussing on exploring longitudinal data ([brolgar](http://brolgar.njtierney.com/)), and improving how we share data alongside research ( [ddd](https://github.com/karthik/ddd)). Other work has focussed on exploring data
with the R package [visdat](http://visdat.njtierney.com/), and on creating analysis principles and tools
to simplify working with, exploring, and modelling missing data with the
package [naniar](http://naniar.njtierney.com/). Nick has experience working with decision trees ([treezy](http://treezy.njtierney.com/)),
optimisation ([maxcovr](http://maxcovr.njtierney.com/)), Bayesian Data Analysis, and MCMC diagnostics ([mmcc](http://mmcc.njtierney.com/).

Nick is a member of the [rOpenSci](https://ropensci.org/) collective, which works to make science
open using R, has been the lead organiser for the rOpenSci ozunconf
events from 2016-2018 ([2016](https://auunconf.ropensci.org/), [2017](https://ozunconf17.ropensci.org/), [2018](https://ozunconf18.ropensci.org/)), and co-hosts the rstats podcast ["Credibly
Curious"](https://soundcloud.com/crediblycurious) with [Dr. Saskia Freytag](https://careers.amsi.org.au/saskia/). Outside of research, Nick likes to
hike, rockclimb, make coffee, bake sourdough, (eventually) knit a hat, take photos, and explore new hobbies.
