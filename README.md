
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

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.


---

## 💪 Biotipos Corporais

Determine o biotipo corporal do usuário para ajustar o plano de treino conforme as características específicas. Aqui estão os biotipos e suas características:

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
    <td>Corpo mais magro, dificuldade em ganhar peso e massa muscular. O treino deve focar em:
      <ul>
        <li><strong>Volume e Intensidade:</strong> Aumentar o volume e a intensidade para promover o ganho muscular.</li>
        <li><strong>Menos Cardio:</strong> Reduzir o tempo dedicado a exercícios cardiovasculares.</li>
        <li><strong>Exercícios Compostos:</strong> Priorizar exercícios que trabalham vários grupos musculares.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura. O treino deve focar em:
      <ul>
        <li><strong>Equilíbrio:</strong> Manter um equilíbrio entre treino de força e cardio.</li>
        <li><strong>Variedade:</strong> Incluir uma variedade de exercícios e técnicas.</li>
        <li><strong>Treinamento de Alta Intensidade:</strong> Incorporar treinos intervalados e técnicas avançadas.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura e dificuldade em perder peso. O treino deve focar em:
      <ul>
        <li><strong>Cardio Intenso:</strong> Incorporar mais exercícios cardiovasculares e HIIT.</li>
        <li><strong>Treino de Força:</strong> Incluir exercícios de resistência para manter a massa muscular.</li>
        <li><strong>Volume e Frequência:</strong> Aumentar a frequência e o volume de treino.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino <strong>Full Body</strong>            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino <strong>ABC</strong>                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino <strong>ABCDE</strong>                |

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
4. **Ajuste o plano** para alinhar com os objetivos do cliente e seu nível de experiência.
5. **Adapte o treino** conforme limitações físicas e lesões, se houver.
6. **Ajuste o plano** com base nas preferências pessoais e no tempo disponível.
7. **Inclua recomendações** sobre nutrição e recuperação para complementar o treino.
8. **Estabeleça avaliações** regulares e ajuste o plano conforme o progresso do cliente.
9. **Adapte o plano** conforme os equipamentos disponíveis.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

<strong>Biotipo:<br> 
Periodização:<br> 
Tipo de Exercicio:<br> 
Objetivo: <br>
Nível: <br>
Limitações: <br>
Preferências: <br>
Nutrição: <br>
Recuperação: <br>
Equipamentos: <br></strong>

## Regras de Negócio

### <strong>Biotipo</strong>
<strong>Objetivo:</strong> Identificar o tipo corporal do cliente para ajustar o plano de treino de acordo com as características específicas de cada biotipo.<br>

### <strong>Ectomorfo:</strong>
 <strong>Corpo mais magro, dificuldade em ganhar peso e massa muscular.<br>
 O treino deve focar em:</strong><br>

<strong>Volume e Intensidade:</strong> Aumentar o volume de treino (número de séries e repetições) e a intensidade (peso usado) para promover o ganho muscular.
<br>
<strong>Menos Cardio:</strong> Reduzir o tempo dedicado a exercícios cardiovasculares para evitar queima excessiva de calorias.
<br>
<strong>Exercícios Compostos:</strong> Priorizar exercícios compostos (como agachamentos e supinos) que trabalham vários grupos musculares simultaneamente.
<br>

### <strong>Mesomorfo:</strong>
 <strong>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.<br>
O treino deve focar em:</strong><br>

<strong>Equilíbrio:</strong> Manter um equilíbrio entre treino de força e cardio para maximizar os resultados em ambos os aspectos.
<br>
<strong>Variedade:</strong> Incluir uma variedade de exercícios e técnicas para evitar estagnação e promover tanto a hipertrofia quanto a resistência.
<br>
<strong>Treinamento de Alta Intensidade:</strong> Incorporar treinos intervalados e técnicas avançadas para maximizar o desempenho.<br>
	
### <strong>Endomorfo:</strong> 
<strong>Corpo com tendência a acumular gordura e dificuldade em perder peso.<br>
O treino deve focar em:</strong></br>

<strong>Cardio Intenso:</strong> Incorporar mais exercícios cardiovasculares e HIIT para aumentar o gasto calórico e promover a queima de gordura.<br>

<strong>Treino de Força:</strong> Incluir exercícios de resistência para manter a massa muscular e apoiar a queima de gordura.<br>

<strong>Volume e Frequência:</strong> Aumentar a frequência e o volume de treino para maximizar o gasto energético.


 ##  Dias de Treino por Semana

<strong>Objetivo: Definir a estrutura do treino com base na quantidade de dias disponíveis para treinar.<br>
O que adicionar:</strong><br>

<strong>1 Dia - Treino Full Body:</strong><br>
<strong>Estrutura:</strong> Realizar um treino completo que inclua todos os principais grupos musculares.<br>
<strong>Exercícios:</strong> Incluir exercícios compostos como agachamento, levantamento terra e supino.<br>
<strong>Volume e Intensidade:</strong> Manter um volume moderado para evitar sobrecarga.<br>

