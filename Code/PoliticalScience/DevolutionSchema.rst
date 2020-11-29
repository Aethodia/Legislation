LegalInterpretation
############################################################

Abstract
============================================================

This file defines how power devolves from the national government to more-local polities.

Contents
============================================================

LegalBindings
------------------------------------------------------------

- Every provision in every national law can have one (and only one) of the following bindings:

  #. Always (Tag: ``Binding:A``) (It is legally applicable in all devolutions.)

  #. Opt-out (Tag: ``Binding:O``) (It is legally applicable in all devolutions that have not opted-out of it.)

  #. Opt-in (Tag: ``Binding:I``) (It is only legally applicable in devolutions that have opted-in to it.)

  #. Never (Tag: ``Binding:N``) (It is only applicable to the national government and in its direct holdings.)

- The default binding (where one is not explicitly stated) is "Opt-out".

- A law can set bindings on itself and its provisions by adding a binding tag (see above) where desired.
