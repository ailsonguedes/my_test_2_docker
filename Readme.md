# My Test 2 (Docker)

Esse programa foi desenvolvido como um segundo teste de utilização do Docker.


## 🔧 Ferramentas Utilizadas

-   Docker:  plataforma de contêineres que permite que os desenvolvedores empacotem seus aplicativos em contêineres portáteis que podem ser executados em qualquer ambiente. Isso torna a implantação e a execução de aplicativos muito mais fáceis e eficientes, pois as dependências e o ambiente de execução são encapsulados no contêiner.
-   Pytest:  framework de testes para a linguaguem python.
## ⚙️ Como Funciona

-   Ao rodar a aplicação o usuário deverá receber a mensagem a mensagem do teste feito pelo pytest: "test_hello.py .     [100%]".

## 💻 Como executar o código

- Instalar Python 
- Abra o prompt de comando
- caminhe até a pasta raiz do programa e contém os arquivo "test_hello.py", "requirements.txt" e "Dockerfile".
- Você precisa inicialmente criar uma imagem Docker a partir do Dockerfile. Utilize o seguinte comando "docker build -t my_project .".
- Para executar o arquivo  (**docker run my_project**)

