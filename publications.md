# Publications
## Summary
ACM TALIP (renamed and expanded as TALLIP now) for papers [1] and [3] is believed to be one of top journals of natural language processing. The paper [1] contributed a novel approach of Mandarin syllable word segmentation, which is based on differentiation between left and right context using double ranks, to make a practical way on open domain text with combinatorial pattern matching rather than machine learning techniques in the mainstream, hence is reliable and lightweight enough for computing resource limited devices. IJCLCLP for the paper [2] has a long history as international journal of Chinese natural language processing. Papers [2], [7], [11], [12], and [13] studied thoroughly on how to utilize unlabeled data on enhancement of linear-chain conditional random fields for Mandarin word segmentation by extracting effective patterns, and achieved competitive results on every domain and segmentation standard in ACL SIGHAN Word Segmentation Bakeoffs, with accuracies ranked ranging from the first to the seventh places. Papers [3], [14], [18], [20], and [21] are NTCIR top-1 ranked system of Chinese-English cross-lingual question answering, and I was responsible for segmentation, extraction, and translation of keywords from questions to retrieve, with accuracies 80% and 92% on top-5 and top-100 passages, respectively, where NTCIR conference is the counterpart of TREC and CLEF in Asia. The paper [4] is another NTCIR top-1 ranked system of Japanese University Entrance Exam on world history essay questions. The paper [6] focused on negation perspective of Mandarin word segmentation evaluation metrics, in hope for a realistic connection between theoretic performance and practical demand, along with a quantitative way to analyze differences between word segmentation standards. Papers [5], [8], and [10] practiced English-to-Chinese named entity transliteration with experiences of Mandarin word segmentation, and reached accuracies above top-4 on three data sets from the transliteration generation shared task of Named Entity Workshop. The paper [9] is not only the text entry (input method) research in Chinese solely in the very first Workshop on Advances in Text Input Methods, but also the unique paper for how to evaluate performances of user profiling, personalization, and adaptation in depth. Papers [15], [16], and [17] were term project papers collaborated with the 1st Academia Sinica’s Taiwan International Graduate Program on Computational Linguistics and Chinese Language Processing, for analyzing and constructing a cross-lingual lexicon ontology based on morphology. The paper [19] applied n-gram statistical language model and specialized on parameter tuning of Stanford Research Institute Language Modeling (SRILM) toolkit, to detect and correct prepositional errors in English writing. Finally, the paper [22] is one of the first studies about variations of maximum matching algorithms for syllable-to-word conversion, i.e. phonetic input (text entry) method, in Mandarin Chinese, and emphasized the importance of verb-noun pairs that can potentially be predicate-argument structures.

## Journal Papers
[1] Mike Tian-Jian Jiang, Tsung-Hsien Lee, and Wen-Lian Hsu. 2013, March. The Left and Right Context of a Word: Overlapping Chinese Syllable Word Segmentation with Minimal Context. ACM Transactions on Asian Language Information Processing (TALIP), 12(1), pp. 2:1-2:25. [Ei Compendex]
> Division of labor:
> - Mike Tian-Jian Jiang: project manager, CRF experiments.
> - Tsung-Hsien Lee: Genetic Algorithm experiments.

[2] Mike Tian-Jian Jiang, Cheng-Wei Shih, Ting-Hao Yang, Chan-Hung Kuo, Richard Tzong-Han Tsai and Wen-Lian Hsu. 2012, September. Enhancement of Feature Engineering for Conditional Random Fields Learning in Chinese Word Segmentation Using Unlabeled Data. International Journal of Computational Linguistics and Chinese Language Processing (IJCLCLP), 17(3), pp. 45-86. [THCI Core, Linguistics Abstracts; Invited paper]
> Division of labor:
> - Mike Tian-Jian Jiang: project manager, methodology.
> - Cheng-Wei Shih: deputy project manager.
> - Ting-Hao Yang: feature labeling.
> - Chan-Hung Kuo: CRF experiment.
> - Richard Tzong-Han Tsai: consultant.

