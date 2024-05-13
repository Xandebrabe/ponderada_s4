# Atividade ponderada - Semana 4

## Processo

Ao instalar o dotnet, podemos executar o comando:

`$ dotnet new console`

Esse comando será responsável por executar a criação do projeto.

Após isso, executamos a instação de alguns packages necessários para o acompanhamento das métricas:

`$ dotnet add package System.Diagnostics.DiagnosticSource` 

Com esses passos realizados, podemos obter uma primeira resposta do sistema, a partir do comando:

`$ dotnet run`

Obteremos a resposta:

![Print1](/assets/app_running.png)

Logo após isso, instalaremos uma biblioteca que torna possível o monitoramento das métricas:

`$ dotnet tool update -g dotnet-counters`

![Print2](/assets/counter_installed.png)