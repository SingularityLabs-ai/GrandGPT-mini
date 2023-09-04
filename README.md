<p align="center">
    <img src="./src/assets/icon.png" width="150">
</p>

<h1 align="center">MultiGPT</h1>

<div align="center">

### MultiGPT is a multi-chatbot

[![author][author-image]][author-url]
[![license][license-image]][license-url]
[![release][release-image]][release-url]
[![last commit][last-commit-image]][last-commit-url]

English &nbsp;&nbsp;|&nbsp;&nbsp; [Indonesia](README_IN.md) &nbsp;&nbsp;|&nbsp;&nbsp; [简体中文](README_ZH-CN.md) &nbsp;&nbsp;|&nbsp;&nbsp; [繁體中文](README_ZH-TW.md) &nbsp;&nbsp;|&nbsp;&nbsp; [日本語](README_JA.md)

##

### Install

<a href="https://chrome.google.com/webstore/detail/"><img src="https://user-images.githubusercontent.com/64502893/231991498-8df6dd63-727c-41d0-916f-c90c15127de3.png" width="200" alt="Get MultiGPT for Chromium"></a>
<a href="https://microsoftedge.microsoft.com/addons/detail/"><img src="https://user-images.githubusercontent.com/64502893/231991158-1b54f831-2fdc-43b6-bf9a-f894000e5aa8.png" width="160" alt="Get MultiGPT for Microsoft Edge"></a>

##

[Screenshot](#-screenshot) &nbsp;&nbsp;|&nbsp;&nbsp; [Features](#-features) &nbsp;&nbsp;|&nbsp;&nbsp; [Supported Bots](#-supported-bots) &nbsp;&nbsp;|&nbsp;&nbsp; [Manual Installation](#-manual-installation) &nbsp;&nbsp;|&nbsp;&nbsp; [Build from Source](#-build-from-source) &nbsp;&nbsp;|&nbsp;&nbsp; [Changelog](#-changelog)

[author-image]: https://img.shields.io/badge/author-wong2-blue.svg
[author-url]: https://github.com/wong2
[license-image]: https://img.shields.io/github/license/ishandutta2007/MultiGPT?color=blue
[license-url]: https://github.com/SingularityLabs-ai/MultiGPT/blob/main/LICENSE
[release-image]: https://img.shields.io/github/v/release/ishandutta2007/MultiGPT?color=blue
[release-url]: https://github.com/SingularityLabs-ai/MultiGPT/releases/latest
[last-commit-image]: https://img.shields.io/github/last-commit/ishandutta2007/MultiGPT?label=last%20commit
[last-commit-url]: https://github.com/SingularityLabs-ai/MultiGPT/commits

</div>

## Todo

- cohere https://dashboard.cohere.com/playground/generate
- Small_Talk https://developer.kore.ai/docs/bots/bot-builder-tool/small-talk/#Import_Small_Talk
- perplexity.ai
- openrouter.ai
- forefront.ai domain specific bots
- chatgpt and dall e via beta.theb.ai
- deepai.org
- sdk.vercel.ai (have multiple bots like poe)
- Midjourney alternative editor.fusionbrain.ai
- chatgpt via https://chat.acytoo.com
- https://apps.apple.com/app/id6446304087

### GPT4
- GPT4 via liaobots.com
- GPT4 via https://gpt4h.ninvfeng.xyz/
- gpt4 xunika

### Bing(GPT4)
- Bing via hf4all-bingo.hf.space

### GPT3.5
- LAION AI H2oGPT https://gpt-gm.h2o.ai/conversation/
- gptgod
- easy chat openai https://chat9.fastgpt.me/
- GPT3.5 via chat.chatgptdemo.net
- chatgpt via ai.ls
- chatgpt via https://e.aifree.site/
- chatgpt via https://h.aifree.site/
- GPT3.5 via https://chats.free2gpt.xyz/
- GPT3 via https://pizzagpt.it/
- GPT3 via powerchat.top


- slack bots CLAUDE_BOT_ID = ['U05J5M9E7MZ','U05J74AT9DL','U05J79DQC0N']

- 
  



##

## 📷 Screenshot

![Screenshot](screenshots/light_1280x800.png?raw=true)

![Screenshot (Dark Mode)](screenshots/dark_1280x800.png?raw=true)

## ✨ Features

- 🤖 Use different chatbots in one app, currently supporting ChatGPT, new Bing Chat, Google Bard, Claude (via Poe), Alpaca, Vicuna, ChatGLM, and will integrate more in the future
- 💬 Chat with multiple chatbots at the same time, making it easy to compare their answers
- 🚀 Support ChatGPT API and GPT-4 Browsing
- 🔍 Shortcut to quickly activate the app anywhere in the browser
- 🎨 Markdown and code highlight support
- 📚 Prompt Library for custom prompts and community prompts
- 💾 Conversation history saved locally
- 📥 Export and Import all your data
- 🔗 Share conversation to markdown
- 🌙 Dark mode

## 🤖 Supported Bots

* ChatGPT (via Webapp/API/Azure/Poe)
* Bing Chat
* Google Bard
* Claude (via Poe)
* iFlytek Spark
* ChatGLM
* Alpaca
* Vicuna
* ...


## 🔧 Manual Installation

- Download grandgpt.zip from [Releases](https://github.com/SingularityLabs-ai/GrandGPT/releases)
- Unzip the file
- In Chrome/Edge go to the extensions page (chrome://extensions or edge://extensions)
- Enable Developer Mode
- Drag the unzipped folder anywhere on the page to import it (do not delete the folder afterward)

## 🔨 Build from Source

- Clone the source code
- `yarn install`
- `yarn build`
- Load `dist` folder to browser by following steps in _Manual Installation_

### Credit

This project is inspired by https://github.com/ZohaibAhmed/ChatGPT-Google , https://github.com/wong2/chatgpt-google-extension
