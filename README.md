# 📚 Flash Cards

## ✨ Descrição

O **Flash Cards** é um aplicativo simples e interativo desenvolvido para ajudar na aprendizagem e revisão de palavras de diferentes idiomas. A ideia do aplicativo é que você possa carregar um arquivo CSV com palavras e seus significados, e então revisá-las de forma eficiente, usando cartões que viram automaticamente para mostrar a tradução ou o significado da palavra.

A cada vez que você clica para indicar que já conhece a palavra ou que não sabe, o aplicativo organiza as palavras para que você possa revisar mais facilmente as que precisa aprender.

## 🚀 Funcionalidades

- **Exibição de palavras:** O aplicativo exibe uma palavra na língua que você está aprendendo e, após 3 segundos, ela vira e mostra o significado na sua língua nativa.
- **Marcação de palavras conhecidas:** Você pode marcar uma palavra como "conhecida", e ela não aparecerá novamente no futuro até que você reinicie o processo de revisão.
- **Revisão contínua:** Se você clicar em "não sei", a palavra será mostrada novamente em algum momento para garantir que você tenha tempo suficiente para aprender.

## ⚙️ Como Funciona

1. O aplicativo carrega um arquivo CSV contendo palavras de um idioma e suas traduções.
2. A cada rodada, ele mostra uma palavra em francês (por exemplo), e após 3 segundos, vira a carta mostrando a tradução para o seu idioma nativo.
3. Se você já souber a palavra, pode clicar no botão "já sei" para que ela não apareça novamente.
4. Se você não souber a palavra, pode clicar no botão "não sei" e ela será mostrada novamente em algum momento.

## 🛠️ Como Usar

### 📥 Pré-requisitos

- **Python 3.6+**
- **Bibliotecas Python:** Tkinter, Pandas

### 📋 Passos para executar

1. **Baixar o projeto:**

   Primeiro, faça o download do projeto para o seu computador.

2. **Preparar o arquivo CSV:**

   Crie ou baixe um arquivo CSV com duas colunas: uma contendo as palavras no idioma que você está aprendendo (por exemplo, francês) e outra com a tradução ou significado na sua língua nativa.

   Exemplo de CSV:
   ```
   bonjour, hello
   merci, thank you
   chat, cat
   ```

3. **Instalar as dependências:**

   No terminal, instale as dependências necessárias com o seguinte comando:

   ```bash
   pip install pandas
   ```

4. **Rodar o aplicativo:**

   Execute o arquivo principal para iniciar o aplicativo:

   ```bash
   python app.py
   ```

   Agora você pode começar a revisar as palavras!

---

📚 **Aprenda de forma divertida!** 🌟
