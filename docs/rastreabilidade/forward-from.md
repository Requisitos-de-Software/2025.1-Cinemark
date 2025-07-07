# Forward-From

## Introdução

A rastreabilidade do tipo **Forward-From** tem como objetivo documentar e evidenciar as conexões que partem dos requisitos identificados rumo aos artefatos gerados nas etapas posteriores do desenvolvimento de software, como casos de uso, cenários e léxicos. Segundo Sayão e Leite (2005, p. 8), “...rastreabilidade *forward-from*, que liga requisitos a artefatos de desenho e implementação...”.
Essa rastreabilidade para frente (forward) garante que todos os requisitos estejam sendo devidamente considerados nas fases seguintes, contribuindo para a verificação da cobertura dos requisitos, a manutenção da consistência do projeto e a facilidade de gerenciamento de mudanças. A seguir, são apresentados os vínculos estabelecidos entre os requisitos elicitados e os artefatos desenvolvidos, demonstrando a aplicação prática desse tipo de rastreabilidade no contexto do projeto.

---

## Metodologia

Para a construção do artefato de **rastreabilidade Forward-From**, foram seguidos os seguintes passos: primeiramente, os requisitos previamente elicitados e aprovados foram analisados individualmente. Em seguida, cada requisito foi mapeado aos artefatos gerados nas fases subsequentes do desenvolvimento, como cenários, casos de uso e entradas do léxico. Esse mapeamento foi realizado com base na análise do conteúdo semântico de cada artefato, buscando identificar quais elementos do sistema foram diretamente influenciados ou derivados de cada requisito. Além disso, utilizamos como apoio os registros de reuniões, documentos de especificação e diagramas do projeto, a fim de garantir uma rastreabilidade coerente e completa. O resultado foi organizado em uma tabela, permitindo uma visualização clara dos vínculos estabelecidos entre os requisitos e os artefatos produzidos.

---

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
						<td><a  href="https://github.com/arthuevg">Arthur Evangelista</a></td>
						<td>Elaborou a rastreablidade Forward-From dos requisitos <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq10" target="_blank">RQ10</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq11" target="_blank">RQ11</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq12A" target="_blank">RQ12A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq12B" target="_blank">RQ12B</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq13" target="_blank">RQ13</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq14" target="_blank">RQ14</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq15" target="_blank">RQ15</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq16A" target="_blank">RQ16A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq16B" target="_blank">RQ16B</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq17" target="_blank">RQ17</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq18" target="_blank">RQ18</a>. </td>
					</tr>
					<tr>
						<td><a  href="https://github.com/Davicamilo23">Davi Camilo</a></td>
						<td>Elaborou a rastreablidade Forward-From dos requisitos <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq37" target="_blank">RQ37</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq38A" target="_blank">RQ38A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq38B" target="_blank">RQ38B</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq39" target="_blank">RQ39</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq40" target="_blank">RQ40</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq41" target="_blank">RQ41</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq42" target="_blank">RQ42</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq43" target="_blank">RQ43</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq44" target="_blank">RQ44</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq45" target="_blank">RQ45</a>. </td>
					</tr>
					<tr>
						<td><a  href="https://github.com/Potatoyz908">Euller Júlio</a></td>
						<td>Elaborou a rastreablidade Forward-From dos requisitos <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq28" target="_blank">RQ28</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq29A" target="_blank">RQ29A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq29B" target="_blank">RQ29B</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq30" target="_blank">RQ30</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq31" target="_blank">RQ31</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq32A" target="_blank">RQ32A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq32B" target="_blank">RQ32B</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq33" target="_blank">RQ33</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq34" target="_blank">RQ34</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq35" target="_blank">RQ35</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq36" target="_blank">RQ36</a>. </td>
					</tr>
					<tr>
						<td><a  href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a></td>
						<td>Elaborou a rastreabilidade Forward-From dos requisitos <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq19" target="_blank">RQ19</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq20A" target="_blank">RQ20A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq20B" target="_blank">RQ20B</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq21A" target="_blank">RQ21A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq21N" target="_blank">RQ21N</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq21C" target="_blank">RQ21C</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq22A" target="_blank">RQ22A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq22B" target="_blank">RQ22B</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq23A" target="_blank">RQ23A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq23B" target="_blank">RQ23B</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq24" target="_blank">RQ24</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq25" target="_blank">RQ25</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq26" target="_blank">RQ26</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq27" target="_blank">RQ27</a>. </td>
					</tr>
					<tr>
						<td><a  href="https://github.com/tiagobalieiro">Tiago Antunes Balieiro</a></td>
						<td>Elaborou a Introdução, Metodologia, Tabela Modelo para rastreabilidade e a rastreablidade Forward-From dos requisitos <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq01" target="_blank">RQ01</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq02A" target="_blank">RQ02A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq02B" target="_blank">RQ02B</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq03" target="_blank">RQ03</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq04" target="_blank">RQ04</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq05" target="_blank">RQ05</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq06" target="_blank">RQ06</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq07" target="_blank">RQ07</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq08" target="_blank">RQ08</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq09" target="_blank">RQ09</a>. </td>
					</tr>
					<tr>
						<td><a  href="https://github.com/ArturDCR">Artur de Camargos Rodrigues</a></td>
						<td>Elaborou a Introdução, Metodologia, Tabela Modelo para rastreabilidade e a rastreablidade Forward-From dos requisitos <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq46" target="_blank">RQ46</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq47" target="_blank">RQ47</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq48" target="_blank">RQ48A</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq48A" target="_blank">RQ48B</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq48B" target="_blank">RQ49</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq49" target="_blank">RQ50</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq50" target="_blank">RQ51</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq51" target="_blank">RQ52</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq52" target="_blank">RQ53</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq53" target="_blank">RQ54</a>, <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq54" target="_blank">RQ09</a>. </td>
					</tr>
			</tbody>
		</table>
	</div>
</div>

