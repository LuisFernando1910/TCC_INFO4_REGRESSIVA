#ConnectServer

## 1. Identificação

* **Identidade Visual:** ![LOGO CONNECT SERVER](https://github.com/LuisFernando1910/TCC_INFO4_REGRESSIVA/blob/main/Connect.png)
* **Redes Sociais:** https://chat.whatsapp.com/J1cMsovMOAN3G7mV3ULvx6
* **Equipe:**
  * Luis Fernando - Desenvolvedor Sistema back-end
  * Nathalia Eduarda de Liz - Desenvolvedor Sistema Front-end
  * Isabele Stachuk - Desenvolvedor Sistema back-end - BD
* **Data de Criação:** 20//07/2024

## 2. Introdução
Atualmente, o serviço de múltiplos acessos na área da informática se mostra como um grande contratempo se não for feito de forma adequada, dificultando que vários usuários acessem recursos computacionais simultaneamente. Isso pode causar problemas como o consumo excessivo de memória, armazenamento e largura de banda de rede. Esses desafios são exacerbados em sistemas distribuídos, que são conjuntos de computadores independentes que funcionam como um único sistema para os usuários finais, e acaba se tornando um ponto crítico quando se trata da sincronização de relógios, pois várias máquinas devem estar coordenadas simultaneamente, do contrário, ocorrerão conflitos e contratempos na execução de eventos estritamente ordenados.
## Objetivos
- **Objetivo geral**: Desenvolver um site intuitivo e funcional que auxilie na gestão de tempo da produção e dos apresentadores de uma Rede de Comunicação Parceira, por meio da utilização de cronômetros regressivos.
- **Objetivos específicos**:
  - Compreender e documentar o processo atual (as-is);
  - Projetar o processo futuro (to-be) auxiliado pelo sistema a ser desenvolvido;
  - Desenvolver um sistema de conexão via NTP e obtenção de um stratum comum;
  - Criar uma interface web responsável pela interação com o usuário e sua infraestrutura;
  - Configurar um sistema de múltiplos acessos.
    
## Justificativa
Apesar de já existir um sistema de tentativa de sincronismo com múltiplos usuários e que seja notável que o processo atual seja funcional e em execução, não é de conhecimento desse projeto compreender os motivos pelos quais a primeira proposta feita para resolver o problema da aplicação de concomitância foi estruturada desta maneira manual, porém é notável que o desenvolvimento desse projeto pode trazer benefícios, como a sincronização automática das praças que serão conectadas a uma rede intranet a partir do protocolo NTP, otimizando o tempo de profissionais que destinam parte de seu tempo ao trabalho manual de inserir a contagem regressiva.
* **Escopo:**
  * **MVP:** 
  * **Entregas:** [Liste as principais entregas do projeto]
  * **Objetivos Quantificáveis:** [Defina métricas de sucesso]
  * **Critérios de Aceitação:** [Defina os critérios para considerar o projeto concluído]
  * **Prototipação:** [Link para o protótipo no Quant-UX]

## 3. Matriz de Riscos

| ID  | Risco                                                                 | Probabilidade | Impacto | Mitigação                                                                                           |
|-----|-----------------------------------------------------------------------|---------------|---------|-----------------------------------------------------------------------------------------------------|
| 1   | Consumo excessivo de memória                                          | Alta          | Alto    | Implementar monitoramento e otimização de recursos.                                                |
| 2   | Falha na sincronização de relógios                                    | Média         | Alto    | Utilizar NTP com servidores de stratum confiáveis e redundância.                                    |
| 3   | Sobrecarga de largura de banda de rede                                | Média         | Médio   | Implementar balanceamento de carga e otimização de tráfego de rede.                                 |
| 4   | Erros humanos na configuração manual                                  | Alta          | Alto    | Automatizar o processo de configuração e sincronização.                                             |
| 5   | Conflitos na execução de eventos estritamente ordenados               | Baixa         | Alto    | Implementar mecanismos de controle de concorrência e ordenação de eventos.                          |
| 6   | Vulnerabilidades de segurança devido à múltiplos acessos simultâneos  | Média         | Alto    | Implementar autenticação robusta e controle de acesso.                                              |
| 7   | Falha na obtenção de tempo de fontes confiáveis                       | Baixa         | Médio   | Configurar múltiplas fontes de tempo e implementar verificações de integridade.                     |
| 8   | Sobrecarga dos profissionais devido ao processo manual                | Alta          | Alto    | Desenvolver um sistema automatizado para reduzir a carga de trabalho manual.                        |

## 4. Organização do Projeto

* **Cronograma:** https://github.com/users/LuisFernando1910/projects/13
# **Equipe:**
- **Luis Fernando - Desenvolvedor Sistema back-end**:
  - Responsável pela implementação da lógica do servidor e integração com o banco de dados.
  - Desenvolver APIs para comunicação entre o front-end e o back-end.
  - Garantir a segurança e a eficiência do sistema, incluindo autenticação e autorização.

- **Nathalia Eduarda de Liz - Desenvolvedor Sistema Front-end**:
  - Criar e manter a interface do usuário, garantindo uma experiência intuitiva e responsiva.
  - Implementar funcionalidades interativas usando tecnologias como HTML, CSS e JavaScript.
  - Colaborar com o time de design para garantir que a interface atenda aos requisitos visuais e funcionais.

- **Isabele Stachuk - Desenvolvedor Sistema back-end - BD**:
  - Projetar e gerenciar o banco de dados, garantindo a integridade e a eficiência dos dados.
  - Implementar consultas e procedimentos armazenados para suportar as funcionalidades do sistema.
  - Realizar backups e otimizações regulares para garantir a disponibilidade e a performance do banco de dados.

## 5. Conclusão
O desenvolvimento de um sistema de múltiplos acessos e sincronização de relógios utilizando NTP representa um avanço significativo para a Rede de Comunicação Parceira. Este projeto visa substituir o processo manual atual, que é suscetível a erros humanos e sobrecarrega os profissionais, por uma solução automatizada e eficiente. A implementação de cronômetros regressivos e a sincronização automática dos dispositivos não apenas otimizará o tempo dos profissionais, mas também garantirá a consistência e a precisão necessárias para a execução ordenada dos eventos. Com uma interface web intuitiva e um sistema robusto de back-end, a empresa poderá melhorar a gestão de tempo e a coordenação entre suas praças, resultando em uma operação mais fluida e confiável.

* **Recursos Utilizados**

| Recurso                | Descrição                                                                 |
|------------------------|---------------------------------------------------------------------------|
| **Servidor Apache 2.4**| Servidor web que hospeda a aplicação, gerencia requisições HTTP e serve os arquivos do site. |
| **Banco de Dados SQLite** | Banco de dados leve e autônomo utilizado para armazenar dados da aplicação de forma eficiente. |
| **Back-end PHP**       | Linguagem de programação utilizada para desenvolver a lógica do servidor, manipulação de dados e integração com o banco de dados. |
| **Front-end JS, HTML e CSS** | Tecnologias utilizadas para criar a interface do usuário, tornando-a interativa e responsiva. |



* **Resultados Esperados:**
    A partir desse projeto, espera-se compreender e documentar o processo atual (as-is) como forma de base para desenvolver o processo futuro (to-be), ambos utilizando os conceitos e notações do Business Process Model and Notation (BPMN). Ademais, o projeto pretende criar e desenvolver um sistema de conexão via NTP - que será responsável pela obtenção do stratum -, juntamente a uma interface web, a qual terá o objetivo de interagir com o usuário e sua infraestrutura, além de gerenciar a entrada deste. Por fim, será implementado ao projeto a possibilidade de múltiplos acessos, viabilizando o acesso de diversas entidades e a modificação de seus dados, simultaneamente.
  
Com isso, a ferramenta a ser desenvolvida visa a automação de um processo que é atualmente manual, sujeito a falhas humanas e consequentemente otimizando o trabalho de profissionais que destinam parte de seu tempo a este serviço. Em paralelo, o projeto propõe trazer mais segurança a usuários que estão dispostos a utilizarem um sistema de sincronização


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
