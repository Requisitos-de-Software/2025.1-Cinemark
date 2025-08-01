## Introdução

A partir das técnicas de elicitação aplicadas (storytelling, questionário, introspecção e análise de interface de usuário), foram levantados e documentados os requisitos do sistema. A Tabela 1 apresenta os requisitos elicitados, categorizando-os em requisitos funcionais (RF) e não funcionais (RNF), bem como seu status atual de implementação e a rastreabilidade com as fontes que os originaram.

---

## Metodologia

A elicitação dos requisitos foi realizada utilizando quatro técnicas: **storytelling**, **questionário**, **introspecção** e **análise de interface de usuário**. Cada técnica foi aplicada para identificar funcionalidades e características do sistema, resultando na documentação apresentada na Tabela 1.

Os requisitos foram classificados em **Requisitos Funcionais (RF)** e **Requisitos Não Funcionais (RNF)**, com rastreabilidade às fontes que os originaram. A Tabela 1 também apresenta o status de implementação de cada requisito na data atual (04/05/2025), permitindo o acompanhamento do progresso do projeto.

---

##  Legenda da tabela 1

- RQx: Requisito Nº X
- RF: Requisito Funcional
- RNF: Requisito Não Funcional
- IS: Requisito elicitado pela técnica de [Introspecção](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/)
- AI: Requisito elicitado pela técnica de [Análise de Interface de Usuário (UI)](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/)
- ST: Requisito elicitado pela técnica de [Storytelling](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/storytelling/)
- Q: Requisito elicitado pela técnica de [Questionário](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/questionario/)

## Tabela 1 – Requisitos Elicitados (Versão 2.0)

