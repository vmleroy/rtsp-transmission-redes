**OBS: Os comandos apresentados foram executados dentro da pasta ```src```**

# Passo 1
Compilar todas as pastas do projeto com os seguintes comandos:

javac ./RTPpacket/RTPpacket.java
javac ./VideoStream/VideoStream.java
javac ./Client/Client.java
javac ./Server/Server.java

* Apos a compilacao de todas as classes, comecaremos a abrir o servidor e o client

# Passo 2
Abrir o servidor

java ./Server/Server.java [ porta_do_servidor ]
Exemplo:
java ./Server/Server.java 3000

# Passo 3
Abrir o cliente que tera a visao do video

java ./Client/Client.java [ ip_ou_nome_do_servidor ] [ porta_do_servidor ] [ arquivo_de_video ]
Exemplo:
java ./Client/Client.java localhost 3000 ../media/movie.Mjpeg 

* Com o cliente e servidor carregado, teremos a GUI do cliente aberta e podemos enviar requisicoes RTSP para o servidor a partir dos botes

# Passo 4

1. Cliente manda a requisicao SETUP. Esse comando e usado para configurar a sessao e os parametros de transporte
2. Cliente manda PLAY. Esse comando inicia a transmissao
3. Cliente pode mandar o PAUSE. Esse comando serve para pausar a transmissao
4. Cliente manda TEARDOWN. Esse comando finaliza a sessao e fecha a conexao tanto do servidor quanto do cliente



