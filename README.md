# Maw3su5 Standard Mandarin Romanization

Yet Another Chinese Romanization

## Description

There's bopomofo which makes great use of the Chinese phonology, but there's no equivalent romanization! So here I give a demonstration of a system that should do just that by remapping Pinyin.

## Demonstration

|  | ∅ | ∅ | ∅ | i | i | o | o | n | n | ng | ng |
| - | - | - | - | - | - | - | - | - | - | - | - |
| ∅ | (?u) | e1 | a2 | ei3 | ai5 | ew(x) | aw | en | an | eg | ag |
| j | i | ie | ia | | | iew | iaw | ien | ian | ieg | iag |
| w | w | we | wa | wei | wai | | | wen | wan | weg | wag |
| y | y | ye | | | | | | yen | yan | yeg | |

* Tones must be marked by 1 for in1ping2, 2 for iang2ping2, 3 for sjang3, and 5 for qyu5. X is added after toneless (cing1) syllable when before other alphabet.

Other phonemes are deriven from Pinyin but there are these following exceptions:

| else | |
| - | - |
| ê | ä |
| er | r |
| yai | iai |
| o | o |
| io | io |
| ri | j |
| shi | sj |
| si | su |
| xi | si |
| zhi | zj |
| zi | zu |
| ji | zi |
| chi | cj |
| ci | cu |
| qi | ci |
| g? | q? |

* Every part of Standard Mandarin syllable should be present, especially the tonal markings.
* The system can be altered to add ⟨n⟩ before ⟨g⟩.
* The system can be altered to add ⟨u⟩ after ⟨y⟩ or use ⟨ü⟩ instead of ⟨y⟩.
* The system can also be altered to omit ⟨e⟩ before coda.
* Diphthong ⟨ae⟩ is a valid but depressed alternative to ⟨ä⟩.

For comparison,

|  | ∅ | ∅ | ∅ | i | i | o | o | n | n | ng | ng |
| - | - | - | - | - | - | - | - | - | - | - | - |
| ∅ | (˙?ㄭ) | ㄜ | ㄚˊ | ㄟˇ | ㄞˋ | ㄡˉ | ㄠ | ㄣ | ㄢ | ㄥ | ㄤ |
| j | ㄧ | ㄧㄝ | ㄧㄚ | | | ㄧㄡ | ㄧㄠ | ㄧㄣ | ㄧㄢ | ㄧㄥ | ㄧㄤ |
| w | ㄨ | ㄨㄛ | ㄨㄚ | ㄨㄟ | ㄨㄞ | | | ㄨㄣ | ㄨㄢ | ㄨㄥ | ㄨㄤ |
| y | ㄩ | ㄩㄝ | | | | | | ㄩㄣ | ㄩㄢ | ㄩㄥ | |

|  | ∅ | ∅ | ∅ | i | i | o | o | n | n | ng | ng |
| - | - | - | - | - | - | - | - | - | - | - | - |
| ∅ | ?i | ē | á | ěi | ài | ·ou | ao | en | an | eng | ang |
| j | yi/-i | ye/-ie | ya/-ia | | | you/-iao | yao/-iao | yin/-in | yan/-ian | ying/-ing | yang/-iang |
| w | wu/-u | wo/-uo | wa/-ua | wei/-ui | wai/-uai | | | wen/-un | wan/-uan | weng/-ong | wang/-uang |
| y | yu/-ü | yue/-üe | | | | | | yun/-ün | yuan/-üan | yong/-iong | |

***

## Characteristics
+ phonemically more relevant and consistent, possibly providing better learning experience for both L1 and L2 users
+ apostrophe not used within core system to let for other uses
+ hyphen too
+ if we exclude Pinyin and its derivatives, this system is actually more in line with existing uses of the letters

* ⟨v⟩ still not used

- mapping /k/ to ⟨q⟩, /-ng/ to ⟨g⟩, /x/ to ⟨x⟩ is unusual in the context of transcription of the sort

## Design Principles
* Use bopomofo-based two vowel analysis 
* Be readable
* Make sense
* Be usable
* Be typable with Qwerty keyboard for usability
* Expanded letter should be typable with US international keyboard

## Roadmap
+ Re-evaluation of phonemes considering historic phones and phonemes.

## Contributing
Whomever wishes to contribute may.

## Authors and acknowledgment
Iso Lee

## License
MIT

## Project status
Not very active
