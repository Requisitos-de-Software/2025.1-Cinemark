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
						<td>Adição do Cartão de Especificação 2</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/arthurevg">Arthur Evangelista</a></td>
						<td>Adição do Cartão de Especificação 1</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/Davicamilo23">Davi Camilo</a></td>
						<td>Adição do Cartão de Especificação 3</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/Potatoyz908">Euller Júlio</a></td>
						<td>Adição do Cartão de Especificação 4 referente ao <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ49">RQ49</a></td>
					</tr>
					<tr>
						<td><a  href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a></td>
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

### Interdependências de Softgoals no NFR Framework

O NFR Framework utiliza um modelo de interdependência de softgoals para representar como diferentes objetivos de qualidade se relacionam entre si. Essas interdependências são fundamentais para entender como a satisfação de um softgoal pode impactar outros, ajudando a identificar conflitos e sinergias entre requisitos não funcionais.

O refinamento é uma interdependência top-down, na qual um softgoal pai gera um ou mais softgoals filhos relacionados a ele. Esse processo é essencial para tornar os objetivos mais claros e específicos. O refinamento pode ser realizado de várias maneiras, incluindo:

* **Decomposição de Softgoal NFR**: divide um softgoal genérico em outros mais especializados, facilitando o tratamento de problemas complexos e ambíguos.

* **Decomposição de Operacionalização**: refina um softgoal de operacionalização em subsoftgoals mais detalhados, ajudando a transformar uma solução geral em alternativas específicas.

* **Decomposição de Afirmação (Claim)**: subdivide softgoals de afirmação com o objetivo de reforçar ou questionar justificativas de projeto.

* **Priorização**: é uma forma especial de decomposição em que um softgoal é replicado com o mesmo conteúdo, mas com nível de prioridade atribuído.

Além disso, o framework prevê:

* **Operacionalizações**: são refinamentos que propõem técnicas de desenvolvimento para alcançar softgoals NFR, representando a transição de um objetivo para uma solução prática.

<p align="center">Figura 3 - Tipos de interdependências</p>

![REFINAMENTO](https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Cinemark/main/docs/assets/modelagem/refinamento.png)

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
|[RQ45](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ45) | Contraste de interface conforme WCAG A/AA. | Usabilidade    |
| [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ50) | Notificações push customizáveis pelo usuário. | Usabilidade     |
| [RQ53](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ53) | Manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra. | Usabilidade     |

## NFR 02 - Segurança

Este softgoal abrange a proteção de dados e a segurança do sistema. A seguir estão os requisitos não-funcionais de segurança modelados com o NFR Framework:

### Tabela 4 - Requisitos Não-Funcionais de Segurança

| ID    | Descrição                                                                 | Tipo         |
|-------|---------------------------------------------------------------------------|--------------|
| [RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ49) | Autenticação por biometria ou PIN para operações sensíveis. | Segurança     |
| [RQ54](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ54) | Ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos). | Segurança     |

A seguir estão os cartões de especificação para os requisitos não-funcionais de segurança:

<p style="text-align: center"><strong>Tabela 7: Cartão de Especificação 5</strong></p>

<center>
<table border="1" cellpadding="6" cellspacing="0">
  <tr><th colspan="2">Requisito Não Funcional – RNF54</th></tr>
  <tr><td><strong>Classificação</strong></td><td>Segurança</td></tr>
  <tr><td><strong>Descrição</strong></td><td>O sistema deve ocultar parcialmente o endereço de e-mail recuperado, substituindo parte dos caracteres por asteriscos (*), de forma a proteger dados sensíveis do usuário.</td></tr>
  <tr><td><strong>Justificativa</strong></td><td>Evitar a exposição completa do e-mail em tela pública ou compartilhada, reduzindo riscos de acesso indevido e aumentando a segurança da informação.</td></tr>
  <tr><td><strong>Origem do Requisito</strong></td><td>Stakeholder (equipe de segurança da informação)</td></tr>
  <tr><td><strong>Critério de Aceitação</strong></td><td>Ao exibir o e-mail recuperado, o sistema deve mascarar parte do nome de usuário (antes do @), mantendo os três primeiros e o domínio visível. Exemplo: **joh***@exemplo.com.</td></tr>
  <tr><td><strong>Dependências</strong></td><td>RQ12 – Recuperação de Conta<br>RQ51 – Política de privacidade de dados</td></tr>
  <tr><td><strong>Prioridade</strong></td><td>Must (Deve)</td></tr>
  <tr><td><strong>Conflitos</strong></td><td>Nenhum identificado</td></tr>
  <tr><td><strong>História</strong></td><td>Criado em 01/06/2025</td></tr>
