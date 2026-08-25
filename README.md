# TCC 2026 — [Transtornos Neurodivergentes]
**LTP3 + QP3 · CEMIC 2026 · Prof. Rafael Martins Alves**

---

## 👥 Integrantes

| Nome completo | GitHub | Turma |
|--------------|--------|-------|
| (Caroline Alves da Mota)
| (Luiz Eduardo de Toledo Aleixo) | @luiztaleixo-lab | 3C |
| (nome 3) | @username | 3A |

**Tema:** (Plataforma Web para ajudar pessoas neurodivergentes)
**Tecnologia:** Python + Flask + SQLite

---

## 🎯 O que o sistema faz

(Descreva em 2-3 frases o problema que o sistema resolve e para quem)

---

## 🔄 Como o grupo trabalha toda semana

1. **Segunda** — cada integrante abre Issues da semana (use o template "Tarefa Semanal")
2. **Durante a semana** — trabalham e fazem commits
3. **Sexta** — o grupo abre 1 Pull Request linkando as Issues concluídas
4. **Push** — métricas de participação aparecem automaticamente no Actions

---

## 📁 Estrutura do projeto

```
neuroapp-js/
│
├── server.js
├── package.json
├── README.md
├── .gitignore
├── .env.example
│
├── src/
│   ├── app.js
│   ├── config.js
│   ├── db.js
│   │
│   ├── data/
│   │   ├── educationTopics.js
│   │   └── forumCategoriesSeed.js
│   │
│   ├── middleware/
│   │   └── auth.js
│   │
│   ├── routes/
│   │   ├── auth.js
│   │   ├── chat.js
│   │   ├── forum.js
│   │   ├── grafo.js
│   │   ├── main.js
│   │   └── perfil.js
│   │
│   ├── sockets/
│   │   └── chatSocket.js
│   │
│   ├── utils/
│   │   └── avatar.js
│   │
│   └── views/
│       ├── layout.ejs
│       ├── index.ejs
│       ├── educacao.ejs
│       ├── neuroguia.ejs
│       ├── grafo.ejs
│       ├── 404.ejs
│       │
│       ├── auth/
│       │   ├── login.ejs
│       │   └── register.ejs
│       │
│       ├── forum/
│       │   ├── index.ejs
│       │   ├── novo_post.ejs
│       │   ├── categoria.ejs
│       │   └── post.ejs
│       │
│       ├── chat/
│       │   └── index.ejs
│       │
│       └── perfil/
│           ├── editar.ejs
│           ├── buscar.ejs
│           └── ver.ejs
│
└── public/
    ├── css/
    │   └── style.css
    │
    ├── js/
    │   ├── neuroguia.js
    │   ├── grafo.js
    │   └── chat.js
    │
    └── img/
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
