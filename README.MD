# 🎹 Piano Virtual

Este é um projeto de **Piano Virtual** que permite ao usuário tocar teclas do piano virtualmente, utilizando o mouse ou o teclado. O piano simula sons reais e possui funcionalidades de controle de volume e visibilidade das teclas.

## 🚀 Funcionalidades

- Tocar notas musicais ao clicar nas teclas do piano ou ao pressionar as teclas correspondentes no teclado.
- Ajuste de volume através de um controle deslizante.
- Alternar a exibição dos nomes das teclas (ativar/desativar).

## 🖥️ Tecnologias Utilizadas

- **HTML5**: Estrutura do piano e seus controles.
- **CSS3**: Estilização e layout responsivo.
- **JavaScript**: Lógica do jogo, interação com o DOM e reprodução de áudio.

## 📦 Instalação e Uso

### 1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/piano-virtual.git
```

### 2. Navegue até a pasta do projeto

### 3. Abra o arquivo index.html no seu navegador:
- Você pode simplesmente abrir o arquivo HTML diretamente no navegador ou utilizar uma extensão como o Live Server no VSCode para rodar localmente.

## 🔧 Como Funciona: 
- Cada tecla do piano tem uma correspondência com uma tecla do teclado (ex: 'A', 'S', 'D', etc.).
- Quando uma tecla é pressionada ou clicada, a função playTune() é chamada, tocando o áudio correspondente à tecla.
- O controle de volume permite ajustar o volume do áudio em tempo real.
- O checkbox "Teclas" permite ocultar ou exibir os nomes das teclas no piano.