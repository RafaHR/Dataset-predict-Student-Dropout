# Dataset-predict-Student-Dropout

O projeto consiste no desenvolvimento de modelos preditivos de classificação para buscar encontrar padrões e conseguir predizer se um determinado aluno irá se graduar, trancar a matéria da faculdade ou abandonar o curso.

Utilizaremos um dataset fornecido pelo Kaggle, que pode ser encontrado atráves desse link: [Predict Students Dropout and Academic Success](https://www.kaggle.com/datasets/syedfaizanalii/predict-students-dropout-and-academic-success)

O esqueleto do projeto consiste em primeiro:
- Obter os dados
- Realizar o pré-processamento
- Fazer a primeira análise exploratória, buscando entender alguns padrões manualmente
- Aplicação do modelo de Machine Learning (Redes Neurais, KNN e Naive Bayes)
- Otimização do modelo com base na análise exploratória e ajustes de Parâmetros.

---

Resumo do Dataset:


Esse Dataset consiste em procurar padrões entre a taxa de sucesso e de abandono do curso de várias instituições de ensino superior em diversos cursos. O conjunto de dados inclui informações conhecidas no momento da matrícula do estudante (trajetória acadêmica, dados demográficos e fatores socioeconômicos) e o desempenho acadêmico dos estudantes ao final do primeiro e segundo semestres.

O Dataset possue cerca de 4424 dados de alunos com 37 colunas, sendo elas:

- Marital status
- Application mode
- Application order
- Course
- Daytime/evening attendance
- Previous qualification
- Previous qualification (grade)
- Nationality
- Mother's qualification
- Father's qualification
- Mother's occupation
- Father's occupation
- Admission grade
- Displaced
- Educational special needs
- Debtor
- Tuition fees up to date
- Gender
- Scholarship holder
- Age at enrollment
- International
- Curricular units 1st sem (credited)
- Curricular units 1st sem (enrolled)
- Curricular units 1st sem (evaluations)
- Curricular units 1st sem (approved)
- Curricular units 1st sem (grade)
- Curricular units 1st sem (without evaluations)
- Curricular units 2nd sem (credited)
- Curricular units 2nd sem (enrolled)
- Curricular units 2nd sem (evaluations)
- Curricular units 2nd sem (approved)
- Curricular units 2nd sem (grade)
- Curricular units 2nd sem (without evaluations)
- Unemployment rate
- Inflation rate
- GDP
- Target

Algumas colunas possuem o número de identificação de um curso, como, por exemplo, 9119 → Informatics Engineering
Por conta disso, é importante verificar na documentação oficial do Dataset, onde estão disponíveis todas as informações necessárias, principalmente sobre o que cada coluna, cada dado, representa.

[Predict Students' Dropout and Academic Success - UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)
