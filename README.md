# Este programa implementa um chatbot básico em Python que interage com o usuário através de prompts de texto. O desenvolvimento deste projeto foi impulsionado pelo poder do Google Gemini, potencializado pelos recursos educacionais da Alura e pela expertise da FIAP.
🚀 Recursos
Interação intuitiva via prompts de texto.
Respostas geradas por um chatbot avançado.
Fácil personalização para diferentes casos de uso.
🛠️ Pré-requisitos
Python 3.x
Uma biblioteca ou API de chatbot (substitua chat pelo seu próprio objeto)
👣 Como usar
Instale as dependências: Instale a biblioteca de chatbot que você escolher.
Configure o chatbot: Configure o objeto chat no código para se conectar ao seu chatbot.
Execute o programa: Execute o arquivo Python.
Interaja com o chatbot: Digite um prompt e pressione Enter. O chatbot irá responder ao seu prompt.
Para sair: Digite "fim" e pressione Enter.
💻 Código
prompt = input("Esperando prompt: ")

while prompt != "fim":
  response = chat.send_message(prompt)
  print("Resposta: ", response.text, "\n")
  prompt = input("Esperando prompt: ")
Use code with caution.
Python

🎉 Agradecimentos
Um agradecimento especial ao Google Gemini, Alura e FIAP por fornecerem as ferramentas e o conhecimento para tornar este projeto possível!