[3] Cheng-Wei Lee, Min-Yuh Day, Cheng-Lung Sung, Yi-Hsun Lee, Tian-Jian Jiang, Chia-Wei Wu, Cheng-Wei Shih, Yu-Ren Chen, and Wen-Lian Hsu. 2008, November. Boosting Chinese Question Answering with Two Lightweight Methods: ABSPs and SCO-QAT. ACM Transactions on Asian Language Information Processing (TALIP), 7(4), pp. 12:1-12:29. [Ei Compendex; Non-self citations: 9]
> Division of labor:
> - Cheng-Wei Lee: project manager.
> - Min-Yuh Day: SVM-based answer classification.
> - Cheng-Lung Sung: pairwise multiple sequence alignment for template generation.
> - Yi-Hsun Lee: template and answer ranking.
> - Tian-Jian Jiang: query term generation from questions, passage retrieval by Lucene and Lemur/Indri.
> - Chia-Wei Wu: MaxEnt-based named entity recognition.
> - Cheng-Wei Shih: template and answer ranking.
> - Yu-Ren Chen: software maintenance.

## Conference Papers
[4] Mike Tian-Jian Jiang. 2017, December. DGLab Question Answering System and Automatic Evaluation Method at NTCIR-13 QA Lab-3 for University Entrance Exam on World History Essay. Proceedings of the 13th NTCIR conference (NTCIR-13), pp. 166-170. [The best system among 4 teams for both Japanese and English]

[5] Chan-Hung Kuo, Shih-Hung Liu, Mike Tian-Jian Jiang, Cheng-Wei Lee, Wen-Lian Hsu. 2012, July. Cost-benefit Analysis of Two-stage Conditional Random Felds based English-to-Chinese Machine Transliteration. Proceedings of the 4th Named Entity Workshop (NEWS), the 50th Annual Meeting of the Association for Computational Linguistics (ACL), pages 76-80.
> Division of labor:
> - Mike Tian-Jian Jiang: project manger, methodology.
> - Chan-Hung Kuo, Shih-Hung Liu: experiment.
> - Cheng-Wei Lee: consultant.

[6] Mike Tian-Jian Jiang, Cheng-Wei Shih, Chan-Hung Kuo, Richard Tzong-Han Tsai and Wen-Lian Hsu. 2011, December. Evaluation via Negativa of Chinese Word Segmentation for Information Retrieval. Proceedings of the 25th Pacific Asia Conference on Language Information and Computing (PACLIC 25), pp. 100-109. [ISI CPCI, ACL Anthology; Acceptance rate=40% (oral), 20% (overall); Non-self citations: 1]
> Division of labor:
> - Mike Tian-Jian Jiang: project manger, methodology.
> - Cheng-Wei Shih: IR experiment.
> - Chan-Hung Kuo: CRF model generation.
> - Richard Tzong-Han Tsai: consultant.

[7] Mike Tian-Jian Jiang, Wen-Lian Hsu, Chan-Hung Kuo, and Ting-Hao Yang. 2011, November. Enhancement of Unsupervised Feature Selection for Conditional Random Fields Learning in Chinese Word Segmentation. Proceedings of the 7th IEEE International Conference on Natural Language Processing and Knowledge Engineering (NLPKE 2011), pp. 382-389. [ISI CPCI, Ei Compendex; Acceptance rate=82/225=36.4%; Non-self citations: 1]
> Division of labor:
> - Mike Tian-Jian Jiang: project manager, methodology.
> - Chan-Hung Kuo: CRF experiment, feature labeling.
> - Ting-Hao Yang: CRF experiment, feature labeling.

[8] Mike Tian-Jian Jiang, Chan-Hung Kuo, and Wen-Lian Hsu. 2011, November. Using Accessor Variety Features of Source Graphemes in Machine Transliteration of English to Chinese. The 2011 Conference on Technologies and Applications of Artificial Intelligence (TAAI 2011), pp. 132-138. [Ei Compendex, DBLP]
> Division of labor:
> - Mike Tian-Jian Jiang: project manger, methodology.
> - Chan-Hung Kuo: CRF experiment, feature labeling.

[9] Mike Tian-Jian Jiang, Chen-Wei Lee, Chad Liu, Yung-Chun Chang, and Wen-Lian Hsu. 2011, November. Robustness Analysis of Adaptive Chinese Input Methods. Proceedings of the 1st Workshop on Advances in Text Input Methods (WTIM 2011), the 5th International Joint Conference on Natural Language Processing (IJCNLP 2011), pp. 53-61. [ISI CPCI, ACL Anthology]
> Division of labor:
> - Mike Tian-Jian Jiang: project manager, methodology.
> - Chen-Wei Lee: character-based bi-gram sampling.
> - Chad Liu: experiment.
> - Yung-Chun Chang: experiment.

