# Lembrou — App final

Aplicativo PWA em HTML/CSS/JS, preparado para GitHub Pages usando a pasta `/docs`.

## Como publicar no GitHub Pages

1. Descompacte este arquivo.
2. Envie a pasta `docs` para a raiz do repositório.
3. Em **Settings > Pages**, configure:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /docs
4. Salve e aguarde o deploy.

## Estrutura do app

- **Agora**: próximo passo, próximos hábitos, já lembrou, mini tracker, humor e nota rápida.
- **Tracker**: consistência, sequência atual, melhor sequência, retomadas, mapa mensal e perguntas.
- **Calendário**: edição retroativa de qualquer dia.
- **Foco**: timer conectado aos hábitos.
- **Mais**: hábitos configuráveis, organização, sentimentos, atalhos, exportação e privacidade.

## Configuração dos hábitos

Cada hábito pode ter:
- nome
- emoji
- cor
- tipo: check, quantidade, duração ou horário
- meta
- unidade
- horário sugerido
- frequência: todos os dias, dias úteis ou personalizado
- dias da semana
- visibilidade
- ordem na tela

## Observações

Os dados são salvos localmente no navegador usando localStorage.
