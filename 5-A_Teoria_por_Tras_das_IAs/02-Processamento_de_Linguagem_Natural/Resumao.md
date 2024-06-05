## Resumão

### Como os Computadores 'Entendem' o Idioma Humano
#### Análise de Linguagem Natural por meio de PLN
- Processamento de Linguagem Natural - Machine Learning
- Mas o que é PNL? Processamento de Linguagem Natural (PLN) é uma vertente da inteligência artificial que ajuda computadores entender, interpretar e manipular a linguagem humana.
- Vamos criar uma assistente virtual? Sistema de reconhecimento por voz
- Aplicações atuais na área. 
    - Sistemas: recomendação, comando por voz, chatbots...
        - Pragmática é o ramo da linguístia que estuda a linguagem no contexto de seu uso na comunicação
        - Relacionado com à análise detalhada da composição, derivação, flexão das palavras e de seus processos de formação. 
        - Pirâmide: Morfológica -> Sintaxe -> Semântica -> Pragmática

#### Deep Learning para PLN
- Deep Learning para PLN - Machine Learning
- Sistema de interpretação de linguagem natural
- Sistemas: recomendação, comando por voz, chatbots...
    - Pragmática é o ramo da linguístia que estuda a linguagem no contexto de seu uso na comunicação
    - Relacionado com à análise detalhada da composição, derivação, flexão das palavras e de seus processos de formação. 
    - Pirâmide: Morfológica -> Sintaxe -> Semântica -> Pragmática
- Os sistemas de NLP permitem que a tecnologia usada não apenas entenda o significado literal de cada palavra que está sendo dita, como também considere aspectos como: 
    - Contexto da conversa;
    - Significados sintáticos e semânticos;
    - Interprete os textos;
    - Análise sentimentos e mais.
- Redes de Deep Learning: 
    - Os primeiros modelos de linguagem usavam arquiteturas NN feedforward ou NN convolucional, mas elas não capturavam muito bem o contexto. Contexto é como uma palavra ocorre em relação às palavras circundantes na frase. Para capturar o contexto, foram aplicados NNs recorrentes.
    - O LSTM, uma variante do RNN, foi então usado para capturar o contexto de longa distância. O LSTM bidirecional (BiLSTM) melhora o LSTM ao observar as sequências de palavras nas direções para frente e para trás.
- Exemplos do mundo real em PLN? 
    - O Google substituiu seu sistema de tradução baseado em frases pela Neural Machine Translation (NMT). Isso reduz os erros de tradução em 60%. Ele usa uma rede LSTM profunda de 8 camadas e codificador e 8 de decodificador.
    - A revolução na área de NLP com Deep Learning teve início em 2018 com o lançamento dos modelos de linguagem pré-treinados ELMOs e ULMFiT. Mas, foi a proposta de uma nova arquitetura de redes neurais, denominada Transformer, baseada unicamente em mecanismo de atenção, que mudaria para sempre as pesquisas nessa área.
    - A arquitetura Transformer permitiu que o treinamento fosse realizado com um volume muito maior de dados do que era possível antes. Isso levou ao desenvolvimento de modelos de linguagem pré-treinados, que são previamente treinados e, posteriormente, são submetidos a um treinamento com um ajuste fino (fine-tuning) nas tarefas específicas de linguagem.
- Mas como isso é possível? 
    - Os word embeddings são representações vetoriais das palavras, que permitem capturar o contexto e relacionamento das palavras nos documentos, sem a necessidade de realizar engenharia de features com anotações exaustivas nas sentenças. 
- Conclusões: 
    - O momento ImageNet, em 2012, marcou o início de um enorme interesse de pesquisadores e empresas no mundo todo por Deep Learning. Já o ano de 2018 determinou o início da revolução da área de NLP com os modelos de linguagem pré-treinados, como ELMo, GPT e BERT, que produziram avanços significativos em várias tarefas de linguagem natural, tais como inferência, análise de sentimento e tradução de linguagem, em um curto espaço de tempo.

#### Exemplo Prático de PLN
- Deep Learning para PLN - Machine Learning
- Sistema de interpretação de linguagem natural
- Sistemas: recomendação, comando por voz, chatbots...
    - Pragmática é o ramo da linguístia que estuda a linguagem no contexto de seu uso na comunicação
    - Relacionado com à análise detalhada da composição, derivação, flexão das palavras e de seus processos de formação. 
    - Pirâmide: Morfológica -> Sintaxe -> Semântica -> Pragmática
- Os sistemas de NLP permitem que a tecnologia usada não apenas entenda o significado literal de cada palavra que está sendo dita, como também considere aspectos como: 
    - Contexto da conversa;
    - Significados sintáticos e semânticos;
    - Interprete os textos;
    - Análise sentimentos e mais.
- Classificação com Bert
    - Exemplo com Bert para tarefa de clasisficação, usando a biblioteca Transformers do Hugging Faces

### Materiais de Apoio
Nossos materiais complementares e de apoio têm como objetivo apresentar informações para facilitar e enriquecer a sua jornada de aprendizado. Para isso, links úteis (como slides, repositórios e páginas oficiais) serão disponibilizados, além de dicas sobre como se destacar na DIO e no mercado de trabalho 😉

#### Slides
(AULA-1)-(Introdução-para-processamento-de-linguagem-natural.pptx)[https://academiapme-my.sharepoint.com/:p:/g/personal/renato_dio_me/EXvZIT4oUDtOvM5IMH0-ZnUBhFVlv-TwYNKgaPDouBlI8A?e=BC2KUY]
 
(PARTE-2)-(Deep-Learning-para-processamento-de-linguagem-natural.pptx)[https://academiapme-my.sharepoint.com/:p:/g/personal/renato_dio_me/EU3wDnUac65Ok11LKqaz9LYBA_gFVWA-iR4PH3PwtaU-xQ?e=1w57uV]
 
(PARTE-3)-(Processamento-de-Linguagem-Natural-na-Prática.pptx)[https://academiapme-my.sharepoint.com/:p:/g/personal/renato_dio_me/EYUgXCryoidNn4yeGyK-ueMBGTS4sVOdbvj5ltYGXqDTTA?e=oMOZfB]
 
#### Dicas/Links Úteis
 
Por fim, disponibilizamos alguns links úteis para que você possa se desenvolver ainda mais através de referências oficiais das tecnologias, páginas de documentação e/ou fóruns de discussão relevantes. Nesse contexto, seguem algumas sugestões:
 
Artigos/Fórum: você pode compartilhar conteúdos técnicos através de (Artigos)[https://web.dio.me/articles] (visíveis globalmente na plataforma da DIO). Por outro lado, você também pode compartilhar suas conquistas e dúvidas usando os Fóruns (que são específicos para cada experiência educacional na DIO, como um Bootcamp por exemplo);
Rooms: caso você esteja inscrito(a) em uma experiência educacional na DIO (como um Bootcamp, por exemplo) você terá acesso ao Rooms. O Rooms é uma ferramenta de bate-papo em tempo real onde todos os inscritos podem interagir, compartilhando dúvidas e dicas (que podem conter imagens e snippets de código-fonte);
Pesquise na Web: pode parecer óbvio, mas é importante frisar a importância das engines de busca no dia-a-dia de um profissional de TI. Caso não encontre o que procura dentro da DIO, pesquise sobre o assunto (conceito, dúvida, erro etc) na Internet (dê um Google), pois na maioria das vezes você será levado à páginas incríveis como o (StackOverflow)[https://stackoverflow.com/] que salvarão o seu dia 😎
