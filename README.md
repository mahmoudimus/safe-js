# SafeJS - Hermetic Sandboxing for JavaScript

Authors: Damien Cassou, Stéphane Ducasse, Nicolas Petton
Paper: [https://hal.inria.fr/hal-00862099](https://hal.inria.fr/hal-00862099)

> Damien Cassou, Stéphane Ducasse, Nicolas Petton.
> SafeJS: Hermetic Sandboxing for JavaScript.
> [Technical Report] 2013, pp.7. hal-00862099

## Abstract

Isolating programs is an important mechanism to support more secure applications. Isolating program in dynamic languages such as JavaScript is even more challenging since reflective operations can circumvent simple mechanisms that could protect program parts. In the paper above, Cassou, Ducasse, and Petton presented SafeJS, an approach and implementation that offers isolation based on separate sandboxes and control of information exchanged between them.

In SafeJS, sandboxes based on web workers do not share any data. Data exchanged between sandboxes is solely based on strings. Using different policies, this infrastructure supports the isolation of the different scripts that usually populate web pages. A foreign component cannot modify the main DOM tree in unexpected manner.

This SafeJS implementation, at the time of the paper's publishing, is currently being used in an industrial setting in the context of the [Resilience Fonds Unique Interministériel 12 project](http://www.oseo.fr/a_la_une/actualites/premiere_annee_du_programme_innovation_strategique_industrielle) (or in English, "Single Interministerial Fund").

## Contribute

If you have a good idea for this project, just open up an issue and I'll update this with a proper contribution guideline.
