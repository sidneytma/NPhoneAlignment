# Forced Alignment of Phone Groupings
*A tool for automated time-stamping of diphones, triphones, and all n-phones.*

Phonetic alignment (annotating the time positions of phonemes) is an important task both for phonetic research and natural language processing tools. Because it is so tedious and time-consuming, automated forced alignment is an extremely useful tool. However, most tools, including Jian Zhu's [Charsiu forced alignment](https://github.com/lingjzhu/charsiu), only annotate single phonemes. In practice, larger phone groupings (particularly diphones) are more useful to annotate, as they account for coarticulation effects which can often completely change the sound of single phonemes.

Thus, my goal is to create and demonstrate a tool that extends Charsiu forced alignment, by aligning the time positions to phone groupings of a user-specified size.
