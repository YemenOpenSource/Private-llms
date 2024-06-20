# PrivateLLMs
 
you like ollama, and llama.cpp , you love PrivateLLMs decentralized (local) llms to run in your computer privately. 

## 1- Building Decentralized LLMs Computer:
  - first download [Ollama](https://ollama.com/download/) on your computer:
      - choose the OS version you want to download:\
             **`For Windows`** just click on [download (the preview)](https://ollama.com/download/OllamaSetup.exe)
     
          **`For Linux`** write this command in your terminal:
           in my case I am using wsl in Windows so, I can use the Linux command in the Windows terminal:
        ```
        curl -fsSL https://ollama.com/install.sh | sh
        ```
        
         
           **`For MacOS`**, click on [download](https://ollama.com/download/Ollama-darwin.zip) 

    - then after downloading the Ollama, run one of the following commands in your terminal, depending on the LLM you want:
      ```
      ollama run llama3
      ```
      ```
      ollama run Mistral
      ```
