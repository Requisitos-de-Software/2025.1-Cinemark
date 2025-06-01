## Introdução

As Histórias de Usuário são uma técnica da Engenharia de Requisitos utilizada para descrever, de forma simples e objetiva, as necessidades dos usuários em relação a um sistema. Elas permitem que as equipes compreendam claramente os objetivos do usuário e suas expectativas. Essa abordagem facilita a comunicação entre as partes envolvidas e serve como base para a criação de critérios de aceitação, essenciais no desenvolvimento ágil. Além disso, elas servem como base para a criação de critérios de aceitação, que ajudam na validação da entrega das funcionalidades.

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
						<td>Elaborou as Histórias de Usuário US31, US32, US33, US34, US35 e US36 (tabelas 33 a 38)</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/arthurevg">Arthur Evangelista</a></td>
						<td>Elaborou a metodologia, as Histórias de usuário US07, US08, US09, US10, US11 e US12(tabelas 9 a 14) e participou como entrevistador na piorização das histórias de usuário.</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/Davicamilo23">Davi Camilo</a></td>
						<td>Elaborou as Histórias de Usuário US19, US20, US21, US22, US23 e US24 (tabelas 21 a 26) e participou como entrevistador na piorização das histórias de usuário.</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/Potatoyz908">Euller Júlio</a></td>
						<td>Elaborou as Histórias de Usuário US13, US14, US15, US16, US17 e US18 (tabelas 15 a 20) e participou como entrevistador na piorização das histórias de usuário.</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a></td>
						<td>Elaborou as Histórias de Usuário US25, US26, US27, US28, US29 e US30 (tabelas 27 a 32) e participou como entrevistador na piorização das histórias de usuário</td>
					</tr>
					<tr>
						<td><a  href="https://github.com/tiagobalieiro">Tiago Antunes Balieiro</a></td>
						<td>Elaborou a introdução, o modelo de tabela para histórias de usuário, as Histórias de Usuário US01, US02, US03, US04, US05 e US06 (tabelas 6 a 8) e participou como entrevistador na piorização das histórias de usuário.</td>
					</tr>
          <tr>
						<td>Victor Magalhães (Product Owner)</td>
						<td>Participou da priorização das histórias de usuário.</td>
					</tr>
			</tbody>
		</table>
	</div>
</div>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

## Metodologia

As histórias de usuário foram elaboradas com base nos [Requisitos Elicitados](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) anteriormente. Cada história foi escrita de acordo com a Tabela 2.

Essa estrutura facilita o entendimento das necessidades dos usuários finais e auxilia na comunicação entre membros da equipe de desenvolvimento.

Para garantir **rastreabilidade**, cada história de usuário está associada explicitamente a um ou mais requisitos elicitados. Isso permite mapear quais funcionalidades estão sendo cobertas e monitorar o progresso e a cobertura do sistema em relação aos objetivos iniciais.

A priorização foi feita utilizando a técnica **Three-Level Scale estendida**, com os seguintes níveis:

* **Alta**: deve ser implementada no primeiro ciclo de desenvolvimento. É essencial para o funcionamento do sistema.
* **Média**: relevante, mas pode ser implementada em ciclos posteriores.
* **Baixa**: desejável, mas opcional; agrega valor, mas não é crítica.
* **Não deve ser implementada**: identificada durante a elicitação, mas foi descartada por motivos de viabilidade, escopo ou prioridade estratégica.

Essa escala ajuda a organizar os esforços da equipe de forma mais estratégica, focando nas entregas que realmente trazem valor imediato ao usuário e ao negócio, ao mesmo tempo em que documenta funcionalidades que podem ser revisitadas no futuro ou que foram explicitamente desconsideradas.

Tabela 2: Modelo de tabela para histórias de usuário.

<div align="center">
  <table>
    <tr>
      <th>ID</th>
      <th>Nome</th>
    </tr>
    <tr>
      <td>USXX</td>
      <td>Título</td>
    </tr>
    <tr>
      <td>Descrição</td>
      <td><em>Eu, como</em> XXX, <em>desejo</em> XXX <em>para</em> XXX</td>
    </tr>
    <tr>
      <td>Critérios de Aceitação</td>
      <td>-XXX <br> -XXX <br></td>
    </tr>
    <tr>
      <td>Prioridade</td>
      <td>Alta, Média ou Baixa, ou desconsiderada</td>
    </tr>
    <tr>
      <td>Rastreabilidade</td>
      <td>RQXX</td>
    </tr>
  </table>
</div>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

## Histórias de Usuário

### US01 - Armazenar cartões de pagamento

