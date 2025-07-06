# Léxicos

## Introdução

O método de Léxicos é utilizado na engenharia de requisitos para descrever, em linguagem natural estruturada, os termos e conceitos relevantes do domínio do sistema. Cada entrada léxica é classificada como **verbo**, **objeto** ou **estado**, com seus respectivos sinônimos, noções e impactos, promovendo uma compreensão comum entre todos os stakeholders.

As definições para cada tipo de termo léxico são:

* **Verbo**: descreve ações, processos ou operações realizadas no sistema, indicando comportamentos ou funcionalidades executadas pelos atores ou pelo próprio sistema.

* **Objeto**: representa entidades ou elementos do domínio do sistema, como pessoas, equipamentos, documentos, ou quaisquer coisas tangíveis ou conceituais relevantes para a solução.

* **Estado**: define condições, situações ou propriedades específicas em que um objeto ou sistema pode estar, indicando diferentes fases, modos ou contextos de operação.


A estrutura de cada termo léxico é composta por:

* **Tipo**: (Verbo, Objeto ou Estado)
* **Sinônimos**: outras formas de se referir ao termo
* **Noção**: definição ou contexto do termo no sistema
* **Impacto**: quais funcionalidades ou elementos são afetados por esse termo
* **Rastreabilidade**: requisito(s) elicitado(s) ao qual o termo está relacionado

## Integrantes do grupo envolvidos

**Tabela 24**

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
						<td>Elaborou os Léxicos 11, 12, 13 e 14 referentes aos requisitos RQ60 e RQ67</td>	
					</tr>
					<tr>
						<td><a  href="https://github.com/arthurevg">Arthur Evangelista</a></td>
						<td>Elaborou os Léxicos 3, 4, 5, 6 e 23 referentes aos requisitos RQ23 e RQ24</td>	
					</tr>
					<tr>
						<td><a  href="https://github.com/Davicamilo23">Davi Camilo</a></td>
						<td>Elaborou os Léxicos 7, 8, 9 e 10 referentes aos requisitos RQ32 e RQ58</td>	
					</tr>
					<tr>
						<td><a  href="https://github.com/Potatoyz908">Euller Júlio</a></td>
						<td>Elaborou a Introdução, metodologia e os Léxicos 1 e 2 referentes aos requisitos RQ33 e RQ59</td>	
					</tr>
					<tr>
						<td><a  href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a></td>
						<td>Elaborou os Léxicos 15, 16, 17, 18 e 19 referentes aos requisitos RQ29 e RQ30</td>	
					</tr>
					<tr>
						<td><a  href="https://github.com/tiagobalieiro">Tiago Antunes Balieiro</a></td>
						<td>Elaborou os Léxicos 21 e 22 referentes aos requisitos RQ26 e RQ39</td>	
					</tr>
			</tbody>
		</table>
	</div>  
</div>

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro).</p></font>

---

## Léxicos Criados

### 1. **Reservar Sala**

