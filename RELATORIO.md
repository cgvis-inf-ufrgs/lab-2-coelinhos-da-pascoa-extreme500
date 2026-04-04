# Relatório - Coelinhos da Páscoa

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: <mark>`00594975`</mark>
- **Nome**: <mark>`Gabriel Pieruccini Knopp`</mark>

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

<mark>`
* Para os 16 coelhos, siga as instruções a seguir.
* Rotacione o coelho levemente para que ele fique olhando para o centro mais tarde.
* De 4 em 4 coelhos, adicione uma rotação em X relativa ao tempo (para que o coelho dê piruetas).
* Escale o coelho em um valor entre 0 e 1 para diminuir o tamanho do modelo.
* Translade o coelho em um x para a distância da origem desejada e em y usando seno e o tempo, para que os coelhos fiquem subindo e descendo.
* Rotacione o coelho em X usando o tempo e a posição "i" do coelho da fila no cálculo (para que eles fiquem separados no círculo girando com o tempo).
* Adicione duas esferas e as escale para que diminuam de tamanho, mantendo o valor y levemente maior que o x e y para ter um formato oval.
* Rotacione em Z os ovos para a direção contrária à qual ele irá girar futuramente, relativa ao tempo (para que o ovo se mantenha de "pé" enquanto orbita o coelho).
* Translade um ovo para a distância da qual ele deve ficar do coelho, e o outro ovo para a distância contrária da qual ele deve ficar do coelho (ex.: 1 e -1).
* Rotacione em Z os ovos para a direção à qual ele irá girar futuramente, relativa ao tempo.
* Agora, faça para ambos os ovos a mesma translação e todas as outras transformações seguintes que o coelho faz também.
* Abaixe levemente o chão para que nenhum objeto fique atravessando ele.
`</mark>

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

<mark>`Sem dúvida, novamente, o maior desafio foi fazer o código rodar no meu pc de casa. Demorei bastante tempo até entender que deveria incluir a linha "#define _USE_MATH_DEFINES" antes de "#include <cmath>" para que o código funcionasse. Depois disso, o resto fluiu normalmente. Dentre as transformações, a talvez mais complexa foi a que envolvia o seno, mas o professor conseguiu me ajudar em aula a chegar na resposta.`</mark>

## Você acha que conseguiu resolver o problema de forma adequada?

<mark>`Acredito que dessa vez, sem dúvida. Quando rodando em casa, o resultado me pareceu que ficou praticamente idêntico ao do vídeo.`</mark>

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

<mark>`Achei extremamente divertido o laboratório, e acho que consegui aplicar bem os conhecimentos sobre matrizes, finalmente! Talvez vale ressaltar o uso da linha "#define _USE_MATH_DEFINES" antes de "#include <cmath>" para usuários de Windows, que eu ACHO que foi o problema que eu enfrentei em casa.`</mark>

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

<mark>`<preencher>`</mark>
