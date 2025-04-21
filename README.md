# What is this?
this readme lays out the inspiration, principles, and rules that specify the 
formation of my network of notes. 

notes about what? Anything - anything i learn which i feel is important.

# Sections

*TODO - put quick links here*

# Outline

this system of notes is heavily inspired by the Zettelkasten system. the devil 
is in the details though, hence this readme.

so what metrics does this system optimize for?
1. note creation needs to be ultra low friction.
1. notes need to retain value after being written.

## There exists a friction

the first point is the most crucial. often i find that my notes are well 
structured and easy to digest after the fact, but the mental effort required to 
get up and running with this style is much too high. 

deciding the hierarchy of the note file is the first major culprit. just as
there are many ways to skin a cat, there are many ways to group the same note.
in my experience, the mental overhead required to pick the path of a new note
increases exponentially with the number of related topics in the repository.
not good.

second, adding metadata to every single note created is a drag. it's not as bad
as choosing file hierarchy, but it still requires effort that produces very
little benefit. one specific example is, in my old obsidian notes, i would
create a tag for every note, which was a way to group notes into categories,
like a hashtag does on a social media post. this was pretty much a useless
feature looking back, unless i wanted to know how many notes i took for a given
topic.

third, the text editor i was using, obsidian, did not mesh well with my
workflow. i always felt my flame of inspiration to take notes qwell at the
thought of loading up the obsidian text editor. it's not a bad editor by any
means, and it even supported re-mapping keys that i often used in my other
IDEs. theres many other great things to say about obsidian, but having to 
open another program with another window to manage on my desktop which 
accomplishes the same goals as my text editors felt very bulky and 
uncomfortable.

## Let's oil those gears

when i found the zettelkasten system, i was immediately a believer. im not sure
what argument was being presented in favor of the system, but i immediately
had wondering thoughts depicting how low friction and addicting such a system
could be.

what i love most about the system in particular is that each note is contained
to a small idea. 

in my interpretation, this idea should be able to be explained in less than 100 
words, which is a bit less than two tweets. this ensures that taking notes does
not feel like the beginning of some daunting task (similar to how this readme
felt to start).

i also love the zettelkasten system because it's not necessary to name notes.
being able to immediately jump into the meat and potatoes of a new note seems
like a great way to ensure i stay in a flow state while learning. any added
tasks up-front take away from this.

recently, I also transitioned to using neovim full time. with this, i learned
the power of plugins, and i wrote a few simple, scrappy plugins that customize
my workflow to perfection. one plugin that im still actively brainstorming
and coding out is called `notorious`, which i may or may not publish on github.
the point of this plugin is solely to provide convenient tools to supercharge
my note taking workflow. for example, its only one command `:Concept` to create
a new concept note filled with the minimal amount of metadata already populated.

## Notes without a purpose

a huge problem with my old notes is that it lacks any soul. this may sound
hippy dippy and subjective, but one tangible aspect that my old notes severely
lack is any expression of wondering thoughts, connections, or conclusions 
drawn from the concepts these notes captured. 

oftentimes when im reading material, ill catch myself drifting down a 
rabbithole, making connections along the way with other bits of knowledge i 
have. these thoughts are, in my opinion, immensely valuable for recall and
understanding. i would argue, without these ponderances, all knowledge is
limited to rote memorization.

this point is a bit more obvious, but copying or slightly rewording phrases
straight from books is not helpful for building recall or understanding. this
should be self explanatory.

## A valuable note is a...

A valuable note is a note which:
1. stimulates and challenges understanding at write-time
1. provides low friction access to the concepts/ideas being captured long after
it has been captured

*TODO - write more here*

# Rules

1. The content of a note should be atomic and immutable.
1. Each note will have a type of one of:
    * concept
    * idea
    * question
    * answer
    * source
1. The content of a note should not exceed 400 characters.
1. Each "concept" note must include a `source` link
1. Each note, except a "source" note, must have an `origin` link
1. Each "source" note must include `reference` meta
