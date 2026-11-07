# Auditoria do site --- Escola de Idiomas

**Site analisado:** https://escola-de-idiomas-oe4m.onrender.com/\
**Data da auditoria:** 07/11/2026

## Escopo

A auditoria foi realizada navegando pelas páginas públicas encontradas
no site:

-   Início (`/`)
-   Cursos (`/cursos`)
-   A Escola (`/escola`)
-   Preços e Horários (`/precos-horarios`)
-   Contato (`/contato`)

A análise foi feita sobre a versão publicada. Os arquivos-fonte do
projeto, incluindo `DESIGN.md`, não estavam disponíveis diretamente a
partir do site publicado; por isso, não foi possível confirmar o
conteúdo interno desses arquivos nem comparar propriedades de CSS
diretamente com o Design System original.

------------------------------------------------------------------------

# 1. Auditoria do resultado

## Problema 1 --- Dados de contato com aparência de placeholder

**Página:** Todas as páginas, principalmente `/contato`

**Elemento:** WhatsApp e informações de atendimento.

**Problema identificado:** O site apresenta o número **(83) 99999-9999**
como WhatsApp em várias áreas. O formato é claramente semelhante a um
número de preenchimento/placeholder. O mesmo dado aparece no rodapé, na
página de contato e em chamadas para ação.

**Por que isso pode ser melhorado:** Informações de contato são
essenciais para uma escola de idiomas. Um número fictício ou não
confirmado pode impedir o contato real do visitante e comprometer a
credibilidade do site.

**Melhoria sugerida:** Substituir o número somente pelo contato oficial
confirmado pela escola. Enquanto o dado real não estiver confirmado, não
criar outro número para substituí-lo.

------------------------------------------------------------------------

## Problema 2 --- Endereço com aparência de informação genérica

**Página:** Início, A Escola, Preços e Horários e Contato.

**Elemento:** Endereço da escola.

**Problema identificado:** O site informa **"Rua Principal, nº 100 --
Centro, Sousa-PB"** em diferentes páginas. O nome "Rua Principal" e o
número 100 têm aparência de dado genérico, e não foi possível confirmar
pelo site se são dados reais da escola.

**Por que isso pode ser melhorado:** O endereço é uma informação factual
de alta importância. Se estiver incorreto, pode levar o visitante ao
local errado e prejudicar a confiança no negócio.

**Melhoria sugerida:** Confirmar o endereço oficial antes da publicação.
Caso seja apenas um dado provisório, substituí-lo por uma informação
real confirmada.

------------------------------------------------------------------------

## Problema 3 --- Instagram apresentado de forma genérica

**Página:** Rodapé de todas as páginas.

**Elemento:** Informação de Instagram.

**Problema identificado:** O rodapé apresenta **@escoladeidiomas**, um
nome muito genérico, sem um link direto para o perfil.

**Por que isso pode ser melhorado:** Um visitante interessado em
conhecer a escola pelas redes sociais precisa conseguir acessar o perfil
rapidamente. Além disso, um nome genérico pode não corresponder ao
perfil real da escola.

**Melhoria sugerida:** Utilizar o @ oficial confirmado e transformar a
informação em um link clicável para o perfil correto.

------------------------------------------------------------------------

## Problema 4 --- Depoimentos apresentados como "experiências reais" sem evidência no próprio site

**Página:** Início.

**Elemento:** Seção "Quem Estuda Aqui".

**Problema identificado:** A seção afirma **"Experiências reais de quem
aprendeu a se comunicar sem medo de errar!"** e apresenta quatro
depoimentos identificados por nomes e iniciais. Entretanto, a página não
apresenta qualquer indicação de como esses depoimentos foram coletados
ou verificados.

**Por que isso pode ser melhorado:** Depoimentos são elementos de prova
social. Quando apresentados como experiências reais, precisam
corresponder a pessoas e experiências reais do negócio. Caso sejam
apenas conteúdo demonstrativo, a afirmação pode gerar uma impressão
factual indevida.

**Melhoria sugerida:** Confirmar os depoimentos com a escola antes da
publicação. Se forem reais, manter somente depoimentos autorizados. Se
forem exemplos fictícios utilizados durante o desenvolvimento,
removê-los ou substituí-los por conteúdo factual confirmado.

