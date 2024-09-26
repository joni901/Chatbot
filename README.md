# Chatboot

Este projeto é um piloto de IA generativa que desenvolvemos na Observatório Social do Brasil (OSB), com o objetivo de responder perguntas específicas dos nossos seguidores sobre os relatórios da organização. O projeto ainda está em andamento e, mais adiante, detalharemos tudo de forma mais completa. A seguir, explico as principais etapas e pontos de melhoria:

# 1. Como o trabalho foi feito:
A. Transformação em chunks: Primeiramente, dividimos os relatórios em chunks (trechos menores de texto). Esses chunks são essenciais para permitir que a IA localize a parte exata do texto relevante para responder às perguntas.

B. Criação de embeddings: Posteriormente, esses chunks foram convertidos em embeddings, que são representações matemáticas (matrizes) para que o sistema consiga compreender melhor o conteúdo dos textos.

C. Processo de perguntas: Utilizamos o mesmo processo de criação de embeddings para as perguntas feitas pelos usuários, permitindo uma comparação eficiente entre os embeddings das perguntas e dos chunks.

D. Identificação da melhor resposta: Por fim, o sistema avalia qual chunk tem a maior probabilidade de conter a resposta correta para a pergunta feita.

# 2. Pontos a melhorar:
A. Respostas diretas: O sistema ainda não responde diretamente à pergunta, mas existe a possibilidade de implementar essa funcionalidade, desde que haja financiamento para desenvolvimento adicional.

B. Respostas distribuídas: Quando a resposta está presente em diferentes partes do texto, o sistema precisa reunir essas informações de forma eficiente. Isso também é tecnicamente possível, mas requer financiamento para viabilizar a melhoria.
