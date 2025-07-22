# Estrutura Dinâmica
Atividade M.A.P.A da faculdade da materia de Estrutura de Dados I


Otimização de Rota com Listas Dinâmicas

Uma rede de lojas de produtos naturais utiliza um sistema automatizado para planejar as
rotas de entrega dos caminhões. Cada parada da rota representa uma loja que deve ser
visitada. No sistema antigo, sempre que uma nova loja era adicionada no meio da rota, era
necessário realocar todos os elementos da estrutura, resultando em lentidão e consumo
excessivo de memória.
Para resolver esse problema, decidiu-se utilizar uma estrutura de dados dinâmica, onde
cada ponto da rota (loja) pudesse ser facilmente inserido ou removido sem a necessidade
de deslocar os outros elementos da lista.
Você foi contratado para ajudar a equipe de desenvolvimento a implementar essa nova
estrutura. Abaixo está o código inicial de uma lista ligada com algumas funções
incompletas. Seu desafio é completar o método inserir_na_posicao para que ele insira uma
nova loja (representada por seu nome) em uma posição específica da rota.
