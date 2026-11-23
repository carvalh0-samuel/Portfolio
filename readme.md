# 💻 Portfólio Pessoal | Samuel.dev

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

Portfólio pessoal desenvolvido para apresentar minha trajetória acadêmica em **Ciência da Computação**, experiência prática em **Suporte de TI**, certificações técnicas e projetos desenvolvidos nas áreas de **Desenvolvimento Web, Mobile e IoT**.

🔗 **Acesse o projeto online:** [https://carvalh0-samuel.github.io/portfolio/](https://carvalh0-samuel.github.io/portfolio/) *(atualize com o link final após ativar o GitHub Pages)*

---

## ✨ Funcionalidades

- **Tema Claro e Escuro (Dark Mode):** Alternância dinâmica entre temas com detecção automática da preferência do sistema operacional e persistência via `localStorage`.
- **Design Totalmente Responsivo:** Layout adaptado para dispositivos móveis, tablets e desktops, incluindo menu de navegação mobile.
- **Download Direto do Currículo:** Botão de acesso rápido na seção inicial para baixar o currículo atualizado em PDF.
- **Vitrine Interativa de Projetos:**
  - Filtro dinâmico por categoria (**Todos**, **Mobile**, **Web** e **IoT / Hardware**).
  - Modal detalhado com descrição completa, tecnologias utilizadas e link direto para o repositório no GitHub.
  - Ilustrações vetoriais (`SVG`) como *fallback* automático caso alguma imagem não seja carregada.
- **Formulário de Contato Funcional:** Integração assíncrona via **FormSubmit** (sem necessidade de back-end), redirecionamento automático para o Gmail Web em ambientes locais, cópia rápida de e-mail com notificação *toast* e botão direto para o **WhatsApp**.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico**
- **Tailwind CSS** (via CDN para estilização responsiva e utilitária)
- **JavaScript (ES6+)** (manipulação do DOM, filtros dinâmicos, modal, controle de tema e requisições `fetch`)
- **Lucide Icons & SVGs Customizados**
- **Google Fonts** (`Inter`)
- **FormSubmit API** (envio de mensagens do formulário de contato)

---

## 🚀 Projetos em Destaque

1. **Medication Schedule App** *(Mobile)* — Aplicativo em React Native e Expo para auxiliar pacientes na adesão terapêutica, com controle de posologia, barra de progresso diário, persistência local e notificações.
2. **Olympus - Projeto Web Responsivo** *(Web)* — Site responsivo desenvolvido de forma colaborativa com HTML5, CSS3, JavaScript, MySQL e versionamento via Git/GitHub.
3. **Irrigação Automática com ESP32** *(IoT / Hardware)* — Protótipo emulado no Wokwi com C++ para monitoramento de temperatura e umidade, acionamento manual/automático e alertas em tempo real via WhatsApp.

---

## 📂 Estrutura de Pastas

```text
portfolio/
├── index.html                                # Página principal, estilos e scripts
├── README.md                                 # Documentação do repositório
└── assets/                                   # Arquivos estáticos do projeto
    ├── Curriculo - Samuel Carvalho.pdf       # Currículo disponível para download
    ├── icone.png                             # Capa do Medication Schedule App
    ├── 01.png                                # Capa do projeto Olympus
    └── ESP32.png                             # Capa do projeto de Irrigação com ESP32
```

---

## ⚙️ Como Executar Localmente

Como o projeto não depende de etapas de *build* ou servidores complexos, basta seguir os passos abaixo:

1. Clone este repositório:
   ```bash
   git clone https://github.com/carvalh0-samuel/portfolio.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd portfolio
   ```
3. Abra o arquivo `index.html` diretamente no seu navegador ou utilize a extensão **Live Server** no VS Code.

---

## 📬 Contato

- **LinkedIn:** [linkedin.com/in/carvalho-samuel](https://linkedin.com/in/carvalho-samuel)
- **GitHub:** [github.com/carvalh0-samuel](https://github.com/carvalh0-samuel)
- **E-mail:** samuelcarvalho1976@gmail.com
- **Localização:** Distrito Federal, Brasil

---

Desenvolvido por **Samuel Marinho de Carvalho**.