------------------------------------------------------------------------

## Problema 5 --- Links específicos de cursos levam para a página geral de cursos

**Página:** Início e `/cursos`.

**Elemento:** CTAs como "Quero estudar Inglês", "Quero estudar
Espanhol", "Quero estudar Francês", "Quero estudar Italiano" e "Quero
aprender Libras".

**Problema identificado:** Os CTAs apresentam intenção específica para
cada idioma, mas a navegação direciona para o mesmo endereço geral de
cursos (`/cursos`), em vez de levar diretamente a uma seção específica
ou página daquele idioma.

**Por que isso pode ser melhorado:** O texto do botão cria uma
expectativa de acesso direto ao curso escolhido. Ao clicar e chegar
novamente à página geral, o usuário precisa procurar o idioma
manualmente.

**Melhoria sugerida:** Fazer cada CTA apontar diretamente para a seção
correspondente do idioma, usando âncoras como `#ingles`, `#espanhol`,
etc., ou criar páginas individuais caso o projeto tenha essa
necessidade.

------------------------------------------------------------------------

## Problema 6 --- Promessa de aula experimental sem CTA claramente dedicado na página de preços

**Página:** `/precos-horarios`.

**Elemento:** Pergunta frequente sobre aula experimental.

**Problema identificado:** A página informa que existe uma aula
demonstrativa e explica que o interessado deve enviar uma mensagem pelo
WhatsApp, mas essa oportunidade aparece dentro do FAQ, sem um CTA
específico e destacado para "Agendar aula experimental".

**Por que isso pode ser melhorado:** A aula experimental é uma ação de
conversão importante. Deixar essa informação apenas dentro de uma
pergunta frequente reduz sua visibilidade.

**Melhoria sugerida:** Adicionar um CTA visual próximo ao conteúdo, por
exemplo "Agendar aula experimental", direcionando para o WhatsApp ou
para o fluxo real de agendamento.

------------------------------------------------------------------------

## Problema 7 --- Informações sobre preços são pouco específicas

**Página:** `/precos-horarios`.

**Elemento:** Tabela de preços.

**Problema identificado:** A página informa que os cursos começam em
**R\$ 150,00/mês**, mas praticamente todos os idiomas aparecem com o
mesmo valor inicial e a modalidade VIP fica "sob consulta".

**Por que isso pode ser melhorado:** O visitante pode não conseguir
entender quanto realmente pagará pelo curso que deseja. A informação de
"a partir de" é válida, mas precisa estar acompanhada de uma forma clara
de obter o preço exato.

**Melhoria sugerida:** Manter o valor inicial somente se ele for real e
confirmado e destacar um CTA específico para consultar o valor do
idioma/modalidade escolhidos.

------------------------------------------------------------------------

## Problema 8 --- Conteúdo repetitivo entre páginas

**Página:** Início, Cursos e A Escola.

**Elemento:** Descrições de metodologia, acolhimento, horários e
formatos.

**Problema identificado:** Conceitos como ensino acolhedor, aulas
práticas, turmas e aulas VIP e horários de atendimento aparecem
repetidamente em diferentes páginas.

**Por que isso pode ser melhorado:** A repetição pode deixar o site mais
extenso sem acrescentar novas informações. Cada página pode ter uma
função mais clara.

**Melhoria sugerida:** Manter uma breve apresentação nas páginas
secundárias e reservar detalhes mais completos para a página
correspondente. Por exemplo, concentrar informações de preços em "Preços
e Horários" e detalhes institucionais em "A Escola".

------------------------------------------------------------------------

# 2. Análise de hierarquia

A hierarquia geral é compreensível: as páginas utilizam títulos
principais, subtítulos e cards para organizar o conteúdo.

Entretanto, existem oportunidades de melhoria:

-   Algumas páginas possuem muitas seções sucessivas com estrutura
    semelhante.
-   Os CTAs de diferentes idiomas têm peso parecido, mesmo quando o
    objetivo pode ser direcionar o usuário para uma ação específica.
