📹 Shorts AI

shorts_ai é um projeto para criar vídeos curtos (Shorts) usando a API do Google com suporte a inteligência artificial para geração/edição automática de conteúdo de vídeo.

🚀 Este README é um template inicial — ajuste as seções conforme as funcionalidades reais do seu projeto.

📌 Visão Geral

O Shorts AI ajuda a automatizar a criação de vídeos curtos — como YouTube Shorts, Reels ou TikTok — a partir de entradas (ex: texto, links ou vídeos longos) utilizando serviços da Google e ferramentas de IA.
Ele pode ser usado para:

Gerar vídeos curtos automaticamente

Aplicar legendas, cortes e transformações

Integrar com APIs do Google (como geração de texto, TTS, etc.)

Automatizar workflows de criação

🔍 Funcionalidades

✅ Geração de vídeos curtos via Google API
✅ Suporte para transformar texto em vídeo
✅ Exportação otimizada para plataformas sociais
✅ Estrutura modular e extensível

(Adicione mais funcionalidades específicas conforme seu projeto evoluir.)

📦 Requisitos

Antes de usar o projeto, verifique se você tem:

Python 3.8+

Conta e credenciais da Google Cloud API

Google Cloud SDK configurado

API de Text-to-Speech ativada

API de geração de vídeo/ML (se aplicável)

ffmpeg instalado (para processamento de vídeo/audio)

🛠️ Instalação

Clone o repositório:

git clone https://github.com/edgarjp3085/shorts_ai.git
cd shorts_ai


Crie um ambiente virtual (recomendado):

python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows


Instale as dependências:

pip install -r requirements.txt

⚙️ Configuração

Configure as credenciais da Google Cloud:

Crie um projeto no Google Cloud Console

Ative as APIs necessárias (TTS, Vision, etc.)

Gere um arquivo credentials.json

Exporte a variável de ambiente:

export GOOGLE_APPLICATION_CREDENTIALS="path/to/credentials.json"


(Windows PowerShell)

$env:GOOGLE_APPLICATION_CREDENTIALS="path\to\credentials.json"

▶️ Uso
🎬 Criar um Short

Execute o script principal:

python main.py --input "<texto-ou-link>" --output shorts_output.mp4


Parâmetros de exemplo:

Flag	Descrição
--input	Texto, URL ou arquivo de origem
--output	Nome do arquivo de vídeo de saída
--mode	Modo de geração (ex: texto → vídeo ou vídeo → short)

(Ajuste os comandos conforme as funções reais do seu código.)

📁 Estrutura do Projeto
shorts_ai/
├── main.py                # Script principal
├── shorts_ai/             # Módulos principais
├── requirements.txt       # Dependências Python
├── README.md              # Este arquivo
└── examples/              # Exemplos de uso

🧪 Exemplos

Exemplo de uso para gerar um short a partir de texto:

python main.py --input "Crie um vídeo curto sobre dicas de produtividade" --output produtividade_short.mp4

🤝 Contribuições

Contribuições são super bem-vindas!
Para propor melhorias:

Faça um fork do repositório

Crie uma branch (git checkout -b feature/nova-funcionalidade)

Commit suas mudanças (git commit -m "descrição")

Envie um pull request
