| Version:  
    ``0/0/0``
| Depends:  
    ``http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html``

A.  Abstract
===========
#.  This file **denotes** the **specifications** which a prospective piece of **legislation must adhere to** in order for **to be legally added** to this repository.

B.  Contents
===========
#.  All legislation should be interpreted per this section's subsection(s).

    #.  All numbers are assumed to be in base-twelve, unless otherwise specified.
    
#.  All legislation must be written in compliance with this section's subsection(s).

    #.  Have filenames that comply with the specifications listed in this section's subsection(s).
    
        #.  Adequately describe the bill's contents.
        #.  Capitalize each word.
        #.  Have no spaces.
        #.  Have .rst at the end.
        #.  Have 20 or fewer characters [1]_, not counting '.rst'.
        
    #.  Have an internal structure that complies with the specifications listed in this section's subsection(s).
        
        #.  Each law must begin with metadata, and this metadata must consist only of certain data-points, these being defined by this section's subsection(s).
            
            #.  Version
            
                #.  (TODO)
                
            #.  Depends
            
                #.  (TODO)
                
            #.  References
            
                #.  (TODO)
                
        #.  Post-metadata, each law may only contain sections that match the requirements of this section's subsection(s).
        
            #.  Abstract
            
                #.  This section should summarize what the law does.  
                #.  It may also mention the law's purpose, and previous work in the area.  
                #.  It may not be longer than 400 words [1]_.
                #.  This section is not legally binding.
                
            #.  Contents
                
                #.  All subsections of this section are legally binding.  
                
            #.  Footnotes
            
                #.  This section contains the contents of the various footnotes referenced throughout a law.  
                #.  This section may be left out if the law has no footnotes.  
                #.  No subsection of this section is legally binding.
                
        #.  The contents of each law must additionally meet the formatting-requirements specified in this section's subsections.
        
            #.  Full compatibility with the reStructuredText format, as specified at ``http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html``.
            #.  The most important parts of a law should properly be emboldened [2]_ [4]_, although emboldening within footnotes is optional, except where otherwise stated.  

            #.  Outside of the 'Footnotes' section itself, footnotes do not need to appear in order -- although drafters are encouraged to place them so.
                    
            #.  Metadata must be formatted in a specific way, as defined by this section's subsection(s).
            
                #.  (TODO)
                
#.  Legislation may only depend upon files in ``/leg`` and ``/res``
#.  Files in ``/res`` may not depend upon anything [3]_.

C.  Footnotes
===========
.. [1]  This number is arbitrary.
.. [2]  This is intended to make legislation easier to speed-read.
.. [3]  This is because files in ``/res`` are intended to allow nomocracy to expand beyond mere text, but are not intended to provide a workaround for standard legislative procedure.
.. [4]  A suggested way to go about this, is to embolden such that, when only the emboldened text is read, the gist of the law can be gained, even if the emboldened text is, by itself, not entirely grammatical.