-   Na página de preços, o valor inicial recebe bastante destaque, mas o
    caminho para descobrir o preço exato de cada modalidade poderia ser
    mais evidente.
-   Na página de contato, o formulário e o botão de WhatsApp são os
    principais elementos de conversão e podem receber uma hierarquia
    visual ainda mais clara.

------------------------------------------------------------------------

# 3. Análise de navegação

A navegação principal apresenta as páginas:

-   Início
-   Cursos
-   A Escola
-   Preços e Horários
-   Contato

Os links principais de navegação estão presentes nas páginas analisadas.

O principal ponto de melhoria encontrado é a granularidade dos links dos
cursos: vários CTAs com nomes específicos de idioma levam para a mesma
página geral de cursos.

Também há links de "Ver detalhes" que podem ser mais específicos para
cada curso.

------------------------------------------------------------------------

# 4. Análise de consistência

A estrutura de conteúdo é consistente entre as páginas, com cabeçalho,
navegação, conteúdo principal e rodapé.

Há, porém, uma oportunidade de melhorar a consistência semântica dos
CTAs. Exemplos como:

-   "Quero estudar Inglês"
-   "Quero estudar Espanhol"
-   "Quero estudar Francês"
-   "Quero estudar Italiano"
-   "Quero aprender Libras"

são específicos, enquanto o destino é compartilhado.

O ideal é que o nível de especificidade do texto do botão corresponda ao
nível de especificidade da página de destino.

------------------------------------------------------------------------

# 5. Design System

O `DESIGN.md` não estava acessível diretamente a partir do site
publicado. Portanto, não é possível afirmar quais regras internas de
tipografia, cores, espaçamento, componentes e estados foram definidas no
documento original.

Na versão publicada, é possível observar uma tentativa de manter padrões
de componentes entre as páginas, principalmente:

-   cards;
-   botões;
-   títulos;
-   listas com marcadores;
-   blocos de CTA;
-   cabeçalho;
-   rodapé.

A comparação definitiva com o `DESIGN.md` deve ser realizada diretamente
nos arquivos-fonte do projeto.

------------------------------------------------------------------------

# 6. Responsividade

A análise estrutural do HTML publicado indica que o site possui
organização voltada para diferentes larguras, porém a verificação visual
completa em diferentes larguras de viewport não pode ser confirmada
somente pela leitura do conteúdo HTML disponibilizado.

Para uma auditoria definitiva de responsividade, o projeto deve ser
testado diretamente em pelo menos:

-   320 px;
-   375 px;
-   768 px;
-   1024 px;
-   1440 px.

Os principais pontos a verificar são:

-   largura dos cards;
-   quebra dos títulos;
-   navegação mobile;
-   tamanho dos botões;
-   espaçamento lateral;
-   imagens;
-   tabelas;
-   formulário de contato.

------------------------------------------------------------------------

# 7. Legibilidade

A estrutura textual é, em geral, organizada por títulos e listas, o que
favorece a leitura.

Entretanto, há bastante conteúdo textual nas páginas de cursos. A
utilização de textos mais curtos e objetivos poderia facilitar a
leitura, principalmente em dispositivos móveis.

Outro ponto é evitar excesso de expressões promocionais e adjetivos
quando não agregarem informação prática.

------------------------------------------------------------------------

# 8. Visual

A estrutura do site utiliza cards, chamadas, seções e CTAs para evitar
uma página puramente textual.

Os principais pontos de atenção visual são:

-   evitar excesso de seções com estruturas muito semelhantes;
-   garantir que os CTAs realmente conduzam a ações específicas;
-   reduzir conteúdo repetido;
-   dar maior destaque às informações que ajudam na decisão de
    matrícula;
-   garantir que imagens e elementos decorativos tenham função visual
    coerente com o Design System.

------------------------------------------------------------------------

# 9. Ciclos de refinamento dirigidos

## Ciclo 1 --- Especificidade dos CTAs dos cursos

**Problema:**\
Os botões dos idiomas possuem textos específicos, mas direcionam para a
mesma página geral de cursos.

