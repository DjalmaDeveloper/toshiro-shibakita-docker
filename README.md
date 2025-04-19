# Projeto Docker - Aplicação Remota e Microsserviços

Nesse projeto é trabalhado a criação e uso de Conteiner através do Docker para a implementação de uma infraestrutura que você criou e quer disponibilizá-la remotamente

- Criação de Máquinas Virtuais Remotas (AWS)
- Criação de container MySQL para implementar Banco de Dados e poder acessá-la de qualquer Gerenciador de Banco de Dados de qualquer lugar
- Fazendo teste de estresse, através do site *loader.io*, para ver quanto processamento o container aguenta
- Criando um Cluster para a comunicação entre várias Máquinas Remotas (Nos)
- Usando o Cluster criado para a replicação de dados entre mais de uma Máquina
- Criando uma Proxy para as requisições recebidas sejam replicadas de uma Máquina para todas as outras
- Usando novamente o site *loader.io* para fazer teste de estresse na Proxy para saber se ela realmente está distribuindo toda a carga por todo o Cluster
