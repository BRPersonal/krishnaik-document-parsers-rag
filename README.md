# krishnaik-document-parsers-rag
Demo of docling,unstructured and llamaparse document parsers

#---------requirements.txt--------
# Document Parsers for RAG - Requirements
# Python 3.10-3.12 recommended
python-dotenv
openai
chromadb
docling==2.55.1
docling-core[chunking]
langchain-docling
unstructured==0.18.15
unstructured[all-docs]
langchain-unstructured
unstructured-inference
unstructured[local-inference]
llama-parse
llama-index
llama-cloud-services
llama-index-vector-stores-chroma
llama-index-embeddings-openai
llama-index-llms-openai
nest-asyncio
langchain
langchain-community
langchain-openai
transformers
sentence-transformers
pandas
openpyxl
pdfminer.six
pi-heif
python-docx
python-pptx
Pillow
#----------------------------------

Setup the project
$ uv init --python 3.12.9
$ uv add --requirements requirements.txt
$ uv add jupyter


verify the python version
$ cat .python-version 
$ cat pyproject.toml
$ ls -alt # you should see uv.lock

Once pyproject.toml is created, you can delete requirements.txt
If you have pyproject.toml file , run
$ uv sync
It will create the virtual environment, install all the packages and create uv.lock file
You are all set
