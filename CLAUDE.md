# Paulo Kito — Versículo do Dia

Este repositório contém o Design System oficial da série “Versículo do Dia” do Paulo Kito.

O sistema é responsável por:

1. Pesquisar novos versículos.
2. Validar os textos bíblicos.
3. Impedir repetição de versículos já utilizados.
4. Montar o lote mensal.
5. Planejar as peças.
6. Gerar as artes para Instagram Stories.
7. Manter consistência visual entre todos os lotes.

---

# Objetivo principal

O comportamento padrão deste projeto é gerar mensalmente:

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

# Fonte de verdade do sistema

Antes de executar qualquer produção, consultar obrigatoriamente:

1. `CLAUDE.md`
2. `content/used-verses.md`
3. `content/verses.md`
4. `content/cta-library.md`
5. `design-system/visual-rules.md`
6. `design-system/layout.md`
7. `design-system/typography.md`
8. `design-system/photography.md`
9. `design-system/ctas.md`
10. `prompts/master-prompt.md`
11. `prompts/batch-generation.md`
12. As imagens presentes em `references/`

Não ignorar essas regras para improvisar um novo sistema.

---

# Fonte bíblica oficial

Todos os versículos devem ser pesquisados e validados em:

https://www.bible.com/pt

Versão obrigatória:

NVI — Nova Versão Internacional

Esta é a fonte definida pelo projeto para seleção e conferência dos versículos.

---

# Regra absoluta sobre pesquisa bíblica

Nunca selecionar um versículo apenas de memória.

Nunca inventar um texto bíblico.

Nunca completar um versículo de memória.

Nunca misturar traduções.

Nunca substituir a NVI por outra tradução.

Nunca alterar o texto encontrado para fazê-lo caber melhor na arte.

O fluxo correto é:

PESQUISAR
↓
VALIDAR
↓
CHECAR DUPLICIDADE
↓
REGISTRAR NO LOTE
↓
PLANEJAR
↓
GERAR

---

# Histórico permanente

O arquivo:

`content/used-verses.md`

é a memória permanente de versículos já utilizados.

Ele deve ser consultado ANTES de qualquer nova seleção.

Uma referência presente nesse arquivo está bloqueada para futuros lotes.

Exemplo:

Se:

`Gálatas 6:9`

já estiver no histórico, não utilizar novamente.

A verificação deve ser feita principalmente pela referência bíblica, e não apenas pelo texto.

---

# Regra de não repetição

Um novo lote não pode conter:

- Referências já utilizadas anteriormente
- Versículos duplicados dentro do próprio lote
- O mesmo versículo em outra tradução
- A mesma referência com outra formatação

A regra de não repetição é permanente entre os meses.

O objetivo é construir um histórico crescente de versículos utilizados.

---

# Fila mensal

O arquivo:

`content/verses.md`

representa exclusivamente o lote atual.

Antes da geração mensal, ele deve conter 30 versículos novos e validados.

Cada registro deve possuir:

- ID
- Referência
- Versão
- Texto
- Tema
- Tamanho
- Status

---

# Processo mensal obrigatório

Quando o usuário solicitar um novo lote de “Versículos do Dia”:

## ETAPA 1 — Consultar histórico

Leia:

`content/used-verses.md`

Identifique todas as referências já utilizadas.

---

## ETAPA 2 — Pesquisar novos versículos

Pesquise novos versículos em:

https://www.bible.com/pt

Utilize somente:

NVI — Nova Versão Internacional

Selecione 30 referências que ainda não aparecem no histórico.

---

## ETAPA 3 — Validar

Para cada versículo:

1. Confirme a referência.
2. Confirme que a tradução é NVI.
3. Confirme o texto.
4. Confirme a pontuação.
5. Compare com `content/used-verses.md`.
6. Confirme que não existe duplicidade dentro do lote.

---

## ETAPA 4 — Garantir variedade

O conjunto de 30 versículos deve possuir variedade temática.

Buscar equilíbrio entre temas como:

- Fé
- Perseverança
- Esperança
- Confiança
- Sabedoria
- Propósito
- Coragem
- Disciplina
- Família
- Amor
- Liderança
- Humildade
- Trabalho
- Direção
- Paciência
- Paz
- Gratidão
- Força
- Promessas
- Dependência de Deus

Evitar selecionar 30 versículos com mensagens praticamente iguais.

---

## ETAPA 5 — Variar comprimento

Buscar aproximadamente:

- 10 versículos curtos
- 10 versículos médios
- 10 versículos longos

