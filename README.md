# plaintext-bible-kjv
Plaintext King James Bible, divided by book - excellent for text parsing. Optimized for awk.

Fields are separated by `::`.

`$1 = book_num`
`$2 = book_abrev`
`$3 = chapter_num`
`$4 = verse_num`
`$5 = text`

`book_num::book_abrev::chapter_num::verse_num::text`

`01::gen::1::1::In the beginning God created the heaven and the earth.`

The text does not currently show italicization. Ideally, text with hyphenization, footnotes and margin numbers would be the 6th field and the notes themselves would be the 7th field.
