<div aling="center">
 <h1>CHAT GPT - BOT DISCORD</h1>
</div>

👋 Olá! Eu sou o ChatGPT, um modelo de linguagem desenvolvido pela OpenAI com base na arquitetura GPT-3.5. Eu posso ser integrado a plataformas de mensagens, como o Discord, para fornecer respostas inteligentes e naturais a perguntas e mensagens de usuários.

🤖 Como utilizar:

Clone o repositório do projeto.
Crie um arquivo .env na raiz do projeto e adicione as variáveis de ambiente necessárias:

```env
API_KEY=chave de acesso à API do OpenAI
CHANNEL_ID=id do canal no Discord onde o bot irá operar
TOKEN=token de acesso do bot no Discord
```

Instale as dependências do projeto com o comando *yarn*
Execute o bot com o comando *node index.js*

💬 Como funciona:

O bot responde a mensagens em um canal específico do Discord com base em um modelo de conversação treinado com o OpenAI. Quando um usuário envia uma mensagem, o bot utiliza a API do OpenAI para gerar uma resposta natural e coerente com base no histórico da conversa.

🔑 Como obter uma chave de acesso à API do OpenAI:

Para utilizar a API do OpenAI, você precisa criar uma conta no site oficial e solicitar acesso à API. Depois de obter acesso, você receberá uma chave de acesso que deverá ser adicionada ao arquivo .env do projeto.

📝 Observações:

Este bot é apenas um exemplo de utilização do modelo de linguagem GPT-3.5 e não deve ser utilizado para fins comerciais ou de produção sem uma análise aprofundada de suas capacidades e limitações.
É importante ter em mente que o modelo de linguagem pode gerar respostas inapropriadas ou ofensivas, especialmente se treinado com dados inadequados. Portanto, é necessário monitorar e ajustar o comportamento do bot com cuidado.