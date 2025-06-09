# Backward-From

## Introdução

A **rastreabilidade backward-from** (para trás, a partir de) descreve o processo de vincular um requisito à sua fonte ou origem. Esse tipo de rastreabilidade é fundamental para entender o contexto e a justificativa por trás de cada requisito, permitindo que a equipe de desenvolvimento compreenda por que um requisito foi criado e quais necessidades ele visa atender.

Em essência, a rastreabilidade backward-from permite que, a partir de um requisito já documentado, seja possível rastrear sua "vida" em direção ao passado, respondendo a perguntas como:

* **Quem** sugeriu o requisito?
* **De qual artefato** ou discussão ele se originou?
* **Por que** o requisito existe?

As fontes de um requisito podem incluir planos de negócio, documentos de estratégia da empresa, legislação, atas de reuniões, ou solicitações diretas de stakeholders.

### Aplicações e Vantagens

A principal vantagem da rastreabilidade backward-from é garantir que cada requisito tenha uma justificativa clara e documentada. Isso auxilia em diversas atividades do desenvolvimento de software:

* **Resolução de conflitos**: Permite identificar as origens de requisitos conflitantes, o que ajuda na busca por uma solução de consenso.
* **Análise de impacto**: Ao entender a origem e a motivação de um requisito, torna-se mais fácil avaliar as consequências de uma possível mudança ou exclusão.
* **Identificação de "gold-plating"**: Ajuda a identificar requisitos que não contribuem para nenhum objetivo de negócio ou não estão associados a nenhuma fonte, ou seja, requisitos que não precisariam ser implementados.
* **Gerenciamento do conhecimento**: Estabelece uma base para o gerenciamento do conhecimento organizacional, conectando as necessidades dos usuários à evolução do sistema.

## Metodologia

A metodologia utilizada para a construção da matriz de rastreabilidade backward-from foi baseada na identificação das fontes de origem dos requisitos, permitindo um mapeamento claro entre os requisitos e suas respectivas fontes. Essa abordagem facilita a análise do impacto de mudanças nos requisitos e a validação de sua implementação.

### Matriz de Rastreabilidade

Na Tabela 1, é apresentado o modelo de matriz de rastreabilidade backward-from utilizado para rastrear os requisitos a partir de suas fontes de origem. A matriz é composta por colunas que identificam o ID do requisito, a descrição do requisito, as fontes de origem e os tipos de fontes.

**Tabela 1**: Modelo de Matriz de Rastreabilidade Backward-From

| **ID do Requisito** | **Descrição do Requisito**                                          | **Fontes de Origem**                | **Atividade de Elicitação**         |
|---------------------|---------------------------------------------------------------------|------------------------------------|----------------------------|
| RQ-XX               | Descrição do requisito                     | ID de rastreabilidade de origem  | Nome das atividades de elicitação utilizdas   |
| RQ-YY               | Descrição do requisito                   | ID de rastreabilidade de origem      | Nome das atividades de elicitação utilizdas             |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31).</p></font>

#### Legenda da Matriz de Rastreabilidade

* **ID do Requisito**: Identificador único do requisito.
* **Descrição do Requisito**: Descrição do requisito rastreado.
* **Fontes de Origem**: Identificador do requisito de origem no artefato de origem, como introspecção, entrevista, questionário, etc. Exemplo: IS00,Q02, ST01, etc.
* **Atividade de Elicitação**: Descrição do tipo de fonte, como Introspecção, Entrevista, Questionário, etc.

## Integrantes do grupo envolvidos

**Tabela 2**: Integrantes do grupo envolvidos no artefato.

<div align="center">
	<div>
		<table>
			<thead>
					<tr>
						<th>Nome</th>
						<th>O que fez</th>
					</tr>
			</thead>
		<tbody>
					<tr>
						<td><a  href="https://github.com/ArturDCR">Artur de Camargos</a></td>
						<td>Lorem Ipsum</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/arthurevg">Arthur Evangelista</a></td>
						<td>Adicionou rastreabilidade dos seguintes requisitos: <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ10">RQ10</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ11">RQ11</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ12">RQ12</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ13">RQ13</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ14">RQ14</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ14">RQ14</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ15">RQ15</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ16">RQ16</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ17">RQ17</a> e
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ18">RQ18</a>.
						</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/Davicamilo23">Davi Camilo</a></td>
						<td>Adicionou rastreabilidade dos seguintes requisitos: <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ37">RQ37</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ38">RQ38</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ39">RQ39</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ40">RQ40</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ41">RQ41</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ42">RQ42</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ43">RQ43</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ44">RQ44</a> e <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ45">RQ45</a>.</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/Potatoyz908">Euller Júlio</a></td>
						<td>Adicionou rastreabilidade dos seguintes requisitos: <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ28">RQ28</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ29">RQ29</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ30">RQ30</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ31">RQ31</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ32">RQ32</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ33">RQ33</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ34">RQ34</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ35">RQ35</a> e <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ36">RQ36</a>.</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a></td>
						<td>Adicionou a Introdução, Metodologia, modelo de tabela Backward-From e rastreabilidade dos seguintes requisitos: <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ19">RQ19</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ20">RQ20</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ21">RQ21</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ22">RQ22</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ23">RQ23</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ24">RQ24</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ25">RQ25</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ26">RQ26</a> e <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ27">RQ27</a>
					</tr>
					<tr>
						<td><a  href="https://github.com/tiagobalieiro">Tiago Antunes Balieiro</a></td>
						<td>Adicionou rastreabilidade dos seguintes requisitos: <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ01">RQ01</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ02">RQ02</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ03">RQ03</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ04">RQ04</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ05">RQ05</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ06">RQ06</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ07">RQ07</a>,
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ08">RQ08</a> e
						<a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ09">RQ09</a>.
						</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/pedroeverton217">Pedro Everton</a></td>
						<td>Lorem Ipsum</td>
					</tr>
			</tbody>
		</table>
	</div>
