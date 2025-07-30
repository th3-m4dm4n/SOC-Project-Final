# SOC Project
# EchoChamber ID87 

<br><br>
The goal of this project was to learn the basics of Machine Learning models. About Python basics, various libraries, understanding Neural Networks and LLM's. <br>
The final project involved fine tuning an existing LLM (DialoGPT from huggingface in my case) to make a personlized chatbot. The pretrained model was fine tuned by me over
a dataset consisting of thousands of multi turn conversations from the television series "Friends" across all the 10 seasons. The dataset was obtained from convokit and the 
link to the file is https://drive.google.com/file/d/1fCezP7-wq1sVML-rWEBvqGhCjhIunnz2/view?usp=sharing. The model was trained from 10th July various times including different
parts of the dataset as well as the whole dataset altogether. The final model even though trained a lot does not perform well. Further training may solve the problem but for now
the model cannot be improved because of time commitments and the bigger problem of unavailability of resources. The model was trained on Google Colab with limited gpu runtime. 
One small training on a subset of the dataset needed 2-2.5 hours for training with and at max 2 such runtimes could be used once. Then 24 hours of cooldown needed. Hence a fast 
progress could not be made. Kaggle notebook was also used with a much higher limit over cloud based gpu but the training was too slow. Due to unavailavbility of local gpu, the 
training could not be done locally on jupyter notebook. Further runtime disconnect errors made the task much more difficult.<br>
Even with these challenges, the model was trained over 3 different datasets including movie dialogues, technical dialogues and casual conversations. But even when the model was
trained and used further for training, it could not learn much or rather learnt too much. Hypermeters were changed various times but a balance could not be found. An honest effort 
was made though to train the model with over 30 hours in total gone in training with further 6-8 hours gone in code writing, using AI to generate some parts and cleaning and debugging 
the code over the past 18 days. The code with output can be  viewed in the PDF.pdf file in the repo and one chat with the bot can be seen in the end where it is evident that the bot is 
'SHIT' in the current phase. Further improvement error is planned to make it like an actual chatbot.
