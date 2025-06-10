# 🚀 API REST - CRUD de Usuários

Este projeto é uma API REST desenvolvida com **Java + Spring Boot**, que permite realizar operações básicas de **Cadastro, Leitura, Atualização e Remoção (CRUD)** de usuários.

🔗 [Repositório no GitHub](https://github.com/EddieNine/API-crud-usuarios)

![Badge](https://img.shields.io/badge/status-finalizado-green)
![GitHub repo size](https://img.shields.io/github/repo-size/EddieNine/API-crud-usuarios)
![GitHub last commit](https://img.shields.io/github/last-commit/EddieNine/API-crud-usuarios)

---

## 📌 Funcionalidades

- ✅ Criar usuários
- ✅ Listar todos os usuários
- ✅ Atualizar dados de um usuário
- ✅ Deletar um usuário por ID

---

## 🛠️ Tecnologias Utilizadas

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database (em memória)
- Postman (para testes)

---

## 🗂️ Estrutura do Projeto

```
src/
└── main/
    └── java/
        └── com/
            └── seuprojeto/
                ├── controller/
                │   └── UsuarioController.java
                ├── model/
                │   └── Usuario.java
                ├── repository/
                │   └── UsuarioRepository.java
                └── Application.java
```

---

## ⚙️ Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/EddieNine/API-crud-usuarios.git
cd API-crud-usuarios
```

### 2. Execute a aplicação

Se estiver usando IntelliJ ou VS Code com suporte a Spring Boot, apenas rode a `Application.java`.

Ou via terminal:

```bash
./mvnw spring-boot:run
```

### 3. Acesse o H2 Database (opcional)

- URL: `http://localhost:8081/h2-console`
- JDBC URL: `jdbc:h2:mem:testdb`
- Usuário: `sa`
- Senha: *(em branco)*

---

## 🧪 Testes com o Postman

- `GET /usuarios` – Lista todos os usuários
- `POST /usuarios` – Cria um novo usuário
```json
{
  "nome": "Edcarlos",
  "email": "edcarlos@email.com"
}
```

- `PUT /usuarios/{id}` – Atualiza um usuário existente
- `DELETE /usuarios/{id}` – Remove um usuário

---

## ✅ Status do Projeto

✔️ Projeto concluído e pronto para ser usado como base para aplicações REST mais complexas.

---

## 📷 Imagem da API em execução

![api-demo](https://user-images.githubusercontent.com/00000000/00000000-00000000-0000-0000-000000000000.png)

---

## 📄 Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🙋‍♂️ Autor

Feito com dedicação por **Edcarlos Cruz**  
📇 [Meu LinkedIn](https://www.linkedin.com/in/edcarloscruz/)
