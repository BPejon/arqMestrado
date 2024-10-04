# Tarefas pra se fazer

## Capítulo Fundamentos

- Concluir introdução - 2h (vou fazer dps da proposta)
- Escrever roteiro da introdução e mandar pra prof - 1h
- Estruturar a Proposta - 1h
- Escrever a proposta - 4h
- Pegar os artigos para ler (2h)
  - Pesquisar por arquivos de geração de texto utilizando LLM
  - Pesquisar por artigo de revisão de geração de texto por LLM
  - Ler os artigos e entender como eles fazem 2h

- Reorgazinar cronograma(fazer por ultimo) - 

## Cronograma

Semana dia 16
Quarta noite: Início do Related Works
Quinta a tarde : Continuar no Related Works
Sexta tarde: Voltar e ver o que precisa colocar na introdução e já introduzir tmb
Sábado: descanso
Domingo manha: a verificar

O que estou fazendo na semana
Quarta: Escrever Preliminary Works - METADE DELE - 2H
Quinta: Analisar em Ingles e continuar preliminary works 2:30
Metade em ingles. Preliminary Work terminado!!!
Sexta: Abstract, remoção de conteudo inutil, mandei pra prof

Semana 23

Terça: Esboço do Abstract e reunião com a Orientadora.
Quarta: Finalizar Abstract (pegar como fazer um abstract) com a ideia principal, escrever o roteiro(paragrafos) da introdução com a nova ideia. Pegar artigos úties para geração de texto
Quinta: Escrever Preliminary Works
Sexta: Continuar preliminary Works e Estruturar e inicializar a nova proposta
Domingo: Ler os papers de geração de artigo

Sexta: Atualizar o capítulo de introdução - OK
Na vdd ta meio bagunçado, falta organizar os parágrafos, eu fui escrevendo o que queria mas n ta muito organizado

Próximo: Vou atualizar o Related Works e colocar em ingles

Semana dia 30
Segunda: Ver comentários da Prof, Enviar relatório do semestre pra prof analisar - OK
Terça: Responder comentários prof. Finalizar revisão do Abstract. - OK
Quarta: 
Manhã: Escrever roteiro da intro, concluir revisão e mandar pra prof. 
Noite: Buscar por artigos de revisão automatica da literatura - OK, estruturar a proposta, inicar a escrita da proposta.
Quinta:
 Manhã: Estruturar a proposta com os artigos necessários para validar meu projeto.
 Tarde: Escrever no foda-se
 Noite: Continuar a escrita.Primeiro escreve tudo. Em seguida busca as referencias que vc quer
Sexta:
Manhã: Lapidar o Preliminary Work e mandar a prof revisar, mandar email pra prof comentando do nosso caminho feliz. Continuar escrevendo o caminho feliz em portuges.
Tarde: mandar pra prof a tarde.
Noite: Continuar escrevendo o capítulo de Proposta em portuges e no que vier.

Perguntar pra prof, nossa solução vai focar na geração de texto, correto?
Pq eu vi outras soluções que usam LLM, porém elas focam em paper screening ou data extract pra colocar em tabelas como essa imagem em anexo.

Eu entendi que nossa solução que queremos criar está mais voltada pra gerar o texto completo, certo?
Eu elaborei o esquema de como seria mais ou menos o caminho ideal da aplicação:

Eu pensei nesse esquema:
1- O pequisador já deve fazer as research question, create a search strategy for a review, screening of literature
2- O pesquisador insere no sistema dados sobre seus objetivos em um formulário elaborado pelo sistema para fazer parte do promt de extração de dados.
2.5- O pesquisador insere sua bibliografia em bibtex
3- O sistema irá embusca dos full text por meio do Scholar API.
4- O sistema irá gerar embedding de todos os textos e realizar Text Preprocessing para retirar ruido e transcrever as imagens em texto.
5- O sistema ira fazer uma triagem dos estudos para identificar os artigos mais relevantes (por exemplo se a bibliografica tivar mais de 100 estudos e pegarmos apenas os 20 mais relevantes)
6- Depois o programa irá fazer uma análise full text dos estudos selecionados e extrair os dados de acordo com a pesquisa do usuário.
7- Então a parte de gerar um artigo de revisão baseado em um prompt com as principais seções de um artigo de revisão para a Ciencia de materiais
8- Em seguida, passar o artigo para uma revisão pela própria LLM em busca de aperfeiçoamento
9- Finalmente volta para o pesquisador experiente no assunto analisar a qualidade do artigo produzido 

Uma dúvida, a gente vai fazer focar nas revisões que o Chu mandou correto, que é mais um survey?
Pq eu li algumas revisões da literatura e eles fazem tabelas com as informações de cada artigo na pesquisa.
Eu vi só 1 fazendo isso. A maioria não usa tabelas.
