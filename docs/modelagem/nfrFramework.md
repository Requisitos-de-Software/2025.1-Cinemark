## Integrantes do grupo envolvidos

**Tabela 1**

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
						<td>Lorem Ipsum</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/Davicamilo23">Davi Camilo</a></td>
						<td>Lorem Ipsum</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/Potatoyz908">Euller Júlio</a></td>
						<td>Lorem Ipsum</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a></td>
						<td>Lorem Ipsum</td>
					</tr>
                    <tr>
						<td><a  href="https://github.com/pedroeverton217">Pedro Everton</a></td>
						<td>Lorem Ipsum</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/tiagobalieiro">Tiago Antunes Balieiro</a></td>
						<td>Adicionou o Modelo de tabela de Cartão de Especificação</td>
					</tr>
			</tbody>
		</table>
	</div>
</div>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

## Introdução

Uma forma de garantir que o software atenda às expectativas dos usuários e stakeholders é por meio da definição de requisitos não funcionais (NFRs). Esses requisitos abrangem aspectos como desempenho, segurança, usabilidade, manutenibilidade e portabilidade. O NFR Framework é uma abordagem que ajuda a identificar, categorizar e priorizar esses requisitos, garantindo que o software seja desenvolvido de acordo com as necessidades do negócio e dos usuários.

## Softgoal Interdependency Graph - SIG

Um Softgoal Interdependency Graph (SIG) é uma representação gráfica usada no framework de Requisitos Não Funcionais (NFR) para ilustrar como diferentes objetivos de qualidade (softgoals) se influenciam mutuamente. Nele, cada softgoal aparece como um nó, e as arestas indicam relações de contribuição—como “ajuda”, “prejudica”, “faz” ou “quebra”—entre esses objetivos. Isso permite visualizar conflitos e sinergias entre requisitos de qualidade (por exemplo, segurança vs. usabilidade) e apoiar a tomada de decisões durante o projeto de sistemas.

### Tipos de SIG

Segundo Silva, 2019, existem 3 tipos de SIG:

* **Softgoals NFR**: Representam diretamente requisitos não-funcionais, como “Confiabilidade”, “Desempenho” etc. Eles não têm critérios de satisfação exatos, mas indicam qualidades que o sistema deve alcançar.

* **Softgoals de Operacionalização**: São as alternativas de implementação que “operacionalizam” (ou viabilizam) um softgoal NFR. Ex.: “Usar comunicação via SSL” para atender ao softgoal “Segurança”.

* **Softgoals de Afirmação**:(“claims”) Expressam justificativas, restrições de domínio ou prioridades que impactam a escolha de operacionalizações. Por exemplo, “Alta carga de trabalho” pode justificar a escolha de uma solução que priorize desempenho, mesmo que aumente o consumo de energia.

<p align="center">Figura 1 - Tipos de Softgoal</p>

![SOFTGOALS](https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Cinemark/main/docs/assets/modelagem/softgoals.png)

<p align="center"><em>Fonte: SILVA, 2019</em></p>

### Contribuições e Tipos no NFR Framework

Durante o processo de refinamento, um softgoal mais específico (descendente) pode influenciar a realização de um softgoal mais amplo (ascendente), seja ajudando ou prejudicando sua satisfação, em maior ou menor grau.
A “satisfação de um softgoal” significa que o requisito não funcional foi atendido de maneira aceitável, ainda que não completamente ou de forma exata. Abaixo estão os tipos de contribuição e suas descrições:

* **AND**: Todos os softgoals filhos precisam ser satisfeitos para que o pai seja satisfeito.

* **OR**: A satisfação de pelo menos um softgoal filho é suficiente para satisfazer o pai.

* **MAKE (++)**: Contribuição fortemente positiva; se o filho for satisfeito, o pai também será.

* **BREAK (−−)**: Contribuição fortemente negativa; se o filho for satisfeito, o pai será negado.

* **HELP (+)**: Contribuição parcialmente positiva; satisfação parcial do filho implica em satisfação parcial do pai.

* **HURT (−)**: Contribuição parcialmente negativa; satisfação do filho implica em negação parcial do pai.

* **UNKNOWN (?)**: Contribuição incerta; não se sabe se é positiva ou negativa.

* **EQUALS**: O filho reflete exatamente o estado do pai (satisfeito ou negado).

* **SOME**: A direção da contribuição (positiva ou negativa) é conhecida, mas não sua intensidade (parcial ou total).

### Avaliação dos Softgoals

O processo de avaliação dos softgoals envolve determinar se eles foram atendidos, parcialmente atendidos ou não atendidos. A seguir estão os tipos de avaliação e suas descrições:

