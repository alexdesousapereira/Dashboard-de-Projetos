# Dashboard-de-Projetos
Click abaixo para acessar o dashboard de projetos.

## Introdução
A Karpa Group Corporation tem sede nos Estados Unidos atua no setor petroquímico e produz resinas
termoplásticas: polietileno (PE), polipropileno (PP) e policloreto de vinila (PVC). 

## Objetivos
O principal objetivo é ter uma visualização completa das informações de todo o portfólio de projetos em andamento, sem perder a visualização dos detalhes dos projetos individuais. Para isso, a equipe de transformação digital em Projetos tinha, inicialmente, duas opções de ferramentas tecnológicas que poderiam ser adotadas: a solução em nuvem do Project Online e o Power BI.
Você é a pessoa Consultora Especializada em Projetos e vai atuar na frente de desenvolvimento do Dashboard em Power BI. Sua missão é agrupar os arquivos locais dos Gerentes de Projeto para apresentá-los em um dashboard único, interativo e dinâmico. Dessa forma, os Gerentes de Projetos ficarão livres da tarefa manual de preparar apresentações individuais e ao mesmo tempo, as Diretorias terão acesso rápido às informações compiladas.

## Requisitos
1. A solução deverá ser desenvolvida utilizando o Power BI Deskop. Assista à primeira aula caso ainda não tenha feito a instalação na sua máquina.
2. Construa o relatório com três páginas: Capa, Overview e Detalhamento por Projeto.
Overview:
- Custo Real, Custo da Linha de Base, Trabalho Real e Trabalho da Linha de Base;
- Percentual de horas trabalhadas;
- Percentual de orçamento consumido;
- Custo e Custo da Linha de Base ao longo do tempo;
- Trabalho e Trabalho da Linha de Base ao longo do tempo;
- Projetos por Área;
- Projetos por Gerência;
- Overview dos projetos com início, término, duração, duração de linha de base, indicador de custo, indicador de trabalho e percentual de conclusão;
- Lista dos projetos em um Gráfico de Gantt, pelo qual se possa visualizar a situação de cada um deles;

Detalhamento por projeto:

- Custo Real, Custo e Custo de Linha de Base;
- Detalhamento do projeto com área, gerente de projeto, início, término, duração, percentual de 
conclusão, total de tarefas;
- Curva S, com o valor acumulado de Custo e do Custo da Linha de Base ao longo do tempo;
- Número de tarefas, com o percentual de tarefas críticas ou não;
- Custo ao longo do tempo, comparando Custo, Custo da Linha de Base e Custo Real;
- Tarefas do projeto, início, téemino, status, custo e trabalho;

Conceitos:

- Início: data de início do projeto;
- Término: data do término prevista do projeto;
- Custo da Linha de Base: custo planejado no início do projeto. É o orçamento do projeto.
- Custo Real: valor gasto no projeto até o dia de hoje;
- Custo: valor previsto que será gasto até o final do projeto, considerando as variações ao longo do mesmo;
- Trabalho da Linha de Base: quantidade de horas que foram planejadas para serem gastas no projeto;
- Trabalho Real: quantidade de horas gastas até o momento;
- Trabalho: quantidade de horas previstas para serem gastas até o final do projeto, considerando as variações ao longo do tempo;
- Duração& da& Lnha& de& Base:& quantidade de dias previstos para finalizar o projeto;
- Duração Real: quantidade de dias trabalhados até o momento;
- Duração: quantidade de dias de trabalho previstos até o final do projeto, considerando as variações ao longo do tempo;
- Percentual de Horas Trabalhadas: Divisão do Trabalho Real pelo Trabalho da Linha de Base. Ele indica quantas horas de trabalho foram realizadas até o momento;
- Percentual de Orçamento Consumido:Divisão do Custo Real pelo Custo da Linha de Base. Ele indica o que foi efetivamente gasto até o momento;
- Indicador de Trabalho: Divisão do Custo Real pelo Custo da Linha de Base. Ele indica o que foi efetivamente gasto até o momento;
- Indicador de Custo: Divisão do Custo pelo Custo de Linha de Base. Ele indica a tendência de o projeto ser fnalizado conforme os valores planejados de custos;
- Percentual Concluído: Divisão da Duração Real pela Duração total.

