A.  Abstract
===========
#.  This file **denotes** the **specifications** which a prospective piece of **legislation must adhere to** in order for **to be legally added** to this repository.

B.  Contents
===========
#.  Every law must…

    #.  …be interpreted per the official legal language [5]_.
    #.  …be contained within a single file.
    #.  …have a filename that…

        #.  …adequately describes its contents.
        #.  …each of whose words are capitalized [6]_.
        #.  …has no spaces.
        #.  …has '.rst' at its end.
        #.  …has 30 [1]_ or fewer characters (not counting '.rst').
        #.  …is unique among all other laws.

    #.  …have an internal structure as per the following:

        #.  The first section should be entitled 'Abstract', and it…

            #.  …should summarize what the law does.
            #.  …may mention the law's purpose, and previous work in the area.
            #.  …may not be longer than 400 [1]_ words.
            #.  …is not legally binding.

        #.  The second section should be entitled 'Contents', and it…

            #.  …contains the legislation itself.
            #.  …is legally binding.
            #.  …TODO.

        #.  The third section should be entitled 'Footnotes', and it…

            #.  …is where all a law's footnotes are to be located.
            #.  …may be left out if the law has no footnotes.
            #.  …is primarily intended to provide sources, thoughts, reasonings, interpretation guides, etc for provisions within a law.
            #.  …is not itself legally binding, although it can assist with the interpretation of an ambiguous law.
            #.  …should be sorted according to numerical order, from smallest-to-largest.

    #.  …be formatted so that…

        #.  …they are fully compliant with the reStructuredText specification at ``http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html``.
        #.  …paths and references to other files in this repository are formatted with code tags, like so:  ``Example``.
        #.  …TODO.

#.  It is encouraged (but not required) to…

    #.  …embolden the most important parts of each law [2]_ [3]_.
    #.  …have all footnotes in each law occur in numerical order, from smallest-to-largest.
    #.  …ensure that each law's footnote indices are complete integer-incremental series [4]_.

#. When a law cites another law, it is enough to give the law's [unique] filename (without '.rst').

C.  Footnotes
===========
.. [1]  This number is arbitrary.
.. [2]  This is intended to make legislation easier to speed-read.
.. [3]  A suggested way to go about this, is to embolden such that, when only the emboldened text is read, the gist of the law can be groked, even if the emboldened text is, by itself, not entirely grammatical.
.. [4]  This means that there should be no sparse series;  there should be no holes.  For example, it is okay to have three footnotes numbered '1', '2', and '3';  but not okay to have three footnotes numbered '1', '2', and '4', since '4' differs from its predecessor by more than 1 (and is therefore not incremental).
.. [5]  The current legal language is specified in ``NationalSymbols``.  It is worth noting, that since this language is, presently, Theodian English;  all numbers in legislation are dozenal (duodecimal).
.. [6]  This, of course, only applies for languages whose official scripts have capital letters.