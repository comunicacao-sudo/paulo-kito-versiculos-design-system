# Paulo Kito — Versículo do Dia

Este repositório contém o Design System oficial da série “Versículo do Dia” do Paulo Kito.

Você é responsável por utilizar este sistema para criar artes em escala para Instagram Stories.

# Objetivo principal

O comportamento padrão deste projeto é gerar:

30 versículos diferentes
=
30 artes individuais
=
30 arquivos PNG separados
=
30 fundos fotográficos diferentes.

Todas as peças devem ser:

- 1080 × 1920 px
- Proporção 9:16
- Verticais
- Prontas para Instagram Stories

Nunca interpretar “30 artes” como uma única imagem contendo 30 peças.

---

# Fonte de verdade

Antes de qualquer geração, consulte obrigatoriamente:

1. `design-system/visual-rules.md`
2. `design-system/layout.md`
3. `design-system/typography.md`
4. `design-system/photography.md`
5. `design-system/ctas.md`
6. `content/verses.md`
7. `content/cta-library.md`
8. `prompts/master-prompt.md`
9. `prompts/batch-generation.md`
10. As imagens presentes em `references/`

Todos esses arquivos fazem parte do sistema.

Não ignore regras do repositório para improvisar uma nova direção visual.

---

# Prioridade das instruções

Em caso de dúvida, seguir esta ordem:

1. `CLAUDE.md`
2. `prompts/batch-generation.md`
3. `prompts/master-prompt.md`
4. Arquivos de `design-system/`
5. `content/`
6. `references/`

Se duas instruções entrarem em conflito, utilizar a de maior prioridade.

---

# Formato padrão de produção

Quando o usuário disser algo como:

“Gere os Versículos do Dia”

“Crie o lote de versículos”

“Faça as artes dos versículos”

e não especificar outra quantidade, interpretar como:

30 artes individuais.

Quando o usuário informar explicitamente outra quantidade, seguir a quantidade solicitada.

---

# Regra absoluta de saída

Para um lote padrão, o resultado final deve conter:

- 30 imagens
- 30 arquivos separados
- 30 versículos diferentes
- 30 fundos diferentes
- 1 versículo por imagem
- 1 CTA por imagem
- 1080 × 1920 px por arquivo
- Proporção 9:16
- PNG

É proibido substituir essa entrega por:

- Mosaico
- Grid
- Colagem
- Prancha
- Mockup com várias peças
- Uma única imagem contendo os 30 versículos
- Uma única imagem contendo miniaturas das artes

Cada versículo corresponde a uma peça independente.

---

# Texto bíblico

Utilize somente os versículos disponibilizados em:

`content/verses.md`

O texto fornecido deve ser tratado como conteúdo definitivo para a arte.

Nunca:

- Alterar palavras
- Resumir
- Parafrasear
- Completar
- Reescrever
- Remover trechos
- Alterar pontuação
- Alterar referência
- Alterar versão bíblica

Se houver inconsistência no conteúdo, sinalize antes de gerar aquela peça.

Nunca invente um versículo para completar um lote.

---

# Estrutura obrigatória da arte

Cada peça deve conter:

1. “Versículo do Dia”
2. Referência bíblica + versão
3. Texto completo do versículo
4. CTA de interação

O versículo é o elemento principal.

A CTA é secundária.

---

# Direção visual

As peças devem transmitir:

- Fé
- Força
- Contemplação
- Profundidade
- Esperança
- Direção
- Sobriedade
- Elegância

A estética deve ser:

- Cinematográfica
- Premium
- Limpa
- Editorial
- Atemporal

---

# Fotografia

Cada peça utiliza uma fotografia de fundo ocupando 100% do canvas.

Priorizar:

- Montanhas
- Horizontes
- Amanhecer
- Entardecer
- Estradas
- Trilhas
- Mar
- Lagos
- Campos
- Deserto
- Penhascos
- Céus
- Névoa
- Paisagens grandiosas

A fotografia deve possuir espaço negativo suficiente para aplicação do texto.

---

# Regra de variedade

Em um lote de 30:

- Não repetir fotografia
- Não reutilizar o mesmo fundo
- Não utilizar apenas reenquadramentos da mesma imagem
- Evitar cenários excessivamente semelhantes
- Variar iluminação
- Variar enquadramento
- Variar perspectiva
- Variar horário do dia
- Variar paisagem
- Variar composição

Ao mesmo tempo, todas as imagens precisam parecer parte da mesma coleção.

Variedade não significa abandonar a identidade.

---

# Referências visuais

As imagens em:

`references/`

são referências oficiais.

Analise:

- Composição
- Hierarquia
- Fotografia
- Respiro
- Contraste
- Escala
- Tipografia
- Atmosfera

Não copie literalmente uma referência.

Use-as para compreender a linguagem visual esperada.

---

# Tipografia

Utilizar duas linguagens tipográficas:

## Sans serif

Para:

- “Versículo do Dia”
- Referência
- CTA

## Serif

Para:

- Texto principal do versículo

O versículo deve possuir aparência editorial e elegante.

Todo o conteúdo deve permanecer alinhado à esquerda.

Priorizar texto branco.

---

# CTA

Toda peça deve possuir uma CTA.

Consultar:

`content/cta-library.md`

A CTA deve ser escolhida de acordo com o significado do versículo.

Exemplos:

- Se você crê, escreva: Amém.
- Recebe essa palavra? Responda: Amém.
- Essa palavra falou com você hoje?
- Declare: eu creio.
- Digite: eu confio.
- Envie para alguém que precisa ler isso.

Não repetir automaticamente “Amém” nas 30 peças.

Não repetir a mesma CTA em peças consecutivas.

---

# Planejamento antes da geração

Antes de gerar um lote, planeje as peças.

Para cada versículo determine:

- ID
- Referência
- Tema
- Comprimento
- Conceito fotográfico
- Cenário
- Iluminação
- Composição
- CTA
- Nome do arquivo

Verifique a variedade do conjunto antes de iniciar a geração.

---

# Controle de qualidade

Antes de finalizar cada arte, confira:

- Texto correto
- Referência correta
- Versão correta
- Nenhuma palavra faltando
- Nenhuma palavra alterada
- Boa quebra de linhas
- Alta legibilidade
- Fundo coerente
- CTA coerente
- Hierarquia correta
- Respeito às margens
- Consistência com as referências

---

# Arquivos

Utilizar o padrão:

`versiculo-ID-referencia.png`

Exemplo:

`versiculo-001-galatas-6-9.png`

Novas gerações devem ser destinadas inicialmente a:

`output/drafts/`

Peças aprovadas podem posteriormente ser movidas para:

`output/approved/`

---

# Regra final

A missão deste sistema não é gerar apenas imagens bonitas.

A missão é criar uma série reconhecível e consistente de “Versículo do Dia” do Paulo Kito em escala.

O resultado padrão esperado é:

30 versículos diferentes.

30 fundos diferentes.

30 artes individuais.

30 arquivos PNG separados.

Todos em 1080 × 1920 px.

Todos seguindo o mesmo Design System.
