# Summary
ACM TALIP (renamed and expanded as TALLIP now) for papers [1] and [3] is believed to be one of top journals of natural language processing, right after MIT Press’ Computational Linguistics, which is the only SCI indexed journal in this field. The paper [1] contributed a novel approach of Mandarin syllable word segmentation, which is based on differentiation between left and right context using double ranks, to make a practical way on open domain text with combinatorial pattern matching rather than machine learning techniques in the mainstream, hence is reliable and lightweight enough for computing resource limited devices. IJCLCLP for the paper [2] has a long history as international journal of Chinese natural language processing. Papers [2], [7], [11], [12], and [13] studied thoroughly on how to utilize unlabeled data on enhancement of linear-chain conditional random fields for Mandarin word segmentation by extracting effective patterns, and achieved competitive results on every domain and segmentation standard in ACL SIGHAN Word Segmentation Bakeoffs, with accuracies ranked ranging from the first to the seventh places. Papers [3], [14], [18], [20], and [21] are NTCIR top-1 ranked system of Chinese-English cross-lingual question answering, and I was responsible for segmentation, extraction, and translation of keywords from questions to retrieve, with accuracies 80% and 92% on top-5 and top-100 passages, respectively, where NTCIR conference is the counterpart of TREC and CLEF in Asia. The paper [4] is another NTCIR top-1 ranked system of Japanese University Entrance Exam on world history essay questions. The paper [6] focused on negation perspective of Mandarin word segmentation evaluation metrics, in hope for a realistic connection between theoretic performance and practical demand, along with a quantitative way to analyze differences between word segmentation standards. Papers [5], [8], and [10] practiced English-to-Chinese named entity transliteration with experiences of Mandarin word segmentation, and reached accuracies above top-4 on three data sets from the transliteration generation shared task of Named Entity Workshop. The paper [9] is not only the text entry (input method) research in Chinese solely in the very first Workshop on Advances in Text Input Methods, but also the unique paper for how to evaluate performances of user profiling, personalization, and adaptation in depth. Papers [15], [16], and [17] were term project papers collaborated with the 1st Academia Sinica’s Taiwan International Graduate Program on Computational Linguistics and Chinese Language Processing, for analyzing and constructing a cross-lingual lexicon ontology based on morphology. The paper [19] applied n-gram statistical language model and specialized on parameter tuning of Stanford Research Institute Language Modeling (SRILM) toolkit, to detect and correct prepositional errors in English writing. Finally, the paper [22] is one of the first studies about variations of maximum matching algorithms for syllable-to-word conversion, i.e. phonetic input (text entry) method, in Mandarin Chinese, and emphasized the importance of verb-noun pairs that can potentially be predicate-argument structures.

# Journal Papers
1.	Mike Tian-Jian Jiang, Tsung-Hsien Lee, and Wen-Lian Hsu. 2013, March. The Left and Right Context of a Word: Overlapping Chinese Syllable Word Segmentation with Minimal Context. ACM Transactions on Asian Language Information Processing (TALIP), 12(1), pp. 2:1-2:25. [Ei Compendex]
Division of labor:
i.	Mike Tian-Jian Jiang: project manager, CRF experiments.
ii.	Tsung-Hsien Lee: Genetic Algorithm experiments.
2.	Mike Tian-Jian Jiang, Cheng-Wei Shih, Ting-Hao Yang, Chan-Hung Kuo, Richard Tzong-Han Tsai and Wen-Lian Hsu. 2012, September. Enhancement of Feature Engineering for Conditional Random Fields Learning in Chinese Word Segmentation Using Unlabeled Data. International Journal of Computational Linguistics and Chinese Language Processing (IJCLCLP), 17(3), pp. 45-86. [THCI Core, Linguistics Abstracts; Invited paper]
Division of labor:
i.	Mike Tian-Jian Jiang: project manager, methodology.
ii.	Cheng-Wei Shih: deputy project manager.
iii.	Ting-Hao Yang: feature labeling.
iv.	Chan-Hung Kuo: CRF experiment.
v.	Richard Tzong-Han Tsai: consultant.
3.	Cheng-Wei Lee, Min-Yuh Day, Cheng-Lung Sung, Yi-Hsun Lee, Tian-Jian Jiang, Chia-Wei Wu, Cheng-Wei Shih, Yu-Ren Chen, and Wen-Lian Hsu. 2008, November. Boosting Chinese Question Answering with Two Lightweight Methods: ABSPs and SCO-QAT. ACM Transactions on Asian Language Information Processing (TALIP), 7(4), pp. 12:1-12:29. [Ei Compendex; Non-self citations: 9]
Division of labor:
i.	Cheng-Wei Lee: project manager.
ii.	Min-Yuh Day: SVM-based answer classification.
iii.	Cheng-Lung Sung: pairwise multiple sequence alignment for template generation.
iv.	Yi-Hsun Lee: template and answer ranking.
v.	Tian-Jian Jiang: query term generation from questions, passage retrieval by Lucene and Lemur/Indri.
vi.	Chia-Wei Wu: MaxEnt-based named entity recognition.
vii.	Cheng-Wei Shih: template and answer ranking.
viii.	Yu-Ren Chen: software maintenance.

