# Fase 1 — Tarefas

<!-- fase-format:2 -->

Cada linha abaixo representa uma entrega da primeira fase do Portal Agrojur. O título explica o resultado esperado para o cliente; a descrição mantém a referência técnica necessária para a execução. Os identificadores ao fim das linhas são controles de sincronização do portal e não devem ser alterados manualmente.

- [x] Preparar o ambiente de construção do Portal Agrojur @Celso !22/09/2026 <!-- id:36b8c091-91ab-42c0-ba98-b7a1165649a0 -->
  > Deixar o projeto, o repositório e uma versão de teste prontos para começar a construção com segurança, sem publicar conteúdo real. Antes de iniciar, confirmar qual ambiente será usado e quem pode acessar a prévia. Referência técnica: SPEC-1-001 · CA-1-001..002 · Leva 1 · CONCLUÍDA em 16/09/2026 — projeto Skip 58949, preview público noindex, repositório gerado pelo Skip e aceite humano confirmados.

- [x] Criar uma área segura para organizar e publicar conteúdos @Celso !22/09/2026 <!-- id:4c971129-9318-45a5-9122-5a639da9b05e -->
  > Organizar os conteúdos por etapa de trabalho e garantir que somente pessoas autorizadas possam criar, revisar ou publicar. Conteúdo incompleto ou acesso indevido deve ser recusado. Referência técnica: SPEC-1-001 · CA-1-003..005 · Leva 2 · CONCLUÍDA em 20/09/2026 — modelo editorial persistente, autenticação, RBAC server-side, histórico de versões, provas negativas e aceite humano no preview.

- [x] Confirmar a segurança e a recuperação da área editorial @Celso !22/09/2026 <!-- id:9eb718d6-448e-4298-9380-014e4cf90018 -->
  > Testar situações de erro e acesso indevido, além de provar que um conteúdo pode sair do ar e ser recuperado. Referência técnica: SPEC-1-001 · CA-1-006 · Leva 3 · CONCLUÍDA em 22/09/2026 — histórico restrito, rota autenticada, recuperação ARCHIVED→IN_REVIEW, nova aprovação antes de republicar, QA e aceite humano no preview.


## Trabalho aberto atualizado — E-F1-002

# Fase 1 — Construção guiada do seu site-portfólio agro

**Cliente:** Moura e Medeiros Advogados Associados · **Atualização:** 29/10/2026 · E-F1-002.

Celso, você não precisa saber programar. O Maestro faz a construção técnica; você fornece ou confirma as informações da sua empresa, olha as entregas e diz o que precisa melhorar.

## Como trabalhar
1. Diga “Quero continuar meu site de portfólio. Leia as tarefas atualizadas e me diga em qual estamos”.
2. O Maestro explica apenas a próxima tarefa e faz uma pergunta por vez. Não precisa responder tudo de uma vez.
3. Quando ele entregar algo, abra o link da prévia. Ele deve explicar onde clicar, o que olhar e o que deveria acontecer.
4. Responda “Testei e está certo, pode seguir” ou diga o que não funcionou. Pedir mudança mantém a mesma tarefa aberta; ele ajusta e mostra de novo.
5. Não precisa abrir um chat de construção no Skip nem executar comandos técnicos: converse com o Maestro e use a prévia para conferir.

**Já concluído:** T01, T02 e T03. Não recomeçar ambiente, acesso e segurança. São 3 aceites históricos em um plano agora com 14 tarefas; tarefas adicionais estão abertas, sem retroagir aceites.
**O que está fora:** blog, newsletter e disparos automáticos. Diagnóstico e calculadora continuam no projeto. A calculadora será reformulada na fase própria, após regras aprovadas, e não impede o portfólio avançar.
**Portfólio da empresa:** Ramon ainda vai colocar na pasta de contextos. O Maestro deve ler de lá quando disponível. Até lá, não inventa conteúdo real nem exige que você refaça o documento.


- [ ] Entender o projeto e organizar o portfólio enviado @Celso <!-- id:f17d2817-58f2-43b9-a8aa-ef3be40dd3f3 -->
  > F1-T04 · SPEC-1-002 · ABERTA · instruções detalhadas abaixo.

