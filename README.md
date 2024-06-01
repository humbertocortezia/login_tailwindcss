# Projeto de Tela de Login

Este é um projeto de uma tela de login simples utilizando Tailwind CSS para estilização.

## Descrição

Este projeto é uma implementação básica de uma tela de login para demonstração e aprendizado de como utilizar Tailwind CSS. O layout é responsivo e segue boas práticas de design moderno.

## Tecnologias Utilizadas

- HTML5
- Tailwind CSS

Adapte conforme necessário para refletir os detalhes específicos e a configuração do seu projeto.

## Pré-requisitos

Para visualizar e editar este projeto, você precisará de um navegador moderno e um editor de texto. Recomendo usar VSCode ou qualquer outro editor de sua preferência.

## Como Usar

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/login_tailwindcss.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd login_tailwindcss
   ```
3. Dentro da pasta execute npm run dev utilize o liveServer ou o servidor do node para visualizar e abra o arquivo `index.html` no seu navegador para visualizar a tela de login.

## Exemplo de Imagem

![Exemplo de Tela de Login](./tela-de-login.png)

## Estrutura da Tela de Login

### HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./src/output.css" />
    <title>Login - sistema</title>
  </head>
  <body class="bg-slate-900">
    <main
      class="w-full min-h-screen flex flex-col md:flex-row items-center justify-center mx-auto"
    >
      <section
        class="w-full flex-1 flex flex-col justify-center items-center p-4"
      >
        <div
          class="w-full max-w-xl flex justify-center items-center flex-col gap-4"
        >
          <img src="img/login.png" alt="Logo users" class="w-36" />
          <h1 class="text-white text-4xl font-bold mb-7">Login</h1>
          <input
            class="w-full rounded-xl p-2"
            type="text"
            placeholder="Email"
          />
          <input
            class="w-full rounded-xl p-2"
            type="password"
            placeholder="Senha"
          />

          <div class="w-full flex items-center justify-between">
            <div class="flex items-center gap-2">
              <input type="checkbox" />
              <label class="text-white font-bold">Lembrar senha</label>
            </div>
            <a href="#" class="text-white">Esqueceu sua senha?</a>
          </div>
          <button
            class="w-full p-2 rounded-xl outline-none bg-indigo-600 text-white hover:bg-indigo-400 duration-300"
          >
            Acessar
          </button>

          <p class="text-white">
            Não possui uma conta?
            <a href="#" class="text-blue-500 hover:to-blue-300">Clique aqui</a>
          </p>
        </div>
      </section>
      <section
        class="hidden md:flex w-full flex-1 justify-center items-center p-4 bg-slate-800 h-screen"
      >
        <div
          class="w-full max-w-x1 flex justify-center items-center flex-col gap-4"
        >
          <img src="img/server.png" alt="Logo users" class="w-36" />
          <h1 class="text-white text-4xl -7 ">Seu sistema em boas mãos</h1>
        </div>
      </section>
    </main>
  </body>
</html>
```
