> Written with [StackEdit](https://stackedit.io/).
> ## [List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words_V2](https://github.com/LDNOOBWV2/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words_V2#list-of-dirty-naughty-obscene-and-otherwise-bad-words_v2)
### 
This list of words is a follow-up and extension of the Shutterstock [List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words/tree/master) as that list is not maintained anymore. As there are many profanity word lists around on the web (and many not maintained) their content was crabbed and joined here together (see the source list below). 
###
The files are available in HuggingFace, there you can find them in the [parquet format](https://huggingface.co/datasets/PeterGraebner/LDNOOBW_V2/tree/refs%2Fconvert%2Fparquet/default/train) as well.
###
As the opinion on which words should be in such lists varies between culture, language, and geographies, feel free to extend them to your needs, hopefully getting a lot of feedback.
###
The lists need reviews from native speakers. It would be great to collect more words and even get more languages (**72** right now).
###
The long list of English words shows that people got very creative to get around profanity filters. The best way to use these hard-coded word lists is to use them as an additional quality criterion for filtering texts like it is done in [RedPajama](https://github.com/togethercomputer/RedPajama-Data) data set, or use them for ML building profanity filters.
###
The next TODO will be to create some regular expressions for often-used spelling variations.
### Structure and Format
 - filename is the **iso-code** of the country
 - file extension is **".txt"** 
 - **utf-8** encoded
 - all words are **lowercase**
 - one expression per line
 - all words contained in the English "*en*" file are excluded in the other language files
 - often used words where the classification as a profane word is doubtful there is a separate csv file
 - the csv-file is: "***questionable_international_words.csv***" 
 - separator is the comma "**,**"
 - **152** words for several languages (see table below)
 - the header line contains the iso-code of the language, a classification column (*category*), and a *remark* column
 - these words are **NOT** included in the language-text-files, e.g. "***.txt**"
 - when I couldn't find a translation, the field contains the string: **<NO_TRANSLATION>**
### Languages Files Overview
language | count | filename | in csv-file | remark
--- | --- | --- | --- | ---
 [Afrikaans](data/af.txt)	  |  86	| af |	Y|
 [Albanian](data/sq.txt) 	  | 122	| sq |	Y|
 [Amharic](data/am.txt)     |  22 | am | N|
 [Arabic](data/ar.txt)		    | 443	| ar |	N|
 [Armenian](data/hy.txt)	   | 106	| hy |	Y|
 [Australian Kriol](data/rop.txt))	|  12	| rop|	N|
 [Basque](data/eu.txt)		    | 137	| eu |	N|
 [Belorussian](data/be.txt)	| 118	| be |	N|
 [Bulgarian](data/bg.txt)	  | 115	| bg |	Y|
 [Burmese](data/my.txt)		   |  52	| my |	N|
 [Cambodian](data/kh.txt)   | 132	| kh |	N|
 [Catalan](data/ca.txt)		   |  65	| ca |	Y|
 [Cebuano](data/ceb.txt)		  |   7	| ceb|	N|
 [Chinese](data/zh.txt)		   |1173	| zh |	Y|
 [Croatian](data/hr.txt)	   | 115	| hr |	Y|
 [Czech](data/cs.txt)		     | 187	| cs |	Y|
 [Danish](data/da.txt)		    | 127	| da |	Y|
 [Dutch](data/nl.txt)		     |1099	| nl |	Y|
 [English](data/en.txt)		   |8053	| en |	Y| various spelling variations
 [Esperanto](data/eo.txt)	  |  37	| eo |	N|
 [Estonian](data/et.txt)	   | 114	| et |	Y|
 [Filipino](data/fil.txt)	  | 103	| fil|	Y|
 [Finnish](data/fi.txt)		   | 212	| fi |	Y|
 [French](data/fr.txt)		    |3194	| fr |	Y| many spelling variations
 [Gaelic](data/gd.txt)		    | 132	| gd |	N|
 [Galician](data/gl.txt)	   | 129	| gl |	N|
 [German](data/de.txt)		    | 447	| de |	Y|
 [Greek](data/el.txt)		     |  86	| el |	Y|
 [Hindi](data/hi.txt)		     | 250	| hi |	Y|
 [Hungarian](data/hu.txt)	  | 213	| hu |	Y|
 [Icelandic](data/is.txt)   |  87	| is |	Y|
 [Italian](data/it.txt)		   |1257	| it |	Y|
 [Indonesian](data/id.txt)	 | 141	| id |	Y|
 [Japanese](data/ja.txt)	   | 250	| ja |	Y|
 [Kabyle](data/kab.txt)	   	|  22	| kab|	N|
 [Klingon](data/tlh.txt)   	|   3	| tlh|	N|
 [Korean](data/ko.txt)	    	|2958	| ko |	Y|
 [Latin](data/la.txt)	     	| 108	| la |	N|
 [Latvian](data/lv.txt)	   	| 118	| lv |	Y|
 [Lithuanian](data/lt.txt)	 | 113	| lt |	Y|
 [Macedonian](data/mk.txt)	 | 113	| mk |	N|
 [Malay](data/ms.txt)	     	| 121	| ms |	Y|
 [Malayalam](data/ml.txt)	  | 116	| ml |	Y|
 [Maltese](data/mt.txt)		   | 123	| mt |	Y|
 [Maori](data/mi.txt)	     	|  20	| mi |	Y|
 [Marathi](data/mr.txt)	   	|  95	| mr |	Y|
 [Mongolian](data/mn.txt)	  | 133	| mn |	N|
 [Norwegian](data/no.txt)  	|  37	| no |	Y|
 [Persian](data/fa.txt)	   	| 527	| fa |	N|
 [Polish](data/pl.txt)		    |8862	| pl |	Y| different grammatical variations
 [Portuguese](data/pt.txt) 	| 412	| pt |	Y|
 [Romanian](data/ro.txt)  	 | 134	| ro |	Y|
 [Russian](data/ru.txt)	   	|4761	| ru |	Y|
 [Samoan](data/sm.txt)		    |  15	| sm |	Y|
 [Serbian](data/sr.txt)	   	| 142	| sr |	Y| sr_k & sr_l in csv file
 [Slovak](data/sk.txt)	     | 139	| sk |	Y|
 [Slovene](data/sl.txt)		   | 108	| sl |	Y|
 [Spanish](data/es.txt)		   |1127	| es |	Y|
 [Swedish](data/sv.txt)	   	| 160	| sv |	Y|
 [Tamil](data/ta.txt)	     	|  48	| ta |	N|
 [Telugu](data/te.txt)		    | 112	| te |	Y|
 [Tetum](data/tet.txt)		    |   6	| tet|	N|
 [Thai](data/th.txt)	      	|1581	| th |	Y|
 [Tongan](data/to.txt)	    	|  15	| to |	N|
 [Turkish](data/tr.txt)    	| 230	| tr |	Y|
 [Ukrainian](data/uk.txt)	  |  91	| uk |	Y|
 [Uzbek](data/uz.txt)	     	| 113	| uz |	N|
 [Vietnamese](data/vi.txt)	 | 537	| vi |	Y|
 [Welsh](data/cy.txt)		     | 174	| cy |	Y|
 [Zulu](data/zu.txt)       	| 137	| zu |	N|
 [???](data/pih.txt)	      	|  17	| pih|	N|
 [???](data/piy.txt)	      	|  15	| piy|	N|
 
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
