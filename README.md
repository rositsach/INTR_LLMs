# Introduction to LLMs 

## Installed Packages

python=3.11

```
openai==0.28 
config==0.5.1 
langchain==0.0.297 
pydantic==1.10.9 
tiktoken==0.5.1 
faiss-cpu==1.7.4 
transformers==4.47.1 
torch==2.5.1 
datasets==3.2.0 
evaluate==0.4.3 
accelerate==1.2.1 
ipywidgets==8.1.5 
matplotlib==3.10.0 
seaborn==0.13.2 
clean-text==0.6.0 
scikit-learn==1.6.0 
sentencepiece==0.2.0 
pandas==2.0.0
```


## Conda Environment

```
conda create –name llms_course_env python=3.11
conda activate llms_course_env
pip install openai==0.28 config==0.5.1 langchain==0.0.297 pydantic==1.10.9 tiktoken==0.5.1 faiss-cpu==1.7.4 transformers==4.47.1 torch==2.5.1 datasets==3.2.0 evaluate==0.4.3 accelerate==1.2.1 ipywidgets==8.1.5 matplotlib==3.10.0 seaborn==0.13.2 clean-text==0.6.0 scikit-learn==1.6.0 sentencepiece==0.2.0 pandas==2.0.0
pip install ipykernel jupyterlab notebook
python -m ipykernel install --user --name=llms_course_env
```

Then when in the notebook, remember to check the kernel is set to "llms_course_env". 
