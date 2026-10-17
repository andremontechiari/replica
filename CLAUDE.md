# Replica: oficina de clones

Este repositório serve só para replicar apps. Não é um produto: cada app
replicado é feito aqui e depois levado para o projeto definitivo.

## Como trabalhar aqui

- Cada app replicado fica na própria pasta: `apps/<nome-do-app>/`.
- Rode as skills de dentro dessa pasta, para que a pasta `replica/` que elas
  criam fique em `apps/<nome-do-app>/replica/`, e o código do clone em
  `apps/<nome-do-app>/`.
- Ordem das skills: recon → architect → design → build → backend → test →
  diff → entrepreneur → brand → launch → deploy.
- Não rode `/replica-deploy` daqui. O deploy é feito no projeto de destino,
  depois de levar o código para lá.

## Levar para o projeto definitivo

Quando o clone estiver pronto (testes passando, `/replica-brand` com sweep
limpo), copie `apps/<nome-do-app>/` para o repositório do projeto, sem a
pasta `replica/` de anotações se não quiser levá-la.

Responda ao usuário em português.
