The notebook contains an assessment of the [stabelelm3b model](https://huggingface.co/stabilityai/stablelm-3b-4e1t) in text summarization through zero-shot and one-shot in-context learning as well as instruction tuning. 
The implementation is done with Python and the help of Hugging Face. The dataset used for the task is [TweetSumm](https://huggingface.co/datasets/Salesforce/dialogstudio/viewer/TweetSumm). 

Data is first cleaned by removing links and IDs and etc. Then it is converted to a reasonalble format and prompts are built according to the required task, zero-shot, one-shot or model tuning.
Assessment is done on the test set and model accuracy is reported by different rouge scores. 
