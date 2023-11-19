> Written with [StackEdit](https://stackedit.io/).
> ## [List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words_V2](https://github.com/LDNOOBWV2/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words_V2#list-of-dirty-naughty-obscene-and-otherwise-bad-words_v2)
### 
This list of words is a follow-up and extension of the Shutterstock [List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words/tree/master) as that list is not maintained anymore. As there are many profanity word lists around on the web (and many not maintained) their content was crabbed and joined here together (see the source list below). 
###
The files are available in HuggingFace, there you can find them in the [parquet format](https://huggingface.co/datasets/PeterGraebner/LDNOOBW_V2/tree/refs%2Fconvert%2Fparquet/default/train) as well.
###
As the opinion on which words should be in such lists varies between culture, language, and geographies, feel free to extend them to your needs, hopefully getting a lot of feedback.
###
The lists need reviews from native speakers. It would be great to collect more words and even get more languages (**75** right now, with over **50k words** alltogether).
###
The long list of English words shows that people got very creative to get around profanity filters. The best way to use these hard-coded word lists is to use them as an additional quality criterion for filtering texts like it is done in [RedPajama](https://github.com/togethercomputer/RedPajama-Data) data set or use them for ML building profanity filters.
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
 - **51** words for several languages (see table below)
 - the header line contains the iso-code of the language, a classification column (*category*), and a *remark* column
 - these words are **NOT** included in the language-text-files, e.g. "***.txt**"
 - when I couldn't find a translation, the field contains the string: **<NO_TRANSLATION>**
### Languages Files Overview
language | count | filename | in csv-file | remark
--- | --- | --- | --- | ---
 [Afrikaans](data/af.txt)	  | 283	| af |	Y|
 [Albanian](data/sq.txt) 	  | 179	| sq |	Y|
 [Algerian](data/dz.txt) 	  |  86	| dz |	N|
 [Amharic](data/am.txt)     |  50 | am | N|
 [Arabic](data/ar.txt)		    |1248	| ar |	N|
 [Armenian](data/hy.txt)	   | 106	| hy |	Y|
 [Australian Kriol](data/rop.txt))	|  16	| rop| N|
 [Azerbaijanian](data/az.txt)	     |  37	| az |	N|
 [Basque](data/eu.txt)		    |  48	| eu |	N|
 [Belorussian](data/be.txt)	| 118	| be |	N|
 [Bulgarian](data/bg.txt)	  | 338	| bg |	Y|
 [Burmese](data/my.txt)		   |  81	| my |	N|
 [Cambodian](data/kh.txt)   | 132	| kh |	N|
 [Catalan](data/ca.txt)		   | 143	| ca |	Y|
 [Cebuano](data/ceb.txt)		  |  18	| ceb|	N|
 [Chinese](data/zh.txt)		   |1816	| zh |	Y|
 [Croatian](data/hr.txt)	   | 267	| hr |	Y|
 [Czech](data/cs.txt)		     | 243	| cs |	Y|
 [Danish](data/da.txt)		    | 185	| da |	Y|
 [Dutch](data/nl.txt)		     |1222	| nl |	Y|
 [English](data/en.txt)		   |8362	| en |	Y| various spelling variations
 [Esperanto](data/eo.txt)	  |  50	| eo |	N|
 [Estonian](data/et.txt)	   | 174	| et |	Y|
 [Filipino](data/fil.txt)	  | 167	| fil|	Y|
 [Finnish](data/fi.txt)		   | 317	| fi |	Y|
 [French](data/fr.txt)		    |3565	| fr |	Y| many spelling variations
 [Gaelic](data/gd.txt)		    |  88	| gd |	N|
 [Galician](data/gl.txt)	   |  74	| gl |	N|
 [German](data/de.txt)		    | 622	| de |	Y|
 [Greek](data/el.txt)		     | 249	| el |	Y|
 [Hindi](data/hi.txt)		     | 374	| hi |	Y|
 [Hungarian](data/hu.txt)	  | 296	| hu |	Y|
 [Icelandic](data/is.txt)   | 137	| is |	Y|
 [Italian](data/it.txt)		   |1755	| it |	Y|
 [Indonesian](data/id.txt)	 | 535	| id |	Y|
 [Japanese](data/ja.txt)	   | 466	| ja |	Y| 
 [Jewish](data/yid.txt)	    | 169	| yid|	N|
 [Kabyle](data/kab.txt)	   	|  22	| kab|	N|
 [Klingon](data/tlh.txt)   	|  33	| tlh|	N|
 [Korean](data/ko.txt)	    	|3097	| ko |	Y|
 [Latin](data/la.txt)	     	| 103	| la |	N|
 [Latvian](data/lv.txt)	   	| 198	| lv |	Y|
 [Lithuanian](data/lt.txt)	 | 158	| lt |	Y|
 [Macedonian](data/mk.txt)	 | 192	| mk |	N|
 [Malay](data/ms.txt)	     	| 204	| ms |	Y|
 [Malayalam](data/ml.txt)	  | 338	| ml |	Y|
 [Maltese](data/mt.txt)		   | 132	| mt |	Y|
 [Maori](data/mi.txt)	     	|  59	| mi |	Y|
 [Marathi](data/mr.txt)	   	|  95	| mr |	Y|
 [Mongolian](data/mn.txt)	  | 277	| mn |	N|
 [Norwegian](data/no.txt)  	| 172	| no |	Y|
 [Persian](data/fa.txt)	   	| 629	| fa |	N|
 [Polish](data/pl.txt)		    |8965	| pl |	Y| different grammatical variations
 [Portuguese](data/pt.txt) 	| 575	| pt |	Y| including Brasilian
 [Romanian](data/ro.txt)  	 | 290	| ro |	Y|
 [Russian](data/ru.txt)	   	|4934	| ru |	Y|
 [Samoan](data/sm.txt)		    | 116	| sm |	Y|
 [Serbian](data/sr.txt)	   	| 466	| sr |	Y| sr_k & sr_l in csv file
 [Slovak](data/sk.txt)	     | 431	| sk |	Y|
 [Slovene](data/sl.txt)		   | 167	| sl |	Y|
 [Spanish](data/es.txt)		   |1705	| es |	Y| including Middle- and South American
 [Swedish](data/sv.txt)	   	| 247	| sv |	Y|
 [Tamil](data/ta.txt)	     	| 119	| ta |	N|
 [Telugu](data/te.txt)		    | 317	| te |	Y|
 [Tetum](data/tet.txt)		    |  11	| tet|	N|
 [Thai](data/th.txt)	      	|1717	| th |	Y|
 [Tongan](data/to.txt)	    	|  68	| to |	N|
 [Turkish](data/tr.txt)    	| 370	| tr |	Y|
 [Ukrainian](data/uk.txt)	  | 208	| uk |	Y|
 [Uzbek](data/uz.txt)	     	| 102	| uz |	N|
 [Vietnamese](data/vi.txt)	 | 798	| vi |	Y|
 [Welsh](data/cy.txt)		     | 169	| cy |	Y|
 [Zulu](data/zu.txt)       	| 115	| zu |	N|
 [???](data/pih.txt)	      	|  14	| pih|	N|
 [???](data/piy.txt)	      	|  13	| piy|	N|
 
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
