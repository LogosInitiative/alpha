# Alpha

Alpha is the code name for logical language with a pure predicate grammar. It is derivation of Logla, and thus Loglan/Lojban, but its grammar is so radically different that it justified it's own project.

It is an open question if the grammar is to "alien" to be a truly practical spoken language. This is one of the question this project hopes to answer.

This README provides a brief overview of the main idea of the language. The Wiki pages will be used to describe the various aspects of the language in detail.

Since the language does not current have its own vocabulary, Loglan and Lojban words will be used.

## Phonology

Presently the phonology is essentially the same as Loglan/Lojban. There is little reason to expect this will change beyond a few minor adjustments.

## Morphology

## Grammar

Alpha's grammar is a truly Logical grammar. Its sentences are composed of sets of predications. These predications start with a predicate followed by sequence of pronouns or proper nouns, one for each argument the predicate supports. Here is a simple example.

    klama mi tu glare tu
    go I there, hot there
    I go where it is hot.

To help us understand this sentence, we can break this to two lines.

    klama mi tu
    glare tu
    
This makes the analog to actual predicate logic much easier to see.

    klama(mi,tu),
    glare(tu).

Clearly this is a unique form of communication. Simply put a statment is a set of predications the form a single conception.

### Personal Pronouns

In everyday speech presonal pronouns are some of the more common words spoken.

    mi - me
    du - you
       - him/her

### Definite Pronouns

Definite pronouns reference a particular thing in the context of converstaion. When using a definite article the speaker or writer expects the listener or reader to recognize the particular entity, whether it is because it has been mentioned before, or it is widely understood to be unique.

With this indtroduction to definite pronouns, we must also introduce the concept of variables. Since more than one definite pronoun can be used in a sentence, refere to separate things, there must be a way to differentiate between mutiple uses. We do this by change alternating the final vowel. The articles in order are:

    la le li lo lu lai lei loi lau

There are nine choices. If needed more can be provided, but it is expected that nine will be sufficient. The human mind will likely find it difficult to follow four, let alone nine. So limiting the number to nine provides a sort of natural limitation on the complexity of sentences.

(*Note the order of the vowels may be changed to improve phonetic distance between adjacent terms.*)

    plise la kukte la
    The apple is delicious.

Both the words `plise` (apple) and `kukte` (tasty), as defined in Lojban, take more than one argument. But we have need only of the first of each, so we need not specify pronouns for the remaining slots.

### Indefinite Pronouns

Indefinite pronouns allow us to make statement about ...

    plise sa kukte sa
    Any apple is delicious.

### Possessive Association

    plise m'la kukte la
    The apple of mine is delicious.

    plise d'la kukte la
    The apple of yours is delicious.

### Restrictive Association

Restrictive pronouns are used to restrict the referent of a pronoun to a limited set as described by other predicates.

    pilse sa xunre r'sa kukte sa
    Any apple that is red is delicious.

### Incidental Association

    pilse la xunre p'la kukte la
    The apple which happens to be red is delicious.
