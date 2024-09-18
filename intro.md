Contexto e Motivação

Criação cada vez maior de publicações no meio científico. Desse modo se torna difícil para os cientistas acompanharem as tendências sem utilizar ferramentas de apoio. IA generativa + LLMs + interfaces conversacionais: oferecem novas possibilidades para criar novas ferramentas que apoiem pesquisadores em tarefas de análise de literatura científica.
Muitos LLMs dispõe de APIs que permitem o desenvolvimento de aplicações em diferentes áreas. Uso de API de serviços nas aplicações voltadas para os cientistas como base de muitas ferramentas no estado-da-arte. Muitas? saberia citar muitas?

**Citar Llama3, GPT4, Gemini**

O uso de LLM e IA generativa no meio do campo científico para conseguir extrair dados de publicações, visto que hj em dia temos cada vez mais publicações científicas. Desse modo, são criadas LLM para auxiliar os pesquisadores. O que quer dizer com `são criadas LLM para auxiliar os pesquisadores? Observo também que só IA generativa e LLMs não é suficiente: os modelos não tem acesso à literatura científica. Como lidar com isso?

*Cientistas utilizam LLM para extrair informações de textos academicos. Uso de LLMs voltadas para a área cientifica com apoio para estudos da literatura, levantamento de informações a partir da literatura científica, Identificar, selecionar e extrair as informações relevantes de um conjunto de vários ou muitos artigos, sem ter que fazer o esforço de ler exaustivamente cada um*

questões que não menciona, e me parecem relevantes

Q: LLMs são treinados com grandes volumes de texto, mas não têm acesso à literatura científica especializada, nem atualizada. Assim, não é possível utilizá-los diretamente para responder perguntas sobre a literatura científica. Qual a solução para isso? Passa por esse tema aqui, RAG: retrieval-augmented generation? O que sabe sobre isso? leu em algum dos artigos?

R: Li sim prof, tem o Artigo que fala sobre essa técnica e o SyntdaSci que utiliza isso nos artigos deles.
Acho uma boa introdução 

Q:que tipo de perguntas o pesquisador poderia fazer, tem ideia, poderia ilustrar algumas?

Q: sugestão: ao invés de pensar em um sistema de Q&A, pensar um sistema de geração de textos: apresenta os artigos, e pede para o sistema fazer um (esboço de?) um review sobre os assuntos abordados;

me parece menos complicado do que pensar nas perguntas que um pesquisador poderia fazer.

R: Acho que é uma boa ideia, vai ao encontro do que a gente tava conversando com o Chu. Daí viraria um sistema que dado uma literatura científica, ele extrairia informações e montaria com resumo detalhado com as informações que foi sugerida pra ele.


acho que poderia pensar no sistema como um protótipo para executar um exercício investigativo´: até que ponto é possível obter um bom´ review, interagindo com um sistema desse tipo? (temos um especialista que poderia ajudar a validar o resultado. Com Q&A acho mais complicado.)

Q: qual seria o modelo LLM por trás do chat conversacional - não é o modelo em si que é essencial identificar, mas decisões sobre o que usar, p. ex. open access vs restricted access; foundation model vs. fine-tuned model (modelos gerais´ vs fine-tuned´ para a linguagem científica (e.g. matSciBERT))

R: Acho que seria legal investigar mais a fundo, porém a priori eu pensei em utilizar a API do OpenAi mesmo, visto que é ele que é mais usados no artigos recentes no estado-da-arte.

Q: não se fala em desejo ao fazer uma proposta, fala-se em objetivos e intenções. Como vai disponibilizar uma ferramenta online open-source se ela usa um modelo que não é open-source? Além disso, em termos de tecnologia, consegue  identificar quais desafios teriam que ser tratados para disponibilizar um sistema online? não sou contra a ideia da ferramenta online, mas me parece uma questão a mais para lidar, sendo que já há muitas questões complicadas para ter um sistema funcionando, online ou não. 

R: O modelo não é open source mas a ferramenta pode ser usada e distribuida gratuitamente, porém para usá-la é necessário colcoar a chave de API do usuário. Tanto é que há soluções que usam OpenAI e são disponibilizadas. 

Eu vejo como se a gente estivesse mundando o foco do projeto para análise de literatura cientifica

- Comentar que o Gap no meu trablho é que as LLM geralmente são treinado com inúmeros base de dados científicos, no entanto elas sofrem com o problema do overlooking, ou seja, elas veem frequentemente os mesmos métodos que nas perguntas elas respondem de forma genérica sem aprofundamento na matéria. Desse modo, quero abordar essas questoes ao enfatizar na literatura que o pesquisador está trazendo

data duplication on training can contribute to llms tendency to a generic modal answer.

Atualmente um dos issues and challenges with integrating natural language chat with material science is the LLM on tendency to generate a generic or modal answer. reforca existing bias and will not recognize new aprouches or not well documented technoogies. Desse modo, esse projeto aborda essas questões ao permitir que o pesquisador insira sua literatura atual para ser examinada, com respostas partindo da LLM e focando na literatura desenvolvida.