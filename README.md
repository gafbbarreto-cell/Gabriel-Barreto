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