<details>
  <summary><strong>Tabela 3 - História de Usuário Armazenar cartões de pagamento</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US01</td>
        <td>Armazenar cartões de pagamento</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> que o aplicativo armazene cartões de pagamento já cadastrados <em>para</em> uso em compras futuras.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>- Na página de pagamento do aplicativo, deve haver uma seção exibindo os cartões previamente salvos. <br> - Ao selecionar um cartão, as informações necessárias devem ser preenchidas automaticamente. <br></td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
	  <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ10">
            RQ10
          </a>
        </td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

### US02 - 	Permitir compra de múltiplos ingressos em uma única transação

<details>
  <summary><strong>Tabela 4 - História de Usuário Permitir compra de múltiplos ingressos em uma única transação</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US02</td>
        <td>Permitir compra de múltiplos ingressos em uma única transação</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> comprar múltiplos ingressos em uma única transação, informando a quantidade de ingressos desejada <em>para</em> simplificar o processo de compra e torná-lo mais eficaz.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>- A página de escolha dos assentos deve permitir a escolha de múltiplos assentos. <br> - Ao selecionar mais de um assento, deve ser possível escolher o tipo de cada ingresso individualmente (inteira, meia, gratuidade). <br></td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
	  <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ11">
            RQ11
          </a>
        </td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

### US03 - Exibir mapa gráfico da sala
<details>
  <summary><strong>Tabela 5 - Exibir mapa gráfico da sala</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US03</td>
        <td>Exibir mapa gráfico da sala</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> que o aplicativo exiba um mapa da sala com indicação de assentos ocupados, livres e especiais <em>para</em> que eu possa escolher entre os assentos disponíveis.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>- Na página de escolha dos assentos, os assentos ocupados, livres e especias devem ser representados por símbolos e cores diferentes. <br> - Ao selecionar um assento, o assento selecionado deve apresentar uma indicação gráfica e uma cor distinta. <br></td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
	  <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ12">
            RQ12
          </a>
        </td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

### US04 - Definir tipo de ingresso por assento

<details>
  <summary><strong>Tabela 6 - História de Usuário Definir tipo de ingresso por assento</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US04</td>
        <td>Definir tipo de ingresso por assento</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> definir o tipo de ingresso por assento <em>para</em> selecionar cada ingresso como inteira, meia ou convênio.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>- Na tela de compra do ingresso, deve haver uma opção para cada ingresso apresentando os tipos disponíveis. <br> - O tipo do ingresso deve ser exibido mesmo após a finalização da compra ao acessar o ingresso. <br></td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
	  <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ14">
            RQ14
          </a>
        </td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

### US05 - Salvar ingressos na carteira digital do dispositivo

<details>
  <summary><strong>Tabela 7 - Salvar ingressos na carteira digital do dispositivo</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US05</td>
        <td>Salvar ingressos na carteira digital do dispositivo</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> que o aplicativo permita que eu salve ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc)<em>para</em> uma maior integração e diversificando as opções para acessar o meu ingresso.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>- Na tela do pedido deve haver um botão para adicionar o ingresso na carteira digital do dispositivo. <br> - O aplicativo deve informar quais carteiras digitais podem ser usadas, ou caso não exista nenhuma carteira no dispositivo. <br></td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
	  <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ26">
            RQ26
          </a>
        </td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

### US06 - Exibir e permitir avaliações

<details>
  <summary><strong>Tabela 8 - História de Usuário Exibir e permitir avaliações</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US01</td>
        <td>Exibir e permitir avaliações</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> que o aplicativo exiba avaliações de filmes e exiba um campo de avaliação <em>para</em> que eu possa avaliar um filme em uma escala de 1 a 5 estrelas. <br></td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>- Na página do filme deve haver uma seção mostrando as avaliações de outros usuários sobre o filme. <br> - Na página do filme deve haver um campo de avaliação. <br> - O campo de avaliação deve ser em formato de 1 a 5 estrelas</td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
	  <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ39">
            RQ39
          </a>
        </td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

### US07 - Criação de conta e login com redes sociais

<details>
  <summary><strong>Tabela 9 - História de Usuário Criação de conta e login com redes sociais</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US07</td>
        <td>Criação de conta e login com redes sociais</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> criar uma conta informando nome, e-mail, senha e CPF ou fazer login via Google/redes sociais <em>para</em> acessar o aplicativo de forma segura e rápida.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Na tela de cadastro, o usuário deve conseguir preencher nome, e-mail, senha e CPF e receber confirmação de sucesso. <br>
          - Na tela de login, deve haver opção para autenticar com Google ou outras redes sociais, como por exemplo, o Facebook, além do login convencional com e-mail e senha. <br>
          - Se o e-mail ou CPF já estiverem cadastrados, o sistema deve exibir mensagem de erro indicando que já existe uma conta com aqueles dados. <br>
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>[ainda não consta]</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ20">
            RQ20
          </a>
        </td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg).</p></font>

