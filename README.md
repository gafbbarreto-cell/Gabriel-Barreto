# Minhas Candidaturas

Aplicativo simples para acompanhar o andamento das candidaturas a vagas.

Para cada candidatura você registra:

- **Empresa**
- **Vaga**
- **Status** do processo seletivo (Aplicado, Em análise, Entrevista, Teste / Case, Oferta, Recusado, Desisti)
- **Próximos passos**
- **Faixa de remuneração**
- **Nota no Bússola de Carreira** (0 a 5)
- **Descrição da vaga** e **descrição da empresa**

## Como usar

Abra o arquivo `index.html` no navegador. Não precisa instalar nada.

- Preencha o formulário e clique em **Adicionar**.
- Use **Editar** para atualizar o status ou os próximos passos.
- Filtre a lista por status.

## Onde os dados ficam

Os dados ficam salvos no próprio navegador (`localStorage`). Por isso:

- Eles só aparecem no mesmo navegador e computador onde foram cadastrados.
- Limpar os dados do navegador apaga a lista.

Use **Exportar backup** de vez em quando para baixar um arquivo `.json`, e **Importar backup** para restaurar ou levar a lista para outro computador.

A importação nunca apaga nada da lista atual:

- Candidatura do mesmo backup (mesmo identificador): é substituída pela versão do arquivo.
- Mesma empresa vinda de outra fonte (ex.: dados do Bússola de Carreira): só os campos vazios são preenchidos; status e próximos passos que você já escreveu ficam como estão.
- Empresa nova: é adicionada.

---

# Meus Treinos

Versão da aba **Treinos** da planilha Sports para acompanhar os treinos da semana. Abra `treinos.html` no navegador (ou clique em **Meus Treinos** na página de candidaturas).

- **Montar a semana:** começa a partir da Semana Ideal, repetindo a última semana, ou em branco. Adicione (`+ treino`) ou remova (`×`) treinos em qualquer dia.
- **Dar check:** marque o treino quando fizer (vira 👊🏻).
- **O que falta fazer:** lista os pendentes separados em *Atrasados*, *Hoje* e *Próximos dias*.
- **Resumo:** feitos / planejados no total e por tipo (Academia, Tênis, Aeróbico), como o quadro Treinos/Semana.
- **Concluir semana:** guarda a semana no histórico (o que não foi feito fica registrado) e já abre a montagem da semana seguinte.
- **Semana Ideal:** edite o modelo (um treino por linha em cada dia).
- **Copiar para a planilha:** copia a semana no mesmo formato da aba Treinos (Semana dd/mm, Treino 1, Treino 2, com 👊🏻) para colar no Excel/Sheets.

Na primeira vez a página já vem com a Semana Ideal e as semanas 28/09 e 05/10 da planilha. Os dados ficam no navegador, como nas candidaturas. Para não perder ou levar para outro aparelho, use **Copiar backup** (copia um texto para guardar numa nota ou e-mail) e **Colar backup** para restaurar, ou **Exportar/Importar backup** com arquivo `.json`.
