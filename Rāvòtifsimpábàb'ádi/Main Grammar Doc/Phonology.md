# Phonology
## Vowels
There are 3 vowels — `a`, `i`, `o` — and three tones — rising (first, `á`), constant (second, `ā`), falling (third, `à`), and no tone (zeroth, unstressed, `a` or `ȧ`). They can be written as either vowel-number (e.g. `a1` meaning /a/ with rising tone, with `a` meaning /a/ with no tone) or with their pinyin equivalents (e.g. `á` meaning /a/ with rising tone, `ȧ` or `a` for no tone).
All vowel-tone pairs are represented by [[#Glyphs]] (unit of written information) and is modified by at most one consonant in the onset marking meaning and sometimes a syllable-final consonant to mark for grammar.

## Consonants
When two pronunciations are listed, the left is what I've historically envisioned, the right is what I've moved toward as I've tried to get people to learn the language. I'm making an effort to use the 'more modern' romanization, but I provide it both as historical reference and because I've almost certainly missed places. 

| \-           | labial        | coronal                | retroflex          | velar         |
| ------------ | ------------- | ---------------------- | ------------------ | ------------- |
| plosive      | `p`/p/ `b`/b/ | `t`/t/ `d`/d/          |                    | `k`/k/ `g`/g/ |
| nasal        | `m`/m/        | `n`/n/                 |                    | `ŋ`/ŋ/        |
| fricative    | `f`/f/ `v`/v/ | `s`/s/ `z`/z/          | `š`/ʂ~ʃ/ `ž`/ʐ~dʒ/ | `h`/x/ `x`/ɣ/ |
| approximants |               | `r`/r,ɾ/ `l`~`w` /l~ʋ/ | `ř`~`j`/ɻ~j/       |               |

![[full-table.png]]
Consonants are [[Writing#Consonant Markings|written]] as modifying a vowel (which should make sense, as the vowel determines the function of a root). 

### Vowel Accessibility?
I am also considering making an [[Thek'nganosh/Ouwi]]-style dialect which replaces tones with a variety of non-tonal vowels. I'm happy to hear feedback/suggestions on this, but the spoken part of the language was never really going to be the most important feature of the language. 

### Consonant Groupings
Some consonants sound similar and so have clustered meanings:
nasals: `m n ŋ`
stops: `b d p t`
fricatives: `s f š ž v z`
approx: `r w j`
velar: `g k h x`

## Phonotactics
Rules!
1. Syllables are (C)V(C)
	1. While there is almost always a consonant to the left (which modifies the specific meaning of the syllable within the function of the vowel), only a few consonants may appear to the right
	2. The only consonants which may appear to the right of every vowel are `p` (short for `pò`) and `z` (short for `zò`), which only appear in particular grammatical contexts, see [[ì-Pronouns#`pò`/`zò` construction]] and [[Grammar#Polysyllabic construction]] for more info
2. Dipthongs are allowed but only as shortenings
	1. If two vowels are next to each other and their distinction is desired, are pronounced separately and written as V`'`V.
	2. Otherwise say VV.
		1. If one of the vowels is non-tonal, say the dipthong with the tone of the tonal one
3. a voiced consonant cannot occur next to its unvoiced pair and vice versa (e.g. no `pb`)
4. Something something sonority hierarchy for onset (deprecated, there were originally plans for rāvòz to be CCVC, but I have long since abandoned those)
	1. a>e>i>[r ř l]>[m n ŋ]>[v z ž x]>[f s š h]>[b d g]>[p t k]
5. rules for replacing illegal strings with legal ones