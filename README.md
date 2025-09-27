# Llama-Model-Streamlit

# This Program With download a Llama Model and work on it.
# Here Llama 3.1 is being used (Even Phi3 and Llama3 are Commented)


Steps to be followed:
Step 1: Download Ollama Model - https://ollama.com/download/
Step 2: After downloading the Ollama Model install and run it.
Step 3: Now ollama Chatbot will work in your system directly.
Step 4: Now to integrate the Model with the a simple customized program(here Python, VS code) run the following command in terminal:
 - pip install ollama
 - pip pull llama3.1 # it will take some time to load the data
 - ollama run llama3.1 # Now you can run and check the if the llama model is being called, if you see the answer for you questions, it ready to be called for integration:)
 - pip install llama_index # if any issues occurs upgrade it by following cms: pip install --upgrade llama-index-llms-ollama
 - pip install streamlit # for the web framework.
Step 5: Now the Program would be ready for execution. Run the code:followed by command
 - streamlit run llama_app.py 
