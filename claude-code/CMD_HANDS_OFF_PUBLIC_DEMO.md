# CMD Hands-off para Claude Code

## Propósito

Este comando simula a ativação do Creator Operating Suite para uma demonstração pública, focando na experiência do usuário não-técnico.

## Workflow

1.  **Reconhecimento de Intenção:** O Claude identifica que o usuário deseja iniciar um workflow de criação de conteúdo.
2.  **Carregamento de Contexto:** O sistema carrega o `PersonalizationOS` (L1) para contextualizar o Claude com as preferências, persona e estilo do criador.
3.  **Seleção de Skill:** Com base na intenção e contexto, o `Intelligence Router` (L3) seleciona a skill `visual-canvas-forge` (L4) para gerar um artefato visual ou `onboarding-xray-ebook` para conteúdo editorial.
4.  **Geração de Output:** A skill selecionada gera um output consistente e formatado, pronto para uso.
5.  **Log de Decisão:** As decisões tomadas (skill usada, contexto aplicado, output gerado) são registradas para futuras referências.

## Exemplo de Uso (simulado)

```
/cmd-hands-off-public-demo --goal "criar um post para LinkedIn sobre os benefícios do Creator Operating Suite" --audience "criadores não-técnicos" --tone "inspirador e prático"
```

## Output Esperado (simulado)

Um rascunho de post para LinkedIn, já formatado, com sugestões de imagens e hashtags, e um resumo das decisões tomadas pelo sistema para chegar a esse resultado.
