# AGENTS.md — Perfil da organização Dallo Participações

## Escopo deste repositório público

O repositório especial `.github` mantém o **perfil público da organização** em `profile/README.md` e seus assets. Não é o código-fonte dos sistemas da Dallo.

- Estas instruções se aplicam a **este repositório**. O `AGENTS.md` da organização não substitui automaticamente o `AGENTS.md` de cada aplicativo; cada repositório deve manter suas regras técnicas.
- Consulte `profile/README.md` e a estrutura de assets antes de alterar o perfil; preserve links, identidade visual, acessibilidade e clareza da comunicação institucional.
- Alterações de branding, marcas, informações comerciais e links externos devem respeitar o conteúdo efetivamente aprovado. Não invente capacidades, prazos, métricas, parcerias ou contatos.
- Este repositório é **público**: não publique caminhos internos, nomes de colaboradores em contextos privados, chamados internos, credenciais, infraestrutura, fontes fechadas ou detalhes de segurança dos sistemas.
- Não introduza scripts, automações, workflows ou publicação de outros projetos apenas para atualizar o perfil.
- Validação: confira Markdown, links, assets e visual do perfil. Não há suíte de testes ou deploy da aplicação definidos aqui.

## Padrão Dallo de colaboração e rastreabilidade

- Trabalhe em branch específica para uma mudança; prefira PR para `main`. Não faça merge, force-push, exclusão de branches, release ou deploy sem pedido explícito.
- Use Conventional Commits (por exemplo, `docs(agents): ...`, `feat(...): ...`, `fix(...): ...`) e mantenha o escopo pequeno.
- Antes de editar, leia os arquivos reais do projeto e confira o diff. Nunca copie comandos, stacks, políticas de release ou caminhos de outro repositório sem confirmar que existem aqui.
- Issues: títulos curtos e orientados à ação, em pt-BR, **sem prefixar nome do repositório ou setor**. Use labels para departamentos/módulos e reaproveite as categorias já cadastradas.
- Assignee deve ser definido quando o responsável for conhecido. Para sub-issues, mantenha o responsável da issue principal, salvo definição diferente; não atribua pessoas por adivinhação.
- Preserve Type, Priority, Effort, labels, responsáveis, milestone e estado ao editar issues. Campos indisponíveis via integração devem ser informados como pendentes, nunca simulados no corpo.
- Vincule demandas ao chamado de origem quando houver, indique contexto, requisitos, critérios verificáveis em checklist, dependências e questões abertas. Chamado fechado não prova funcionalidade entregue.
- Prefira sub-issues nativas quando disponíveis; caso contrário, use referências `#N` e checklist na issue principal, esclarecendo que não há vínculo nativo.
- No PR, explique motivação, alterações, impacto, validação, riscos/rollback e vínculo com a issue. Use `Closes #N` somente se os critérios de aceitação foram integralmente atendidos; caso contrário, `Refs #N`.
- Nunca inclua segredos, tokens, arquivos `.env` reais, dumps, dados pessoais ou registros empresariais sensíveis no código, issues, PRs ou logs.
- Consulte os workflows antes de publicar: mudanças só em documentação **podem** disparar CI/build/deploy; não pressuponha filtros como `paths-ignore`.
- Ao finalizar, relate o que mudou, o que foi efetivamente testado, pendências, branch e PR. Não declare testes/deploy que não foram executados.
