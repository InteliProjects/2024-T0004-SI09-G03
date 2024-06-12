# Análise Heurística

Pensando em como melhorar tanto o nosso dashboard quanto a experiência do usuário, recebemos e analisamos os feedbacks sobre o mockup da nossa solução e fizemos alterações significativas no nosso front-end, buscando encontrar a melhor forma de demonstrar os dados.

Este documento dará uma visão geral dos feedbacks recebidos durante os testes, juntamente com a nossa preocupação com as heurísticas de Nielsen

Visão Lider da Planta:
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/d4c1f7c3-41ff-4d82-a7ef-b739d041f80a)

Visão Gerente de RH:
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/ac86ddb8-2335-4ff5-acbd-9504ef593299)

## 1. Visibilidade do Status do Sistema

No contexto da visibilidade do estado do sistema, enfatizamos a importância de garantir que o usuário esteja sempre informado sobre o que está acontecendo. Isto é alcançado por meio de feedback apropriado dentro de um tempo razoável, assegurando que o usuário nunca se perca durante sua navegação e sempre se sinta em controle da interação com a interface. Este aspecto foi destacado como um ponto positivo pelos nossos colegas e, por isso, o mantemos na nossa versão atual do front-end. Um exemplo claro dessa implementação é a nossa sidebar, que demonstra de forma inequívoca onde o usuário se encontra no sistema, garantindo que ele sempre saiba sua localização dentro da aplicação.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/607119da-d2e6-4d00-b391-def341590f90)

Além disso, um outro detalhe é o destaque dado à planta atualmente selecionada na tela, reforçando nossa dedicação à clareza e à eficácia na comunicação do estado do sistema ao usuário.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/86aa181d-00ef-4228-8883-20b5ec288f63)

## 2. Compatibilidade entre o sistema e o mundo real

Ao alinhar nosso sistema com a correspondência entre o sistema e o mundo real, priorizamos que o sistema fale a língua do usuário, empregando palavras e simbolos familiares, em vez de jargões técnicos ou termos orientados ao sistema. Nesse sentido, adotamos ícones e símbolos amplamente reconhecidos pelos usuários para facilitar sua adaptação e navegação. Por exemplo, utilizamos a engrenagem para simbolizar as configurações e um olho para representar a visão geral. Além disso, utilizamos símbolos relacionados a calendários, para representar dias perdidos de trabalho, por exemplo, visando uma comunicação intuitiva e direta com nosso público-alvo.

Essa atenção aos detalhes e à familiaridade visual foi positivamente destacada durante nossos testes, reforçando nossa decisão de manter essas escolhas no design final. Essa estratégia assegura não apenas uma interface amigável, mas também promove uma experiência de usuário mais fluida e intuitiva.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/3ecb4809-7888-40b9-a41f-2f47f643f05f)
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/50509572-5873-4aae-8fa2-69e52d9955cc)
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/969c97ad-c9d5-4391-93ab-b4ad8d71e27b)
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/dcd8979c-aee5-4708-8340-1d348855f4c9)


## 3. Controle e liberdade para o usuário

Na heurística de controle do usuário e liberdade, enfatizamos a importância de oferecer ao usuário a capacidade de desfazer e refazer ações, proporcionando a liberdade para explorar. Com o objetivo de reforçar a percepção do usuário de estar no controle de sua interação com o dashboard, mostramos onde ele pode interagir, através de detalhamentos adicionais ao passar o mouse sobre os gráficos. Essa abordagem não apenas assegura que o usuário se sinta mais “dono” da sua experiência, mas também aumenta sua confiança ao navegar e interagir com o sistema.

Recebemos feedbacks apontando que essa era uma área com potencial para melhorias. Dessa forma, dedicamo-nos a aprimorar os recursos já existentes e a introduzir novas opções que ampliam ainda mais o controle do usuário sobre o dashboard. Esses esforços visam otimizar a experiência de uso, permitindo que o usuário explore e interaja com a interface de maneira mais intuitiva.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/6d66a8e9-5aa4-4e10-b38a-f0c442ec49b3)

## 4. Consistência e Padronização

A heurística de consistência e padrões destaca a importância de evitar confusões para o usuário, assegurando que palavras, situações ou ações distintas não causem diferenças sobre seus significados. Com o intuito de manter uma identidade visual, tanto para o nosso dashboard quanto em alinhamento com a marca da Volkswagen, optamos por manter uma paleta de cores consistente em todo o dashboard. Isso inclui posicionar elementos importantes, como a sidebar, em locais fixos, garantindo sua presença constante, independentemente da página acessada. Esse cuidado visa não só reforçar a familiaridade do usuário com o ambiente digital, mas também fortalecer a sua orientação e conforto durante a navegação.

