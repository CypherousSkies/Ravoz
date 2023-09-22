# Grammar
## Non-Linear "Grammar"
(images to come eventually)
I'm going to call this grammar (even though this is closer to orthography) as it makes the most sense to do so. If you've read the [UNLWS](https://s.ai/nlws) documentation, everything there is transferable to this, with very few changes (mostly removing sidedness because my brain doesn't like that feature).
### Binding points on [[Writing#Glyphs|Glyphs]]
Rāvòz combines glyphs in the same way UNLWS and Ouwi do: namely by joining "binding points" lines. In the UNLWS documentation, they use a green circle to denote a binding point, which while very useful, I'm too lazy to replicate. So! how do you know what's a binding point in Rāvòz? Usually, a cusp point or extended line. You'll need some clarification so let me go over the cases for each vowel:
- `i` & `a` have two binding points: one on their "tails" and one below their "heads", not connected to anything else. The first binding point is usually a source, name, or type which modifies the glyph. The second one is what the glyph is modifying; which can be a relation, connection, or glyph. When the glyph has something in the second binding point, it shouldn't touch, but float nearby as it's modifying but not a full part of it.
- `o` is a special case. It may intersect with a line of another glyph/relation by crossing with just one leg (in which case it acts like an adjective/adverb)  or with both legs (in which case it conjugates that relation).
- `í` & `á` all have exactly one binding point, their outgoing tails. `ó` has the same binding point, plus an additional one above its head, wherein a second `ó` glyph may be written, providing an "answer" to the uncertainty.
- `ī` has exactly two binding points in both its forms: its outgoing legs. Each of these is a participant in the glyph's action.
- `ā` may have any number of binding points, to a minimum of 1. New ones may be added anywhere on the circle and the may be directed (marked with an outgoing triangle) or undirected (unmarked). In the case where it has exactly one binding point, it must be written as directed, and is said with a syllable-final `f`.
- `ō` has at least 2 binding points, but may add arbitrarily many "stops". The first binding point (which is directly connected to the head of the glyph) is usually what is doing the travelling or being compared. The subsequent binding points appear at the cusps of the zig-zagging tail and mark the various stops on the journey or comparison points. The tail may be arbitrarily extended to accommodate as many stops as desired, though at least one must be specified, unless the glyph is acting as a unit (said with a syllable-final `f`) in which case it acts either as a terminator (the idea of the unit) or a relation (name/amount of the unit).
- `ì` has exactly one binding point on its tail in all its forms. When `ì` is acting as a name, the closed circular cartouche around it looks and acts like `á`.
- `à` words usually have exactly one binding point, though its placement varies. `à` glyphs are written floating around a relation or glyph to modify it in a similar way to `i`/`a` words.
- `ò` has no regular form, though usually at least one on its tail, if written at all. In the case of what UNLWS calls Cartouches and I'm calling Parentheticals, the "parenthesis" has as many binding points as are necessary.
### More elaborate connections
Sometimes, you want to express something in a way that needs more connections than you have available binding points for. For example, in [[The Chant Text|The Chant]] I translate the concept of brutalism as `má'or ŋádi zí gàbmí` (roughly: the building(s) for use by people which are artificial and sterile), which has three binding points. To resolve this, a connection may split into as many directions as necessary to create the desired effect. If you're particular about keeping the grammar extra proper, you may write these nexi as unmarked `ā`, as that is how it is linearized (you see I lied, that phrase would be read as `má'or ŋádi āg zí vò gàbmí` so that all the binding points are evened out).
### Grouping & Rel gaps
Okay great! You can now write phrases with arbitrarily many glyphs, connecting them into a beautiful web of meaning. So what happens if you want to relate to a collection of glyphs? Or better yet, what if you have a clause which references an entire web of glyphs? Or maybe you just want to refer to a particular glyph in context of an extant phrase; well my inquisitive friend, do I have some grammatical structures for you.
As with everything in language, there are many ways of doing the same thing, which, in this case means a couple of neat structures:
First, and the easiest to understand, are Parentheticals (called Cartouches in UNLWS): these are curved lines that float above a glyph or group of glyphs and allow glyphs to bind the whole group, usually said `mò` (e.g. `pìpīno'ìpi zi mò lì pō tòšírī'ábi sò tòmòrodōri'ábi sò tòšírī`, roughly: "Pipin told \[me\] that you fulfilled the prophecy, going from the Shire to Mordor and back, but \[I\] don't believe him"). You can construct "if" statements this way by indicating possible scenarios/worlds with `nò` parentheticals, as well as indicate dream events with `ŋò` parentheticals.
Second is the Rel Gap (written like - |). This option is almost equivalent to using `mò`, and can be said the same or with `miv/m`, depending if one means it as a simple connection, or if the phrase attached to `miv/m` depends on the results of that connection (e.g. in `fomáŋà mi pó mim forī mi fómáŋàmo`, roughly: "Who were they? What did they value?", to whom the "they" in "What did they value?" refers depends on the answer to "Who were they?"). The exact why of this complication is inherited from UNLWS's (ir)rel gaps, although Rāvòz does not inherit the "sidedness" property of rel gaps. As with parentheticals, where this is placed may change its meaning (e.g. `rì fī miv nádiŋí'ádi fogā` would read as "I remember the fish that was prepared" and `rì fī miv fogāg nádiŋí'ádi` would read as "I remember the preparation of the fish").
### Decoration Sidedness (feat. Language Tape)
This isn't critical to understand as it usually won't make a difference, but I claim its useful. Consider the following:
```
  di    pi
A----rā----B
```
This would read very roughly as "A and B perceive; A is an animate observer, B is a person observer." In this case, `di` and `pi` are unrelated, meaning that the animate-ness of A is not related to the person-ness of B. So it would be reasonable to assume that A and B are separate (e.g. a camera and a person walking by) (This meaning doesn't change when flipped vertically)
By contrast:
```
  di
A----rā----B
        pi
```
Would read roughly as "A animately as B personly perceive." Notably the `di` and `pi` here are correlated to eachother, implying something like A was more bystandery because B was more directly involved, or equivalently, B was more directly involved because A was more bystandery (a distinction only being possible with clarifying relations or decorations).

The way my brain decided to explain this to me in my dream was as people asking for/having tape.
So for the former case, imagine person A has a 1" wide roll of tape, and person B wants any kind of tape, then A offers the tape in one hand, and B takes with opposite right (meaning the tape passes to the left or right of the people).
In the latter case, imagine person A has a 1" wide roll of tape, and person B wants a particular size of tape (not necessarily 1"), then they would pass the tape across them (like shaking hands), (mis)matching the two desires.

### The Implicit Author/Speaker
In some places, you'll notice that an "I/me" shows up in a translation where there isn't a `rì`. This is because, in many cases, it's not necessary to reiterate the subjectivity of the statement (e.g. in `pìpīno'ìpi zi mò lì pō tòšírī'ábi sò tòmòrodōri'ábi sò tòšírī`, `zi` is understood to mean that the source is untrustworthy *to me*). In general, when expressing things like animacy, certainty, feelings, and honestly most statements, it is assumed that the speaker means it as their opinion/experience, unless it is marked explicitly (e.g. if I instead wanted to say that it was Dinodas that doesn't trust Pipin, then I would say `dì'or zi` instead of just `zi`). As an extension, when speaking, it's not always necessary to say `rì` when it would be written, if it is clear from the context that it is me who is the subject.
### Putting it all together!
The following is a translation of [[Doctor Who Quotes#Good Things & Bad Things]]: (there's an error: `lomípi` is written as `lomídi`)
![[good-bad-things.png]]
It's constructed of the following groups of glyphs connected to each-other:
![[good-bad-things-exploded.png]]

## Linear Grammar
All that non-linear stuff is great for writing, but this is a language that can be spoken too, so here's the spoken grammar.
### Word order
Word order is largely free, as relation functions are marked fairly clearly, however there are a few conventions:
- try to start and end sentences with terminators.
- if the order of inputs to a relation is important (e.g. "inside of"), then it should go between its arguments, preferring to say the group with the most animate participant first.
- if the order of inputs is not important, say the relation first (or last).
- Try to keep related sections clustered, prioritizing the most animate sections first (e.g. "My girlfriend, who is especially beautiful in dim lighting, came to the (dimly lit) bar with me." is preferable to "My girlfriend came to the bar with me. The bar's dim lighting made her look especially beautiful." unless the observation of her beauty is being emphasized as caused by being in the bar)
### Caps
Caps change the function of a word (and are written as [[Writing#Polysyllabic Cartouches]]). Their format is suffixing the word with `'<vowel>`, with `<vowel>` being the new function (e.g. my discord nickname is `gànībòhò'ìdi`, which has the cap `ìdi`, marking it as an [[i-Animacy & Certainty|animate]] [[ì-Pronouns|name]]).
### Polysyllabic construction
In most cases, all you'll need is `[conj]<root>[adj][animacy]['<cap>]`, with `conj` and `adj` being [[o-Adjectives & Conjugation|o words]], and animacy as a [[i-Animacy & Certainty|i word]].

In the case where that is simply not enough, however, here are some rules for gluing a bunch of words together (though you'll likely want to reference [[Writing#Parts of "Speech"]])
1. A "locus" centers around a root glyph and is either "simple" (e.g. just a root, possibly with a cap), or "complex":
	- Complex relation loci form as follows: `[nested?]+[conj]+<root>+[adj]+[medium]+[domain]+[animacy]+[certainty]+<cap>`
	- Complex terminator loci form as follows: `[nested?]+[conj]+<root>+[adj]+[domain]+[animacy]+[number]+<cap>`
	- Complex conj (`o`) loci: `[nested?]+<root>+[adj]+<cap>`
	- Complex media (`a`) loci form as follows: `[nested?]+<root>+[adj]+([particle]+[kind] | [rel2rel]+[direction]+[mood])+<cap>`
	- Complex animacy/domain (`à`/`i`) loci form as follows: `[nested?]+<root>+[adj/animacy/domain]+<cap>`
		- repetitions of a root intensify (e.g. to distinguish a computer and a hammer one might refer to the former as "animate animate" or "animate person" and the second as "animate" or "animate inanimate")
	- Complex certainty (`i`) loci form as follows: `<root>+[adj/certainty]+<cap>`
2. Loci come together in the following way:
	1. The functional core (the "root") always appears first
	2. Each modifying locus in any\* order (preferring to keep connected portions together), clarifying connection to other loci (if necessary) with vowel particles, and noting external binding points with pronouns
3. Caps are constructed based on the kind of glyph: (function here means stating the operative vowel, preceded with an apostrophe e.g. `'á` for nouny terminators)
	- Relation caps are: `[function]+<direction>`
	- Terminator caps are: `[function]+<animacy>`
	- Particle caps are: `[function]+<particle/rel2rel/term>`
	- `à` caps are: `[function]+<marking>`
	- `ì` caps are: `[function]+(<animacy> | i)`
4. Shortenings
	- Have a long word? shorten it by omitting clarifying information with `zò`, then capping it by restating the vowel (so for nouns use `á`) and the usual cap.
	- Examples:
		- `rāvòtifsimpábáb'ádi` can be shortened to `rāvòzò'ádi` or `rāvòz'ádi`
		- `míbàtišoŋōhnōxfosòvovòŋōfsozo'íbi` (roughly, the path the sun traces through the sky) shortens to `míbàtiŋōhzò'íbi`

\* for canonical poly-locus words, there may be a preferred order, though this is not grammatically mandatory.
### Internal caps and VV structures
@@ I have thoughts but am not sure what to do with them
### Compound Roots

## Mythical Grammar
Something something numerology? I was inspired by the Cursed Conlang Circus, which had a number of interesting ideas relating to grammar by making words have numerological agreement. Numbers aren't really my thing, but if someone wants to run with this lmk