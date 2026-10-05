# App Treino

Checklists interativos de treino — sem backend, sem instalação, abre direto no navegador do celular.

## Páginas

- **`index.html` — Treino ABC**: 3 treinos (A peito/ombro/tríceps, B costas/trapézio/bíceps, C perna), com foto, grupo muscular, séries × repetições editável e checklist de progresso.
- **`retomada.html` — Treino Retomada**: plano de 3 dias para quem está voltando a treinar (2 dias de inferiores + 1 de superiores), com observações de carga/progressão, tempo de descanso por exercício e checklist de progresso.

Ambas têm cronômetro de descanso entre séries e fotos/ícones clicáveis (abrem ampliados em pop-up).

## Como usar

Abra a página direto no navegador do celular (dá pra adicionar à tela inicial) ou publique com o GitHub Pages:

1. Settings → Pages → Branch: `main` → pasta `/ (root)`
2. Treino ABC fica em `https://ricardomedeiros1.github.io/apptreino/`
3. Treino Retomada fica em `https://ricardomedeiros1.github.io/apptreino/retomada.html`

## Editar os treinos

Os exercícios de cada dia estão no array `DIAS`, dentro da tag `<script>` de cada arquivo HTML.