* Satisfeito(✓): O Softgoal totalmente atendido, com todos os critérios de aceitação cumpridos.
* Fracamente satisfeito (𝒲+): Satisfação parcial; O softgoal foi atendido de forma limitada, sem atingir sua totalidade.
* Negado (X): O requisito O softgoal foi claramente não atendidoe pode até contradizer os objetivos do sistema.
* Fracamente negado(𝒲-): O softgoal sofreu impacto negativo parcial, mas não foi totalmente negado.
* Conflitante (🗲): O softgoal recebeu contribuições contraditórias (ex.: uma solução ajuda e outra prejudica), impedindo uma avaliação conclusiva.
* Indeterminado(u): Não é possível determinar com clareza se o softgoal foi atendido ou não.
  O processo de avaliação é crucial para entender o estado atual dos softgoals e identificar áreas que precisam de atenção ou ajustes.
  Para isso, a avaliação inicia-se a partir dos softgoals mais específicos (filhos) e vai subindo na hierarquia até chegar aos softgoals mais amplos (pais). A avaliação é feita com base nas contribuições recebidas de cada softgoal filho, considerando a direção e intensidade dessas contribuições.

<p align="center">Figura 2 - Tipos de avaliação NFR Framework</p>

![SATISFACAO](https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Cinemark/main/docs/assets/modelagem/satisfacao_softgoal.png)

<p align="center"><em>Fonte: SILVA, 2019</em></p>

## Metodologia

A metodologia utilizada para a modelagem dos requisitos não funcionais foi baseada no NFR Framework, que é uma abordagem estruturada para identificar, categorizar e priorizar requisitos não funcionais. O processo envolveu as seguintes etapas:

### 1. **Identificação dos Softgoals**:

Os softgoals foram identificados com base nas necessidades e expectativas dos stakeholders, considerando aspectos como usabilidade, segurança e desempenho. Cada softgoal foi definido de forma clara e concisa, refletindo um objetivo de qualidade específico.

### 2. **Modelagem dos Softgoals**:

Cada softgoal foi modelado como um nó no Softgoal Interdependency Graph (SIG), representando suas relações de contribuição com outros softgoals utilizando a notação do NFR Framework evidenciada por Silva, 2019. A notação pode ser vista lida abaixo:

* **AND**

* **OR**

* **MAKE (++)**

* **BREAK (−−)**

* **HELP (+)**

* **HURT (−)**

* **EQUALS**

* **SOME**

* **UNKNOWN (?)**

#### Cartão de Especificação

O Cartão de Especificação é uma ferramenta utilizada para documentar requisitos não funcionais de forma estruturada. Ele contém informações essenciais sobre cada requisito, como classificação, descrição, justificativa, origem, critério de aceitação, dependências, prioridade, conflitos e histórico (SILVA,2019). A tabela abaixo apresenta um modelo de Cartão de Especificação que foi utilizado para documentar os requisitos não funcionais modelados no NFR.

Tabela 2 - Modelo de tabela de Cartão de Especificação

<font size="3"><p style="text-align: center">Tabela 1: Template de cartão de especificação </p></font>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNFXX</th></tr>
  <tr><td><strong>Classificação</strong></td><td>	Classificação do RNF conforme a hierarquia do catálogo.</td></tr>
  <tr><td><strong>Descrição</strong></td><td>Declaração única do significado do requisito.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Justificativa sobre a criação do requisito</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td>Origem do requisito (stakeholder, norma técnica e etc...)</td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>Métrica do requisito que possa ser testada e que deve ser satisfeita.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>Requisitos relacionados a este.</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>A prioridade foi definida pelo método MoSCoW sendo Must(Deve), Should(Deveria), Could(Poderia), Won't(Não fazer) </td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Requisitos conflitantes com este.</td></tr>
  <tr><td><strong>História</strong></td><td>Data de criação e de modificações.</td></tr>
</table>
</center>

<font size="2"><p style="text-align: center">Fonte: [Gabriel Castelo](https://github.com/GabrielCastelo-31) </p></font>

### 3. **Avaliação dos Softgoals**:

A avaliação dos softgoals foi realizada com base nas contribuições recebidas de cada softgoal filho, considerando a direção e intensidade dessas contribuições. A avaliação foi feita seguindo a hierarquia dos softgoals, começando pelos mais específicos e subindo até os mais amplos. Foi seguida a notação de avaliação do NFR Framework, que inclui os tipos de satisfação (satisfeito, fracamente satisfeito, negado, fracamente negado, conflitante e indeterminado):

* Satisfeito (✓): Softgoal totalmente atendido, com todos os critérios de aceitação cumpridos.
* Fracamente satisfeito (𝒲+): Parcialemente satisfeito
* Negado (X): Softgoal não atendido.
* Fracamente negado (𝒲-): Parcialmente não atendido.
* Conflitante (🗲): O softgoal recebeu contribuições contraditórias
* Indeterminado (u): Não é possível determinar com clareza se o softgoal foi atendido ou não.

## NFR 01 - Usabilidade

Este softgoal representa a facilidade de uso e a experiência do usuário com o sistema. A seguir estão os requisitos não-funcionais de usabilidade modelados com o NFR Framework:

### Tabela 3 - Requisitos Não-Funcionais de Usabilidade

| ID    | Descrição                                                                 | Tipo         |
|-------|---------------------------------------------------------------------------|--------------|
|[RQ44](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ44) | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão. | Usabilidade   |

## NFR 02 - Segurança

Este softgoal abrange a proteção de dados e a segurança do sistema. A seguir estão os requisitos não-funcionais de segurança modelados com o NFR Framework:

### Tabela 4 - Requisitos Não-Funcionais de Segurança

| ID    | Descrição                                                                 | Tipo         |
|-------|---------------------------------------------------------------------------|--------------|
| [RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ49) | Autenticação por biometria ou PIN para operações sensíveis. | Segurança     |
| [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ50) | Notificações push customizáveis pelo usuário. | Segurança     |
| [RQ53](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ53) | Manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra. | Segurança     |
| [RQ54](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ54) | Ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos). | Segurança     |