<strong>3 Dias - Treino ABC:</strong><br>
<strong>Estrutura:</strong> Dividir o treino em três sessões, focando em grupos musculares específicos a cada dia.<br>
<strong>Dia A:</strong> Peito e tríceps<br>
<strong>Dia B:</strong> Costas e bíceps<br>
<strong>Dia C:</strong> Pernas e ombros<br>
<strong>Recuperação:</strong> Garantir um dia de descanso entre treinos para recuperação adequada.<br>

<strong>5 Dias - Treino ABCDE:</strong><br>
<strong>Estrutura:</strong> Dividir o treino em cinco sessões, com foco específico em diferentes grupos musculares.<br>
<strong>Dia A:</strong> Peito<br>
<strong> B:</strong> Costas<br>
<strong>Dia C:</strong> Pernas<br>
<strong>Dia D:</strong> Ombros<br>
<strong>Dia E:</strong> Braços (bíceps e tríceps)<br>

<strong>Recuperação:</strong> Considerar uma estrutura que permita recuperação adequada, possivelmente incluindo um dia de descanso ativo.<br>

 ##  Tipo de Treino
<strong>Objetivo:Selecionar o tipo de treino baseado nas preferências e necessidades do cliente.<br>
O que adicionar:</strong><br>

<strong>Funcional:</strong><br>
<strong>Objetivo:</strong> Melhorar a funcionalidade geral do corpo.<br>
<strong>Exercícios:</strong> Incluir movimentos funcionais como agachamentos, flexões e levantamento de kettlebells.<br>
<strong>Estrutura:</strong> Incorporar exercícios que simulam atividades diárias e melhoram a estabilidade.<br>

<strong>Maquinário:</strong><br>
<strong>Objetivo:</strong> Isolar grupos musculares específicos.<br>
<strong>Exercícios:</strong> Utilizar máquinas como leg press, máquina de peck deck, e extensora de pernas.<br>
<strong>Estrutura:</strong> Focar em exercícios que permitam uma carga controlada e repetitiva.<br>

<strong>Peso Livre:</strong><br>
<strong>Objetivo:</strong> Trabalhar vários grupos musculares simultaneamente.<br>
<strong>Exercícios:</strong> Utilizar halteres, barras e kettlebells para exercícios como supino, agachamento e levantamento terra.<br>
<strong>Estrutura:</strong> Priorizar exercícios que exijam estabilização e coordenação.<br>

<strong>Cardio:</strong><br>
<strong>Objetivo:</strong> Melhorar a resistência cardiovascular.<br>
<strong>Exercícios:</strong> Inclui atividades como corrida, ciclismo ou remo.<br>
<strong>Estrutura:</strong>Alternar entre sessões de cardio de baixa intensidade e alta intensidade.<br>

<strong>HIIT:</strong><br>
<strong>Objetivo: </strong>Promover a queima de gordura e melhorar a capacidade cardiovascular.<br>
<strong>Exercícios:</strong> Alternar entre períodos curtos de exercícios intensos e períodos de descanso.<br>
<strong>Estrutura: </strong>Sessões de 20-30 minutos, incluindo exercícios como burpees, sprints e saltos.<br>


 ## Objetivos do Cliente<br>
<strong>Objetivo: Adaptar o plano de treino para alinhar com os objetivos específicos do cliente.<br>
O que adicionar:</strong>
<br>
<strong>Perda de Peso:</strong><br>
<strong>Estrutura:</strong> Focar em treinos com alta queima calórica, como HIIT e sessões prolongadas de cardio.<br>
<strong>Exercícios:</strong> Incluir movimentos que engajem grandes grupos musculares e aumentem o metabolismo.
<br>
<strong>Ganho de Massa Muscular:</strong><br>
<strong>Estrutura:</strong> Priorizar exercícios de resistência e treinos com pesos livres e máquinas.<br>
<strong>Exercícios:</strong> Focar em exercícios compostos e técnicas avançadas como drop sets e supersets.
<br>
<strong>Aumento de Resistência:</strong><br>
<strong>Estrutura:</strong> Combinar cardio prolongado com treinamento funcional.<br>
<strong>Exercícios: </strong>Incluir exercícios de resistência com altas repetições e períodos mais longos de atividade cardiovascular.
<br>
<strong>Melhoria na Mobilidade e Flexibilidade:</strong><br>
<strong>Estrutura:</strong> Incorporar sessões de alongamento, yoga e exercícios de mobilidade.<br>
<strong>Exercícios:</strong> Focar em movimentos que aumentem a amplitude de movimento e reduzam rigidez.<br>

 ## Histórico de Treinamento<br>
<strong>Objetivo:</strong> Adaptar o plano de treino com base no nível de experiência do cliente.<br>
<strong>O que adicionar:</strong><br>

