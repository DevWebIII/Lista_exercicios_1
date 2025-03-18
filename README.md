# Lista_exercicios_1

Respostas

1) Os principais protocolos são GET e POST. O método GET recebe os dados e o método POST envia dados.

2) Nessa arquitetura, o cliente, como um navegador por exemplo, faz uma requisição ao servidor.
O servidor recebe essa requisição, processa os dados e retorna uma resposta na forma de um documento HTTP
para que o cliente possa interpretar e exibir.

3) O protocolo HTTP desempenha o papel de realizar a comunicação entre cliente e servidor.

4 -
a) GET - recebe dados do servidor; POST - envia dados para o servidor; DELETE - exclui um recurso específico do servidor.

b) 200 - operação bem sucedida; 404 - recurso não localizado; 500 - problemas no servidor interno.

5) O cliente poderia enviar uma nova requisição a cada instante para verificar se houve alguma mudança.
Outra possibilidade seria o cliente fazer uma requisição e o servidor mantê-la aberta até que houvesse uma nova curtida ou e-mail.
Assim que o servidor enviasse uma resposta, a requisição seria encerrada e o cliente faria uma nova requisição, que permaneceria
em espera até que outra mudança acontecesse.
