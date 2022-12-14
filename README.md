# SCM_Psicultura

Ideias que inspiram o projeto (sites, blogs, sistemas, fontes de dados): (*****INCOMPLETO****)
 * https://aquabit.com.br/?gclid=CjwKCAiAheacBhB8EiwAItVO2_rL7AFCz7uG1uRjxqcE1846T-lW-Q7qvPjndztknbMo4G_gfS1EYRoC5aUQAvD_BwE
 * https://www.scielo.br/j/rbz/a/7zSgd4p6MkqpkRhMLRp5Krh/abstract/?lang=pt
 * http://www.proedu.rnp.br/bitstream/handle/123456789/1460/Piscicultura_Z_WEB.pdf?sequence=1&isAllowed=y

## Integrantes do grupo (*****COMPLETO****)
 * Henrique Pablo Pinheiro dos Santos Pimentel - henrique___pablo@hotmail.com
 * Bruno Cavalcanti de Mendonça - lekinn.c.mend@gmail.com
 * Ruallyson Felype Travassos de Moura - ruallysonfelype@gmail.com
 * Thomas Jefferson do Nascimento Ferreira -  thomasj.nascimento@gmail.com
 * Maiara Santos de Souza - maiarasouzaz.lc@gmail.com

## Descrição geral do projeto (*****INCOMPLETO****)
Nesta descrição, apresente um texto resumido com a(s) principal(is) funcionalidade(s) do sistema. 
É muito importante que você consiga responder em uma única frase: qual a principal funcionalidade do seu sistema? 
A partir disso, você deve detalhar as funcionalidades do sistema tentando responder às perguntas:
 1. Quem vai usar o programa?

Administrador - Gestão central (Pessoa que tem a capacidade de visualizar, manipular, cadastrar e remover dados e geradores de dados. Além de gerenciar as permissões dos usuários).

Moderador - Gestão moderada (Pessoa que tem a capacidade de visualizar, manipular e gerenciar os dados).

Usuário - Apenas visualização (Pessoa com a capacidade de apenas visualizar os dados).

 2. Que serviços são “necessários” (leia-se: importantes para os clientes e usuários)?
Visualização da planilha de dados.
Visualização gráfica dos dados da planilha.
Seleção de parâmetros da visualização de dados.
Sistema de gerenciamento de permissão de acesso aos dados.

 3. Quais serviços cada usuário pode executar?
 Administrador:
Gerar planilha de dados
Gerar gráfico de dados
Controle de importação e exportação de dataset
Gerenciamento de permissões dos usuários

Moderador
Gerar planilha de dados
Gerar gráfico de dados
Controle de importação e exportação de dataset

Usuário 
Visualizar planilha de dados
Visualizar gráfico de dados


## Requisitos do projeto (*****INCOMPLETO****) 
Liste de forma numerada e com identificadores únicos os seus requisitos de projeto. 
A descrição de cada requisito deve ser breve, porém informativa. 
Exemplo de requisitos para um sistema de automação comercial (A INFORMAÇÃO ABAIXO É SOMENTE UM EXEMPLO E DEVE SER ALTERADA):
 * **Importar arquivos (tanques)** - O sistema deve ser capaz de importar arquivos no formato fornecido pelo cliente.
 * **Exportar arquivos (tanques)** - O sistema deve ser capaz de exportar arquivos no formato pdf, csv e outro fornecido pelo cliente.
 * **Gerar planilha de dados** - O sistema deve ser capaz de gerar uma planilha com os dados de um ou mais tanques.
 * **Gerar gráfico dos dados do tanque** - O sistema deve ser capaz de gerar um gráfico com os dados de um ou mais tanques.
 * **Sistema de login** - O sistema deve ser capaz de controlar o acesso através de login e senha.
 * **Sistema de cadastramento** - O sistema deve ser capaz de cadastrar/remover e armazenar os dados únicos de login e senha.
 * **Sistema de gerenciamento** - O sistema deve ser capaz de gerenciar as permissões de acesso do usuário ao dataset.
 * **Controle de parâmetro dos “peixes”** - O sistema deve ser capaz de cadastrar os “peixes” com seus parâmetros min/max necessários para sobrevivência.
 * **Comparação de gráficos** - O sistema deve ser capaz de comparar mais os dados de mais de um tanque e exibir em um gráfico.
 * **Sistema de comparação de parâmetros dos “peixes” e tanques** - O sistema deve ser capaz de comparar os dados do tanque com os parâmetros cadastrados do “peixe”.
 * **Sistema de alerta** - O sistema deve ser capaz de gerar um sinal de alerta ao ser atingido os valores min/max do “peixe” no tanque.
 * **Relatórios de desempenho zootécnicos** - O sistema deve conseguir medir a eficiência produtiva atingida durante a criação do lote a partir dos parâmetros fornecidos pelo cliente. 
 * **Controle de ração** - O sistema deve ser capaz de conseguir calcular a quantidade de ração fornecida em cada tanque, monitorando as necessidades em relação a cada “peixe”.

ATENÇÃO - A sua lista de requisitos não deve ultrapassar mais de 30 itens.
 
## Cronograma de MVPs com seleção de requisitos (*****FALTA FAZER****)
Liste os possíveis MVPs associando-os diretamente aos requisitos do projeto e faça uma breve descrição e justificativa de cada MVP. 
A descrição deve ser breve e justificar as escolhas. 
Exemplo de sequência de MVPs:
* **MVP1 - Cadastros** - [REQ1, REQ2]: cadastros básicos de todas as entidades
* **MVP2 - Regras** - [REQ3, REQ4]: implementação de regras mínimas para venda de produtos com cartão de crédito.
