# Instruções para Executar o Projeto Angular na Sua Máquina

Este guia fornecerá instruções passo a passo para clonar, configurar e executar o projeto Angular em sua máquina local. O projeto consiste em um frontend e um backend, e você encontrará instruções separadas para cada parte.

## Clonando o Repositório

1. Abra o terminal em seu computador.
2. Navegue até o diretório onde deseja armazenar o projeto.
3. Execute o seguinte comando para clonar o repositório:

# git clone URL_DO_REPOSITORIO

(Substitua `URL_DO_REPOSITORIO` pela URL real do repositório do projeto.)

## Configurando e Executando o Frontend

1. Abra o terminal e navegue até a pasta do frontend do projeto:

# cd caminho/para/pasta/frontend

2. Instale as dependências do projeto usando o npm (ou yarn, se preferir):

# npm install

3. Após a conclusão da instalação, execute o seguinte comando para iniciar o servidor de desenvolvimento:

# ng serve

4. Aguarde até que o processo seja concluído e observe o terminal. Deve aparecer uma mensagem indicando que o servidor está em execução.
5. Abra seu navegador da web e digite o seguinte endereço na barra de endereços:

# http://localhost:4200

Isso o levará à interface do frontend da aplicação.

## Configurando e Executando o Backend

1. Abra um novo terminal (mantendo o terminal do frontend aberto).
2. Navegue até a pasta do backend do projeto:

# cd caminho/para/pasta/backend

3. Instale as dependências do backend usando o npm:

# npm install

4. Uma vez concluída a instalação, execute o seguinte comando para iniciar o servidor backend:

# node ace serve

5. Você verá informações no terminal indicando que o servidor backend está em execução. Não é necessário abrir o link exibido.

## Conclusão

Após seguir essas etapas, seu projeto Angular estará em pleno funcionamento. O frontend estará acessível em `http://localhost:4200`, enquanto o backend será executado em um endereço indicado no terminal. Agora você pode explorar e desfrutar da aplicação!

