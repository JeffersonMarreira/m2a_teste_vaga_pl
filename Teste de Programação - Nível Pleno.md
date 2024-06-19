<h1 align="center">Teste de Programação - Nível Pleno</h1>

<p align="center"><i>Aplicação: Controle de Abastecimentos</i></p>

![Static Badge](https://img.shields.io/badge/python-blue)
![Static Badge](https://img.shields.io/badge/orm-django-3fb950)
![Static Badge](https://img.shields.io/badge/report-PyPDF-DAA520)

## Descrição Geral

  Você foi contratado para analisar e desenvolver um software para gerenciar os abastecimentos e tanques de combustíveis do posto ABC. 
  
  O gerente do posto forneceu as seguintes informações e requisitos:

- ### 1 - Requisitos Funcionais
    #### 1.1 - Registro de Abastecimentos:

    Controle dos abastecimentos feitos durante cada dia.
   
    Identificação da bomba utilizada, quantidade de litros e valor abastecido.

    Registro do imposto de 13% sobre o valor abastecido.

    #### 1.2 - Estrutura dos Tanques e Bombas:
    
    O posto ABC possui dois tanques: um de gasolina e um de óleo diesel.
    
    Cada tanque possui duas bombas de combustível associadas.

    #### 1.3 - Relatórios:

    Relatório de abastecimentos agrupados por dia, tanque, bomba e valor.
    
    Exibição da soma total do período no relatório.

    #### 1.4 - Gerenciamento de Estoque (Opcional):

    Controle do nível de combustível em cada tanque.
    
    Alertas para reabastecimento quando o nível de combustível estiver baixo.

    #### 1.5 - Histórico e Auditoria (Opcional):

    Registro histórico de todas as operações de abastecimento e alterações nos níveis de tanque.

    Logs de auditoria para rastrear alterações críticas no sistema.

- ### 2 - Requisitos Não Funcionais
    #### 2.1 - Boas Práticas:
    
    Utilize boas práticas de desenvolvimento e padrões de código limpo.

    Utilize o Git para controle de versão e publique o projeto no GitHub.

    #### 2.2 - Testes:

    Crie testes unitários, funcionais e de integração para a aplicação.
    
    #### 2.3 - Tecnologia:
    
    Utilize Python e Django.

    Utilize PyPDF para os relatórios.

    #### 2.4 - Desempenho e Escalabilidade (Opcional):

    Implemente caching para melhorar o desempenho dos relatórios.

    Garanta que a aplicação possa escalar para suportar um grande volume de dados.

    #### 2.5 - Segurança (Opcional):
    
    Implemente autenticação e autorização de usuários.

    Garanta que a aplicação esteja protegida contra vulnerabilidades comuns (e.g., SQL Injection, XSS).

- ### 3 - Instruções para Entrega

    #### 3.1 - Configuração do Ambiente:

    Crie um repositório no GitHub e configure o projeto Django com um ambiente virtual.

    Adicione as dependências necessárias no arquivo requirements.txt.

    #### 3.2 - Modelagem do Banco de Dados:
    
    Crie modelos Django para representar tanques, bombas e abastecimentos.
    
    Defina as relações apropriadas entre os modelos.

    #### 3.3 - Funcionalidades:

    Implemente a lógica para registrar os abastecimentos com os detalhes necessários.

    Calcule e registre o imposto de 13% sobre o valor abastecido.

    Implemente o controle do nível de combustível nos tanques e alertas para reabastecimento.

    #### 3.4 - Relatórios:

    Implemente a funcionalidade para gerar relatórios em PDF utilizando o PyPDF.

    Os relatórios devem ser agrupados por dia, tanque, bomba e valor, com a soma total do período.

    #### 3.5 - Testes:

    Crie testes unitários para validar a lógica dos modelos e das funcionalidades.

    Crie testes funcionais para verificar a geração correta dos relatórios.

    Implemente testes de integração para validar a interação entre os componentes.

    #### 3.6 - Segurança e Desempenho (Opcional):

    Implemente autenticação e autorização de usuários.

    Garanta que a aplicação esteja protegida contra vulnerabilidades comuns.

    Utilize caching para melhorar o desempenho dos relatórios.

    #### 3.7 - Publicação no GitHub:

    Suba o projeto em um repositório público no GitHub.

    Inclua um arquivo README.md com instruções claras sobre como configurar e rodar a aplicação.