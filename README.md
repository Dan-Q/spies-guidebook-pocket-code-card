# Spy's Guidebook Pocket Code Card (Digital Edition)

Usborne Publishing's _Spy's Guidebook_ was one of my favourite childhood books when it was published in 1989. I was delighted to see it inspiring a new generation when in 2021 my seven year-old fell in love with her copy of the book (the 2007 edition) too.

Pages 24-25 of the 2007 edition propose a symmetric substitution cipher based on a quarter-folding card whose visible parts dictate the message key (from eight practical permutations) and illustrate the transformations. My 7 year-old and I have been playing with this algorithm and using it as a vehicle to talk about encryption in general, the strengths and limitations of symmetric ciphers, and about attacks of the known-plaintext and frequency analysis types.

This repository contains a HTML+JS implementation of the cipher, plus a printable PDF for easily making a paper-based variant. An explanatory blog post will follow.

## Try it

You can try it online at https://danq.dev/spy-pocket-code/

## Usage

To use the digital version, open `index.html` in your browser. Select two key cards using the dropdowns (you'll see a preview of them), and type your message into the first of the two text boxes below. The output will be shown in the second text box. As a symmetric cipher, use the same process to decode: put ciphertext in the top box, get plaintext out of the bottom.

To use the paper version, [download and print the PDF](https://raw.githubusercontent.com/Dan-Q/spies-guidebook-pocket-code-card/main/printable-card.pdf) (colour printing highly recommended), duplexed on the short edge. You'll get three copies on a single sheet of A4 paper. Cut around, and fold between each block. To encipher/decipher, manipulate the paper along the folds to show the correct two key blocks. Transform each character in your message by finding it and swapping it for the character in the same column and the same coloured background. For more details, see the _Spy's Guidebook_ by Usborne Publishing.

## License

The CSS code embeds the font Source Code Pro, used under the Open Font License.

All other code and the included PDF are made freely available for any purpose under the Unlicense.
