# Daschat Bots
Exemplos de bots feitos com a plataforma low code do Daschat.

### Definições
**ITM** = Menu interativo em texto. Este tipo de bot oferece um texto ao contato com uma série de opçes numeradas e o contato deve de responder digitando o número da opção escolhida por ele.

**SLOT** = Local onde uma informação é salva para uso posterior no Daschat. É a forma de passar uma informação de um componente do fluxo da conversa para outro ou para um atendente humano. Em uma linguagem de programação seria o equivalente a uma váriavel.

**FLUXO DA CONVERSA** = Todas as etapas por onde as mensagens de uma conversa passam. Pode ser um bot de inteligência artificial, bot interativo, um plugin de integração a um sistema de ERP ou os agentes humanos usando um sistema de atendimento.

**HANDSOFF** = O ato de transferir o fluxo da conversa para um atendente humano.

### Exemplos disponíveis

#### Bots sem ITM
O tipo de bot mais simples possível. Retorna uma mensagem ao contato e transfere imeditamente a conversa para um atendente humano (handsoff)

Exemplos: 

| Funcionalidade                                                                                |                 Exemplo                 |
| --------------------------------------------------------------------------------------------- | :-------------------------------------: |
| Responde ao contato com uma apresentação inicial e transfere para atendente humano em seguida | [just_welcome](just_welcome/flows.json) |

#### Bots com ITM
Estes bots enviam mensagens de texto contendo menus com opções numeradas para que o contato escolha o caminho que ele quer seguir na conversa. É o equivalente ao que se conhece como URA com IVR em sistemas de telefonia. Normalmente o contato deve de responder digitando o número da opção desejada ou clicando em um botão interativo.

Exemplos: 

| Funcionalidade                                                                                                                                                                                                               |                   Exemplo                   |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------------------------------------: |
| Responde ao contato com uma apresentação inicial e apresenta um menu para o contato escolher um departamento de atendimento. Este bot salva a informação do departamento escolhido, para uso posterior no fluxo da conversa. | [with_dept_menu](with_dept_menu/flows.json) |