<font size="3"><p style="text-align: center">Autores: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) e [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

---

## Matriz de Rastreabilidade

### Legenda

A Tabela 2 apresenta a legenda com o significado de cada sigla utilizada nas tabelas de rastreabilidade a seguir. Essas siglas representam os diferentes artefatos produzidos ao longo do processo de Engenharia de Requisitos.

**Tabela 2**

| Legenda | Artefato                  |
| ------- | ------------------------- |
| US      | História usuário          |
| ST      | Storytelling              |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| AI      | Análise de Interface de Usuário |
| INT     | Introspecção              |
| Q       | Questionário              |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

### Modelos

A tabela 3 apresenta o modelo a ser seguido para a rastreabilidade dos Requisitos Funcionais.

**Tabela 3**

|                 RFXX                 |                            Descrição                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [EXX](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        *Tema do Épico*                                                        |
|         História de Usuário          | [USXX](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) Eu, como XXX, desejo XXX para XXX |
|                Léxico                |                                               [LXX](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#lexicos-criados)                                                |
|             Casos de uso             |                                            [UCXX](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/casosDeUso/#especializacao-dos-casos-de-uso)                                            |
|               Cenários               |                                              [CXX](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#introducao)                                               |
| Artefatos (elicitação de requisitos) |                                            *Ex: [QXX](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/questionario/#Q01)*                                            |

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

A tabela 4 apresenta o modelo a ser seguido para a rastreabilidade dos Requisitos Não Funcionais.

**Tabela 4**

|                 RNFXX                 |                            Descrição                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      [NFR XXXXXXXXXXX](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/nfrFramework/#nfr-01-usabilidade)                      |
| Especificação Suplementar |                [ES XXXXXXXXXXX](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#4-funcionalidade)                 |
| Artefatos (elicitação de requisitos) |                                            *Ex: [QXX](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/questionario/#Q01)*                                            |

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) e [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

---

## Requisitos Funcionais

#### **RQ01**

|                 [RQ01](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq01)                 |                            Exibir na tela inicial filmes em cartaz, com pôsteres, novidades e promoções.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           Não se aplica                                             |
|                 Tema                 |                                                       Não se aplica                                                      |
|         História de Usuário          | Não se aplica |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                       |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |    [IS01](../elicitação/introspecção.md#IS01), [AI01](../elicitação/analiseUI.md#AI01)   |

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

#### **RQ02A**

|                 [RQ02A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq02A)                 |                            Detectar localização automaticamente.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E12](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Compra e Acompanhamento de Pedidos                                                        |
|         História de Usuário          | [US15](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) Eu, como usuário, desejo que o aplicativo detecte automaticamente minha localização e permita alterá-la manualmente para ver sessões e cinemas próximos à minha região. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [IS02](../elicitação/introspecção.md#IS02)

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

#### **RQ02B**

|                 [RQ02B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq02B)                 |                            Permitir alteração manual da localização.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E12](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Compra e Acompanhamento de Pedidos                                                        |
|         História de Usuário          | [US15](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) Eu, como usuário, desejo que o aplicativo detecte automaticamente minha localização e permita alterá-la manualmente para ver sessões e cinemas próximos à minha região. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [AI02](../elicitação/analiseUI.md#AI02)

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

#### **RQ03**

|                 [RQ03](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq03)                 |                            Navegar por abas: Home, Filmes, Cinemas, Snack Bar, Club e Mais.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            Não se aplica                                             |
|                 Tema                 |                                                        Não se aplica                                                        |
|         História de Usuário          | Não se aplica |
|                Léxico                |                                               Não se aplica                                            |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [AI03](../elicitação/analiseUI.md#AI03)

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

#### **RQ04**

|                 [RQ04](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq04)                 |                            Autenticar usuário por e-mail e senha.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Conta e Sessão do Usuário                                                        |
|         História de Usuário          | [US35](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) 	Eu, como usuário do aplicativo Cinemark, desejo autenticar-me com e-mail e senha, para acessar minha conta e benefícios pessoais. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                           Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                              |
| Artefatos (elicitação de requisitos) |                                            [AI04](../elicitação/analiseUI.md#AI04)

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

#### **RQ05**

|                 [RQ05](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq05)                 |                            Buscar filmes por nome.	                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E02](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Exploração e Descoberta de Filmes                                                        |
|         História de Usuário          | [US22](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) Eu, como usuário, desejo buscar filmes pelo nome para localizar rapidamente o conteúdo que desejo assistir. |
|                Léxico                |                                               Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [AI05](../elicitação/analiseUI.md#AI05)

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

#### **RQ06**

|                 [RQ06](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq06)                 |                            Listar filmes em cartaz, pré-venda e futuros lançamentos.	                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E02](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Exploração e Descoberta de Filmes                                                        |
|         História de Usuário          | [US23](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) Eu, como usuário, desejo visualizar listas de filmes em cartaz, em pré-venda e em breve lançamento para planejar melhor minhas idas ao cinema. |
|                Léxico                |                                               Não se aplica                                                |
|             Casos de uso             |                                           Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [AI06](../elicitação/analiseUI.md#AI06)

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

#### **RQ07**

|                 [RQ07](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq07)                 |                            Exibir informações do filme (título, sinopse, gênero, duração, direção, elenco, distribuidor, origem).	                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E04](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Apoio à Decisão e Conteúdo Cinematográfico                                                        |
|         História de Usuário          | [US24](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) Eu, como usuário, desejo acessar informações detalhadas sobre o filme, como título, sinopse, gênero, duração, direção, elenco, distribuidor e origem para decidir se quero assisti-lo. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [IS03](../elicitação/introspecção.md#IS03), [AI07](../elicitação/analiseUI.md#AI07)

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

#### **RQ08**

|                 [RQ08](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq08)                 |                            Exibir sessões com data, horário, idioma, formato e sala.	                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            Não se aplica                                             |
|                 Tema                 |                                                        Não se aplica                                                        |
|         História de Usuário          | Não se aplica |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                              |
| Artefatos (elicitação de requisitos) |                                            [IS04](../elicitação/introspecção.md#IS04), [ST01](../elicitação/storytelling.md#ST01), [AI08](../elicitação/analiseUI.md#AI08), [Q01](../elicitação/questionario.md#Q01)

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

#### **RQ09**

|                 [RQ09](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq09)                 |                            	Permitir compra de ingressos com cartão de crédito, débito ou Pix.	                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            Não se aplica                                             |
|                 Tema                 |                                                        Não se aplica                                                        |
|         História de Usuário          | Não se aplica |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                           Não se aplica                                            |
|               Cenários               |                                             Não se aplica                                              |
| Artefatos (elicitação de requisitos) |                                            [IS05](../elicitação/introspecção.md#IS05), [AI14](../elicitação/analiseUI.md#AI14), [Q02](../elicitação/questionario.md#Q02)

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

#### **RQ10**

|                 [RQ10](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq10)                |                            Armazenar cartões de pagamento cadastrados para uso em compras futuras.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Compra e Acompanhamento de Pedidos                                                     |
|         História de Usuário          | [US01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) - Eu, como usuário, desejo que o aplicativo armazene cartões de pagamento já cadastrados para uso em compras futuras. |
|                Léxico                | Não se aplica|
|             Casos de uso             | Não se aplica                                          |
|               Cenários               |                                             Não se aplica                                             |
| Artefatos (elicitação de requisitos) |                  [IS06](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS06)                        |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ11**

|                 [RQ11](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq11)                |                            Permitir compra de múltiplos ingressos em uma única transação.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                       Compra e Finalização                                                      |
|         História de Usuário          | [US02](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) - Eu, como usuário, desejo comprar múltiplos ingressos em uma única transação, informando a quantidade de ingressos desejada para simplificar o processo de compra e torná-lo mais eficaz.|
|                Léxico                |                                              Não se aplica                                               |
|             Casos de uso             |   Não se aplica                                         |
|               Cenários               |                                              Não se aplica|
| Artefatos (elicitação de requisitos) |  [IS07](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS07)                                          |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ12A**

|                 [RQ12A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq12A)                 |                            Exibir mapa da sala com indicação gráfica de assentos ocupados, livres e especiais.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Compra e finalização                                                       |
|         História de Usuário          | [US03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) - Eu, como usuário, desejo que o aplicativo exiba um mapa da sala com indicação de assentos ocupados, livres e especiais para que eu possa escolher entre os assentos disponíveis. |
|                Léxico                |                                               [L23](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#23-usuario)                                                |
|             Casos de uso             |                                            Não se aplica|
|               Cenários               |                                             Não se aplica|
| Artefatos (elicitação de requisitos) |   [IS08](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS08), [AI09](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI09)|

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ12B**

|                 [RQ12B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq12B)                 |                            Permitir seleção de assentos pelos usuários.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Compra e finalização                                                       |
|         História de Usuário          | [US03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) - Eu, como usuário, desejo que o aplicativo exiba um mapa da sala com indicação de assentos ocupados, livres e especiais para que eu possa escolher entre os assentos disponíveis. |
|                Léxico                |                                               [L23](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#23-usuario)                                                |
|             Casos de uso             |                                            Não se aplica|
|               Cenários               |                                             Não se aplica|
| Artefatos (elicitação de requisitos) |   [IS08](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS08)|

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ13**

|                 [RQ13](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq13)                 |                            Exigir seleção de ao menos um assento antes de prosseguir.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E12](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                       Localização e Assentos                                                       |
|         História de Usuário          | [US16](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) - Eu, como usuário, desejo ser obrigado a selecionar um assento antes de prosseguir com o pagamento para garantir que tenho lugar reservado na sala escolhida. |
|                Léxico                |                                              Não se aplica                                               |
|             Casos de uso             |   Não se aplica                                           |
|               Cenários               |                                             Não se aplica                                              |
| Artefatos (elicitação de requisitos) |          [AI10](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI10)                                          |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ14**

|                 [RQ14](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq14)                |                            Definir tipo de ingresso por assento (inteira, meia, convênio, voucher).                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Compra e finalização|
|         História de Usuário          | [US04](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) - Eu, como usuário, desejo definir o tipo de ingresso por assento para selecionar cada ingresso como inteira, meia ou convênio. |
|                Léxico                |                                              Não se aplica                                           |
|             Casos de uso             |         Não se aplica                                  |
|               Cenários               |                                             Não se aplica|
| Artefatos (elicitação de requisitos) |       [AI11](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI11)                                           |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ15**

|             [RQ15](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq15)                |                            Integrar bomboniere ao app para compra antecipada de itens.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            Não se aplica                                             |
|                 Tema                 |                                                        Não se aplica|
|         História de Usuário          | Não se aplica |
|                Léxico                |                                              Não se aplica                                              |
|             Casos de uso             |  Não se aplica                                            |
|               Cenários               |                                             Não se aplica|
| Artefatos (elicitação de requisitos) |    [IS11](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS11), [AI12](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI12)                                             |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ16A**

|             [RQ16A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq16A)                 |                            Exibir resumo da compra.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            Não se aplica                                             |
|                 Tema                 |                                                       Não se aplica                                                  |
|         História de Usuário          | Não se aplica |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) |    [AI13](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI13), [AI29](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI29)                                           |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ16B**

|             [RQ16B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq16B)                 |                            Permitir aplicação de cupom de desconto.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            Não se aplica                                             |
|                 Tema                 |                                                       Não se aplica                                                  |
|         História de Usuário          | Não se aplica |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) |    [AI13](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI13), [AI29](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI29)                                           |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ17**

|             [RQ17](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq17)                 |                            	Gerar QR Code e chave Pix para pagamentos via Pix.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            Não se aplica                                             |
|                 Tema                 |                                                       Não se aplica                                                  |
|         História de Usuário          | Não se aplica |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) |   [AI15](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/#AI15)                                          |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ18**

|             [RQ18](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq18)                 |                            Disponibilizar ingresso digital no app.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            Não se aplica                                             |
|                 Tema                 |                                                       Não se aplica                                                  |
|         História de Usuário          | Não se aplica |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) | [IS09](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS09), [ST03](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/storytelling/#ST03)|

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg), 2025.</p></font>

#### **RQ19**

|             [RQ19](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq19)                 | Salvar automaticamente ingressos na seção “Meus Ingressos” após confirmação de compra.                           |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E05](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-5-gerenciamento-de-ingressos)|
|                 Tema                 | Compra e Acompanhamento de Pedidos                                       |
|         História de Usuário          | [US26](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us26-salvamento-automatico-de-ingressos) Eu, como usuário do aplicativo Cinemark, desejo que meus ingressos sejam salvos automaticamente na seção “Meus Ingressos” após a confirmação da compra para acessá-los facilmente quando precisar apresentá-los no cinema.                                     |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |  Não se aplica  |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) | [AI16](../elicitação/analiseUI.md#AI16)|

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ20A**

|             [RQ20A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq20)                 |                            Permitir criação de conta (nome, e-mail, senha, CPF).                            |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 | Não se aplica                                            |
|                 Tema                 |                                                       Conta e Sessão do Usuário                                                 |
|         História de Usuário          | Não se aplica |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) | [AI17](../elicitação/analiseUI.md#AI17) |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ20B**

|             [RQ20B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq20)                 |                            Permitir login com Google/redes sociais.                            |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-1-autenticacao-e-gerenciamento-de-conta)                                            |
|                 Tema                 |                                                       Conta e Sessão do Usuário                                                 |
|         História de Usuário          | [US07](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us07-login-com-redes-sociais) Eu, como usuário, desejo fazer login via Google/redes sociais para acessar o aplicativo de forma segura e rápida. |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) | [IS26](../elicitação/introspecção.md#IS26) |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ21A**

|             [RQ21A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq21A)                 |                            Recuperar conta por envio de link de redefinição de senha por e-mail.                            |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-1-autenticacao-e-gerenciamento-de-conta)                                            |
|                 Tema                 |                                                       Conta e Sessão do Usuário                                                 |
|         História de Usuário          | [US08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us08-recuperacao-de-conta-via-e-mail) Eu, como usuário, desejo recuperar meu acesso ao aplicativo enviando um link de redefinição de senha por e-mail ou recuperando meu e-mail através do CPF para, então, redefinir minha senha com código para voltar a usar minha conta quando esquecer minhas credenciais. |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) | [AI18](../elicitação/analiseUI.md#AI18) |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ21B**

|             [RQ21B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq21B)                 |                            Recuperar e-mail via CPF.                            |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-1-autenticacao-e-gerenciamento-de-conta)                                            |
|                 Tema                 |                                                       Conta e Sessão do Usuário                                                 |
|         História de Usuário          | [US08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us08-recuperacao-de-conta-via-e-mail) Eu, como usuário, desejo recuperar meu acesso ao aplicativo enviando um link de redefinição de senha por e-mail ou recuperando meu e-mail através do CPF para, então, redefinir minha senha com código para voltar a usar minha conta quando esquecer minhas credenciais. |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) | [AI19](../elicitação/analiseUI.md#AI19) |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ21C**

|             [RQ21C](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq21C)                 |                            Redefinir e-mail com código de verificação.                            |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-1-autenticacao-e-gerenciamento-de-conta)                                            |
|                 Tema                 |                                                       Conta e Sessão do Usuário                                                 |
|         História de Usuário          | [US08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us08-recuperacao-de-conta-via-e-mail) Eu, como usuário, desejo recuperar meu acesso ao aplicativo enviando um link de redefinição de senha por e-mail ou recuperando meu e-mail através do CPF para, então, redefinir minha senha com código para voltar a usar minha conta quando esquecer minhas credenciais. |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) | [AI20](../elicitação/analiseUI.md#AI20) |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ22A**

|             [RQ22A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq22A)                 |                            Exibir histórico de filmes assistidos (data, horário, cinema).                      |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-1-autenticacao-e-gerenciamento-de-conta)                                            |
|                 Tema                 |                                                       Conta e Sessão do Usuário                                                 |
|         História de Usuário          | [US09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us09-exibir-historico-de-filmes-e-compras) Eu, como usuário autenticado, desejo visualizar meu histórico de filmes assistidos (com data, horário e cinema) e meu histórico de compras na bomboniere para acompanhar meus registros, visualizar minhas compras e avalar possíveis reembolsos. |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) | [IS13](../elicitação/introspecção.md#IS13) |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ22B**

|             [RQ22B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq22B)                 |                            Exibir histórico de compras na bomboniere.                      |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-1-autenticacao-e-gerenciamento-de-conta)                                            |
|                 Tema                 |                                                       Conta e Sessão do Usuário                                                 |
|         História de Usuário          | [US09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us09-exibir-historico-de-filmes-e-compras) Eu, como usuário autenticado, desejo visualizar meu histórico de filmes assistidos (com data, horário e cinema) e meu histórico de compras na bomboniere para acompanhar meus registros, visualizar minhas compras e avalar possíveis reembolsos. |
|                Léxico                |                                              Não se aplica                                             |
|             Casos de uso             |             Não se aplica                                         |
|               Cenários               |   Nâo se aplica                                            |
| Artefatos (elicitação de requisitos) | [IS14](../elicitação/introspecção.md#IS14)  |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ23A**

|             [RQ23A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq23A)                 |                            Filtrar filmes por categoria.                     |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E02](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-2-exploracao-de-filmes)                                            |
|                 Tema                 |                                                       Exploração e Descoberta de Filmes                                               |
|         História de Usuário          | [US10](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us10-filtrar-filmes-por-categoria) Eu, como usuário, desejo aplicar filtros por categoria de filme e visualizar avaliações de público e plataformas externas para encontrar rapidamente produções de meu interesse com base em reviews confiáveis. |
|                Léxico                | [L03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#3-filtrar-filmes)                                          |
|             Casos de uso             |             [UC01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#41-cenario-1-filtrar-filmes-por-categoria-e-exibir-avaliacoes)                                          |
|               Cenários               |            [C01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#cenario-1-filtrar-filmes-por-categoria-e-exibir-avaliacoes)                                   |
| Artefatos (elicitação de requisitos) | [IS15](../elicitação/introspecção.md#IS15)  |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ23B**

|             [RQ23B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq23B)                 |                            O sistema deve exibir avaliações de plataformas externas, como o IMDB e Rotten Tomatoes.                     |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E02](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-2-exploracao-de-filmes)                                            |
|                 Tema                 |                                                       Exploração e Descoberta de Filmes                                               |
|         História de Usuário          | [US10](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us10-filtrar-filmes-por-categoria) Eu, como usuário, desejo aplicar filtros por categoria de filme e visualizar avaliações de público e plataformas externas para encontrar rapidamente produções de meu interesse com base em reviews confiáveis. |
|                Léxico                | [L04](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#4-avaliacoes-de-filmes)                                          |
|             Casos de uso             |             Não se aplica                                          |
|               Cenários               |            [C01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#cenario-1-filtrar-filmes-por-categoria-e-exibir-avaliacoes)                                   |
| Artefatos (elicitação de requisitos) | [IS15](../elicitação/introspecção.md#IS15)  |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ24**

|             [RQ24](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq24)                 |                            Exibir trailers dentro do app.                     |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E02](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-2-exploracao-de-filmes)                                            |
|                 Tema                 |                                                       Exploração e Descoberta de Filmes                                               |
|         História de Usuário          | [US11](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us11-exibir-trailers-dentro-do-app) Eu, como usuário, desejo assistir trailers dos filmes diretamente no aplicativo para avaliar rapidamente se quero comprá-los antes de ir ao cinema. |
|                Léxico                | [L05](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#5-assistir-trailer), [L06](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#6-trailer)                                          |
|             Casos de uso             |             [UC04](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/casosDeUso/#tabela-4-exibir-trailers-dentro-do-app)                                        |
|               Cenários               |   [C02](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#cenario-2-exibir-trailers-dentro-do-app)                                              |
| Artefatos (elicitação de requisitos) | [IS16](../elicitação/introspecção.md#IS16)  |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ25**

|             [RQ25](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq25)                 |                            O fluxo de compra de ingresso do aplicativo deve possuir no máximo 5 etapas.                    |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-3-compra-e-finalizacao)                                            |
|                 Tema                 |                                                       Compra e Acompanhamento de Pedidos                                             |
|         História de Usuário          | [US12](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us12-fluxo-de-compra-simplificado) Eu, como usuário, desejo realizar a compra de ingressos e snacks em no máximo 5 etapas para tornar o processo mais rápido e conveniente, minimizando a taxa de desistência de compra. |
|                Léxico                | Não se aplica                                        |
|             Casos de uso             |             Não se aplica                                      |
|               Cenários               |   Não se aplica                                             |
| Artefatos (elicitação de requisitos) | [IS17](../elicitação/introspecção.md#IS17)  |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ26**

|             [RQ26](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq26)                 |                            Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc).                    |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E05](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-5-gerenciamento-de-ingressos)                                            |
|                 Tema                 |                                                       Compra e Acompanhamento de Pedidos                                             |
|         História de Usuário          | [US05](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us05-salvar-ingressos-na-carteira-digital-do-dispositivo) Eu, como usuário, desejo que o aplicativo permita que eu salve ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc)para uma maior integração e diversificando as opções para acessar o meu ingresso. |
|                Léxico                | [L21](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#21-salvar-ingresso-na-carteira-digital)                                      |
|             Casos de uso             |             [UC09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/casosDeUso/#tabela-9-permitir-salvar-ingressos-na-carteira-digital-do-dispositivo)                                      |
|               Cenários               |   [C11](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#cenario-11-permitir-salvar-ingressos-na-carteira-digital-do-dispositivo)                                            |
| Artefatos (elicitação de requisitos) | [IS18](../elicitação/introspecção.md#IS18)  |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ27**

|             [RQ27](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq27)                 |                            Permitir uso de pontos acumulados para desconto em ingressos e produtos.                    |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                           [E08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-8-sistema-de-fidelidade-e-beneficios-cinemark-club)                                            |
|                 Tema                 |                                                       Personalização da Experiência Cinemark                                              |
|         História de Usuário          | [US25](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us25-utilizacao-de-pontos-para-desconto) Eu, como usuário do programa de fidelidade da Cinemark, desejo utilizar meus pontos acumulados para obter desconto em ingressos e produtos. |
|                Léxico                | Não se aplica                                    |
|             Casos de uso             |             Não se aplica                                      |
|               Cenários               |   Não se aplica                                            |
| Artefatos (elicitação de requisitos) | [IS19](../elicitação/introspecção.md#IS19) e [Q03](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/questionario/#Q03)  |

<font size="3"><p style="text-align: center">Autor: [Gabriel Castelo](https://github.com/GabrielCastelo-31), 2025.</p></font>

#### **RQ28**

|                 [RQ28](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq28)                 |                            Alertar usuário sobre pontos suficientes para ingresso grátis 3 dias antes da expiração.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-8-sistema-de-fidelidade-e-beneficios-cinemark-club)                                             |
|                 Tema                 |                                                        Personalização da Experiência Cinemark                                                        |
|         História de Usuário          | [US27](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us27-alerta-sobre-pontos-acumulados) Eu, como usuário do aplicativo Cinemark, desejo receber alertas quando a quantidade de pontos permitir resgate de ingresso grátis e antes da expiração dos pontos para não perder a oportunidade de usá-los a tempo. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [IS20](../elicitação/introspecção.md#IS20) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ29A**

|                 [RQ29A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq29A)                 |                            Sugerir cinemas com base no histórico de visitas.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-9-experiencia-personalizada-com-cinemas)                                             |
|                 Tema                 |                                                        Personalização da Experiência Cinemark                                                        |
|         História de Usuário          | [US30](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us30-sugestao-de-cinemas-personalizada) Eu, como usuário do aplicativo Cinemark, desejo receber sugestões de cinemas baseadas na minha localização e histórico de visitas para encontrar mais facilmente unidades relevantes para mim. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                             [C09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#tabela-9-cenario-de-sugerir-cinemas-personalizados)                                              |
| Artefatos (elicitação de requisitos) |                                            [IS21](../elicitação/introspecção.md#IS21) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ29B**

|                 [RQ29B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq29B)                 |                            Sugerir cinemas com base na localização atual.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-9-experiencia-personalizada-com-cinemas)                                             |
|                 Tema                 |                                                        Personalização da Experiência Cinemark                                                        |
|         História de Usuário          | [US30](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us30-sugestao-de-cinemas-personalizada) Eu, como usuário do aplicativo Cinemark, desejo receber sugestões de cinemas baseadas na minha localização e histórico de visitas para encontrar mais facilmente unidades relevantes para mim. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                             [C09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#tabela-9-cenario-de-sugerir-cinemas-personalizados)                                              |
| Artefatos (elicitação de requisitos) |                                            [IS21](../elicitação/introspecção.md#IS21) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ30**

|                 [RQ30](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq30)                 |                            Permitir que o usuário salve cinemas como favoritos.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-9-experiencia-personalizada-com-cinemas)                                             |
|                 Tema                 |                                                        Personalização da Experiência Cinemark                                                        |
|         História de Usuário          | [US28](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us28-favoritar-cinemas) Eu, como usuário do aplicativo Cinemark, desejo salvar cinemas como favoritos para acessar rapidamente minhas unidades preferidas ao procurar sessões ou realizar compras. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              [C10](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#tabela-10-cenario-de-permitir-salvar-cinemas-favoritos)                                               |
| Artefatos (elicitação de requisitos) |                                            [IS22](../elicitação/introspecção.md#IS22) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ31**

|                 [RQ31](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq31)                 |                            Permitir notificações personalizadas (ex.: “avise-me quando o filme X entrar em cartaz”).                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-9-experiencia-personalizada-com-cinemas)                                             |
|                 Tema                 |                                                        Personalização da Experiência Cinemark                                                        |
|         História de Usuário          | [US21](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us21-permitir-notificacoes-personalizadas) Eu, como usuário, desejo configurar notificações personalizadas como "avise-me quando o filme X entrar em cartaz" para não perder lançamentos que são de meu interesse. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [IS23](../elicitação/introspecção.md#IS23) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ32A**

|                 [RQ32A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq32A)                 |                            Exibir recomendações de filmes baseadas em histórico.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-9-experiencia-personalizada-com-cinemas)                                             |
|                 Tema                 |                                                        Personalização da Experiência Cinemark                                                        |
|         História de Usuário          | [US19](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us19-exibir-recomendacoes-de-filmes-baseadas-em-historico-e-preferencias) Eu, como usuário, desejo visualizar recomendações personalizadas de filmes com base no meu histórico de navegação e preferências para descobrir novos títulos que são de interesse. |
|                Léxico                |                                              [L07](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#7-exibir-recomendacoes-de-filmes) [L08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#8-recomendacoes-de-filmes)                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              [C05](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#45-cenario-5-exibir-recomendacoes-de-filmes-baseadas-em-historico-e-preferencias)                                               |
| Artefatos (elicitação de requisitos) |                                            [IS24](../elicitação/introspecção.md#IS24) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ32B**

|                 [RQ32B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq32B)                 |                            Exibir recomendações de filmes baseadas em preferências.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-9-experiencia-personalizada-com-cinemas)                                             |
|                 Tema                 |                                                        Personalização da Experiência Cinemark                                                        |
|         História de Usuário          | [US19](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us19-exibir-recomendacoes-de-filmes-baseadas-em-historico-e-preferencias) Eu, como usuário, desejo visualizar recomendações personalizadas de filmes com base no meu histórico de navegação e preferências para descobrir novos títulos que são de interesse. |
|                Léxico                |                                              [L07](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#7-exibir-recomendacoes-de-filmes) [L08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#8-recomendacoes-de-filmes)                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              [C05](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#45-cenario-5-exibir-recomendacoes-de-filmes-baseadas-em-historico-e-preferencias)                                               |
| Artefatos (elicitação de requisitos) |                                            [IS24](../elicitação/introspecção.md#IS24) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ33**

|                 [RQ33](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq33)                 |                            Permitir alteração de preferências de idioma.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E11](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#épico-11--configurações-de-idioma)                                             |
|                 Tema                 |                                                        Configurações de Idioma                                                        |
|         História de Usuário          | [US14](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us14-alterar-preferências-de-idioma) Eu, como usuário, desejo alterar as preferências de idioma do aplicativo para acessar o conteúdo em meu idioma de preferência. |
|                Léxico                |                                              [L2](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#2-preferência-de-idioma)                                                |
|             Casos de uso             |                                            [UC06](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/casosDeUso/#tabela-8-alterar-preferências-de-idioma)                                            |
|               Cenários               |                                              [C4](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#44-cenário-4-alterar-preferências-de-idioma)                                               |
| Artefatos (elicitação de requisitos) |                                            [IS25](../elicitação/introspecção.md#IS25) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ34**

|                 [RQ34](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq34)                 |                            Disponibilizar área dedicada ao Cinemark Club, contendo ingressos, pontos acumulados e validade.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#épico-8-sistema-de-fidelidade-e-benefícios-cinemark-club)                                             |
|                 Tema                 |                                                        Sistema de Fidelidade e Benefícios (Cinemark Club)                                                        |
|         História de Usuário          | [US29](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us29-área-dedicada-ao-cinemark-club) Eu, como usuário, desejo ter acesso a uma área dedicada ao Cinemark Club para visualizar meus ingressos, pontos acumulados e validade dos benefícios. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [IS12](../elicitação/introspecção.md#IS12) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ35**

|                 [RQ35](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq35)                 |                            Exibir notificações de promoções com título, descrição e validade.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-9-experiencia-personalizada-com-cinemas)                                             |
|                 Tema                 |                                                        Personalização da Experiência Cinemark                                                        |
|         História de Usuário          | [US35](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us35-autenticacao-por-e-mail-e-senha) Eu, como usuário do aplicativo Cinemark, desejo visualizar notificações e promoções com informações completas (título, descrição e validade) para poder aproveitar as ofertas disponíveis antes que expirem. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [AI32](../elicitação/analiseUI.md#AI32) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ36**

|                 [RQ36](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq36)                 |                            Impedir avanço para pagamento com carrinho vazio.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#features)                                             |
|                 Tema                 |                                                        Compra e Acompanhamento de Pedidos                                                        |
|         História de Usuário          | [US38](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us36-mensagens-de-erro-e-confirmacao) Eu, como usuário do aplicativo Cinemark, desejo ser impedido de avançar para a tela de pagamento quando meu carrinho estiver vazio para evitar confusão durante o processo de compra. |
|                Léxico                |                                              Não se aplica                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [AI30](../elicitação/analiseUI.md#AI30) |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

#### **RQ37**

|                 [RQ37](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq37)                 |                            O sistema deve permitir que o usuário edite o perfil de usuário, gerenciando dados pessoais e métodos de pagamento.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-1-autenticacao-e-gerenciamento-de-conta)                                             |
|                 Tema                 |                                                        	Gerenciamento de Perfil e Dados do Usuário                                                        |
|         História de Usuário          | [US07](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us07-login-com-redes-sociais) Eu, como usuário, desejo acessar e editar meu perfil, incluindo dados pessoais e métodos de pagamento, para manter minhas informações atualizadas e facilitar compras futuras no aplicativo. |
|                Léxico                |                                              [L23](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#23-usuario)                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [AI31](../elicitação/analiseUI.md#AI31) |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

#### **RQ38B**

|                 [RQ38B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq38B)                 |                            	O sistema deve exibir mensagens de confirmação para ações bem-sucedidas realizadas pelo usuário.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E07](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-7–feedback-do-sistema)                                             |
|                 Tema                 |                                                        Mensagens de Feedback e Confirmações Visuais                                                        |
|         História de Usuário          | [US36](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us36-mensagens-de-erro-e-confirmacao) Eu, como usuário, desejo receber mensagens de erro compreensíveis e confirmações visuais sempre que realizar uma ação, para entender claramente o que aconteceu e como proceder dentro do aplicativo. |
|                Léxico                |                                              [L23](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#23-usuario)                                                |
|             Casos de uso             |                                            Não se aplica                                            |
|               Cenários               |                                              Não se aplica                                               |
| Artefatos (elicitação de requisitos) |                                            [ST05](../elicitação/storytelling.md#ST05), [IS37](../elicitação/introspecção.md#IS37) |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

#### **RQ39**

|                 [RQ39](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq39)                 |                            	O aplicativo deve exibir avaliações dos filmes feitas por usuários.                             |
| :----------------------------------: | :------------------------------------------------------------------------------------------------------------------------: |
|                Épico                 |                                            [E04](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/#epico-4-hub-de-conteudo-cinematografico)                                             |
|                 Tema                 |                                                        	Avaliação de Filmes pelos Usuários                                                        |
|         História de Usuário          | [US06](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#us06-exibir-e-permitir-avaliacoes) Eu, como usuário, desejo visualizar avaliações de outros usuários e registrar minha própria nota para os filmes em uma escala de 1 a 5 estrelas, para compartilhar minha opinião e usar o feedback da comunidade ao escolher um filme. |
|                Léxico                |                                              [L4](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#4-avaliacoes-de-filmes) [L22](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#22-avaliar-filmes) [L23](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/#23-usuario)                                                |
|             Casos de uso             |                                            [UC08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/casosDeUso/#tabela-10-permitir-que-usuarios-avaliem-filmes-com-escala-de-1-a-5-estrelas)                                            |
|               Cenários               |                                              [C12](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/#412-cenario-12-exibir-avaliacoes-e-permitir-que-usuarios-avaliem-filmes-com-escala-de-1-a-5-estrelas)                                               |
| Artefatos (elicitação de requisitos) |                                            [IS15](../elicitação/introspecção.md#IS15) |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

---

### Requisitos Não Funcionais

#### **RQ38A**
|                 [RQ38A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq38A)                 |                            O sistema deve exibir mensagens de erro descritivas.                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      Não se aplica                      |
| Especificação Suplementar |                Não se aplica                 |
| Artefatos (elicitação de requisitos) |                                            [ST05](../elicitação/storytelling.md#ST05), [IS37](../elicitação/introspecção.md#IS37) |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

#### **RQ40**

|                 [RQ40](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq40)                 |                            Tempo de resposta de até 3 segundos em telas críticas (seleção de assentos, pagamento).                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      Não se aplica                      |
| Especificação Suplementar |                [Tabela 2](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#7-desempenho)                 |
| Artefatos (elicitação de requisitos) |                                            [IS29](../elicitação/introspecção.md#IS29), [Q09](../elicitação/questionario.md#Q09), [Q12](../elicitação/questionario.md#Q12) |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

#### **RQ41**

|                 [RQ41](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq41)                 |                            Garantir uptime de 99,5% para funções críticas como seleção de ingressos, assentos, pagamento.                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      Não se aplica                      |
| Especificação Suplementar |                [Tabela 3](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#6-confiabilidade)                 |
| Artefatos (elicitação de requisitos) |                                            [AI28](../elicitação/analiseUI.md#AI28) |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

#### **RQ42**

|                 [RQ42](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq42)                 |                            Sistema responsivo e adaptável a diferentes tamanhos de tela (smartphone e tablet).                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      Não se aplica                      |
| Especificação Suplementar |                [Tabela 4](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#5-usabilidade)                 |
| Artefatos (elicitação de requisitos) |                                            [AI24](../elicitação/analiseUI.md#AI24) |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

#### **RQ43**

|                 [RQ43](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq43)                 |                            O aplicativo deve permitir que o usuário realize todo o fluxo de seleção de assentos e compra de ingresso com, em média, 4 interações diretas com o sistema.                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      Não se aplica                      |
| Especificação Suplementar |                [Tabela 17](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#5-usabilidade)                 |
| Artefatos (elicitação de requisitos) |                                            [IS28](../elicitação/introspecção.md#IS28) |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

#### **RQ44**

|                 [RQ44](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq44)                 |                            Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão.                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      [Cartão de Especificação 2](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/nfrFramework/#nfr-01-usabilidade)                      |
| Especificação Suplementar |                [Tabela 14](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#5-usabilidade)                 |
| Artefatos (elicitação de requisitos) |                                            [IS35](../elicitação/introspecção.md#IS35), [IS36](../elicitação/introspecção.md#IS36), [AI25](../elicitação/analiseUI.md#AI25), [ST05](../elicitação/storytelling.md#ST05) |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

#### **RQ45**

|                 [RQ45](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq45)                 |                            As cores da interface do aplicativo devem possuir nível de contraste conforme a WCAG A/AA.                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      [Cartão de Especificação 1](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/nfrFramework/#nfr-01-usabilidade)                      |
| Especificação Suplementar |                [Tabela 8](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#5-usabilidade)                 |
| Artefatos (elicitação de requisitos) |                                            [AI25](../elicitação/analiseUI.md#AI25) |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

#### **RQ46**

|                 [RQ46](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq46)                 |                            Garantir legenda clara para cores e ícones no mapa de assentos                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                                       Não se aplica                                       |
| Especificação Suplementar |                [Tabela 5](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#tabela-5-detalhamento-do-rq46)                |
| Artefatos (elicitação de requisitos) |                                            [AI22](../elicitação/analiseUI.md#AI22) |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos Rodrigues](https://github.com/ArturDCR), 2025.</p></font>

#### **RQ47**

|                 [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq47)                 |                            Atualizar automaticamente o valor total conforme seleção de ingressos e produtos                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      [Requisitos Não-Funcionais de Desempenho](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/nfrFramework/#nfr-03-desempenho)                      |
| Especificação Suplementar |                [Tabela 6](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#tabela-6-detalhamento-do-rq47)                 |
| Artefatos (elicitação de requisitos) |                                            [AI23](../elicitação/analiseUI.md#AI23) |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos Rodrigues](https://github.com/ArturDCR), 2025.</p></font>

#### **RQ48A**

|                 [RQ48A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq48A)                 |                            Proteger dados de pagamento e histórico do usuário com criptografia                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                                       Não se aplica                                       |
| Especificação Suplementar |                [Tabela 7](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#tabela-7-detalhamento-do-rq48)                 |
| Artefatos (elicitação de requisitos) |                                            [IS32](../elicitação/introspecção.md#IS32), [Q10](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/questionario) |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos Rodrigues](https://github.com/ArturDCR), 2025.</p></font>

#### **RQ48B**

|                 [RQ48B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq48B)                 |                            Proteger histórico do usuário.                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                                       Não se aplica                                       |
| Especificação Suplementar |                [Tabela 7](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#tabela-7-detalhamento-do-rq48)                 |
| Artefatos (elicitação de requisitos) |                                            [IS32](../elicitação/introspecção.md#IS32), [Q10](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/questionario) |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos Rodrigues](https://github.com/ArturDCR), 2025.</p></font>

#### **RQ49**

|                 [RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq49)                 |                            Autenticação por biometria ou PIN para operações sensíveis                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      [Requisitos Não-Funcionais de Segurança](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/nfrFramework/#nfr-02-seguran%C3%A7a)                      |
| Especificação Suplementar |                [Tabela 9](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#tabela-9-detalhamento-do-rq49)                 |
| Artefatos (elicitação de requisitos) |                                            [IS33](../elicitação/introspecção.md#IS33) |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos Rodrigues](https://github.com/ArturDCR), 2025.</p></font>

#### **RQ50**

|                 [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq50)                 |                            Notificações push customizáveis pelo usuário                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      [Requisitos Não-Funcionais de Usabilidade](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/nfrFramework/#nfr-01-usabilidade)                      |
| Especificação Suplementar |                [Tabela 11](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#tabela-11-detalhamento-do-rq50)                 |
| Artefatos (elicitação de requisitos) |                                            [IS50](../elicitação/introspecção.md#IS50) |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos Rodrigues](https://github.com/ArturDCR), 2025.</p></font>

#### **RQ51**

|                 [RQ51](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq51)                 |                            Exibir mapa de assentos com indicação gráfica clara                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                                       Não se aplica                                       |
| Especificação Suplementar |                [Tabela 12](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#tabela-12-detalhamento-do-rq51)                 |
| Artefatos (elicitação de requisitos) |                                            [IS31](../elicitação/introspecção.md#IS31) |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos Rodrigues](https://github.com/ArturDCR), 2025.</p></font>

#### **RQ52**

|                 [RQ52](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq52)                 |                            Limitar quantidade máxima de 20 unidades por item no Snack Bar                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      	Não se aplica                      |
| Especificação Suplementar |                [Tabela 13](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#tabela-13-detalhamento-do-rq52)                 |
| Artefatos (elicitação de requisitos) |                                            [AI26](../elicitação/analiseUI.md#AI26) |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos Rodrigues](https://github.com/ArturDCR), 2025.</p></font>

#### **RQ53**

|                 [RQ53](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq53)                  |                            Manter informações da sessão visíveis durante a compra                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      [Requisitos Não-Funcionais de Usabilidade](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/nfrFramework/#nfr-01-usabilidade)                      |
| Especificação Suplementar |                [Tabela 15](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#tabela-15-detalhamento-do-rq53)                 |
| Artefatos (elicitação de requisitos) |                                            [AI27](../elicitação/analiseUI.md#AI27) |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos Rodrigues](https://github.com/ArturDCR), 2025.</p></font>

#### **RQ54**

|                 [RQ54](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq54)                 |                            Ocultar parcialmente o e-mail recuperado para segurança                             |
| :-----------------------: | :----------------------------------------------------------------------------------------: |
|            NFR            |                      [Requisitos Não-Funcionais de Segurança](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/nfrFramework/#nfr-02-seguran%C3%A7a)                      |
| Especificação Suplementar |                [Tabela 18](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especificaçãoSuplementar/#tabela-18-detalhamento-do-rq54)                 |
| Artefatos (elicitação de requisitos) |                                            [AI33](../elicitação/analiseUI.md#AI33) |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos Rodrigues](https://github.com/ArturDCR), 2025.</p></font>

---

## Referências Bibliográficas

> **SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado.** Rastreabilidade de requisitos. Rio de Janeiro: Departamento de Informática, Pontifícia Universidade Católica do Rio de Janeiro, 2005. (Monografias em Ciência da Computação, n. 20/05). ISSN 0103-9741.

> **SERRANO, Milene; SERRANO, Maurício.** Requisitos – Aula 26. Universidade de Brasília, Campus Gama (UnB Gama). Material de aula.

---

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  06/06/2025 |  Criação do Documento | [Pedro Everton](https://github.com/pedroeverton217) |  |
| `1.1`  |  06/06/2025 |  Adição da tabela de participantes, introdução, metodologia e modelo de tabela para rastreabilidade Forward-From de cada requisito | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Pedro Everton](https://github.com/pedroeverton217) |
| `1.2`  |  06/06/2025 |  Adição da rastreabilidade dos requisitos [RQ01](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq01), [RQ02](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq02), [RQ03](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq03), [RQ04](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq04), [RQ05](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq05), [RQ06](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq06), [RQ07](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq07), [RQ08](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq08), [RQ09](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq09) | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Pedro Everton](https://github.com/pedroeverton217) |
| `1.3`  |  06/06/2025 |  Adição da rastreabilidade dos requisitos [RQ10](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq10), [RQ11](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq11), [RQ12](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq12), [RQ13](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq13), [RQ14](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq14), [RQ15](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq15), [RQ16](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq16), [RQ17](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq17), [RQ18](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq18) | [Arthur Evangelista](https://github.com/arthuevg) | [Pedro Everton](https://github.com/pedroeverton217) |
| `1.4`  |  08/06/2025 |  Adição da rastreabilidade dos requisitos [RQ28](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq28), [RQ29](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq29), [RQ30](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq30), [RQ31](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq31), [RQ32](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq32), [RQ33](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq33), [RQ34](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq34), [RQ35](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq35), [RQ36](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq36) | [Euller Júlio da Silva](https://github.com/Potatoyz908) | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) |
| `1.5`  |  08/06/2025  | Adição da rastreabilidade dos requisitos [RQ37](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq37), [RQ38](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq38), [RQ39](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq39), [RQ40](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq40), [RQ41](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq41), [RQ42](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq42), [RQ43](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq43), [RQ44](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq44), [RQ45](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#rq45) | [Davi Camilo](https://github.com/Davicamilo23) | [Euller Júlio da Silva](https://github.com/Potatoyz908) |
| `1.6` | 08/06/2025 | Ajuste na rastreabilidade de léxicos, casos de uso e cenários nos requisitos 37 a 45 | [Davi Camilo](https://github.com/Davicamilo23) | [Euller Júlio da Silva](https://github.com/Potatoyz908) |
| `1.7` | 05/07/2025 | Adiciona rastreabilidade dos requisitos: [RQ19](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ20](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ21](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ22](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ23](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ24](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ25](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ26](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ27](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados) | [Gabriel Castelo](https://github.com/GabrielCastelo-31)| [Euller Júlio da Silva](https://github.com/Potatoyz908) |
| `1.8` | 05/07/2025 | Corrije rastreabilidade com base na separação de RQ20 em RQ20A e RQ20B | [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Euller Júlio da Silva](https://github.com/Potatoyz908) |
| `2.0`  |  06/07/2025 |  Correção nos requisitos que foram alterados na elicitação | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg) |
| `2.1`  |  06/07/2025 |  Correção nos requisitos não funcionais | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg) |
| `2.2` | 06/07/2025 | Adiciona rastreabilidade dos requisitos: [RQ46](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ48A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ48B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ51](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ52](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ53](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados),[RQ54](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados) | [Artur de Camargos Rodrigues](https://github.com/ArturDCR)| [Davi Camilo](https://github.com/Davicamilo23) |