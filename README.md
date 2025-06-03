<h1 align="center" style="font-weight: bold;">goCalculator</h1>

<p align="center">
  <a href="#tech">Tecnologias</a> • 
  <a href="#about">Sobre</a> •
  <a href="#started">Começando</a> • 
  <a href="#contribute">Contribuir</a>
</p>

<p align="center">
    <b>Este é um projeto simples de calculadora desenvolvido em Go para operações básicas.</b>
</p>

<h2 id="tech">Tecnologias</h2>

- [Go](https://go.dev/doc/) - Uma linguagem de programação de código aberto que facilita a construção de software simples, confiável e eficiente.
- [fmt](https://pkg.go.dev/fmt) - Pacote Go para formatação de I/O.
- [strconv](https://pkg.go.dev/strconv) - Pacote Go para conversões de string para tipos numéricos e vice-versa.
- [strings](https://pkg.go.dev/strings) - Pacote Go que implementa funções úteis para manipulação de strings.

<h2 id="about">Sobre</h2>

<p>Este projeto é uma calculadora simples desenvolvida em <b>Go</b>, capaz de realizar operações aritméticas básicas: adição, subtração, multiplicação e divisão. Foi criada para demonstrar o uso fundamental da linguagem Go em um aplicativo de console interativo.</p>

<h3>Funcionalidades</h3>

- **Adição** (`+`)
- **Subtração** (`-`)
- **Multiplicação** (`*`)
- **Divisão** (`/`)

<h3>Observações</h3>

- No momento, a calculadora suporte apenas operações com dois números inteiros.
- A entrada deve seguir estritamente o formato `número1operadornúmero2` (`2+2`).
- A divisão por zero resultará em uma mensagem de erro.
- Operadores inválidos farão com que o programa entre em `panic`.

<h2 id="started">Começando</h2>

1. **Certifique-se de ter o Go instalado:** Se você ainda não tem, pode baixá-lo em [go.dev/dl](https://go.dev/dl/).

2. **Clone este repositório:**

```bash
git clone https://github.com/vdonoladev/goCalculator.git
```

2. **Navegue até o diretório do projeto:**

```bash
cd goCalculator
```

3. **Execute o script:**

```bash
go run main.go
```

<h2 id="contribute">Contribuir</h2>

1. `git clone https://github.com/vdonoladev/goCalculator.git`
2. `git checkout -b feature/NAME-OF-FEATURE`
3. Siga os **Commit Patterns**
4. Abra um **Pull Request** explicando o problema resolvido ou o recurso feito, se houver, anexe a captura de tela das modificações visuais e aguarde a revisão!

<h3>Documentações que podem ajudar</h3>

- [📝 How to create a Pull Request](https://www.atlassian.com/br/git/tutorials/making-a-pull-request)

- [💾 Commit pattern](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)