<strong>Iniciante:</strong><br>
<strong>Estrutura:</strong> Introduzir exercícios básicos e técnicas fundamentais.<br>
<strong>Exercícios:</strong> Incluir exercícios com baixa complexidade e foco em forma correta.
<br>
<strong>Intermediário:</strong><br>
<strong>Estrutura:</strong> Introduzir variações de exercícios e progressões de carga.<br>
<strong>Exercícios:</strong> Incluir uma combinação de exercícios compostos e isolados, com aumento gradual da intensidade.
<br>
<strong>Avançado:</strong><br>
<strong>Estrutura:</strong> Incorporar técnicas avançadas e variações para maximizar os resultados.<br>
<strong>Exercícios:</strong> Utilizar técnicas como supersets, drop sets, e treinamento em pirâmide.<br>

6. ## Limitações Físicas e Lesões<br>
<strong>Objetivo:Ajustar o plano para acomodar limitações físicas e lesões do cliente.<br>
O que adicionar:</strong><br>

<strong>Lesões Recorrentes:</strong><br>
<strong>Estrutura:</strong> Adaptar os exercícios para evitar agravamento da lesão.<br>
<strong>Exercícios:</strong> Incluir exercícios de reabilitação e movimentos modificados que minimizem o impacto na área afetada.
<br>
<strong>Condições Médicas:</strong><br>
<strong>Estrutura: </strong>Ajustar os exercícios conforme as orientações médicas.<br>
<strong>Exercícios:</strong>Incorporar atividades seguras e apropriadas para a condição específica do cliente.<br>

7. ## Preferências Pessoais<br>
<strong>Objetivo: Ajustar o plano para alinhar com as preferências do cliente.<br>
O que adicionar:</strong><br>
<br>
<strong>Preferência por Tipo de Exercício:</strong><br>
<strong>Estrutura: </strong>Aumentar a proporção de exercícios que o cliente gosta.<br>
<strong>Exercícios: </strong>Adaptar o plano para incluir mais dos tipos de exercício preferidos pelo cliente.<br>

<strong>Tempo Disponível:</strong><br>
<strong>Estrutura:</strong> Ajustar a duração e a intensidade dos treinos conforme o tempo disponível do cliente.<br>
<strong>Exercícios:</strong> Criar treinos eficientes e compactos se o tempo for limitado.<br>

8. ## Nutrição e Recuperação<br>
<strong>Objetivo: Complementar o plano de treino com orientações sobre nutrição e recuperação.<br.>
O que adicionar:</strong><br>

<strong>Nutrição:</strong><br>
<strong>Orientações Gerais:</strong> Oferecer recomendações básicas sobre alimentação balanceada para suportar os objetivos do cliente.<br>
<strong>Suplementação:</strong> Considerar sugestões sobre suplementos se apropriado para o objetivo e biotipo.<br>

<strong>Recuperação:</strong><br>
<strong>Estrutura:</strong> Incluir recomendações para recuperação, como alongamentos, massagens e técnicas de relaxamento.<br>
<strong>Sono:</strong> Enfatizar a importância de uma boa qualidade de sono para a recuperação muscular e desempenho.<br>

9. ## Avaliação e Progressão<br>
<strong>Objetivo: Estabelecer critérios para avaliar e ajustar o plano conforme o progresso do cliente.<br>
O que adicionar:</strong><br>

<strong>Avaliações Regulares:</strong><br>
<strong>Estrutura:</strong> Definir pontos de checagem para avaliar o progresso, como testes de força, resistência ou composição corporal.<br>
<strong>Feedback:</strong> Solicitar feedback do cliente sobre o plano e fazer ajustes conforme necessário.
<br>
<strong>Ajustes de Treino:</strong><br>
<strong>Estrutura:</strong> Revisar e ajustar o plano de treino com base nos resultados das avaliações e no progresso observado.<br>
<strong>Meta de Ajuste:</strong> Fazer alterações para manter o desafio e a eficácia do treino.<br>

10. ## Equipamentos Disponíveis<br>
<strong>Objetivo: Adaptar o plano de treino conforme os equipamentos disponíveis para o cliente.<br>
O que adicionar:</strong><br>

<strong>Treino em Casa:</strong><br>
<strong>Estrutura:</strong> Criar planos com exercícios que podem ser feitos com equipamento mínimo ou com o peso do próprio corpo.<br>
<strong>Exercícios:</strong> Utilizar itens domésticos ou equipamentos básicos como halteres, bandas elásticas, e kettlebells.
<br>
<strong>Academia Completa:</strong><br>
<strong>Estrutura:</strong> Aproveitar a variedade de equipamentos disponíveis para um plano mais diversificado.<br>
<strong>Exercícios:</strong> Incluir o uso de máquinas, pesos livres e acessórios variados para um treino completo e bem equilibrados.
<br>

## Resultado Esperado<br>
Com base nas variáveis fornecidas e nas regras de negócio descritas, elabore um plano de treino personalizado que combine o biotipo, a frequência de treino, o tipo de treino, e todos os outros aspectos relevantes. Certifique-se de que o plano seja equilibrado, eficaz e adaptado às necessidades e objetivos específicos do cliente, incluindo detalhes como exercícios específicos, repetições, séries, períodos de descanso, e recomendações adicionais para nutrição e recuperação.

