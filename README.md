#ConnectServer

## 1. Identificação

* **Identidade Visual:** ![LOGO CONNECT SERVER](https://github.com/LuisFernando1910/TCC_INFO4_REGRESSIVA/blob/main/Connect.png)
* **Redes Sociais:** https://chat.whatsapp.com/J1cMsovMOAN3G7mV3ULvx6
* **Equipe:**
  * Luis Fernando - Desenvolvedor Sistema back-end
  * Nathalia Eduarda de Liz - Desenvolvedor Sistema Front-end
  * Luis Fernando - Desenvolvedor Sistema back-end - BD
* **Data de Criação:** 20//07/2024

## 2. Introdução
Atualmente, o serviço de múltiplos acessos na área da informática se mostra como um grande contratempo se não for feito de forma adequada, dificultando que vários usuários acessem recursos computacionais simultaneamente. Isso pode causar problemas como o consumo excessivo de memória, armazenamento e largura de banda de rede. Esses desafios são exacerbados em sistemas distribuídos, que são conjuntos de computadores independentes que funcionam como um único sistema para os usuários finais, e acaba se tornando um ponto crítico quando se trata da sincronização de relógios, pois várias máquinas devem estar coordenadas simultaneamente, do contrário, ocorrerão conflitos e contratempos na execução de eventos estritamente ordenados. Esse tipo de dificuldade é especialmente relevante quando o sincronismo de eventos é essencial para a consistência da regra de negócio, que não deve se sobrecarregar, e em paralelo, deve executar os comandos solicitados ordenadamente, sejam eles vindos da mesma fonte ou não. O uso de sistema de múltiplos usuários síncronos se aplica a várias áreas, como a tecnologia, vendas, finanças e até mesmo o entretenimento e pode ser resolvido de algumas maneiras, dentre elas um sistema de contagem regressiva, muito usado atualmente em empresas de mídia de difusão, por exemplo. 

Para uma empresa sincronizar todos os seus relógios hoje em dia, existem algumas técnicas e tecnologias que podem ser empregadas para garantir que todos os dispositivos estejam ajustados corretamente. Dentre elas, se destaca o uso de NTP (Network Time Protocol), que é um protocolo de rede utilizado para sincronizar relógios de computadores conectados via redes de comunicação. O NTP utiliza uma hierarquia de níveis chamada de "estratos" (stratum) para organizar os servidores provedores de tempo. Existem algumas variantes de stratum, os stratum 0 são dispositivos de referência de tempo, como relógios atômicos, receptores de GPS, satélites ou outras fontes de tempo altamente precisas. O stratum 1 são servidores diretamente conectados a dispositivos stratum 0 e fornecem o tempo aos servidores de stratum 2, além disso, são de referência na rede. Os stratum 2 fornecem o tempo para os servidores de stratum 3, e assim até os stratum 15, com cada nível subsequente introduzindo um pequeno atraso adicional.

A partir da conexão entre servidores NTP internos, ou externos, corretamente configurados com fontes de tempo confiáveis, os dispositivos conectados na  rede podem sincronizar seus horários sempre que necessário. No entanto, em alguns contextos, a configuração e a obtenção desses dados ainda é realizada de maneira manual. Esse fato pode ser observado em uma rede de difusão televisiva, necessidade na qual é baseado o projeto. Ela possui um sistema de sincronização de relógio no qual o horário é obtido a partir de uma fonte de tempo confiável, para que  então o responsável técnico na Rede de Comunicação Parceira, com  sede em  Curitiba, recolha-o  e o configure  manualmente na máquina principal. Esse processo se repete em todas as praças (compreendidas como as regiões do Paraná e as cidades que disponibilizam telejornais diariamente), fazendo com que estas não sejam conectadas e sincronizadas umas às outras. Esse processo, apesar de eficaz em execução, possui algumas  desvantagens, tais como a sobrecarga dos profissionais que precisam dedicar seu tempo a um processo manual, vulnerável a erros humanos. Portanto, este projeto visa desenvolver um sistema de múltiplos acessos que favorece a conexão entre as praças e sincroniza os dados inseridos, substituindo o atual processo manual, burocrático e suscetível a erros.      

* **Objetivo:** Desenvolver um site intuitivo e funcional que auxilie na gestão de tempo da produção e dos apresentadores de uma Rede de Comunicação Parceira, por meio da utilização de cronômetros regressivos. O projeto também visa sincronizar o serviço de múltiplos acessos através do portal web, permitindo que diversas entidades acessem e modifiquem simultaneamente seus conteúdos, auxiliando na resolução de problemas de sobrecarga do sistema atual e concorrência de acessos.
* **Escopo:**
  * **MVP:** [Descreva o produto mínimo viável]
  * **Entregas:** [Liste as principais entregas do projeto]
  * **Objetivos Quantificáveis:** [Defina métricas de sucesso]
  * **Critérios de Aceitação:** [Defina os critérios para considerar o projeto concluído]
  * **Prototipação:** [Link para o protótipo no Quant-UX]

## 3. Matriz de Riscos

| Risco | Impacto | Probabilidade | Mitigação |
|---|---|---|---|
| [Risco 1] | [Alto/Médio/Baixo] | [Alto/Médio/Baixo] | [Ações para mitigar] |
| ... | ... | ... | ... |

## 4. Organização do Projeto

* **Cronograma:** [Inserir um diagrama de Gantt ou um cronograma textual]
* **Equipe:** [Descreva a organização da equipe e as responsabilidades de cada membro]
* **Trello/Jira:** [Link para o board do projeto]

## 5. Conclusão

* **Recursos:** [Liste as tecnologias, ferramentas e linguagens utilizadas]
* **Resultados Esperados:** [Descreva os resultados que se espera alcançar com o projeto]
* **Monitoramento:** [Explique como o projeto será monitorado e acompanhado]

## Documentação

* **Requisitos:** [Link para o documento de requisitos]
* **Casos de Uso:** [Link para o documento de casos de uso]
* **Diagramas:**
  * **Atividades:** [Link]
  * **Sequência:** [Link]
  * **Classes:** [Link]
  * **Entidade-Relacionamento:** [Link]

## Como Contribuir

[Descreva como outras pessoas podem contribuir com o projeto]

**Observações:**

* **Formatação:** Utilize Markdown para formatar o texto. Existem diversos editores que suportam Markdown, como o próprio GitHub, Visual Studio Code e Atom.
* **Imagens:** Para adicionar imagens, utilize o seguinte formato: `![Descrição da imagem](caminho/para/a/imagem.png)`
* **Links:** Para adicionar links, utilize o seguinte formato: `[Texto do link](link)`
* **Tabelas:** Para criar tabelas, utilize pipes (|) para delimitar as colunas e hifen (-) para criar a linha de separação.
* **Blocos de código:** Para destacar blocos de código, utilize três acentos graves (```) antes e depois do código.