## NFR 03 - Desempenho

Este softgoal refere-se à eficiência e velocidade do sistema. A seguir estão os requisitos não-funcionais de desempenho modelados com o NFR Framework:

### Tabela 5 - Requisitos Não-Funcionais de Desempenho

| ID    | Descrição                                                                 | Tipo         |
|-------|---------------------------------------------------------------------------|--------------|
| [RQ40](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ40) | Tempo de resposta de até 3 segundos em telas críticas (seleção de assentos, pagamento). | Desempenho    |
| [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ47) | Atualizar automaticamente o valor total conforme seleção de ingressos e produtos. | Desempenho    |

***

**Tabela 2 - Cartão de Especificação 1**

| Campo                 | Descrição                                                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| **Requisito:** |  [RQ45](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ45)                                                                                                         |
| **Classificação:** | Acessibilidade / Usabilidade                                                                                                              |
| **Descrição:** | A interface do sistema deve atender aos critérios de contraste de cores definidos pelas Diretrizes de Acessibilidade para Conteúdo Web (WCAG) nos níveis A e AA. |
| **Justificativa:** | Garantir que o conteúdo textual e visual seja perceptível por usuários com baixa visão ou daltonismo, promovendo uma experiência inclusiva e em conformidade com padrões internacionais de acessibilidade. |
| **Origem do Requisito:** | [Análise de Interface](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/)                                                                           |
| **Critério de Aceitação:** | Todas as combinações de cores entre texto e plano de fundo, e entre componentes de interface significativos e seus planos de fundo, devem atingir uma taxa de contraste mínima de 4.5:1 para texto normal e 3:1 para texto grande (ou conforme especificado para componentes gráficos na WCAG 2.1 AA). A conformidade deve ser validada utilizando ferramentas de análise de contraste reconhecidas. |
| **Dependências:** | Definição da paleta de cores do sistema, Guia de estilo da interface.                                                                     |
| **Prioridade:** | Must                                                                                                                       |
| **Conflitos:** | Pode haver conflito com escolhas estéticas de design que não considerem os requisitos de contraste desde o início.                       |
| **História:** | 01/06/2025                                                                                                                              |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg).</p></font>

***

## Tabela X - Requisitos Não-Funcionais Não Implementados

| ID    | Descrição                                                                 | Tipo         |
|-------|---------------------------------------------------------------------------|--------------|
| [RQ54](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ54) | Ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos). | Segurança     |
| [RQ45](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ45) | Contraste de interface conforme WCAG A/AA. | Usabilidade    |
| [RQ44](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ44) | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão. | Usabilidade   |
| [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ47) | Atualizar automaticamente o valor total conforme seleção de ingressos e produtos. | Desempenho    |
| [RQ53](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ53) | Manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra. | Segurança     |
| [RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ49) | Autenticação por biometria ou PIN para operações sensíveis. | Segurança     |
| [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ50) | Notificações push customizáveis pelo usuário. | Segurança     |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg).</p></font>

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  22/05/2025 |  Criação do Documento | [Davi Camilo](https://github.com/Davicamilo23)  | [Euller Júlio da Silva](https://github.com/Potatoyz908) |
| `1.1`  | 26/05/2025 | Adição do modelo da tabela de participantes | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.2`  | 01/06/2025 | Adição do modelo da tabela de Cartão de Especificação e correção da imagem dos tipos de Softgoal | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.3`  | 01/06/2025 | Adição de introdução e Softgoal Interdependency Graph | [Gabriel Castelo](https://github.com/GabrielCastelo-31) e [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.4`  | 01/06/2025 | Adição da Tabela 2 | [Arthur Evangelista](https://github.com/arthurevg)| [Davi Camilo](https://github.com/Davicamilo23) |
| `1.5`  | 01/06/2025 | Adição de fundamentação teórica e alteração do modelo de tabela de Cartão de Especificação | [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Davi Camilo](https://github.com/Davicamilo23) |
