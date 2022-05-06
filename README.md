# Who did what to Whom? Transformers and humans respond diversely to features effecting arguments relationship

Pre-trained transformer-based language models have achieved state-of-art performance in many areas of NLP, but it is an open question whether the models are capable of integrating syntax and semantics in language processing like humans. To study this, we focus on argument hierarchy construction using the Chinese structure “NP1+\textsc{ba/bei}+NP2+VP” and investigate if models and humans interpret the relation between NP1 and NP2 similarly with the effect of cues representing telicity, agency and individuation. By analyzing the data collected from a human acceptability judgment experiment and output from various language models, we find that 

1) models and humans respond to (non-)agentive and atelic features very similarly. 
2) Differently, the models show insufficient sensitivity to pragmatic functional meaning and individuation concept which humans heavily rely on to establish arguments' relation. 
3) Furthermore, it is found that the models tend to interpret subject as agent. In contrary, Chinese speakers' agent alignment is independent on subject position.


Note: We conducted a human acceptability judgment experiment using a four-point-scale questionnaire to obtain human ratings for the sentences in each condition. 
Participants are required to judge the sentences following this instruction: the fully acceptable sentences should be marked as 1; sentences including rather acceptable phrasings should be marked as 2; sentences including rather unacceptable phrasing should be marked as 3, and sentences including some fully unacceptable phrasing should be marked as 4. A larger score indicates a sentence is less acceptable.

Tested language models: Bert-base, ELECTRA-large, RoBERTa-base, ERNIE 1.0 and MacBERT-base/large
