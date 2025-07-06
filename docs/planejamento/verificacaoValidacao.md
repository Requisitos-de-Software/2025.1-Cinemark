# Análise de Requisitos: Verificação e Validação

## Introdução

Nesta fase, o grupo realizou a verificação e validação dos requisitos por meio de um processo estruturado, baseado no método de inspeção de Fagan, o qual contempla seis etapas principais: Planejamento, Visão Geral, Preparação, Inspeção, Retrabalho e Acompanhamento. Esse modelo orientou a organização das atividades, garantindo um controle de qualidade mais rigoroso sobre os artefatos gerados durante todo o desenvolvimento do projeto.

---

## Metodologia

### Planejamento e Visão Geral

Inicialmente, verificamos as atividades que exigiriam a participação de todos os membros do grupo. Baseado nos requisitos do professor, estabelecemos que cada integrante deveria, caso ainda não tenha feito, contribuir na produção de um Rich Picture (de um aplicativo não selecionado), participar de no mínimo de uma técnica de elicitação, elaborar de cenários e casos de uso de 2 requisitos não implementados, elaborar no mínimo uma especificação suplementar e um NFR Framework, produzir histórias de usuário de 6 requisitos funcionais (2 não implementados e 4 implementados), elaborar elos de 6 requisitos funcionais e na prototipação com, no mínimo, dois requisitos funcionais não implementados.

### Preparação

A partir disso, o grupo reuniu todos os artefatos gerados até aquele momento e os classificou com uma pontuação de 1 a 5, levando em consideração a complexidade e o esforço necessário para revisão e validação, excluindo os Requisitos Elicitados, pois foi decidido em todo o grupo corrigi-los juntos.

### Inspeção

Com base nessa classificação, os artefatos foram distribuídos entre os membros do grupo de maneira equilibrada. A seguir está a tabela 1 com a alocação dos artefatos e suas respectivas pontuações.

<font size="3"><p style="text-align: center">Tabela 1: Divisão dos artefatos</p></font>