# Conference Papers
4.	Mike Tian-Jian Jiang. 2017, December. DGLab Question Answering System and Automatic Evaluation Method at NTCIR-13 QA Lab-3 for University Entrance Exam on World History Essay. Proceedings of the 13th NTCIR conference (NTCIR-13), pp. 166-170. [The best system among 4 teams for both Japanese and English]
5.	Chan-Hung Kuo, Shih-Hung Liu, Mike Tian-Jian Jiang, Cheng-Wei Lee, Wen-Lian Hsu. 2012, July. Cost-benefit Analysis of Two-stage Conditional Random Felds based English-to-Chinese Machine Transliteration. Proceedings of the 4th Named Entity Workshop (NEWS), the 50th Annual Meeting of the Association for Computational Linguistics (ACL), pages 76-80.
Division of labor:
i.	Mike Tian-Jian Jiang: project manger, methodology.
ii.	Chan-Hung Kuo, Shih-Hung Liu: experiment.
iii.	Cheng-Wei Lee: consultant.
6.	Mike Tian-Jian Jiang, Cheng-Wei Shih, Chan-Hung Kuo, Richard Tzong-Han Tsai and Wen-Lian Hsu. 2011, December. Evaluation via Negativa of Chinese Word Segmentation for Information Retrieval. Proceedings of the 25th Pacific Asia Conference on Language Information and Computing (PACLIC 25), pp. 100-109. [ISI CPCI, ACL Anthology; Acceptance rate=40% (oral), 20% (overall); Non-self citations: 1]
Division of labor:
i.	Mike Tian-Jian Jiang: project manger, methodology.
ii.	Cheng-Wei Shih: IR experiment.
iii.	Chan-Hung Kuo: CRF model generation.
iv.	Richard Tzong-Han Tsai: consultant.
7.	Mike Tian-Jian Jiang, Wen-Lian Hsu, Chan-Hung Kuo, and Ting-Hao Yang. 2011, November. Enhancement of Unsupervised Feature Selection for Conditional Random Fields Learning in Chinese Word Segmentation. Proceedings of the 7th IEEE International Conference on Natural Language Processing and Knowledge Engineering (NLPKE 2011), pp. 382-389. [ISI CPCI, Ei Compendex; Acceptance rate=82/225=36.4%; Non-self citations: 1]
Division of labor:
i.	Mike Tian-Jian Jiang: project manager, methodology.
ii.	Chan-Hung Kuo: CRF experiment, feature labeling.
iii.	Ting-Hao Yang: CRF experiment, feature labeling.
8.	Mike Tian-Jian Jiang, Chan-Hung Kuo, and Wen-Lian Hsu. 2011, November. Using Accessor Variety Features of Source Graphemes in Machine Transliteration of English to Chinese. The 2011 Conference on Technologies and Applications of Artificial Intelligence (TAAI 2011), pp. 132-138. [Ei Compendex, DBLP]
Division of labor:
i.	Mike Tian-Jian Jiang: project manger, methodology.
ii.	Chan-Hung Kuo: CRF experiment, feature labeling.
9.	Mike Tian-Jian Jiang, Chen-Wei Lee, Chad Liu, Yung-Chun Chang, and Wen-Lian Hsu. 2011, November. Robustness Analysis of Adaptive Chinese Input Methods. Proceedings of the 1st Workshop on Advances in Text Input Methods (WTIM 2011), the 5th International Joint Conference on Natural Language Processing (IJCNLP 2011), pp. 53-61. [ISI CPCI, ACL Anthology]
Division of labor:
i.	Mike Tian-Jian Jiang: project manager, methodology.
ii.	Chen-Wei Lee: character-based bi-gram sampling.
iii.	Chad Liu: experiment.
iv.	Yung-Chun Chang: experiment.
10.	Mike Tian-Jian Jiang, Chan-Hung Kuo, and Wen-Lian Hsu. 2011, November. English-to-Chinese Machine Transliteration using Accessor Variety Features of Source Graphemes. Proceedings of the 3rd Named Entity Workshop (NEWS 2011), the 5th International Joint Conference on Natural Language Processing (IJCNLP 2011), pp. 86-90. [ISI CPCI, ACL Anthology; Non-self citations: 1]
Division of labor:
i.	Mike Tian-Jian Jiang: project manager, methodology.
ii.	Chan-Hung Kuo: CRF experiment, feature labeling.
11.	Ting-Hao Yang, Tian-Jian Jiang, Chan-Hung Kuo, Richard Tzong-Han Tsai, and Wen-Lian Hsu. 2011, September. Unsupervised Overlapping Feature Selection for Conditional Random Fields Learning in Chinese Word Segmentation. Proceedings of the 23rd Conference on Computational Linguistics and Speech Processing (ROCLING 2011), pp. 109-122. [ACL Anthology; Invited paper; Non-self citations: 3]
Division of labor:
i.	Ting-Hao Yang: feature labeling.
ii.	Tian-Jian Jiang: project manger, methodology.
iii.	Chan-Hung Kuo: CRF experiment.
iv.	Richard Tzong-Han Tsai: consultant.
12.	Tian-Jian Jiang, Shih-Hung Liu, Cheng-Lung Sung, and Wen-Lian Hsu. 2010, September. Term Contributed Boundary Feature using Conditional Random Fields for Chinese Word Segmentation Task. Proceedings of the 22nd Conference on Computational Linguistics and Speech Processing (ROCLING 2010), pp. 143-156. [ACL Anthology; Non-self citations: 2]
Division of labor:
i.	Tian-Jian Jiang: project manager, methodology.
ii.	Shih-Hung Liu: CRF experiment.
iii.	Cheng-Lung Sung: suffix array based pattern extraction.
13.	Tian-Jian Jiang, Shih-Hung Liu, Cheng-Lung Sung, and Wen-Lian Hsu. 2010, August. Term Contributed Boundary Tagging by Conditional Random Fields for SIGHAN 2010 Chinese Word Segmentation Bakeoff. Proceedings of the 1st CIPS-SIGHAN Joint Conference on Chinese Language Processing, pp. 266-269. [ACL Anthology; Non-self citations: 1]
Division of labor:
i.	Tian-Jian Jiang: project manager, methodology.
ii.	Shih-Hung Liu: CRF experiment.
iii.	Cheng-Lung Sung: suffix array based pattern extraction.
14.	Cheng-Wei Lee, Min-Yuh Day, Cheng-Lung Sung, Yi-Hsun Lee, Tian-Jian Jiang, Chia-Wei Wu, Cheng-Wei Shih, Yu-Ren Chen, and Wen-Lian Hsu. 2007, May. Chinese-Chinese and English-Chinese Question Answering with ASQA at NTCIR-6 CLQA. Proceedings of NTCIR-6 Workshop Meeting, pp. 175-181. [Non-self citations: 5]
Division of labor:
i.	Cheng-Wei Lee: project manager.
ii.	Min-Yuh Day: SVM-based answer classification.
iii.	Cheng-Lung Sung: pairwise multi-sequence alignment for template generation.
iv.	Yi-Hsun Lee: template and answer ranking.
v.	Tian-Jian Jiang: passage retrieval.
vi.	Chia-Wei Wu: MaxEnt-based named entity recognition.
vii.	Cheng-Wei Shih: template and answer ranking.
viii.	Yu-Ren Chen: software maintenance.
15.	Siaw-Fong Chung, Tian-Jian Jiang, Kamrul Hasan, Sophia Lee, I-Li Su, Laurent Prevot, Chu-Ren Huang. 2007, January. Extending an International Lexical Framework for Asian Languages, the Case of Mandarin, Taiwanese, Cantonese, Bangla and Malay. Proceedings of the First International Workshop on Intercultural Collaboration (IWIC), pp. 24-26. [Non-self citations: 5]
16.	Laurent Prevot, Chu-Ren Huang, Kamrul Hasan, Sophia Lee, I-Li Su, Siaw-Fong Chung, Tian-Jian Jiang. 2006. Meta-modeling and standardization issues for Asian Languages lexical resources. Proceedings of International Conference on Terminology, Standardization and Technology Transfer, pp. 151-162. [Non-self citations: 1]
17.	Siaw-Fong Chung, Kamrul Hasan, Tian-Jian Jiang, Sophia Lee, I-Li Su, Laurent Prevot and Chu-Ren Huang. 2006, August. Extending an international lexical framework for Asian languages, the case of Mandarin, Taiwanese, Cantonese, Bangla and Malay. 第五屆數位典藏技術研討會, pp. 87-94. [Non-self citations: 1]
Division of labor for the above three papers:
i.	Siaw-Fong Chung: Malay.
ii.	Tian-Jian Jiang: Taiwanese (Min-nan).
iii.	Kamrul Hasan: Bangla.
iv.	Sophia Lee: Cantonese.
v.	I-Li Su: Mandarin.
vi.	Laurent Prevot: project manager.
vii.	Chu-Ren Huang: methodology.
18.	Hao Tang, Cheng-Wei Lee, Tian-Jian Jiang, and Wen-Lian Hsu. 2006, December. Query Term Selection Strategies for Web-based Chinese Factoid Question Answering. Proceedings of the 11th Conference on Artificial Intelligence and Applications (TAAI 2006). [Non-self citations: 2]
Division of labor:
i.	Hao Tang: query term selection, factoid question answering.
ii.	Cheng-Wei Lee: project manager.
iii.	Tian-Jian Jiang: query term generation and selection.
