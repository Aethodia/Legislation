DevolutionSchema
############################################################

Abstract
============================================================

This file defines how power devolves from the national government to more-local polities.

Optimizations often come at an expense;  and not everything can be optimized-for at once.
People living in different areas may wish to specialize their local policies in ways that could not or should not be done at the national level.
Likewise, areas may opt to have their local laws reflect their cultures.
Giving significant autonomy to devolved legislatures allows these adjustments to happen, decreases federal instability, and gives room for them to compete and try out new and untested ideas, thus paving the way for the national policies of tomorrow.

Contents
============================================================

Devolutions
------------------------------------------------------------

- Theodia is to be divided into metropolitan areas (henceforth "metpols").

- TODO

LegalBindings
------------------------------------------------------------

- Every provision in every national law can have one (and only one) of the following bindings:

  #. Always (Tag: ``Binding:A``) (It is legally applicable in all devolutions.)

  #. Opt-out (Tag: ``Binding:O``) (It is legally applicable in all devolutions that have not opted-out of it.)

  #. Opt-in (Tag: ``Binding:I``) (It is only legally applicable in devolutions that have opted-in to it.)

  #. Never (Tag: ``Binding:N``) (It is only applicable to the national government and in its direct holdings.)

- The default binding (where one is not explicitly stated) is ``Binding:O``.

- A law can set bindings on itself and its provisions by adding a binding tag (see above) where desired.