- [ ] Organizar a aparência agro e limpar a navegação @Celso <!-- id:be77ef7e-2270-4d03-be1f-c554f607b848 -->
  > F1-T05 · SPEC-1-002 · ABERTA · instruções detalhadas abaixo.

- [ ] Apresentar os serviços e conferir os textos do site @Celso <!-- id:df742e7f-60f7-4736-a0ca-4c1bcaa56f1b -->
  > F1-T06 · SPEC-1-002 · ABERTA · instruções detalhadas abaixo.

- [ ] Preparar títulos e informações técnicas das páginas @Celso <!-- id:bcf0b7c6-b6da-4398-82af-e2ceecb70d9d -->
  > F1-T07 · SPEC-1-003 · ABERTA · instruções detalhadas abaixo.

- [ ] Testar o site no celular e facilitar a navegação @Celso <!-- id:3a3a3548-6882-4ee5-9d5a-cae69e231a28 -->
  > F1-T08 · SPEC-1-003 · ABERTA · instruções detalhadas abaixo.

- [ ] Confirmar seu WhatsApp e colocar o botão de contato @Celso <!-- id:c6909f65-a8fb-4d1d-8678-29dcd919d857 -->
  > F1-T09 · SPEC-1-004 · ABERTA · instruções detalhadas abaixo.

- [ ] Decidir como o visitante pede um diagnóstico @Celso <!-- id:db228cef-8d68-4f7d-bfca-b47d8ef9de3f -->
  > F1-T10 · SPEC-1-004 · ABERTA · instruções detalhadas abaixo.

- [ ] Construir o pedido de diagnóstico em ambiente de teste @Celso <!-- id:a7e1c5d3-6e29-48a8-b7f6-53306f811413 -->
  > F1-T11 · SPEC-1-004 · ABERTA · instruções detalhadas abaixo.

- [ ] Conferir quem recebe os diagnósticos e testar problemas @Celso <!-- id:9fdf5edd-819f-44f1-ad6f-68d6abf74a27 -->
  > F1-T12 · SPEC-1-004 · ABERTA · instruções detalhadas abaixo.

- [ ] Entender a calculadora e reunir as regras com o contador @Celso <!-- id:d63feb83-ecc7-40b0-8821-64df3692b49b -->
  > F1-T13 · SPEC-1-005 · ABERTA · instruções detalhadas abaixo.

- [ ] Revisar o conjunto e preparar a próxima etapa @Celso <!-- id:2ed300d9-1242-40c1-be26-74e81aca901a -->
  > F1-T14 · SPEC-1-005 · ABERTA · instruções detalhadas abaixo.


## F1-T04 — Entender o projeto e organizar o portfólio enviado

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-002. **Critérios:** CP-001,CP-002. **Dependência:** T03 aceita; portfólio do Ramon disponível para textos reais. **Estado:** PRÓXIMA: AGUARDA PORTFÓLIO PARA TEXTOS REAIS. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
Um site de portfólio é a apresentação da sua empresa na internet. É parecido com um cartão de visitas mais completo: mostra quem você é, quem atende, quais serviços oferece e como conversar com você. Não administra processos nem substitui seu trabalho jurídico.

### O que você faz, passo a passo
Quando o Ramon avisar que o documento foi colocado na pasta de contextos, escreva: “Vamos continuar a tarefa F1-T04. Leia o portfólio que o Ramon colocou na pasta e me explique o que vamos construir.” Leia o resumo que o Maestro mostrar. Corrija serviços que não oferece, informações antigas ou a forma como quer ser apresentado. Se o arquivo ainda não estiver lá, você pode entender o projeto e conversar sobre identidade, mas os textos reais esperam o documento.

### O que o Maestro vai construir ou preparar
Ler o arquivo da pasta de contextos, registrar nome/ID/versão e trechos-fonte; extrair apresentação, público, serviços e contato sem inventar. Mostrar uma lista curta, em linguagem comum. Fazer uma pergunta por vez. Perguntar primeiro a prioridade dos serviços, depois as lacunas de nome/logo. O consultor disse que subirá o arquivo: não pedir a Celso para escrever o portfólio novamente. Se ausente, registrar AGUARDA PORTFÓLIO e não travar conversas independentes de identidade.

