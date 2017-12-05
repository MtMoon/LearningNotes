# 英文表述
1. our proposed model outperform a variety of strong baselines and achieve state-of-the-art performance.
2. XX models have recently proven to be successful at different tasks
3. another kind of tasks are centered around XXX, which have a broad set of applications
4. our experimental results also demonstrate that
5. in Section X， we detail the XXX，<font color=red> **这里detail做动词** </font>
6. XXX are hyper-parameters to be chosen
7. Previous accounts of semantic representation fall under three broad families
8. while poem generation is a highly creative process that involves not only rules but also innovations for which pure statistical models are not appropriate in principle.
9. More importantly, besides such strict regulations, a good quatrain should also read fluently, hold a consistent theme, and express a unique affection
10. has aroused a long-standing criticism for machine poem generation
11. The memory component involves a set of ‘direct’ mappings from input to output
12. The output from the two components are then integrated, leading to a consolidated output.
13. Using the Chinese poetry generation model shown in Fig. 1 as an example, this section discusses the creation of a memory-augmented neural mode
14. The output of the model is a posterior probability over the whole set of characters, written by:
15.  Since many of the low-energy areas are nothing to do with good generations
16. This section describes the experiments and results carried out in this paper
17. ECM addresses the factor in three ways
18. In recent years, there has been a rising tendency in AI research to enhance Human-Computer Interaction by humanizing machines
19. to create a robot capable of acting and talking with a user at the human level requires the robot to understand human cognitive behaviors, while one of the most important human behaviors is expressing and understanding emotions and affects
20.  it is necessary to equip the machine with emotional intelligence.
21. There have been prior works on endowing dialogue systems or conversational agents with emotional intelligence, through text, facial expression,and other modalities <font color=red>这里主要注意endow with的用法 </font>
22. In this paper, we address the problem of generating emotional responses in conversational chatbots <font color=red>这里是address的用法</font>
23. To the best of our knowledge, this is the first work addressing the emotion factor in large-scale conversation generation. To summarize, our contributions are as follows: <font color=red>注意这个词组， To the best of our knowledge。 然后论文结构中，To summarize, our contributions are as follows:这个表述 </font>
24. Data-driven approaches are applied to build
25. Due to the success of <font color=red>注意due to，相比于because of， due to有得益于，归功于的意味 </font>
26. Existing works focus on improving the content quality of generated responses <font color=red>这个表述注意，existing works </font>
27. avoid meaningless response is to apply deep reinforcement learning which can model the long-term delayed reward in chatbot’s dialogues
28. Memory Network (Weston et al., 2014) and Neural Turing Machine (NTM) augment traditional RNNs with memory structures to improve the ability of modeling long-range sequences<font color=red>这里的argument ... with ... 应该是把 ... 参数以 ...的意思</font>
29. Inspired by these models,<font color=red>受这些模型的启发</font>
30. Before presenting the proposed model, we first introduce <font color=red>这个表述比较重要</font>
31. Details of GRU can be found in XXX
32. Once the state vector st is obtained, the decoder generates a token by sampling from the output probability distribution ot computed from the decoder’s state st , as follows:<font color=red>注意once的用法，即一旦。。。</font>
33. Since an emotion category (for instance, Anger, Disgust, Happiness) provides a high-level abstraction of an expression of the emotion <font color=red>这里可以用在style里</font>
34.  This is mainly because they acquire such knowledge based<font color=red>两个注意点， 主要是因为，以及such knowledge </font>
35. When trained with a very large corpus, traditional language models have demonstrated to some extent the ability to encode/decode knowledge
36. Media produce an endless stream of new knowledge every day
37. We do not investigate the reasoning ability in this paper but highlight this example because the explicit representation of facts would help to handle such examples.
38. In this paper, we propose a XXX model as a step towards addressing the limitations of traditional language modeling when it comes to exploiting factual knowledge
39. It is especially noteworthy that<font color=red>注意这个表示，特别值得注意的是</font>
40. This approach has proven to be very effective and efficient for<font color=red>这个表述也是值得注意，</font>
41. In the simplest seq2seq scenario<font color=red>这里要注意的是短语，in the scenario of XXX 或者是 in the XXX scenario. </font>
42.  Many different sequential (and non-sequential) encoders have proven to be effective for different source domains<font color=red>XXX have to be effective for</font>
43. The decoder is tasked with generating a target sequence of words from a target vocabulary
44. We begin by making one small change to the seq2seq modeling framework <font color=red>这里的表述是we begin by making XXX </font>
45. where we have omitted the x argument to f for brevity. <font color=red>这里的表述，为了简洁省略了bias </font>
46.  using a scoring function f parameterized with an RNN<font color=red>这里 parameterized with an RNN 以...为参数化 </font>
47. Neural generation models are of growing interest for various applications.
48. To show the generality of the model
49. The most relevant is work from
50. In this section, we introduce the proposed algorithm.  We first go over the vanilla beam search method and then detail the proposed algorithm which fosters diversity during decoding.
51. Recently, neural network-based sequence-to-sequence learning (Seq2Seq) has achieved remarkable success in various natural language processing (NLP) tasks, including but not limited to<font color=red>一个表述：including but not limited to</font>
52. Our most successful approach falls into the second category (sub-word units)
53. When α = 0 and β = 0, our decoder falls back to pure beam search by probabili<font color=red>这里的表述： falls back to 退化回 </font>
54. The past several years have witnessed the rapid progress of end-to-end Neural Machine Translation (NMT)<font color=red>The past several years have witnessed the rapid progress of 拟人手法</font>
55. Whenever possible, we omit the source index j to make the illustration less cluttered.
56. For example, if a source word is translated in the past, it is less likely to be translated again and should be assigned a lower alignment probability
57. and therefore are prone to the “coverage” mistakes<font color=red>这里的表述： be prone to 易于，有...的倾向</font>
58. where the term XXX penalizes the discrepancy between the sum of alignment probabilities and the expected fertility for linguistic coverage.
59. Semantic networks constitute a some-what idealized representation that<font color=red>在某种程度上有点理想化的 a some-what idealized</font>
60. However, a number of difficulties arise when working with such data<font color=red>这句也很重要，arise的用法</font>
61. Semantic space models have been successful at simulating a wide range of psycholinguistic phenomena including semantic priming<font color=red>词组 been successful at</font>
62. These models are similar in spirit to LSA
63. Thus, full understanding of the compositional process involves an account of how novel interpretations are integrated with existing knowledge
64. and its occurrence across a range of contexts can be constructed in the same manner as described above
65. which form the building blocks of larger units. If we cannot model the composition of basic phrases, there is little hope that we can construct compositional representations for sentences or even documents (we return to this issue in our Discussion section)
66. This simplified semantic space will serve to illustrate examples of the composition functions we consider in this paper<font color=red>词组 serve to</font>
67. excluding a list of stop words
68. it has proven challenging to deal with
69. However, low values of n impose an artificially local horizon to the language model
70. a small fraction of the training costs of the best models from the literature<font color=red>注意from the literature，“从现有文献中” </font>
71. On each of these projected versions of queries, keys and values we then perform the attention function in parallel, yielding dv -dimensional output values.<font color=red>注意测例yielding的用法</font>
72. which is most often the case wit
73. the goal of the system is to answer the question by retrieving the supporting fact for that question, from which the answer can be derived
74. Both soft attention and hard attention have limitations
75.  It is computationally very expensive
76.  So instead, 
77. This should reduce the approximation bias and hence improve the overall performance.
78. Composing classic poems is considered as a challenging task with a set of structural, phonological, and semantic requirements, hence only few best scholars are able to master the skill to manipulate or to organize terms.
79. It is relatively straightforward for the machine to check whether a candidate poem conforms to those requirements.
80. To sum up,   our contributions are as follows:  For the first time, XXX
81.  Its input is the word embedding of the previous character, augmented with the global information vector
82. Question answering (QA) is a complex natural language processing task which requires an understanding of the meaning of a text and the ability to reason over relevant facts.
83. In cases where the input sequence is a single sentence, the input module outputs the hidden states of the recurrent network.
84.  We abbreviate the above computation with ht = GRU (xt , ht−1 ).
85.  For each pass i, the mechanism takes as input a candidate fact ct. <font color=red>注意这里，当as input表示的内容太长时，可以将as input前置 </font>
