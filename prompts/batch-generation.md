# Batch Generation — Versículo do Dia

Este arquivo define como gerar várias peças da série “Versículo do Dia” em uma única rodada.

## Objetivo

Permitir a criação em lote de múltiplos versículos sem perder consistência visual, textual e estratégica.

---

# Instrução principal

Leia obrigatoriamente:

1. `CLAUDE.md`
2. `design-system/visual-rules.md`
3. `design-system/layout.md`
4. `design-system/typography.md`
5. `design-system/photography.md`
6. `design-system/ctas.md`
7. `content/verses.md`
8. `content/cta-library.md`
9. `prompts/master-prompt.md`

Depois execute a produção em lote.

---

# Seleção dos versículos

Use apenas versículos com:

Status: pendente

A quantidade de peças será informada no pedido.

Exemplo:

“Gere os próximos 10 versículos pendentes.”

Nesse caso:

- Pegue os 10 primeiros com status `pendente`
- Respeite a ordem dos IDs
- Não pule nenhum sem justificativa

---

# Processo em lote

Para cada versículo:

1. Identifique o ID.
2. Leia o texto completo.
3. Confirme referência e versão.
4. Identifique o tema central.
5. Classifique como curto, médio ou longo.
6. Defina o conceito fotográfico.
7. Escolha uma CTA.
8. Monte a composição.
9. Revise o texto.
10. Finalize a peça.

---

# Variação entre as peças

As peças precisam parecer parte da mesma série, mas não podem ficar visualmente repetitivas.

Variar entre:

- Montanhas
- Horizonte
- Amanhecer
- Entardecer
- Estradas
- Trilhas
- Mar
- Lagos
- Campos
- Deserto
- Céus
- Paisagens amplas

Evitar usar o mesmo tipo de fotografia em peças consecutivas quando houver outras opções coerentes.

---

# CTAs em lote

Não repetir a mesma CTA em peças consecutivas.

Evitar repetir a mesma CTA dentro do mesmo lote sempre que possível.

Alternar entre:

- Fé
- Identificação
- Declaração
- Compartilhamento

A CTA deve continuar sendo escolhida de acordo com o sentido do versículo.

Não alternar categorias de forma mecânica se isso prejudicar a coerência.

---

# Controle de repetição visual

Dentro do mesmo lote:

- Não usar a mesma fotografia
- Não usar composições praticamente idênticas
- Não colocar todos os blocos de texto na mesma altura
- Não usar sempre montanhas
- Não usar sempre pôr do sol
- Não repetir enquadramentos excessivamente semelhantes

A consistência deve vir do Design System, e não da repetição exata da composição.

---

# Nome dos arquivos

Usar o seguinte padrão:

`versiculo-ID-referencia.png`

Exemplos:

`versiculo-001-galatas-6-9.png`

`versiculo-002-1-joao-4-16.png`

Usar:

- letras minúsculas
- sem acentos
- hífens no lugar de espaços

---

# Organização dos arquivos

Salvar as peças geradas inicialmente em:

`output/drafts/`

Somente após aprovação, mover para:

`output/approved/`

---

# Revisão obrigatória do lote

Antes de considerar o lote concluído, revisar peça por peça.

Confirmar:

- Texto bíblico correto
- Referência correta
- Versão correta
- Nenhuma palavra alterada
- CTA coerente
- CTA sem repetição excessiva
- Fotografia coerente
- Boa legibilidade
- Hierarquia correta
- Identidade consistente

---

# Relatório do lote

Após a geração, apresentar um resumo no seguinte formato:

## Lote gerado

### 001
Referência:
Tema:
CTA:
Conceito visual:
Status: draft

### 002
Referência:
Tema:
CTA:
Conceito visual:
Status: draft

Repetir para todas as peças.

---

# Exemplo de comando

Use este modelo sempre que quiser gerar um novo lote:

“Leia todo o sistema do repositório e gere os próximos 10 versículos com status `pendente`.

Siga integralmente o `prompts/master-prompt.md` e o `prompts/batch-generation.md`.

Crie uma peça 1080x1920 para cada versículo.

Não altere nenhum texto bíblico.

Escolha CTAs coerentes e evite repetições.

Salve os arquivos em `output/drafts/`.

Ao final, apresente o relatório do lote.”
