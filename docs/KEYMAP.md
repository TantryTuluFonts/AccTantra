# AccTantra key map

This is the complete AccTantra key assignment for ASCII Tulu fonts. You type with a normal keyboard and the font draws the Tulu letters. Every table here is generated from the rules of the [Tulu transliterator](https://tantrytulufonts.github.io/tulu-transliterator/) (the "Mallige encoding"), which is the reference implementation of this scheme, so they always agree.

The picture shows every letter and digit key and the glyph it gives in each AccTantra font (Darage, Mandara, Allige, Mallige, in that order):

![AccTantra key chart](../assets/keychart.png)

**How to read the tables.** Keys are case-sensitive: `n` and `N` are different letters. IAST is the romanisation used in the transliterator; the Devanagari, Kannada and Malayalam columns show the same letter in those scripts for comparison.

## Consonants

| Keys | IAST | Devanagari | Kannada | Malayalam |
|---|---|---|---|---|
| `k` | k | क | ಕ | ക |
| `K` | kh | ख | ಖ | ഖ |
| `g` | g | ग | ಗ | ഗ |
| `G` | gh | घ | ಘ | ഘ |
| `Z` | ṅ | ङ | ಙ | ങ |
| `c` | c | च | ಚ | ച |
| `C` | ch | छ | ಛ | ഛ |
| `j` | j | ज | ಜ | ജ |
| `J` | jh | झ | ಝ | ഝ |
| `z` | ñ | ञ | ಞ | ഞ |
| `q` | ṭ | ट | ಟ | ട |
| `Q` | ṭh | ठ | ಠ | ഠ |
| `w` | ḍ | ड | ಡ | ഡ |
| `W` | ḍh | ढ | ಢ | ഢ |
| `N` | ṇ | ण | ಣ | ണ |
| `t` | t | त | ತ | ത |
| `T` | th | थ | ಥ | ഥ |
| `d` | d | द | ದ | ദ |
| `D` | dh | ध | ಧ | ധ |
| `n` | n | न | ನ | ന |
| `p` | p | प | ಪ | പ |
| `P` | ph | फ | ಫ | ഫ |
| `b` | b | ब | ಬ | ബ |
| `B` | bh | भ | ಭ | ഭ |
| `m` | m | म | ಮ | മ |
| `y` | y | य | ಯ | യ |
| `r` | r | र | ರ | ര |
| `l` | l | ल | ಲ | ല |
| `v` | v | व | ವ | വ |
| `L` | ḷ | ळ | ಳ | ള |
| `S` | ś | श | ಶ | ശ |
| `x` | ṣ | ष | ಷ | ഷ |
| `s` | s | स | ಸ | സ |
| `h` | h | ह | ಹ | ഹ |
| `VZ` | ḻ | ळ | ೞ | ഴ |
| `Vr` | ṟ | ऱ | ಱ | റ |
| `VP` | f | फ़ | ಫ | ഫ |
| `Vj` | z | ज़ | ಜ | ജ |

The four letters with a two-key sequence beginning with `V` (`VZ`, `Vr`, `VP`, `Vj`) are the extra consonants used for sounds outside the core set.

## Independent vowels

A vowel on its own (not attached to a consonant) is typed with `A` as a base:

| Keys | IAST | Devanagari | Kannada | Malayalam |
|---|---|---|---|---|
| `AAMM` | aṁ | अँ | ಅಁ | അഁ |
| `AAM` | aṃ | अं | ಅಂ | അം |
| `AAH` | aḥ | अः | ಅಃ | അഃ |
| `ARR` | r̥̄ | ॠ | ೠ | ൠ |
| `Vll` | ḹ | ॡ | ೡ | ൡ |
| `VlX` | l̥ | ऌ | ಌ | ഌ |
| `Vl` | l̥ | ऌ | ಌ | ഌ |
| `eeA` | ai | ऐ | ಐ | ഐ |
| `EAa` | ō | ओ | ಓ | ഓ |
| `eAa` | o | ऒ | ಒ | ഒ |
| `EA` | ē | ए | ಏ | ഏ |
| `eA` | e | ऎ | ಎ | എ |
| `OA` | ǣ | ए | ಏ | ഏ |
| `oA` | æ | ऎ | ಎ | എ |
| `AY` | au | औ | ಔ | ഔ |
| `AR` | r̥ | ऋ | ಋ | ഋ |
| `AU` | ū | ऊ | ಊ | ഊ |
| `Au` | u | उ | ಉ | ഉ |
| `AI` | ī | ई | ಈ | ഈ |
| `Ai` | i | इ | ಇ | ഇ |
| `Aa` | ā | आ | ಆ | ആ |
| `AA` | a | अ | ಅ | അ |

`AA` followed by `A` (that is, `AAA`) gives the reduced vowel ụ.

## Vowel signs

The inherent vowel *a* needs no key: a consonant alone already carries it (`k` is *ka*). Other vowels attach to a consonant as signs. The "Example" column shows the keys for *k* with each vowel.

| Vowel (IAST) | Sign key | Where it goes | Example | Devanagari | Kannada | Malayalam |
|---|---|---|---|---|---|---|
| ā | `a` | after the consonant | `ka` | का | ಕಾ | കാ |
| i | `i` | after the consonant | `ki` | कि | ಕಿ | കി |
| ī | `I` | after the consonant | `kI` | की | ಕೀ | കീ |
| u | `u` | after the consonant | `ku` | कु | ಕು | കു |
| ū | `U` | after the consonant | `kU` | कू | ಕೂ | കൂ |
| r̥ | `R` | after the consonant | `kR` | कृ | ಕೃ | കൃ |
| r̥̄ | `RR` | after the consonant | `kRR` | कॄ | ಕೄ | കൄ |
| l̥ | `VlX` | after the consonant | `kVlX` | कॢ | ಕೢ | കൢ |
| ḹ | `VllX` | after the consonant | `kVllX` | कॣ | ಕೣ | കൣ |
| e | `e` | before the consonant | `ek` | कॆ | ಕೆ | കെ |
| ē | `E` | before the consonant | `Ek` | के | ಕೇ | കേ |
| æ | `o` | before the consonant | `ok` | कॆ | ಕೆ | കെ |
| ǣ | `O` | before the consonant | `Ok` | के | ಕೇ | കേ |
| ai | `EE` | before the consonant | `EEk` | कै | ಕೈ | കൈ |
| o | `e … a` | around the consonant | `eka` | कॊ | ಕೊ | കൊ |
| ō | `E … a` | around the consonant | `Eka` | को | ಕೋ | കോ |
| au | `E … Y` | around the consonant | `EkY` | कौ | ಕೌ | കൌ |

The vowels ṃ, ḥ and ṁ in this table are the nasal and visarga marks; see "Marks" below. Wherever a table says "before the consonant", type the vowel key *first*: the font draws the sign to the left of the consonant, so you type the shape you see in the order you see it.

## Virama, conjuncts and other controls

| Keys | What it does | Example |
|---|---|---|
| `A` | **Chandravirama.** Cancels the inherent vowel and draws the crescent mark. | `kA` |
| `AX` | **Suryavirama.** The same, drawn with the looped mark, used on the consonants listed below. | `kAX` |
| consonant + `A` + consonant | **Conjunct.** Joins two or more consonants into one cluster. | `kAt` |
| `f` after a consonant | **Repha.** Puts an *r* before it, drawn above the cluster. | `kmf` is *karma* |
| `F` after a syllable | **Gemination.** Doubles the last consonant. | |
| `X` | Zero-width non-joiner. Stops two consonants from joining. | |

The suryavirama is used on these consonants: *k*, *g*, *ṭ*, *ṇ*, *t*, *d*, *n*, *m*, *h*, *bh*, *ḷ*, *r*. The transliterator writes `AX` after them automatically. Darage and Mallige draw the loop; Mandara and Allige draw the same mark for `A` and `AX`.

## Marks and punctuation

| Keys | Result |
|---|---|
| `M` | anusvara (ṃ) |
| `H` | visarga (ḥ) |
| `MM` | candrabindu (ṁ) |
| `.` | danda (।). Mallige draws it; Darage, Mandara and Allige show a full stop |
| `..` | double danda (॥) |
| `,` | comma |

## Digits

The digit keys `0` to `9` show the Tulu-script numerals in the fonts. The transliterator leaves digits unchanged when converting to other scripts.

## Convert text

The [Tulu transliterator](https://tantrytulufonts.github.io/tulu-transliterator/) converts between AccTantra text and IAST, Devanagari, Kannada or Malayalam, in both directions. It is the quickest way to check a spelling or to move existing text into AccTantra.

See also: [Conjunct reference](CONJUNCTS.md) · [Typing examples](EXAMPLES.md)
