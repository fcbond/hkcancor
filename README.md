# Hong Kong Cantonese Corpus (HKCanCor) 香港粵語語料庫

These are the transcriptions of the Hong Kong Cantonese Corpus
(HKCanCor) 香港粵語語料庫 created by Luke Kang Kwong <kkluke@ntu.edu.sg>.

## Introduction 簡介


The Hong Kong Cantonese Corpus was collected from transcribed
conversations that were recorded between March 1997 and August 1998.
About 230,000 Chinese words were collected in the annotated corpus. It
contains recordings of spontaneous speech (51 texts) and radio
programmes (42 texts), which involve 2 to 4 speakers, with 1 text of
monologue. The text were word-segmented, annotated with part-of-speech
tagging and Cantonese pronunciation using the romanisation scheme of
Linguistic Society of Hong Kong (LSHK).

香港粵語語料庫收錄了在1997年3月至1998年8月期間修錄整理的粵語談話內容。本語料庫修錄了93段2至4人的對話（其中51段是在交談時錄音所得﹐另外42段由電台節目剪輯而成）和1段個人獨白﹐修錄詞語合計約有230,000個。語料以詞語作單位切分﹐並標上發音及詞性。發音部份使用了香港語言學學會(LSHK)的粵拼標準。

### Downloads 下載

-   [Corpus Specification 語料庫格式](data/format_v.pdf)
-   [README](data/README)
-   [LICENSE (CC BY)](data/LICENSE)
-   Monologue 口述\
    [Recording 錄音 (mp3)](sample/m.mp3) /  [Tagged
    標注 (big5-hkscs)](sample/m_v.txt) /  [Non-tagged
    無標注 (big5-hkscs)](sample/m_h.txt) / 
-   Dialogue 1 對話1\
    [Recording 錄音 (mp3)](sample/d1.mp3) /  [Tagged
    標注 (big5-hkscs)](sample/d1_v.txt) /  [Non-tagged
    無標注 (big5-hkscs)](sample/d1_h.txt) / 
-   Dialogue 2 對話2\
    [Recording 錄音 (mp3)](sample/d2.mp3) /  [Tagged
    標注 (big5-hkscs)](sample/d2_v.txt) /  [Non-tagged
    無標注 (big5-hkscs)](sample/d2_h.txt) / 
-   Radio 1 收音機1\
    [Recording 錄音 (mp3)](sample/r1.mp3) /  [Tagged
    標注 (big5-hkscs)](sample/r1_v.txt) /  [Non-tagged
    無標注 (big5-hkscs)](sample/r1_h.txt) / 
-   Radio 2 收音機2\
    [Recording 錄音 (mp3)](sample/r2.mp3) /  [Tagged
    標注 (big5-hkscs)](sample/r2_v.txt) /  [Non-tagged
    無標注 (big5-hkscs)](sample/r2_h.txt) / 
-   Full Text 完整文件\
    [BIG5-HKSCS (zipped, transcriptions only,
    no sound)](data/hkcancor-big5hkscs.zip)\
    [UTF8 (zipped, transcriptions only,
    no sound)](data/hkcancor-utf8.zip)

Unfortunately, only samples of the sound are available for download, the complete files were not released.

## Citation
If you use them, please cite:

K. K. Luke and May L.Y. Wong (2015)[The Hong Kong Cantonese Corpus:
Design and Uses](data/LukeWong_Hong-Kong-Cantonese-Corpus.pdf) *Journal of Chinese Linguistics* (to appear).

### Links

-   [PyCantonese: Working with Cantonese corpus data using
    Python](https://github.com/pycantonese/pycantonese) by Jackson L.
    Lee



## License
They are released under a CC BY license.
<http://creativecommons.org/licenses/by/4.0/legalcode>

> You are free to:
>
>   Share — copy and redistribute the material in any medium or format
>
>   Adapt — remix, transform, and build upon the material
>   for any purpose, even commercially.
> 
> The licensor cannot revoke these freedoms as long as you follow the license terms.
> 
> Under the following terms:
> 
>   Attribution — You must give appropriate credit, provide a link to
>   the license, and indicate if changes were made. You may do so in
>   any reasonable manner, but not in any way that suggests the
>   licensor endorses you or your use.
> 
>   No additional restrictions — You may not apply legal terms or
>   technological measures that legally restrict others from doing
>   anything the license permits.
> 

### Tagset

See the paper for a full description.

| No. | Tag | POS (in Chinese) | POS (in English)                 |
|-----|-----|------------------|----------------------------------|
| 1   | Ag  | 形语素           | Adjective Morpheme               |
| 2   | a   | 形容词           | Adjective                        |
| 3   | ad  | 副形词           | Adjective as Adverbial           |
| 4   | an  | 名形词           | Adjective with Nominal Function  |
| 5   | Bg  | 区别语素         | Non-predicate Adjective Morpheme |
| 6   | b   | 区别词           | Non-predicate Adjective          |
| 7   | c   | 连词             | Conjunction                      |
| 8   | Dg  | 副语素           | Adverb Morpheme                  |
| 9   | d   | 副词             | Adverb                           |
| 10  | e   | 叹词             | Interjection                     |
| 11  | f   | 方位词           | Directional Locality             |
| 12  | g   | 语素             | Morpheme                         |
| 13  | h   | 前接成分         | Prefix                           |
| 14  | i   | 成语             | Idiom                            |
| 15  | j   | 简略语           | Abbreviation                     |
| 16  | k   | 后接成分         | Suffix                           |
| 17  | l   | 习用语           | Fixed Expression                 |
| 18  | Mg  | 数语素           | Numeric Morpheme                 |
| 19  | m   | 数词             | Numeral                          |
| 20  | Ng  | 名语素           | Noun Morpheme                    |
| 21  | n   | 名词             | Common Noun                      |
| 22  | nr  | 人名             | Personal Name                    |
| 23  | ns  | 地名             | Place Name                       |
| 24  | nt  | 机构团体         | Organisation Name                |
| 25  | nx  | 外文字符         | Nominal Character String         |
| 26  | nz  | 其它专名         | Other Proper Noun                |
| 27  | o   | 拟声词           | Onomatopoeia                     |
| 28  | p   | 介词             | Preposition                      |
| 29  | Qg  | 量语素           | Classifier Morpheme              |
| 30  | q   | 量词             | Classifier                       |
| 31  | Rg  | 代语素           | Pronoun Morpheme                 |
| 32  | r   | 代词             | Pronoun                          |
| 33  | s   | 处所词           | Space Word                       |
| 34  | Tg  | 时间语素         | Time Word Morpheme               |
| 35  | t   | 时间词           | Time Word                        |
| 36  | Ug  | 助语素           | Auxiliary Morpheme               |
| 37  | u   | 助词             | Auxiliary                        |
| 38  | Vg  | 动语素           | Verb Morpheme                    |
| 39  | v   | 动词             | Verb                             |
| 40  | vd  | 副动词           | Verb as Adverbial                |
| 41  | vn  | 名动词           | Verb with Nominal Function       |
| 42  | w   | 标点符号         | Punctuation                      |
| 43  | x   | 非语素字         | Unclassified Item                |
| 44  | Yg  | 语气语素         | Modal Particle Morpheme          |
| 45  | y   | 语气词           | Modal Particle                   |
| 46  | z   | 状态词           | Descriptive                      |
