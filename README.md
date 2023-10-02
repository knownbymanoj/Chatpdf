
# Pdf Chatbot

The project is to use OpenAI embedding and chat models and help you answer queries related to the pdf you use.

(Hugging face models can also be used but need to have appropriate hardware)




## How to start using this code

#### 1) Git all the files using

```
git clone https://github.com/knownbymanoj/Chatpdf.git
```

#### 2) Install all requirements using 
```
pip install -r requirements.txt
```
#### 3) Update .env file which has your opeanAI or HuggingFace Models key

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `OPENAI_API_KEY=` | `string` | **Required**. Your API key |
| `HUGGINGFACEHUB_API_TOKEN=` | `string` | **Required**. Your API key |

#### 4) Run your Code in Terminal using and that's it your chatbot is on and a link is displayed and if not redirected you can coipy and paste the link in your browser.

```http
  streamlit run app.py
```

## That's it your chatbot looks like this 
### I have used my Resume as a example pdf since i found it easily
## Screenshots

![Chart Interface](https://github.com/knownbymanoj/SpeakPDFly/blob/main/github_1.png)
![Chart Interface](https://github.com/knownbymanoj/SpeakPDFly/blob/main/github_2.png)


## Acknowledgements

 - [Reference Github repo](https://github.com/alejandro-ao/ask-multiple-pdfs/tree/main)


