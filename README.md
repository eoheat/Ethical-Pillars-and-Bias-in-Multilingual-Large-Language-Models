# Ethical-Pillars-and-Bias-in-Multilingual-Large-Language-Models

This repository is the official implementation of Ethical Pillars and Bias in Multilingual Large Language Models.

# Paper Overview
From healthcare to educational guidance, artificial intelligence increasingly shapes consequential decisions. Therefore, it is critical to understand whether large language models (LLMs) engage in true moral reasoning or merely reproduce ethically coded language patterns. This paper develops and tests a systematic framework for evaluating the moral reasoning capabilities of large language models (LLMs) across four languages through a philosophical lens. It builds on the key ethical theories of deontology, consequentialism, and virtue ethics, and extends them with new indices. This approach utilizes a seven-pillar rubric that focuses on the depth of reasoning, coherence, context sensitivity, and cultural grounding. These results highlight the need for further research into the varying tendencies of LLMs across languages, moral ambiguity, and cultural alignment, given the numerous inconsistencies observed in these metrics.

# Requirements
To install dependencies:
pip install -r requirements.txt

# Evaluation
To evaluate, run each model independently.

# Results Discussion
<img width="1017" height="198" alt="image" src="https://github.com/user-attachments/assets/433b384a-4ecf-4973-8ee0-a20c6028c56f" />
<img width="1017" height="198" alt="image" src="https://github.com/user-attachments/assets/8af80a4c-be08-4500-a64c-eed01ca77898" />
<img width="1017" height="198" alt="image" src="https://github.com/user-attachments/assets/02de2fca-00fb-47aa-9791-2f88e32dcc26" />
<img width="1017" height="198" alt="image" src="https://github.com/user-attachments/assets/4a2d706c-8e2b-4866-91c7-a9ea070b87bf" />

# Deontology 
Throughout all languages and models, Deontology had low variance, showing that the appeal to duty-based reasoning is present but not necessarily dominant. The mean scores ranged from 1.7 to 2.2, with ChatGPT-5 and Mistral-3.2 Small performing higher in Spanish and Korean, while Gemini-2.5 flash and Claude-4 Sonnet showed higher consistency in Deontology in Mandarin. This alignment indicates that LLMs reference duties and rights fairly often but don’t have these concepts guide their philosophical frameworks. This shows that deontological reasoning is a supporting justification rather than a primary theory LLMs rely on. 


# Consequentialism
A high mean for consequentialism was present, with the majority of the models and languages having a range from 2.4 to 2.9 or above. This was by far the highest scoring category within our benchmarks, suggesting that moral alignment within LLMs were to consider consequences and outcomes much more explicitly compared to the other pillars. For example, in the Spanish and Mandarin outputs, Claude-4 Sonnet and Gemini-2.5 flash reached nearly the highest level performance possible, indicating consistency in outcome-based decision making. The stability of these results across languages implies that LLMs’ moral reasoning is heavily influenced by Western thought, prioritizing outcomes as the main moral determinant.

# Coherence 
The models and languages spanned widely in coherence, with scores ranging from 1.6 to 2.9. This may reveal that coherence is dependent on the training data of the model and language, as some of the models are consistent but have specific languages which largely deviate from the rest of the LLM’s coherence scores. High coherence values were observed in Claude-4 Sonnet and Gemini-2.5 flash, especially in English and Mandarin, where structure of argument was consistent even when reasoning differed. Models like Llama displayed fluctuations suggesting that reasoning is sensitive to language representation and token biases.

# Virtue Ethics
The variance for virtue ethics remained roughly the same, with scores hovering around the 1.5 to 2 range. With scores that land around the middle of scoring, it indicates that the LLMs have a relatively solid recall of virtue ethics, but fail to reason from it like deontology. In English and Korean GPT-4 and Mistral-3.2 Small showed slightly more frequent usage of virtue ethics related terms, potentially due to exposure to texts that emphasize character. The limited depth of virtue ethics reasoning shows that LLMs tend to treat virtues as less important than deontological and certainly consequentialist views.

# Context
The majority of the models all struggled with consistency in contextualization, with all the models having a range of context due to language. For example, Korean scored the highest on average for mean context across all models, which may point to the training data being a focal point in contextualization skills. Lower English and Mandarin context scores could indicate generalizations or abstraction bias. This supports the hypothesis that context reasoning in LLMs is not just about model size or diversity in training data, but of the relational semantics embedded within specific language corpora.

# Moral Uncertainty Index (MUI)
MUI scores typically ranged between 1.0 and 2.0 and showed much more cross-linguistic and model variation. Mandarin models tended to end up with higher MUI values, especially in Gemini-2.5 flash and Mistral, showing greater sensitivity to uncertainty. This could suggest that certain models are more likely to acknowledge uncertainty or weigh competing outcomes instead of making confident conclusions. On the other hand, lower MUI scores in English and Spanish responses, especially from Claude-4 Sonnet and ChatGPT-4, may show higher decisiveness, even when faced with hard decisions.

# Cultural Grounding and Reasoning Index (CGRI)
CGRI scores were low, with none having a mean higher than 1.0. This reveals a lack of cultural sensitivity in the reasoning of models. Mistral’s Mandarin performance (0.73) was the highest mean CGRI, showing some sensitivity, though still far from great. These results are similar to previous findings that models that are trained on English datasets often default to Western norms and overlook other cultures.








