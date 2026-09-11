# Hortêncio AI 🤖

Um assistente pessoal inteligente com integração Google, suporte multiplataforma (Android/Web) e arquitetura modular.

## 🎯 Objetivo

Hortêncio AI é um assistente pessoal que:
- Entende pedidos em linguagem natural
- Responde perguntas de forma clara
- Pesquisa informações atualizadas na internet
- Integra-se com serviços Google (Gmail, Drive, Calendar, etc.)
- Analisa arquivos e imagens
- Executa operações complexas de forma segura

## ✨ Recursos Principais

- ✅ Interface de chat responsiva (Web + Android)
- ✅ Suporte para múltiplos idiomas (português, inglês, etc.)
- ✅ Integração OAuth 2.0 com Google
- ✅ Sistema de ferramentas modular
- ✅ Análise de arquivos e imagens
- ✅ Histórico de conversas
- ✅ Modo claro e escuro
- ✅ Segurança em primeiro lugar

## 📁 Estrutura do Projeto

```
hortencion-ai/
├── backend/                 # API Backend (Python/FastAPI)
├── frontend-web/           # Interface Web (React)
├── frontend-android/       # App Android (Kotlin)
├── docs/                   # Documentação
└── README.md
```

## 🔧 Tecnologias

- **Backend**: Python 3.9+, FastAPI, PostgreSQL
- **Frontend Web**: React 18+, TypeScript, TailwindCSS
- **Mobile**: Kotlin, Jetpack Compose
- **Autenticação**: OAuth 2.0
- **APIs**: Google Cloud APIs
- **Banco de dados**: PostgreSQL com SQLAlchemy

## 📋 Pré-requisitos

- Python 3.9+
- Node.js 16+
- Android Studio (para desenvolvimento mobile)
- Conta Google Cloud com APIs habilitadas
- PostgreSQL 12+

## 🚀 Quick Start

### 1. Clone o repositório

```bash
git clone https://github.com/hortenciodelfimpedro-beep/hortencion-ai.git
cd hortencion-ai
```

### 2. Configuração Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env
# Configure as variáveis de ambiente
python -m uvicorn main:app --reload
```

### 3. Configuração Frontend Web

```bash
cd frontend-web
npm install
cp .env.example .env.local
# Configure as variáveis de ambiente
npm start
```

### 4. Configuração Android

```bash
cd frontend-android
# Abra em Android Studio
# Configure o arquivo local.properties
# Build e execute
```

## 📖 Documentação

- [INSTALLATION.md](docs/INSTALLATION.md) - Guia detalhado de instalação
- [GOOGLE_SETUP.md](docs/GOOGLE_SETUP.md) - Configuração Google Cloud
- [API_DOCUMENTATION.md](docs/API_DOCUMENTATION.md) - Documentação da API
- [ARCHITECTURE.md](docs/ARCHITECTURE.md) - Arquitetura do sistema

## 🔐 Segurança

- ✅ Sem armazenamento de senhas
- ✅ OAuth 2.0 para autenticação
- ✅ Tokens armazenados com segurança
- ✅ Princípio de menor privilégio
- ✅ Confirmação para ações críticas
- ✅ Registros de auditoria

## 🛠️ Sistema de Ferramentas

O Hortêncio AI utiliza um sistema modular de ferramentas:

- **SearchTool** - Pesquisar na internet
- **GmailTool** - Acessar emails
- **DriveTool** - Gerenciar arquivos
- **CalendarTool** - Gerenciar eventos
- **MapsPlacesTool** - Localização e lugares
- **YouTubeSearchTool** - Buscar vídeos
- **FileAnalyzerTool** - Analisar documentos
- **CodeGeneratorTool** - Gerar código
- **CalculatorTool** - Cálculos complexos

## 🧪 Testes

```bash
# Backend
cd backend
pytest

# Frontend Web
cd frontend-web
npm test
```

## 📝 Variáveis de Ambiente

Ver `.env.example` em cada diretório para exemplos de configuração.

**IMPORTANTE**: Nunca coloque credenciais reais no repositório!

## 🤝 Contribuindo

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

MIT License - veja LICENSE para detalhes

## 👤 Autor

**Hortêncio** - Seu Assistente AI Pessoal

---

**Status do Projeto**: 🚧 Em Desenvolvimento

**Última Atualização**: 2026
