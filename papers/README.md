# Literature Review
Here we classify, organize, and summerize the papers we read

## Table of content

+ [Diachronic Word Embeddings Reveal Statistical Laws of Semantic Change](#diachronic-word-embeddings-reveal-statistical-laws-of-semantic-change)
+ [Linear Algebraic Structure of Word Senses, with Applications to Polysemy](#linear-algebraic-structure-of-word-senses-with-applications-to-polysemy)
+ [Different Contexts Lead to Different Word Embeddings](#different-contexts-lead-to-different-word-embeddings)
+ [Geometry of Polysemy](#geometry-of-polysemy)
+ [A Word-Embedding-based Sense Index for Regular Polysemy Representation](#a-word-embedding-based-sense-index-for-regular-polysemy-representation)
+ [A Simple Approach to Learn Polysemous Word Embeddings](#a-simple-approach-to-learn-polysemous-word-embeddings)
+ [Predictable Meaning Shift: Some Linguistic Properties of Lexical Implication Rules](#predictable-meaning-shift-some-linguistic-properties-of-lexical-implication-rules)
+ [Regular polysemy: A distributional model](#regular-polysemy-a-distributional-model)
+ [Minimally Supervised Classification to Semantic Categories usingAutomatically Acquired Symmetric Patterns](#minimally-supervised-classification-to-semantic-categories-usingautomatically-acquired-symmetric-patterns)
+ [Automatic lexical semantic classification of nouns](#automatic-lexical-semantic-classification-of-nouns)
+ [Lexicalised Systematic Polysemy in WordNet](#lexicalised-systematic-polysemy-in-wordnet)
+ [Regular Polysemy in WordNet](#regular-polysemy-in-wordnet)
+ [A corpus-based account of regular polysemy: the case of context-sensitive adjectives](#a-corpus-based-account-of-regular-polysemy-the-case-of-context-sensitive-adjectives)
+ [A cascade approach for complex-type classification](#a-cascade-approach-for-complex-type-classification)
+ [REGULAR POLYSEMY](#regular-polysemy)
+ [Choosing which to use? A study of distributional models for nominal lexical semantic classification](#choosing-which-to-use-a-study-of-distributional-models-for-nominal-lexical-semantic-classification)


<hr/>

#### Diachronic Word Embeddings Reveal Statistical Laws of Semantic Change
* 213 Citations, 288(ggl)
* 70 Highly Influenced Papers
* 140 Cite Background
* 121 Cite Methods
* 23 Cite Results

**Keywords:** polysemy index application<br/>
**Summary**<br/>
The goal is to find a quantitative measure for how the meaning of words change through 
time, three word embeddings have been considered, PPMI, SVD, Skip-gram, several corpuses
are given for different timespans. One is large with relatievly low quality, the other
is clean but shorter. 

The criteria for similarity of words is the
The performance of these word embeddings is measured in two ways, firstly we consider 
certain words such as "gay", "awfull", and "broadcast" for which we know how their 
meaning has changed through time and see if that can be infered from the behavior of 
the embeddings. Secondly we find words that have potentially had a significant shift in
their meaning through time by comparing how the vectors have changed and then check
history records to see if those words have actually changed meaning in the way predicted
by the model.

PPMI didn't prove to be very effective, SVD was good for one corpus, Skip-gram for the
other.

Finally, two claims have been mained:
* There is a linear association between log(frequency) of word usage with the rate of
    sense shift which is defined by integrating the gradient of changes of the vector
    over time.
* Polysemy is defined as: 
"For each two occurances w0 and w1 of a given word in the corpus, how often where the
words in w0's context used in the context of the words in w1's context and vice versa."

<details><summary>BibTex</summary>
<pre>@inproceedings{hamilton-etal-2016-diachronic,
    title = "Diachronic Word Embeddings Reveal Statistical Laws of Semantic Change",
    author = "Hamilton, William L.  and
      Leskovec, Jure  and
      Jurafsky, Dan",
    booktitle = "Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = aug,
    year = "2016",
    address = "Berlin, Germany",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/P16-1141",
    doi = "10.18653/v1/P16-1141",
    pages = "1489--1501",
}</pre>
</details>

<hr/>

#### Linear Algebraic Structure of Word Senses, with Applications to Polysemy
* 61 Citations, 65(ggl)
* 11 Highly Influenced Papers
* 41 Cite Background
* 21 Cite Methods
* 1 Cite Results

**Keywords:** Linear Algebra<br/>
**Summary**<br/>
The claim is that [I didn't exactly understand the claim, it's better if you write it
yourself]

Then an assumption is made [It's also better you write this, try to copy paste from the
actual paper if you need to, but don't be too verbose, summerize the section of the
paper if it's too verbose.] Gaussian walk model.

<details><summary>BibText</summary>
<pre>@article{tacl_a_00034,
    author = {Arora, Sanjeev and Li, Yuanzhi and Liang, Yingyu and Ma, Tengyu and Risteski, Andrej},
    title = {Linear Algebraic Structure of Word Senses, with Applications to Polysemy},
    journal = {Transactions of the Association for Computational Linguistics},
    volume = {6},
    number = {},
    pages = {483-495},
    year = {2018},
    doi = {10.1162/tacl\_a\_00034},
    URL = {https://doi.org/10.1162/tacl_a_00034},
    eprint = {https://doi.org/10.1162/tacl_a_00034},
}</pre>
</details>

<hr/>

#### Different Contexts Lead to Different Word Embeddings
* 8(ggl)

**Keywords:** neural networks<br/>
**Summary**<br/>
Separating context vector from core vector

**Notes**

For what types of polysemy does this work well? Regular?

<details><summary>BibText</summary>
<pre>@inproceedings{hu-etal-2016-different,
    title = "Different Contexts Lead to Different Word Embeddings",
    author = "Hu, Wenpeng  and
      Zhang, Jiajun  and
      Zheng, Nan",
    booktitle = "Proceedings of {COLING} 2016, the 26th International Conference on Computational Linguistics: Technical Papers",
    month = dec,
    year = "2016",
    address = "Osaka, Japan",
    publisher = "The COLING 2016 Organizing Committee",
    url = "https://www.aclweb.org/anthology/C16-1073",
    pages = "762--771",
}</pre>
</details>

<hr/>

#### Geometry of Polysemy
* 7(ggl)

**Keywords:** Linear Algebra, classification<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@article{DBLP:journals/corr/MuBV16,
  author    = {Jiaqi Mu and
               Suma Bhat and
               Pramod Viswanath},
  title     = {Geometry of Polysemy},
  journal   = {CoRR},
  volume    = {abs/1610.07569},
  year      = {2016},
  url       = {http://arxiv.org/abs/1610.07569},
  archivePrefix = {arXiv},
  eprint    = {1610.07569},
  timestamp = {Mon, 13 Aug 2018 16:47:42 +0200},
  biburl    = {https://dblp.org/rec/bib/journals/corr/MuBV16},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}</pre>
</details>

<hr/>

#### A Word-Embedding-based Sense Index for Regular Polysemy Representation
* 4(ggl)

**Keywords:**:<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{del-tredici-bel-2015-word,
    title = "A Word-Embedding-based Sense Index for Regular Polysemy Representation",
    author = "Del Tredici, Marco  and
      Bel, N{\'u}ria",
    booktitle = "Proceedings of the 1st Workshop on Vector Space Modeling for Natural Language Processing",
    month = jun,
    year = "2015",
    address = "Denver, Colorado",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W15-1510",
    doi = "10.3115/v1/W15-1510",
    pages = "70--78",
}</pre>
</details>

<hr/>

#### A Simple Approach to Learn Polysemous Word Embeddings
* 5(ggl)

**Keywords:**:<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@article{DBLP:journals/corr/SunRD17,
  author    = {Yifan Sun and
               Nikhil Rao and
               Weicong Ding},
  title     = {A Simple Approach to Learn Polysemous Word Embeddings},
  journal   = {CoRR},
  volume    = {abs/1707.01793},
  year      = {2017},
  url       = {http://arxiv.org/abs/1707.01793},
  archivePrefix = {arXiv},
  eprint    = {1707.01793},
  timestamp = {Mon, 13 Aug 2018 16:48:49 +0200},
  biburl    = {https://dblp.org/rec/bib/journals/corr/SunRD17},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}</pre>
</details>
<hr/>

#### Predictable Meaning Shift: Some Linguistic Properties of Lexical Implication Rules
* 96 Citations, 170(ggl)
* 33 Cite Background
* 2 Cite Results

**Keywords:** Linguistics, Regular polysemy<br/>
**Summary**<br/>
<pre>1. container/containerful : cup
2. animal/food            : lamb, chicken
3. animal/skin            : crocodile
4. plant/food             : banana
5. product/producer       : newspaper, Honda
k. substance/colour       : jade, amber
7. object/shape           : pyramid
8. language/people        : Spanish
9. music/dance            : waltz
10. figure/ground         : door/window
11. place/people          : city, New York</pre>
(this was actually copy pasted from "Lexicalised Systematic Polysemy in WordNet")

<details><summary>BibText</summary>
<pre>@inproceedings{ostler-atkins-1991-predictable,
    title = "Predictable Meaning Shift: Some Linguistic Properties of Lexical Implication Rules",
    author = "Ostler, Nicholas  and
      Atkins, B.T.S.",
    booktitle = "Lexical Semantics and Knowledge Representation",
    year = "1991",
    url = "https://www.aclweb.org/anthology/W91-0208",
}</pre>
</details>
<hr/>

#### Regular polysemy: A distributional model
* 22 Citations, 26(ggl)
* 3 Highly Influenced Papers
* 15 Cite Background
* 10 Cite Methods
* 1 Cite Results

**Keywords:**:<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{Boleda2012RegularPA,
  title={Regular polysemy: A distributional model},
  author={Gemma Boleda and Sebastian Pad{\'o} and Jason Utt},
  booktitle={*SEM@NAACL-HLT},
  year={2012}
}</pre>
</details>
<hr/>

#### Minimally Supervised Classification to Semantic Categories usingAutomatically Acquired Symmetric Patterns
* 6(ggl)

**Keywords:**:<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{Schwartz2014MinimallySC,
  title={Minimally Supervised Classification to Semantic Categories using Automatically Acquired Symmetric Patterns},
  author={Roy Schwartz and Roi Reichart and Ari Rappoport},
  booktitle={COLING},
  year={2014}
}</pre>
</details>
<hr/>

#### Automatic lexical semantic classification of nouns
* 10(ggl)

**Keywords:**<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@article{DBLP:journals/corr/abs-1303-1930,
  author    = {N{\'{u}}ria Bel and
               Lauren Romeo and
               Muntsa Padr{\'{o}}},
  title     = {Automatic lexical semantic classification of nouns},
  journal   = {CoRR},
  volume    = {abs/1303.1930},
  year      = {2013},
  url       = {http://arxiv.org/abs/1303.1930},
  archivePrefix = {arXiv},
  eprint    = {1303.1930},
  timestamp = {Mon, 13 Aug 2018 16:48:59 +0200},
  biburl    = {https://dblp.org/rec/bib/journals/corr/abs-1303-1930},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}</pre>
</details>
<hr/>

#### Lexicalised Systematic Polysemy in WordNet
* 38 Citations, 55(ggl)
* 15 Cite Background
* 8 Cite Methods

**Keywords:**: <br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{Peters2000LexicalisedSP,
  title={Lexicalised Systematic Polysemy in WordNet},
  author={Wim Peters and Ivonne Peters},
  booktitle={LREC},
  year={2000}
}</pre>
</details>

<hr/>

#### Regular Polysemy in WordNet
* 15(ggl)

**Keywords:**: Linear Algebra<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@article{Barque2009RegularPI,
  title={Regular Polysemy in WordNet},
  author={Lucie Barque and François-R{\'e}gis Chaumartin},
  journal={JLCL},
  year={2009},
  volume={24},
  pages={5-18}
}</pre>
</details>
<hr/>

#### A corpus-based account of regular polysemy: the case of context-sensitive adjectives
* 25 Citations, 41(ggl)
* 2 Highly Influenced Papers
* 14 Cite Background
* 6 Cite Methods

**Keywords:**: <br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{Lapata:2001:CAR:1073336.1073345,
 author = {Lapata, Maria},
 title = {A Corpus-based Account of Regular Polysemy: The Case of Context-sensitive Adjectives},
 booktitle = {Proceedings of the Second Meeting of the North American Chapter of the Association for Computational Linguistics on Language Technologies},
 series = {NAACL '01},
 year = {2001},
 location = {Pittsburgh, Pennsylvania},
 pages = {1--8},
 numpages = {8},
 url = {https://doi.org/10.3115/1073336.1073345},
 doi = {10.3115/1073336.1073345},
 acmid = {1073345},
 publisher = {Association for Computational Linguistics},
 address = {Stroudsburg, PA, USA},
}</pre>
</details>
<hr/>

#### A cascade approach for complex-type classification
* 2(ggl)
    
**Keywords:**: <br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{Romeo2014ACA,
  title={A cascade approach for complex-type classification},
  author={Lauren Romeo and Sara Mendes and N{\'u}ria Bel},
  booktitle={LREC},
  year={2014}
}</pre>
</details>
<hr/>

#### Choosing which to use? A study of distributional models for nominal lexical semantic classification
* 4(ggl)

**Keywords:**<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{Romeo2014ChoosingWT,
  title={Choosing which to use? A study of distributional models for nominal lexical semantic classification},
  author={Lauren Romeo and Gianluca Lebani and N{\'u}ria Bel and Alessandro Lenci},
  booktitle={LREC},
  year={2014}
}</pre>
</details>
<hr/>

#### Towards the automatic detection and identification of English puns
* 17 Citations, 16(ggl)
* 3 Highly Influenced Papers
* 8 Cite Background
* 5 Cite Methods

**Keywords:** review<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{Miller2016TowardsTA,
  title={Towards the automatic detection and identification of English puns},
  author={Tristan Miller and Mladen Turkovi{\'c}},
  year={2016}
}</pre>
</details>
<hr/>

#### Clustering Polysemic Subcategorization Frame Distributions Semantically
* 84 Citations
* 8 Highly Influenced Papers
* 43 Cite Background
* 35 Cite Methods
* 5 Cite Results

**Keywords:**<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{Korhonen2003ClusteringPS,
  title={Clustering Polysemic Subcategorization Frame Distributions Semantically},
  author={Anna Korhonen and Yuval Krymolowski and Zvika Marx},
  booktitle={ACL},
  year={2003}
}</pre>
</details>
<hr/>

#### Embedding Words and Senses Together via Joint Knowledge-Enhanced Training
* 35 Citations
* 10 Highly Influenced Papers
* 25 Cite Background
* 7 Cite Methods
* 5 Cite Results

**Keywords:**<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{Mancini2016EmbeddingWA,
  title={Embedding Words and Senses Together via Joint Knowledge-Enhanced Training},
  author={Massimiliano Mancini and Jos{\'e} Camacho-Collados and Ignacio Iacobacci and Roberto Navigli},
  booktitle={CoNLL},
  year={2016}
}</pre>
</details>
<hr/>

#### Lexical Meaning in Context - A Web of Words
* 116 Citations
* 22 Highly Influenced Papers
* 64 Cite Background
* 13 Cite Methods
* 1 Cite Results

**Keywords:**<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre>@inproceedings{Asher2011LexicalMI,
  title={Lexical Meaning in Context - A Web of Words},
  author={Nicholas Asher},
  year={2011}
}</pre>
</details>
<hr/>

#### The Representation of Polysemous Words
* 105 Citations
* 18 Highly Influenced Papers
* 83 Cite Background
* 17 Cite Methods
* 17 Cite Results

**Keywords:** Psycholinguistics, psychology<br/>
**Summary**<br/>
If we were to hear of a new species of plant called a delgar, we could say both “There is a delgar growing in my yard” (individual plant) and “This pen is made out of delgar” (the substance derived from that plant). Thus, these forms of polysemy are highly productive, and they are used quite easily when new words enter the lexicon (Murphy, 1997). For example, the word book can be used to refer both to a physical object containing a text and to the content of that text. The same form of polysemy is present in recently invented words for new information-storage devices such as videotape, CD, and DVD; for example, That CD is cracked (object) and That CD is brilliant (content of the CD).
Given the differences just described between polysemy and homonymy, it is obviously critical to keep these two phenomena distinct. Polysemy is the normal, expected presence of related senses in a word, such as an object and the substance making up that object, and homonymy is the unpredictable coincidence of two different words having the same name.
<details><summary>BibText</summary>
<pre>@inproceedings{Klein2001TheRO,
  title={The Representation of Polysemous Words},
  author={Devorah Emily Klein and Gregory L. Murphy},
  year={2001}
}</pre>
</details>
<hr/>

####

**Keywords:**<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre></pre>
</details>
<hr/>

####

**Keywords:**<br/>
**Summary**<br/>
<details><summary>BibText</summary>
<pre></pre>
</details>
<hr/>

#### REGULAR POLYSEMY
**Keywords:** Linguistics<br/>
* 602(ggl)
* 86 Citations
* 15 Highly Influenced Papers
* 68 Cite Background
* 2 Cite Methods
* 1 Cite Results

**Summary**<br/>
Apresjan uses this notion of concept lexicalisation as acriterion for distinguishing between regular and irregular polysemy:
'Polysemy of the word A with the meaning ai and aj iscalled regular if, in the given language, there exists at leastone other word B with the meanings bi bj, which aresemantically distinguished from each other in exactly thesame way as ai and aj and if ai and bi, aj and bj arenonsynonymous.
Polysemy is called irregular if the semantic distinctionbetween ai and aj is not exemplified in any other word ofthe given language.'
(this was actually copy pasted from "Lexicalised Systematic Polysemy in WordNet")

<details><summary>BibText</summary>
<pre>@Inbook{D.1974,
    author={D., APRESJAN JU},
    chapter={REGULAR POLYSEMY},
    title={ling},
    year={1974},
    month={2019},
    day={11-15T12:04:40.532+01:00},
    volume={12},
    pages={5},
    note={142},
    doi={10.1515/ling.1974.12.142.5},
    url={https://www.degruyter.com/view/j/ling.1974.12.issue-142/ling.1974.12.142.5/ling.1974.12.142.5.xml}
}</pre>
</details>
<hr/>