### US08 - Recuperação de conta via e-mail ou CPF

<details>
  <summary><strong>Tabela 10 - História de Usuário Recuperação de conta via e-mail ou CPF</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US08</td>
        <td>Recuperação de conta via e-mail ou CPF</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> recuperar meu acesso ao aplicativo enviando um link de redefinição de senha por e-mail ou recuperando meu e-mail através do CPF para, então, redefinir minha senha com código <em>para</em> voltar a usar minha conta quando esquecer minhas credenciais.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Na tela de login, deve haver link “Esqueci minha senha” que redireciona para um formulário pedindo e-mail ou CPF. <br>
          - Ao informar o CPF, o sistema deve buscar o e-mail cadastrado e enviar um código de redefinição. <br>
          - Ao informar o e-mail diretamente, o sistema deve enviar um link seguro para redefinição de senha. <br>
          - O usuário deve conseguir redefinir a senha usando o código ou o link enviado, com confirmação ao final, garantindo ao usuário que a operação foi concluída com sucesso. <br>
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>[ainda não consta]</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td>
        <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ21">
            RQ21
          </a>
        </td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg).</p></font>

### US09 - Exibir histórico de filmes e compras

<details>
  <summary><strong>Tabela 11 - História de Usuário Exibir histórico de filmes e compras</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US09</td>
        <td>Exibir histórico de filmes e compras</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário autenticado, <em>desejo</em> visualizar meu histórico de filmes assistidos (com data, horário e cinema) e meu histórico de compras na bomboniere <em>para</em> acompanhar meus registros, visualizar minhas compras e avalar possíveis reembolsos.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Na área do usuário, deve haver seção “Histórico” que lista cada compra realizada no aplicativo. <br>
          - Caso a compra tenha sido de itens da bomboniere, deve ser exibido a data, itens e valor da compra. <br>
          - Caso a compra tenha sido de ingressos, deve ser exibido a data, filme, cinema, sessão e o valor gasto. <br>
          - Se não houver histórico, deve exibir uma mensagem informando “Nenhum registro encontrado”. <br>
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>[ainda não consta]</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td>
         <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ22">
            RQ22
          </a>
        </td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg).</p></font>

### US10 - Filtrar filmes por categoria

<details>
  <summary><strong>Tabela 12 - História de Usuário Filtrar filmes por categoria</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US10</td>
        <td>Filtrar filmes por categoria</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> aplicar filtros por categoria de filme e visualizar avaliações de público e plataformas externas <em>para</em> encontrar rapidamente produções de meu interesse com base em reviews confiáveis.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Na tela de listagem de filmes, deve existir opção de selecionar uma ou mais categorias (por exemplo: Ação, Comédia, Drama). <br>
          - Após aplicar filtro, apenas os filmes das categorisas selecionadas devem ser exibidos. <br>
          - Para cada filme listado, deve exibir nota média do público e resumo de avaliação de plataforma externa (por exemplo, IMDb). <br>
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>[ainda nao consta]td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td> <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ23">
            RQ23
          </a></td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg).</p></font>

### US11 - Exibir trailers dentro do app

<details>
  <summary><strong>Tabela 13 - História de Usuário Exibir trailers dentro do app</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US11</td>
        <td>Exibir trailers dentro do app</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> assistir trailers dos filmes diretamente no aplicativo <em>para</em> avaliar rapidamente se quero comprá-los antes de ir ao cinema.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Na página de detalhes de cada filme, deve existir botão “Assistir Trailer”. <br>
          - Ao clicar em “Assistir Trailer”, o vídeo deve ser reproduzido dentro do próprio app, sem necessidade de sair para site externo. <br>
          - O player deve permitir play, pause e controle de volume. <br>
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>[ainda nao consta]</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td> <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ24">
            RQ24
          </a></td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg).</p></font>

### US12 - Fluxo de compra simplificado

