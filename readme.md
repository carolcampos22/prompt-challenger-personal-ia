<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto - Exemplo
Com os valores de variáveis a seguir:


- Biotipo: Endomorfo
- Periodização: 3 dias (Treino ABC)
- Tipo: Cardio
- Experiência: Iniciante
- Objetivo: Perda de Gordura
- Disponibilidade: Média Duração (45-60 min)
- Estilo: Sedentário
- Peso Atual: 75 kg
- Peso Desejado: 60 kg
- Tempo para Atingir o Peso: 1 ano

foi proposto o seguinte treino:

# Treino ABC (Cardio)

## Dia A: Cardio de Intensidade Moderada

- Aquecimento: Caminhada rápida (10 min)
- Treino Principal:
- Corrida leve (20 min) ou elíptico (20 min)
- Ciclismo moderado (20 min)
- Resfriamento: Caminhada leve (10 min)
- Alongamento: Alongamento estático para membros inferiores e superiores (5 min)

## Dia B: Cardio com Enfoque em HIIT Leve

- Aquecimento: Caminhada rápida (10 min)
- Treino Principal:
- 5 ciclos de 1 min de corrida rápida alternado com 2 min de caminhada leve (25 min no total)
- Resfriamento: Caminhada leve (10 min)
- Alongamento: Alongamento estático para membros inferiores e superiores (5 min)

## Dia C: Cardio de Baixa Intensidade com Movimentos Funcionais

- Aquecimento: Caminhada rápida (10 min)
- Treino Principal:
- Caminhada inclinada (20 min)
- Exercícios funcionais: Polichinelo (3x15), Step-up em banco (3x15)
- Resfriamento: Caminhada leve (10 min)
- Alongamento: Alongamento estático para membros inferiores e superiores (5 min)

## Dicas de Alimentação
- Controle de Porções: Divida suas refeições em 5-6 pequenas porções ao longo do dia para manter o metabolismo ativo.
- Priorize Proteínas Magras: Consuma frango, peixe, ovos e leguminosas para ajudar na manutenção da massa magra enquanto perde gordura.
- Fibras e Vegetais: Aumente a ingestão de vegetais e alimentos ricos em fibras para melhorar a saciedade e regular a digestão.
- Redução de Carboidratos Simples: Evite açúcares refinados e alimentos ultraprocessados. Prefira carboidratos complexos como batata-doce, arroz integral e aveia.

## Quantidade Mínima Diária de Ingestão de Líquidos
Para manter-se hidratada, especialmente durante o processo de perda de peso e com a prática de exercícios, recomenda-se uma ingestão mínima de 2,5 a 3 litros de água por dia. Beba água antes, durante e após os treinos.

## Considerações Finais
- Como iniciante, priorize a correta execução dos movimentos e mantenha um ritmo confortável. O objetivo é criar uma base sólida e evitar lesões.
- A consistência será fundamental para atingir seu peso desejado em um ano. Combine o treino com uma alimentação balanceada e evite pular refeições.
- Integre mais atividades físicas no dia a dia para reduzir o sedentarismo, como caminhar mais e usar escadas em vez de elevadores.

Esse plano equilibrado ajudará a atingir seus objetivos de perda de gordura de forma sustentável e saudável.