Embora este aspecto não tenha sido o mais enfatizado no momento, devido à implementação de apenas uma tela, já demonstramos um comprometimento consciente com essa heurística. Este ponto já foi levado em consideração no nosso mockup, e planejamos fazer o mesmo na versão final do dashboard.

Buscamos fazer as correções apontadas durante o teste de usabilidade, para aprimorar aquilo que já havíamos definido.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/a283c066-cfed-4fdb-8aa3-20817ff72a66)
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/ef93beb3-65a5-471d-8183-4929c09e9884)

## 5. Prevenção de erros

A heurística de prevenção de erros enfatiza a superioridade de um design que evita erros em vez de apenas corrigi-los após sua ocorrência. O sistema deve ser projetado com mecanismos que antecipem e previnam erros potenciais antes que eles aconteçam. Durante nossas sessões de feedback, foi reconhecido que a prevenção de erros representava uma lacuna em nosso design inicial, particularmente pela ausência de um sistema de notificação de erros. Conscientes de que esta versão do nosso dashboard é apenas o começo, ainda não implementamos mudanças significativas para abordar essa questão.

Inicialmente, optamos por limitar as ações disponíveis aos usuários às capacidades da nossa base de dados e proporcionamos a possibilidade de realizar ajustes específicos por meio dos filtros disponíveis. Essa abordagem visa minimizar a chance de erros pelo usuário, alinhando as ações possíveis às funcionalidades suportadas pelo sistema. No entanto, reconhecemos a importância de aprofundar e expandir nossas estratégias de prevenção de erros nas próximas sprints, com o objetivo de aprimorar ainda mais a usabilidade e a segurança do usuário ao interagir com o dashboard.

## 6. Reconhecimento em vez de memorização

A heurística de reconhecimento em vez de memorização sublinha a necessidade de criar um sistema em que o usuário possa facilmente reconhecer ações e elementos, sem a necessidade de recordar informações de uma interação anterior. Este princípio é essencial para garantir uma experiência de usuário fluida e intuitiva. Seguindo essa diretriz, e voltando à abordagem mencionada anteriormente no tópico 2, sobre a correspondência entre o sistema e o mundo real, nos esforçamos para incorporar ícones e ações que sejam imediatamente reconhecíveis e familiarizados aos usuários.

Para maximizar a intuitividade do uso da nossa ferramenta, adotamos práticas de design comuns, como a opção de passar o mouse sobre gráficos para revelar detalhes adicionais, uma sidebar consistentemente localizada na parte esquerda da tela para navegação, e a disposição central de informações relevantes ao usuário. Essas escolhas de design são deliberadas para minimizar a carga cognitiva, permitindo aos usuários se concentrarem no conteúdo relevante e na realização de suas tarefas com eficiência, sem a necessidade de recordar como navegar ou interagir com diferentes partes do sistema.

Esse ponto foi destacado durante a sessão de feedbacks, como algo que ainda tinha espaço para melhoria, então trocamos alguns ícones, como por exemplo da visão geral.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/09622b03-f8e1-4f3d-94d6-ff3a01be3028)
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/47bd6478-36ba-4584-af40-9686247eed34)
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/eebd129b-2954-4165-87e4-b685ebad366e)
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/b3f7513b-9c9a-4b32-81e9-05b156280ff0)


## 7. Eficiência e flexibilidade de uso

A heurística de flexibilidade e eficiência de uso ressalta a importância de incluir aceleradores no design da interface, que, embora possam passar despercebidos por usuários novatos, permitem que usuários experientes otimizem sua interação com o sistema.

Reconhecendo a necessidade de ampliar o foco nessa área do nosso projeto, consideramos essencial oferecer aos usuários recorrentes métodos para acelerar suas tarefas e facilitar a visualização de informações que possam variar ao longo do ano. Uma estratégia que adotamos para melhorar a flexibilidade e eficiência de uso envolve a incorporação de dados "datados", como a exibição de gráficos que separam informações por meses, e o rastreamento de dias de trabalho perdidos devido a atestados médicos.

Essa abordagem não só aumenta a relevância das informações apresentadas, adaptando-se às necessidades de análise temporal dos usuários, mas também introduz uma camada adicional de utilidade para aqueles familiarizados com o sistema, que podem querer comparar, por exemplo, a frequência de atestados ao longo de diferentes períodos. Ao oferecer essas funcionalidades, buscamos não apenas atender às necessidades dos usuários de primeira viagem, mas também enriquecer a experiência daqueles que interagem com nosso sistema de maneira mais intensiva e recorrente.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/19fde80d-312a-483e-bea6-f9f540c0b3b6)
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/2fb6029c-0e7e-49d1-9cc3-6a18610b235e)