<details>
  <summary><strong>Tabela 14 - História de Usuário Fluxo de compra simplificado</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US12</td>
        <td>Fluxo de compra simplificado</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> realizar a compra de ingressos e snacks com o mínimo de toques até a confirmação <em>para</em> tornar o processo mais rápido e conveniente, minimizando a taxa de desistência de compra.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Deve haver um fluxo unificado que permita selecionar filme, assento e snacks em seguida, sem voltar a telas intermediárias. <br>
          - Em cada passo, exibir informações resumidas do carrinho (filme, assento, itens da bomboniere). <br>
          - O resumo final deve exibir o total a pagar e permitir confirmação com um único toque. <br>
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>[ainda nao consta]</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td> <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ25">
            RQ25
          </a></td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista](https://github.com/arthurevg).</p></font>

### US13 - Reservar salas para eventos

<details>
  <summary><strong>Tabela 15 - História de Usuário Reservar salas para eventos</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US13</td>
        <td>Reservar salas para eventos</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> reservar salas de cinema para eventos privados <em>para</em> realizar eventos personalizados, como festas ou reuniões.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O aplicativo deve permitir seleção de data, hora e quantidade de pessoas. <br>
          - O usuário deve visualizar claramente a disponibilidade das salas antes da confirmação. <br>
          - O usuário deve receber uma confirmação após a reserva ser efetuada com sucesso.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq59" target="_blank">RQ59</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908).</p></font>

### US14 - Alterar preferências de idioma

<details>
  <summary><strong>Tabela 16 - História de Usuário Alterar preferências de idioma</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US14</td>
        <td>Alterar preferências de idioma</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> alterar as preferências de idioma no aplicativo <em>para</em> personalizar minha experiência de navegação.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O usuário deve conseguir acessar as configurações de idioma facilmente.<br>
          - O sistema deve aplicar imediatamente o novo idioma selecionado em todas as telas do aplicativo.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq33" target="_blank">RQ33</a></td>
</tr>
    </tbody>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908).</p></font>

### US15 - Detectar localização automaticamente

<details>
  <summary><strong>Tabela 17 - História de Usuário Detectar localização automaticamente</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US15</td>
        <td>Detectar localização automaticamente e permitir alteração manual</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> que o aplicativo detecte automaticamente minha localização e permita alterá-la manualmente <em>para</em> ver sessões e cinemas próximos à minha região.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O aplicativo deve detectar automaticamente a localização do usuário ao iniciar.<br>
          - O usuário deve ter a opção clara para alterar a localização manualmente.<br>
          - Ao alterar a localização, o sistema deve atualizar imediatamente as informações apresentadas.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq02" target="_blank">RQ02</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908).</p></font>

### US16 - Selecionar assento obrigatório

<details>
  <summary><strong>Tabela 18 - História de Usuário Selecionar assento obrigatório</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US16</td>
        <td>Exigir seleção de assento antes do pagamento</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> ser obrigado a selecionar um assento antes de prosseguir com o pagamento <em>para</em> garantir que tenho lugar reservado na sala escolhida.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O aplicativo deve impedir que o usuário avance para pagamento sem selecionar um assento.<br>
          - Deve haver uma mensagem clara indicando que é necessário selecionar o assento antes de continuar.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq13" target="_blank">RQ13</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908).</p></font>

### US17 - Permitir cancelar compras

<details>
  <summary><strong>Tabela 19 - História de Usuário Cancelar compras</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US17</td>
        <td>Permitir cancelar compras</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> cancelar compras feitas anteriormente <em>para</em> corrigir erros ou desistir da compra.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O usuário deve ter uma opção clara para cancelar a compra.<br>
          - O cancelamento deve gerar uma confirmação de sucesso visível para o usuário.<br>
          - Deve ser especificado um prazo limite para cancelamento da compra.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
     <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq62" target="_blank">RQ62</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908).</p></font>

### US18 - Excluir conta permanentemente

<details>
  <summary><strong>Tabela 20 - História de Usuário Excluir conta permanentemente</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US18</td>
        <td>Excluir conta permanentemente</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> excluir permanentemente minha conta do aplicativo <em>para</em> garantir que meus dados não fiquem armazenados caso eu não queira mais utilizar o serviço.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O usuário deve acessar facilmente a opção para exclusão da conta.<br>
          - O sistema deve pedir confirmação adicional antes da exclusão.<br>
          - Após exclusão, todos os dados pessoais devem ser permanentemente removidos do sistema.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq64" target="_blank">RQ64</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908).</p></font>

### US19 - Exibir recomendações de filmes baseadas em histórico e preferências

<details>
  <summary><strong>Tabela 21 - História de Usuário Exibir recomendações de filmes baseadas em histórico e preferências</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US19</td>
        <td>Exibir recomendações de filmes baseadas em histórico e preferências</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> visualizar recomendações personalizadas de filmes com base no meu histórico de navegação e preferências <em>para</em> descobrir novos títulos que são de interesse.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O sistema deve apresentar uma seção com recomendações personalizadas na tela inicial ou em uma aba dedicada.<br>
          - As recomendações devem levar em consideração o histórico de filmes visualizados e/ou avaliados pelo usuário.<br>
          - O usuário pode atualizar suas preferências de gênero ou estilo, influenciando as recomendações futuras.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
      <td>Rastreabilidade</td>
        <td> <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ32">
            RQ32
          </a></td>
      </tr>
    </tbody>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23).</p></font>

