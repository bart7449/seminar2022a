# Seminar II: Deep Learning-based Natural Language Processing
Natural language processing (NLP) is a crucial part of artificial intelligence (AI), modeling how machine understand and generate human languages.  
In recent years, deep learning approaches have obtained very high performance on many NLP tasks. 
In this course, students will gain knowledge about cutting-edge neural networks for NLP.

## Course Information
- This course meets for in-class lecture Fri 15:00 - 17:00 (Seminar room No.2 at KISTI KIUM).
- In this seminar class, students are asked to review seminal papers related to NLP techniques and present them in the class.
- Two or three papers will be reviewed every week. 
- For all inquiries related to this course, please contact kyongha@kisti.re.kr

### Instructor
This seminar is supervised by Dr. Kyong-Ha Lee at <a href="https://www.ust.ac.kr/prog/major/eng/sub03_03_02/IR/view.do?majorNo=32">KISTI campus</a>. 

### Time and Location
- Fri. 15:00  ~ 17:00
- <span style="color:red">Due to the spread of COVID 19 virus, some lectures may be held online.</span> 
## Materials
- Related lecture : Stanford CS224N http://web.stanford.edu/class/cs224n/
- A curated list of resources dedicated to Natural Language Processing https://github.com/keon/awesome-nlp
- All slides for this seminar class will be available here. 
## Logistics
- All course announcements take place though this page. Please check this page frequently.
- You must submit your presentation materials to me by e-mail one day before class.
- 
### Class components and grading
- Your grade will be recorded as a success or failure 

|Event|Date| In-class Presentation| Materials and Assignments|
|---------|----------|---------------------|------------|
|Week 1|4 March 2022| Course Introduction| None|
|Week 2|11 March 2022|<ul><li>Network archtecture(Srivastava)<li>NLP from scratch(Sunkyong)|<ul><li><a href="https://cs231n.github.io/neural-networks-1/">cs231n notes on network architectures</a><li><a href="https://www.jmlr.org/papers/volume12/collobert11a/collobert11a.pdf">Natural Language Processing(Almost from Scratch)</a>|
|Week 3|17 March 2022|Word embeddings<ul><li>Word2Vec(Juyeon)<li>GloVe(Ikjae)|<ul><li><a href="https://arxiv.org/pdf/1301.3781.pdf">Efficient Estimation of Word Representations in Vector Space</a> (original word2vec paper)<li><a href="https://proceedings.neurips.cc/paper/2013/file/9aa42b31882ec039965f3c4923ce901b-Paper.pdf">Distributed Representations of Words and Phrases and their Compositionality</a>(negative sampling paper)|
|Week 4|25 March 2022|Embeddings for Subwords and Graphs<ul><li>node2vec:Graph embedding(Tergel)<li>FastText(Srivastava)|<ul><li><a href="https://watermark.silverchair.com/tacl_a_00051.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAu8wggLrBgkqhkiG9w0BBwagggLcMIIC2AIBADCCAtEGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMYfUXl8QsN1DjBzoXAgEQgIIComnopfb1mZiHWrLVWvYEkhlldmUmVWjoK5K5_3oS_Ycf24IV-x8miLywACe0hWsTFaue4DOWpPYwRm1SawmG49nI8BbCq605AofDpuHhUfvbpAuHzNIY7qMK-Ek_2GcyB_RiFN5Qe22XfUYpBpPvlMCKLkfG9JJT3bQUL_YdA6Gjc5BMbuJ5MExBPG2oUjILuTjX514xpSH6zF4VcEIQnfGzChcRvwRXA0H34NmFzHz7hY7u8lB5V7IBQm9sUKt9QM7-qcCU1guIvBAADMy9yA7LUGFqTBV7g-dimPkYPYIAEsltWgPAZVcIYHl5FGX0Glw2v87_BdK-qG5ePHly_k9OoXu7ULhQ85p7XdsSUJX4VMKOICR3g0GBTAbEIZMFThwT4foM64tYFPz4cdCvUTFU3V07IF_COM9dTM-V93FVJwVAf3p9it9U3mx6Vk3ycfYdJS2U2QqCy30tzPPTmd3sZOsb_Lvyoc9bLThclQoZcpkR5X0TsAHjF9ehxISzyrR-XCFpnlQpqM8MkcMWKRxL2aFrdLtxP-_SHaxUURtRLhvJfRs5nLZY_emBCBdH4dkK0DVZehZnjFJ4zk0QC5bvRgjt8ouhFGEfstXNLfOJGQ7UOXsRbCRKzs1C2y36b4_iwD--Mf39JJ47kwNLg5GSZRXX4tw7bz9C8a3wJ6-WFRWvkjPJqhiiJ2-874zsA_Up4dY_oAI1VgsLNg5CgnJf_YFBYAl0pOc8F1mUcHXMrq_CD1iNPijvMYmANOVM3RRZygJ-2jEkUaH9ztwIu55nVpSVvTTG_uyrRWReWm4yy1qXptxMGYdwHwiGoiLobkrO6QuCkUKdFZHudW_s_JTSqigFDYfr1CYIHFRL-r2uon4Fzx57OyusyCthEFpcxhTe">Enriching Word Vectors with Subword Information</a><li><a href="https://dl.acm.org/doi/pdf/10.1145/2939672.2939754">node2vec: Scalable Feature Learning for Networks</a>|
|Week 5|25 March 2022|<ul><li>N-gram Language Models<li>Sequence Modeling:Recurrent and Recursive neural Nets|<ul><li>N-gram Language Models (textbook chapter)<li>The Unreasonable Effectiveness of Recurrent Neural Networks (blog post overview) <li>Sequence Modeling: Recurrent and Recursive Neural Nets (Sections 10.1 and 10.2)|  
|Week 5|1 April 2022|<ul><li>Vanishing gradients<li>Seq2Seq|<ul><li>Sequence Modeling: Recurrent and Recursive Neural Nets (Sections 10.3, 10.5, 10.7-10.12)<li>On the difficulty of training Recurrent Neural Networks (proof of vanishing gradient problem)<li>Vanishing Gradients Jupyter Notebook (demo for feedforward networks)<li>Understanding LSTM Networks (blog post overview)|
|Week 6|8 April 2022|<ul><li>Machine translation<li>Attention mechanism|<ul><li>Sequence to Sequence Learning with Neural Networks (original seq2seq NMT paper)<li>Neural Machine Translation by Jointly Learning to Align and Translate (original seq2seq+attention paper)<li>Attention and Augmented Recurrent Neural Networks (blog post overview) |
|Week 7|15 April 2022|Benchmarks |<ul><li>GLUE<li>KLUE|| 
|Week 8|22 April 2022| | |
|Week 9|29 April 2022| | |
|Week 10|6 May 2022| | |
|Week 11|13 May 2022| | |
|Week 12|20 May 2022| | |
|Week 13|27 May 2022| | |
|Week 14|3 June 2022| | |
|Week 15|10 June 2022| | |
|Week 16|17 June 2022| | |
  
