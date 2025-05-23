## Olá Github! 👋

- 🐍 Dev Python e Red Teamer
- 🔭 Atualmente trabalhando com Machine Learning e Automação
- 🤖 Apaixonado em criar bots/agentes autônomos, seja pra data mining ou automatizar games
- ⚡ Robótica, Eletrônica e Hardware Hacking
- 😎 Adepto fiel à filosofia Open Source, pwn everyone, hack everything

## Github Stats
<a href="https://github.com/luizmlo/luizmlo">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=luizmlo&hide=html,jupyter%20notebook&theme=tokyonight&langs_count=3" />
</a>

<a href="https://github.com/luizmlo/a3_botnet">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=luizmlo&repo=a3_botnet&theme=tokyonight" />
</a>

<a href="https://github.com/luizmlo/easylstm">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=luizmlo&repo=easylstm&theme=tokyonight" />
</a>


## Tecnologias e Ferramentas
![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=ubuntu&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Editor-Visual%20Studio%20Code-informational?style=flat&logo=visualstudiocode&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=javascript&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Code-C%2B%2b-informational?style=flat&logo=cplusplus&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Tools-Tensorflow-informational?style=flat&logo=tensorflow&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Tools-Pandas-informational?style=flat&logo=pandas&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Tools-Matplotlib-informational?style=flat&logo=plotly&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Tools-MongoDB-informational?style=flat&logo=mongodb&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Shell-Bash-informational?style=flat&logo=gnu-bash&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Shell-Powershell-informational?style=flat&logo=powershell&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Sec-Metasploit-informational?style=flat&logo=monster&logoColor=white&color=6700cd)
![](https://img.shields.io/badge/Sec-Burp%20Suite-informational?style=flat&logo=webpack&logoColor=white&color=6700cd)

# Portfolio WIP
- [Desenvolvimento](#Desenvolvimento)
  - [XYO Coin Bot](#xyocoin)
  - [Smart Tron](#smarttron)
  - [EasyLSTM](#EasyLSTM)
- [Segurança](#Segurança)
  - [Botnet](#a3_botnet)
  - [CTF's](#ctfs)

<a name="Desenvolvimento"></a>
## Desenvolvimento
<a name="xyocoin"></a>
   ### XYO Mining Bot
   - #### Este projeto é um Bot usando Computer Vision e Automação de Android, feito em Python;
   - #### O XYO Coin é um aplicativo de celular em que você consegue "minerar" a criptomoeda XYO (ERC-20) vendendo dados de geolocalização e sensores, onde a ideia principal é sair andando ou dirigindo por aí enquanto você recebe suas recompensas pela geomineração. Caso você queira receber as recompensas sem se locomover, é necessária a solução de captchas em forma de minigames;
   - #### Neste projeto foram utilizadas ferramentas como OpenCV, Scrcpy, MongoDB e Google Tesseract;
   ![Demo](https://i.imgur.com/2yWwiml.gif)
   ![Integração e Analytics com MongoDB Atlas](https://i.imgur.com/BZh7173.png)
 
 <a name="smarttron"></a>
   #
   ### Smart Tron
   - #### Este foi um projeto desenvolvido para um cliente pela plataforma Fiverr;
   - #### O Smart Tron é uma aplicação GUI multiplataforma (Windows, OSX e Linux) desenvolvida com Python e usando ferramentas como Pandas, KivyMD, TA-Lib e Websockets;
   - #### O projeto é um robô de operações na corretora de valores [IqOption](https://iqoption.com/), onde são usadas diferentes maneiras para analisar dados de mercado e tentar prever seus possíveis movimentos no futuro, operando no mercado Forex, Ações, CFD's e Criptomoedas;
   - #### Este projeto teve também integração com Cloud, incluindo um dashboard em tempo real de Analytics, plataformas de gerenciamento de clientes e otimização;
   - #### O app foi vendido online como Infoproduto, foi necessário um sistema de criação e validação de licenças em nuvem;(https://github.com/dashingsoft/pyarmor)
   ![Tela de Login](https://i.imgur.com/cl0nXR7.png)
   ![Analytics](https://i.imgur.com/fdb1i8m.png)

 <a name="EasyLSTM"></a>
  #
  ### [EasyLSTM](https://github.com/luizmlo/easylstm)
  - #### Esta é uma biblioteca em Python desenvolvida para facilitar a criação e uso de Redes Neurais do tipo LSTM;
  - #### Devido ao funcionamento interno de redes LSTM, são necessários pré processamentos nos dados que podem dificultar seu uso para iniciantes;
  - #### Com esse projeto, é possível ir do import ao uso efetivo do Modelo em menos de 10 linhas de código;
  - #### A descrição, instruções para uso e exemplos podem ser encontrados em Inglês [aqui](https://github.com/luizmlo/easylstm);
  ## 7 Linhas de código, desde o import até a previsão de valores futuros
  ```python
  from easy_lstm import EasyLSTM
  import pandas
  dataset = pandas.read_csv('./path_to_dataset.csv')
  dataset['y'] = dataset['feature'].shift(-1, axis=0)[:-1] #Turning a time series into a supervised learning problem
  model, X_train, y_train, X_test, y_test = EasyLSTM(data=dataset, n_steps=4).do_magic()
  model.fit(X_train, y_train, epochs=20)
  predictions = model.predict(X_test)
  ```
  ![Demo](https://i.imgur.com/ollIvqY.png)

<a name="Segurança"></a>
## Segurança
<a name="a3_botnet"></a>
  ### [Websockets Botnet](https://github.com/luizmlo/a3_botnet)
   - #### Botnet web incluindo servidor de C2 e agentes, feita com python e js para um trabalho da faculdade;