### US20 - Fornecer comparação de preços entre cinemas

<details>
  <summary><strong>Tabela 22 - História de Usuário Fornecer comparação de preços entre cinemas</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US20</td>
        <td>Fornecer comparação de preços entre cinemas</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> comparar os preços de ingressos em diferentes cinemas <em>para</em> optar pela melhor opção de custo-benefício.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O aplicativo deve exibir, para um mesmo filme, os preços de ingresso em diferentes cinemas próximos.<br>
          - As comparações devem incluir preço por tipo de ingresso (inteira, meia, 3D, entre outros) e cinema.<br>
          - A exibição dos preços deve estar atualizada conforme os dados fornecidos pelos cinemas.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
      <td>Rastreabilidade</td>
        <td> <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ58">
            RQ58
          </a></td>
      </tr>
    </tbody>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23).</p></font>

### US21 - Permitir notificações personalizadas

<details>
  <summary><strong>Tabela 23 - História de Usuário Permitir notificações personalizadas</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US21</td>
        <td>Permitir notificações personalizadas</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> configurar notificações personalizadas como "avise-me quando o filme X entrar em cartaz" <em>para</em> não perder lançamentos que são de meu interesse.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O usuário deve poder marcar filmes para ser notificado quando estes estiverem disponíveis.<br>
          - As notificações devem ser enviadas por push ou e-mail, conforme a escolha do usuário.<br>
          - O sistema deve permitir gerenciar e remover notificações configuradas.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
      <td>Rastreabilidade</td>
        <td> <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ31">
            RQ31
          </a></td>
      </tr>
    </tbody>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23).</p></font>

### US22 - Buscar filmes por nome

<details>
  <summary><strong>Tabela 24 - História de Usuário Buscar filmes por nome</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US22</td>
        <td>Buscar filmes por nome</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> buscar filmes pelo nome <em>para</em> localizar rapidamente o conteúdo que desejo assistir.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O aplicativo deve permitir digitar o nome de um filme em um campo de busca.<br>
          - Os resultados devem ser exibidos em tempo real ou após clicar no botão de busca.<br>
          - A busca deve ser flexível, aceitando variações como letras maiúsculas/minúsculas, acentuação e nomes parciais.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
      <td>Rastreabilidade</td>
        <td> <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ05">
            RQ05
          </a></td>
      </tr>
    </tbody>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23).</p></font>

### US23 - Listar filmes em cartaz, pré-venda e futuros lançamentos

<details>
  <summary><strong>Tabela 25 - História de Usuário Listar filmes em cartaz, pré-venda e futuros lançamentos</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US23</td>
        <td>Listar filmes em cartaz, pré-venda e futuros lançamentos</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> visualizar listas de filmes em cartaz, em pré-venda e em breve lançamento <em>para</em> planejar melhor minhas idas ao cinema.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O sistema deve exibir separadamente os filmes em cartaz, os disponíveis em pré-venda e os lançamentos futuros.<br>
          - As listas devem ser atualizadas automaticamente conforme as datas de exibição dos filmes.<br>
          - O usuário deve poder navegar entre essas categorias de forma intuitiva, compreendendo a diferença entre as categorias.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
      <td>Rastreabilidade</td>
        <td> <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ06">
            RQ06
          </a></td>
      </tr>
    </tbody>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23).</p></font>

### US24 - Exibir informações do filme

<details>
  <summary><strong>Tabela 26 - História de Usuário Exibir informações do filme</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US24</td>
        <td>Exibir informações do filme</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> acessar informações detalhadas sobre o filme, como título, sinopse, gênero, duração, direção, elenco, distribuidor e origem <em>para</em> decidir se quero assisti-lo.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - A página do filme deve exibir claramente todas as informações relevantes: título, sinopse, gênero, duração, direção, elenco, distribuidor e país de origem.<br>
          - As informações devem ser organizadas de forma visualmente clara e acessível para os usuários.<br>
          - O usuário deve conseguir acessar essa página a partir da listagem ou busca de filmes.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
      <td>Rastreabilidade</td>
        <td> <a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#:~:text=RQ07">
            RQ07
          </a></td>
      </tr>
    </tbody>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23).</p></font>

### US25 - Utilização de pontos para desconto

<details>
  <summary><strong>Tabela 27 - História de Usuário Utilização de pontos para desconto</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US25</td>
        <td>Utilização de pontos para desconto</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como </em>usuário do programa de fidelidade da Cinemark, <em>desejo</em> utilizar meus pontos acumulados <em>para</em> obter desconto em ingressos e produtos.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O sistema deve exibir o saldo atual de pontos do usuário autenticado.<br>
          - O sistema deve permitir selecionar o uso de pontos no momento do pagamento de ingressos e/ou produtos.<br>
          - O valor do desconto correspondente aos pontos utilizados deve ser claramente informado antes da confirmação da compra.<br>
          - O sistema deve atualizar corretamente o saldo de pontos após a utilização.<br>
          - O sistema deve impedir a utilização de pontos se o saldo for insuficiente.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq27" target="_blank">RQ27</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor:  [Gabriel Castelo](https://github.com/GabrielCastelo-31).</p></font>

