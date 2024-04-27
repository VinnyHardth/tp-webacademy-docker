# Execução

Para executar o projeto localmente, siga estes passos simples:

1. **Clone o repositório:**

   ```bash
   git clone git@github.com:seu-usuário/tp-webacademy-docker.git
    ```
2. **Navegue até a pasta do projeto:**

   ```bash
   cd seu-projeto
   ```

3. **Inicie os containers:**

   ```bash
   docker-compose up -d
   ```
   ou, se preferir ver os logs no terminal:
   ```bash
    docker-compose up
    ```

4. **Acesse a aplicação no navegador:** Uma vez que os containers estejam em execução, você pode acessar a aplicação em seu navegador web através do [http://localhost:8000](http://localhost:8000)

5. **Gerenciador de banco de dados:** Para acessar o gerenciador de banco de dados, basta abrir o seguinte link em seu navegador: [http://localhost:8080](http://localhost:8080). O phpMyAdmin já está configurado para acessar o banco de dados do projeto. 

6. **Exemplos de inputs para o frontend:** estão presente no arquivo `dados-livros-exemplos.txt` na raiz do projeto.