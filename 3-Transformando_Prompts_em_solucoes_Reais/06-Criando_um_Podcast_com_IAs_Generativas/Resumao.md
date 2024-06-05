## Resumão

### Definição de um grupo
- Qual área vc quer se destacar profissionalmente e qual seu público alvo
Ex: Javascript e iniciantes de frontend

### O que é prompt Engineering
- Material Compartilhado: https://helpful-jump-17b.notion.site/PAS-Podcast-AI-Studio-210489e15d7a4a73b743bb159e45d06f

### Como escrever prompts melhores
- seja específico
Exemplo fraco: "Discuta sobre engenharia civil."
Exemplo forte: "Descreva os desafios enfrentados na construção de pontes suspensas e forneça exemplos de soluções inovadoras."

- forneça contexto adequado
Exemplo fraco: "Projete um novo sistema de abastecimento de água."
Exemplo forte: "Você foi contratado para projetar um sistema de abastecimento de água em uma área rural com pouca infraestrutura existente. Considere as limitações orçamentárias e ambientais ao propor uma solução sustentável."

- estimule a aplicação prática do conhecimento
Exemplo fraco: "Explique as leis da termodinâmica."
Exemplo forte: "Você está projetando um sistema de refrigeração para um data center. Descreva as leis da termodinâmica que são relevantes para o projeto e como elas podem ser aplicadas para maximizar a eficiência energética."

- estimule a comunicação lara e concisa 
Exemplo fraco: "Resolva a equação diferencial fornecida."
Exemplo forte: "Explique, em termos simples, o processo passo a passo para resolver uma equação diferencial de primeira ordem usando o método da separação de variáveis. Ilustre sua explicação com um exemplo numérico."

### Conceitos avançados de prompt
- Prompts negativos - São comandos de texto que ajudam a especificar o que você não deseja na sua geração de imagens. Ao usar **prompts negativos**, você pode reduzir ou eliminar elementos específicos que você não gosta ou não precisa.

- Passagem variáveis (prompt pattern) - Para deixar os resultados menos aleatórios e mais direcionados, sempre envie através de linguagem natural blocos de variáveis
Ex:
Prompt original: "Olá, [NOME]! Como posso te ajudar hoje?"

Durante a interação, peça para substituir o bloco "[NOME]" pelo nome real da pessoa, assim:

Usuário: "Olá, ChatGPT! Meu nome é João. Como posso te ajudar hoje?"

Ao receber o texto do usuário com a substituição da variável, o modelo responderá adequadamente:

ChatGPT: "Olá, João! Como posso te ajudar hoje?"

### Criando um título poderoso 
Ex:
- Você é um roteirista de podcast, e vamos criar um podcast de tecnologia, focado em front end e eu gostaria de uma ajuda sua para criar 5 sugestões de nomes criativos para um podcast de front end feito por nerds, e que tenha algum trocadilho nerd no nome

O podcast vai falar sobre dicas e novidades sobre o mundo do front end e o que está acontecendo no mercado

{REGRAS}

- O nome deve ser enxuto, um nome e um subtítulo
- O nome tenha algum trocadilho nerd com nomes de franquias conhecidas como harry potter, star wars ou senhor dos anéis
- O nome deve conter alguma palavra forte que remeta a front end

{REGRAS NEGATIVAS}

- Não quero que o título contenha palavras em inglês
- Não quero que utilize nenhuma das palavras nessa lista: Javascript, programador
- Não utilize a palavra frontend no nome nem qualquer variação dela

- Crie variações de título e subtítulo do título abaixo:
[Título e Subtítulo]

### Imagem de capa e dicas de midjourney
[ o que você quer] + palavras de contexto de configurações da imagem e filtros + adjetivos da imagem
Ex:
- a podcaster young guy bald hair smiling with microphone, side by side night city, camera settings f/ 8, 1/ 100s, ISO 100, complex lighting, backlighting, dynamic cinematic lighting, global illumination, ultra-high resolution,realistic filter of real colors, photo processing in 16K, cinematic, photorealistic, hyperrealistic ,hyper realistic, cinematic light, ultra realistic photography, ultra detailed --ar 1:1 --v 5.2

**create knight character as podcaster medieval with microphone, retro style, isometric, cube, game style, low resolution, down angle , game boy colors, 8 bits, retro sprites --ar 1:1 --v 5.2**

Aspect Ratios
Usado para definir o formato das imagens geradas
--ar 16:9

Version
Usado para definir qual a versão do modelo generativo iremos utilizar
--v 5.2

### Criando um roteiro com variáveis
Ex:
- Você é um roteirista de podcast, e vamos criar um  roteiro de um podcast de tecnologia, focado em frontend cujo o nome é "DevQuest - A Ordem dos Desenvolvedores" e tem foco em frontend,  com o público alvo de iniciantes em frontend

o formato do roteiro deve ser
[INTRODUÇÃO]
[CURIOSIDADE 1]
[CURIOSIDADE 2]
[FINALIZAÇÃO]

{REGRAS}

- no bloco [INTRODUÇÃO] substitua por uma introdução iguais as introduções dos vídeos do canal 'ei nerd', como se fossem escritos pelo Peter Jordan
- no bloco [CURIOSIDADE 1] substitua por uma curiosidade de CSS
- no bloco [CURIOSIDADE 2] sobre uma ferramenta para front ends
- no bloco [FINALIZAÇÃO] substitua por uma despedida cool com o final 'Eu sou Felipão e esse foi o CodeQuest dessa semana'
- use termos de fácil explicação
- O podcast vai ser apresentado somente por uma pessoa, chamada Felipão
- O podcast deve ser curto

{REGRAS NEGATIVAS}

- Não use muitos termos técnicos
- Não ultrapasse 5 minutos de duração

### Gerando o audio com Eleven Labs
https://elevenlabs.io/

### Editando seu podcast de maneira fácil
https://capcut.com/pt-br