[10] Mike Tian-Jian Jiang, Chan-Hung Kuo, and Wen-Lian Hsu. 2011, November. English-to-Chinese Machine Transliteration using Accessor Variety Features of Source Graphemes. Proceedings of the 3rd Named Entity Workshop (NEWS 2011), the 5th International Joint Conference on Natural Language Processing (IJCNLP 2011), pp. 86-90. [ISI CPCI, ACL Anthology; Non-self citations: 1]
> Division of labor:
> - Mike Tian-Jian Jiang: project manager, methodology.
> - Chan-Hung Kuo: CRF experiment, feature labeling.

[11] Ting-Hao Yang, Tian-Jian Jiang, Chan-Hung Kuo, Richard Tzong-Han Tsai, and Wen-Lian Hsu. 2011, September. Unsupervised Overlapping Feature Selection for Conditional Random Fields Learning in Chinese Word Segmentation. Proceedings of the 23rd Conference on Computational Linguistics and Speech Processing (ROCLING 2011), pp. 109-122. [ACL Anthology; Invited paper; Non-self citations: 3]
> Division of labor:
> - Ting-Hao Yang: feature labeling.
> - Tian-Jian Jiang: project manger, methodology.
> - Chan-Hung Kuo: CRF experiment.
> - Richard Tzong-Han Tsai: consultant.

[12] Tian-Jian Jiang, Shih-Hung Liu, Cheng-Lung Sung, and Wen-Lian Hsu. 2010, September. Term Contributed Boundary Feature using Conditional Random Fields for Chinese Word Segmentation Task. Proceedings of the 22nd Conference on Computational Linguistics and Speech Processing (ROCLING 2010), pp. 143-156. [ACL Anthology; Non-self citations: 2]
> Division of labor:
> - Tian-Jian Jiang: project manager, methodology.
> - Shih-Hung Liu: CRF experiment.
> - Cheng-Lung Sung: suffix array based pattern extraction.

[13] Tian-Jian Jiang, Shih-Hung Liu, Cheng-Lung Sung, and Wen-Lian Hsu. 2010, August. Term Contributed Boundary Tagging by Conditional Random Fields for SIGHAN 2010 Chinese Word Segmentation Bakeoff. Proceedings of the 1st CIPS-SIGHAN Joint Conference on Chinese Language Processing, pp. 266-269. [ACL Anthology; Non-self citations: 1]
> Division of labor:
> - Tian-Jian Jiang: project manager, methodology.
> - Shih-Hung Liu: CRF experiment.
> - Cheng-Lung Sung: suffix array based pattern extraction.

[14] Cheng-Wei Lee, Min-Yuh Day, Cheng-Lung Sung, Yi-Hsun Lee, Tian-Jian Jiang, Chia-Wei Wu, Cheng-Wei Shih, Yu-Ren Chen, and Wen-Lian Hsu. 2007, May. Chinese-Chinese and English-Chinese Question Answering with ASQA at NTCIR-6 CLQA. Proceedings of NTCIR-6 Workshop Meeting, pp. 175-181. [Non-self citations: 5]
> Division of labor:
> - Cheng-Wei Lee: project manager.
> - Min-Yuh Day: SVM-based answer classification.
> - Cheng-Lung Sung: pairwise multi-sequence alignment for template generation.
> - Yi-Hsun Lee: template and answer ranking.
> - Tian-Jian Jiang: passage retrieval.
> - Chia-Wei Wu: MaxEnt-based named entity recognition.
> - Cheng-Wei Shih: template and answer ranking.
> - Yu-Ren Chen: software maintenance.

[15] Siaw-Fong Chung, Tian-Jian Jiang, Kamrul Hasan, Sophia Lee, I-Li Su, Laurent Prevot, Chu-Ren Huang. 2007, January. Extending an International Lexical Framework for Asian Languages, the Case of Mandarin, Taiwanese, Cantonese, Bangla and Malay. Proceedings of the First International Workshop on Intercultural Collaboration (IWIC), pp. 24-26. [Non-self citations: 5]

[16] Laurent Prevot, Chu-Ren Huang, Kamrul Hasan, Sophia Lee, I-Li Su, Siaw-Fong Chung, Tian-Jian Jiang. 2006. Meta-modeling and standardization issues for Asian Languages lexical resources. Proceedings of International Conference on Terminology, Standardization and Technology Transfer, pp. 151-162. [Non-self citations: 1]

