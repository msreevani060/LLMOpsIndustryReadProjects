## commands need to follow
mkdir <project_folder_name>
cd <project_folder_name>

## for conda env setup
conda create -p docpvenv python==3.10 -y

conda activate <path_of_env>

pip install -r requirements.txt

## git commands

git init

git add .

git commit -m "<write your commit message>"

git push

## for cloning repository

git clone https://github.com/msreevani060/LLMOpsIndustryReadProjects.git

## minimum requirement for this project
1. LLM Model ##groq (freely), openai (paid), gemini (15 days access free), claude (paid), huggingface(freely), ollama(local setup)

2. Embedding model # can load from openai, hf, gemini

3. Vectordatabases ## inmemory vector db, ##ondisk ##cloudbased most used. #inmemory to store in memory ones.