**Prompt utilizado:**\
"Analise os CTAs dos cinco idiomas na página inicial e na página de
cursos. Cada botão deve levar diretamente à seção correspondente ao
idioma escolhido, sem remover conteúdo ou alterar a estrutura visual.
Utilize âncoras específicas para Inglês, Espanhol, Francês, Italiano e
Libras, mantendo o Design System existente."

**Correção realizada:**\
A correção deve ser aplicada nos arquivos-fonte do projeto. Na versão
publicada analisada, os CTAs continuam apontando para a página geral de
cursos.

**Teste:**\
Verificar cada CTA individualmente e confirmar se o usuário chega
diretamente ao conteúdo do idioma selecionado.

**Resultado:**\
Problema identificado, mas a correção não pôde ser aplicada diretamente
porque os arquivos-fonte não estavam disponíveis a partir do site
publicado.

**Decisão:**\
Manter o problema registrado para correção no projeto-fonte.

------------------------------------------------------------------------

## Ciclo 2 --- Dados factuais de contato

**Problema:**\
O site utiliza o número `(83) 99999-9999` e o Instagram
`@escoladeidiomas`, que precisam ser confirmados antes de serem tratados
como dados reais da escola.

**Prompt utilizado:**\
"Revise todas as informações factuais de contato do site. Não invente
nenhum dado. Substitua somente os dados provisórios pelo WhatsApp e
Instagram oficiais fornecidos pelo negócio. Atualize cabeçalho, rodapé,
página de contato, CTAs e links para que todos utilizem exatamente os
mesmos dados."

**Correção realizada:**\
Não foi aplicada na versão publicada, pois o contato oficial não pode
ser deduzido com segurança apenas pelo site.

**Teste:**\
Depois de receber os dados oficiais, clicar em todos os CTAs de WhatsApp
e no Instagram e confirmar que todos apontam para os canais corretos.

**Resultado:**\
Problema permanece pendente de confirmação factual.

**Decisão:**\
Não substituir os dados por valores inventados. A correção deve ocorrer
somente após confirmação dos dados oficiais.

------------------------------------------------------------------------

## Ciclo 3 --- Destaque para aula experimental

**Problema:**\
A página de preços informa que existe uma aula demonstrativa, mas a ação
aparece principalmente no FAQ e não possui um CTA dedicado com destaque
equivalente às demais ações.

**Prompt utilizado:**\
"Na página de Preços e Horários, transforme a informação sobre aula
experimental em um CTA claro e visualmente destacado. Preserve o
conteúdo existente e o Design System. O botão deve levar ao canal real
de atendimento utilizado para agendamento, sem inventar novas
informações."

**Correção realizada:**\
A alteração deve ser feita no arquivo-fonte da página de preços.

**Teste:**\
Verificar se o CTA aparece em desktop e mobile e se o clique leva ao
canal correto de atendimento.

**Resultado:**\
A versão publicada ainda apresenta a informação dentro do FAQ, sem um
CTA dedicado claramente destacado.

**Decisão:**\
Registrar como melhoria pendente para implementação no projeto-fonte.

------------------------------------------------------------------------

# 10. Checklist final

-   [x] Tenho pelo menos quatro páginas distintas.
-   [x] Todas estão ligadas pela navegação principal.
-   [x] O conteúdo corresponde ao tema de uma escola de idiomas.
-   [ ] O Design System foi comparado diretamente com o `DESIGN.md`.
-   [ ] O site foi testado visualmente em todas as larguras de viewport.
-   [x] Foram identificados mais de cinco pontos reais de melhoria.
-   [x] Foram documentados três ciclos de refinamento dirigido.
-   [x] Não foram inventadas informações factuais para corrigir
    problemas.
-   [x] Os problemas de informações possivelmente provisórias foram
    registrados.
-   [ ] Os refinamentos foram efetivamente aplicados na versão
    publicada.
-   [x] A auditoria registra o que foi possível verificar e o que
    depende dos arquivos-fonte.

## Observação final

A auditoria foi baseada na versão pública disponível em 07/11/2026. Como
o endereço publicado não disponibiliza os arquivos-fonte nem o
`DESIGN.md`, as correções de código e a comparação detalhada com o
Design System precisam ser realizadas no projeto original.
