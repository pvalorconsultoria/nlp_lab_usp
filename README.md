# Laboratório de Processamento de Linguagem Natural da USP 2023

Trabalho de conclusão do Laboratório de Processamento de Linguagem Natural da USP 2023. Um exemplo de como refinar um modelo de linguagem treinando em mandarim e adaptá-lo ao português com alguns caveats xD

## Modelo de Linguagem

Os modelos de linguagem são um tipo de inteligência artificial (IA) que pode ser usado para entender e gerar linguagem natural. Eles são usados em aplicativos de processamento de linguagem natural (NLP), como tradução automática, resumo de texto, resposta a perguntas e muito mais. Os modelos de linguagem são treinados em grandes conjuntos de dados de texto para aprender a estrutura e o significado da linguagem. Isso permite que eles gerem novas frases que soam como se tivessem sido escritas por um humano.

Os modelos de linguagem tornaram-se cada vez mais importantes para tarefas de NLP devido à sua capacidade de capturar as nuances da linguagem natural. Eles podem ajudar as máquinas a entender melhor o contexto das conversas e interpretar com precisão a entrada do usuário. À medida que a tecnologia de IA continua a evoluir, os modelos de linguagem se tornarão ainda mais importantes para os aplicativos de NLP.

## Motivação para esse Exemplo

A democratização da tecnologia de IA tem sido um dos principais focos da comunidade de pesquisa nos últimos anos. Uma maneira de conseguir isso é criar modelos multilíngues que possam ser usados por pesquisadores de diferentes países e culturas. Isso é especialmente importante para os países de língua portuguesa, que têm menos recursos do que outros idiomas, como o chinês. Ao criar modelos linguísticos compatíveis tanto com o português como com o chinês, a comunidade de pesquisa portuguesa pode beneficiar da vasta quantidade de recursos disponíveis em chinês e utilizá-los para aprofundar a sua própria investigação. Isso os ajudará a crescer e se tornar mais competitivos na comunidade global de IA.

## Modelo de Linguagem para o Portuchinês

Neste exemplo, vamos refinar o modelo de linguagem [bert-base-chinese](https://huggingface.co/bert-base-chinese), um modelo de linguagem baseado em atenção em grandes corpos de texto escritos em mandarim, e adaptá-lo ao idioma criado para o ensino de mandarim para falantes de português - o [portuchinês](https://github.com/pvalorconsultoria/nlp_lab_usp/blob/main/Portuchin%C3%AAs.pdf) :)

Como visto no site da hugging-face, o modelo bert-base-chinese é baseado no modelo [BERT original](https://huggingface.co/bert-base-uncased), mas foi adaptado para entender melhor o texto chinês. Isso torna mais fácil para os desenvolvedores criar modelos que possam processar com precisão o texto chinês e gerar resultados significativos. Esse modelo tem sido usado em várias aplicações, como classificação de texto, resposta a perguntas e análise de sentimentos, etc.

No nosso caso, vamos criar um dataset sintético do portuchinês e adaptar esse grande modelo de linguagem em mandarim para essa língua construída. Assim, esperamos que esse pequeno novo modelo de linguagem seja capaz de entender a gramática do portuchinês, emprestada do mandarim, mas também introduzir palavras em português em seu vocabulário.

Outro experimento interessante é saber se o modelo que foi treinado em grandes volumes de texto do mandarim seria capaz de expandir as capacidades do portuchinês. Isto é, certas regras gramáticas que estão bastante presentes no mandarim seriam automaticamente aprendidas sem que haja exemplos no dataset sintético criado para o exemplo xD.
