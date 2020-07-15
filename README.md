# IRC-Redes
Internet Relay Chat implementado em C++ para a disciplina de Redes de Computadores. 

## Autores
- Igor Takeo Ambo de Melo / Número USP: 10830054
- Mateus Ferreira Gomes / Número USP: 10734773
- Guilherme Targon Marques Barcellos / Número USP: 10724181

## Comandos para compilar e rodar no Terminal Linux.
- git clone https://github.com/igortakeo/Redes.git

- cd IRC-Redes/ (Para entrar na pasta que contém os arquivos).

- make all (Para compilar todos os arquivos .cpp).

- make runs (Para rodar o servidor).

- make runc (Para rodar o cliente).

- make clean (Para excluir da pasta os arquivos executáveis).

> **OBS: Abra outro terminal para rodar o cliente caso esteja na mesma máquina em que o servidor foi iniciado**.

## Como usar
Rodando o servidor será pedido uma porta para a conexão, se a conexão for bem sucedida será mostrada a mensagem "Open Server", se não será mostrada "Bind Failed".
Caso queira fazer port-forwarding o cliente irá pedir o ip e a porta para a conexão. Já se quiser fazer uma conexão localhost use o **ip: 127.0.0.1** e a mesma porta usada para estabelecer a conexão do servidor.

Após a conexão com o canal de comunicação será aberto outro terminal, para mostrar as mensagens dos clientes que estão conectados ao canal.

Todos as mensagens devem ser escritas no terminal do cliente, o terminal do canal mencionado anteriormente só irá mostrar as mensagens.

Todos os canais seguem a mesma regra para o nome **#(Número)** (Por exemplo: #0 e #55).
