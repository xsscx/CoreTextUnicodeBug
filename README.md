# CoreTextUnicodeBug
CoreText Unicode Bug on OSX 10.13.3 using LLDB, BackTrace, Registers


The original sequence is U+0C1C U+0C4D U+0C1E U+200C U+0C3E, which is a sequence of Telugu characters: the consonant ja (జ), a virama ( ్ ), the consonant nya (ఞ), a zero-width non-joiner, and the vowel aa ( ా)
