# GitHub Copilot com VS Code

Este repositorio deixou de ser apenas um passo a passo curto e virou um kit pratico de onboarding para usar o GitHub Copilot com Visual Studio Code. A ideia aqui e ajudar quem esta comecando a instalar, configurar e usar o Copilot de um jeito mais produtivo, com exemplos reais de configuracao, instrucoes de repositorio e materiais de apoio.

## O que foi adicionado

- guia principal de instalacao e uso
- checklist de setup
- troubleshooting para problemas comuns
- configuracao de workspace em `.vscode`
- instrucoes de repositorio em `.github/copilot-instructions.md`
- prompt files para explicacao e revisao
- exemplos de perfis de configuracao

## Estrutura do repositorio

- `.vscode/extensions.json`: recomenda as extensoes principais
- `.vscode/settings.json`: perfil equilibrado para produtividade
- `.github/copilot-instructions.md`: orienta como o Copilot deve responder dentro do repositorio
- `.github/prompts`: prompts reutilizaveis para chat no VS Code
- `docs/checklist-de-instalacao.md`: validacao rapida de setup
- `docs/troubleshooting.md`: problemas comuns e recuperacao
- `examples`: perfis prontos de configuracao

## Instalacao e configuracao

1. Instale o Visual Studio Code.
2. Abra a aba de extensoes.
3. Instale `GitHub Copilot`.
4. Instale `GitHub Copilot Chat`.
5. Faca login com a sua conta GitHub.
6. Confirme se as extensoes ficaram ativas.
7. Abra um projeto e teste sugestoes inline.
8. Abra o chat do Copilot e faca uma pergunta sobre o codigo.

## Configuracao sugerida

O arquivo `.vscode/settings.json` ja vem com uma base equilibrada:

- inline suggestions ativadas
- next edit suggestions ativadas
- sugestoes desativadas para `plaintext`
- sugestoes desativadas para `scminput`

Isso ajuda a manter o Copilot util em codigo, sem atrapalhar texto livre ou mensagens de commit.

## Materiais prontos para uso

### Instrucoes de repositorio

Use `.github/copilot-instructions.md` para orientar o comportamento do Copilot no contexto do projeto, por exemplo:

- preferir respostas didaticas
- destacar trade-offs
- revisar codigo com foco em bugs e testes
- manter linguagem clara em portugues brasileiro

### Prompt files

Em `.github/prompts`, o repositorio traz dois atalhos uteis:

- `explicar-codigo.prompt.md`
- `revisar-alteracoes.prompt.md`

Eles ajudam a transformar o Copilot Chat em uma ferramenta mais consistente para estudo e revisao.

## Perfis de configuracao

Em `examples`, deixei duas opcoes prontas:

- `settings-balanced-mode.json`: modo equilibrado para produtividade
- `settings-learning-mode.json`: modo mais controlado para estudo

## Troubleshooting

Se algo nao funcionar como esperado:

- confira a autenticacao da conta GitHub
- atualize o VS Code
- recarregue a janela do editor
- revise as extensoes instaladas

O guia completo esta em `docs/troubleshooting.md`.

## Fontes oficiais

Este material foi reorganizado com base nas documentacoes oficiais do GitHub sobre:

- configuracao e uso do Copilot no editor
- custom instructions para repositorios
- troubleshooting de autenticacao e disponibilidade

Referencias:

- [GitHub Docs: Configuring GitHub Copilot in your environment](https://docs.github.com/en/copilot/configuring-github-copilot/configuring-github-copilot-in-your-environment)
- [GitHub Docs: Adding repository custom instructions for GitHub Copilot](https://docs.github.com/en/copilot/how-tos/configure-custom-instructions/add-repository-instructions)
- [GitHub Docs: Troubleshoot common issues with GitHub Copilot](https://docs.github.com/en/copilot/how-tos/troubleshoot-copilot/troubleshoot-common-issues)

## Proximos passos recomendados

- adicionar capturas de tela do fluxo no VS Code
- incluir versao em ingles do material
- criar exemplos por linguagem
- adicionar cenarios de uso para estudo, refatoracao e code review