</table>
</center>

<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a></p></font>

## NFR 03 - Desempenho

Este softgoal refere-se à eficiência e velocidade do sistema. A seguir estão os requisitos não-funcionais de desempenho modelados com o NFR Framework:

### Tabela 5 - Requisitos Não-Funcionais de Desempenho

| ID    | Descrição                                                                 | Tipo         |
|-------|---------------------------------------------------------------------------|--------------|
| [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ47) | Atualizar automaticamente o valor total conforme seleção de ingressos e produtos. | Desempenho    |

***

**Tabela 6 - Cartão de Especificação 1**

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

**Tabela 7 - Cartão de Especificação 2**

| Campo                 | Descrição                                                                                                                                 |
| :-------------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| **Requisito:**        | [RQ44](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ44)                                                                                |
| **Classificação:**    | Acessibilidade / Usabilidade                                                                                                              |
| **Descrição:**        | A interface deve ser compatível com leitores de tela (ex: NVDA, VoiceOver) e oferecer recursos adaptativos para usuários com baixa visão, como redimensionamento de texto e navegação por teclado.        |
| **Justificativa:**    | Garantir autonomia e usabilidade para pessoas com deficiência visual, assegurando conformidade com a Lei Brasileira de Inclusão (LBI) e diretrizes internacionais de acessibilidade digital (WCAG 2.1).   |
| **Origem do Requisito:** | [Introspecção](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS35)                                                                                         |
| **Critério de Aceitação:** | <ul><li>Todos os elementos interativos devem ser identificáveis por leitores de tela, com rótulos descritivos e estados claros (ex: foco/seleção)</li><li>Funcionalidades críticas devem ser operáveis via teclado (tabulação, atalhos)</li><li>Texto deve ser redimensionável até 200% sem perda de funcionalidade</li><li>Validação realizada por ferramentas automatizadas (ex: Axe, Lighthouse) e testes manuais com usuários reais</li></ul> |
| **Dependências:**     | Implementação de componentes semânticos (HTML5/ARIA), biblioteca de UI compatível com acessibilidade, Guia de estilo da interface.                                                                       |
| **Prioridade:**       | Must                                                                                                                                      |
| **Conflitos:**        | Restrições técnicas de frameworks não acessíveis ou componentes de terceiros que violam padrões WCAG.                                                                                                     |
| **História:**         | 01/06/2025                                                                                                                                |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos](https://github.com/ArturDCR).</p></font>

**Tabela 8 - Cartão de Especificação 3**

| Campo                     | Descrição                                                                                                                                                                                                                      |
| :------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Requisito:**            | [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ47)                                                                                                                                              |
| **Classificação:**        | Desempenho                                                                                                                                                                                                       |
| **Descrição:**            | O sistema deve recalcular e exibir automaticamente o valor total da compra sempre que o usuário adicionar, remover ou modificar a quantidade de ingressos e produtos selecionados.                                           |
| **Justificativa:**        | Garantir uma experiência de compra transparente e compreensível, permitindo que o usuário tenha controle imediato sobre os valores finais antes de concluir o pedido.                                                              |
| **Origem do Requisito:**  | [Análise de Interface](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/)              |
| **Critério de Aceitação:**| Ao adicionar ou remover ingressos e produtos, o valor total exibido na tela deve ser atualizado automaticamente, sem necessidade de recarregar a página ou confirmar manualmente.                                           |
| **Dependências:**         | Funcionalidade de seleção de ingressos e produtos implementada, integração com lógica de precificação.                                                                                                                       |
| **Prioridade:**           | Must                                                                                                                                                                                                                          |
| **Conflitos:**            | Pode exigir tratamento de erros em casos de valores inválidos ou sincronização inadequada entre diferentes componentes da interface.                                                                                          |
| **História:**             | 01/06/2025                                                                                                                                                                                                                     |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23).</p></font>

  

**Tabela 9 - Cartão de Especificação 4**

