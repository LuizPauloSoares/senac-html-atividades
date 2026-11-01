[🇧🇷 Português](README.md) | [🇺🇸 English](README.en.md)

# 🏫 Senac HTML Activities

HTML and CSS activities from the Senac course: a landing page and a 5-screen web system.

## 📌 Status
- **Activity 1:** ✅ completed
- **Activity 2:** 🚧 in progress (layout and validations done; JavaScript missing)

## 🛠️ Technologies
- HTML5 (forms, tables, meta tags)
- CSS3 (Flexbox, `position: sticky`, `@media`)

## 📂 Project structure
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

## ⚙️ How it works

### Activity 1 — First Page
- Shows the Senac logo, the `SENAC` title and a horizontal menu (Free Courses, Technical Courses, Undergraduate, Postgraduate).
- `estilo.css` colors the title blue and the menu orange/bold.
- Meta tags (description, keywords, author, language) help with SEO and accessibility.
- The `meta refresh` redirects to `https://sp.senac.br` after 5 seconds.

### Activity 2 — Senac System
- **Home:** menu linking to every screen.
- **Login:** email and password (8 to 20 characters).
- **Sign up:** name (letters only), email and strong password (upper, lower, number and symbol) with confirmation, validated by HTML itself.
- **Users list:** table of registered users (sample data, masked password).
- **Calculator:** visual is ready; buttons don't work yet.
- Fields get a green (valid) or red (invalid) border while typing; responsive layout up to 600px.

## 🗃️ Data structure
Users list table (static): `ID | Name | Email | Password | Actions`.

## 📋 Prerequisites
- A modern browser (Chrome, Edge, Firefox)
- Git (to clone) and VS Code with Live Server (optional)

## 🚀 Installation and setup
1. Clone the project:
   ```bash
   git clone https://github.com/LuizPauloSoares/senac-html-atividades.git
   cd senac-html-atividades
   ```
2. Open in your browser:
   - Activity 1: `atividade1/atividade1.html`
   - Activity 2: `atividade2/home.html`
3. ⚠️ In activity 1, the page redirects to the Senac website after 5 seconds. To avoid it, comment out the `meta http-equiv="refresh"` line.

## 🖼️ Usage examples / Screenshots

### Activity 1
![Activity 1](screenshots/atividade1.png)

### Activity 2
**Home**
![Home](screenshots/home.png)

**Login**
![Login](screenshots/login.png)

**Sign up**
![Sign up](screenshots/cadastro.png)

**Users list**
![Users list](screenshots/consulta.png)

**Calculator**
![Calculator](screenshots/calculadora.png)

## 🗺️ Roadmap / Next steps
- [ ] Calculator JavaScript (operations, `C` and `<`)
- [ ] Validate "confirm password" (must match password)
- [ ] Save sign-ups (localStorage) and list them in the Users page
- [ ] Real login logic
- [ ] Standardize the menu across pages
- [ ] Fix `authot` to `author` in activity 1
- [ ] Move inline styles of activity 1 to the CSS

## 📄 License
MIT

## 👤 Author / Credits
**Luiz Paulo** — Senac course

- 📧 Email: _your-email_
- 📸 Instagram: _@your-user_
- 💼 LinkedIn: _profile-link_
- 🐙 GitHub: [LuizPauloSoares](https://github.com/LuizPauloSoares)
