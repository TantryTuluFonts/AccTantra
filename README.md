# AccTantra

**A single typing standard for every ASCII Tulu font.**

*Part of the [Tantry Tulu Font Foundry](https://github.com/TantryTuluFonts), by Prahlad Prasad Tantry.*

![AccTantra key chart](assets/keychart.png)

## What is AccTantra?

AccTantra is a typing standard for the Tulu language on ASCII-based fonts. You type with an ordinary keyboard, and an AccTantra font draws the Tulu letters. The same keystrokes work in every AccTantra font, so a text typed once can be shown in any of them.

The name is made of two words. *Accu* means to press or print, as in a printing press. *Tantra* means a text, theory, system, method or technique. Together, AccTantra means **"the doctrine of printing"**.

### Why it exists

Tulu is a Dravidian language with a rich history and culture, but support for its script in everyday software has been thin. Many ASCII Tulu fonts have been made over the years, each with its own idea of which key means which letter. Text typed for one font comes out as nonsense in another.

AccTantra fixes this at the keyboard level. Because every font follows the same key assignments, the underlying Latin text stays the same whichever font is applied on top.

## Quick start

1. Install an AccTantra font, for example one from the table below.
2. Choose that font in your editor or design tool.
3. Type using the keys in the [key chart](docs/KEYMAP.md).

**Example:** type `EAamAX nEma narayNay`, and any AccTantra font shows *Om namo Narayanaya*:

![Om namo Narayanaya in four AccTantra fonts](assets/example-om-namo-narayanaya.png)

## AccTantra fonts

These fonts all follow the AccTantra key assignments:

| Font | Style | Repository |
|---|---|---|
| Darage | OpenType (`.otf`), source available | [TantryTuluFonts/darage](https://github.com/TantryTuluFonts/darage) |
| Mandara | Bold, rounded | [TantryTuluFonts/mandara](https://github.com/TantryTuluFonts/mandara) |
| Allige | Academy edition | [TantryTuluFonts/allige](https://github.com/TantryTuluFonts/allige) |
| Mallige | Largest conjunct set | [TantryTuluFonts/mallige](https://github.com/TantryTuluFonts/mallige) |

The key chart above shows the same keys in all four, so you can compare how each one draws each letter.

## How the typing works

- **Letters on phonetic keys.** Consonants sit on the Latin letter they most resemble, and aspirated or related consonants use the Shift version of the same key (`k` is *ka*, `K` is *kha*). Keys are case-sensitive.
- **Inherent vowel.** A consonant alone already carries the short *a*. Other vowels are signs: after the consonant (`a` gives *ā*, `i`, `I`, `u`, `U`, `R`), before it (`e`, `E`, `o`, `O`), or around it (*o* and *ō* are `e...a` and `E...a`).
- **Independent vowels.** A vowel on its own is built on `A`, for example `Aa` is *ā* and `EAa` is *ō*.
- **The virama.** `A` after a consonant is the **chandravirama**, and `AX` is the **suryavirama** (the looped form, used on *k g ṭ ṇ t d n m h bh ḷ r*). Darage and Mallige draw the loop.
- **Conjuncts.** To join consonants, type consonant, `A`, consonant: `kAt`. The font substitutes the joined shape. See the [conjunct reference](docs/CONJUNCTS.md) for what each font supports.
- **Repha and doubling.** `f` after a consonant puts an *r* above it (`kmf` is *karma*), and `F` doubles a consonant.
- **Marks.** `M` is anusvara, `H` is visarga, and `MM` is candrabindu.
- **Digits.** The keys `0` to `9` give Tulu-script numerals.

The complete reference, every key with its IAST, Devanagari, Kannada and Malayalam equivalents, is in **[docs/KEYMAP.md](docs/KEYMAP.md)**.

## Convert text

The **[Tulu transliterator](https://prahladtantry.github.io/tulu-transliterator/)** converts between AccTantra text and IAST, Devanagari, Kannada or Malayalam in both directions. Use it to turn existing text into AccTantra keys, or to read AccTantra text in another script. It is also the reference implementation of this standard: the tables in the key map come from it.

## Documentation

| Page | What it covers |
|---|---|
| [Key map](docs/KEYMAP.md) | Every key: consonants, vowels, signs, virama, marks, with the visual chart |
| [Conjunct reference](docs/CONJUNCTS.md) | Which consonant pairs each font joins, generated from the fonts |
| [Typing examples](docs/EXAMPLES.md) | Real words with their keys, rendered and converted |

## Typing real Unicode instead

AccTantra is for ASCII fonts, where the text is stored as Latin characters. If you want to store Tulu as real Unicode text, the same typing logic is available as a keyboard:

- **[AccTantra_Unicode](https://github.com/TantryTuluFonts/AccTantra_Unicode)** is a Keyman keyboard for the Tulu-Tigalari script, following the AccTantra key logic.
- **[Mallige_unicode](https://github.com/TantryTuluFonts/Mallige_unicode)** is a Unicode font for the Tulu-Tigalari script, to display what the keyboard types.

## Goals

- **Make Tulu easy to type online.** Let people create and share Tulu text on websites, social media and documents.
- **Keep one standard.** Offer a single layout so that every present and future ASCII Tulu font is compatible.
- **Stay independent of the font.** The Latin text underneath never depends on which font is applied.
- **Support preservation.** Help document, study and revitalise the language in the digital era.
- **Enable cultural expression.** Give Tulu speakers a way to write their literature and traditions in their own script.

## License

AccTantra is licensed under the **SIL Open Font License, Version 1.1**. You may use, study, modify and redistribute it freely, provided it is not sold on its own and derivative works stay under the same license. The full text is in [OFL.txt](OFL.txt), and a FAQ is at <https://openfontlicense.org>.

Copyright (c) 2025-2026, Prahlad Prasad Tantry.

## Contributing

AccTantra is meant to be extended by the community. Corrections, additional fonts that follow the standard, and documentation fixes are all welcome. Please [open an issue](https://github.com/TantryTuluFonts/AccTantra/issues) to discuss a change.

## Author

Designed and maintained by **Prahlad Prasad Tantry** · [Tantry Tulu Font Foundry](https://github.com/TantryTuluFonts)
