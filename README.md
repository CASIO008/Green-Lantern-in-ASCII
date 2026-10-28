# 🟢 Anel do Lanterna Verde — ASCII 3D

> Um anel da Tropa dos Lanternas Verdes renderizado em tempo real em **ASCII 3D**, com projeção física de raios, iluminação dinâmica, rotação cósmica planetária e persistência de dados.

🌐 **Acesse online via GitHub Pages:**  
👉 **[https://casio008.github.io/Green-Lantern-in-ASCII/](https://casio008.github.io/Green-Lantern-in-ASCII/)**

---

## ✨ Funcionalidades

- **💎 Renderização 3D em ASCII Puro**: Modelagem geométrica detalhada do anel, símbolo do Lanterna Verde, aros prateados, veios esmeralda e partículas de energia de força de vontade.
- **💾 Retenção de Memória (`localStorage`)**: A contagem de recargas e o estado da carga são persistidos mesmo ao fechar ou atualizar a página.
- **⚡ Recarga Rápida (Clique)**: Clique no anel ou na tela para recarregar a energia para 100% e somar `+1` na contagem.
- **🔄 Apagar Sequência e Reiniciar (Segurar)**: Segure pressionado no anel por ~1.1s para zerar a contagem (`CONTAGEM = 0`), reiniciar o ciclo de energia e redefinir a sequência.
- **🪐 Movimento Planetário Cósmico**: Rotação orbital ininterrupta inspirada em mecânica celeste, com precessão e nutação suave.
- **🖱️ Parallax e Controle de Câmera**: Mova o mouse sobre a tela para inclinar sutilmente a perspectiva de visão e direcionar a luz.
- **📜 Descarga e Carga Manual**: Use a roda do mouse (*scroll*) para acelerar o tempo de descarga ou testar diferentes níveis de energia.
- **📺 Modo Picture-in-Picture (PiP)**: Pressione a tecla `P` ou dê um duplo clique no anel para destacá-lo em uma janela flutuante sem abas no canto do seu monitor.

---

## 🎮 Controles

| Ação | Como Executar |
| :--- | :--- |
| **Recarregar (100% + Contagem)** | **Clique** no anel ou em qualquer área da tela |
| **Apagar Sequência e Reiniciar** | **Segure pressionado no anel** (~1.1s) até a barra encher |
| **Ajustar Carga** | Gire a **roda do mouse** (*scroll*) para descarregar/carregar |
| **Parallax 3D** | **Mova o cursor** sobre a tela |
| **Janela Flutuante (PiP)** | Pressione a tecla **`P`** ou dê **duplo clique** |

---

## 🚀 Como Ativar o GitHub Pages no Repositório

Para visualizar o projeto publicado diretamente na web:

1. Acesse o repositório no GitHub: [CASIO008/Green-Lantern-in-ASCII](https://github.com/CASIO008/Green-Lantern-in-ASCII)
2. Vá em **Settings** (Configurações) > **Pages** (no menu lateral esquerdo).
3. Na seção **Build and deployment**:
   - **Opção recomendada (GitHub Actions)**: Selecione `GitHub Actions` como *Source*. O fluxo já configurado em `.github/workflows/deploy-pages.yml` fará o deploy automático a cada commit.
   - **Ou (Deploy from a branch)**: Selecione `Deploy from a branch`, escolha a branch `main` e a pasta `/ (root)`, depois clique em **Save**.
4. Aguarde alguns instantes e seu site estará acessível em:  
   🔗 `https://casio008.github.io/Green-Lantern-in-ASCII/`

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Canvas & JavaScript Puro (ES6+)**: Sem frameworks externos ou dependências pesadas.
- **Web API LocalStorage**: Retenção e recuperação de estado no navegador do usuário.
- **CSS3 Responsivo (`vmin`)**: Ajuste automático perfeito para celulares, monitores ultrawide ou janelas compactas.
- **Google Fonts (JetBrains Mono)**: Tipografia monospace de alta legibilidade para caracteres ASCII.

---

*“No dia mais claro, na noite mais densa, o mal sucumbirá ante a minha presença!”* 🟢
