# Week 2 summary
- [x] Resposible research session
- [x] Look at GPT-Neo from hugging face and try to get it traning on a small dataset
- [x] Figure out the training stiuation (DefltBlue, Google Colab, My old gpu?)
- [x] While GPT-Neo is training, read through papers for this week (marked in zotero)
- [ ] Look at roBERTa from hugging face and try to get it training - moved to this week
- [x] Try agin following along with Karpathy videos
- [x] Chose 3 - 5 activations functions to work with and justify the choics
    In short
    - RELU - relu strikes back, the most used activation function
    - GELU - mostly used today bert and gpt - gated - to find long-range relationships in data
    - GeGlu - used by babyLM challenge  - gated
    - SiLu - to compare silu - gated or non gated or both?
    - Swish - parametric  SiLu
    - parametric PReLU
- [x] Write introduction of the report
- [x] trained baseline NEO
- [x] implemented relu NEO
- [ ] Prepeare week 3 presentation :o
- [ ] Write related works section of the reprot - more works coming in so moved to week 3
- [x] read through baby LM winner 2023
- [x] suvery layer norm paper
- [x] survey NormFormer paper -> forward snowball -> FoundationLayerNormalization, pre-norm, post-norm
    - does each of the 3 extra operations needs to be added to each leyer?
- [x] survey KAN: Kolmogorov–Arnold Networks

# Week 3 plan
- [] why is no one using adaptive activation functions in LLM?
- [] try to implementent LLM using adaptive activation function (swish and prelu)
- [] write related works section of the reprot
- [] ACS assigment 1
- [] write approach setion
- [] implement and train NEO with ReLU, GeLu, GeGLu, SiLU
- [] implement and train BERT with ReLU, GeLu, GeGLu, SiLU
- [] implement neo with ppost norm and normformer?