### US26 - Salvamento automático de ingressos

<details>
  <summary><strong>Tabela 28 - História de Usuário Salvamento automático de ingressos</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US26</td>
        <td>Salvamento automático de ingressos</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como </em> usuário do aplicativo Cinemark, <em>desejo</em> que meus ingressos sejam salvos automaticamente na seção “Meus Ingressos” após a confirmação da compra <em>para</em> acessá-los facilmente quando precisar apresentá-los no cinema.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O sistema deve salvar automaticamente os ingressos comprados na seção “Meus Ingressos” assim que a transação for confirmada.<br>
          - O usuário deve conseguir visualizar detalhes como filme, data, horário, poltrona e detalhes do ingresso.<br>
          - O ingresso salvo deve estar disponível mesmo sem conexão com a internet.<br>
          - O sistema deve armazenar os ingressos apenas para o usuário autenticado que realizou a compra.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq19" target="_blank">RQ19</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor:  [Gabriel Castelo](https://github.com/GabrielCastelo-31).</p></font>

### US27 - Alerta sobre pontos acumulados

<details>
  <summary><strong>Tabela 29 - História de Usuário Alerta sobre pontos acumulados</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US27</td>
        <td>Alerta sobre pontos acumulados</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como </em> usuário do aplicativo Cinemark, <em>desejo</em> receber alertas quando a quantidade de pontos permitir resgate de ingresso grátis e antes da expiração dos pontos <em>para</em> não perder a oportunidade de usá-los a tempo.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O sistema deve alertar o usuário quando ele acumular pontos suficientes para trocar por um ingresso grátis.<br>
          - O sistema deve alertar o usuário com antecedência mínima de 10 dias antes da expiração dos pontos.<br>
          - Os altertas devem ser repetidos a cada 2 dias após o primeiro alerta, até que o usuário utilize os pontos ou eles expirem.<br>
          - Os alertas devem estar disponíveis via notificações push e na área de notificações do aplicativo.<br>
          - O alerta deve informar o número de pontos disponíveis e o benefício correspondente.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq28" target="_blank">RQ28</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor:  [Gabriel Castelo](https://github.com/GabrielCastelo-31).</p></font>

### US28 - Favoritar cinemas

<details>
  <summary><strong>Tabela 30 - História de Usuário Favoritar cinemas</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US28</td>
        <td>Favoritar cinemas</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como </em> usuário do aplicativo Cinemark, <em>desejo</em> salvar cinemas como favoritos <em>para</em> acessar rapidamente minhas unidades preferidas ao procurar sessões ou realizar compras.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O sistema deve permitir que o usuário marque um ou mais cinemas como favoritos.<br>
          - Os cinemas favoritados devem aparecer no topo das listas de seleção de unidades.<br>
          - O usuário deve conseguir visualizar, editar ou remover cinemas da lista de favoritos.<br>
          - Os favoritos devem ser armazenados por usuário autenticado e persistir entre sessões do app.<br>
          - O usuário deve receber uma confirmação visual ao favoritar ou desfavoritar um cinema.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq30" target="_blank">RQ30</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor:  [Gabriel Castelo](https://github.com/GabrielCastelo-31).</p></font>

### US29 - Área dedicada ao Cinemark Club

<details>
  <summary><strong>Tabela 31 - História de Usuário Área dedicada ao Cinemark Club</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US29</td>
        <td>Área dedicada ao Cinemark Club</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como </em> usuário do aplicativo Cinemark e membro do Cinemark Club, <em>desejo</em> acessar uma área dedicada no aplicativo que reúna meus ingressos, pontos acumulados e sua validade, <em>para</em> visualizar de forma centralizada meu histórico de benefícios e controlar o uso dos meus pontos de fidelidade.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O sistema deve disponibilizar uma seção exclusiva para membros do Cinemark Club.<br>
          - A área deve estar acessível a partir do menu principal do aplicativo.<br>
          - O usuário deve conseguir visualizar seus pontos acumulados, ingressos disponíveis e respectivas validades.<br>
          - O sistema deve permitir que o usuário visualize o histórico de uso dos pontos e ingressos.<br>
          - O usuário deve conseguir acessar facilmente as regras do programa de fidelidade e como acumular mais pontos. <br>
          - O usuário deve poder acessar o histórico de uso dos pontos e ingressos.<br>
          - A área do Cinemark Club deve estar disponível apenas para usuários autenticados e manter persistência de dados entre sessões do app.</br>
          - Deve existir um indicador visual (por exemplo, aviso destacado) quando houver pontos prestes a expirar nos próximos 7 dias.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq34" target="_blank">RQ34</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor:  [Gabriel Castelo](https://github.com/GabrielCastelo-31).</p></font>

