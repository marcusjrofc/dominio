# Domínio: <Aluguel de bicicletas>

Como ele funciona de verdade (pesquisei em: <site, vídeo, pessoa que trabalha nele>).

## 5 coisas
(o que o sistema guarda; ex.: numa biblioteca, livro, leitor, empréstimo)

1.Bicicleta: guarda o modelo, status (disponível, em uso, manutenção) e código de identificação.

2.Cliente (ou Usuário): guarda os dados pessoais, forma de pagamento e se tem algum aluguel em andamento.

3.Estação (ou Ponto): guarda o local, capacidade total e quantas vagas (docas) estão livres.

4.Aluguel (ou Viagem): guarda quem alugou, qual bicicleta, estação de origem, estação de destino e o tempo decorrido.

5.Plano (ou Assinatura): guarda o tipo de passe do cliente (ex: viagem única, diário, mensal) e os limites de tempo de cada um.

## 5 ações
(o que acontece com essas coisas; ex.: emprestar um livro)

1.Desbloquear/Retirar bicicleta: inicia o aluguel, muda o status da bicicleta e tira uma vaga livre da estação.

2.Devolver bicicleta: encerra o aluguel, calcula o tempo e devolve a bicicleta para uma vaga na estação.

3.Enviar para manutenção: bloqueia uma bicicleta avariada para que não possa ser alugada por ninguém.

4.Comprar plano: associa um pacote de viagens ou saldo ao perfil do cliente.

5.Transferir bicicletas (Remanejamento): ação interna para tirar bicicletas de uma estação lotada e levar para uma vazia.

## 3 regras
(o que nunca pode acontecer; ex.: ninguém pega mais de 3 livros ao mesmo tempo)

1.Um cliente não pode ter mais de um aluguel ativo ao mesmo tempo.

2.Uma bicicleta com status "em manutenção" ou "em uso" não pode ser desbloqueada.

3.A devolução não pode ser finalizada em uma estação que não tenha vagas (docas) disponíveis.
