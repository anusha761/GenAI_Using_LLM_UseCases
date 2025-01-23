# Generative AI With LLMs - Performing Dialog Summarization
> This project focuses on leveraging Generative AI capabilities, using 2 approaches, prompt engineering and finetuning on Flan T5 Large Language Model to perform dialog summarization.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- This project uses GenAI capabilities to perform Dialog Summarization. There are 2 approaches in the project - prompt engineering, that is simple and crafts the input parameters without tampering the underlying parameters and finetuning, that tailors the model’s weights and knowledge to specific tasks or domains, generating contextually relevant responses. Both use approaches use Large Language Model Flan T5. One approach demonstrates the use of few shot prompting technique to improve the summarization process. The other approach goes deeper and does two ways of fine tuning - full fine tuning and Parameter Efficient Fine Tuning (PEFT) to further enhance the understanding of content and summarization capabilities of the LLM.



## Conclusion
For prompt engineering approachFew shot prompting yielded good result. It is a simple, fast, yet effective way of generating responses from Large Language Models, without modifying underlying parameters. The fine tuned models generate more accurate and relevant responses by tuning the underlying parameters but these techniques are very time consuming and computationally intensive. Both the full fine tuned model and the PEFT model did noticeably well than the original model. PEFT model results were slightly lesser than the full fine tuned model but the results are still acceptable. The training time and computational resource intensity are quite lower than the full fine tuned model and outweighs the slight decrease in performance.




## Technologies Used
- pandas - version 2.2.2
- numpy - version 1.26.4
- transformers - version 4.27.2
- peft - version 0.3.0
- torch - version 1.13.1


  ## Contact
  Anusha Chaudhuri [anusha761]
