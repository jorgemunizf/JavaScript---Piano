# 🎹 Simulador de Piano em JavaScript

<img width="800" height="493" alt="image" src="https://github.com/user-attachments/assets/9b9f0d6f-a612-4ac4-a02e-5ef44d50900a" />


Um projeto interativo desenvolvido com **HTML**, **CSS** e **JavaScript** que simula um **piano virtual** no navegador.  
Cada tecla corresponde a um som real, permitindo tocar músicas diretamente no teclado do computador ou clicando nas teclas virtuais na tela.

---

## 📁 Estrutura do Projeto

```
JavaScript---Piano/
├── src/
│   ├── scripts/
│   │   └── engine.js          # Lógica principal do piano (eventos e sons)
│   ├── styles/
│   │   ├── main.css           # Estilização principal do layout
│   │   └── reset.css          # Reset de estilos padrão do navegador
│   └── tunes/
│       ├── a.wav              # Arquivos de áudio correspondentes a cada tecla
│       ├── d.wav
│       ├── e.wav
│       ├── f.wav
│       ├── g.wav
│       ├── h.wav
│       ├── j.wav
│       ├── k.wav
│       ├── l.wav
│       ├── o.wav
│       ├── p.wav
│       ├── s.wav
│       ├── t.wav
│       ├── u.wav
│       ├── w.wav
│       ├── y.wav
│       └── ;.wav
├── index.html                 # Página principal do projeto
└── README.md                  # Documentação do projeto
```

---

## 🚀 Funcionalidades

- 🎵 Simulação realista de sons de piano (notas `.wav`)
- ⌨️ Suporte para toques via **teclado físico**
- 🖱️ Interação via **cliques do mouse** nas teclas virtuais
- 💡 Feedback visual ao pressionar cada tecla
- 📱 Layout responsivo, adaptável a diferentes telas

---

## 🧠 Como Funciona

O arquivo `engine.js` é responsável por:
1. Mapear as teclas do teclado físico (ex: A, S, D, F...) aos arquivos `.wav` correspondentes.
2. Capturar eventos de clique e teclado.
3. Tocar o som associado e aplicar o efeito visual de tecla pressionada.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** → Estrutura do piano e layout da página  
- **CSS3** → Estilização, responsividade e animações  
- **JavaScript (ES6)** → Lógica do piano e controle dos eventos  
- **Áudios `.wav`** → Sons reais das notas musicais

---

## ▶️ Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/JavaScript---Piano.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd JavaScript---Piano
   ```

3. Abra o arquivo `index.html` em seu navegador:
   ```bash
   firefox index.html
   ```
   ou  
   simplesmente **arraste o arquivo** para uma aba do navegador.

---

## 💡 Sugestões de Melhoria

- Adicionar opção de **gravar e reproduzir** melodias.  
- Criar **modo de aprendizado** com músicas guiadas.  
- Implementar **variações de instrumentos** (sintetizador, órgão, etc).  
- Criar **interface com animações visuais** mais imersivas.  

---

## 🧑‍💻 Autor

**Desenvolvido por [Jorge Muniz](https://github.com/jorgemunizf)**  
Projeto feito como exercício prático para aprimorar conhecimentos em **JavaScript, DOM e manipulação de áudio.**

---

🗓️ *Gerado automaticamente em 15/10/2025, 16:14:25*  
📂 *Estrutura detectada via FileTree Pro Extension*