</div>

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31).</p></font>

## Matriz de Rastreabilidade Backward-From

Na Tabela 3, apresentamos a matriz de rastreabilidade backward-from, que relaciona os requisitos com suas fontes de origem e as atividades de elicitação correspondentes

**Tabela 3**: Matriz de Rastreabilidade Backward-From

| **ID do Requisito** | **Descrição do Requisito** | **Fontes de Origem** | **Atividade de Elicitação** |
|---------------------|----------------------------|-----------------------|----------------------|
| [RQ01](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ01) | Exibir na tela inicial filmes em cartaz, com pôsteres, novidades e promoções. | [IS01](../elicitação/introspecção.md#IS01), [AI01](../elicitação/analiseUI.md#AI01) | Instrospecção, Análise de Interface |
| [RQ02](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ02) | Detectar localização automaticamente e permitir alteração manual. |  [IS02](../elicitação/introspecção.md#IS02), [AI02](../elicitação/analiseUI.md#AI02) | Instrospecção, Análise de Interface |
| [RQ03](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ03) | Navegar por abas: Home, Filmes, Cinemas, Snack Bar, Club e Mais. | [AI03](../elicitação/analiseUI.md#AI03) | Análise de Interface |
| [RQ04](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ04) | Autenticar usuário por e-mail e senha. | [AI04](../elicitação/analiseUI.md#AI04) | Análise de Interface |
| [RQ05](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ05) | Buscar filmes por nome. | [AI05](../elicitação/analiseUI.md#AI05) | Análise de Interface |
| [RQ06](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ06) | Listar filmes em cartaz, pré-venda e futuros lançamentos. | [AI06](../elicitação/analiseUI.md#AI06) | Análise de Interface |
| [RQ07](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ07) | Exibir informações do filme (título, sinopse, gênero, duração, direção, elenco, distribuidor, origem). | [IS03](../elicitação/introspecção.md#IS03), [AI07](../elicitação/analiseUI.md#AI07) | Instrospecção, Análise de Interface |
| [RQ08](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ08) | Exibir sessões com data, horário, idioma, formato e sala. | [IS04](../elicitação/introspecção.md#IS04), [ST01](../elicitação/storytelling.md#ST01), [AI08](../elicitação/analiseUI.md#AI08), [Q01](../elicitação/questionario.md#Q01) | Introspecção, Storytelling, Análise de Interface, Questionário |
| [RQ09](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ09) | Permitir compra de ingressos com cartão de crédito, débito ou Pix. | [IS05](../elicitação/introspecção.md#IS05), [AI14](../elicitação/analiseUI.md#AI14), [Q02](../elicitação/questionario.md#Q02) | Introspecção, Análise de Interface, Questionário |
| [RQ10](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ10) | Armazenar cartões de pagamento cadastrados para uso em compras futuras. | [IS06](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS06) | Introspecção |
| [RQ11](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ11) | Permitir compra de múltiplos ingressos em uma única transação. | [IS07](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS07) | Introspecção |
| [RQ12](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ12) |Exibir mapa da sala com indicação gráfica de assentos ocupados, livres e especiais, e permitir seleção pelos usuários. | [IS08](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS08), [AI09](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI09) | Introspecção, Análise de Interface |
| [RQ13](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ13) | Exigir seleção de ao menos um assento antes de prosseguir. | [AI10](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI10) | Análise de Interface |
| [RQ14](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ14) | Definir tipo de ingresso por assento (inteira, meia, convênio, voucher). | [AI11](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI11) | Análise de Interface |
| [RQ15](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ15) | Integrar bomboniere ao app para compra antecipada de itens e retirada rápida. |  [IS11](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS11), [AI12](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI12) | Introspecção, Análise de Interface |
| [RQ16](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ16) | Exibir resumo da compra e permitir aplicação de cupom de desconto. | [AI13](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI13), [AI29](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI29) | Análise de Interface |
| [RQ17](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ17) | Gerar QR Code e chave Pix para pagamentos via Pix. | [AI15](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI15) | Análise de Interface |
| [RQ18](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ18) | Disponibilizar ingresso digital no app, eliminando a necessidade de impressão. |  [IS09](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS09), [ST03](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/storytelling/#ST03) | Introspecção, Análise de Interface |
| [RQ19](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ19) | Salvar automaticamente ingressos na seção “Meus Ingressos” após confirmação de compra. | [AI16](../elicitação/analiseUI.md#AI16) | Análise de Interface |
| [RQ20](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ20) | Permitir criação de conta (nome, e-mail, senha, CPF) e login com Google/redes sociais. |[AI17](../elicitação/analiseUI.md#AI17), [IS26](../elicitação/introspecção.md#IS26) | Análise de Interface, Introspecção|
| [RQ21](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ21) | Recuperação de conta: enviar link de redefinição de senha por e-mail, recuperar e-mail via CPF e redefinir com código. | [AI18](../elicitação/analiseUI.md#AI18), [AI19](../elicitação/analiseUI.md#AI19), [AI20](../elicitação/analiseUI.md#AI20) | Análise de Interface |
| [RQ22](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ22) | Exibir histórico de filmes assistidos (data, horário, cinema) e histórico de compras na bomboniere. |[IS13](../elicitação/introspecção.md#IS13), [IS14](../elicitação/introspecção.md#IS14) | Introspecção |
| [RQ23](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ23) | Filtrar filmes por categoria e exibir avaliações de público e plataformas externas. |[IS15](../elicitação/introspecção.md#IS15) | Introspecção |
| [RQ24](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ24) | Exibir trailers dentro do app. | [IS16](../elicitação/introspecção.md#IS16) | Introspecção |
| [RQ25](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ25) | Oferecer fluxo de compra simplificado, com o mínimo de toques até a confirmação. | [IS17](../elicitação/introspecção.md#IS17) | Introspecção |
| [RQ26](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ26) | Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc). | [IS18](../elicitação/introspecção.md#IS18) | Introspecção |
| [RQ27](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ27) | Permitir uso de pontos acumulados para desconto em ingressos e produtos. | [IS19](../elicitação/introspecção.md#IS19), [Q03](../elicitação/questionario.md#Q03) | Introspecção, Questionário |
| [RQ28](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ28) | Alertar usuário sobre pontos suficientes para ingresso grátis e antes da expiração. | [IS20](../elicitação/introspecção.md#IS20) | Introspecção |
| [RQ29](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ29) | Sugerir cinemas com base no histórico de visitas e na localização atual. | [IS21](../elicitação/introspecção.md#IS21) | Introspecção |
| [RQ30](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ30) | Permitir que o usuário salve cinemas como favoritos. | [IS22](../elicitação/introspecção.md#IS22) | Introspecção |
| [RQ31](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ31) | Permitir notificações personalizadas (ex.: “avise-me quando o filme X entrar em cartaz”). | [IS23](../elicitação/introspecção.md#IS23) | Introspecção |
| [RQ32](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ32) | Exibir recomendações de filmes baseadas em histórico e preferências. | [IS24](../elicitação/introspecção.md#IS24) | Introspecção |
| [RQ33](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ33) | Permitir alteração de preferências de idioma. | [IS25](../elicitação/introspecção.md#IS25) | Introspecção |
| [RQ34](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ34) | Disponibilizar área dedicada ao Cinemark Club: ingressos, pontos acumulados e validade. | [IS12](../elicitação/introspecção.md#IS12) | Introspecção |
| [RQ35](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ35) | Exibir notificações e promoções com título, descrição e validade. | [AI32](../elicitação/analiseUI.md#AI32) | Análise de Interface |
| [RQ36](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ36) | Impedir avanço para pagamento com carrinho vazio. | [AI30](../elicitação/analiseUI.md#AI30) | Análise de Interface |
| [RQ37](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ37) | Criar e editar perfil do usuário, gerenciar dados pessoais e métodos de pagamento. | [AI31](../elicitação/analiseUI.md#AI31) | Análise de Interface |
| [RQ38](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ38) | Mensagens de erro claras e confirmações de ações para o usuário. | [ST05](../elicitação/storytelling.md#ST05), [IS37](../elicitação/introspecção.md#IS37) | Storytelling, Introspecção |
| [RQ39](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ39) | Exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas. | [IS15](../elicitação/introspecção.md#IS15) | Introspecção |
| [RQ40](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ40) | Tempo de resposta de até 3 segundos em telas críticas (seleção de assentos, pagamento). | [IS29](../elicitação/introspecção.md#IS29), [Q09](../elicitação/questionario.md#Q09), [Q12](../elicitação/questionario.md#Q12) | Introspecção, Questionário |
| [RQ41](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ41) | Garantir uptime de 99,5% para funções críticas. | [AI28](../elicitação/analiseUI.md#AI28) | Análise de Interface |
| [RQ42](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ42) | Sistema responsivo e adaptável a diferentes tamanhos de tela (smartphone e tablet). | [AI24](../elicitação/analiseUI.md#AI24) | Análise de Interface |
| [RQ43](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ43) | 	Interface intuitiva, com navegação fácil e boa usabilidade. | [IS28](../elicitação/introspecção.md#IS28) | Introspecção |
| [RQ44](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ44) | 	Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão. | [IS35](../elicitação/introspecção.md#IS35), [IS36](../elicitação/introspecção.md#IS36), [AI25](../elicitação/analiseUI.md#AI25), [ST05](../elicitação/storytelling.md#ST05) | Introspecção, Análise de Interface, Storytelling |
| [RQ45](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ45) | Contraste de interface conforme WCAG A/AA. | [AI25](../elicitação/analiseUI.md#AI25) | Análise de Interface |
| [RQ46](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ46) | xxxxx | xxxxx | xxxxx |
| [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ47) | xxxxx | xxxxx | xxxxx |
| [RQ48](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ48) | xxxxx | xxxxx | xxxxx |
| [RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ49) | xxxxx | xxxxx | xxxxx |
| [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ50) | xxxxx | xxxxx | xxxxx |
| [RQ51](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ51) | xxxxx | xxxxx | xxxxx |
| [RQ52](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ52) | xxxxx | xxxxx | xxxxx |
| [RQ53](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ53) | xxxxx | xxxxx | xxxxx |
| [RQ54](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ54) | xxxxx | xxxxx | xxxxx |
| [RQ55](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ55) | xxxxx | xxxxx | xxxxx |
| [RQ56](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ56) | xxxxx | xxxxx | xxxxx |
| [RQ57](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ57) | xxxxx | xxxxx | xxxxx |
| [RQ58](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ58) | xxxxx | xxxxx | xxxxx |
| [RQ59](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ59) | xxxxx | xxxxx | xxxxx |
| [RQ60](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ60) | xxxxx | xxxxx | xxxxx |
| [RQ61](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ61) | xxxxx | xxxxx | xxxxx |
| [RQ62](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ62) | xxxxx | xxxxx | xxxxx |
| [RQ63](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ63) | xxxxx | xxxxx | xxxxx |
| [RQ64](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ64) | xxxxx | xxxxx | xxxxx |
| [RQ65](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ65) | xxxxx | xxxxx | xxxxx |
| [RQ66](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ66) | xxxxx | xxxxx | xxxxx |
| [RQ67](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#:~:text=RQ67) | xxxxx | xxxxx | xxxxx |

## Referências Bibliográficas

> **SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado.** Rastreabilidade de requisitos. Rio de Janeiro: Departamento de Informática, Pontifícia Universidade Católica do Rio de Janeiro, 2005. (Monografias em Ciência da Computação, n. 20/05). ISSN 0103-9741.
> **SERRANO, Milene; SERRANO, Maurício.** Requisitos – Aula 26. Universidade de Brasília, Campus Gama (UnB Gama). Material de aula.

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  06/06/2025 |  Criação do Documento | [Pedro Everton](https://github.com/pedroeverton217) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.1`  |  07/06/2025 |  Adição da tabela de integrantes do grupo |  [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Pedro Everton](https://github.com/pedroeverton217) |
| `1.2`  |  07/06/2025 |  Adição de introdução e metodologia de rastreabilidade Backward-From | [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.3`  |  07/06/2025 |  Adição da tabela Backward-From | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |[Davi Camilo](https://github.com/Davicamilo23)
| `1.4`  |  07/06/2025 |  Adição de rastreabilidade dos requisitos RQ19, RQ20, RQ21, RQ22, RQ23, RQ24, RQ25, RQ26, RQ27  | [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Euller Júlio](https://github.com/Potatoyz908) |
| `1.5`  |  08/06/2025 |  Adição de rastreabilidade dos requisitos RQ28 a RQ36  | [Euller Júlio](https://github.com/Potatoyz908) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.6`  |  08/06/2025 |  Adição de rastreabilidade dos requisitos RQ10 a RQ18  | [Arthur Evangelista](https://github.com/arthurevg) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.7`  |  08/06/2025 |  Adição de rastreabilidade dos requisitos RQ37 a RQ45  | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg) |

| `1.8`  |  08/06/2025 |  Adição de rastreabilidade dos requisitos RQ01 a RQ09  | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Euller Júlio](https://github.com/Potatoyz908) |

