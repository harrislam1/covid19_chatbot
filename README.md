# covid19_chatbot ![alt text][logo]
[logo]:https://github.com/harrislam1/covid19_chatbot/blob/master/c0481846-wuhan_novel_coronavirus_illustration-spl.jpg "COVID19 Illustration"
The purpose of this chatbot is to provide general advice to questions regarding COVID-19.  

# Description
This project uses the BERT [Deeppavlov](http://docs.deeppavlov.ai/en/master/) Framework for classifying and creating responses to questions. 
It was trained with a corpus based on the CDC and WHO websites, which then was put to be hosted on a Heroku server.

# Instructions to get this chatbot running locally
1) Download this repo
2) `pip3 install -r requirements.txt` to your local environment
3) Run `python3 app.py` command on your terminal
4) Click on link that appears at the end(it should be localhost:5000) 