[17] Siaw-Fong Chung, Kamrul Hasan, Tian-Jian Jiang, Sophia Lee, I-Li Su, Laurent Prevot and Chu-Ren Huang. 2006, August. Extending an international lexical framework for Asian languages, the case of Mandarin, Taiwanese, Cantonese, Bangla and Malay. 第五屆數位典藏技術研討會, pp. 87-94. [Non-self citations: 1]
> Division of labor for the above three papers:
> - Siaw-Fong Chung: Malay.
> - Tian-Jian Jiang: Taiwanese (Min-nan).
> - Kamrul Hasan: Bangla.
> - Sophia Lee: Cantonese.
> - I-Li Su: Mandarin.
> - Laurent Prevot: project manager.
> - Chu-Ren Huang: methodology.

[18] Hao Tang, Cheng-Wei Lee, Tian-Jian Jiang, and Wen-Lian Hsu. 2006, December. Query Term Selection Strategies for Web-based Chinese Factoid Question Answering. Proceedings of the 11th Conference on Artificial Intelligence and Applications (TAAI 2006). [Non-self citations: 2]
> Division of labor:
> - Hao Tang: query term selection, factoid question answering.
> - Cheng-Wei Lee: project manager.
> - Tian-Jian Jiang: query term generation and selection.

[19] Shih-Hung Wu, Chen-Yu Su, Tian-Jian Jiang, and Wen-Lian Hsu. 2006, September. An Evaluation of Adopting Language Model as the Checker of Preposition Usage. Proceedings of the 18th Conference on Computational Linguistics and Speech Processing (ROCLING 2006), pp. 369-386. [ACL Anthology; Non-self citations: 4]
> Division of labor:
> - Shih-Hung Wu: project manager, methodology.
> - Chen-Yu Su: experiment.
> - Tian-Jian Jiang: consultant of language modeling.

[20] Cheng-Wei Lee, Cheng-Wei Shih, Min-Yuh Day, Tzong-Han Tsai, Tian-Jian Jiang, Chia-Wei Wu, Cheng-Lung Sung, Yu-Ren Chen, Shih-Hung Wu, and Wen-Lian Hsu. 2005. ASQA: Academia Sinica Question Answering System for NTCIR-5 CLQA. Proceedings of NTCIR-5 Workshop, pp. 202-208. [Non-self citations: 17]
> Division of labor:
> - Cheng-Wei Lee: project manager.
> - Cheng-Wei Shih: template and answer ranking.
> - Min-Yuh Day: SVM-based answer classification.
> - Tzong-Han Tsai: MaxEnt-based named entity recognition.
> - Tian-Jian Jiang: query term generation from questions, passage retrieval by Lucene and Lemur/Indri.
> - Chia-Wei Wu: MaxEnt-based named entity recognition.
> - Cheng-Lung Sung: pairwise multiple sequence alignment for template generation.
> - Yu-Ren Chen: software maintenance.
> - Shih-Hung Wu: consultant.

[21] Cheng-Wei Lee, Cheng-Wei Shih, Min-Yuh Day, Tzong-Han Tsai, Tian-Jian Jiang, Chia-Wei Wu, Cheng-Lung Sung, Yu-Ren Chen, Shih-Hung Wu, and Wen-Lian Hsu. 2005, December. Perspectives on Chinese Question Answering Systems. Proceedings of the Workshop on the Sciences of the Artificial (WSA 2005). [Non-self citations: 3]
> Division of labor:
> - Cheng-Wei Lee: project manager.
> - Cheng-Wei Shih: template and answer ranking.
> - Min-Yuh Day: SVM-based answer classification.
> - Tzong-Han Tsai: MaxEnt-based named entity recognition.
> - Tian-Jian Jiang: query term generation from questions, passage retrieval by Lucene and Lemur/Indri.
> - Chia-Wei Wu: MaxEnt-based named entity recognition.
> - Cheng-Lung Sung: pairwise multiple sequence alignment for template generation.
> - Yu-Ren Chen: software maintenance.
> - Shih-Hung Wu: consultant.

[22] Jia-Lin Tsai, Tien-Jien Chiang, and Wen-Lian Hsu. 2004, September. Applying Meaningful Word-Pair Identifier to the Chinese Syllable-to-Word Conversion Problem. Proceedings of the 16th Conference on Computational Linguistics and Speech Processing (ROCLING 2004). [ACL Anthology; Non-self citations: 3]
> Division of labor:
> - Jia-Lin Tsai: project manager, methodology.
> - Tien-Jien Chiang: experiment, split/merge forward-backword maximum matching methodology.