* **Tipo**: Verbo
* **Sinônimos**: Agendar sala, Solicitar sala, Alugar sala
* **Noção**: Ação realizada por um usuário para garantir o uso exclusivo de uma sala de cinema para fins particulares, como eventos, festas ou sessões privadas.
* **Impacto**: Ao reservar uma sala, o sistema deve verificar disponibilidade, coletar informações do evento, registrar a reserva e gerar confirmação. Afeta diretamente o módulo de reservas, a agenda de salas e o fluxo de pagamento.
* **Rastreabilidade**: [RQ59](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Fornecer reservas de salas para eventos.

<p align="center"><br>
Autor: <a href="https://github.com/Potatoyz908">Euller Júlio</a>, 2025.</p>

### 2. **Preferência de Idioma**

* **Tipo**: Objeto
* **Sinônimos**: Idioma, Configuração de idioma, Idioma da interface
* **Noção**: Representa a configuração escolhida pelo usuário para a linguagem da interface do aplicativo. Pode incluir opções como português, inglês, espanhol, etc.
* **Impacto**: Ao modificar essa configuração, a interface deve ser imediatamente ajustada para o idioma escolhido. Afeta a experiência do usuário e a apresentação de todos os textos exibidos no sistema.
* **Rastreabilidade**: [RQ33](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Permitir alteração de preferências de idioma.


<p align="center"><br>
Autor: <a href="https://github.com/Potatoyz908">Euller Júlio</a>, 2025.</p>

### 3. **Filtrar Filmes**

* **Tipo**: Verbo
* **Sinônimos**: Selecionar por categoria, Classificar filmes, Aplicar filtro de gênero
* **Noção**: Ação realizada pelo usuário para limitar a exibição de filmes com base em categorias ou gêneros disponíveis, como ação, comédia, drama etc.
* **Impacto**: Ao realizar o filtro, o sistema deve consultar os dados cadastrados de filmes, aplicar os critérios definidos e exibir apenas os resultados compatíveis. Isso influencia a navegação e a personalização da experiência do usuário.
* **Rastreabilidade**: [RQ23](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Filtrar filmes por categoria e exibir avaliações de público e plataformas externas.

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

### 4. **Avaliações de Filmes**

* **Tipo**: Objeto
* **Sinônimos**: Opiniões, Notas, Reviews
* **Noção**: Representa as notas e comentários fornecidos tanto por usuários da plataforma quanto por sistemas externos de avaliação (como IMDb, Rotten Tomatoes etc.).
* **Impacto**: Essas avaliações são exibidas junto aos detalhes dos filmes, impactando a decisão do usuário sobre assistir ou não. O sistema deve buscar e apresentar essas informações de forma clara e atualizada.
* **Rastreabilidade**: [RQ23](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Filtrar filmes por categoria e exibir avaliações de público e plataformas externas.

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

### 5. **Assistir Trailer**

* **Tipo**: Verbo
* **Sinônimos**: Ver prévia, Reproduzir trailer, Ver vídeo promocional
* **Noção**: Ação em que o usuário inicia a reprodução de um vídeo promocional (trailer) de um filme dentro do próprio aplicativo.
* **Impacto**: Ao assistir ao trailer, o sistema deve reproduzir o conteúdo audiovisual sem necessidade de redirecionamento externo. Isso melhora a experiência do usuário e pode influenciar o interesse em assistir ao filme.
* **Rastreabilidade**: [RQ24](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir trailers dentro do app.

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

### 6. **Trailer**

* **Tipo**: Objeto
* **Sinônimos**: Prévia, Vídeo de divulgação, Teaser
* **Noção**: Conteúdo audiovisual curto, destinado à divulgação de um filme, contendo cenas selecionadas para atrair o público.
* **Impacto**: Os trailers devem estar associados aos filmes e disponíveis para reprodução dentro do app. Devem estar integrados a um player funcional e acessível.
* **Rastreabilidade**: [RQ24](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir trailers dentro do app.

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

### 7. **Exibir Recomendações de Filmes**

- **Tipo**: Verbo
- **Sinônimos**: Sugerir filmes, Recomendação personalizada, Indicar títulos
- **Noção**: Ação em que o sistema apresenta sugestões de filmes ao usuário com base em seu histórico de visualização, avaliações e preferências cadastradas no aplicativo.
- **Impacto**: Melhora a personalização da experiência do usuário, aumentando o engajamento e a probabilidade de escolha de um filme por parte do usuário. Exige análise de dados comportamentais e preferência do usuário para entregar recomendações relevantes.
- **Rastreabilidade**: [RQ32A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir recomendações de filmes baseadas em histórico e [RQ32B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir recomendações de filmes baseadas em preferências. 

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Davi Camilo</a>, 2025.</p>

### 8. **Recomendações de Filmes**

- **Tipo**: Objeto
- **Sinônimos**: Sugestões, Indicações, Lista personalizada
- **Noção**: Conjunto de filmes apresentados ao usuário com base em dados como seu histórico, preferências e comportamento de uso.
- **Impacto**: Influencia diretamente a decisão do usuário, aumentando as chances do mesmo assistir a um filme recomendado. Deve ser exibido em local de fácil acesso, com informações claras e atrativas.
- **Rastreabilidade**: [RQ32](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir recomendações de filmes baseadas em histórico e preferências.

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Davi Camilo</a>, 2025.</p>

### 9. **Comparar Preços de Ingressos**

- **Tipo**: Verbo
- **Sinônimos**: Ver preços, Analisar valores, Checar tarifas
- **Noção**: Ação em que o usuário solicita a exibição de preços de ingressos e combos para um mesmo filme em diferentes cinemas disponíveis.
- **Impacto**: Permite ao usuário tomar decisões mais econômicas e conscientes. O sistema deve coletar e apresentar os preços de forma clara, organizada e atualizada, respeitando as regras de cada cinema Cinemark.
- **Rastreabilidade**: [RQ58](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Fornecer comparação de preços entre cinemas.

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Davi Camilo</a>, 2025.</p>

### 10. **Tabela Comparativa de Preços**

- **Tipo**: Objeto
- **Sinônimos**: Comparação de preços, Série de valores, Lista de tarifas
- **Noção**: Tabela exibida ao usuário com os preços de ingressos e combos em diferentes cinemas para o mesmo filme.
- **Impacto**: Facilita a comparação direta, promovendo escolhas mais vantajosas para o usuário. Deve incluir o local dos cinemas, horários e valores totais, respeitando promoções e taxas aplicáveis.
- **Rastreabilidade**: [RQ58](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Fornecer comparação de preços entre cinemas.

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Davi Camilo</a>, 2025.</p>

### 11. **Fornecimento de um Hub para crítica de filmes**

- **Tipo**: Objeto
- **Sinônimos**: Central de Críticas, Seção de Avaliações, Espaço de Opiniões
- **Noção**: Área centralizada no aplicativo Cinemark onde usuários podem ler, escrever e interagir com críticas e avaliações de filmes em cartaz ou futuros lançamentos.
- **Impacto**: Permite que usuários compartilhem opiniões, influenciem decisões de outros espectadores e engajem com a comunidade.
- **Rastreabilidade**: [RQ60](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Fornecer um Hub para crítica de filmes.

<p align="center"><br>
Autor: <a href="https://github.com/ArturDCR">Artur de Camargos</a>, 2025.</p>

### 12. **Fornecer um Hub para crítica de filmes**

- **Tipo**: Verbo
- **Sinônimos**: Disponibilizar espaço para críticas, Oferecer seção de avaliações
- **Noção**: Ação de implementar e manter uma área dedicada no aplicativo para que críticas de filmes sejam centralizadas e acessíveis.
- **Impacto**: Melhora a experiência do usuário ao agregar informações relevantes e promover interação social.
- **Rastreabilidade**: [RQ60](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Fornecer um Hub para crítica de filmes.

<p align="center"><br>
Autor: <a href="https://github.com/ArturDCR">Artur de Camargos</a>, 2025.</p>

### 13. **Acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial**

- **Tipo**: Objeto
- **Sinônimos**: Compra de ingressos, Seção de ingressos, Botão de ingressos
- **Noção**: Funcionalidade ou elemento de interface que permite ao usuário visualizar, selecionar e comprar ingressos para sessões de cinema de forma rápida e intuitiva.
- **Impacto**: Reduz atritos na jornada do usuário, aumentando conversões de vendas e satisfação.
- **Rastreabilidade**: [RQ67](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial.

<p align="center"><br>
Autor: <a href="https://github.com/ArturDCR">Artur de Camargos</a>, 2025.</p>

### 14. **Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial**

- **Tipo**: Verbo
- **Sinônimos**: Simplificar compra de ingressos, Otimizar visibilidade de ingressos
- **Noção**: Ação de garantir que a interface do aplicativo priorize e torne óbvio o caminho para comprar ingressos (ex.: botão fixo, atalho no menu).
- **Impacto**: Acelera o processo de compra e reduz a taxa de abandono de carrinho.
- **Rastreabilidade**: [RQ67](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial.

<p align="center"><br>
Autor: <a href="https://github.com/ArturDCR">Artur de Camargos</a>, 2025.</p>

### 15. **Histórico de visitas**

- **Tipo:** Objeto
- **Sinônimos:** histórico de sessões, cinemas visitados anteriormente
- **Noção:** Conjunto de registros armazenados no perfil do usuário, indicando cinemas visitados e frequência de visitas.
- **Impacto:** Usado pelo sistema como critério de personalização para sugestões de cinema.
- **Rastreabilidade:** [RQ29](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) - Sugerir cinemas com base no histórico de visitas e [RQ29B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) - Sugerir cinemas com base na localização atual.

<p align="center"><br>
Autor: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a>, 2025.</p>

### 16: **Localização atual**

- **Tipo:** Objeto
- **Sinônimos:** posição geográfica, localização do usuário
- **Noção:** Ponto geográfico detectado pelo sistema, geralmente via GPS, utilizado para identificar cinemas próximos ao usuário.
- **Impacto:** Requisito essencial para a filtragem geográfica nas sugestões de cinema; afeta permissões e uso de recursos do dispositivo.
- **Rastreabilidade:** [RQ29A](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) - Sugerir cinemas com base no histórico de visitas e [RQ29B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) - Sugerir cinemas com base na localização atual.

<p align="center"><br>
Autor: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a>, 2025.</p>

### 17: **Salvar como favorito**

- **Tipo:** Verbo
- **Sinônimos:** adicionar aos favoritos, marcar como preferido
- **Noção:** Ação que permite ao usuário registrar um cinema em sua lista pessoal de favoritos para facilitar o acesso futuro.
- **Impacto:** Afeta o banco de dados do usuário, a interface de exibição de favoritos e as funcionalidades de busca personalizada.
- **Rastreabilidade:** [RQ30](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Permitir que o usuário salve cinemas como favoritos

<p align="center"><br>
Autor: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a>, 2025.</p>

### 18: **Favorito**

- **Tipo:** Estado
- **Sinônimos:** preferido, marcado
- **Noção:** Estado atribuído a um cinema pelo usuário indicando preferência e desejo de acesso facilitado.
- **Impacto:** Afeta a forma como os cinemas são priorizados na navegação do usuário e em futuras interações com o sistema.
- **Rastreabilidade:** [RQ30](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Permitir que o usuário salve cinemas como favoritos

<p align="center"><br>
Autor: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a>, 2025.</p>

### 19: **Lista de favoritos**

- **Tipo:** Objeto
- **Sinônimos:** favoritos, cinemas salvos
- **Noção:** Conjunto de cinemas marcados como favoritos pelo usuário, armazenado em seu perfil pessoal.
- **Impacto:** Funcionalidade essencial para navegação personalizada e acesso rápido a cinemas preferidos.
- **Rastreabilidade:** [RQ30](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Permitir que o usuário salve cinemas como favoritos

<p align="center"><br>
Autor: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a>, 2025.</p>

### 20: **Sugerir**

- **Tipo:** Verbo
- **Sinônimos:** recomendar, indicar, apresentar opções
- **Noção:** Ação realizada pelo sistema para apresentar ao usuário uma lista de cinemas com base em critérios como localização atual e histórico de visitas anteriores.
- **Impacto:** Afeta o módulo de recomendação, a interface de exibição de sugestões e o uso de localização do dispositivo.
- **Rastreabilidade:** [RQ29](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) - Sugerir cinemas com base no histórico de visitas e [RQ29B](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) - Sugerir cinemas com base na localização atual.

<p align="center"><br>
Autor: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a>, 2025.</p>

### 21. **Salvar ingresso na carteira digital**

- **Tipo**: Verbo
- **Sinônimos**: Adicionar à carteira digital, Armazenar ingresso, Salvar no Google Wallet / Apple Wallet
- **Noção**: Ação de permitir que o usuário adicione o ingresso de cinema à sua carteira digital do dispositivo (como Google Wallet ou Apple Wallet), facilitando o acesso ao ingresso durante a entrada no cinema.
- **Impacto**: Facilita o armazenamento e a acessibilidade do ingresso, proporcionando uma experiência de usuário mais prática. Requer integração com serviços de carteira digital no sistema..
- **Rastreabilidade**: [RQ26](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir recomendações de filmes baseadas em histórico e preferências.

<p align="center"><br>
Autor: <a href="https://github.com/tiagobalieiro">Tiago Antunes Balieiro</a>, 2025.</p>

### 22. **Avaliar filme**

- **Tipo**: Verbo
- **Sinônimos**: Classificar filme, Atribuir nota, Avaliar filme com estrelas
- **Noção**: Ação de atribuir uma nota de 1 a 5 estrelas a um filme após assisti-lo, permitindo que os usuários compartilhem sua opinião sobre o filme com outros usuários.
- **Impacto**: Afeta a visualização das recomendações e as estatísticas de avaliação, promovendo a melhoria do sistema de sugestões de filmes baseados em avaliações de usuários.
- **Rastreabilidade**: [RQ39](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir recomendações de filmes baseadas em histórico e preferências.

<p align="center"><br>
Autor: <a href="https://github.com/tiagobalieiro">Tiago Antunes Balieiro</a>, 2025.</p>

### 23. **Usuário**

* **Tipo**: Sujeito  
* **Sinônimos**: Pessoa usuária, cliente, utilizador  
* **Noção**: Indivíduo que acessa e interage com o sistema para utilizar suas funcionalidades, como realizar login, efetuar reservas, consultar sessões ou alterar configurações.  
* **Impacto**: O usuário é o principal ator do sistema. Suas interações disparam fluxos de uso essenciais, como autenticação e execução de funcionalidades críticas. A experiência do usuário deve ser priorizada no design e implementação das interfaces.  
* **Rastreabilidade**: O termo está presente nos seguintes requisitos: [RQ04](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1), [RQ12](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1), [RQ28](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1), [RQ30](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1), [RQ37](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1), [RQ38](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1), [RQ39](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1), [RQ48](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1), [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1), [RQ62](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1), [RQ64](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) e [RQ65](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1)

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

---

## Referências Bibliográficas

> SALES, André Barros de. *Requisitos – Aula 10: Léxicos*. Universidade de Brasília, 2025. Disponível em: `<https://aprender3.unb.br>` (material interno da disciplina). Acesso em: 18 maio 2025.

> LEITE, J. C. S. do Prado; FRAGOSO, Gerson H. *Manual de Engenharia de Requisitos – Vol. 1: Fundamentos*. 2. ed. Rio de Janeiro: LTC, 2014.

> PAULA FILHO, Wilson de Pádua. *Engenharia de Software: Fundamentos, Métodos e Padrões*. 2. ed. Rio de Janeiro: LTC, 2009.

---

## Histórico de Versão

| Versão | Data       | Descrição                                     | Autor(es)                                      | Revisor(es)                                       |
| ------ | ---------- | --------------------------------------------- | ---------------------------------------------- | ------------------------------------------------- |
| `1.0`  | 13/05/2025 | Criação do Documento                          | [Davi Camilo](https://github.com/Davicamilo23) | Todos                                             |
| `1.1`  | 18/05/2025 | Adição da introdução, metodologia e referências | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.2`  | 18/05/2025 | Adição dos léxicos dos requisitos RQ59 e RQ33 | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.3`  | 18/05/2025 | Adição dos léxicos 3, 4, 5 e 6 (RQ23 e RQ24) | [Arthur Evangelista](https://github.com/arthurevg) | [Euller Júlio](https://github.com/Potatoyz908) |
| `1.4`  | 18/05/2025 | Adição dos léxicos 7 e 8 (referentes ao RQ32), e 9 e 10 (referentes ao RQ58) | [Davi Camilo](https://github.com/Davicamilo23) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.5`  | 18/05/2025 | Adição dos léxicos 11 e 12 (referentes ao RQ60), e 13 e 14 (referentes ao RQ67) | [Artur de Camargos](https://github.com/ArturDCR) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.6`  | 18/05/2025 | Correção dos léxicos dos requisitos RQ59 e RQ33 | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.7`  | 18/05/2025 | Adição dos léxicos 15, 16, 17, 18, 19 e 20 (referentes ao RQ29 e RQ30) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Euller Júlio](https://github.com/Potatoyz908) |
| `1.8`  | 18/05/2025 | Adição dos léxicos 21 (referente ao RQ26), e 22 (referentes ao RQ39) | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos](https://github.com/ArturDCR)  |
| `1.9`  | 19/05/2025 | Adição do léxico 23 | [Arthur Evangelista](https://github.com/arthurevg) | [Euller Júlio](https://github.com/Potatoyz908) |
| `1.10`  | 22/05/2025 | Ajuste no texto de introdução para torná-lo mais claro e objetivo | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.11`  | 26/05/2025 | Adição da tabela de participantes | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.12`  | 06/07/2025 | Ajuste no RQ29, adicionando suas novas versões RQ29A e RQ29B | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.13`  | 06/07/2025 | Ajuste no RQ32, adicionando suas novas versões RQ32A e RQ32B | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |