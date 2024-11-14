### DOC:

https://aider.chat/docs/usage/voice.html

### SETUP

python -m pip install -U aider-chat
export OPENAI_API_KEY=sk...

### SET LLM MODELS

aider --4o
aider --model o1-mini
aider --list-models openai/

export GROQ_API_KEY=
aider --model groq/llama3-70b-8192
aider --list-models groq/

export OLLAMA_API_BASE=http://127.0.0.1:11434
aider --model ollama/llama3:70b

### RUN

aider

### TO RUN BROWSER

aider --browser

### CHAT MODES

/chat-mode code
/chat-mode architect
/chat-mode ask
/chat-mode help

## VOICE MODE

/voice

### COMMANDS

/add <file> - Adiciona um arquivo à sessão para edição.
/drop <file> - Remove um arquivo da sessão para liberar espaço de contexto.
/diff - Mostra as alterações feitas desde o último comando.
/run <comando> - Executa comandos de shell e adiciona a saída ao chat.
/undo - Reverte a última modificação realizada pela IA.
/commit - Comita alterações manuais feitas no arquivo fora do Aider.
/ask - Faz perguntas ou solicita análises sem alterar o código.
/architect - Inicia uma discussão sobre a arquitetura do código antes de fazer alterações.
/help - Exibe ajuda para comandos disponíveis no Aider​

aider
.
