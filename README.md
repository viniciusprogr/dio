# DIO Agent na Prática

Desafio de Projeto da [DIO](https://dio.me): configure o [DIO Agent](https://github.com/digitalinnovationone/dio-agent) e use as skills dele para estudar, praticar e planejar a sua carreira.

## Como fazer

1. Clique em **Use this template** para criar a sua cópia deste repositório.
2. Siga os passos abaixo, copiando cada prompt para o DIO Agent.
3. Preencha a seção [Minha entrega](#minha-entrega) e entregue o link da sua cópia na DIO.

## 1. Configure o DIO Agent

- Instale um harness. Recomendamos o [Google Antigravity](https://antigravity.google/docs), mas qualquer um [da lista do DIO Agent](https://github.com/digitalinnovationone/dio-agent#-comece-em-3-passos) funciona.
- Baixe o [DIO Agent](https://github.com/digitalinnovationone/dio-agent) em **Code**, **Download ZIP**, e extraia.
- No harness, abra a pasta que tem o arquivo `AGENTS.md` e mande:

```
Oi!
Quem é você e como pode me ajudar nos meus estudos na DIO?
```

Se ele se apresentar como DIO Agent, está tudo certo.

## 2. Estudar

Troque o conceito pelo que você quer entender:

```
Me explica o que é uma skill de um agente de IA.
Meu nível: uso IA no dia a dia, mas nunca configurei um agente.
```

## 3. Praticar

Use um desafio em que você travou ou este exemplo:

```
Estou travado em um Desafio de Código da DIO.
O desafio pede a soma de todos os números de 1 até N.
Meu código imprime só o último número, não a soma:
let n = parseInt(gets());
let soma = 0;
for (let i = 1; i <= n; i++) {
  soma = i;
}
print(soma);
Me ajuda a destravar sem dar a resposta pronta.
```

## 4. Planejar

Preencha os colchetes com a sua Trilha:

```
Quero montar um plano de estudos.
Trilha: [link do seu Bootcamp ou Formação]
Objetivo: concluir em [4 semanas].
Meu nível: [iniciante, intermediário ou avançado].
Tempo: [1 hora por dia, de segunda a sexta].
```

## Bônus: seu próximo passo

Se você quer construir com IA:

```
Quero escolher meu próximo passo na Carreira AI Builder.
Quero construir: [um app para os pedidos do meu negócio].
Programação: [nenhuma, o básico ou trabalho com isso].
Objetivo: [tirar uma ideia do papel].
```

---

## Minha entrega

Olá! Como posso ajudar? Estou na pasta dio-agent-main. Posso explorar o projeto, explicar o código, corrigir algo ou criar uma funcionalidade nova.

Bora destravar! E já parabéns: você chegou bem perto. A estrutura está certa (ler o n, começar soma em 0, laço de 1 até n, imprimir no fim). O problema está em uma única linha.

🧠 Primeira dica: o que o = faz
Em JavaScript, o = é atribuição. Ele substitui o valor antigo da variável pelo novo. O valor antigo é jogado fora.

Pensa num quadro branco: cada vez que roda soma = i, você apaga o quadro e escreve só o número da vez.

🔍 Teste de mesa
Vamos “rodar o código no papel” com n = 4. Olha o que acontece com soma a cada volta do laço:

Volta	i	O que a linha faz	soma depois
1ª	1	soma = 1	1
2ª	2	soma = 2	2
3ª	3	soma = 3	3
4ª	4	soma = 4	4
É por isso que sai só o último número. Mas a resposta certa para n = 4 seria 10 (1 + 2 + 3 + 4).

🤔 Agora é com você
Preencha essa mesma tabela, mas do jeito que deveria ser:

Volta	i	soma antes	soma depois
1ª	1	0	1
2ª	2	1	3
3ª	3	?	?
4ª	4	?	?
Repara na relação entre a coluna “antes”, o i e a coluna “depois”.

Olhando essa tabela, como você calcularia o novo valor de soma a partir do valor antigo dela e do i?

Me conta o que pensou, mesmo que não tenha certeza. Se ainda travar, te dou a próxima dica. 😉

Quero montar um plano de estudos.
Trilha: Ai Builder
Objetivo: concluir em [4 semanas].
Meu nível: iniciante.
Tempo: 1 hora por dia, de segunda a sexta.

Montei seu plano! Antes, um aviso importante para ele caber na sua rotina.

⚠️ Combinando expectativas
AI Builder é uma Carreira da DIO, não uma única trilha. Ela tem uma Formação de base e mais três caminhos (Negócios, SaaS e Agentes). Concluir a Carreira inteira em 4 semanas, estudando 1 hora por dia, não seria realista.

O que cabe muito bem nesse prazo é a Formação de base: Inteligência Artificial na Prática. Ela é o ponto de partida recomendado para iniciantes e, segundo a página, não tem pré-requisitos.

E um detalhe legal: o projeto final dessa Formação é configurar e usar o DIO Agent. Ou seja, você já começou! 🎉

📋 Resumo
Base: Formação Inteligência Artificial na Prática (3 módulos, 9 atividades)
Nível: iniciante
Ritmo: 1h por dia, de segunda a sexta (5h por semana, 20h no total)
Duração estimada: a página não mostra a carga horária (o contador aparece como 0). Por isso fiz uma estimativa pela quantidade de atividades, deixando uma folga generosa.
🗓️ Cronograma
Semana 1: Fundamentos

Dia	O que fazer
Seg	Módulo 1, Entendendo a IA Que Você Já Usa, atividade 1
Ter	Módulo 1, atividade 2
Qua	Módulo 1, atividade 3
Qui	Módulo 2, Prompt e Contexto: Pedindo Bem à IA, atividade 1
Sex	Revisão: teste 3 prompts diferentes para uma mesma tarefa sua e compare os resultados
Semana 2: Prática e projeto

Dia	O que fazer
Seg	Módulo 2, atividades 2 e 3
Ter	Módulo 3, Seu Primeiro Assistente e o Próximo Passo, atividade 1
Qua	Módulo 3, atividades 2 e 3
Qui	Projeto final, DIO Agent na Prática: use a skill de plano de estudos (já fizemos isso aqui 😉) e a de destravar desafios
Sex	Projeto final: monte seu plano estratégico de carreira com a skill Caminho AI Builder
Semanas 3 e 4: Primeiro passo no caminho escolhido
Essa parte depende de qual Formação você vai escolher no fim da semana 2. Quando você decidir, eu preencho essas duas semanas com os módulos reais dela.

🏁 Marcos
✅ Fim da semana 1: você explica, com as suas palavras, por que um prompt com contexto funciona melhor.
✅ Fim da semana 2: Formação de base concluída, projeto final entregue e caminho escolhido.
✅ Fim da semana 4: primeiros módulos da Formação escolhida concluídos.
💡 Dica: registre essa rotina na ferramenta Meta de Estudo da DIO, dentro da Formação. Você define os dias e o tempo de estudo, acompanha seu progresso e recebe lembretes por e-mail. Ajuda muito a manter a constância.

Para eu já adiantar as semanas 3 e 4: o que você gostaria de construir com IA? Por exemplo, um produto para um negócio, um software, ou agentes que automatizam tarefas. Se ainda não souber, tudo bem, a semana 2 serve justamente para descobrir isso.

Fontes:

Formação Inteligência Artificial na Prática, DIO


essas foram algumas respostas do dioAgent
