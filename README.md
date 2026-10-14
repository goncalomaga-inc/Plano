# O meu plano

App web simples para acompanhar o plano alimentar e de treino no dia a dia. Funciona no telemóvel e pode ser instalada no ecrã principal.

## O que tem

- **Hoje** — check-in da manhã, refeições do dia, extras fora do plano, suplementos e água.
- **Corrida** — registo das sessões, ritmo, regras para avançar e histórico.
- **Semana** — resumo da semana, relatório para enviar e cópia de segurança.
- **Plano** — plano alimentar, plano de corrida, recomendações e como instalar.

## Como usar

Abre o `index.html` no navegador. Não é preciso instalar nada nem ter servidor.

### Instalar no ecrã principal

- **iPhone (Safari):** Partilhar → Adicionar ao ecrã principal.
- **Android (Chrome):** menu ⋮ → Instalar app.

No iPhone, os dados do Safari e os da app instalada ficam guardados em sítios diferentes. Instala primeiro e usa sempre pelo ícone.

## Os teus dados

Tudo fica guardado só neste navegador (`localStorage`). Se limpares o navegador ou mudares de telemóvel, perdes os registos. Usa a **Cópia de segurança** no separador Semana para guardar e repor um ficheiro `.json`.

## Ficheiros

| Ficheiro | Para que serve |
| --- | --- |
| `index.html` | A app completa (HTML, CSS e JavaScript) |
| `manifest.webmanifest` | Nome, cores e ícones da app instalada |
| `icon-180.png`, `icon-512.png` | Ícones |
