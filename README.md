# LLM Tools Demo

The objective of this article is to run large language models locally to analyze local docs.

## Tools  

[LM Studio](https://github.com/AshleyDhevalall/llm-tools-demo/tree/main#lm-studio)  
[AnythingLLM](https://github.com/AshleyDhevalall/llm-tools-demo/tree/main#anythingllm)  
[GTP4All](https://github.com/AshleyDhevalall/llm-tools-demo/tree/main#gtp4all)  

## Comparison

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

## Clone repository
```
git clone https://github.com/AshleyDhevalall/llm-tools-demo.git
```

## LM Studio

### What is LM Studio?
LM Studio is a desktop app for developing and experimenting with LLMs on your computer.

Key functionality

- A desktop application for running local LLMs  
- A familiar chat interface  
- Search & download functionality (via Hugging Face 🤗)  
- A local server that can listen on OpenAI-like endpoints  
- Systems for managing local models and configurations  

### Steps to follow

1. Download [LM Studio](https://lmstudio.ai/)
> [!TIP]
> [QuickStart](https://lmstudio.ai/docs/basics#1-download-an-llm-to-your-computer)  

2. Open LM Studio. Please patient while the application opens...  
![lmstudio](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/lmstudio.png)

3. Download model (Click `My Models` on left menu). Ensure you have selected 'Developer' as the role
You can search for models by keyword (e.g. llama, gemma, lmstudio), or by providing a specific user/model string.  
You can even insert full Hugging Face URLs into the search bar!. Please patient while to model downloads...  
> [!TIP]
> [Download Models](https://lmstudio.ai/docs/basics/download-model)

![download](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/lmstudio_download.png)

4. Click `Chat` on left menu
> [!TIP]
> [Managing chats](https://lmstudio.ai/docs/basics/chat)
  
Select model
![select-model](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/lmstudio_select_model.png)

5. Navigate to the folder in [Clone Repository](https://github.com/AshleyDhevalall/llm-tools-demo/tree/main#clone-repository) and select the `samples\UsingSQLWithPowerShellExamplesv1.ps1` file

6. Enter your prompt and click `Send`
```
what passwords are used?
```

Sample chat response  
![chat_response](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/lmstudio_chat_response.png)

> [!IMPORTANT]  
> Always verify the accuracy of the results

### Further reading  
[Docs](https://lmstudio.ai/docs)  
[Download Models](https://lmstudio.ai/docs/basics/download-model)  
[Chat](https://lmstudio.ai/docs/basics/chat)  
[Chat with Documents](https://lmstudio.ai/docs/basics/rag)  



## AnythingLLM

### What is AnythingLLM?

It is an all-in-one zero-setup private application for local LLMs, RAG and AI Agents with embedding models and vector database supportability

### Steps to follow

1. Download [AnythingLLM](https://anythingllm.com/download)
> [!TIP]
> [QuickStart](https://docs.anythingllm.com/installation-desktop/overview)  

2. Open AnythingLLM. Please patient while the application opens...  
![anythingllm](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/anythingllm.png)

3. Create new workspace. Enter name for collection and click `Save`
> [!TIP]
> [Workspaces](https://docs.anythingllm.com/chat-ui)
<img src="https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/anythingllm_workspace.png" style='height: 30%; width: 30%;'>

4. Upload files.  Navigate to the folder in [Clone Repository](https://github.com/AshleyDhevalall/llm-tools-demo/tree/main#clone-repository) and select the `samples\romeo-and-juliet.pdf` file
> [!WARNING]  
> PDF, TXT, DOCX, Word docs and more. Unfortunately AnythingLLM does not support .ps1 file :(

<img src="https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/anythingllm_upload.png" style='height: 40%; width: 40%;'>

Drag and drop your files into the box shown below

<img src="https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/anythingllm_drag-and-drop.png" style='height: 40%; width: 40%;'>

Once complete, select the file and click `Move to Workspace`

<img src="https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/anythingllm_move-to-workspace.png" style='height: 60%; width: 60%;'>

Click `Save and Embed`

<img src="https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/anythingllm_embedding.png" style='height: 65%; width: 65%;'>

Please patient while the files complete embedding...

Close the `My Documents window` once the embedding is complete

<img src="https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/anythingllm_download.png" style='height: 50%; width: 50%;'>

5. Enter your prompt and click `Send prompt message to workspace` icon
```
Who are the characters in Romeo and Juliet?
```

Sample prompt response  
![chat](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/anythingllm_chat_response.png)

> [!IMPORTANT]  
> Always verify the accuracy of the results  

### Troubleshooting
Could not respond to message. fetch failed
> [!TIP]
> [Fetch failed error on embed](https://docs.anythingllm.com/fetch-failed-on-upload)

![troubleshooting](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/anythingllm_trouble-shooting.png)

### Further reading 
[Setup](https://docs.anythingllm.com/setup/llm-configuration/local/built-in)  
[Configuration](https://docs.anythingllm.com/configuration)  
[System Requirements](https://docs.anythingllm.com/installation-desktop/system-requirements)  
[FAQ](https://docs.anythingllm.com/llm-not-using-my-docs)  



## GTP4All

### What is GTP4All?

An open-source ecosystem used for integrating LLMs into applications without paying for a platform or hardware subscription. It was created by Nomic AI, an information cartography company that aims to improve access to AI resources.

Designed to run on modern to relatively modern PCs without needing an internet connection or even a GPU! This is possible since most of the models provided by GPT4All have been quantized to be as small as a few gigabytes, requiring only 4–16GB RAM to run.

### Steps to follow

1. Download [GPT4All Desktop](https://www.nomic.ai/gpt4all)
> [!TIP]
> [QuickStart](https://docs.gpt4all.io/gpt4all_desktop/quickstart.html)  

2. Open GTP4All. Please patient while the application opens...  
![open_gtp4all](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/gpt4all_open_gtp4all.png)

3. Adding new model (Click `Models` on left menu) and then click `+ Add Model` button  
> [!TIP]
> [Models](https://docs.gpt4all.io/gpt4all_desktop/models.html)

![add_model](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/gpt4all_add_model_1.png)

4. Search for `Llama 3.2 1B Instruct` and then click `Download`. Please patient while to model downloads...

![explore_models](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/gpt4all_explore_models.png)

5. Configure settings
> [!TIP]
> [Settings](https://docs.gpt4all.io/gpt4all_desktop/settings.html)

6.1 Click `LocalDocs` on left menu. Provide a `Collection name` eg. `Sample Test`
> [!TIP]
> [LocalDocs](https://docs.gpt4all.io/gpt4all_desktop/localdocs.html)  

<img src="https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/gpt4all_add_document_collection.png" style='height: 70%; width: 70%;'>

6.2 Click `Browse`. 

Navigate to the folder in [Clone Repository](https://github.com/AshleyDhevalall/llm-tools-demo/tree/main#clone-repository) and select the `samples` folder. Please patient while the embeddings complete...  

<img src="https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/gpt4all_embeddings.png" style='height: 70%; width: 70%;'>

7. Click `New chat` on left menu. Ensure you select the files from the `Local Docs` panel on the right side  
  
    Enter your prompt and click `Send`
```
what passwords are used?
```
> [!TIP]
> [Chat](https://docs.gpt4all.io/gpt4all_desktop/chats.html)

Sample chat response  
![chat](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/gpt4all_chat.png)

> [!IMPORTANT]  
> Always verify the accuracy of the results  
> GTP4All has an option that allows you to view the source of the files in the Chat response

### Troubleshooting
#### Embedding taking too long
Uploading large files will result in an increased duration for the embedding to complete. Alternatively try a smaller subset of docs

#### Load Docs collection shows 0 files and 0 words

<img src="https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/gpt4all_troubleshooting.png" style='height: 70%; width: 70%;'>

Ensure that you have included the correct file extension
![allowed_file_extensions](https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/gpt4all_allowed_file_extensions.png)

> [!TIP]
> [Allowed File Extensions](https://github.com/nomic-ai/gpt4all/wiki/LocalDocs)

#### Chat window closes after selecting model -> try using a smaller model
This usually happens when using models that required more RAM than is available on your system. Try using a smaller model

<img src="https://github.com/AshleyDhevalall/llm-tools-demo/blob/main/docs/gpt4all_ram_required.png" style='height: 70%; width: 70%;'>

### Further reading  
[Quickstart](https://docs.gpt4all.io/gpt4all_desktop/quickstart.html#quickstart)  
[Wiki](https://github.com/nomic-ai/gpt4all/wiki)  
[FAQ](https://docs.gpt4all.io/gpt4all_help/faq.html)  
[Settings](https://docs.gpt4all.io/gpt4all_desktop/settings.html)  
[What Is GPT4All and How Does It Work?](https://www.makeuseof.com/what-is-gpt4all-and-how-does-it-work/)  

## Authors

[Ashley Dhevalall](https://github.com/AshleyDhevalall)

## Acknowledgements

[GTP4All](<https://www.nomic.ai/gpt4all>)  
[AnythingLLM](<https://anythingllm.com/>)  
[Joshua Stenhouse](<https://virtuallysober.com/2017/07/10/working-with-sql-databases-using-powershell/>)  
[Jayric Maning](<https://www.makeuseof.com/what-is-gpt4all-and-how-does-it-work/>)  
[anakin.ai](<https://anakin.ai/blog/anything-llm/>)  
[LM Studio](<https://lmstudio.ai/>)  