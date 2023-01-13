# The Rāvòtifsimpábàb'ádi Project
**Rāvòtifsimpábàb'ádi Losim**
> perceive-group_separator(directional emphasis)-\[enigmatic-terminator\]-\[\[personal_perception-reverse_rel\]-spiritual_domain-information\]-function_mark-noun-animate partial-personal_perception-reverse_rel
> "The partial experience (project) which is spiritual language (which is a tool) which allows (through personal experience) the perception of the enigmatic (unknowables, spirits, gods)"

The `rāvòtifsimpábàb'ádi` project (or just `rāvòzò'ádi` or `rāvòz'ádi` for short, anglicized Rāvòz) is a spiritual artlang (also known by its autonym `tābòkò'afdi`) with a non-linear writing system.
Rāvòz is the successor to Thék'ŋānòsh (itself a stylistic derivative of [Ouwi](https://ouwi.org/index.html) and functional derivative of [UNLWS](https://s.ai/nlws/)), which was simpler and more "complete" (having a closed set of "simple" words), but it didn't *sound* quite right. Also, after the Great Vowel Collapse (don't ask), it became kinda messy to work with. So we're restarting with mostly similar intentions, and hopefully better-fated ends.

Rāvòz is a work-in-progress and will be posted here _eventually_. When I post it, I'm happy to watch it take on a life of its own among speakers and writers, but for now it's a deeply personal project designed to help me work through some spirituality feelings. That said, don't take it _too_ seriously. Much of it struggles with being the result of too-tight design decisions and a general lack of destination. When Rāvòz launches, I'll be making a discord to talk about/in the language and I'm more than happy to answer questions about it!

Discord: https://discord.gg/GaP6X7YGUd

What follows is an outline of the highlights of my design documents.

## How to use this Repo

This repo represents my current, up-to-date notes about Ravoz and relevant topics in an [Obsidian](https://obsidian.md/) mind map/wiki. I've done my best to cite my sources and keep things up to date but most of the non-Ravoz sections (especially on UNLWS) haven't been updated since [[The Rāvòzò'ádi Project|Ravoz]] was [[Thek'nganosh|Thek'nganosh]].

## Goals
- Build a non-linear, dyslexic-friendly writing system
- Be fun to say (read: I want retroflex and tones because I'm Like That)
- Have a featural consonant marking system
- Look smooth and be fun to write (read: I want compatability with off-the-shelf graph-embedding algorithms)
- Have a relatively small "simple"
- Be polysynthetic to convey non-linear information efficiently and in a cool way when spoken (inspired by the kitchen-sink approach of [Ithkuil](https://ithkuil.place))
- Make the core vocabulary and construction of the language to be ideologically/spiritually significant
	- Gender may only be expressed in ranges
	- Remove references to biological/intrinsic separations (e.g. sex, family, sentient/sapient) where possible
	- While the results of violence should be easy to talk about, causing violence should not
	- Separate people and their characters
	- Make spiritual topics easy to discuss
	- Be poetic wherever possible
- Be compatible with [UNLWS](https://s.ai/nlws/)
- Be easily extensible (e.g. for regularly-constructed combinations and shorthands of sub-graphs be able to form cannonical new glyphs)
- Easily facilitate [garden-stream](https://hapgood.us/2015/10/17/the-garden-and-the-stream-a-technopastoral/)-style conversations and note-taking
- Accommodate Unmarked Poems, where you write something without consonant markings! It wouldn't really be possible to say and are more an exercise in subjectivity than a poem but wow would that be cool.

## Phonology

### Vowels
There are 3 vowels — `a`, `i`, `o` — and four tones: rising (first, `á`), constant (second, `ā`), falling (third, `à`), and no tone (zeroth, unstressed, `a` or `ȧ`), which are the same as in Mandarin Chinese. They can be written as either vowel-number (e.g. `a1` meaning /a/ with rising tone, with `a` meaning /a/ with no tone) or with their pinyin equivalents (e.g. `á` meaning /a/ with rising tone, `ȧ` or `a` for no tone).
Each vowel-tone pair is represented by a glyph (unit of written information) and is modified by at least one consonant. In general, changing tone corresponds to terminators, constant tone to relations, and no tone to particles.

#### Glyphs
Glyphs are written like this:
type | triangle (i) | circle (a) | irregular (o) 
-|-|-|-
particle ( )| curl-tri | 6 | V 
terminator (/) | 4 | o- | -c
relation (-) | A | /o\ | $\gamma$ˇ 
decorations (\\) | pronouns | numbers/domains | grouping

And function like this:
type | i | a | o
-|-|-|-
. | i-Animacy & Certainty | a-Media | o-Adjectives & Conjugation
/ | í-States of Being | á-Nouns | ó-Questions & Unknowns
\- | ī-Reflexive Relations | ā-Collections | ō-Paths
\\ | ì-Pronouns | à-Domain Markers & Numbers | ò-Grouping

##### Unmarked Glyphs
If, however, a glyph is not marked it may take on a new meaning, usually following what the glyph already stands for:
type | triangle | circle | irregular
-|-|-|-
particle | animate | medium | adj/conj
term | exists | person/noun | question
relation | is/becomes | semantic branch/and/or/cause | path

It should be noted that as the decorations can't really avoid being marked, and so are omitted from this table.

There are many reasons to leave a glyph unmarked (especially for `ā` which is vital to managing the flow of complex graphs), so don't be shy to use them!

### Consonants
\- | labial |  coronal | retroflex |  velar 
-|-|-|-|-
plosive| `p`/p/ `b`/b/ | `t`/t/ `d`/d/ |  | `k`/k/ `g`/g/ 
nasal| `m`/m/ |  `n`/n/ | | `ŋ`/ŋ/
fricative| `f`/f/ `v`/v/ | `s`/s/ `z`/z/ | `š`/ʂ/ `ž`/ʐ/ | `h`/x/ `x`/ɣ/ 
approximants| | `r`/r,ɾ/ `l` /l/ | `ř`/ɻ/ | 

Consonants are written as modifying a vowel (which should make sense, as the vowel determines the function of a root).

### Phonotactics
Rules!
1. Syllables are (C)(C)V(C)
2. Dipthongs are allowed but only as shortenings
	1. If two vowels are next to each other and their distinction is desired, are pronounced separately and written as V`'`V.
	2. Otherwise say VV.
		1. If one of the vowels is non-tonal, say the dipthong with the tone of the tonal one
3. a voiced consonant cannot occur next to its unvoiced pair and vice versa (e.g. no `pb`)
4. \[NYI\] Something something sonority hierarchy for onset
	1. a>e>i>\[r ř l\]>\[m n ŋ\]>\[v z ž x\]>\[f s š h\]>\[b d g\]>\[p t k\]
5. \[NYI\] rules for replacing illegal strings with legal ones

## Grammar

### Parts of Speech:
- **Terminators**: These are intransitive verbs and nouns, things which (generally) form the beginning or end of a sentence.

- **Relations**: These (as the name suggests) are verbs which form a relation between two (or more) loci (so things like "A loves B")

	- As a note the irregular relation (`ō`) is called a **path**, which while not entirely its own grammatical category, is interesting in its own right. It may function as a relation (depicting change from something to something else) or a kind of special terminator (placing something within a range).

- **Particles**: In addition to serving as grammatical modifiers (conjugation, clarifying medium, & kind), they may serve as terminators or relations to relations (e.g. how "liked that" in "I liked that she grabbed flowers" forms a relation between "I" and "grabbed")

- **Decorations**: Grammatically, decorations are much like relations, just far less regular.

	- `ì` syllables are pronouns (which are rarely written) which serve as placeholder connections in linear or complex texts (in practice they are a special kind of relation which function like terminators)

	- `à` syllables are numbers and domain markers, which are written above or below a line to give more information (in practice a kind of particle which cannot serve as a terminator)

	- `ò` syllables are grouping words (including prepositions, parentheses, and [[#Cartouches]]) with a various ways of being written


### Word order
Word order is largely free, as relation functions are marked fairly clearly, however there are a few conventions:
- try to start and end sentences with terminators.
- if the order of inputs to a relation is important (e.g. "inside of"), then it should go between its arguments, preferring to say the group with the most animate participant first.
- if the order of inputs is not important, say the relation first (or last).
- Try to keep related sections clustered, prioritizing the most animate sections first (e.g. "My girlfriend, who is especially beautiful in dim lighting, came to the (dimly lit) bar with me." is preferable to "My girlfriend came to the bar with me. The bar's dim lighting made her look especially beautiful." unless the observation of her beauty is being emphasized as caused by being in the bar)
