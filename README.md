# 🔐 Login Dev-Club

<div align="center">

Um formulário de login moderno e responsivo com design glassmorphism elegante e efeitos visuais impressionantes.

![Login Dev-Club](/screenshot.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

</div>

---

## ✨ Características

- 🎨 **Design Glassmorphism** - Interface moderna com efeito vidro translúcido
- ⭐ **Efeito de Estrelas** - Fundo dinâmico com estrelas CSS puras
- 📱 **Responsivo** - Se adapta perfeitamente a qualquer tamanho de tela
- 🎭 **Ícones Font Awesome** - Ícones elegantes no formulário
- 🎯 **Formulário Completo** - Campos de validação, "Lembrar-me" e recuperação de senha
- ⚡ **Performance** - Carregamento rápido, sem dependências externas pesadas

---

## 🚀 Início Rápido

### Pré-requisitos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet (para carregar fontes e ícones)

### Instalação

1. **Clone o repositório:**

```bash
git clone https://github.com/seu-usuario/login-dev-club.git
cd login-dev-club
```

2. **Abra o arquivo:**

```bash
# Simplesmente abra o arquivo no seu navegador
open index.html
```

Ou use um servidor local:

```bash
# Python 3
python -m http.server 8000

# Node.js com http-server
npx http-server
```

3. **Acesse no navegador:**

```
http://localhost:8000
```

---

## 📁 Estrutura do Projeto

```
login-dev-club/
├── index.html          # Arquivo principal HTML
├── style.css          # Estilos CSS
└── README.md          # Documentação
```

---

## 🎨 Paleta de Cores

| Cor                | Hex                         | Uso                 |
| ------------------ | --------------------------- | ------------------- |
| Roxo Profundo      | `#2a1b6b`                   | Fundo principal     |
| Roxo Médio         | `#5c44a2`                   | Gradiente           |
| Branco Translúcido | `rgba(255, 255, 255, 0.15)` | Fundo do formulário |
| Branco             | `#fff`                      | Texto               |
| Violeta            | `#7c0c9e`                   | Accent color        |

---

## 🎯 Funcionalidades

### Campos do Formulário

- ✅ **Campo de Usuário** - Com ícone de usuário
- 🔒 **Campo de Senha** - Com ícone de cadeado
- ☑️ **Lembrar-me** - Checkbox para manter sessão
- 🔑 **Esqueceu a Senha** - Link para recuperação
- 📝 **Registrar-se** - Link para criar nova conta

### Validação

- ✔️ Campos obrigatórios (required)
- 📧 Compatível com validação HTML5

---

## 💻 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos modernos (Flexbox, Grid, Gradientes, Backdrop Filter)
- **Font Awesome 6.4.0** - Ícones escaláveis
- **Google Fonts (Poppins)** - Tipografia moderna

---

## 🔧 Customização

### Alterar Cores

Edite o arquivo `style.css`:

```css
/* Fundo do corpo */
background: linear-gradient(to bottom, #2a1b6b, #5c44a2);

/* Cor dos ícones */
accent-color: #7c0c9e;
```

### Adicionar Mais Campos

Adicione no `index.html`:

```html
<div class="caixa-formulario">
  <input type="email" placeholder="Email" required />
  <i class="fas fa-envelope"></i>
</div>
```

### Integrar com Backend

Modifique o formulário em `index.html`:

```html
<form action="https://seu-servidor.com/login" method="POST">
  <!-- campos aqui -->
</form>
```

---

## 🌐 Demonstração

Abra [clique aqui](./index.html) para ver a demonstração ao vivo.

---

## 📸 Preview

![Login Dev-Club Preview](screenshot.png)

_Interface limpa, moderna e intuitiva com design glassmorphism_

---

## 🎓 Conceitos Utilizados

- **Glassmorphism** - Design moderno com efeito vidro
- **CSS Backdrop Filter** - Blur e transparência
- **Flexbox** - Layout responsivo
- **Gradientes CSS** - Efeitos visuais
- **Position Absolute/Fixed** - Posicionamento de elementos
- **Pseudo-elementos CSS** - Efeitos adicionais

---

## 🐛 Conhecidos

- Compatibilidade com navegadores mais antigos (IE não suportado)
- Backdrop filter pode ter performance limitada em dispositivos antigos

---

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um **Fork** do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um **Pull Request**

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

**Dev-Club**

- 🌐 Website: [dev-club.com](https://dev-club.com)
- 📧 Email: contato@dev-club.com
- 🐙 GitHub: [@dev-club](https://github.com/dev-club)

---

## 📞 Suporte

Se tiver dúvidas ou encontrar problemas:

- 📝 Abra uma [Issue](../../issues)
- 💬 Nos contate via email
- 📚 Consulte a [Documentação](./README.md)

---

## 🙏 Agradecimentos

- [Font Awesome](https://fontawesome.com/) - Ícones
- [Google Fonts](https://fonts.google.com/) - Tipografia Poppins

---

<div align="center">

⭐ Se gostou, deixe uma estrela! ⭐

![GitHub Stars](https://img.shields.io/github/stars/seu-usuario/login-dev-club?style=social)
![GitHub Forks](https://img.shields.io/github/forks/seu-usuario/login-dev-club?style=social)

</div>