### Como você confere e dá seu feedback
Celso confere resumo e mapa de páginas. Registrar quais pontos aprovou e quais faltam. Evidência: mapa com referência à fonte e aceite da organização, não publicação.

### Onde parar e o que não fazer
Não aceitar ausência de reclamação como aprovação. Nome final, logo e fatos ausentes não são inventados.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.

## F1-T05 — Organizar a aparência agro e limpar a navegação

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-002. **Critérios:** CP-003,CP-004. **Dependência:** T04 aceita para conteúdo; identidade pendente admite somente prévia claramente provisória. **Estado:** ABERTA, aguarda dependências e teste humano da anterior. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
Agora vamos dar ao site a aparência de um negócio voltado ao campo. A limpeza serve para tirar da navegação o que não faz parte do seu site, não para apagar informações ou trabalhos já feitos.

### O que você faz, passo a passo
Diga: “Vamos ajustar a aparência do meu site para o público agro.” Mostre ao Maestro a logo do escritório se já tiver. Se não tiver, diga isso. Conte quais imagens fazem sentido para seu público, como lavoura, pecuária ou tecnologia agrícola. Abra a prévia pelo link que ele entregar. Olhe a página inicial e responda: “Gostei de ...; quero mudar ...”. Não precisa entender código.

### O que o Maestro vai construir ou preparar
Reaproveitar o projeto existente e componentes aceitos; montar uma prévia de home e menu coerentes com o portfólio. Retirar blog/newsletter de menus, CTAs, rodapé, campos de inscrição e links ativos; se houver rotas antigas, preservar dados/código/histórico e tornar a retirada reversível, sem apagar coleção/arquivo. Remover apenas placeholders da apresentação pública, guardando versão anterior. Não alterar autenticação ou trabalho aceito. Mostrar antes/depois. Usar referências agro como direção, não fingir que imagens são da fazenda do Celso nem usar material sem licença. Nome/logo provisórios identificados; verde-musgo/fundo final dependem de feedback.

### Como você confere e dá seu feedback
Prévia antes/depois, home e menu sem blog/newsletter nem links órfãos; teste do menu no celular. Celso comenta e aprova visual ou pede ajustes. Repetir nesta task até aceite.

### Onde parar e o que não fazer
Não apagar dados, mudar marca/repo/domínio ou publicar. Não tocar calculadora além de manter estado seguro/links de demonstração não validada.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.

## F1-T06 — Apresentar os serviços e conferir os textos do site

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-002. **Critérios:** CP-002,CP-005,CP-006. **Dependência:** T05 aceita e portfólio disponível/aprovado. **Estado:** ABERTA, aguarda dependências e teste humano da anterior. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
Cada área do site vai explicar um serviço real em linguagem que o produtor rural entenda: que tipo de problema você ajuda a resolver e como ele pode entrar em contato. Não é uma promessa de resultado.

### O que você faz, passo a passo
Diga: “Vamos preencher a apresentação e os serviços com meu portfólio.” Abra as páginas que o Maestro indicar. Confira nome, experiência, serviços e linguagem. Avise o que está errado ou o que falta. Você não precisa escrever textos do zero: o Maestro prepara com base no documento e você confere.

### O que o Maestro vai construir ou preparar
Criar apresentação e páginas/blocos de serviços a partir do manifesto aprovado. Agronomia/aviação só aparecem na extensão comprovada no portfólio e aprovada por Celso, sem supor oferta profissional. Não exigir artigos, cluster/blog ou rotina de produção editorial. Aplicar revisão humana de publicidade jurídica, escapar conteúdo externo, impedir script/instrução embutida e PII não aprovada; manter histórico/recuperação do modelo já aceito. Conteúdo normativo exige fonte oficial/verificação antes de público. Mostrar cada página e solicitar aprovação explícita.

### Como você confere e dá seu feedback
Jornada início→serviço e retorno funciona. Testes negativos: texto não aprovado, promessa de êxito, PII e script não publicam; recuperação preserva versão anterior. Textos reais aprovados por Celso.

### Onde parar e o que não fazer
Não criar serviço, depoimento, cliente ou credencial. Se revisão jurídica faltar, prévia restrita/noindex, sem liberar público.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.

