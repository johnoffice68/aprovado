- Mostre as informações apenas dos alunos aprovados. A aprovação é acima de 7,0;
σ(NOTA > 7.0)(ALUNO)
- Exiba as informações dos alunos do primeiro ano com nota maior ou igual a 8,0;
σ(SERIE = '1 ANO' AND NOTA >= 8.0)(ALUNO)
- Exiba apenas os nomes e as notas dos alunos;
π(P_NOME, NOTA)(ALUNO)


- Crie uma tabela PROFESSOR que apresente apenas o primeiro e o último nome do professor;

π(NOME, SOBRENOME)(PROFESSOR)
- Crie uma tabela ALUNO com o primeiro e o último nome de cada;
π(P_NOME, U_NOME)(ALUNO)


- Mostre o resultado da união entre a tabela ALUNO(PNome, UNome) e a tabela PROFESSOR;




- Exiba o resultado da intersecção entre a tabela ALUNO(PNome, UNome) e a tabela PROFESSOR;
- Exiba o resultado da diferença entre a tabela ALUNO(PNome, UNome) e a tabela PROFESSOR. 
