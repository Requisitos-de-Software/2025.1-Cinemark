## Introdução

O Product Backlog é um artefato essencial no processo de desenvolvimento ágil, atuando como uma lista estruturada e priorizada de tudo que deve ser implementado no produto. Sob responsabilidade do Product Owner, esse backlog é continuamente atualizado e organizado, garantindo que a equipe de desenvolvimento trabalhe nos itens mais relevantes e com maior valor para o projeto.

## Metodologia

As histórias de usuário foram previamente definidas com base nos objetivos do projeto, considerando as principais funcionalidades esperadas para o sistema. A equipe de desenvolvimento ficou responsável por organizá-las, estruturando-as em uma hierarquia de temas, épicos e funcionalidades (features), de forma a facilitar o entendimento e a gestão do escopo. Após essa organização inicial, o Product Owner (PO) ficou encarregado de realizar a priorização, [botar aqui dps a priorização usada]. As tabelas a seguir apresentam o backlog estruturado com os respectivos épicos, funcionalidades e histórias de usuário, além de uma explicação sobre a hierarquia e os termos utilizados.

## Integrantes do grupo envolvidos

Tabela 1: Integrantes do grupo envolvidos no artefato.

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
						<td>Elaborou a introdução, metodologia, descrição dos temas, épicos, features e histórias de usuário. Também fez as features relacionadas às seguintes histórias de usuário: US07, US08, US09, US10, US11 e US12</td>
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
						<td>Lorem Ipsum</td>
					</tr>
			</tbody>
		</table>
	</div>
</div>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

# Temas

Analisando as histórias de usuário definidas para o projeto Cinemark, agrupamos os requisitos em três grandes temas:

1. **Conta e Autenticação**: tudo que envolve criação de conta, login e recuperação de credenciais.  
2. **Exploração de Filmes**: funcionalidades que permitem ao usuário navegar, filtrar e visualizar informações relacionadas aos filmes.  
3. **Compra e Finalização**: todo o fluxo de compra de ingressos e produtos, desde a seleção até a confirmação.

---

# Features

Cada épico (descrito abaixo) foi desdobrado em features, que representam capacidades de alto nível do produto. A tabela a seguir mostra o mapeamento entre épicos e features.

| Épico                         | Feature                                   |
|-------------------------------|------------------------------------------|
| Épico 1 – Conta e Autenticação     | Feature 1 – Criação de Conta e Login       |
|                               | Feature 2 – Recuperação de Conta           |
| Épico 2 – Exploração de Filmes     | Feature 3 – Histórico de Filmes e Compras  |
|                               | Feature 4 – Filtragem por Categoria        |
|                               | Feature 5 – Exibição de Trailers           |
|                               | Feature 11 – Exibir e Permitir Avaliações          |
| Épico 3 – Compra e Finalização     | Feature 6 – Fluxo de Compra Simplificado   |
|                               | Feature 7 – Armazenar Cartões de pagamento           |
|                               | Feature 8 – Compra de Múltiplos Ingressos           |
|                               | Feature 9 – Mapa Gráfico da Sala            |
|                               | Feature 10 – Definir Tipo de Ingresso           |

