> Written with [StackEdit](https://stackedit.io/).
> ## [List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words_V2](https://github.com/LDNOOBWV2/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words_V2#list-of-dirty-naughty-obscene-and-otherwise-bad-words_v2)
### 
This list of words is a follow-up and extension of the Shutterstock [List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words/tree/master) as that list is not maintained anymore. As there are many profanity word lists around on the web (and many not maintained) their content was crabbed and joined here together (see the source list below). 
###
As the opinion on which words should be in such lists varies between culture, language, and geographies, feel free to extend them to your needs. I hope to be able to collect more words in different languages and even more languages. The lists need reviews from native speakers, as many words are not known by me.
###
The long list of English words shows people got very creative to get around profanity filters, so in my opinion, the best way to use these hard-coded word lists is as an additional (of many) criteria for filtering texts like it is done in [RedPajama](https://github.com/togethercomputer/RedPajama-Data) data set.
The next TODO will be to create some regular expressions for often-used spelling variations.
### Structure and Format
 - filename is the **iso-code** of the country 
 - **utf-8** encoded
 - all words are **lowercase**
 - one expression per line
 - all words contained in the English "*en*" file are excluded in the other language files
 - often used words where the classification as a profane word is doubtful there is a separate csv file
 - the csv-file is: "*questionable_international_words.csv*" 
 - separator is the comma "**,**"
 - 152 words for several languages (see table below)
 - the header line contains the iso-code of the language, a classification column, and a remark column
 - these words are **NOT** included in the language-files
### Languages Files Overview
language | count | filename | in csv-file | remark
--- | --- | --- | --- | ---
 [Afrikaans](data/af)	  |  86	| af |	Y|
 [Albanian](data/sq) 	  | 122	| sq |	Y|
 [Amharic](data/am)     |  22 | am | N|
 [Arabic](data/ar)		    | 443	| ar |	N|
 [Armenian](data/hy)	   | 106	| hy |	Y|
 [Australian Kriol](data/rop)	|  12	| rop|	N|
 [Basque](data/eu)		    | 137	| eu |	N|
 [Belorussian](data/be)	| 118	| be |	N|
 [Bulgarian](data/bg)	  | 115	| bg |	Y|
 [Burmese](data/my)		   |  52	| my |	N|
 [Catalan](data/ca)		   |  65	| ca |	Y|
 [Cebu](data/ceb)		     |   7	| ceb|	N|
 [Chinese](data/zh)		   |1173	| zh |	Y|
 [Croatian](data/hr)	   | 115	| hr |	Y|
 [Czech](data/cs)		     | 187	| cs |	Y|
 [Danish](data/da)		    | 127	| da |	Y|
 [Dutch](data/nl)		     |1099	| nl |	Y|
 [English](data/en)		   |8053	| en |	Y| various spelling variations
 [Esperanto](data/eo)	  |  37	| eo |	N|
 [Estonian](data/et)	   | 114	| et |	Y|
 [Filipino](data/fil)	  | 103	| fil|	Y|
 [Finnish](data/fi)		   | 212	| fi |	Y|
 [French](data/fr)		    |3194	| fr |	Y| many spelling variations
 [Gaelic](data/gd)		    | 132	| gd |	N|
 [Galician](data/gl)	   | 129	| gl |	N|
 [German](data/de)		    | 447	| de |	Y|
 [Greek](data/el)		     |  86	| el |	Y|
 [Hindi](data/hi)		     | 250	| hi |	Y|
 [Hungarian](data/hu)	  | 213	| hu |	Y|
 [Icelandic](data/is)	  |  87	| is |	Y|
 [Italian](data/it)		   |1257	| it |	Y|
 [Indonesian](data/id)	 | 141	| id |	Y|
 [Japanese](data/ja)	   | 250	| ja |	Y|
 [Kabyle](data/kab)	   	|  22	| kab|	N|
 [Kambodsha](data/kh)	  | 132	| kh |	N|
 [Klingon](data/tlh)   	|   3	| tlh|	N|
 [Korean](data/ko)	    	|2958	| ko |	Y|
 [Latin](data/la)	     	| 108	| la |	N|
 [Latvian](data/lv)	   	| 118	| lv |	Y|
 [Lithuanian](data/lt)	 | 113	| lt |	Y|
 [Macedonian](data/mk)	 | 113	| mk |	N|
 [Malay](data/ms)	     	| 121	| ms |	Y|
 [Malayalam](data/ml)	  | 116	| ml |	Y|
 [Maltese](data/mt)		   | 123	| mt |	Y|
 [Maori](data/mi)	     	|  20	| mi |	Y|
 [Marathi](data/mr)	   	|  95	| mr |	Y|
 [Mongolian](data/mn)	  | 133	| mn |	N|
 [Norwegian](data/no)  	|  37	| no |	Y|
 [Persian](data/fa)	   	| 527	| fa |	N|
 [Polish](data/pl)		    |8862	| pl |	Y| different grammatical variations
 [Portuguese](data/pt) 	| 412	| pt |	Y|
 [Romanian](data/ro)  	 | 134	| ro |	Y|
 [Russian](data/ru)	   	|4761	| ru |	Y|
 [Samoan](data/sm)		    |  15	| sm |	Y|
 [Serbian](data/sr)	   	| 142	| sr |	Y|
 [Slovak](data/sk)		    | 139	| sk |	Y|
 [Slovene](data/sl)		   | 108	| sl |	Y|
 [Spanish](data/es)		   |1127	| es |	Y|
 [Swedish](data/sv)	   	| 160	| sv |	Y|
 [Tamil](data/ta)	     	|  48	| ta |	N|
 [Telugu](data/te)		    | 112	| te |	Y|
 [Tetum](data/tet)		    |   6	| tet|	N|
 [Thai](data/th)	      	|1581	| th |	Y|
 [Tongan](data/to)	    	|  15	| to |	N|
 [Turkish](data/tr)	   	| 230	| tr |	Y|
 [Ukrainian](data/uk)	  |  91	| uk |	Y|
 [Uzbek](data/uz)	     	| 113	| uz |	N|
 [Vietnamese](data/vi)	 | 537	| vi |	Y|
 [Welsh](data/cy)		     | 174	| cy |	Y|
 [Zulu](data/zu)	      	| 137	| zu |	N|
 [???](data/pih)	      	|  17	| pih|	N|
 [???](data/piy)	      	|  15	| piy|	N|
 
### Categories in *questionable_international_words.csv*
The categories used are:
 - **cul**: cultural differences
 - **dm**: drugs & medicine
 - **his**: historical 
 - **leg**: Legislative term
 - **mab**: medical, anatomic, biological term
 - **pol**: political
 - **rel**: religious
 - **so**: sexual orientation
 - **vm**: various meanings
###
 This is just an ad hoc classification where several expressions can be in different categories.