| Campo                 | Descrição                                                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| **Requisito:**        | [RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ49)                                                                                                         |
| **Classificação:**    | Segurança                                                                                                                              |
| **Descrição:**        | Autenticação por biometria ou PIN para operações sensíveis.                                                                            |
| **Justificativa:**    | Garantir maior segurança nas operações sensíveis, protegendo dados do usuário contra acessos não autorizados.                          |
| **Origem do Requisito:** | [Introspecção](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS35)                                                                                         |
| **Critério de Aceitação:** | <ul><li>O sistema deve permitir autenticação por biometria ou PIN em todas as operações sensíveis.</li><li>Validação realizada por testes de segurança e conformidade com padrões de autenticação.</li></ul> |
| **Dependências:**     | Implementação de mecanismos de autenticação biométrica e PIN, integração com dispositivos compatíveis.                                  |
| **Prioridade:**       | Must                                                                                                                                   |
| **Conflitos:**        | Possíveis incompatibilidades com dispositivos que não suportam biometria ou PIN.                                                       |
| **História:**         | 01/06/2025                                                                                                                             |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908).</p></font>

**Tabela 10 - Cartão de Especificação 5**  

| Campo                 | Descrição                                                                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| **Requisito:**        | [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ50)                                                                               |
| **Classificação:**    | Usabilidade / Personalização                                                                                                            |
| **Descrição:**        | O sistema deve permitir que usuários personalizem suas preferências para recebimento de notificações push, incluindo tipos de alertas e frequência. |
| **Justificativa:**    | Garantir que os usuários recebam apenas notificações relevantes, melhorando a experiência e reduzindo perturbações, conforme boas práticas de UX e leis de proteção de dados (LGPD). |
| **Origem do Requisito:** | [Introspecção](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS35)                                                                         |
| **Critério de Aceitação:** | <ul><li>Opções de personalização devem incluir: promoções, alertas de sessão, novidades de cinema e atualizações de conta</li><li>Configurações devem ser salvas automaticamente no perfil do usuário</li><li>Estado "silenciar notificações" deve ser respeitado pelo sistema</li><li>Teste A/B deve mostrar redução de 40% em desativamentos de notificações</li></ul> |
| **Dependências:**     | Sistema de notificações push implementado, módulo de preferências do usuário.                                                            |
| **Prioridade:**       | Could                                                                                                                                  |
| **Conflitos:**        | Estratégias de marketing que dependem de notificações em massa podem ter alcance reduzido.                                              |
| **História:**         | 01/06/2025                                                                                                                              |

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>


***

## Tabela 12 - Requisitos Não-Funcionais Não Implementados

| ID    | Descrição                                                                 | Tipo         |
|-------|---------------------------------------------------------------------------|--------------|
| [RQ54](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ54) | Ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos). | Segurança     |
| [RQ45](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ45) | Contraste de interface conforme WCAG A/AA. | Usabilidade    |
| [RQ44](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ44) | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão. | Usabilidade   |
| [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ47) | Atualizar automaticamente o valor total conforme seleção de ingressos e produtos. | Desempenho    |
| [RQ53](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ53) | Manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra. | Usabilidade     |
| [RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ49) | Autenticação por biometria ou PIN para operações sensíveis. | Segurança     |
| [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ50) | Notificações push customizáveis pelo usuário. | Usabilidade     |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg).</p></font>

---

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  22/05/2025 |  Criação do Documento | [Davi Camilo](https://github.com/Davicamilo23)  | [Euller Júlio da Silva](https://github.com/Potatoyz908) |
| `1.1`  | 26/05/2025 | Adição do modelo da tabela de participantes | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.2`  | 01/06/2025 | Adição do modelo da tabela de Cartão de Especificação e correção da imagem dos tipos de Softgoal | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.3`  | 01/06/2025 | Adição de introdução e Softgoal Interdependency Graph | [Gabriel Castelo](https://github.com/GabrielCastelo-31) e [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.4`  | 01/06/2025 | Adição da Tabela 2 | [Arthur Evangelista](https://github.com/arthurevg)| [Davi Camilo](https://github.com/Davicamilo23) |
| `1.5`  | 01/06/2025 | Adição de fundamentação teórica e alteração do modelo de tabela de Cartão de Especificação | [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.6`  | 01/06/2025 | Adição de metodologia | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |[Tiago Antunes Balieiro](https://github.com/tiagobalieiro) |
| `1.7`  | 01/06/2025 | Adição da tabela 3 referente ao requisisto 44 | [Artur de Camargos](https://github.com/ArturDCR) |[Tiago Antunes Balieiro](https://github.com/tiagobalieiro) |
| `1.8`  | 01/06/2025 | Adição do cartão 3 | [Davi Camilo](https://github.com/Davicamilo23) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.9`  | 01/06/2025 | Adição do cartão 4 | [Euller Júlio](https://github.com/Potatoyz908) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.10`  | 01/06/2025 | Adição do cartão 5 | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos](https://github.com/ArturDCR) |