<sub><p align="center">Autores: [Arthur Evangelista](https://github.com/arthurevg), [Tiago Antunes Balieiro](https://github.com/tiagobalieiro)</p></sub>

---

## Histórias de Usuário

As [Histórias de Usuário]((https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario)	) estão detalhadas numa seção dedicada a elas. Elas ajudam a transformar os épicos em funcionalidades mais claras e focadas no ponto de vista de quem vai usar o sistema. Elas servem como um guia prático para o desenvolvimento, mostrando o que o usuário espera fazer e por quê. Geralmente, obedecem o seguinte formato:

> “Eu, como [tipo de usuário], desejo [funcionalidade] para [objetivo].”

Cada uma está ligada a um épico, servindo como base para decisões de projeto, testes e validações futuras.

## Product Backlog

### Épico 1 – Autenticação e Gerenciamento de Conta
> *Objetivo: Permitir ao usuário gerenciar sua conta de forma prática e segura, incluindo funcionalidades como cadastro, login, recuperação de senha, gerenciamento de métodos de pagamento e acesso ao histórico de compras.*

| Feature                           | História de Usuário (ID)                                 | Priorização |
|-----------------------------------|----------------------------------------------------------|-------------|
| Feature 1 – Criação de Conta e Login   | [US07](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) – Criação de conta e login com redes sociais        |         |
| Feature 2 – Recuperação de Conta       | [US08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) – Recuperação de conta via e-mail ou CPF            |         |
| Feature 3 – Histórico de Compras   | [US09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) – Exibir histórico de filmes e compras                |       |

<sub><p align="center">Autores: [Arthur Evangelista](https://github.com/arthurevg)</p></sub>

---

### Épico 2 – Exploração de Filmes  
> *Objetivo: oferecer ao usuário formas rápidas de navegar pelo catálogo, ver detalhes sobre os filmes e assistir trailers.*

| Feature                              | História de Usuário (ID)                                   | Priorização |
|--------------------------------------|------------------------------------------------------------|-------------|
| Feature 4 – Filtragem por Categoria        | [US10](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) – Filtrar filmes por categoria                         |         |
| Feature 5 – Exibição de Trailers           | [US11](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) – Exibir trailers dentro do app                        |       |
| Feature 11 – Exibir e Permitir Avaliações           | [US06](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) –  Exibir e Permitir Avaliações                       |       |

<sub><p align="center">Autores: [Arthur Evangelista](https://github.com/arthurevg), [Tiago Antunes Balieiro](https://github.com/tiagobalieiro)</p></sub>

---

### Épico 3 – Compra e Finalização  
> *Objetivo: garantir que o usuário consiga concluir sua compra (ingressos/produtos) de forma ágil e intuitiva.*

| Feature                             | História de Usuário (ID)                                    | Priorização |
|-------------------------------------|-------------------------------------------------------------|-------------|
| Feature 6 – Fluxo de Compra Simplificado  | [US12](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) – Fluxo de compra simplificado                         |       |
| Feature 7 – Armazenar Cartões de pagamento  | [US01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) – Armazenar Cartões de pagamento                         |       |
| Feature 8 – Compra de Múltiplos Ingressos  | [US02](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) – Compra de Múltiplos Ingressos                        |       |
| Feature 9 – Mapa Gráfico da Sala  | [US03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) – Mapa Gráfico da Sala                         |       |
| Feature 10 – Definir Tipo de Ingresso  | [US04](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) – Definir Tipo de Ingresso                         |       |

<sub><p align="center">Autores: [Arthur Evangelista](https://github.com/arthurevg), [Tiago Antunes Balieiro](https://github.com/tiagobalieiro)</p></sub>

---
## Épicos

Para contextualizar, cada épico abaixo traz uma descrição sucinta de seu propósito e suas histórias de usuário relacionadas(ID).
 
---

### Épico 1: Autenticação e Gerenciamento da Conta
**Histórias de usuário relacionadas:** [US07](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario), [US08](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) e [US09](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) 

**Descrição:** Este épico agrupa tudo o que é necessário para que um usuário crie uma conta Cinemark (inclusive usando redes sociais), faça login no app e recupere sua conta caso tenha problemas com suas credenciais.  

---

### Épico 2: Exploração de Filmes  
**Histórias de usuário relacionadas:** [US10](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario), [US11](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) e [US06](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario)

**Descrição:** Foca nas funcionalidades de navegação pelo catálogo de filmes:    
- Filtrar a lista de filmes por categorias (gênero, classificação etária etc.);  
- Assistir trailers diretamente no próprio app Cinemark.  

---

### Épico 3: Compra e Finalização  
**Histórias de usuário relacionadas:** [US12](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario), [US01](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario), [US02](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario), [US03](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario) e [US04](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/#historias-de-usuario)  

**Descrição:**  Este épico engloba as funcionalidades para o usuário criar, acessar e recuperar sua conta de forma simples e segura, incluindo login com redes sociais. Também abrange o gerenciamento da conta, com recursos como a visualização do histórico de compras realizadas, funcionalidades no pagamento e melhorias para o usuário ao comprar o ingresso.

---





## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  22/05/2025 |  Criação do Documento | [Davi Camilo](https://github.com/Davicamilo23)  | [Euller Júlio da Silva](https://github.com/Potatoyz908) |
| `1.1`  | 26/05/2025 | Adição do modelo da tabela de participantes | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.2`  | 31/05/2025 | Adição da introdução, metodologia, descrição dos temas, épicos, features e histórias de usuário. Foi adicionado as features relacionadas a US07, US08, US09, US10, US11 e US12 | [Arthur Evangelista](https://github.com/arthurevg) | [Artur de Camargos](https://github.com/ArturDCR) |

