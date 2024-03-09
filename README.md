## TESTE PRÁTICO - MoradaApp
### Objetivo principal
Desevolver um CRUD básico de usuários com um processo simples de autenticação utilizando as tecnologias citadas na vaga:
- Postgres
- NestJs
- Typescript
- TypeOrm

### Cronograma
- Prazo de entrega do teste: 23/03 às 16:00 até 6/04 às 16:00
- Disponibilidade de agenda para apresentação final: 29/03 até 13/04

### Requisitos obrigatórios
| ID | Descrição |
| ----- |:-------:|
| 001 | O sistema deve seguir o contrato elaborado em swagger/openapi.json, para ler o seu conteúdo basta entrar na pasta /swagger, instalar as dependências e executar o start:docs presente no package.json ou apenas copie o conteúdo do openapi e jogue no editor oficial do [swagger](https://editor.swagger.io/) |
| 002 | O candidato obrigatoriamente deve sugerir no mínimo uma alteração a ser feita no contrato com a intenção de corrigir determinadas vulnerabilidades |
| 003 | O sistema deve seguir o ERD elaborado em database.dbml e disponível no [dbdocs](https://dbdocs.io/N%C3%ADcolas%20Cleiton/MoradaAppTest) |
| 004 | O sistema deve conter no mínimo testes unitários |
| 005 | O sistema deve ter todas as mensagens das responses retornadas pelo servidor em português |
| 006 | O sistema deve adotar boas práticas de desenvolvimento de software, como por exemplo o DDD |
| 007 | O candidato deve, de maneira obrigatória, implementar o algoritmo de criptografia bcrypt |

Após a conclusão do teste, o candidato deve renomear o arquivo template.md para README.md e preencher o seu conteúdo.

### Diferenciais (NÃO É OBRIGATÓRIO)
Caso o candidato deseja se destacar no processo seletivo, recomenda-se realizar algumas das seguintes implementações de sua própria preferência:
1. **Docker**: é preferivel que o candidato opte por utilizar o docker e o docker compose para facilitar a execução em diferentes ambientes;
2. **Organização**: quanto mais o fluxo de trabalho que o dev usar for organizado, mais ele estará próximo de sua adimissão, ou seja, implementações como o eslint, prettier, husky e outras ferramentas são extremamente bem vistas;
3. **Github Actions**: será bem visto a implementação de pipelines de CI/CD utilizando o Github Actions. No caso das pipelines de deploy, o candidato deve se preocupar em implantar seu código utilizando o Dockerhub;
4. **Tempo de entrega**: entregas mais rápidas são muito bem vistas;
5. **Refatoração de contrato**: além das sugestões de possíveis alterações que são obrigatorias, o candidato pode refatorar o contrato elaborado da API, sugerindo novos fluxos para serem implementados tanto no processo de autenticação, quanto no próprio CRUD do usuário e indicar o tempo que levaria de implementação, dentro do README.md, caso esse novo contrato fosse admitido
6. **Refatoração do ERD**: se no processo de refatoração do contrato, o candidato sentir a necessidade de alterar algum conteúdo do ERD, o mesmo deve realizar as alterações usando a linguagem DBML no arquivo /database.dbml
