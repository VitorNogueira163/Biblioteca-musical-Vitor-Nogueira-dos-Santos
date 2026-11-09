# Sistema-musical-Vitor-Nogueira-dos-Santos
# Sistema Musical 🎵

Um reprodutor e organizador musical web projetado para ser **totalmente responsivo, personalizável e leve**. O projeto foi desenvolvido utilizando tecnologias web padrão (HTML5 e CSS3), focando em uma experiência de usuário fluida tanto em computadores quanto em dispositivos móveis.

---

## 🚀 Recursos Principais

* **Design Responsivo & Portabilidade:** Interface adaptável com suporte total para celulares, tablets e desktops (Mobile-First).
* **Navegação Dinâmica:** Links estruturados para navegação entre álbuns, playlists e artistas.
* **Interface Limpa:** Layout moderno focado na usabilidade e na acessibilidade dos controles musicais.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica do player, listas de reprodução e seções de mídia.
* **CSS3:** Estilização avançada, Flexbox/Grid para alinhamento e Media Queries para adaptação móvel.

---

## 🎨 Configuração de Cores (Paleta)

O projeto utiliza **Variáveis CSS (Custom Properties)** no arquivo de estilos para gerenciar a paleta de cores de forma centralizada. Você pode alterar a identidade visual do sistema modificando o bloco `:root`:

```css
:root {
  --cor-background: #121212;   /* Fundo principal (Estilo Dark Mode) */
  --cor-primary: #1DB954;      /* Cor de destaque (botões, links ativos) */
  --cor-surface: #181818;      /* Cards e elementos secundários */
  --cor-text: #FFFFFF;         /* Texto principal */
  --cor-text-muted: #B3B3B3;   /* Textos secundários e legendas */
}
```

---

## 📱 Portabilidade para Celulares

Para garantir que o sistema funcione perfeitamente em telas menores, o projeto conta com:
1. **Meta Tag Viewport:** Configurada no HTML para ajustar a escala automaticamente em telas mobile.
2. **Media Queries:** Regras CSS específicas aplicadas para reorganizar menus e otimizar o espaço do player em celulares.

```html
<!-- Incluído no <head> para garantir a portabilidade -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## 📂 Como Executar o Projeto

1. Faça o clone deste repositório:
   ```bash
   git clone https://github.com
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd seu-repositorio
   ```
3. Abra o arquivo `index.html` diretamente em qualquer navegador web.
