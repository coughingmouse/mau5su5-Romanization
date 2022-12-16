# Mau\su\ Standard Chinese Romanization

Yet Another Chinese Romanization

## Description

There's bopomofo which makes great use of the Chinese phonology, but there's no equivalent romanization! So here I give a demonstration of a system that should do just that by remapping Pinyin.

I made it for just that, but I feel like it could be more useful so I've set more casual variant as default.

## Demonstration

|  | ∅ | ∅ | ∅ | i | i | o | o | n | n | ng | ng |
| - | - | - | - | - | - | - | - | - | - | - | - |
| ∅ | (?ux) | e- | a/ | eiv | ai\ | eux | au | en | an | eng | ang |
| j | i | ie | ia | | | iu | iau | in | ian | ing | iang |
| w | o | oe | oa | oi | oai | | | on | oan | ong | oang |
| y | ü | üe | | | | | | ün | üan | üng | |

* Tones can be marked by 1 for in-ping/, 2 for iang/ping/, 3 for sjangv, and 5 for qü\. ⟨x⟩ is added after toneless (cing-) syllable.

Other phonemes are deriven from Pinyin but there are these following exceptions:

| else | |
| - | - |
| ê | ä |
| er | r |
| yai | iai |
| o | ow |
| io | iow |
| ri | j |
| shi | sj |
| si | su |
| xi | si |
| xu | sy |
| zhi | zj |
| zi | zu |
| ji | zi |
| ju | zy |
| chi | cj |
| ci | cu |
| qi | ci |
| qu | cy |
| g? | q? |

* Every part of Standard Mandarin syllable should be present, especially the tonal markings.
* ⟨y⟩ instead of ⟨ü⟩ and ⟨ae⟩ instead of ⟨ä⟩ can be used.
* The system can be altered to remove ⟨n⟩ before ⟨g⟩.
* The system can be altered to use ⟨yu⟩ instead of ⟨ü⟩.
* The system can also be altered to include ⟨e⟩ before coda either after glide or regardless.

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

- mapping /k/ to ⟨q⟩ (and /-ng/ to ⟨g⟩) is unusual in the context of transcription of the sort
- using ⟨x⟩ not as an alphabet is new

## Design Principles
* Use bopomofo-based two vowel analysis 
* Be readable
* Make sense
* Be usable
* Be typable with Qwerty keyboard for usability
* Expanded letter should be typable with US international keyboard
* Be compatible for passport names

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
