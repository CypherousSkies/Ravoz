# Thétk ngā nòsh
`The3tknga1no2sh` (anglicized "Thek'nganosh") translates as "Understanding all of infinity through belief/on no authority".
This is spiritual artlang with a non-linear writing system, primarily about telling stories and using them to communicate ideas in a spiritually significant way.

Each vowel with a tone forms a glyph and (in keeping with its [[Ouwi]] roots) saying the consonants in order recovers a story for each vowel, which forms the core vocabulary of the language.

The goals are as follows:
- Build a non-linear dyslexic-friendly writing system
- Make the core vocabulary and construction of the language to be ideo-religiously significant
- Be compatible with [[00 UNLWS|UNLWS]]
- Be easily extensible (e.g. for regularly-constructed combinations and shorthands of sub-graphs be able to form cannonical new glyphs)
- Easily facilitate [garden-stream](https://hapgood.us/2015/10/17/the-garden-and-the-stream-a-technopastoral/)-[[#Conversations|style]] conversations and note-taking

## Design Notes
- Each story has one line for each consonant (=> Each story has the same # of lines )
- Each story represents a single vowel
- Each vowel is a connector which expresses a relation between concepts (e.g. being a list)
- Must be fun to write and say
- Must support poetry
- Must support being written with curved connections
- Must be dyslexic friendly (meaning the same up to rotation, translation, and reflection)
### Ideas
- 10 vowels is a lot. How far could we get with 3 or 5 vowels? Maybe with tones?
- I do want a native way of consonant marking because writing in a latinate character is kinda boring and not super fun
- I don't like how violent and somewhat hopeless the stories are, so I'd like my versions to be a little nicer
	- Also more in line with my ideo-religious beliefs
- Also I would like there generally to be a more robust native vocabulary, while still supporting a creole approach
- Consider as well, poems for each of the consonants (as the consonant inventory is much larger than vowel inventory, a full story would be difficult), though it might be preferable to use the same word multiple times and have several possible poems to emphasize the range of use for each word
- I'd like the "sound" of a word to give some hint to its meaning, making use of the poems and stories
- I also want the language to look smoother -- I'm not a fan of how angular Ouwi naively looks
- Also there needs to be a spoken words which mean "Branch here which I intend to return to", "Branch here which I do not intend to return to", "Continuing from the aforementioned branch", as well as question "What was it that you were going to return to?" all without written components (possibly a consonant which is only spoken, but has no glyph?)
- Have cannonical polysyllabic words be formed in the style of the [Tamarians of Star Trek](https://memory-alpha.fandom.com/wiki/Tamarian_language) -- having shorthand words (ending in `sh`) which stand in for important stories?
## Sounds
Syllables are CV(C) with tonal vowels.
Syllable-final consonants are somewhat rare as they tend to indicate specific grammatical effects.
Most of the time, you'll use monosyllabic words. I mean there's 171(ish) of them, which is a pretty good start.

### Polysyllabic words
Native polysyllabic words are of the form [`*i`(`p,#`)]\*`c` (in the usual [[#Transliterations|shorthand]]) with the exceptions of some [[#Proper Nouns]]. They should be extensions of their monosyllabic parts (to keep with the idea of the vowel stories being central to the language), though deviations are inevitable.

It should be noted `o1` and `a3` are what are called "[[#Parts of speech|terminators]]", meaning they may only be in the first (as spoken) syllable of a (native) word (except in cases where that would ungrammatical, as with [[a1-Collections & Nexus|a1]] and [[o2-Intransitive, Adjectives, & TAMs#Conjugation|o2]]). `a2` may not appear in polysyllabic words.
#### Caps
Polysyllabic words can broadly be categorized by their caps:
- Vertical cap (`|`, read as `tk`): Animate names (so not places or non-doing things) are (usually) bisyllabic, do not have the usual restriction of syllable-final pronoun sounds (meaning `g`, `k`, `h`, and `x` are fair game, so long as they are closed, e.g. show up at least twice, marking a connection), and are usually written somewhat artistically.
	- This cap is also for animate words whose meaning is distinct from their compound meanings.
- Double-o cap (`oo` or `8`, read as `sh`, bind to 'o' which the word doesn't bind to already): Inanimate & place names. When a particular sound is desirable, syllable-final consonants are used; when a meaning is desirable, syllable-final consonants should be only used when they mean something.
	- This cap is also for inanimate polysyllabic words whose meaning is distinct from their compound meanings.
- Plus cap (`+`, read as `z`): Transliterated foreign nouns are usually written "properly" (following the rules for proper nouns) unless it's unambiguous which vowel each consonant is referring to. Additionally, the usual rules about terminators do not apply here.
#### Proper Nouns
Proper nouns are polysyllabic words with the following restrictions:
- All but the word-final consonant (the "cap") cannot be any of `g`, `k`, `h`, `x`, `tk`, `sh`, or `z` to avoid confusion with pronouns and caps.
- Most proper nouns are written serially, though this is more of a suggestion than a rule.
- Writing the syllable-final consonants is somewhat free-form when writing proper nouns. It's conventional to put them on the following serial arm but have fun with it

### Vowels
There are 3 vowels, (a,e,o), and three tones (constant, falling, rising). These are ascii transliterated as vowel-tone number e.g. `a1` is a with constant tone.
Each vowel has a glyph whose binding points are along their lines. In the case where a line is curved, that means that, by default, that line is curved, though in practice, most lines are likely to be somewhat curved.

vowels | \- (1) | \\ (2) | \/ (3)
-|-|-|-
a | \-o< | \- | 4
e | A    | $u^4$  | $\gamma^V$
o | o\-  | v  | >\_o(

ascii|Symbol|Meaning|Story
-|-|-|-
`a1` | -o< | set/group | [[a1-Collections & Nexus]]
`a2` | \- | number, spoken-only | [[a2-Spoken-only & line decorations]]
`a3` | 4 | question | [[a3-Unknowns]]
`e1` | A | rel (unordered) | [[e1-Reflexive, Directed]]
`e2` | $u^4$ | rel (ordered) | [[e2-Particles & Decorations]]
`e3` | $\gamma^V$ | command/three-way ordered verb | [[e3-Color and Intensity]]
`o1` | o- | noun | [[o1-Nouns]]
`o2` | v | adj | [[o2-Intransitive, Adjectives, & TAMs]]
`o3` | >\_o( | range | [[o3-Paths & Travel]]

### Consonants
Consonants are written as particles above or below the vowel glyph (as if modifying).
Words containing `tk` are exclusively spoken and so have no (vowel-modifying) written component.

\- | labial | dental | alveolar | retroflex |  velar | glottal
-|-|-|-|-|-|-
plosive| `b` |  | `d` | | `k` `g` |  `'`
nasal| `m` | | `n` | | `ng`
trill/tap| | | `r`
fricative| `v` | `th` | `z` | `sh` `j` | `h` `x`| 
approximant| | `l` | `r` | `rz` | `y`

In order they are:

/ʔ/`'` ![['.png|150]]
/m/`m`![[m.png|150]]
/n/`n`![[n.png|150]]
/$\eta$/`ng`![[ng.png|150]]
/p,b/`b`![[t.png|150]]
/d,t/`d`![[d.png|150]]
/f,v/`v`
/$\theta$/`th`![[th.png|150]]
/r/`r`![[r.png|150]]
/ɻ/`rz`![[rz.png|150]]
/ʐ/`j`![[j.png|150]]
/ʂ/`sh`![[sh.png|150]]
/z,s/`z`![[z.png|150]]
/l/`l`![[l.png|150]]
/j/`y`![[y.png|150]]
/g/`g`![[g.png|150]]
/k/`k`![[k.png|150]]
/x/`h`![[h.png|150]]
/ɣ/`x`![[x.png|150]]
(/ǂ,k'/`tk`)

#### Consonant Groups
Consonants often form groups with opposing meanings:
Nasals: `m`, `n` (sometimes `ng`)
Dentals: `t`, `d` (sometimes `th`)
v: `v`, `th`
s: `j`, `sh`, `z`, `l`, `y`
alvelor: `g`, `k` (sometimes also glottals)
glottal: `h`, `x`
#### `tk` & pronoun glyphs
In linear writing, it's useful to have a way to write the various forms of `tk` words and pronouns. For each vowel they are as follows:
`a1`:
`a2`: place a `|` on the noted branch and refer back as `|<pronoun>`
`a3`: 

## Grammar
### Parts of speech
Perhaps unsurprisingly, each glyph approximately corresponds to a part of speech.
For the purposes of making sense to non-speakers, they are:
- [[o1-Nouns|nouns]] (which include most [[a1-Collections & Nexus|groups]])
- [[o2-Intransitive, Adjectives, & TAMs|adjectives]]
- [[o3-Paths & Travel|paths]] (connections, prepositions)
- verbs (which can be [[o2-Intransitive, Adjectives, & TAMs|order-1]], [[e2-Particles & Decorations|directed order-2]], [[e1-Reflexive, Directed|undirected order-2]], [[e3-Color and Intensity|directed order-3+]], or [[a1-Collections & Nexus|undirected order-3+]]).
That said, a more useful set of parts of speech would perhaps be:
- **terminators**; which (usually) function like [[o1-Nouns|nouns]] or [[o2-Intransitive, Adjectives, & TAMs#^ca66e2|objectless verbs]]
- **relations** (which can be directed or undirected); which may have 2 or 3 arguments, but that can be extended with use of `a1` words, and function like verbs with objects
- **paths**; which indicate sequential relationships
- and **line decorations**; which are usually [[a2-Spoken-only & line decorations|a2]] words or SI [[o2-Intransitive, Adjectives, & TAMs]] words
Though which is better is, perhaps, academic.
### Short-hands
I'm not going to write out the same words over and over again, so here's some shorthands.
#### Descriptions
Shorthand | Graph Notation | description
-|-|-
DI | `=` | double-intersect
SI | `/` | single-intersect
S | `-` | serially (polysyllabic)
D | n/a | line decoration (negation, plural)
\- | n/a | connected normally
@ | n/a | placeholder for glyph sequence
R\<@,@,...\> | `<@,@,...>` | radiate the glyph sequences $@_1$, $@_2$, etc. 
#### Transliterations
Shorthand | description
-|-
`p` | any pronoun sound (`g`, `k`, `h`, `x`) or unknown closer (`tk`)
`i` | any vowel sound
`#` | any number sound (`'` to `j`)
`*` | any consonant
`c` | any cap
### Conventions
It's useful to have some understood rules to navigate the complexities of this language:
#### Speaking (and Transliterating)
Transliterating and speaking graphs are complicated in Thek'nganosh, as so much of the language can be said in any order. As a result, let's set some conventions (in order of priority) to help you navigate reading aloud:
1. Start at an `o1` terminator (following the usual rules for groups and conjugations)
2. When an `a1` branch occurs, say the branches in ascending order of length (shortest first)
3. Try to follow the shortest paths between terminators (don't get lost in cycles)
4. Avoid reversing [[e1-Reflexive, Directed#Speaking a reversed glyph|directed]] glyphs
5. End with `a3` terminators
6. End with `o2` terminators
7. End with `o1` terminators

This won't cover all cases, and it might be preferable in many cases to split a graph into many separate sentences with [[a2-Spoken-only & line decorations#Pronouns|pronouns]] covering connections between sentences. In general, try not to speak in overly-long sentences and if it's not important to preserve a variadic `'o1` with many paths, break each branch into a sentence of its own.
#### Transcribing (and Translating)
When transcribing (or translating) sentences or a linear work, start by grouping information into clusters of related statements (e.g. a story about person might have clusters about their appearance, their community, their friends, etc.), then connecting them to avoid pronouns. If the same word (representing the same thing) comes up several times, consider splitting its connection with an `'a1` glyph.
See also: [[#Conversations]]
#### Graph notation
Sometimes it's useful to write out how a graph will be drawn, this can be done as follows:
- Write the name of each glyph followed by parentheses with comma separated alphanumeric text representing binding points, separated by a semicolon (e.g. `mo1(m);`, the last semicolon of a scope being optional).
	- The character `.` notes an unused binding point
	- The order of the arguments is the canonical ordering (see each glyph's page)
	- In general it's good practice to use Thek'nganosh consonant names for binding point names, but that's not a hard requirement.
- A group of glyphs can be written inside square brackets (`[@]`). All binding points not starting with an underscore (`_`) are locally bound to this scope, and will not interfere with outside bindings.
	- Binding points outside of the group begin with an underscore and are bound outside of the brackets with parentheses (as if the group were a glyph e.g. `[nga1(_1,m,n);no2(n);mo1(m)](m)`)
		- Distributive stacks are special situations where a group of glyphs need to be referenced multiple times to the same binding points, written `[@(_1,_2)](m,n;ng,t)` (see [[Relations#Distributive]]).
	- If there are no external binding points, or there are more arguments than binding points, the group is automatically in a [[e2-Particles & Decorations#Cartouches|cartouche]]
		- [[e3-Color and Intensity#Counterfactual Cartouches|Counterfactual Cartouches]] are defined the same way, but with curly braces (`{@}`) instead of square braces
	- Radiating groups are a series of sequences which bind to the same place, written between angle braces (`<@>`); e.g. `<@(_1),@(_1),@(_1)>(m)`. Note that each sequence in a radiative sequence must have the same number of external binding points.
- Polysyllabic and intersecting glyphs are written with [[#Short-hands]]
- [[#Caps]] are written as if they are glyphs (e.g. `|(m,_1);`)
- Closed off branches are written with `|` in the glyph's arguments (e.g. `the3(.,|,m);` for `the3tk` in `the3tk nga1 no2sh`)
### Creoles & Foreign Text
It's useful to use foreign writing systems in Thek'nganosh and be able to notate them, so here's a couple ways that's supported:
#### Natural Language Creole
For words borrowed in from other languages, write them next to the vowel glyph representing their kind (so a name could be over a `'o1`, as in Ouwi). When spoken, say it as `'ip<word>`. So `'o1gCar` would be a valid binding point for the English word "Car".
#### UNLWS Mixed Script
[[00 UNLWS|UNLWS]] (said `'a1nle2z`) graphs are naively supported as a photographic/professional script (much like Japanese's kanji) for Thek'nganosh as it is more compressed and less visually cluttered. By nature, UNLWS supports using Thek'nganosh words as part of larger graphs, which can be used to convey ideas for which UNLWS doesn't yet have the vocab for. 
When saying an UNLWS graph, the closest Thek'nganosh word is used for each glyph (this may get difficult, but with some work it can be done). Translating between these systems shouldn't be terribly hard, though one should note that UNLWS has arbitrarily many connections converging to a single binding point, which may take a number of `a1` words. 
### Conversations
Following the Garden (`ro1the3sh` literally "home of understanding/thoughts") & Stream (`ro1the1sh` literally "home of conversations") [model](https://hapgood.us/2015/10/17/the-garden-and-the-stream-a-technopastoral/), my thoughts are as follows:
- The Stream (made up of linear speech) is either ascii/utf-8 transliterated Thek'nganosh, which may be rendered but isn't necessarily converted into script (so a "forum" built for Thek'nganosh might support graph speech, but transliterated is likely the norm)
	- Long-form posts would (usually) be written in script, per Sai's blog post, organizing to form arguments
	- Short-form posts would (almost always) be transliterated text, as if a section of a conversation.
- The Garden (made up of connected, searchable, semi-isolated Graphs) as essays/posts/dynamic knowledge units which are (almost) always in script (so a "forum" would have a federated wiki portion which can be easily referenced with a page-specific link)
	- For related thoughts see [[#Transcribing and Translating]]
Towards making this, I'd look at integrating a blogging/social news platform with a [Federated Wiki farm](https://github.com/fedwiki/wiki) (with appropriate plugins), but I think multiple stream sources are inevitable, and that's okay! What's important is the collaborative Garden.
