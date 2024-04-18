# Large Language Models (LLMs) Projects 

These projects are part of DS5983 Special Topics in Data Science - LLMs at Khoury Collge, Northeastern University.

## Projects

* **Project 1 (N-gram models):** 
    * Test various n-gram models on Reuters.
* **Project 2 (Transformer Architecture Implementation and Machine Translation):** 
    * Implemented Transformer model architecture form scratch. Train the model on a machine translation task from German to English using the Multi30k dataset. 
    * Implemented greedy decoding and beam search for translation.
* **Project 3 (Text Summarization with HuggingFace BART):**     
    * Evaluated summarization of 3 pre-trained Hugging Face Transformer models BART, T5, Pegasus on SAMSum dataset. 
    * Improved BART model’s ROUGE score on testing set from 28.7 to 37.5 by fine-tuning with Mixed Precision (AMP).
* **Project 4 (Prompt Engineering and Few-Shot Learning with Flan-T5 for Dialogue Summarization):** 
    * Performed prompt engineering on Flan-T5 using dialogsum dataset with instructional prompts and pre-built T5 prompts. 
    * Experimented with zero-shot and few-shot learning to assess their impact on summaries' relevance and coherence.
* **Project 5 (Fine-Tuning Flan-T5 with PEFT (LoRA)):**        
    * Fine-tuned Flan-T5 LLM for dialogue summarization, employing full and parameter-efficient techniques (PEFT), achieving enhanced performance metrics evaluated via ROUGE scores. 
    * Applied Low-Rank Adaptation (LoRA) to optimize training efficiency, reducing computational resources while maintaining high accuracy in AI-driven summarization tasks.
* **Final Project (Chatbot leveraging RAG for Financial Document (10Q, 10K) Summarization)**: Check [github.com/kHarshit/Financial_Document_Summarization_through_RAG](https://github.com/kHarshit/Financial_Document_Summarization_through_RAG)
     * Developed Chatbot leveraging Retrieval Augmented Generation (RAG) with GPT, LLama 2, Gemma models to extract, summarize key performance indicators (KPIs) from 10-Q financial docs with LangChain, HuggingFace for LLM, Chroma for vector databases

### Syllabus

* Learn about different types of language models (statistical, neural).
* Understand the key components of large language models, their architecture, configuration, training procedures and optimization.    
* Understand the transformer architecture and its variants.
* Learn how to work with the HuggingFace transformer library.
* Become familiar with popular LLMs such as GPT, BERT, Flan-T5 and LLaMA.
* Implement, train, and fine-tune LLMs for various tasks, such as text genearation, summarization, and question answering.
* Evaluate and analyze the performance of LLMs using various evaluation metrics.
* Learn how to use LLMs as agents and general-purpose task solvers.
* Discuss the ethical and societal implications of using LLMs in different scenarios.
* Demonstrate creativity and innovation by applying LLMs to novel tasks or by tackling current challenges in the field.
