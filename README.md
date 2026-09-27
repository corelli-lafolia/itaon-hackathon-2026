# ItaOn · assistente financeiro para o primeiro salário

> **Protótipo de hackathon.** Exercício desenvolvido no Hackathon Itaú, Case A: Primeira vida financeira. **Não é um produto oficial do Itaú.** Todos os dados são fictícios.

## Acesse o protótipo

**👉 [Abrir o protótipo](https://SEU-USUARIO.github.io/itaon-hackathon/)**

- Funciona no celular e no computador, sem instalar nada.
- Para a melhor experiência, abra no **Chrome** (Android ou computador) ou no **Safari** (iPhone).
- Para usar o **microfone**, abra sempre pelo link acima (https). Se você baixar o arquivo e abri-lo direto, o navegador bloqueia o microfone.


---

## O problema

**Quem:** jovens de 18 a 24 anos no primeiro emprego (CLT ou estágio), com conta-salário aberta pela empresa.

**A dor:** o salário cai na conta e a pessoa vê só o valor total. Ela não sabe quanto já está comprometido com fatura, contas fixas e ajuda em casa. Muitas vezes transfere tudo para outro banco no mesmo dia e só descobre no meio do mês que o dinheiro não dá.

**Nossa frase-guia:**
> Queremos ajudar **o jovem no primeiro emprego** a **saber quanto do salário está livre de verdade**, **quando o salário cai na conta**, porque hoje **ele vê só o valor total e descobre os compromissos ao longo do mês**. Saberemos que ajudamos se **ele consegue dizer, em menos de 2 minutos, quanto pode gastar por dia até o próximo pagamento**.

## A solução

O **ItaOn** é um assistente dentro do app que entra em ação no **dia do salário**.

1. **Aviso:** "Seu salário de R$ 2.100 caiu! Vamos organizar o seu dinheiro?"
2. **Contas do mês:** a pessoa **escreve ou fala** as contas do jeito dela, por exemplo *"pago 90 de internet, dou 400 pra minha mãe, fatura de uns 600"*.
3. **Conferência:** o ItaOn transforma o texto em itens, e a pessoa **confere e corrige** cada um. Valores aproximados ("uns 600") vêm marcados para revisão.
4. **Distribuição:** um gráfico mostra para onde vai o salário. Se sobrar dinheiro, o ItaOn sugere **investir uma parte**. A pessoa escolhe quanto, com um controle deslizante, e o prazo de resgate (rápido, médio ou longo). Também pode guardar para um objetivo pessoal, como uma bicicleta nova.
5. **Resultado:** **"Você pode gastar R$ 30 por dia até 05/11."**
6. **Motivo para voltar:** o plano fica na tela inicial, junto com o painel **"Para onde vai seu dinheiro"** (gastos por área: iFood, Uber, mercado...). No próximo salário, as contas já vêm preenchidas.

## Como testar (2 minutos)

**Tarefa:** *"O salário do Cláudio, de R$ 2.100, caiu. Descubra quanto ele pode gastar por dia até o próximo pagamento."*

1. Toque em **"Vamos organizar o seu dinheiro?"**.
2. Informe as contas de um destes jeitos:
   - toque em **"Usar exemplo"**;
   - toque em **"Simular áudio"**;
   - fale no **microfone**, por exemplo *"pago noventa de internet, dou quatrocentos pra minha mãe e a fatura deu uns seiscentos"*;
   - ou digite.
3. Confira os itens e toque em **"Está certo, continuar"**.
4. Na janela de investimento, escolha um valor ou toque em **"Agora não"**.
5. Veja o resultado. Com R$ 100 investidos, dá **R$ 30/dia**. Sem investir, dá **R$ 33/dia**.

**Dados de demonstração:** Cláudio, 20 anos, salário de R$ 2.100, contas de R$ 1.090 (internet R$ 90, ajuda em casa R$ 400, fatura R$ 600) e próximo pagamento em 05/11.

**Dicas sobre a voz:**
- Na primeira vez, o navegador pede permissão para usar o microfone. Toque em **Permitir**.
- Se a voz do navegador não funcionar, o protótipo oferece o **ditado do teclado**, que funciona em qualquer navegador:
  - **Android:** microfone do teclado, em cima;
  - **iPhone:** microfone do teclado, embaixo;
  - **Windows:** Windows + H;
  - **Mac:** tecla Fn duas vezes.
- Para investigar problemas, abra o link com **`?debug=1`** no fim. Um painel mostra o que o navegador respondeu.


## Próximos passos

1. Trocar a interpretação simulada por um **modelo de linguagem real**, chamado por um backend (sem chaves no navegador).
2. Usar os **dados reais** do extrato e do cartão, com consentimento do cliente.
3. Rodar um **piloto** com um grupo de controle para medir o efeito.
4. Explorar: início que se adapta ao uso, conexão com produtos que o banco já tem (como limite garantido por investimento) e parcerias, sempre como opção e nunca como empurrão.


---

*Exercício fictício desenvolvido no hackathon. Não é um comunicado ou produto oficial do Itaú. Não use dados reais no protótipo.*

Tudo em HTML, CSS e JavaScript puros, sem dependências nem instalação.