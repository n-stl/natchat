# natchat
A Tamil romanization scheme for casual microblogging and frequent Web use.

Goals:
- improve upon previous schemes including [ISO 15919](https://en.wikipedia.org/wiki/ISO_15919), 7-bit ISO, and [ITRANS](https://en.wikipedia.org/wiki/ITRANS), while being particularly suited to Tamil phonology
- easy to type with a standard ASCII keyboard, and easy to read by an American English speaker, without sacrificing phonological accuracy
- easy to mentally convert into spoken Tamil

Features:
- all lower case for ease of reading
- usage of : for long vowels and - for nasals
- usage of . preceding retroflex consonants (like 7-bit ISO)
- retroflex approximant ழ் gains a more intuitive representation (no 'zh')
- English loanwords may be typed with English spelling

## sample text

| tamil script | IPA | ITRANS | ISO | 'orthographical' natchat | 'simple' natchat |
| --- | --- | --- | --- | --- | --- |
| மனிதப் பிறவியினர் சகலரும் சுதந்திரமாகவே பிறக்கின்றனர் | mənid̪əp‿piriʋijinər səgələrum sud̪ən̪d̪irəmaːgəʋeː pirəkːin̺d̺ranər | ma^nithap piRaviyi^nar chagalarum chudhandhiramAgavE piRakki^nRa^nar | maṉitap piṟaviyiṉar cakalarum cutantiramākavē piṟakkiṉṟaṉar | manidhap pi^raviyinar cagalarum cudha_ndhirama:gave: pi^rakkind^ranar | manidha piraviyinar sagalarum sudhandhirama:gave: pirakkindranar |

Some immediate differences become apparent:
- Unlike ISO transliteration, natchat captures spoken allophones and pronunciation changes (medial k becoming g, th becoming dh, c becoming s, intrusive t/d in trill combinations)
- Unlike ISO, no need for diacritics above/below letters
- Unlike ITRANS, all letters are lowercase for ease of reading, and more common letters take more common representations (e.g. ன் = n)
- Flexibility to be adapted for more or less orthographical or phonological specificity; 'simple' natchat drops distinctions between dental/alveolar n and tap/trill r, and is suited to everyday web use

## vowels
natchat vowels are broadly similar to IPA, apart from ä being simplified to a. Spoken nasalization can be simply depicted with -.

| tamil vowel | natchat equivalent | [IPA](https://en.wikipedia.org/wiki/Help:IPA/Tamil) |
| --- | --- | --- |
| அ | a | ä |
| ஆ | a: | äː |
| இ | i | i |
| ஈ | i: | iː |
| உ | u | u |
| ஊ | u: | uː |
| எ | e | e |
| ஏ | e: | eː |
| ஐ | ai | aɪ̯ |
| ஒ | o | o |
| ஓ | o: | oː |
| ஔ | au | aʊ̯ |
| (nasalization, spoken only) | - (hyphen following vowel) | nasal vowel ([ãː], [õː], etc.) |
| (shortened உ or இ, spoken only <sup>1</sup>) | u/ or i/ | ɯ~ɨ |

1. Word final /u/ is pronounced as [ɯ], this phenomenon is called குற்‌றியலுகரம்‌ (kut^riyalugaram). This representation u/ is optional and may be used if phonological accuracy is desired. Similarly, /i/ preceding /j/ is shortened.

## consonants
Retroflex consonants are written with a preceding period, apart from ழ் which is written \r to represent its rough similarity to AmEng "r". Doubled retroflex consonants may be written with a single preceding period for simplicity, for example ku.tti குட்டி. Dental consonants can be written with a preceding underscore if necessary.

| tamil consonant | natchat equivalent (with allophones) | [IPA](https://en.wikipedia.org/wiki/Help:IPA/Tamil) |
| --- | --- | --- |
| க் | k (or g) | k, medial g ~ x ~ ɣ |
| ங் | ng | ŋ |
| ச் | c (or s) | t͡ɕ ~ t͡ʃ, medial s, postnasal dʑ~dʒ |
| ஞ் | ~n | ɲ |
| ட் | .t (or .d, or t or d <sup>1</sup>) | ʈ, medial ɖ~ɽ |
| ண் | .n | ɳ |
| த் | th (or dh) | t̪ ~ θ, medial d̪ ~ ð |
| ந் | _n or n <sup>2</sup> | n̪ |
| ப் | p (or b) | p, medial b~β |
| ம் | m | m |
| ய் | y | j |
| ர் | r | ɾ |
| ல் | l | l |
| வ் | v | ʋ |
| ழ் | \r | ɻ |
| ள் | .l | ɭ |
| ற் | ^r or r <sup>2</sup> | r |
| (doubled consonant) | letter written twice | consonant+ ː|
| ற்ற | t^r or tr <sup>3</sup> | tːr |
| ன்ற | nd^r or ndr <sup>3</sup> | ndr |
| ஞ்ச | nj <sup>3</sup> | n̠ʲd̠ʒ |

Notes:
1. .t and .d can be alternatively written t and d since there is no equivalent alveolar sound in written Tamil, thus no confusion in a Tamil context. However, since they are unique from AmEng "t" and "d", to preserve retroflex representation, they are written here with a period preceding. 
2. If it is unnecessary to distinguish ன் from ந், both can be written as n. Similarly, if it is unnecessary to distinguish ர் from ற், both can be written as r.
3. For ease of representing the phonetic change caused by Tamil grammar for digraphs ற்ற and ன்ற, a t or d is placed in between the consonants, respectively. Similarly, for representing the phonetic change in the digraph ஞ்ச, it can simply be written nj rather than ~nc.

Loaned [Grantha](https://en.wikipedia.org/wiki/Tamil_script#Extra_consonants_used_in_Tamil) consonants:
| grantha consonant | natchat equivalent | [IPA](https://en.wikipedia.org/wiki/Help:IPA/Tamil) |
| --- | --- |
| ஜ | j | dʑ |
| ஶ் | `s | ɕ |
| ஷ் | sh | ʂ |
| ஸ் | s | s |
| ஹ் | h | h |
| க்ஷ் | ksh | kʂ |