## Dados
***
A extração dos dados foi feita em Agosto de 2021 e foi disponibilizado um arquivo do Access para cada um dos projetos, contendo todos os dados dos mesmos. A única tabela que você precisa utilizar de cada arquivo é a MSP_EpmTask, que contem todos os detalhes das tarefas do projeto.
- Duração, Custo de Trabalho da Linha de Base: são os valores orçados, ou seja, foram planejados no início dos projetos são imutáveis;
- Duração, Custo e Trabalho: representa o total dos valores realizados e o restante previsto até a última tarefa, bem como os valores excedentes ao planejado;
- Duração, Custo e Trabalho Real: indicam apenas os valores das tarefas executadas até o momento atual.

## Análises
***
Para as análises foram direcionadas as seguintes perguntas:

1. Qual é o orçamento total e qual o valor gasto até o momento?

Resposta: 
Orçamento: R$ 1.367.420
Total Gasto: R$ 863.295

2. Quantas horas de trabalho estão previstas na Linha de Base e quantas horas de trabalho foram realizadas?

Resposta: 9.515 horas e 6.987 horas respectivamente.

3. Qual é o percentual de horas trabalhadas e o percentual de orçamento consumido até o momento? 
Resposta: 73% e 63% respectivamente.

4. Os projetos estão distribuídos em quais Áreas? Quantos projetos por Área?

Resposta: Engenharia (3), Qualidade (2), Tecnologia (1)

 Qual é o Gerente com maior número de Projetos?

Resposta: Marcelo

5. Qual é o projeto com a duração planejada mais longa?  Quem é o Gerente?
Resposta: Construção de Estacionamento com 208 dias e o gerente é Leonardo.

6. Algum projeto já foi concluído? Qual? Qual?

Resposta: Sim, Reforma do Galpão

7. De todos os projetos, qual apresenta o maior número de KPIs não atendidos?

Resposta: O projeto Bomba de Gasolina está com os KPIs de Custo e Trabalho fora dos limites.

8. No projeto Bomba de Gasolina, qual foi o mês com maior diferença entre as horas de trabalho da linha de base comparado com o trabalho?

Resposta: Junho. Linha de base: 80h e Realizado: 1.008h.

9. Pela exibição do Gráfico de Gantt, qual a sequência de conclusão dos projetos? 

Resposta: Reforma do Galpão, Processo de Logística, Bomba de Gasolina, Normas de Segurança, Construção do Estacionamento e Instalação dos Equipamentos.

10. Qual é o percentual de conclusão e duração do Projeto de Processos de Logística? 

Resposta: 87% e 150 dias.

11. Há quantas tarefas ao todo no Projeto de Processos de Logística e qual o percentual delas são tarefas críticas? 

Resposta: 23 tarefas. 17% são tarefas críticas.

12. Quais são as tarefas que ainda precisam ser concluídas no Projeto de Processos de Logística? 

Resposta: Elaborar o treinamento, Obter a aprovação e 
Realizar o Treinamento.

13. No Projeto da Bomba de Gasolina, a partir de qual mês se observa o descolamento da Curva S do Custo Acumulado do Custo da Linha de Base Acumulado?

Resposta: Maio/2021

# Direitos de Uso
***
Este repositório têm como objetivo apresentar o **Dashboard de Projetos** feito no Microsoft Power BI. Então, dentro deste repositório você pode utilizar deste conteúdo sem nenhuma restrição contanto que não me responsebilize por eventuais causas ou danos morais perante minha responsabilidade.	

Exigido | Permitido | Proibido
:---: | :---: | :---:
Aviso de licença e direitos autorais | Uso comercial | Responsabilidade Assegurada
 || Modificação ||	
 || Distribuição ||	
 || Sublicenciamento || 



