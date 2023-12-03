# Retrieval Augmented Generation (RAG)

**Steps to run the code:**
1. Create a virtual environment with python 3.10.13
`conda create --name RAG_bot python=3.10.13`
2. Activate in your new virtual environment
`conda activate RAG_bot`
3. Install the requirements
`pip install -r requirements.txt`
4. Install pytorch and faiss-gpu separately
`conda install pytorch pytorch-cuda=11.8 -c pytorch -c nvidia`
`conda install faiss-gpu`
5. Create a folder called `model` under `rag/`
6. Download Llama model `nous-hermes-llama-2-7b.Q4_0.gguf` from https://huggingface.co/TheBloke/Nous-Hermes-Llama-2-7B-GGUF/tree/main and add it to `model/`
7. Run the notebook
