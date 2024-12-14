# MVP_-Machine_Learning_Analytics-
MVP Machine Learning & Analytics Hugo Figueiredo

Link Google Colab: https://colab.research.google.com/drive/1BXu-QQrtq325Yj33oVG7I7ZX4R_pvRCX?usp=sharing

Link Base de dados: https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset/data?select=Student_performance_data+_.csv


Para esse problema, será utilizada a base de dados "Student_performance_data" que contem infomaçõessobre 2392 estudantes do ensino médio. A base traz dados demográficos, hábitos de estudos, envolvimento dos pais, atividades extra-curriculares e desempenho acadêmico. A variável alvo desse problema será a "GradeClass", que tras as notas dos alunos em diferentes categorias (A,B,C,D e F)

O objetivo do problema é criar um modelo de classificação capaz de prever a nota que um aluno pode receber a partir dos dados demográficos, hábitos de estudos, envolvimento dos pais, atividades extra-curriculares e desempenho acadêmico

Descrição das variáveis:

1 - StudentID : Um identificador exclusivo atribuído a cada aluno (1001 a 3392).

2- Idade : A idade dos alunos varia de 15 a 18 anos.

3- Gênero : Gênero dos alunos, onde 0 representa Masculino e 1 representa Feminino.

4- Etnia : A etnia dos alunos, codificada da seguinte forma: 0: Caucasian; 1: Afro-americano; 2: Asiático; 3: Outro

5- ParentalEducation : O nível de educação dos pais, codificado da seguinte forma: 0: Nenhum; 1: Ensino Médio; 2: Alguma faculdade; 3: Bacharel; 4: Superior

6- StudyTimeWeekly : Tempo de estudo semanal em horas, variando de 0 a 20.

7- Ausências : Número de faltas durante o ano letivo, variando de 0 a 30.

8- Tutoria : Status de tutoria, onde 0 indica Não e 1 indica Sim.

9- ParentalSupport : O nível de apoio parental, codificado da seguinte forma: 0: Nenhum; 1: Baixo; 2: Moderado; 3: Alto ;4: Muito alto

10- Atividades extracurriculares Extracurricular : Participação em atividades extracurriculares, onde 0 indica Não e 1 indica Sim.

11- Esportes : Participação em esportes, onde 0 indica Não e 1 indica Sim.

12- Música : Participação em atividades musicais, onde 0 indica Não e 1 indica Sim.

13- Voluntariado : Participação em voluntariado, onde 0 indica Não e 1 indica Sim.

14- GPA : Média de notas em uma escala de 2,0 a 4,0, influenciada por hábitos de estudo, envolvimento dos pais e atividades extracurriculares.

15- GradeClass : Classificação das notas dos alunos com base no GPA: 0: 'A' (GPA >= 3,5) 1: 'B' (3,0 <= GPA < 3,5) 2: 'C' (2,5 <= GPA < 3,0) 3: 'D' (2,0 <= GPA < 2,5) 4: 'F' (GPA < 2,0)
