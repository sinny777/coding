## WIP on Learning Python coding

Please NOTE that this is currently WIP

### Prerequisites:

  - Install pyenv (For Windows)
  
 ```
  
  Invoke-WebRequest -UseBasicParsing -Uri "https://raw.githubusercontent.com/pyenv-win/pyenv-win/master/pyenv-win/install-pyenv-win.ps1" -OutFile "./install-pyenv-win.ps1"; &"./install-pyenv-win.ps1"

  pyenv --version

```

  - After installing pyenv 

```

pyenv install 3.10.2
pyenv global 3.10.2

pip install --upgrade pip

virtualenv venv -p python3.10.2
source venv/bin/activate
jupyter lab

#pip freeze > requirements.txt
pip install -r requirements.txt

```

  - **Or you can install following libraries separately as well**

```

pip install python-dotenv
pip install jupyterlab
pip install matplotlib

pip install --upgrade "ibm-watson>=7.0.0"
pip install "ibm-watson-machine-learning>=1.0.320" | tail -n 1
pip install "pydantic>=1.10.0" | tail -n 1
pip install langchain | tail -n 1
pip install langchain --upgrade
pip install PyPDF2
pip install --upgrade pymupdf

pip install "unstructured[pdf]"
pip install chromadb
pip install chroma-migrate

pip install llama-index llama_hub wikipedia
pip install llama-cpp-python


pip install pypdf
pip install InstructorEmbedding
pip install 'transformers[torch]'
pip install sentence-transformers
pip install Flask flask-restful flask_httpauth
pip install cachetools
pip install unstructured
pip install from-root
pip install text-extensions-for-pandas
pip install --upgrade ibm-watson
pip install tensorflow


```

### Make sure you have ".env" file with following content

```

LOGLEVEL=DEBUG

GENAI_KEY=pak-<REPLACE IT WITH YOUR IBM GENAI APIKEY>
GENAI_API=<REPLACE IT WITH YOUR IBM GENAI ENDPOINT>

REST_USERNAME=admin
REST_PASSWORD=1SatnamW
DATA_PATH=./datasets


```

## REFERENCES:

  - [Python Course](https://neetcode.io/courses/lessons/python-for-coding-interviews)
  - [Deploy Watson NLP model to CP4D](https://medium.com/@alex.lang/deploy-watson-nlp-models-in-ibm-cloud-pak-for-data-f16b4d8b0cc7)
  - [Watson NLP Embed Documentation](https://www.ibm.com/docs/en/watson-libraries?topic=models-creating-custom)
  