## F1-T07 — Preparar títulos e informações técnicas das páginas

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-003. **Critérios:** CP-007. **Dependência:** T06 aceita. **Estado:** ABERTA, aguarda dependências e teste humano da anterior. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
As páginas precisam ter nomes e descrições organizados para que pessoas e buscadores entendam o site. Isso não garante aparecer em primeiro lugar no Google.

### O que você faz, passo a passo
Diga: “Pode organizar os títulos e descrições das páginas.” Confira os nomes que o Maestro mostrar e corrija algo que não represente o escritório. A parte técnica ele faz.

### O que o Maestro vai construir ou preparar
Aproveitar contrato técnico existente de metadata/canonical/sitemap/robots e dados estruturados aplicáveis; usar somente páginas do portfólio aprovadas, diagnóstico e calculadora conforme estado permitido. Blog/newsletter fora da geração e links; preview noindex. Domínio/marca definitivos só após decisão. Não inventar resultados de analytics nem conectar serviço novo sem consentimento.

### Como você confere e dá seu feedback
Relatório por rota com títulos/descrições, sitemap e robots coerentes; crawl sem links críticos quebrados, preview noindex. Celso confere títulos.

### Onde parar e o que não fazer
Nenhuma indexação produtiva automática ou garantia de tráfego.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.

## F1-T08 — Testar o site no celular e facilitar a navegação

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-003. **Critérios:** CP-008. **Dependência:** T07 aceita. **Estado:** ABERTA, aguarda dependências e teste humano da anterior. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
Um site bonito também precisa ser fácil de usar. Vamos conferir se os textos dão para ler, os botões aparecem e a página desce normalmente, sem animação atrapalhando.

### O que você faz, passo a passo
Abra o link de teste no computador e no celular. Entre em uma área de serviço, volte ao início e role a página até o fim. Diga ao Maestro onde travou, ficou pequeno ou confundiu. Pode escrever: “No celular, o botão ... não apareceu.”

### O que o Maestro vai construir ou preparar
Testar viewports de celular e desktop, teclado/foco, contraste/labels, carregamento e preferência de movimento reduzido. Reproduzir o problema de rolagem observado na call; animação não pode prender o usuário. Relatar o que testou e corrigir apenas o recorte autorizado. Não exigir que Celso rode comandos técnicos.

### Como você confere e dá seu feedback
Capturas e relatório técnico com navegação/rolagem e CTAs utilizáveis em ambos viewports; Celso executa roteiro e confirma que consegue usar.

### Onde parar e o que não fazer
Falha crítica mantém task aberta; não maquiar resultado de auditoria.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.

## F1-T09 — Confirmar seu WhatsApp e colocar o botão de contato

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-004. **Critérios:** CP-009. **Dependência:** T08 aceita. **Estado:** ABERTA, aguarda dependências e teste humano da anterior. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
O botão do WhatsApp é um atalho. O visitante clica e abre uma conversa com você no WhatsApp. Ele ainda precisa escrever e apertar enviar. O site não responde sozinho, não envia campanhas e não precisa de uma API para esse botão.

### O que você faz, passo a passo
O Maestro vai perguntar: “Qual número de WhatsApp deve receber as mensagens do site? Na nossa reunião foi informado (65) 99987-2104. Continua sendo esse ou quer usar outro? Confirme com DDD.” Responda e abra a prévia. Clique no botão e confira se aparece a conversa certa. Não precisa mandar mensagem para testar.

### O que o Maestro vai construir ou preparar
Perguntar/confirmar número antes de configurar, conforme nova orientação do consultor. Reaproveitar número da call como referência, não como autorização atual automática. Normalizar país/DDD; se país ambíguo, perguntar, não adivinhar. Implementar apenas link https://wa.me/<numero-internacional-confirmado>, acionado por clique explícito. Sem mensagem automática, API, bot, leitura de conversas, CRM ou segredo. Um único destino confirmado no menu/flutuante/contato quando usados, sem sobrepor conteúdo.

### Como você confere e dá seu feedback
Testar número inválido/vazio (não ativar), destino confirmado (abrir conversa correta), celular/desktop/teclado e ausência de envio automático. Captura sem dados de conversa + confirmação de Celso.

