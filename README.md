# DSList Game Backend

DSList Game Backend é um projeto para listagem de jogos RPG e Aventura, permitindo a visualização detalhada de informações como título, ano, gênero, plataforma e muito mais.

## Funcionalidades

- Lista jogos por:
  - ID
  - Título
  - Nome do jogo
  - Ano
  - Gênero
  - Plataforma
  - Pontuação
  - URL da imagem
  - Descrição longa
  - Descrição curta
 
## Modelo de Domínio DSList
![Captura de tela 2025-01-07 010528](https://github.com/user-attachments/assets/b514ee1e-f6f0-4dfc-9d3d-d5114f7ace66)


## Tecnologias Utilizadas

- **Linguagem:** Java
- **Framework:** Spring Initializr
- **Banco de Dados:** ORM H2 e PostgreSQL
- **Containerização:** Docker
- **Ambiente de Desenvolvimento:** Spring Tools Suite 4 (STS4)

## Como Usar

### Pré-requisitos

- Java 17+
- Docker
- Spring Tools Suite 4 (opcional, mas recomendado)

### Passos para Configuração

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/dslist-game-backend.git
   ```

2. Configure o banco de dados no arquivo `application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/dslist
   spring.datasource.username=seu_usuario
   spring.datasource.password=sua_senha
   ```

3. Execute o projeto com o Spring Tools Suite 4 ou pelo terminal:
   ```bash
   ./mvnw spring-boot:run
   ```

4. Para rodar com Docker, utilize o comando:
   ```bash
   docker-compose up
   ```

### Endpoints Principais

- `GET /games` - Retorna todos os jogos
- `GET /games/{id}` - Retorna detalhes de um jogo específico
- `POST /games` - Adiciona um novo jogo
- `PUT /games/{id}` - Atualiza informações de um jogo
- `DELETE /games/{id}` - Remove um jogo

## Contribuições

Contribuições são bem-vindas! Siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma nova branch:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça commit das suas alterações:
   ```bash
   git commit -m "Adiciona nova feature"
   ```
4. Envie para o repositório remoto:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Desenvolvido com ❤️ por Willanms Ramos

