API para Agência de Viagens 🌍✈️


Descrição
API RESTful desenvolvida com Java e Spring Boot, para auxiliar clientes e parceiros de turismo no planejamento de viagens. Permite o cadastro, busca e gerenciamento de destinos, além de funcionalidades para avaliação e reserva de pacotes.

Funcionalidades
Cadastrar destinos de viagem.
Listar todos os destinos disponíveis.
Pesquisar destinos por nome ou localização.
Visualizar informações detalhadas de um destino.
Avaliar destinos com notas de 1 a 10.
Excluir destinos.
Tecnologias Utilizadas
Java: Linguagem de programação.
Spring Boot: Framework para construção da API.
Maven: Gerenciador de dependências.
Como Executar o Projeto
Clone o repositório:
bash
Copiar código
git clone https://github.com/emizisy/agenciaviagem.git
Navegue até a pasta do projeto:
bash
Copiar código
cd agenciaviagem
Configure a IDE (ex.: IntelliJ IDEA).
Execute o comando:
bash
Copiar código
mvn spring-boot:run
Acesse a API em http://localhost:8080.
Endpoints
Método	Endpoint	Descrição
POST	/destinos	Cadastrar um novo destino.
GET	/destinos	Listar todos os destinos disponíveis.
GET	/destinos/{id}	Ver informações detalhadas de um destino.
GET	/destinos/search?nome=	Pesquisar destinos por nome ou localização.
PATCH	/destinos/{id}/avaliar	Avaliar um destino.
DELETE	/destinos/{id}	Excluir um destino.