### Onde parar e o que não fazer
Clique não é mensagem enviada, lead, contratação ou autorização para disparo.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.

## F1-T10 — Decidir como o visitante pede um diagnóstico

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-004. **Critérios:** CP-010. **Dependência:** T09 aceita. **Estado:** ABERTA, aguarda dependências e teste humano da anterior. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
O diagnóstico é um primeiro pedido de avaliação. A pessoa conta brevemente do que precisa e deixa um contato para você analisar. Não é uma resposta jurídica automática, nem contrato, orçamento ou promessa de resultado. É diferente do botão WhatsApp, que só abre uma conversa.

### O que você faz, passo a passo
Diga: “Quero entender e definir o diagnóstico do site.” Responda uma pergunta por vez: o que você precisa saber no primeiro contato; quais dados realmente precisa; quem recebe e acompanha esses pedidos; como quer receber/consultar; qual texto explica o uso dos dados. Se não souber alguma resposta, diga isso para o Maestro explicar as possibilidades. Não envie documentos sigilosos para testar.

### O que o Maestro vai construir ou preparar
Propor campos mínimos como sugestão explícita, nunca decisão fechada; obter aprovação de finalidade, campos, obrigatórios, destinatário/dono, canal autorizado, forma de recebimento, acesso, consentimento, retenção e mensagem de confirmação. Explicar escolhas sem termos de banco/API. Não presumir e-mail ou capacidade de envio WhatsApp; não usar credenciais do consultor. Conferir no projeto existente se há fila/backend seguro. Preferir reuso, documentar viabilidade. Se falta acesso ou decisão de proteção de dados, manter gate aberto com pergunta concreta. Não ativar coleta real.

### Como você confere e dá seu feedback
Contrato B-DIAG assinado por aceite explícito de Celso nos itens definidos; lista clara do que vai acontecer após envio e de quem fará atendimento. Se houver dependência técnica externa, registrar Ramon como dono e parar somente essa capacidade.

### Onde parar e o que não fazer
Sem definição de destino e proteção dos dados, não implementar formulário produtivo nem inventar destinatário.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.

## F1-T11 — Construir o pedido de diagnóstico em ambiente de teste

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-004. **Critérios:** CP-011,CP-012. **Dependência:** T10 aceita e B-DIAG completo, acesso técnico demonstrado. **Estado:** ABERTA, aguarda dependências e teste humano da anterior. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
Com as escolhas anteriores, o Maestro vai construir o formulário: as caixas onde o visitante preenche o pedido. Primeiro vamos usar dados fictícios para provar que funciona e que só a pessoa autorizada consegue consultar.

### O que você faz, passo a passo
Diga: “Pode construir o diagnóstico com o que aprovamos, usando dados de teste.” Depois abra o link. Preencha com um nome inventado e uma mensagem sem dados de cliente. Veja a confirmação. Não precisa configurar banco, endpoint ou servidor.

### O que o Maestro vai construir ou preparar
Reusar backend seguro/autenticação aceitos, validar no servidor exatamente os campos B-DIAG, consentimento quando exigido, limites de entrada, antiabuso e idempotência por requisição. Duplo clique/retry da mesma solicitação não cria dois pedidos; pedidos novos legítimos não são descartados por coincidência de texto. Fila/destino e confirmação conforme contrato; não alegar e-mail entregue se apenas armazenado. Dados acessíveis somente ao papel aprovado; logs sanitizados. Destino externo sem integração provada: task bloqueada, não substituir silenciosamente. Estados de sucesso, validação e indisponibilidade com mensagem simples e recuperação sem perda. Não instalar dependência/serviço alternativo por conta própria.

### Como você confere e dá seu feedback
RED sem campo/consentimento/permissão e com retry; GREEN pedido sintético recebido uma vez no destino aprovado e consulta restrita; erro de destino não comunica sucesso falso. Regressão de acesso público, XSS, logs e recuperação. Build/testes do projeto e roteiro humano.

### Onde parar e o que não fazer
Nenhuma coleta real/publicação até autorização específica e política aplicada; nenhuma alteração do schema/modelo aceito fora do necessário e autorizado na SPEC.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.

