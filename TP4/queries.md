## Relational Algebra Queries

**1.** `π nr Aluno`

**2.** `π cod,design (σ curso = 'AC' Cadeira)`

**3.** `(π Nome Aluno) ∩ (π Nome Prof)`

**4.** `(π Nome Aluno) - (π Nome Prof)`

**5.** `(π Nome Aluno) ∪ (π Nome Prof)`

**6.** `π Nome (σ cod='TS1' (Aluno ⨝ Prova))`

**7.** `π Nome (σ curso='IS' ((Aluno ⨝ Prova) ⨝ Cadeira))`

**8.**  `(π Nome, cod (Aluno ⨝ σ nota ≥ 10 Prova)) ÷ (π cod σ curso='IS' Cadeira)`

**9.** `γ max(nota) -> notaMax Prova`

**10.** `γ avg(nota) -> notaMed (σ cod='BD' Prova)`

**11.** `γ count(nr) -> numAlunos Aluno`

**12.** `γ curso; count(cod) -> nr Cadeira`

**13.** `γ nr; count(*) -> provas Prova`

**14.** `γ avg(provas) -> medProvas γ nr; count(*) -> provas Prova`

**15.** `π Nome, media (γ nr; avg(nota) -> media Prova ⨝ Aluno)`

**16.** `π cod, nota, Nome (γ cod; max(nota) -> nota Prova ⨝ Prova ⨝ Aluno)`

**17.**