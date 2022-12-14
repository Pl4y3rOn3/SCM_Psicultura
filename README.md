# SCM_Psicultura

Ideias que inspiram o projeto:
 * https://aquabit.com.br/?gclid=CjwKCAiAheacBhB8EiwAItVO2_rL7AFCz7uG1uRjxqcE1846T-lW-Q7qvPjndztknbMo4G_gfS1EYRoC5aUQAvD_BwE
 * https://www.scielo.br/j/rbz/a/7zSgd4p6MkqpkRhMLRp5Krh/abstract/?lang=pt
 * http://www.proedu.rnp.br/bitstream/handle/123456789/1460/Piscicultura_Z_WEB.pdf?sequence=1&isAllowed=y
 * https://thingsboard.io/

## Integrantes do grupo
 * Henrique Pablo Pinheiro dos Santos Pimentel - henrique___pablo@hotmail.com
 * Bruno Cavalcanti de Mendonça - lekinn.c.mend@gmail.com
 * Ruallyson Felype Travassos de Moura - ruallysonfelype@gmail.com
 * Thomas Jefferson do Nascimento Ferreira -  thomasj.nascimento@gmail.com
 * Maiara Santos de Souza - maiarasouzaz.lc@gmail.com

## Descrição geral do projeto
O presente programa tem como objetivo fornecer de maneira simplificada um sistema de consulta e monitoramento de dados de uma base de pesca. Este sistema possui três principais tipos de usuários : o administrador, o moderador e o usuário. Onde o primeiro, o administrador tem como a atribuição de gestão central, tendo as possibilidades de visualizar e manipular dados, criar “tanques” e “peixes”, criar/remover/modificar parâmetros dos “tanques” de "peixes" e gerenciar as permissões dos usuários. O segundo, moderador, tem a atribuição de gestão moderada, tendo  as possibilidades limitadas de visualizar, manipular e gerenciar dados. Por último, e não menos importante, temos o usuário, ao qual suas possibilidades serão limitadas apenas à visualização, ou seja, terá acesso apenas aos dados coletados e apresentados a ele.
   A partir disso, o presente sistema oferecerá os seguintes serviços: a visualização da planilha de dados, visualização gráfica dos dados da planilha, seleção de parâmetros de visualização de dados, sistema de monitoramento, relatório de desempenho zootécnicos, gerenciamento e armazenamento de informações, e sistema de gerenciamento de permissões de acesso aos dados.
    Assim, cada tipo de usuário poderá executar serviços diferentes, que serão destacados e especificados aqui.  O administrador, como já ressaltado, além da possibilidade de gerar planilhas e gráficos de dados, também poderá ter acesso ao serviço de controle de importação e exportação de dataset, seleção de parâmetros de visualização de dados, sistema de monitoramento, relatório de desempenho zootécnicos, gerenciamento e armazenamento de informações, e sistema de gerenciamento de permissões de acesso do usuário aos dados. Já o moderador, terá acesso à apenas alguns desses serviços como, gerar planilhas e gráficos de dados, sistema de monitoramento, relatório de desempenho zootécnicos, gerenciamento e armazenamento de informações,  além da importação e exportação de dataset. Enquanto o usuário, será limitado apenas ao serviço de visualizar planilhas, gráficos de dados e alertas do sistema.


## Requisitos do projeto
 * **REQ1 - Importar arquivos (tanques)** - O sistema deve ser capaz de importar arquivos no formato fornecido pelo cliente.
 * **REQ2 - Exportar arquivos (tanques)** - O sistema deve ser capaz de exportar arquivos no formato pdf, csv e outro fornecido pelo cliente.
 * **REQ3 - Gerar planilha de dados** - O sistema deve ser capaz de gerar uma planilha com os dados de um ou mais tanques.
 * **REQ4 - Gerar gráfico dos dados do tanque** - O sistema deve ser capaz de gerar um gráfico com os dados de um ou mais tanques.
 * **REQ5 - Sistema de login** - O sistema deve ser capaz de controlar o acesso através de login e senha.
 * **REQ6 - Sistema de cadastramento** - O sistema deve ser capaz de cadastrar/remover e armazenar os dados únicos de login e senha.
 * **REQ7 - Sistema de gerenciamento** - O sistema deve ser capaz de gerenciar as permissões de acesso do usuário ao dataset.
 * **REQ8 - Controle de parâmetro dos “peixes”** - O sistema deve ser capaz de cadastrar os “peixes” com seus parâmetros min/max necessários para sobrevivência.
 * **REQ9 - Comparação de gráficos** - O sistema deve ser capaz de comparar mais os dados de mais de um tanque e exibir em um gráfico.
 * **REQ10 - Sistema de comparação de parâmetros dos “peixes” e tanques** - O sistema deve ser capaz de comparar os dados do tanque com os parâmetros cadastrados do “peixe”.
 * **REQ11 - Sistema de alerta** - O sistema deve ser capaz de gerar um sinal de alerta ao ser atingido os valores min/max do “peixe” no tanque.
 * **REQ12 - Relatórios de desempenho zootécnicos** - O sistema deve conseguir medir a eficiência produtiva atingida durante a criação do lote a partir dos parâmetros fornecidos pelo cliente. 
 * **REQ13 - Controle de ração** - O sistema deve ser capaz de conseguir calcular a quantidade de ração fornecida em cada tanque, monitorando as necessidades em relação a cada “peixe”.
 * **REQ14 - Gerenciamento de informações** - O sistema irá armazenar todos os dados e informações referentes aos tanques.
 
## Cronograma de MVPs com seleção de requisitos
 * **MVP1 - Importação de dados - [REQ1, REQ2, REQ3, REQ5]: Exportar e importar informações vindas da base de pesca com um sistema simples de login de único usuário.
 * **MVP2 - Gráficos e Gerenciamento - [REQ4, REQ6, REQ7]: Gerar gráficos a partir dos dados fornecidos e sistema de cadastro e gerenciamento de usuário. 
 * **MVP3 - Sistemas de alerta - [REQ8, REQ10, REQ11, REQ14]: Realizar a armazenagem e comparação de parâmetros min/max dos peixes com os dados fornecidos e gerar alertas.
 * **MVP4 - Geração de relatório - [REQ9, REQ12, REQ13]: Realização de intersecção de gráficos e geração de relatório zootécnico.
  
