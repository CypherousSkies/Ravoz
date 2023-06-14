# Phonology
## Vowels
There are 3 vowels — `a`, `i`, `o` — and three tones — rising (first, `á`), constant (second, `ā`), falling (third, `à`), and no tone (zeroth, unstressed, `a` or `ȧ`). They can be written as either vowel-number (e.g. `a1` meaning /a/ with rising tone, with `a` meaning /a/ with no tone) or with their pinyin equivalents (e.g. `á` meaning /a/ with rising tone, `ȧ` or `a` for no tone).
All vowel-tone pairs are represented by [[#Glyphs]] (unit of written information) and is modified by at most one consonant in the onset marking meaning and sometimes a syllable-final consonant to mark for grammar.
In general, changing tone corresponds to terminators, constant tone to relations, and no tone to particles. (edit 5/15/23: yeah this was from an old version of the language in which i planned to have three tones total: )
Additionally, in transliteration it is also acceptable to write in the direction of the changing tones with acute and grave markings, though this has makes no semantic difference (except perhaps as a meta-textual spoken-only way to emphasize a reversal of time). (edit 5/12/22: i have no idea what this paragraph means so feel free to discard it)

### Atonal dialect
I am also considering making an [[Ouwi]]-style dialect which replaces tones with a variety of non-tonal vowels. I'm also considering giving alternatives for the retroflex sounds for those that find them difficult. I'm happy to hear feedback/suggestions on this, but the spoken part of the language was never really going to be the most important feature of the language. 

## Consonants
\- | labial |  coronal | retroflex |  velar 
-|-|-|-|-
plosive| `p`/p/ `b`/b/ | `t`/t/ `d`/d/ |  | `k`/k/ `g`/g/ 
nasal| `m`/m/ |  `n`/n/ | | `ŋ`/ŋ/
fricative| `f`/f/ `v`/v/ | `s`/s/ `z`/z/ | `š`/ʂ/ `ž`/ʐ/ | `h`/x/ `x`/ɣ/ 
approximants| | `r`/r,ɾ/ `l` /l/ | `ř`/ɻ/ | 
![[full-table.png]]
Consonants are [[Writing#Consonant Markings|written]] as modifying a vowel (which should make sense, as the vowel determines the function of a root). 

### Consonant Groupings
Some consonants sound similar and so have clustered meanings:
nasals: `m n ŋ`
stops: `b d p t`
fricatives: `s f š ž v z`
approx: `r l ř`
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