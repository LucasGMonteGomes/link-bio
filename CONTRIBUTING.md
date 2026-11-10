# Contribuindo

Obrigado por considerar uma contribuição para o LinkBio! Sugestões, correções e melhorias são bem-vindas.

## Antes de começar

- Confira se já existe uma issue sobre a alteração proposta.
- Para mudanças maiores, abra uma issue antes para alinhar a ideia.
- Para mudanças de conteúdo, links ou aparência, explique o objetivo da alteração.

## Fluxo de contribuição

1. Faça um fork do repositório e clone-o:

   ```bash
   git clone https://github.com/LucasGMonteGomes/link-bio.git
   cd link-bio
   ```

2. Crie uma branch com um nome descritivo:

   ```bash
   git checkout -b melhoria/descricao-curta
   ```

3. Faça alterações pequenas e focadas, seguindo a estrutura e o estilo existentes.
4. Instale as dependências e execute o site localmente:

   ```bash
   npm install
   npm run dev
   ```

5. Verifique o build antes de abrir o pull request:

   ```bash
   npm run build
   ```

6. Envie suas alterações e abra um pull request com uma descrição clara do que foi feito e por quê.

## Áreas comuns de alteração

- `src/index.html` — perfil, bio e links
- `src/projetos.html` — lista de projetos
- `src/style.css` — apresentação visual e responsividade
- `src/assets/` — imagens e recursos visuais

## Orientações para pull requests

- Mantenha cada pull request focado em uma mudança.
- Descreva o comportamento esperado e o que foi alterado.
- Inclua capturas de tela quando a mudança afetar a aparência.
- Verifique links, textos alternativos de imagens e apresentação em telas pequenas.
- Não adicione dependências sem necessidade.
- Confirme que `npm run build` termina sem erros.

## Relatar problemas

Abra uma issue com uma descrição objetiva, passos para reproduzir o problema, comportamento esperado e observado e, se útil, capturas de tela.

## Código de Conduta

Ao participar, siga o [Código de Conduta](CODE_OF_CONDUCT.md). Para reportar problemas de segurança, consulte [SECURITY.md](SECURITY.md).
