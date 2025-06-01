## Introdução

Uma forma de garantir que o software atenda às expectativas dos usuários e stakeholders é por meio da definição de requisitos não funcionais (NFRs). Esses requisitos abrangem aspectos como desempenho, segurança, usabilidade, manutenibilidade e portabilidade. O NFR Framework é uma abordagem que ajuda a identificar, categorizar e priorizar esses requisitos, garantindo que o software seja desenvolvido de acordo com as necessidades do negócio e dos usuários.

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

## Softgoal Interdependency Graph

Um Softgoal Interdependency Graph (SIG) é uma representação gráfica usada no framework de Requisitos Não Funcionais (NFR) para ilustrar como diferentes objetivos de qualidade (softgoals) se influenciam mutuamente. Nele, cada softgoal aparece como um nó, e as arestas indicam relações de contribuição—como “ajuda”, “prejudica”, “faz” ou “quebra”—entre esses objetivos. Isso permite visualizar conflitos e sinergias entre requisitos de qualidade (por exemplo, segurança vs. usabilidade) e apoiar a tomada de decisões durante o projeto de sistemas.

### Tipos de Softgoals

Existem 3 tipos de softgoals: Softgoals NFR, Softgoals de Operacionalização e Softgoals de Afirmação. Softgoals NFR correspondem diretamente aos requisitos não-funcionais, podendo aparecer organizados em catálogos e hierarquias ao longo do projeto de modo a capturar qualidades desejadas (por exemplo, “Desempenho” ou “Segurança”) . Já os Softgoals de Operacionalização representam alternativas concretas de implementação para atender a esses softgoals NFR ou a outros softgoals de operacionalização, envolvendo processos, estruturas de dados ou restrições no sistema-alvo (como “usar comunicação via SSL” para satisfazer o softgoal de segurança) . Por fim, os Softgoals de Afirmação—também chamados de claims—reúnem características do domínio (por exemplo, prioridades, carga de trabalho ou restrições de negócio) que fundamentam decisões de design; eles servem de justificativa para apoiar ou negar formas de priorização e refinamento, fornecendo razões claras para escolhas arquiteturais e facilitando rastreabilidade e revisão futura

**Figura 1 - Tipos de Softgoal**

![SOFTGOALS](https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Cinemark/main/docs/assets/modelagem/softgoals.png)

<p align="center"><em>Fonte: SILVA, 2019</em></p>

## Modelo de Cartão de Especificação

Tabela 2 - Modelo de tabela de Cartão de Especificação

| Nº Requisito: 1 (RQXX)[https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ26]| Classificação: XXXX |
|---------------| ------------|
| Descrição: XXXX.
| Justificativa: XXXX.
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: XXXX. 
| Dependências: XXXX
| Prioridade: XXXX
| Conflitos: XXXX
| História: --/--/----

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

## Tabela X - Requisitos Não-Funcionais Não Implementados

| ID    | Descrição                                                                 | Tipo         |
|-------|---------------------------------------------------------------------------|--------------|
| RQ54 | Ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos). | Segurança     |
| RQ40 | Tempo de resposta de até 3 segundos em telas críticas (seleção de assentos, pagamento). | Eficiência    |
| RQ44 | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão. | Usabilidade   |
| RQ47 | Atualizar automaticamente o valor total conforme seleção de ingressos e produtos. | Eficiência    |
| RQ49 | Autenticação por biometria ou PIN para operações sensíveis. | Segurança     |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg).</p></font>

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  22/05/2025 |  Criação do Documento | [Davi Camilo](https://github.com/Davicamilo23)  | [Euller Júlio da Silva](https://github.com/Potatoyz908) |
| `1.1`  | 26/05/2025 | Adição do modelo da tabela de participantes | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.2`  | 01/06/2025 | Adição do modelo da tabela de Cartão de Especificação e correção da imagem dos tipos de Softgoal | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.3`  | 01/06/2025 | Adição de introdução e Softgoal Interdependency Graph | [Gabriel Castelo](https://github.com/GabrielCastelo-31) e [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Davi Camilo](https://github.com/Davicamilo23) |

