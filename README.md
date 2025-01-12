# Esquema-Conceitual-Oficina--Projeto-DIO
Este projeto consiste no desenvolvimento de um sistema de controle e gerenciamento de ordens de serviço (OS) para uma oficina mecânica. O sistema foi projetado para otimizar o processo de execução de serviços de reparo e revisão de veículos, desde o momento em que o cliente traz o veículo até a conclusão do serviço.  O modelo de dados desenvolvido é responsável por armazenar informações sobre clientes, veículos, serviços, peças, mecânicos, equipes e ordens de serviço.
O principal objetivo deste sistema é gerenciar e organizar todas as etapas da execução dos serviços na oficina, incluindo o cálculo de custos de serviços e peças, o acompanhamento de status das ordens de serviço e o gerenciamento das equipes de mecânicos.

Funcionalidades

O sistema é capaz de gerenciar:

Clientes e Veículos: Cada cliente pode registrar múltiplos veículos, que serão submetidos a serviços na oficina.

Ordens de Serviço (OS): Para cada veículo, é gerada uma ordem de serviço que inclui informações como número, data de emissão, valor total, status (em andamento, concluída, cancelada) e a data prevista para a conclusão do serviço.

Serviços e Peças: Cada OS contém serviços específicos a serem realizados, com valores calculados a partir de uma tabela de mão-de-obra, além das peças necessárias para a execução do serviço, cada uma com seu valor associado.

Mecânicos e Equipes: Os mecânicos possuem especialidades e são alocados em equipes para executar os serviços das ordens de serviço.

Ferramenta Utilizada:
MySQL Workbench
