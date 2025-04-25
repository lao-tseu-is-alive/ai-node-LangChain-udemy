# ai-node-LangChain-udemy

Code from [Alex Dan Udemy Course](https://www.udemy.com/user/alexhorea/) : Generative AI for NodeJs using OpenAI, LangChain - TypeScript


## install NodeJs with nvm
Go to [nvm GitHub](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating) and follow instructions to install nvm :

    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

then 

    nvm ls-remote
    nvm install v22.15.0
    nvm use v22.15.0


## install vs code
You can either go to [vscode website](https://code.visualstudio.com/docs/setup/linux) to download and install vscode on your computer.

Or you can use the online version at : [vscode.dev](https://vscode.dev/)

you can edit your own github projet directly like this [https://vscode.dev/github/lao-tseu-is-alive/ai-node-LangChain-udemy](https://vscode.dev/github/lao-tseu-is-alive/ai-node-LangChain-udemy)

## OpenAI API
You must connect to [OpenAI AOI platform](https://platform.openai.com/login). Then generate an API secret KEy and store in in .env file in the root of this project. This file should contain something like this

        OPENAI_API_KEY=whatever-the-content-of-the-secret-key-generated-for-you

+ [OpenAI models pricing](https://openai.com/api/pricing/)


## Embeddings

    + OpenAI [Vector embeddings](https://platform.openai.com/docs/guides/embeddings/embedding-models)
    + [huggingface Embedding Leaderboard](https://huggingface.co/spaces/mteb/leaderboard)