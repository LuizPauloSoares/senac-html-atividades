[🇧🇷 Português](README.md) | [🇺🇸 English](README.en.md)

# 🏫 Senac HTML Atividades

Atividades de HTML e CSS do curso do Senac: uma página inicial e um sistema web de 5 telas.

## 📌 Status
- **Atividade 1:** ✅ concluída
- **Atividade 2:** 🚧 em desenvolvimento (layout e validações prontos; falta JavaScript)

## 🛠️ Tecnologias utilizadas
- HTML5 (formulários, tabelas, meta tags)
- CSS3 (Flexbox, `position: sticky`, `@media`)

## 📂 Estrutura do projeto
```
senac-html-atividades/
├── atividade1/
│   ├── atividade1.html
│   ├── estilo.css
│   ├── livro.png
│   └── senac.png
├── atividade2/
│   ├── home.html
│   ├── logar.html
│   ├── cadastro.html
│   ├── consulta.html
│   ├── calculadora.html
│   └── estilo.css
└── screenshots/
```

## ⚙️ Como funciona

### Atividade 1 — Primeira Página
- Mostra o logo do Senac, o título `SENAC` e um menu horizontal (Cursos Livres, Cursos Técnico, Graduação, Pós Graduação).
- O `estilo.css` pinta o título de azul e o menu de laranja/negrito.
- As meta tags (description, keywords, author, language) ajudam em SEO e acessibilidade.
- O `meta refresh` redireciona para `https://sp.senac.br` após 5 segundos.

### Atividade 2 — Sistema Senac
- **Home:** menu com links para todas as telas.
- **Login:** e-mail e senha (8 a 20 caracteres).
- **Cadastro:** nome (só letras), e-mail e senha forte (maiúscula, minúscula, número e símbolo) com confirmação, validados pelo próprio HTML.
- **Consulta:** tabela de usuários cadastrados (dados de exemplo, senha mascarada).
- **Calculadora:** visual pronto; os botões ainda não funcionam.
- Campos com borda verde (válido) ou vermelha (inválido) ao digitar; layout responsivo até 600px.

## 🗃️ Estrutura de dados
Tabela da tela Consulta (estática): `ID | Nome | Email | Senha | Ações`.

## 📋 Pré-requisitos
- Navegador atual (Chrome, Edge, Firefox)
- Git (para clonar) e VS Code com Live Server (opcionais)

## 🚀 Instalação e configuração
1. Clone o projeto:
   ```bash
   git clone https://github.com/LuizPauloSoares/senac-html-atividades.git
   cd senac-html-atividades
   ```
2. Abra no navegador:
   - Atividade 1: `atividade1/atividade1.html`
   - Atividade 2: `atividade2/home.html`
3. ⚠️ Na atividade 1, a página redireciona para o site do Senac em 5 segundos. Para evitar, comente a linha `meta http-equiv="refresh"`.

## 🖼️ Exemplos de uso / Screenshots

### Atividade 1
![Atividade 1](screenshots/atividade1.png)

### Atividade 2
**Home**
![Home](screenshots/home.png)

**Login**
![Login](screenshots/login.png)

**Cadastro**
![Cadastro](screenshots/cadastro.png)

**Consulta**
![Consulta](screenshots/consulta.png)

**Calculadora**
![Calculadora](screenshots/calculadora.png)

## 🗺️ Roadmap / Próximos passos
- [ ] JavaScript da calculadora (operações, `C` e `<`)
- [ ] Validar "confirme sua senha" (igual à senha)
- [ ] Salvar cadastros (localStorage) e listar na Consulta
- [ ] Lógica real do login
- [ ] Padronizar o menu entre as páginas
- [ ] Corrigir `authot` para `author` na atividade 1
- [ ] Mover estilos inline da atividade 1 para o CSS

## 📄 Licença
MIT

## 👤 Autor / Créditos
**Luiz Paulo** — curso do Senac

- 📧 Email: _seu-email_
- 📸 Instagram: _@seu-usuario_
- 💼 LinkedIn: _link-do-perfil_
- 🐙 GitHub: [LuizPauloSoares](https://github.com/LuizPauloSoares)