### US30 - Sugestão de cinemas personalizada

<details>
  <summary><strong>Tabela 32 - História de Usuário Sugestão de cinemas personalizada</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US30</td>
        <td>Sugestão de cinemas personalizada</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como </em> usuário do aplicativo Cinemark, <em>desejo</em> receber sugestões de cinemas com base no meu histórico de visitas e na minha localização atual, <em>para</em>facilitar a escolha do cinema mais conveniente para mim.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - O sistema deve acessar a localização atual do usuário (com permissão) para sugerir cinemas próximos.<br>
          - O sistema deve considerar o histórico de visitas do usuário para priorizar sugestões personalizadas.<br>
          - A lista de cinemas sugeridos deve aparecer de forma destacada na tela inicial ou na busca por sessões.<br>
          - O sistema deve permitir que o usuário veja o motivo da sugestão (ex: "Próximo a você" ou "Você já visitou").<br>
          - O usuário deve ter a opção de desativar as sugestões personalizadas nas configurações do aplicativo.<br>
          - As sugestões devem ser atualizadas sempre que o usuário abrir o aplicativo ou mudar de localização.
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
  <td>Rastreabilidade</td>
  <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq29" target="_blank">RQ29</a></td>
</tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor:  [Gabriel Castelo](https://github.com/GabrielCastelo-31).</p></font>

### US31 - Hub de Críticas de Filmes

<details>
  <summary><strong>Tabela 33 - História de Usuário Hub de Críticas de Filmes</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US31</td>
        <td>Hub de Críticas de Filmes</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário do aplicativo Cinemark, <em>desejo</em> acessar um hub centralizado com críticas de filmes, <em>para</em> avaliar opiniões antes de decidir qual filme assistir.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Seção "Críticas" acessível via menu principal<br>
          - Exibição de críticas profissionais e de usuários com classificação por estrelas<br>
          - Filtros por filme, data e relevância<br>
          - Publicação de críticas por usuários autenticados<br>
          - Funcionamento com conexão instável
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq60" target="_blank">RQ60</a></td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor:  [Artur de Camargos](https://github.com/ArturDCR).</p></font>

### US32 - Acesso Rápido aos Ingressos

<details>
  <summary><strong>Tabela 34 - História de Usuário Acesso Rápido aos Ingressos</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US32</td>
        <td>Acesso Rápido aos Ingressos</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário do aplicativo Cinemark, <em>desejo</em> encontrar meus ingressos de forma imediata, <em>para</em> acessá-los rapidamente ao chegar ao cinema.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Botão "Meus Ingressos" fixo na barra inferior<br>
          - Visível em todas as telas principais<br>
          - Exibição cronológica com destaque para data/sessão<br>
          - Alertas visuais para sessões próximas<br>
          - Acesso em até 2 toques
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq67" target="_blank">RQ67</a></td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor:  [Artur de Camargos](https://github.com/ArturDCR).</p></font>

### US33 - Logout da Conta

<details>
  <summary><strong>Tabela 35 - História de Usuário Logout da Conta</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US65</td>
        <td>Logout da Conta</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário do aplicativo Cinemark, <em>desejo</em> realizar logout de minha conta, <em>para</em> garantir minha segurança e privacidade ao compartilhar o dispositivo ou encerrar o uso.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Opção de logout visível na área do usuário<br>
          - Confirmação antes de efetivar o logout<br>
          - Redirecionamento para tela inicial após logout<br>
          - Encerramento de todas as sessões ativas<br>
          - Feedback visual claro de logout bem-sucedido<br>
          - Remoção segura de credenciais locais<br>
          - Compatibilidade com leitores de tela
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq65" target="_blank">RQ65</a></td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos](https://github.com/ArturDCR).</p></font>

### US34 - Detecção de Localização

<details>
  <summary><strong>Tabela 36 - História de Usuário Detecção de Localização</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US34</td>
        <td>Detecção de Localização</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário do aplicativo Cinemark, <em>desejo</em> que minha localização seja detectada automaticamente com opção de alteração manual, <em>para</em> encontrar cinemas próximos rapidamente.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Detecção automática de geolocalização ao abrir o app<br>
          - Exibição clara da localização detectada<br>
          - Botão "Alterar Local" visível<br>
          - Lista de cidades/estados para seleção manual<br>
          - Persistência da última localização escolhida
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq02" target="_blank">RQ02</a></td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor:  [Artur de Camargos](https://github.com/ArturDCR).</p></font>

### US35 - Autenticação por E-mail e Senha

<details>
  <summary><strong>Tabela 37 - História de Usuário Autenticação por E-mail e Senha</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US35</td>
        <td>Autenticação por E-mail e Senha</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário do aplicativo Cinemark, <em>desejo</em> autenticar-me com e-mail e senha, <em>para</em> acessar minha conta e benefícios pessoais.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Campos para e-mail e senha na tela de login<br>
          - Validação de formato de e-mail<br>
          - Recuperação de senha via e-mail<br>
          - Opção "Manter conectado"<br>
          - Mensagens claras de erro para credenciais inválidas<br>
          - Bloqueio temporário após múltiplas tentativas falhas
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq04" target="_blank">RQ04</a></td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor:  [Artur de Camargos](https://github.com/ArturDCR).</p></font>

### US36 - Mensagens de Erro e Confirmação

<details>
  <summary><strong>Tabela 38 - História de Usuário Mensagens de Erro e Confirmação</strong></summary>

  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Nome</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>US38</td>
        <td>Mensagens de Erro e Confirmação</td>
      </tr>
      <tr>
        <td>Descrição</td>
        <td><em>Eu, como</em> usuário, <em>desejo</em> receber mensagens de erro compreensíveis e confirmações explícitas após ações críticas, <em>para</em> entender falhas e evitar operações involuntárias.</td>
      </tr>
      <tr>
        <td>Critérios de Aceitação</td>
        <td>
          - Mensagens de erro em linguagem simples, com causa e solução<br>
          - Confirmações para ações irreversíveis (ex: compras/exclusões)<br>
          - Feedback visual imediato (toast/notificação) para todas as interações<br>
          - Formatação acessível (contraste WCAG AA + ícones intuitivos)<br>
          - Compatibilidade com leitores de tela (TalkBack/VoiceOver)<br>
          - Opção de "Desfazer" em confirmações quando aplicável
        </td>
      </tr>
      <tr>
        <td>Prioridade</td>
        <td>xxxx</td>
      </tr>
      <tr>
        <td>Rastreabilidade</td>
        <td><a href="https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#rq38" target="_blank">RQ38</a></td>
      </tr>
    </tbody>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos](https://github.com/ArturDCR).</p></font>

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  22/05/2025 |  Criação do Documento | [Davi Camilo](https://github.com/Davicamilo23)  | [Euller Júlio da Silva](https://github.com/Potatoyz908) |
| `1.1`  | 26/05/2025 | Adição do modelo da tabela de participantes | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.2`  | 31/05/2025 | Adição da introdução e modelo de tabela para histórias de usuário | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Euller Júlio da Silva](https://github.com/Potatoyz908) |
|`1.3`| 31/05/2025|Adição da Metodologia, US07, US08, US09, US10, US11 e US12|[Arthur Evangelista](https://github.com/arthurevg)|[Tiago Antunes Balieiro](https://github.com/tiagobalieiro)|
|`1.4`| 31/05/2025|Adição das histórias de usuário US13, US14, US15, US16, US17 e US18|[Euller Júlio da Silva](https://github.com/Potatoyz908)|[Tiago Antunes Balieiro](https://github.com/tiagobalieiro)|
| `1.5`  | 31/05/2025 | Adição das histórias de usuário US19, US20, US21, US22, US23 e US24 | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.6`  | 31/05/2025 | Adição das histórias de usuário US25, US26, US27, US28, US29 e US30 | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |  [Davi Camilo](https://github.com/Davicamilo23) |
| `1.7`  | 01/06/2025 | Adição das histórias de usuário US31, US32, US33, US34, US35 e US36 | [Artur de Camargos](https://github.com/ArturDCR) |  [Davi Camilo](https://github.com/Davicamilo23) |
| `1.8`  | 01/06/2025 | Adição das histórias de usuário US01, US02, US04, US05, US06 e US07 | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) |  [Euller Júlio da Silva](https://github.com/Potatoyz908) |
|`1.9`| 1/06/2025|Correção nas tabelas de histórias de usuário US13, US14, US15, US16, US17 e US18|[Euller Júlio da Silva](https://github.com/Potatoyz908)|[Tiago Antunes Balieiro](https://github.com/tiagobalieiro)|
|`1.10`| 1/06/2025| Correções gramaticais nas tabelas de histórias de usuário e adição na tabela de participantes |[Tiago Antunes Balieiro](https://github.com/tiagobalieiro)|[Arthur Evangelista](https://github.com/arthurevg)|