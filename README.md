# Repositório para os código no Linux 
## Geral
### Listando e matando processos   ps / psgrep / pkill
O + no nome dos usuário indica apenas que ele tem mais caracteres do que ṕode serexibido. <br>
Por exemplo tinorbe+
````
ps -aux            -- listar todos os processos
ps -U  fmeserver   -- listar todos os processos do usuário femserver 
ps -U tinorberto | awk '{print $1}' -- lista apenas apenas o nª do processo
pgrep -U 999 |xargs kill -9  -- matar todos os processos do usuário 999
pkill -U 999  -- matar todos os processos do usuário 999
````
