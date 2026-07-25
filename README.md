# Plant Buddy 🪴

Um aplicativo simples para desktop inspirado nos brinquedos Tamagotchi, onde você precisa manter uma pequena planta virtual viva. Este projeto foi desenvolvido com HTML, CSS, JavaScript e Electron.

<div align="center">
    <video src="https://github.com/user-attachments/assets/3bcede11-a05b-49d8-86f0-567ec83137b5" controls width="100%"/>
    
</div>





## Funcionalidades
- **Mecânica de nível de água** 💧  
Uma barra de água visível que diminui ao longo do tempo.
- **Humores dinâmicos** 😄  
A planta muda entre quatro estados de acordo com seu nível de água: **Relaxando**, **Okay**, **Com sede** e **Murcha**.
- **Lembrete de cuidados** 🔔  
Uma pequena mensagem abaixo da planta informa como ela está se sentindo.

## Como Jogar
O aplicativo começa do zero sempre que é aberto. Sua planta inicia com **100% de água**, e a barra vai diminuindo gradualmente com o passar do tempo.

- Clique em **"Water"** para aumentar a barra em **+25%**. Você poderá regar novamente após **10 segundos**.
- Observe o humor da planta. Ele muda conforme o nível de água e avisa quando ela está com sede.
- Se a barra chegar a **0%**, a planta murcha e a sessão termina. Clique em **"Restart"** para começar novamente.

## Como Executar
Quer testar o aplicativo? Siga os passos abaixo:

### 1. Clone o repositório
```bash
git clone https://github.com/Peziiim/Plant-buddy.git
cd plant-buddy
```

### 2. Instale as dependências
Certifique-se de ter o **Node.js** instalado em sua máquina e execute:

```bash
npm install
```

Isso instalará o Electron e todas as dependências necessárias para executar o aplicativo.

### 3. Execute o aplicativo
```bash
npm start
```

O Plant Buddy será aberto como um aplicativo para desktop utilizando Electron.

## Feedback
Se encontrar algo confuso ou tiver sugestões de melhorias, fique à vontade para abrir uma *issue* ou enviar um *pull request*!

---

#### Código desenvolvido seguindo as instruções do curso **Codedex**! 🚀
