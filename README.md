# 🎯 Jogo da Forca em Java - POO

Este repositório contém a implementação de um **Jogo da Forca** utilizando a linguagem Java, com foco nos conceitos de **Programação Orientada a Objetos (POO)**. O projeto foi desenvolvido para rodar em ambiente **console** e representa todos os elementos clássicos do jogo, desde a definição da palavra oculta até a representação gráfica simplificada da forca.

## 🎓 Objetivo Educacional

Este projeto tem como principal objetivo aplicar de forma prática os pilares da **POO** em Java:

- **Abstração**: Representação das entidades do jogo de forma genérica e reutilizável.
- **Encapsulamento**: Organização e proteção do estado interno dos objetos.
- **Herança e Polimorfismo**: Uso conforme aplicável à lógica do jogo.
- **Responsabilidade única**: Separação clara entre controle do jogo, entrada do usuário e exibição.

## 🧩 Funcionalidades

- ✅ Menu inicial com opções para jogar ou sair
- ✅ Seleção aleatória da palavra secreta
- ✅ Validação de letras já digitadas
- ✅ Feedback visual simplificado da forca no console
- ✅ Contagem regressiva de tentativas restantes
- ✅ Mensagens personalizadas para vitória ou derrota
- ✅ Estrutura modular baseada em boas práticas de OOP

## 💻 Tecnologias e Ferramentas

- **Java (amazon corretto 21)**
- **Paradigma: Orientado a Objetos**
- **Ambiente: Console (CLI)**

## 📁 Estrutura do Projeto

hangman/  
└── src/  
└── main/  
└── java/  
└── br/  
└── com/  
└── dio/  
└── hangman/  
├── Main.java  
├── exception/  
│ ├── GameIsFinishedException.java  
│ └── LetterAlreadyInputedException.java  
└── model/  
├── ForcaGame.java  
├── PalavraSecreta.java  
└── BancoDePalavras.java  


## ▶️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/JogoForcaJava.git
   cd JogoForcaJava

2. Compile e execute o programa via terminal:  
   javac -d bin src/**/*.java  
   java -cp bin Main  

(Observação: Não é necessário nenhum framework ou biblioteca externa.)

## 🧠 Conceitos Trabalhados

- Estrutura de repetição e decisão
- Manipulação de strings e coleções
- Entrada e saída no console
- Modularização e separação de responsabilidades
- Design limpo e manutenção de código
