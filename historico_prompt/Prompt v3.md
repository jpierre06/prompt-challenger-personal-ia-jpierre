# Prompt v3

> # Prompt de Entrada

# Contexto

Você é um especialista personal treiner e vai me ajudar a montar um treino ideal, basedao nas três variáveis abaixo:


# Área de variáveis 

{{biotipo}}

{{periodização}}

{{tipo}}

{{restrição}}


# Regras

Regra 1: biotipo 

Identificar qual o tipo informado nas variáveis acima. Tipo corporal deve ser algum dos itens abaixo:

* 	Biotipo 	= Descrição
-	Ectomorfo 	= Corpo mais magro, difícil ganhar peso e massa muscular.
-	Mesomorfo 	= Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
-	Endomorfo 	= Corpo com tendência a acumular gordura, maior dificuldade em perder peso.


Regra 2: periodização

Dependendo da quantidade mínima de dias informados na área de variáveis, criar umas das periodizações de treino abaixo:

* 	Dias por Semana 	= Tipo de Treino Sugerido
-	1 dia 	= Treino Full Body
-	3 dias 	= Treino ABC
-	5 dias 	= Treino ABCDE


Regra 3: tipo

Definir o tipo de treino definir conforme descrição das atividades abaixo:

* 	Tipo de Treino 	= Descrição
-	Funcional 	= Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
-	Maquinário 	= Exercícios feitos em máquinas, com foco em isolar grupos musculares.
-	Peso Livre 	= Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
-	Cardio 	= Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
-	HIIT 	= Treinos intervalados de alta intensidade, ótimos para queima de gordura.


Regra 4: restrição

Adaptar os exercícios propostos de acordo com as regras de restrições médicas abaixo:

A quarta regra envolve a escolha do tipo de exercício baseado no histórico médico do aluno
*	Tipo de Lesão	= Descrição
-	Sem restrição	= Não tem nenhum tipo de restrição de atiivdade física por questões médicas
-	Lesão no joelho	= Restrição de exercíos que podem prejudicar ou agravar a lesões no joelho
-	Lesão no pé	= Restrição de exercíos que podem prejudicar ou agravar a lesões no pé
-	Lesão no mão	= Restrição de exercíos que podem prejudicar ou agravar a lesões na mão
-	Lesão no cotovelo	= Restrição de exercíos que podem prejudicar ou agravar a lesões no cotovelo
-	Lesão no ombro	= Restrição de exercíos que podem prejudicar ou agravar a lesões no ombro
-	Lesão no quabril	= Restrição de exercíos que podem prejudicar ou agravar a lesões no quabril
-	Problema cardíaco = Restrição de exercíos que podem afetar ou agravar problemas cardíacos


Regra 5: personal

Essa regra define se a pessoa precisa de um personal treiner para acompanhar a execução das atividades, 
ou se a pessoa pode fazer a atividade sozinha sem acompanhamento de personal treiner

Essa regra deve ser inferida a partir das definições das regras anteriores


# Resultado esperado
Com base nos valores informados na área Entrada de variáveis e com as guidelines, 
crie um treino ideal para a pessoa que corresponde a combinação das variáveis, 
caso alguma variável não seja informada, tentar inferir qual seria a melhor opção



# Entrada de variáveis

biotipo = endomorfo

periodização = 3 dias de treino

tipo = Funcional e Cardio

restrição = Lesão no joelho


# Solicitação de prompt

Crie um treino com base no documento anexo e os valores fornecidos na Entrada de Variáveis



> # Texto de Saída

Vou criar um programa de treino incluindo a recomendação sobre acompanhamento profissional:

**Análise Completa do Perfil:**
- Biotipo Endomorfo: Foco em metabolismo e queima de gordura
- Periodização ABC (3x semana)
- Tipo: Combinação de Funcional e Cardio
- Restrição: Lesão no joelho
- Personal: RECOMENDADO - devido à combinação de:
  1. Lesão no joelho (requer supervisão técnica)
  2. Exercícios funcionais (necessita correção postural)
  3. Biotipo endomorfo (precisa otimização de intensidade)

**Programa de Treino Semanal:**

TREINO A (Segunda-feira) - Membros Superiores e Core
1. Aquecimento (10 min) - Supervisionado:
   - Bicicleta estacionária (resistência controlada)
   - Mobilidade articular guiada

2. Circuito Funcional (4 rounds) - Supervisão Necessária:
   - Remada com elástico em pé (15 reps)
   * Atenção à postura e ativação do core
   - Push-ups modificados (12 reps)
   * Correção do alinhamento corporal
   - Rotação de tronco com elástico (15 cada)
   * Controle do movimento e respiração
   - Bird dog (12 cada lado)
   * Estabilização lombar
   - Prancha (30 segundos)
   * Alinhamento neutro da coluna

3. Cardio Low Impact (15 min):
   - Bicicleta estacionária intervalada
   * Monitoramento cardíaco e biomecânico

TREINO B (Quarta-feira) - Membros Inferiores Adaptado
1. Aquecimento (10 min) - Supervisionado:
   - Elíptico com técnica guiada
   - Mobilidade de quadril específica

2. Circuito Funcional (4 rounds) - Supervisão Crítica:
   - Ponte de glúteos (15 reps)
   * Ativação correta dos glúteos
   - Abdução de quadril deitado (15 cada)
   * Alinhamento pélvico
   - Extensão de quadril em 4 apoios (12 cada)
   * Controle da lombar
   - Isometria parcial (30 segundos)
   * Proteção do joelho lesionado
   - Core com bola (30 segundos)
   * Estabilização do tronco

3. Cardio Adaptado (20 min):
   - Remo com técnica monitorada

TREINO C (Sexta-feira) - Full Body Adaptado
1. Aquecimento (10 min) - Supervisionado:
   - Mobilidade global guiada
   - Ativação muscular progressiva

2. Circuito Funcional (4 rounds) - Supervisão Necessária:
   - Puxada com elástico (12 reps)
   * Controle escapular
   - Elevação lateral guiada (15 reps)
   * Ritmo escapulo-umeral
   - Dead bug modificado (15 cada)
   * Controle da pelve
   - Extensão de quadril máquina (12 reps)
   * Ajuste biomecânico
   - Prancha lateral modificada (30 segundos)
   * Progressão adequada

**Justificativa para Acompanhamento Profissional:**
1. Segurança:
   - Monitoramento da lesão no joelho
   - Adaptação correta dos exercícios
   - Prevenção de compensações

2. Eficiência:
   - Ajuste preciso de cargas
   - Correção técnica imediata
   - Progressão individualizada

3. Motivação:
   - Feedback constante
   - Ajuste de intensidade
   - Suporte técnico-emocional

**Recomendações para Execução:**
1. Início com Personal 3x/semana
2. Reavaliação após 8 semanas
3. Possível redução para 2x/semana após adaptação
4. Nunca executar exercícios novos sem supervisão

**Progressão com Acompanhamento:**
- Semanas 1-2: Aprendizado técnico
- Semanas 3-4: Aumento gradual de carga
- Semanas 5-6: Incremento de complexidade
- Semanas 7-8: Avaliação de autonomia

Deseja algum esclarecimento sobre o programa ou sobre a necessidade do acompanhamento profissional?
