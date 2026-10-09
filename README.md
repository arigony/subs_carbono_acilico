# Substituição nucleofílica acílica · simulador

Simulador interativo para revisão das reações de substituição nucleofílica em carbono acílico (Química Orgânica, PUCRS). Cada etapa mostra as setas de elétrons animadas, os átomos se movendo até a estrutura seguinte e a posição no diagrama de energia (adição, intermediário tetraédrico, eliminação).

## Mecanismos

| # | Reação | Link direto |
|---|--------|-------------|
| 1 | Aminólise de cloreto de acila (cloreto de acetila + 2 NH₃ → acetamida) | `#cloreto` |
| 2 | Alcoólise de anidrido (anidrido acético + etanol → acetato de etila) | `#anidrido` |
| 3 | Esterificação de Fischer (ácido acético + metanol, H⁺) | `#fischer` |
| 4 | Saponificação (acetato de etila + OH⁻) | `#saponificacao` |

Também inclui:
- escada de reatividade dos derivados (cloreto > anidrido > éster ≈ ácido > amida), com pKa do grupo de saída;
- ferramenta "partindo de / quero obter", que diz se a conversão é possível diretamente;
- quadro comparativo (nucleófilo, grupo de saída, catálise, intermediário, reversibilidade);
- desafios com correção imediata.

Para abrir direto num mecanismo, acrescente o código ao endereço, por exemplo:
`https://SEU-USUARIO.github.io/substituicao_acilica/#fischer`

## Como publicar no GitHub Pages

1. Crie um repositório público chamado `substituicao_acilica`.
2. Envie `index.html`, `README.md` e `.nojekyll` para a raiz.
3. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e clique em **Save**.
4. Em um ou dois minutos a página estará em `https://SEU-USUARIO.github.io/substituicao_acilica/`.

## Uso

- **Próxima / Anterior** ou as setas ← → do teclado avançam as etapas.
- **Repetir setas** anima de novo o movimento dos elétrons.
- **Reproduzir tudo** percorre o mecanismo inteiro automaticamente.

Arquivo HTML único, sem instalação. Funciona em computador e celular, com tema claro e escuro.

Veja também:
- [Adição à ligação dupla C=C](https://arigony.github.io/adicao_mecanismo/)
- [Substituição e eliminação: SN1, SN2, E1, E2](https://arigony.github.io/substiticao_eliminacao/)
