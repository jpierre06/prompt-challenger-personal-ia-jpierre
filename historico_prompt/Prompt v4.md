# Prompt v1

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

restrição = Sem restrição


# Solicitação de prompt

Crie um treino com base no documento anexo e os valores fornecidos na Entrada de Variáveis



> # Texto de Saída

Vou adaptar o programa de treino considerando a ausência de restrições médicas, mantendo o foco no biotipo endomorfo e maximizando a queima calórica:

**Análise do Perfil:**
- Biotipo Endomorfo: Foco em metabolismo e queima de gordura
- Periodização ABC (3x semana)
- Tipo: Combinação de Funcional e Cardio
- Restrição: Sem restrições
- Personal: RECOMENDADO INICIALMENTE - devido a:
  1. Exercícios funcionais complexos
  2. Necessidade de controle de intensidade
  3. Aprendizagem correta dos movimentos

**Programa de Treino Semanal:**

TREINO A (Segunda-feira) - Full Body + Cardio
1. Aquecimento (10 min):
   - Pular corda (3 min)
   - Polichinelos (2 min)
   - Mobilidade dinâmica (5 min)

2. Circuito Funcional (4 rounds):
   - Burpees (12 reps)
   - Thruster com halter (15 reps)
   - Mountain climbers (30 segundos)
   - Battle rope (45 segundos)
   - Wall ball (15 reps)
   
3. HIIT Final (15 min):
   - 30 segundos sprint na esteira
   - 30 segundos recuperação ativa

TREINO B (Quarta-feira) - Força + Condicionamento
1. Aquecimento (10 min):
   - Corrida leve
   - Exercícios de mobilidade

2. Circuito Força (4 rounds):
   - Agachamento com salto (15 reps)
   - Push-ups (12 reps)
   - Box jump (10 reps)
   - Remada com TRX (15 reps)
   - Turkish get-up (5 cada lado)

3. Cardio (20 min):
   - Revezamento entre:
     * Remo (2 min)
     * Bike (2 min)
     * Elíptico (2 min)

TREINO C (Sexta-feira) - Potência + Resistência
1. Aquecimento (10 min):
   - Jump rope duplo
   - Alongamento dinâmico

2. Circuito HIIT (5 rounds):
   - Kettlebell swing (20 reps)
   - Jumping lunges (12 cada perna)
   - Pull-ups ou remada invertida (10 reps)
   - Medicine ball slam (15 reps)
   - Prancha com shoulder tap (40 segundos)

3. Finalização (15 min):
   - Tabata:
     * 20s trabalho/10s descanso
     * Alternando entre burpees e mountain climbers

**Intensidade e Progressão:**
1. Fase Inicial (2 semanas):
   - Foco na técnica
   - Intensidade moderada
   - Personal obrigatório

2. Fase Intermediária (3-6 semanas):
   - Aumento progressivo de carga
   - Incremento de velocidade
   - Personal recomendado

3. Fase Avançada (7+ semanas):
   - Máxima intensidade
   - Complexidade total
   - Personal opcional

**Recomendações:**
1. Intervalos:
   - Entre exercícios: 30 segundos
   - Entre circuitos: 2 minutos
   
2. Hidratação:
   - 500ml antes do treino
   - 200ml a cada 15 minutos

3. Monitoramento:
   - Frequência cardíaca
   - Percepção de esforço (manter entre 7-8/10)

4. Progressão Sugerida:
   - Aumentar repetições a cada 2 semanas
   - Reduzir intervalos gradualmente
   - Incrementar complexidade dos movimentos

**Observações sobre Autonomia:**
1. Primeiras 4 semanas:
   - Acompanhamento profissional recomendado
   - Aprendizado dos movimentos
   - Estabelecimento de intensidade adequada

2. Após adaptação:
   - Possibilidade de treinos independentes
   - Check-ups periódicos
   - Ajustes de programa a cada 8 semanas

Gostaria de algum ajuste no programa ou esclarecimento sobre os exercícios propostos?