| ID   | Descrição                                                                                                             | Rastreabilidade      | Categoria | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | -------------------- | --------- | ------------ |
| RQ01  | Exibir na tela inicial filmes em cartaz, com pôsteres, novidades e promoções.                                          | [IS01](../elicitação/introspecção.md#IS01), [AI01](../elicitação/analiseUI.md#AI01)            | RF        | Sim          |
| RQ02A  | Detectar localização automaticamente.                                                      | [IS02](../elicitação/introspecção.md#IS02)            | RF        | Sim          |
| RQ02B  | Permitir alteração manual da localização.                                                      | [AI02](../elicitação/analiseUI.md#AI02)            | RF        | Sim          |
| RQ03  | Navegar por abas: Home, Filmes, Cinemas, Snack Bar, Club e Mais.                                                       | [AI03](../elicitação/analiseUI.md#AI03)                 | RF        | Sim          |
| RQ04  | Autenticar usuário por e-mail e senha.                                                                                 | [AI04](../elicitação/analiseUI.md#AI04)                 | RF        | Sim          |
| RQ05  | Buscar filmes por nome.                                                                                                | [AI05](../elicitação/analiseUI.md#AI05)                 | RF        | Sim          |
| RQ06  | Listar filmes em cartaz, pré-venda e futuros lançamentos.                                                              | [AI06](../elicitação/analiseUI.md#AI06)                 | RF        | Sim          |
| RQ07  | Exibir informações do filme (título, sinopse, gênero, duração, direção, elenco, distribuidor, origem).                 | [IS03](../elicitação/introspecção.md#IS03), [AI07](../elicitação/analiseUI.md#AI07)            | RF        | Sim          |
| RQ08  | Exibir sessões com data, horário, idioma, formato e sala.                                                              | [IS04](../elicitação/introspecção.md#IS04), [ST01](../elicitação/storytelling.md#ST01), [AI08](../elicitação/analiseUI.md#AI08), [Q01](../elicitação/questionario.md#Q01)      | RF        | Sim          |
| RQ09  | Permitir compra de ingressos com cartão de crédito, débito ou Pix.                                                     | [IS05](../elicitação/introspecção.md#IS05), [AI14](../elicitação/analiseUI.md#AI14), [Q02](../elicitação/questionario.md#Q02)            | RF        | Sim          |
| RQ10 | Armazenar cartões de pagamento cadastrados para uso em compras futuras.                                                | [IS06](../elicitação/introspecção.md#IS06)                  | RF        | Sim          |
| RQ11 | Permitir compra de múltiplos ingressos em uma única transação.                                                         | [IS07](../elicitação/introspecção.md#IS07)                  | RF        | Sim          |
| RQ12A | Exibir mapa da sala com indicação gráfica de assentos ocupados, livres e especiais. | [IS08](../elicitação/introspecção.md#IS08), [AI09](../elicitação/analiseUI.md#AI09)            | RF        | Sim          |
| RQ12B | Permitir seleção de assentos pelos usuários. | [IS08](../elicitação/introspecção.md#IS08)            | RF        | Sim          |
| RQ13 | Exigir seleção de ao menos um assento antes de prosseguir.                                                             | [AI10](../elicitação/analiseUI.md#AI10)                 | RF        | Sim          |
| RQ14 | Definir tipo de ingresso por assento (inteira, meia, convênio, voucher).                                               | [AI11](../elicitação/analiseUI.md#AI11)                 | RF        | Sim          |
| RQ15 | Integrar bomboniere ao app para compra antecipada de itens.                                          | [IS11](../elicitação/introspecção.md#IS11), [AI12](../elicitação/analiseUI.md#AI12)           | RF        | Sim          |
| RQ16A | Exibir resumo da compra.                                                     | [AI13](../elicitação/analiseUI.md#AI13), [AI29](../elicitação/analiseUI.md#AI29)           | RF        | Sim          |
| RQ16B | Permitir aplicação de cupom de desconto.                                                     | [AI13](../elicitação/analiseUI.md#AI13), [AI29](../elicitação/analiseUI.md#AI29)           | RF        | Sim          |
| RQ17 | Gerar QR Code e chave Pix para pagamentos via Pix.                                                                     | [AI15](../elicitação/analiseUI.md#AI15)                 | RF        | Sim          |
| RQ18 | Disponibilizar ingresso digital no app.                                         | [IS09](../elicitação/introspecção.md#IS09), [ST03](../elicitação/storytelling.md#ST03)                  | RF        | Sim          |
| RQ19 | Salvar automaticamente ingressos na seção “Meus Ingressos” após confirmação de compra.                                        | [AI16](../elicitação/analiseUI.md#AI16)                 | RF        | Sim          |
| RQ20A | Permitir criação de conta (nome, e-mail, senha, CPF).                                      | [AI17](../elicitação/analiseUI.md#AI17)           | RF        | Sim          |
| RQ20B | Permitir login com Google/redes sociais.                                      | [IS26](../elicitação/introspecção.md#IS26)           | RF        | Não          |
| RQ21A | Recuperar conta por envio de link de redefinição de senha por e-mail. | [AI18](../elicitação/analiseUI.md#AI18)     | RF        | Sim          |
| RQ21B | Recuperar e-mail via CPF. | [AI19](../elicitação/analiseUI.md#AI19)     | RF        | Sim          |
| RQ21C | Redefinir e-mail com código de verificação. | [AI20](../elicitação/analiseUI.md#AI20)     | RF        | Sim          |
| RQ22A | Exibir histórico de filmes assistidos (data, horário, cinema).                    | [IS13](../elicitação/introspecção.md#IS13)           | RF        | Sim          |
| RQ22B | Exibir histórico de compras na bomboniere.                    | [IS14](../elicitação/introspecção.md#IS14)           | RF        | Sim          |
| RQ23A | Filtrar filmes por categoria.                                    | [IS15](../elicitação/introspecção.md#IS15)                 | RF        | Não          |
| RQ23B | O sistema deve exibir avaliações de plataformas externas, como o IMDB e Rotten Tomatoes.                                    | [IS15](../elicitação/introspecção.md#IS15)                 | RF        | Não          |
| RQ24 | Exibir trailers dentro do app.                                                                                         | [IS16](../elicitação/introspecção.md#IS16)                 | RF        | Não          |
| RQ25 | O fluxo de compra de ingresso do aplicativo deve possuir no máximo 5 etapas.                                       | [IS17](../elicitação/introspecção.md#IS17)                 | RF        | Não          |
| RQ26 | Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc).                      | [IS18](../elicitação/introspecção.md#IS18)                 | RF        | Não          |
| RQ27 | Permitir uso de pontos acumulados para desconto em ingressos e produtos.                                               | [IS19](../elicitação/introspecção.md#IS19), [Q03](../elicitação/questionario.md#Q03)                 | RF        | Sim          |
| RQ28 | Alertar usuário sobre pontos suficientes para ingresso grátis 3 dias antes da expiração.                                    | [IS20](../elicitação/introspecção.md#IS20)                 | RF        | Não          |
| RQ29A | Sugerir cinemas com base no histórico de visitas.                                              | [IS21](../elicitação/introspecção.md#IS21)                 | RF        | Não          |
| RQ29B | Sugerir cinemas com base na localização atual.                                               | [IS21](../elicitação/introspecção.md#IS21)                 | RF        | Não          |
| RQ30 | Permitir que o usuário salve cinemas como favoritos.                                                                   | [IS22](../elicitação/introspecção.md#IS22)                 | RF        | Não          |
| RQ31 | Permitir notificações personalizadas (ex.: “avise-me quando o filme X entrar em cartaz”).                              | [IS23](../elicitação/introspecção.md#IS23)                 | RF        | Não          |
| RQ32A | Exibir recomendações de filmes baseadas em histórico.                                                   | [IS24](../elicitação/introspecção.md#IS24)                 | RF        | Não          |
| RQ32B | Exibir recomendações de filmes baseadas em preferências.                                                   | [IS24](../elicitação/introspecção.md#IS24)                 | RF        | Não          |
| RQ33 | Permitir alteração de preferências de idioma.                                                                          | [IS25](../elicitação/introspecção.md#IS25)                 | RF        | Não          |
| RQ34 | Disponibilizar área dedicada ao Cinemark Club, contendo ingressos, pontos acumulados e validade.                                | [IS12](../elicitação/introspecção.md#IS12)                 | RF        | Sim          |
| RQ35 | Exibir notificações de promoções com título, descrição e validade.                                                      | [AI32](../elicitação/analiseUI.md#AI32)                 | RF        | Sim          |
| RQ36 | Impedir avanço para pagamento com carrinho vazio.                                                                      | [AI30](../elicitação/analiseUI.md#AI30)                 | RF        | Sim          |
| RQ37 | O sistema deve permitir que o usuário edite o perfil de usuário, gerenciando dados pessoais e métodos de pagamento.                                     | [AI31](../elicitação/analiseUI.md#AI31)                 | RF        | Sim          |
| RQ38A | O sistema deve exibir mensagens de erro descritivas.                                                       | [ST05](../elicitação/storytelling.md#ST05), [IS37](../elicitação/introspecção.md#IS37) | RNF        | Sim      |
| RQ38B | O sistema deve exibir mensagens de confirmação para ações bem-sucedidas realizadas pelo usuário.                                                       | [ST05](../elicitação/storytelling.md#ST05), [IS37](../elicitação/introspecção.md#IS37) | RF        | Sim      |
| RQ39 | O aplicativo deve exibir avaliações dos filmes feitas por usuários.                                 | [IS15](../elicitação/introspecção.md#IS15)| RF        | Não          |
| RQ40 | Tempo de resposta de até 3 segundos em telas críticas (seleção de assentos, pagamento).                                | [IS29](../elicitação/introspecção.md#IS29), [Q09](../elicitação/questionario.md#Q09), [Q12](../elicitação/questionario.md#Q12)                 | RNF       | Sim          |
| RQ41 | Garantir uptime de 99,5% para funções críticas como seleção de ingressos, assentos, pagamento.                                                                        | [AI28](../elicitação/analiseUI.md#AI28)                 | RNF       | Sim          |
| RQ42 | Sistema responsivo e adaptável a diferentes tamanhos de tela (smartphone e tablet).                                    | [AI24](../elicitação/analiseUI.md#AI24)                 | RNF       | Sim          |
| RQ43 | O aplicativo deve permitir que o usuário realize todo o fluxo de seleção de assentos e compra de ingresso com, em média, 4 interações diretas com o sistema.                                                            | [IS28](../elicitação/introspecção.md#IS28)                 | RNF       | Sim          |
| RQ44 | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão.                              | [IS35](../elicitação/introspecção.md#IS35), [IS36](../elicitação/introspecção.md#IS36), [AI25](../elicitação/analiseUI.md#AI25), [ST05](../elicitação/storytelling.md#ST05)           | RNF       | Não          |
| RQ45 | As cores da interface do aplicativo devem possuir nível de contraste conforme a WCAG A/AA.                                                                             | [AI25](../elicitação/analiseUI.md#AI25)                 | RNF       | Não          |
| RQ46 | O aplicativo deve exibir uma tabela com o significado de cada ícone e cor presente no mapa de assento.                                                        | [AI22](../elicitação/analiseUI.md#AI22)                 | RNF       | Sim          |
| RQ47 | Atualizar automaticamente o valor total conforme seleção de ingressos e produtos.                                      | [AI23](../elicitação/analiseUI.md#AI23)                 | RNF       | Sim          |
| RQ48A | Proteger dados de pagamento.                                                   | [IS32](../elicitação/introspecção.md#IS32), [Q10](../elicitação/questionario.md#Q10)                 | RNF       | Sim          |
| RQ48B | Proteger histórico do usuário.                                                   | [IS32](../elicitação/introspecção.md#IS32), [Q10](../elicitação/questionario.md#Q10)                 | RNF       | Sim          |
| RQ49 | Autenticação por biometria ou PIN para operações sensíveis, como exclusão de conta, visualização de dados de pagamento.                                                            | [IS33](../elicitação/introspecção.md#IS33)                 | RNF       | Sim          |
| RQ50 | Notificações push customizáveis pelo usuário.                                                                          | [IS34](../elicitação/introspecção.md#IS34)                 | RNF       | Não          |
| RQ51 | Exibir mapa de assentos com indicação gráfica clara de ocupação e disponibilidade.                                     | [IS31](../elicitação/introspecção.md#IS31)                 | RNF       | Sim          |
| RQ52 | Limitar quantidade máxima de 20 unidades por item no Snack Bar.                                                        | [AI26](../elicitação/analiseUI.md#AI26)                 | RNF       | Sim          |
| RQ53 | O sistema deve manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra.               | [AI27](../elicitação/analiseUI.md#AI27)                 | RNF       | Sim          |
| RQ54 | Ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos).                                       | [AI33](../elicitação/analiseUI.md#AI33)                 | RNF       | Sim          |
| RQ55 | O sistema deve validar e-mail e senha antes de criação ou redefinição de conta.                | [AI34](../elicitação/analiseUI.md#AI34)                 | RNF       | Sim          |
| RQ56 | Remover automaticamente promoções expiradas da interface.                                                              | [AI35](../elicitação/analiseUI.md#AI35)                 | RNF       | Sim          |
| RQ57 | Validar dados pessoais no perfil antes de salvar.                                                                      | [AI36](../elicitação/analiseUI.md#AI36)                 | RNF       | Sim          |
| RQ58 | Fornecer comparação de preços entre cinemas.                                                                          | [Q04](../elicitação/questionario.md#Q04)                 | RF       | Não          |
| RQ59 | O aplicativo deve permitir que usuários avaliem filmes com escala de 1 a 5 estrelas dentro de um HUB de avaliações.                                                                              | [Q05](../elicitação/questionario.md#Q05)                 | RF       | Não          |
| RQ60 | Fornecer um Hub para crítica de filmes.                                                                               | [Q06](../elicitação/questionario.md#Q06)                 | RF       | Não          |
| RQ61 | Manter a conta logada após o login.                                                                                   | [Q07](../elicitação/questionario.md#Q07)                 | RF       | Sim          |
| RQ62 | Permitir que o usuário cancele compras.                                                                               | [Q08](../elicitação/questionario.md#Q08)                 | RF       | Sim          |
| RQ63 | O aplicativo deve consumir no máximo 200mb de memória RAM.                                                       | [Q11](../elicitação/questionario.md#Q11)                 | RNF       | Sim          |
| RQ64 | Permitir que o usuário exclua permanentemente sua conta.                                                       | [IS38](../elicitação/introspecção.md#IS38)                 | RF       | Sim          |
| RQ65 | Permitir ao usuário realizar logout de sua conta.                                                       | [IS39](../elicitação/introspecção.md#IS39)                 | RF       | Sim          |
| RQ66 | Permitir acesso ao ingresso offline, sem depender de conexão à internet na hora da sessão.                                                       | [IS10](../elicitação/introspecção.md#IS10), [IS30](../elicitação/introspecção.md#IS30)                 | RNF       | Não          |
| RQ67 | O aplicativo deve exibir, no menu inicial, um botão para acesso direto aos ingressos.                                                       | [IS27](../elicitação/introspecção.md#IS27)                 | RF       | Não          |

<font size="3"><p style="text-align: center">Autor(a): [Arthur Evangelista de Oliveira](https://github.com/arthurevg) e [Davi Camilo Menezes](https://github.com/Davicamilo23), 2025.</p></font>


## Tabela 2 - Apenas os Requisitos Não Implementados e Funcionais (Versão 2.0)

| ID   | Descrição                                                                                                             | Rastreabilidade      | Categoria | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | -------------------- | --------- | ------------ |
| RQ20B | Permitir login com Google/redes sociais.                                      | [IS26](../elicitação/introspecção.md#IS26)           | RF        | Não          |
| RQ23A | Filtrar filmes por categoria.                                    | [IS15](../elicitação/introspecção.md#IS15)                 | RF        | Não          |
| RQ23B | O sistema deve exibir avaliações de plataformas externas, como o IMDB e Rotten Tomatoes.                                    | [IS15](../elicitação/introspecção.md#IS15)                 | RF        | Não          |
| RQ24  | Exibir trailers dentro do app.                                                                                         | [IS16](../elicitação/introspecção.md#IS16)                 | RF        | Não          |
| RQ25  | O fluxo de compra de ingresso do aplicativo deve possuir no máximo 4 etapas.                                       | [IS17](../elicitação/introspecção.md#IS17)                 | RF        | Não          |
| RQ26  | Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc).                      | [IS18](../elicitação/introspecção.md#IS18)                 | RF        | Não          |
| RQ28 | Alertar usuário sobre pontos suficientes para ingresso grátis 3 dias antes da expiração.                                    | [IS20](../elicitação/introspecção.md#IS20)                 | RF        | Não          |
| RQ29A | Sugerir cinemas com base no histórico de visitas                                              | [IS21](../elicitação/introspecção.md#IS21)                 | RF        | Não          |
| RQ29B | Sugerir cinemas com base na localização atual.                                               | [IS21](../elicitação/introspecção.md#IS21)                 | RF        | Não          |
| RQ30  | Permitir que o usuário salve cinemas como favoritos.                                                                   | [IS22](../elicitação/introspecção.md#IS22)                 | RF        | Não          |
| RQ31  | Permitir notificações personalizadas (ex.: “avise-me quando o filme X entrar em cartaz”).                              | [IS23](../elicitação/introspecção.md#IS23)                 | RF        | Não          |
| RQ32A | Exibir recomendações de filmes baseadas em histórico.                                                   | [IS24](../elicitação/introspecção.md#IS24)                 | RF        | Não          |
| RQ32B | Exibir recomendações de filmes baseadas em preferências.                                                   | [IS24](../elicitação/introspecção.md#IS24)                 | RF        | Não          |
| RQ33  | Permitir alteração de preferências de idioma.                                                                          | [IS25](../elicitação/introspecção.md#IS25)                 | RF        | Não          |
| RQ39 | O aplicativo deve exibir avaliações dos filmes feitas por usuários.                                 | [IS15](../elicitação/introspecção.md#IS15)| RF        | Não          |
| RQ58 | Fornecer comparação de preços entre cinemas.                                                                          | [Q04](../elicitação/questionario.md#Q04)                 | RF       | Não          |
| RQ59 | O aplicativo deve permitir que usuários avaliem filmes com escala de 1 a 5 estrelas dentro de um HUB de avaliações.                                                                              | [Q05](../elicitação/questionario.md#Q05)                 | RF       | Não          |
| RQ60 | Fornecer um Hub para crítica de filmes.                                                                               | [Q06](../elicitação/questionario.md#Q06)                 | RF       | Não          |
| RQ67 | O aplicativo deve exibir, no menu inicial, um botão para acesso direto aos ingressos.                                                       | [IS27](../elicitação/introspecção.md#IS27)                 | RF       | Não          |

<font size="3"><p style="text-align: center">Autor(a): [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) e [Davi Camilo Menezes](https://github.com/Davicamilo23), 2025.</p></font>

## Tabela 3 - Apenas os Requisitos Não Implementados e Não Funcionais (Versão 2.0)

| ID   | Descrição                                                                                                             | Rastreabilidade      | Categoria | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | -------------------- | --------- | ------------ |
| RQ44 | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão.                              | [IS35](../elicitação/introspecção.md#IS35), [IS36](../elicitação/introspecção.md#IS36), [AI25](../elicitação/analiseUI.md#AI25), [ST05](../elicitação/storytelling.md#ST05)           | RNF       | Não          |
| RQ45 | As cores da interface do aplicativo devem possuir nível de contraste conforme a WCAG A/AA.                                                                             | [AI25](../elicitação/analiseUI.md#AI25)                 | RNF       | Não          |
| RQ50 | Notificações push customizáveis pelo usuário.                                                                          | [IS34](../elicitação/introspecção.md#IS34)                 | RNF       | Não          |
| RQ66 | Permitir acesso ao ingresso offline, sem depender de conexão à internet na hora da sessão.                                                       | [IS10](../elicitação/introspecção.md#IS10), [IS30](../elicitação/introspecção.md#IS30)                 | RNF       | Não          |

<font size="3"><p style="text-align: center">Autor(a): [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) e e [Davi Camilo Menezes](https://github.com/Davicamilo23), 2025.</p></font>

---

## Conclusão

Os requisitos elicitados por meio de técnicas como introspecção, análise de UI, questionários e storytelling foram fundamentais para compreender as necessidades e expectativas dos usuários. Com base nesses requisitos, aplicamos quatro técnicas distintas de priorização para organizar e hierarquizar as funcionalidades identificadas: 

- [Kano Model](https://requisitos-de-software.github.io/2025.1-Cinemark/prioriza%C3%A7%C3%A3o/kanomodel/)

- [Moscow](https://requisitos-de-software.github.io/2025.1-Cinemark/prioriza%C3%A7%C3%A3o/moscow/)

- [Three Level Scale](https://requisitos-de-software.github.io/2025.1-Cinemark/prioriza%C3%A7%C3%A3o/threelevelscale/)

- [100$](https://requisitos-de-software.github.io/2025.1-Cinemark/prioriza%C3%A7%C3%A3o/100%24/)

---

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  04/05/2025 |  Criação do Documento com Introdução, metodologia, e tabela com os requisitos elicitados |[Arthur Evangelista](https://github.com/arthurevg) | Todos |
| `1.1`  |  04/05/2025 | Ajuste na formatação | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.2`  |  04/05/2025 | Correções na rastreabilidade de alguns itens | [Arthur Evangelista](https://github.com/arthurevg)| [Artur de Camargos](https://github.com/ArturDCR) |
| `1.3`  |  04/05/2025 | Correções na rastreabilidade do RQ38 | [Euller Júlio](https://github.com/Potatoyz908) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.4`  |  11/05/2025 | Correções na tabela de requisitos elicitados | [Euller Júlio](https://github.com/Potatoyz908) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.5`  | 12/05/2025 | Adição da conclusão | [Arthur Evangelista](https://github.com/arthurevg) | [Artur de Camargos Rodrigues](https://github.com/ArturDCR) |
| `1.6`  | 12/05/2025 | Ajuste na legenda da tabela 1, na rastreabilidade e adição de RQ66 e RQ67 | [Davi Camilo](https://github.com/Davicamilo23) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.6.1` | 14/05/2025 | Ajuste no RQ66 | [Davi Camilo](https://github.com/Davicamilo23) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.7` | 24/05/2025 | Adição das tabelas 2 e 3 para melhor visualização dos requisitos não implementados | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.8` | 24/05/2025 | Correção do RQ29. Foi desmebrado em dois requisitos: RQ29A e RQ29B | [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Davi Camilo](https://github.com/Davicamilo23) |
| `2.0` | 02/07/2025 | Correção de todos os requisitos do projeto | [Davi Camilo](https://github.com/Davicamilo23) | Todos |
| `2.1`  |  05/07/2025 | Correções na rastreabilidade e na descrição dos RQ53 e RQ55 | [Euller Júlio](https://github.com/Potatoyz908) | [Artur de Camargos](https://github.com/ArturDCR) |
| `2.2`  |  05/07/2025 | Correção na escrita do RQ25 | [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Davi Camilo](https://github.com/Davicamilo23) |
