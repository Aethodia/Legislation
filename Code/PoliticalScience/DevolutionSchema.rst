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
``Binding:N`` [1]_

Devolutions
------------------------------------------------------------

- Theodia is to be divided into metropolitan areas (henceforth "metpols").

- TODO

LegalBindings
------------------------------------------------------------

- Every provision in every national law can have one (and only one) of the following bindings:

  #. Always (Tag: ``Binding:A``) (It is legally applicable in all devolutions.) [2]_

  #. Opt-out (Tag: ``Binding:O``) (It is legally applicable in all devolutions that have not opted-out of it.) [3]_

  #. Opt-in (Tag: ``Binding:I``) (It is only legally applicable in devolutions that have opted-in to it.) [4]_

  #. Never (Tag: ``Binding:N``) (It is only applicable to the national government and in its direct holdings.) [5]_

- The default binding (where one is not explicitly stated) is ``Binding:O``.

- A law can set bindings on itself and its provisions by adding a binding tag (see above) where desired.

Footnotes
============================================================

.. [1] Devolutional bindings are defined in ``DevolutionScheme:LegalBindings``.

.. [2] Generally speaking, this should only be used when national uniformity is required.

.. [3] This is for most policies.  Devolutions are permitted to opt-out of these where necessary, such as where they are unable to fulfill the requirements of a provision, or when the provision is not revelant to their situation, or when they wish to trial a different policy.

.. [4] This is primarily intended for policies that are not yet ready for nationwide adoption.  This allows novel policies to be tested at small scales aforehand.

.. [5] This is mostly for technical things, like the structure and operation of the federal government.