## 8. Estética e design minimalista

A heurística de estética e design minimalista destaca a importância de uma interface limpa e focada, evitando a sobrecarga de informações irrelevantes ou raramente necessárias. Este princípio visa assegurar que as informações essenciais não sejam ofuscadas por elementos desnecessários, permitindo que os usuários se concentrem no que é mais importante. Em linha com essa abordagem, nos dedicamos a criar um design que seja ao mesmo tempo estéticamente agradável e funcional, sem causar distração ou confusão.

Optamos por utilizar cores suaves e não intrusivas, alinhadas com a identidade visual, além de ícones facilmente reconhecíveis que facilitam a navegação e o entendimento da interface. Os gráficos foram desenhados para apresentar as informações de maneira clara e direta, "mastigadas", para minimizar qualquer dificuldade de compreensão por parte do usuário. Esse cuidado com a apresentação visual e a organização das informações visa reduzir o "susto inicial" que os usuários podem experimentar ao se depararem com uma nova ferramenta, facilitando assim a sua adaptação e entendimento contínuo ao longo de toda a interação com a aplicação.

Esse ponto foi destacado como algo positivo durante o teste, então nos dedicamos para manter os aspectos elogiados, enquanto melhoramos os que foram indicados, como por exemplo, os ícones utilizados.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/f6566cba-dcb0-4f9b-b285-6dcfd503579c)


## 9. Ajude os usuários a reconhecerem, diagnosticarem e recuperarem-se de erros

Mensagens de erro são uma parte crítica da comunicação entre o sistema e os usuários. Elas devem ser informativas, diretas e oferecer uma solução construtiva sem causar frustração ou confusão adicional. O design deve ser intuitivo, com indicações visuais claras de onde o erro ocorreu e o que precisa ser feito para corrigi-lo.

### Design Intuitivo de Erros
No exemplo da tela de login da Volkswagen, ícones de alerta vermelhos são exibidos ao lado dos campos onde há erros - no caso, os campos de e-mail e senha. Isso atrai imediatamente a atenção do usuário para a área problemática.

### Comunicação Clara
A mensagem "Seu e-mail ou senha estão incorretos" é exibida em vermelho, destacando-se contra o fundo claro e imediatamente informando o usuário sobre a natureza do erro. Essa linguagem direta ajuda a evitar confusão e permite que o usuário compreenda rapidamente o problema.

### Resolução de Problemas
O link "Esqueceu a senha?" é colocado de forma proeminente perto dos campos de entrada, oferecendo uma solução fácil e acessível para o usuário que não consegue lembrar a senha.

### Feedback Positivo
Apesar da mensagem de erro, o design não é ameaçador ou excessivamente crítico, mantendo uma atmosfera positiva e encorajando o usuário a tentar novamente.

<img width="462" alt="image" src="https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/68927480/3c5c25f7-31b6-4aba-9a57-3781dbdc889e">

## 10. Ajuda e documentação

Entendemos que mesmo um sistema intuitivo como o nosso pode apresentar desafios e dúvidas para os usuários em determinados momentos. Para endereçar essas situações, é essencial que disponibilizemos ajuda e documentação adequadas. Estes recursos devem ser facilmente acessíveis e projetados para oferecer suporte efetivo e direto, garantindo que os usuários possam encontrar soluções rápidas e eficientes para suas questões.

Conforme ilustrado na imagem em anexo das configurações de notificações e interface do usuário, uma opção destacada é "Tutorial a cada vez que fizer login". Esse recurso foi desenvolvido com o intuito de fornecer aos usuários, especialmente aos novos ou aos que precisam de um breve lembrete sobre as funcionalidades do sistema, uma orientação passo a passo imediatamente após o acesso à plataforma.

<img width="502" alt="image" src="https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/68927480/d05e173f-b23f-4b91-834a-af8c5448225e">

## Conclusão

A análise heurística nos ajudou a pensar em quais elementos seriam absolutamente necessários para que a nossa solução ficasse o mais completa e intuitiva possível. Pensando tanto em design quanto em usabilidade, sem perder informações valiosas com os gráficos que temos.

As recomendações feitas pelos outros grupos deixaram um ponto de partida valiosíssimo para que fizéssemos as alterações necessárias para a construção do nosso dashboard.