## F1-T12 — Conferir quem recebe os diagnósticos e testar problemas

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-004. **Critérios:** CP-013. **Dependência:** T11 aceita. **Estado:** ABERTA, aguarda dependências e teste humano da anterior. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
Não basta aparecer “enviado” no site. Precisamos conferir se o pedido chegou a quem vai atender e se um visitante não consegue ver informações de outro.

### O que você faz, passo a passo
Com o Maestro, faça um pedido fictício e confira no lugar combinado se chegou. Tente enviar um campo obrigatório em branco e veja se a mensagem explica o que corrigir. Confirme quem vai acompanhar pedidos e como saberá que tem pedido novo. Se não conseguir ver o destino, conte isso; não marque como pronto.

### O que o Maestro vai construir ou preparar
Executar prova do destino, acesso autorizado/negado e deduplicação; simular indisponibilidade de forma segura sem perturbar produção. Mostrar o fluxo operacional ao responsável. Registrar evidências sanitizadas, sem transformar consulta de formulário em classificação automática de lead. Revalidar consentimento/retenção e sinalizar pendências antes do go-live.

### Como você confere e dá seu feedback
Celso mostra pedido fictício no destino correto e explica como será atendido; prova negativa de acesso e falha/retry passa. Aceite humano explícito ou task permanece aberta.

### Onde parar e o que não fazer
Pedido enviado não equivale a diagnóstico realizado nem relação profissional constituída.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.

## F1-T13 — Entender a calculadora e reunir as regras com o contador

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-005. **Critérios:** CP-014,CP-015. **Dependência:** T12 aceita; não exige regras tributárias prontas para começar a explicação. **Estado:** ABERTA, aguarda dependências e teste humano da anterior. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
Uma calculadora é uma ferramenta em que a pessoa preenche informações e recebe um resultado estimado. Neste projeto, a ideia é mostrar cenários da transição tributária para o público agro. Ela não descobre regras sozinha, não faz o imposto definitivo nem substitui o contador ou a análise jurídica. Uma tela com números não prova que a conta está certa.

### O que você faz, passo a passo
Diga: “Explique minha calculadora com um exemplo fictício e me diga o que falta definir.” O Maestro deve explicar o que entra e o que sai sem usar números fiscais inventados. Depois você e seu contador respondem, aos poucos: quem pode usar; qual dúvida ela responde; quais dados pedir; que regras/documentos sustentam a conta; um exemplo calculado e o resultado esperado; quais casos ela não atende; quem confere e aprova. Se não souber, diga “vou conferir com meu contador”.

### O que o Maestro vai construir ou preparar
Inspecionar em modo leitura a calculadora existente para explicar apenas o que é verificável; se acesso não disponível, declarar lacuna. Demonstrar a estrutura de entradas→regras→resultado sem produzir orientação fiscal. Perguntar uma questão por vez e pular o que estiver respondido e vigente no documento. Registrar B-CALC: objetivo, público, ano/período, entradas/unidades, regra/fórmula, fontes oficiais/vigência, cenários e casos de teste aprovados, precisão/arredondamento, limites, responsável, disclaimer/versão e condição de suspensão. Nenhum parâmetro tributário é inferido de código existente ou busca por IA sem aprovação humana. Identificar o que Celso responde e o que depende do contador.

### Como você confere e dá seu feedback
Entregar ficha compreensível: “o que a calculadora faz”, “o que não faz”, “o que já sabemos” e “o que falta você/contador responderem”. Preparação pode ser aceita com pendências explicitamente registradas; NÃO equivale a B-CALC completo nem aceite da calculadora. Reforma/implementação só na F2 após liberação de Ramon e metodologia/testes aprovados.

### Onde parar e o que não fazer
Não alterar cálculo, inventar alíquota/fórmula, validar resultado pelo código ou cobrar todas as respostas numa única mensagem. Pendências da calculadora não impedem preparar o site.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.

## F1-T14 — Revisar o conjunto e preparar a próxima etapa