| Integrante | Artefatos atribuídos |
|---|---|
|[Arthur Evangelista de Oliveira](https://github.com/arthurevg)| Técnicas de Elicitação ([Análise de Interface de Usuário](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/), [Introspecção](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/), [Questionário](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/questionario/) e [Storytelling](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/storytelling/)) [4] e [Casos de Uso](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/casosDeUso/) [2] |
|[Artur de Camargos Rodrigues](https://github.com/ArturDCR)| [Especificação Suplementar](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/especifica%C3%A7%C3%A3oSuplementar/) [2] e [Backlog](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/backlog/) [3] |
|[Davi Camilo Menezes](https://github.com/Davicamilo23)| Planejamento ([Aplicativo Escolhido](https://requisitos-de-software.github.io/2025.1-Cinemark/planejamento/aplicativo/), [Cronograma](https://requisitos-de-software.github.io/2025.1-Cinemark/planejamento/cronograma/), [Ferramentas](https://requisitos-de-software.github.io/2025.1-Cinemark/planejamento/ferramentas/), [Heatmap](https://requisitos-de-software.github.io/2025.1-Cinemark/planejamento/heatmap/) e [Metodologia](https://requisitos-de-software.github.io/2025.1-Cinemark/planejamento/metodologia/)) [1] e [Backward-From](https://requisitos-de-software.github.io/2025.1-Cinemark/rastreabilidade/backward-from/), [Forward-From](https://requisitos-de-software.github.io/2025.1-Cinemark/rastreabilidade/forward-from/) e [Matriz Geral de Rastreabilidade](https://requisitos-de-software.github.io/2025.1-Cinemark/rastreabilidade/matriz-geral/) [5] |
|[Euller Júlio da Silva](https://github.com/Potatoyz908)| [Perfil de Usuário](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/perfilusuario/) e [Personas](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/personas/) [2] e [NFR Framework](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/nfrFramework/) [3] |
|[Gabriel Henrique Castelo Costa](https://github.com/GabrielCastelo-31)| [Léxicos](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/lexicos/) [2] e [Pós-Rastreabilidade](https://requisitos-de-software.github.io/2025.1-Cinemark/rastreabilidade/pos-rastreabilidade/) [4] |
|[Pedro Everton de Paula](https://github.com/pedroeverton217)| [Rich Picture](https://requisitos-de-software.github.io/2025.1-Cinemark/planejamento/richpicture/) [1], [Histórias de Usuário](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/historias/) [3] e Validação ([Prototipação](https://requisitos-de-software.github.io/2025.1-Cinemark/validacao/prototipacao/) e [Comprovação Informal](https://requisitos-de-software.github.io/2025.1-Cinemark/validacao/comprovacaoInformal/)) [1] |
|[Tiago Antunes Balieiro](https://github.com/tiagobalieiro)| Técnicas de Priorização ([100$](https://requisitos-de-software.github.io/2025.1-Cinemark/prioriza%C3%A7%C3%A3o/100%24/), [Kano Model](https://requisitos-de-software.github.io/2025.1-Cinemark/prioriza%C3%A7%C3%A3o/kanomodel/), [MoSCoW](https://requisitos-de-software.github.io/2025.1-Cinemark/prioriza%C3%A7%C3%A3o/moscow/) e [Three Level Scale](https://requisitos-de-software.github.io/2025.1-Cinemark/prioriza%C3%A7%C3%A3o/threelevelscale/)) [4] e [Cenários](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/cenarios/) [2] |

<font size="3"><p style="text-align: center">Fonte: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

### Retrabalho e Acompanhamento

Durante o processo, foram identificados pontos críticos para a entrega final, que envolvem ajustes e verificações essenciais, sendo os principais:

- Correção dos requisitos elicitados incorretamente;

- Correção e implementação de hiperlinks de rastreabilidade faltantes;

- Correções e adições de itens e fotos nas referências nas listas de verificação do projeto;

A fins de documentação, a seguir, segue uma tabela com os artefatos (no formato de PDF) antes das alterações, juntamente com as listas de verificação e inspeção (versão 1.0), de maneira a mostrar o desenvolvimento completo dos artefatos:

<font size="3"><p style="text-align: center">Tabela 2: Versão 1.0 dos artefatos</p></font>

| Tipo de artefato | Artefato (versão 1.0) | Lista de verificação (versão 1.0) | Inspeção (versão 1.0) |
| --- | --- | --- | --- |
| Pré-rastreabilidade | [Rich Picture](../PDFpaginas/Rich%20Picture%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2001%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%201%20-%20Cinemark.pdf) |
| Elicitação (Usuário) | [Perfil de Usuário](../PDFpaginas/Perfil%20de%20Usu%C3%A1rio%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Elicitação (Usuário) | [Personas](../PDFpaginas/Personas%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Elicitação (Técnica de Elicitação) | [Análise de Interface de Usuário](../PDFpaginas/An%C3%A1lise%20de%20Interface%20de%20Usu%C3%A1rio%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Elicitação (Técnica de Elicitação) | [Introspecção](../PDFpaginas/Introspec%C3%A7%C3%A3o%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Elicitação (Técnica de Elicitação) | [Questionário](../PDFpaginas/Question%C3%A1rio%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Elicitação (Técnica de Elicitação) | [Storytelling](../PDFpaginas/Storytelling%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Elicitação | [Requisitos Elicitados](../PDFpaginas/Requisitos%20Elicitados%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Elicitação (Técnica de Priorização) | [100$](../PDFpaginas/100$%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Elicitação (Técnica de Priorização) | [Kano Model](../PDFpaginas/Kano%20Model%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Elicitação (Técnica de Priorização) | [MoSCoW](../PDFpaginas/MoSCoW%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Elicitação (Técnica de Priorização) | [Three Level Scale](../PDFpaginas/Three%20Level%20Scale%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2002%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%202%20-%20Cinemark.pdf) |
| Modelagem | [Casos de Uso](../PDFpaginas/Casos%20de%20Uso%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2003%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%203%20-%20Cinemark.pdf) |
| Modelagem | [Especificação Suplementar](../PDFpaginas/Especifica%C3%A7%C3%A3o%20Suplementar%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2003%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%203%20-%20Cinemark.pdf) |
| Modelagem | [Cenários](../PDFpaginas/Cen%C3%A1rios%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2003%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%203%20-%20Cinemark.pdf) |
| Modelagem | [Léxicos](../PDFpaginas/L%C3%A9xicos%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2003%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%203%20-%20Cinemark.pdf) |
| Modelagem Ágil | [NFR Framework](../PDFpaginas/NFR%20Framework%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2004%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%204%20-%20Cinemark.pdf) |
| Modelagem Ágil | [Backlog](../PDFpaginas/Backlog%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2004%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%204%20-%20Cinemark.pdf) |
| Modelagem Ágil | [Histórias de Usuário](../PDFpaginas/Hist%C3%B3rias%20de%20Usu%C3%A1rio%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2004%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%204%20-%20Cinemark.pdf) |
| Rastreabilidade | [Backward-From](../PDFpaginas/Backward-From%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2006%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%206%20-%20Cinemark.pdf) |
| Rastreabilidade | [Forward-From](../PDFpaginas/Forward-From%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2006%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%206%20-%20Cinemark.pdf) |
| Rastreabilidade | [Matriz Geral de Rastreabilidade](../PDFpaginas/Matriz%20Geral%20de%20Rastreabilidade%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2006%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%206%20-%20Cinemark.pdf) |
| Rastreabilidade | [Pós-Rastreabilidade](../PDFpaginas/P%C3%B3s-Rastreabilidade%20-%20Cinemark.pdf) | [Lista de verificação 1.0](../PDFpaginas/Entrega%2006%20-%20Cinemark.pdf) | [Inspeção 1.0](../PDFpaginas/Entrega%206%20-%20Cinemark.pdf) |
| Validação | [Prototipação](../PDFpaginas/Prototipa%C3%A7%C3%A3o%20-%20Cinemark.pdf) | - | - |
| Validação | [Comprovação Informal](../PDFpaginas/Comprova%C3%A7%C3%A3o%20Informal%20-%20Cinemark.pdf) | - | - |

<font size="3"><p style="text-align: center">Fonte: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

Com isso, cada membro do grupo deverá revisar os artefatos sob sua responsabilidade, garantindo clareza, consistência e rastreabilidade dos requisitos. A equipe consolidará os documentos, revisará os IDs, aplicará correções e garantirá que todos os critérios definidos nas etapas de Fagan sejam atendidos até a conclusão de todas as atividades (07/07/2025).

---

## Conclusão

A verificação e validação dos requisitos é uma etapa fundamental durante o ciclo de vida do software para assegurar a conformidade com os requisitos. A adoção do modelo de inspeção de Fagan ofereceu uma estrutura clara e eficaz para o processo, possibilitando a identificação e correção de problemas antes da implementação, sendo essencial a participação de todo o grupo para que a entrega final contemple todas os itens necessários em sua maior qualidade.

---

## Referências Bibliográficas

> - TIGO SOLUTIONS. Differences between software walkthrough, review, and inspection. Disponível em: https://en.tigosolutions.com/differences-between-software-walkthrough-review-and-inspection-5706. Acesso em: 2 jul. 2025.

---

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  01/07/2025 |  Criação do Documento | [Davi Camilo](https://github.com/Davicamilo23)  | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.1`  |  02/07/2025 |  Adição da Introdução, Metodologia, Conclusão e Referências Bibliográficas | [Davi Camilo](https://github.com/Davicamilo23)  | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.2`  | 06/07/2025  |  Adição de informações (verificação e inspeção) | [Davi Camilo](https://github.com/Davicamilo23) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
