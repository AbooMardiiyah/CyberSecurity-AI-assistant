### FineTuning Qwen2.5-7B model on cybersecurity data

### High Level Diagram
![CyberQwen architecture diagram](https://drive.google.com/file/d/1SmrEHoqCb0z66awarAuEQCuj3H-75csO/view?usp=sharing)

I fine-tuned and deployed an  LLM using FastAPI and ngrok within google colab. 
This process consists of 4 notebooks following the data collection pipeline and typical FTI pipeline architecture for any ML project.
To successfully run the codes, you need the following:
*  create a huggingface token and save it in the environment variable,
*  also you will need comet-ml key for logging the training parameters.
*  create an ngrok key which  is needed to run the fastapi application
*  lastly, OpenAI api key to generate synthetic dataset. Explanations on how to get this keys is mentioned in the video. 

Here is the link to the [vide presentation](https://drive.google.com/file/d/1xjyi1gU_nz2FiCiJ6LOPoSqsK2_-M-vL/view?usp=sharing). 
Here is the link to the [slides presentation](https://docs.google.com/presentation/d/1aQjyHV9I9tQ1rBnUWiI483jZ-FlLlAVD9DZBTPOKiMw/edit?usp=sharing). 

### Future Improvements for the coding and practical section includes : 
  * Collaboration with stakeholders to collect requirements
  * Set up proper infrastructure to track and orchestrate data collection, feature generation , fine-tuning and inference pipeline (ZenML and Opik for LLM monitoring)
  * Data Quality validation and improvement (use frameworks like distilabel, flesch, text-descriptives, semhash etc).
  * LLM monitoring and evaluation ( LLM as a judge)
  * Prompt engineering.
  * Implementing advanced RAG techniques and so much more .

