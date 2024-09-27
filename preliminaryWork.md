# Preliminary Work

Introdução da seção

## Subsection: Chat GPT API experiments

Seção focada em explicar os experimentos realizados com o Chat Gpt:

Introdução

Objetivo do experimento: Queremos inicialmente verificar o quão complexo é utilizar uma LLM e a api do Chat GPT
Em seguida, verificar se o chatGpt consegue uma gerar uma boa análise da literatura de BL films de diferentes formas:
    1- Sem contexto
    2- Como um pdf de contexto
    3- Com multiplos pdfs de contexto
Tudo em plain Text.

Conclusão do trabalho realizado
Sem nenhum pdf, a análise fica superficial, porém com mais pdfs, ele começa a misturar informações dos pdfs e vira uma confusão.
Impedimento: a api só aceita X tokens, muitos pdfs = multiplos tokens. Ficamos impossibilitados de mandar com 8 artigos.
Mandamos divididos para fazer o texto inteiro, no entanto ele gerou o mesmo texto diversas vezes
Deixar o github dos experimentos (tenho que organizar eles)

Solução de implementação
Vetorizar os pdfs e aplicar RAG

## Document collection vectorization
