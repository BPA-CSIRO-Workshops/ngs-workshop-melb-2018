Providing Feedback
==================

While we endeavour to deliver a workshop with quality content and
documentation in a venue conducive to an exciting, well run hands-on
workshop with a bunch of knowledgeable and likable trainers, we know
there are things we could do better.

Whilst we want to know what didn't quite hit the mark for you, what
would be most helpful and least depressing, would be for you to provide
ways to improve the workshop. i.e. constructive feedback. After all, if
we knew something wasn't going to work, we wouldn't have done it or put
it into the workshop in the first place! Remember, we're experts in the
field of bioinformatics not experts in the field of biology!

Clearly, we also want to know what we did well! This gives us that "feel
good" factor which will see us through those long days and nights in the
lead up to such hands-on workshops!

With that in mind, we'll provide three really high tech mechanism
through which you can provide anonymous feedback during the workshop:

1.  A sheet of paper, from a flip-chart, sporting a "happy" face and a
    "not so happy" face. Armed with a stack of colourful post-it notes,
    your mission is to see how many comments you can stick on the
    "happy" side!

2.  Some empty ruled pages at the back of this handout. Use them for
    your own personal notes or for write specific comments/feedback
    about the workshop as it progresses.

3.  An online post-workshop evaluation survey. We'll ask you to complete
    this before you leave. If you've used the blank pages at the back of
    this handout to make feedback notes, you'll be able to provide more
    specific and helpful feedback with the least amount of brain-drain!

Document Structure
==================

We have provided you with an electronic copy of the workshop's hands-on
tutorial documents. We have done this for two reasons: 1) you will have
something to take away with you at the end of the workshop, and 2) you
can save time (mis)typing commands on the command line by using
copy-and-paste.

While you could fly through the hands-on sessions doing copy-and-paste
you will learn more if you take the time, saved from not having to type
all those commands, to understand what each command is doing!

The commands to enter at a terminal look something like this:

    tophat --solexa-quals -g 2 --library-type fr-unstranded -j annotation/Danio_rerio.Zv9.66.spliceSites -o tophat/ZV9_2cells genome/ZV9 data/2cells_1.fastq data/2cells_2.fastq

The following styled code is not to be entered at a terminal, it is
simply to show you the syntax of the command. You must use your own
judgement to substitute in the correct arguments, options, filenames etc

``` {style="command_syntax"}
tophat [options]* <index_base> <reads_1> <reads_2>
```

The following is an example how of R commands are styled:

``` {style="R"}
R --no-save
library(plotrix) 
data <- read.table("run_25/stats.txt", header=TRUE) 
weighted.hist(data$short1_cov+data$short2_cov, data$lgth, breaks=0:70)
q()
```

The following icons are used in the margin, throughout the documentation
to help you navigate around the document more easily:

\hspace*{.2cm}
Important\
For reference\
Follow these steps\
Questions to answer\
Warning - STOP and read\
Bonus exercise for fast learners\
Advanced exercise for super-fast learners\

Resources Used
==============

We have provided you with an environment which contains all the tools
and data you need for the duration of this workshop. However, we also
provide details about the tools and data used by each module at the
start of the respective module documentation.
