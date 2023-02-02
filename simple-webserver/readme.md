**Simple Web Server [Com Hot Reload]**
*Esse é um exemplo simples de servidor web criado com a linguagem de programação Rust. O código faz uso da biblioteca **[Rocket](https://rocket.rs/)** para gerenciar as rotas e requisições.*

 **Instalação**
*Instale a versão mais recente do [Rust](https://www.rust-lang.org/learn/get-started).
Clone [esse repositório](https://github.com/CarlosDevlpr/learning-rustlang) para o seu computador:* 

    git clone https://github.com/CarlosDevlpr/learning-rustlang

*Entre na pasta do projeto:* 

    cd learning-rustlang/simple-webserver

*Coloque o rust em modo nightly*

    rustup default nightly

*Execute o build e compile o servidor*

    cargo build

 **Habilitando Hot Reload**
*Instale o cargo-watch (que monitora todas os arquivos, detecta mudanças e faz o Hot Reload)*

    cargo install cargo-watch

*Configure o cargo watch no projeto*

    cargo watch

*Execute o comando para iniciar o servidor já com Hot Reload.*

    cargo watch --exec run 

 **Uso**
*Acesse http://localhost:8000/ no seu navegador para ver a mensagem "Hello World" exibida.*

**Personalização**
*Você pode personalizar as rotas e a resposta do servidor editando o arquivo main.rs.*