# prolog-english-grammar-parser
parser for a definite clause grammar of English-Light. English- Light is a fragment of English (i.e., English-Light does not include any ungrammatical English sentences).


Using Prolog, A parser for a defnite clause grammar of English-Light. English- Light is a fragment of English (i.e., English-Light does not include any ungrammatical English sentences) which accounts to structures as those appearing in the following examples.

a) The young boy pushed and stored a big box in the large empty room after school.
b) The old woman and the old man gave the poor young man a white envelope in the shed behind the building.
c) Every boy quickly climbed some big tree and every girl watched some boy.
d) Some brilliant students and many professors watched and admired talented lecturers and appreciated bright scientists and researchers.

The lexicon includes all the words appearing in the examples above, at least twenty nouns, at least twenty verbs (with the past tense in􏰁ection), at least twenty adjectives, at least ten adverbs, at least ten prepositions, and at least ten determiners.

The grammar contains no ε-rules and should have the symbol S as its start variable. A successful parse should result in building a parse tree for the input; The parser
generates such a tree. We linearly represent a parse tree as follows:
a) l, where l is the label of a leaf.
b) p(l1, l2, . . . , ln), where p is a label of a parent node and li is the ith sub-tree thereof, where left-to-right order is assumed.
