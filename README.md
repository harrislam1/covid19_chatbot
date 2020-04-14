# covid19_chatbot 

The purpose of this chatbot is to provide general advice to questions regarding COVID-19.  

![alt text](https://github.com/harrislam1/covid19_chatbot/blob/master/covid-19.png "COVID19 Illustration")


# Description
This project uses the BERT [Deeppavlov](http://docs.deeppavlov.ai/en/master/) Framework for classifying and creating responses to questions. 
It was trained with a corpus based on the CDC and WHO websites, which then was put to be hosted on a Heroku server.

# Instructions to run this chatbot locally on your computer
1) Download this repo
2) `pip3 install -r requirements.txt` to your local environment
3) Run `python3 app.py` command on your terminal
4) Click on link that appears at the end (it should be localhost:5000) 
