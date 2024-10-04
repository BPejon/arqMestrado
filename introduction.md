# Introdução

## Contexto e Motivação

- Criação cada vez maior de publicações no meio científico. Desse modo se torna dificil para os cientistas acompanharem as tendencias sem o uso de ferramentas de llm

- O principal desafio em LLM é a alucinação. Devido a diversas categorias de alucinação, a LLM tende a cofabular e inventar respostas ou não responder ao que o pesquisador pede. Desse modo, esse será um tópico abordado no projeto e implementar táticas de mitigar as alucinações e indicar os locais coretos dos documentos por meio do RAG.s
(Sinto que é importante tocar no tema de alucinaçaõ de llm, pois é um tema recorrente nos artigos de LLM pra material science. Além disso, o RAG é uma saída eficaz para evitar confabulações.) 

- Outro desafio desse mestrado é que foi observado na literatura que um dos desafios de se trabalhar com LLM e ciencia de dados é que o treinamento das LLMs acabam resultando em respostas genéricas. Desse modo, este projeto busca resolver esse problema ao inserir uma literatura ao sistema e ele lebar em conta essa literatura para elaboração da resposta.

Além disso, as bases de dados das LLMs são desatualizadas com as informações novas e principalmente científicas.

- O uso de LLM e IA generativa no meio do campo científico para conseguir extrair dados de publicações, visto que hj em dia temos cada vez mais publicações científicas. Desse modo, são criadas LLM para auxiliar os pesquisadores.

- Cientistas utilizam LLM para extrair informações de textos academicos. Uso de LLMs voltadas para a área cientifica com apoio para estudos da literatura, levantamento de informações a partir da literatura científica, Identificar, selecionar e extrair as informações relevantes de um conjunto de vários ou muitos artigos, sem ter que fazer o esforço de ler exaustivamente cada um

## Problemas q quero solucionar

- Quero solucionar o desafio de criar revisões de literatura automáticos criado por LLM. Serão enviados para o sistema um conjunto de documentos submetidos pelo pesquisador de ciencia de materias e a IA utilizará métodos do estado-da-arte para criar uma revisão da literatura baseado nesses documentos e no conhecimento prévio da IA.Serão utilizados ferramentas do estad-da-arte para evitar a problemática de halucinação.
(n sei se coloco como problema a solucionar ou meu goal)
(Vou ter q pesquisar ferramentas de geração de texto na arae de ciencias de materiais)
-AI Scientist

- Quero solucionar de que não há um chat conversacional voltado para o cientista na área de material science. As interface de linguagem natural são amplas e genéricas, por isso há esse gap na área de NLI.
- Quero mitigar o problema da halucinação implementando estratégias do estado-da-arte para garantir que as informações emitidas pela LLM são verdadeiras, implementando o RAG, promt modelling e linkando informações emitidas aos textos correspondentes.
- Quero quer o chat consiga extrair dados de imagens e tabelas para compor as respostas, visto que essa é uma dificuldade das outras LLM.   

Quero testar pra ver qual é melhor, uma ferramenta com poucos artigos ou uma ferramenta com milhares de artigos.

## Goals

- Meu objetivo é investigar como uma interface conversacional pode apoiar um pesquisador na área de material science e identificar as informações relevantes sobre esse tema.
- Solução, é utilizar o estado-da-arte de interface conversacional para identificar os locais de melhor respostas nos artigos e enviar para a LLM para construção de uma resposta detalhada sobre o assunto específico utilizando os métodos do estado-da-arte
- Meu Desejo é disponibilizar essa ferramenta online de modo open source para a comunidade cientifica.
  
## Estrutura do Documento

Capítulo 2 - Fundamentação

Capítulo 3 - Proposta de Trabalho

Capítulo 4(ou final do 3) - Conclusão e trabalhos a serem realizados 


## DICAS que gostaria de ter ouvido antes:

- Organize seu projeto antes de começar. Fazer um 1 page e 8 pages sobre o projeto para clarificar o que ele será
- Começar a ler artigos mais cedo.  



Fundamentos - o que é uma NLI?

Related Works


IDeia
Jogo Estilo gears of war modo horda

Vc entra em um mapa do modo horda com modos de jogo, Horda até 25, 30,40.

No mapa, vc consegue construir fortificações para melhorar sua base
Magia-
Personagens corpo a corpo,
magos,
metralhadora,

evolução ao longo das hordas numa mesma partida

Chefes a cada 10 niveis
Opcional: Cada classe tem seu melhoramento
Mecha -> Cria mechas,
Armadilha -> cria armadilhas
Bardo -> Bufa a galera
Mago -> Poderes em área fortes
Bruxo-> Lacaio pra ajudar
Lobisomen-> Grande poder por curto periodo de tempo
Vampiro-> Se cura de abates de inimigos
Bruto -> Bate muito e fica descontrolado

## Fable

Fazer um loldle do fab
|Rosto Herói|Gênero|Classe|Idade?|Região|Data 
Fazer um com a Arte do Herói aproximada e ir desaproximando
Da pra fazer um com as cartas, e fazer outro com as armas ou equipamentos

DB  = 
id,
name,
gender,
class, = ('Shadow, Brute')
?idade,
region, = Default Rathe
fFeatured in,

Screening vai ficar a parte dos pesquisadores. O que podemos fazer são variações de promtpts.
Não usaremos API da OpenAI, pois custou na pesquisa 500 dol e n temos esse money.