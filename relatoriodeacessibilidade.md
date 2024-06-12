# Introdução

No desenvolvimento deste projeto, foi dada uma atenção especial às diretrizes do WCAG (Web Content Accessibility Guidelines) com o objetivo de tornar nosso sistema acessível a todos os usuários, independente de suas limitações ou deficiências. Seguindo estas diretrizes, procuramos garantir que todos tenham acesso equitativo à informação e aos serviços oferecidos pela plataforma. Abaixo, detalhamos as ações tomadas em conformidade com as recomendações do WCAG, categorizadas por cores para facilitar a compreensão das diferentes áreas de foco, incluindo estrutura de informação, autenticação, legibilidade de tela, e comunicação de status. Cada medida adotada visa promover uma experiência de usuário inclusiva, destacando nossa dedicação em tornar o conteúdo digital acessível a todos.


# Vermelho

## 1.3.1 - Informações e Relações [A]

A organização estrutural de uma tela deve ser construída de forma que sua arquitetura de informação faça sentido tanto para quem vê, quanto para quem ouve o conteúdo.

Pensando em qual história o usuário gostaria de visualizar a partir da base de dados, focamos em apresentar os dados de forma simples e direta, agrupando elementos similares. Assim, o usuário não fica confuso nem perdido durante a navegação.

No entanto, não temos algo para pessoas que teriam que "escutar" o conteúdo. Pensando no tempo do nosso projeto, não conseguimos implementar um sistema para transformar um dashboard em algo audiovisual. No entanto, encontramos alguns sistemas que poderiam nos auxiliar quanto a isso. Para tornar nossa plataforma mais acessível a usuários com deficiência visual, existe a inclusão do software JAWS (Job Access With Speech), que é um leitor de tela poderoso, permitindo a navegação e leitura de conteúdos digitais por meio de sintetizadores de voz. Assim, mesmo aqueles que não conseguem interagir visualmente com o nosso dashboard poderão receber as informações por meio de áudio, garantindo que nosso conteúdo seja acessível a todos.

Essa ferramenta tem a possibilidade de transformar dashboards em áudios, possibilitando uma maior acessibilidade e poderia ser uma solução para essa ausência.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/45d55ccc-2b39-4361-be99-816cae2674e5)

# Azul

## 2.2.5 - Nova autenticação [AAA]

Quando uma seção autenticada expira, qualquer pessoa logada deve ser capaz de continuar sua atividade, sem qualquer perda de dados, ao efetuar uma nova autenticação no ambiente.

No nosso sistema não temos input de dados em nenhum momento a não ser no log in. Sendo assim nosso sistema passou pelo teste, mesmo sendo [AAA].

## 2.4.2 - Página com título [A]

Todas as telas devem ter um título principal e que descreva claramente a sua finalidade. Prezando pela navegabilidade da página, e para ter certeza de que os usuários sabem exatamente onde se encontram na página, colocamos os títulos no topo superior esquerdo de cada tela. Inicialmente esse foi um ponto que não havíamos pensado, mas após um breve teste com alguns voluntários, foi indicado como um possível ponto de melhora. Por mais que seja algo simples, passou despercebido e foi corrigido.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/a978fc41-4d78-4259-8797-481797dd54da)
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/1aceb9a7-fc78-4048-b7bf-e7b5cd68267d)

# Amarelo

## 3.1.1 - Idioma da página [A]

Declarar adequadamente o idioma da tela faz com que leitores de telas utilizem uma entonação correta para citar conteúdos. Sempre os declare.

Não temos opção de outras linguagens porque desenvolvemos o nosso sistema somente para usuários da Volkswagen Brasil, por isso não tínhamos declarado. Mas conforme a WCAG pede, iremos inserir no nosso front a informação “PT-BR” e a bandeira do Brasil.

# Verde

## 4.1.3 - Mensagens de status [AA]

Qualquer tipo de mensagem que é resultado de uma ação ou que informa o andamento de um processo e que seja relevante para a pessoa, deve ser transmitida sem que ocorra uma mudança de contexto (foco) na tela.

Durante a navegação, o usuário consegue claramente visualizar onde ele se encontra nos sistema, tendo uma resposta rápida para as alterações e tenha certeza de que, na navegação, o usuário não se perca.

No entanto, não temos nada para mostrar um “carregamento” de alguma ação, uma vez que neste momento não temos nenhuma ação que necessitaria de uma atualização na página.

![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/f03d513f-e023-47cd-921c-dea3ecfc2fe6)
![image](https://github.com/Inteli-College/2024-T0004-SI09-G03/assets/99208930/4e32cf4e-0055-4fe3-956d-c9a740651b9c)


