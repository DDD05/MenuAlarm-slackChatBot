# Menu Alarm ChatBot (Slack)

식당 메뉴를 알려주는 Slack 용 챗봇입니다.



### 🔨Stack

- 언어
  - `Python`
- `Flask`,`beautifulsoup4`,`slackeventsapi`



### 🔧Install

- [Install python 3.6.8](https://www.python.org/downloads/release/python-368/)

      > python --version
      Python 3.6.8

- Install package

      # package list include 'requirements.txt' file 
      > pip install -r requirements.txt

- Install [ngrok](https://dashboard.ngrok.com/get-started) server

  ``` ba
  $ unzip /ngrok.zip
  ```



### 🔸Run

- Chatbot Server

  ```bash
  > python ./chatbot_project/control_chatbot.py
  ```

* ngrok Server

  ```bash
  $ {path_download_ngrok}/ngrok.exe http 5000
  ```



### 👓UI

![image-20200327172155817](./picture/page1.jpg)