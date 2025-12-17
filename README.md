# 🚢 Game of Ship in C

![C++](https://img.shields.io/badge/C++-Game-blue)
![Allegro](https://img.shields.io/badge/Allegro-Library-red)
![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-green)
![License](https://img.shields.io/badge/license-MIT-green)

Esse é o **meu primeiro jogo feito com a biblioteca Allegro em C/C++**, onde o jogador controla um navio em um cenário básico. O jogo foi desenvolvido como um projeto experimental e pode **conter bugs**, já que foi feito quando eu ainda estava aprendendo. ([GitHub][1])

Projeto criado com foco **educacional e de portfólio**, demonstrando:

* Uso da biblioteca **Allegro** para manipular gráficos e áudio
* Estruturação de um **loop de jogo**
* **Eventos de teclado**
* Renderização simples de sprites e objetos
* Arquivos de recursos (imagens, sons)

## 🎮 Demonstração

> O jogo funciona como um app nativo compilado, rodando janelas com gráficos e sons usando a biblioteca Allegro. ([GitHub][1])

📌 **Objetivo principal:**
Controlar o seu navio, navegar pelo cenário e interagir com o ambiente.

*(Se quiser, posso te ajudar a adicionar GIF ou vídeo do gameplay aqui 👾)*

## 🕹️ Como Jogar

* 🎮 Use as teclas direcionais para mover o navio
* 🚀 Explore o cenário
* 🔊 O jogo pode incluir sons e efeitos conforme os recursos adicionados

⚠️ *Instruções completas de controles podem estar no arquivo `INTRUÇÔES DO JOGO.txt` incluído no repositório.* ([GitHub][1])

## 📌 Funcionalidades

* 🎨 Janela gráfica aberta com **Allegro**
* 🛳️ Navegação do navio pelo cenário
* 🎵 Suporte a **músicas e efeitos sonoros**
* 📁 Recursos organizados em pastas (`imagens`, `musicas`, `som`) ([GitHub][1])
* 🐞 Feito como projeto de aprendizagem (pode conter bugs) ([GitHub][1])

## 🏗️ Arquitetura do Projeto

Fluxo lógico do jogo:

```
main.cpp (inicialização)
↓
Setup Allegro
↓
Loop principal do jogo
    * Captura eventos
    * Atualiza estado
    * Renderiza objetos
↓
Finaliza e fecha
```

O projeto também inclui:

* Arquivos binários compilados (como `.exe`) ([GitHub][1])
* Makefile para compilação no Windows (`Makefile.win`) ([GitHub][1])

## ⚙️ Tecnologias Utilizadas

* **C++ / C**
* **Allegro** (biblioteca de jogos)
* **Recursos gráficos e sons**
* Compilador compatível com projetos Allegro

## 🚀 Como Compilar e Executar

### ⚙️ Requisitos

Antes de tudo, instale a **Allegro** e um compilador C/C++ (como MinGW ou GCC).

### ✔️ Windows com Makefile

1. Abra o terminal na raiz do projeto
2. Execute:

```bash
make -f Makefile.win
```

3. Esse comando deve gerar o executável (`Project1.exe`)
4. Rode:

```bash
./Project1.exe
```

### 🛠️ Manual

Você também pode compilar diretamente:

```bash
g++ main.cpp -o game -lallegro -lallegro_image -lallegro_audio -lallegro_ttf
./game
```

*(A linha de compilação pode variar conforme a sua instalação da Allegro)*

## 🧠 Lógica do Jogo (Resumo)

* O jogo abre uma janela gráfica
* O loop principal:

  * Lê eventos de teclado
  * Atualiza a posição do navio
  * Renderiza os gráficos
  * Reproduz sons conforme necessário
* O foco é **interação em tempo real com o jogador**

## 🚀 Possíveis Evoluções

* 🏁 Sistema de **pontuação**
* 🔥 Adicionar **inimigos e obstáculos**
* 💥 Colisões e física básica
* 📱 Suporte a mais controles (gamepad)
* 📈 Melhorias visuais e sprites atualizados
* 🧪 Remover bugs e refatorar o código
* 💡 Menu de início e tela de Game Over

