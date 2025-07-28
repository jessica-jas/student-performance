# Análise do Desempenho Escolar - Student Performance

Este projeto analisa o desempenho de estudantes em duas disciplinas — **Matemática** e **Português** — com base na base de dados **[Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)**, amplamente utilizada em estudos de Machine Learning e Data Science.

---

## **1. Sobre o Projeto**
O objetivo deste projeto é:
- Unificar os dois datasets (`student-mat.csv` e `student-por.csv`);
- Realizar uma **análise exploratória de dados (EDA)**;
- Criar **visualizações gráficas** para entender o comportamento dos alunos;
- Identificar os principais fatores que impactam a **nota final (G3)**.

---

## **2. Sobre a Base de Dados**
A base contém dados de estudantes de duas escolas portuguesas. As informações foram obtidas a partir de **boletins escolares** e **questionários**.  
As duas tabelas disponíveis são:
- `student-mat.csv` — desempenho em **Matemática**;
- `student-por.csv` — desempenho em **Português**.

A nota **G3** é a **nota final**, enquanto **G1** e **G2** correspondem ao 1º e 2º períodos.

---

## **3. Dicionário de Variáveis**

**Informações do Aluno:**
- **school** – escola do aluno (`GP`: Gabriel Pereira ou `MS`: Mousinho da Silveira)
- **sex** – sexo do aluno (`F`: feminino ou `M`: masculino)
- **age** – idade do aluno (15 a 22 anos)
- **address** – tipo de endereço (`U`: urbano ou `R`: rural)
- **famsize** – tamanho da família (`LE3`: ≤ 3 ou `GT3`: > 3)
- **Pstatus** – situação de coabitação dos pais (`T`: juntos ou `A`: separados)

**Educação dos Pais:**
- **Medu** – escolaridade da mãe (0: nenhuma, 1: 4ª série, 2: 5ª-9ª, 3: ensino médio, 4: superior)
- **Fedu** – escolaridade do pai (0 a 4, mesma codificação de Medu)
- **Mjob** – profissão da mãe (`teacher`, `health`, `services`, `at_home`, `other`)
- **Fjob** – profissão do pai (`teacher`, `health`, `services`, `at_home`, `other`)

**Aspectos Escolares e Sociais:**
- **reason** – motivo para escolher a escola (`home`, `reputation`, `course`, `other`)
- **guardian** – responsável (`mother`, `father`, `other`)
- **traveltime** – tempo de viagem para escola (1: <15 min a 4: >1 hora)
- **studytime** – tempo semanal de estudo (1: <2h a 4: >10h)
- **failures** – número de reprovações (0 a 4)
- **schoolsup** – apoio educacional extra (`yes` ou `no`)
- **famsup** – apoio da família (`yes` ou `no`)
- **paid** – aulas pagas (`yes` ou `no`)
- **activities** – atividades extracurriculares (`yes` ou `no`)
- **nursery** – frequentou pré-escola (`yes` ou `no`)
- **higher** – deseja ensino superior (`yes` ou `no`)
- **internet** – acesso à internet (`yes` ou `no`)
- **romantic** – relacionamento amoroso (`yes` ou `no`)

**Indicadores de Comportamento:**
- **famrel** – qualidade da relação familiar (1 a 5)
- **freetime** – tempo livre (1 a 5)
- **goout** – sair com amigos (1 a 5)
- **Dalc** – consumo de álcool durante a semana (1 a 5)
- **Walc** – consumo de álcool nos fins de semana (1 a 5)
- **health** – estado de saúde (1 a 5)
- **absences** – número de faltas (0 a 93)

**Notas:**
- **G1** – nota do 1º período (0 a 20)
- **G2** – nota do 2º período (0 a 20)
- **G3** – nota final (0 a 20)

---

