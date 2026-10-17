# replica

Oficina separada para replicar apps com as 11 skills do
[replica-skill](https://github.com/Jakeschincariol/replica-skill) (MIT,
licença em `LICENSE-replica-skill`).

As skills estão em `.claude/skills/`, então qualquer sessão do Claude Code
aberta neste repositório já tem `/replica-recon`, `/replica-build` etc.

Fluxo:

1. Abra uma sessão neste repositório e peça: "replicar o app X em apps/x".
2. Rode as skills em ordem (veja `CLAUDE.md`).
3. Com o clone pronto, copie `apps/x/` para o seu projeto.