Essa distribuição não precisa ser matematicamente exata.

Ela existe para produzir variedade visual no mês.

---

## ETAPA 6 — Preencher o lote

Registrar os 30 versículos selecionados em:

`content/verses.md`

Todos devem começar com:

`Status: pendente`

Não iniciar a geração das imagens antes de completar e validar esta etapa.

---

## ETAPA 7 — Planejar as artes

Antes de gerar imagens, planejar individualmente as 30 peças.

Para cada uma, definir:

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

O planejamento deve garantir variedade entre as 30 peças.

---

## ETAPA 8 — Gerar

Gerar:

30 arquivos PNG individuais.

Cada arquivo deve possuir:

- 1080 × 1920 px
- Proporção 9:16
- 1 versículo
- 1 fundo fotográfico exclusivo
- 1 CTA

Nunca criar mosaico, grid ou colagem.

---

# Estrutura obrigatória de cada arte

Cada peça deve conter:

1. “Versículo do Dia”
2. Referência bíblica + NVI
3. Texto completo do versículo
4. CTA de interação

O versículo é sempre o elemento principal.

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

Cada peça deve utilizar um fundo fotográfico diferente.

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

# Regra dos fundos

Dentro de um lote de 30:

- Não repetir fotografia
- Não reutilizar o mesmo fundo
- Não utilizar apenas reenquadramentos da mesma imagem
- Variar cenário
- Variar iluminação
- Variar perspectiva
- Variar horário do dia
- Variar composição

Todas as peças, porém, precisam continuar pertencendo à mesma identidade visual.

---

# Referências visuais

As imagens presentes em:

`references/`

são referências oficiais do projeto.

Utilizá-las para compreender:

- Composição
- Hierarquia
- Fotografia
- Respiro
- Contraste
- Tipografia
- Atmosfera

Não copiar literalmente as referências.

---

# Tipografia

Utilizar:

## Sans serif

Para:

- “Versículo do Dia”
- Referência
- CTA

## Serif

Para:

- Texto principal do versículo

Todo conteúdo deve permanecer alinhado à esquerda.

Priorizar texto branco.

---

# CTA

Toda peça deve possuir uma CTA.

Consultar:

`content/cta-library.md`

Selecionar a CTA de acordo com o significado do versículo.

Não repetir a mesma CTA em peças consecutivas.

Não utilizar “Amém” automaticamente nas 30 peças.

---

# Regra absoluta de saída

Para o lote mensal padrão, entregar:

- 30 imagens
- 30 arquivos separados
- 30 versículos diferentes
- 30 fundos diferentes
- 30 CTAs coerentes
- 1 versículo por arquivo
- 1080 × 1920 px
- Proporção 9:16
- PNG

Nunca substituir por:

- Mosaico
- Grid
- Colagem
- Prancha
- Mockup
- Uma única imagem contendo várias peças

---

# Nome dos arquivos

Utilizar:

`versiculo-ID-referencia.png`

Exemplo:

`versiculo-001-salmos-23-4.png`

Regras:

- Letras minúsculas
- Sem acentos
- Sem espaços
- Hífens como separadores

---

# Destino

Novas gerações:

`output/drafts/`

Após aprovação humana:

`output/approved/`

Nenhuma peça deve ser considerada automaticamente aprovada.

---

# Atualização do histórico

IMPORTANTE:

Gerar uma arte não significa que o versículo já foi utilizado.

Somente depois da aprovação/publicação do lote os versículos devem ser adicionados a:

`content/used-verses.md`

Isso evita bloquear versículos de peças rejeitadas ou descartadas.

---

# Controle de qualidade

Antes de finalizar cada peça, conferir:

- Texto exatamente igual à fonte validada
- Referência correta
- NVI confirmada
- Nenhuma palavra faltando
- Nenhuma palavra alterada
- Boa legibilidade
- Boa quebra de linhas
- Fundo exclusivo
- CTA coerente
- Hierarquia correta
- Consistência visual

---

# Regra final

O sistema deve funcionar continuamente mês após mês.

A cada novo lote:

HISTÓRICO
↓
PESQUISA
↓
30 NOVOS VERSÍCULOS
↓
VALIDAÇÃO NVI
↓
PLANEJAMENTO
↓
30 FUNDOS DIFERENTES
↓
30 ARTES
↓
APROVAÇÃO
↓
ATUALIZAÇÃO DO HISTÓRICO

O resultado deve ser uma biblioteca crescente de conteúdos sem repetição de versículos e com identidade visual consistente.
