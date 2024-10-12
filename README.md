# Event City TDD
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

# Sobre o projeto
Este repositório é uma atividade avaliativa do curso Spring Boot Expert da DevSuperior, composta por um sistema para gerenciar cidades e eventos. O projeto foi desenvolvido utilizando a prática de Test-Driven Development (TDD), visando implementar funcionalidades que atendam aos requisitos especificados nos testes automatizados.
### Tecnologias Utilizadas

- *Back end*: Spring Boot, com foco no desenvolvimento guiado por testes (TDD), além de modelagem de banco de dados e criação de APIs REST.
  
Durante o desenvolvimento, aprofundei meus conhecimentos em TDD, aplicando boas práticas de teste e integração contínua para criar uma aplicação backend sólida e testável.

## Modelo conceitual
![Modelo Conceitual](/assertsReadme/diagrama.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- TDD

# Rotas
&#9679;	Eventos

| Método | Caminho                      | Descrição                                           |
| ------ | ---------------------------- | -------------------------------------------------- |
| PUT    | /events/{id}                 | Atualiza os dados de um evento específico pelo ID.	 |

&#9679;	Empregados
| Método | Caminho                      | Descrição                                           |
| ------ | ---------------------------- | -------------------------------------------------- | 
| GET    | /cities             | Retorna uma lista de todas as cidades, ordenadas pelo nome.             | 
| POST   | /cities                   |	Adiciona uma nova cidade.                              |
| DELETE   | /cities/{id}	                   |		Remove uma cidade específica pelo ID.                            |


# Como executar o projeto

## Back end
Pré-requisitos: Java 21

```bash
# clonar repositório
git clone https://github.com/Ital023/DSCommerce.git

# executar o projeto
./mvnw spring-boot:run
```

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Ital023" title="Github do Ítalo Miranda">
        <img src="https://avatars.githubusercontent.com/u/113559117?v=4" width="100px;" alt="Foto do Ítalo Miranda no GitHub"/><br>
        <sub>
          <b>Ítalo Miranda</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
