# Prompt v2

> # Prompt de Entrada

# Contexto

Você é um especialista personal treiner e vai me ajudar a montar um treino ideal, baseado nas variáveis abaixo:


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

Vou adaptar o programa de treino considerando especialmente a restrição do joelho, mantendo o foco no seu biotipo e objetivos:

**Análise do Perfil Atualizado:**
- Biotipo Endomorfo: Foco em aumentar metabolismo e queima de gordura
- Periodização ABC (3x semana)
- Tipo: Combinação de Funcional e Cardio
- Restrição: Lesão no joelho - Evitaremos impacto e sobrecarga no joelho

**Programa de Treino Semanal Adaptado:**

TREINO A (Segunda-feira) - Membros Superiores e Core
1. Aquecimento (10 min):
   - Bicicleta estacionária (baixa resistência)
   - Mobilidade de membros superiores
   
2. Circuito Funcional (4 rounds):
   - Remada em pé com elástico (15 reps)
   - Push-ups na parede ou bancada (12 reps)
   - Rotação de tronco com elástico (15 cada lado)
   - Elevação lateral de braços (12 reps)
   - Prancha (30 segundos)

3. Cardio Low Impact (15 min):
   - Bicicleta estacionária intervalada
   - 2 min ritmo moderado / 1 min ritmo acelerado

TREINO B (Quarta-feira) - Membros Inferiores Adaptado
1. Aquecimento (10 min):
   - Elíptico suave
   - Mobilidade de quadril

2. Circuito Funcional (4 rounds):
   - Ponte de glúteos (15 reps)
   - Abdução de quadril com elástico (15 cada lado)
   - Extensão de quadril em 4 apoios (12 cada lado)
   - Isometria na parede (30 segundos)
   - Prancha lateral (20 segundos cada lado)

3. Cardio Adaptado (20 min):
   - Remo ergômetro em intensidade moderada

TREINO C (Sexta-feira) - Full Body Adaptado
1. Aquecimento (10 min):
   - Bicicleta estacionária
   - Mobilidade geral sem impacto

2. Circuito Funcional (4 rounds):
   - Elevação frontal com halter (12 reps)
   - Remada baixa com elástico (15 reps)
   - Dead bug (15 reps cada lado)
   - Extensão de quadril na máquina (12 reps)
   - Prancha com apoio de antebraço (45 segundos)

3. Cardio Final (15 min):
   - Alternância entre bicicleta e elíptico

**Recomendações Especiais:**
1. EVITAR:
   - Agachamentos profundos
   - Exercícios com impacto
   - Saltos
   - Corrida
   
2. PRIORIZAR:
   - Exercícios em cadeia cinética aberta
   - Movimentos controlados
   - Fortalecimento do quadríceps e posteriores
   - Cardio sem impacto

**Orientações Adicionais:**
1. Descanso entre circuitos: 2-3 minutos
2. Hidratação constante
3. Sempre respeitar a dor
4. Intensidade: 6-7/10 na escala de esforço
5. Tempo total por treino: 45-50 minutos

**Progressão Sugerida:**
- Semanas 1-2: Foco em técnica e adaptação
- Semanas 3-4: Aumento gradual de carga
- Semanas 5-6: Incremento no tempo sob tensão
- Semanas 7-8: Aumento de volume

Gostaria de algum ajuste específico ou tem alguma dúvida sobre os exercícios adaptados para sua condição?