**Responsável pela execução:** Maestro. **Sua participação:** responder/confirmar informações e testar. **SPEC:** SPEC-1-005. **Critérios:** CP-016. **Dependência:** T13 preparação aceita; T04..12 aceitas; três tarefas históricas preservadas. **Estado:** ABERTA, aguarda dependências e teste humano da anterior. **Prazo:** a combinar, sem nova data presumida.

### O que é e por que estamos fazendo
Vamos percorrer o site inteiro como se você fosse o visitante: conhecer a empresa, entender um serviço, abrir o WhatsApp e pedir uma avaliação. A calculadora será tratada de acordo com o que já foi validado, sem apresentar um cálculo sem conferência como pronto.

### O que você faz, passo a passo
Abra a prévia e diga ao Maestro: “Vamos conferir o site inteiro.” Faça o roteiro com ele. Diga o que precisa melhorar. Ao terminar, ele mostra o que ficou pronto e o que ainda depende do contador ou de você. Só depois pede ao Ramon a liberação da próxima fase. O site não vai para o ar sem autorização.

### O que o Maestro vai construir ou preparar
Executar matriz F1: identidade/fonte e serviços, sem blog/newsletter; diagnóstico sintético com recebimento real no destino de teste, WhatsApp confirmado sem envio, navegação/rolagem/teclado/mobile, privacidade, noindex e recuperação. Calculadora sem validação fica identificada/bloqueada para uso público, preservando código/histórico; escolher exposição em produção somente com aprovação e prova, não esconder apagando. Explicar pendências e pedir feedback. Registrar handoff: aceites/provas e portões B-CALC e go-live. Consultor decide F2; não reabrir concluídas nem solicitar aprovação do consultor por task.

### Como você confere e dá seu feedback
Tabela de cobertura CP-001..016 com evidência, pendência ou não aplicável justificado; roteiro humano aceito. Testes do aplicativo ocorrerão ao executar as tasks, não nesta autoria documental.

### Onde parar e o que não fazer
Não declarar calculadora finalizada, site publicado, F2 liberada ou resultado comercial alcançado.

**Roteiro obrigatório do Maestro:** antes, explicar “vamos fazer X para você conseguir Y”; depois, entregar link da prévia e até três ações claras para testar. Perguntar “O que achou? Quer mudar algo?”. Ajustar nesta tarefa até o aceite explícito, salvar prova/teste humano e só então apresentar a próxima. Não pedir nova aprovação do consultor entre tarefas da fase liberada; decisões técnicas sem acesso e a próxima fase vão ao Ramon.



## Tasks

