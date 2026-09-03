# TCC 2026 — [Transtornos Neurodivergentes]
**LTP3 + QP3 · CEMIC 2026 · Prof. Rafael Martins Alves**

---

## 👥 Integrantes

| Nome completo | GitHub | Turma |
|--------------|--------|-------|
| (Caroline Alves da Mota) | @carolinnealvesdamota-cell | 3C |
| (Luiz Eduardo de Toledo Aleixo) | @luiztaleixo-lab | 3C |
| (nome 3) | @username | 3A |

**Tema:** (Plataforma Web para ajudar pessoas neurodivergentes)
**Tecnologia:** Python + Flask + SQLite

---

## 🎯 O que o sistema faz

(Plataforma Digital para para auxiliar pessoas com Transtornos Neurodivergentes )

---

## 🔄 Como o grupo trabalha toda semana

1. **Segunda** — cada integrante abre Issues da semana (use o template "Tarefa Semanal")
2. **Durante a semana** — trabalham e fazem commits
3. **Sexta** — o grupo abre 1 Pull Request linkando as Issues concluídas
4. **Push** — métricas de participação aparecem automaticamente no Actions

---

## 📁 Estrutura do projeto

```neuroguia/
├── app.py                      # Servidor Flask, rotas, segurança e eventos SocketIO
├── models.py                   # Modelos de banco de dados (User, ForumRoom, ForumMessage, PrivateMessage)
├── chatbot.py                  # Base de conhecimento e lógica do Chatbot (13 tópicos)
├── requirements.txt            # Dependências Python
├── static/
│   ├── css/
│   │   └── style.css           # Folha de estilos editorial (sem emojis)
│   ├── js/
│   │   ├── chat.js             # Comunicação SocketIO do fórum e chat privado
│   │   ├── chatbot.js          # Controle interativo com delay de digitação
│   │   └── main.js             # Filtro dinâmico do catálogo clínico
│   └── data/
│       └── conditions.json     # Base clínica das 10 condições
├── templates/
│   ├── base.html               # Layout base com aviso educativo fixo
│   ├── index.html              # Catálogo clínico
│   ├── forum.html              # Fórum de discussões
│   ├── private_chat.html       # Janela de chat privado 1:1
│   ├── search.html             # Busca de usuários
│   ├── profile.html            # Edição de perfil
│   ├── user_profile.html       # Visualização pública de perfis
│   ├── auth.html               # Login e cadastro
│   └── chatbot.html            # Interface do assistente interativo
└── graphify-out/               # Grafo de conhecimento gerado pelo Graphify
    ├── graph.json              # Grafo em formato JSON
    ├── graph.html              # Visualizador interativo do grafo
    ├── GRAPH_REPORT.md         # Relatório analítico de arquitetura
    └── obsidian/               # Notas integradas para Obsidian
```

---

## ⚡ Comandos rápidos

```bash
# Clonar o repositório
git clone <URL>

# Rodar o projeto
pip install -r requirements.txt
python src/app.py

# Rodar os testes
pytest tests/ -v
```