| ID | Tarefa | Dono | SPEC | Critério | Subseção / prova | Pré-condição | Ponto de parada | Status |
|---|---|---|---|---|---|---|---|---|
| F1-T04 | Entender o projeto e organizar o portfólio enviado | Maestro | SPEC-1-002 | CP-001,CP-002 | TDD/T04: Celso confere resumo e mapa de páginas. Registrar quais pontos aprovou e quais faltam. Evidência: mapa com referência à fonte e aceite da organização, não publicação. | T03 aceita; portfólio do Ramon disponível para textos reais | Não aceitar ausência de reclamação como aprovação. Nome final, logo e fatos ausentes não são inventados. | ABERTA |
| F1-T05 | Organizar a aparência agro e limpar a navegação | Maestro | SPEC-1-002 | CP-003,CP-004 | TDD/T05: Prévia antes/depois, home e menu sem blog/newsletter nem links órfãos; teste do menu no celular. Celso comenta e aprova visual ou pede ajustes. Repetir nesta task até aceite. | T04 aceita para conteúdo; identidade pendente admite somente prévia claramente provisória | Não apagar dados, mudar marca/repo/domínio ou publicar. Não tocar calculadora além de manter estado seguro/links de demonstração não validada. | ABERTA |
| F1-T06 | Apresentar os serviços e conferir os textos do site | Maestro | SPEC-1-002 | CP-002,CP-005,CP-006 | TDD/T06: Jornada início→serviço e retorno funciona. Testes negativos: texto não aprovado, promessa de êxito, PII e script não publicam; recuperação preserva versão anterior. Textos reais aprovados por Celso. | T05 aceita e portfólio disponível/aprovado | Não criar serviço, depoimento, cliente ou credencial. Se revisão jurídica faltar, prévia restrita/noindex, sem liberar público. | ABERTA |
| F1-T07 | Preparar títulos e informações técnicas das páginas | Maestro | SPEC-1-003 | CP-007 | TDD/T07: Relatório por rota com títulos/descrições, sitemap e robots coerentes; crawl sem links críticos quebrados, preview noindex. Celso confere títulos. | T06 aceita | Nenhuma indexação produtiva automática ou garantia de tráfego. | ABERTA |
| F1-T08 | Testar o site no celular e facilitar a navegação | Maestro | SPEC-1-003 | CP-008 | TDD/T08: Capturas e relatório técnico com navegação/rolagem e CTAs utilizáveis em ambos viewports; Celso executa roteiro e confirma que consegue usar. | T07 aceita | Falha crítica mantém task aberta; não maquiar resultado de auditoria. | ABERTA |
| F1-T09 | Confirmar seu WhatsApp e colocar o botão de contato | Maestro | SPEC-1-004 | CP-009 | TDD/T09: Testar número inválido/vazio (não ativar), destino confirmado (abrir conversa correta), celular/desktop/teclado e ausência de envio automático. Captura sem dados de conversa + confirmação de Celso. | T08 aceita | Clique não é mensagem enviada, lead, contratação ou autorização para disparo. | ABERTA |
| F1-T10 | Decidir como o visitante pede um diagnóstico | Maestro | SPEC-1-004 | CP-010 | TDD/T10: Contrato B-DIAG assinado por aceite explícito de Celso nos itens definidos; lista clara do que vai acontecer após envio e de quem fará atendimento. Se houver dependência técnica externa, registrar Ramon como dono e parar somente essa capacidade. | T09 aceita | Sem definição de destino e proteção dos dados, não implementar formulário produtivo nem inventar destinatário. | ABERTA |
| F1-T11 | Construir o pedido de diagnóstico em ambiente de teste | Maestro | SPEC-1-004 | CP-011,CP-012 | TDD/T11: RED sem campo/consentimento/permissão e com retry; GREEN pedido sintético recebido uma vez no destino aprovado e consulta restrita; erro de destino não comunica sucesso falso. Regressão de acesso público, XSS, logs e recuperação. Build/testes do projeto e roteiro humano. | T10 aceita e B-DIAG completo, acesso técnico demonstrado | Nenhuma coleta real/publicação até autorização específica e política aplicada; nenhuma alteração do schema/modelo aceito fora do necessário e autorizado na SPEC. | ABERTA |
| F1-T12 | Conferir quem recebe os diagnósticos e testar problemas | Maestro | SPEC-1-004 | CP-013 | TDD/T12: Celso mostra pedido fictício no destino correto e explica como será atendido; prova negativa de acesso e falha/retry passa. Aceite humano explícito ou task permanece aberta. | T11 aceita | Pedido enviado não equivale a diagnóstico realizado nem relação profissional constituída. | ABERTA |
| F1-T13 | Entender a calculadora e reunir as regras com o contador | Maestro | SPEC-1-005 | CP-014,CP-015 | TDD/T13: Entregar ficha compreensível: “o que a calculadora faz”, “o que não faz”, “o que já sabemos” e “o que falta você/contador responderem”. Preparação pode ser aceita com pendências explicitamente registradas; NÃO equivale a B-CALC completo nem aceite da calculadora. Reforma/implementação só na F2 após liberação de Ramon e metodologia/testes aprovados. | T12 aceita; não exige regras tributárias prontas para começar a explicação | Não alterar cálculo, inventar alíquota/fórmula, validar resultado pelo código ou cobrar todas as respostas numa única mensagem. Pendências da calculadora não impedem preparar o site. | ABERTA |
| F1-T14 | Revisar o conjunto e preparar a próxima etapa | Maestro | SPEC-1-005 | CP-016 | TDD/T14: Tabela de cobertura CP-001..016 com evidência, pendência ou não aplicável justificado; roteiro humano aceito. Testes do aplicativo ocorrerão ao executar as tasks, não nesta autoria documental. | T13 preparação aceita; T04..12 aceitas; três tarefas históricas preservadas | Não declarar calculadora finalizada, site publicado, F2 liberada ou resultado comercial alcançado. | ABERTA |

