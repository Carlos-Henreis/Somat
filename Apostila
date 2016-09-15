










                      #UNIVERSIDADE FEDERAL DE SéO CARLOS


                            #SISTEMAS OPERACIONAIS II







                       #SISTEMA OPERACIONAL MULTIPROGRAMADO 

                             ABERTO PARA TREINAMENTO









                            Prof. H‚lio Crestana Guardia

                            Prof. Dr. Cl udio Kirner






                Bacharelado  em  Ciˆncia  da Computa‡âo - UFSCar 

                                      1990


















             Introdu‡âo
             
             Um  sistema  operacional  ‚  um programa que  age  como  uma 
        interface  entre um usu rio e o hardware de  um  computador.  Sua 
        fun‡âo  ‚  gerar  um ambiente no qual  usu rios  possam  executar 
        programas,  utilizando  o computador de maneira  eficiente.  Para 
        isto,  o  sistema operacional deve atuar como um gerenciador  dos 
        recursos de hardware dispon¡veis, e como um programa de controle, 
        encarregado  de  administrar a execu‡âo de  programas,  impedindo 
        erros ou uso impr¢prio do computador. 
             A existˆncia de diferentes tipos de sistemas computacionais, 
        como   microcomputadores,  redes  de computadores,  sistemas  com 
        m£ltiplos processadores,  e at‚ m quinas nâo  convencionais,  faz 
        com  que   os sistemas operacionais tamb‚m difiram,  variando  em 
        estrutura,  potˆncia  e complexidade,  de acordo com os  recursos 
        dispon¡veis que serâo gerenciados.
             Os  principais recursos que um sistema operacional  gerencia 
        sâo :  processadores,  unidades de armazenamento, dispositivos de 
        entrada e sa¡da, e dados.
             Sem   tornar  inconsistentes  os  tempos  de  execu‡âo   dos 
        programas,  um sistema operacional procura maximizar a utiliza‡âo 
        da UCP, maximizar o n£mero de programas executados num per¡odo de 
        tempo,  executar  cada  programa o mais  rapidamente  poss¡vel  e 
        minimizar  o  tempo de resposta entre a m quina e  seus  usu rios 
        interativos.
             As  opera‡ùes definidas em um sistema operacional incluem  : 
        implementa‡âo  de  uma  interface  com  os  usu rios  do  sistema 
        computacional, compartilhamento dos recursos dispon¡veis entre os 
        usu rios, possibilidade de troca de informa‡ùes, facilidades para 
        a  realiza‡âo de opera‡ùes de entrada e sa¡da,  e  capacidade  de 
        regenera‡âo a partir de situa‡ùes de erro.
             Uma  das  caracter¡sticas  mais  importantes  dos   sistemas 
        operacionais ‚ o suporte para multiprograma‡âo.
             Multiprograma‡âo   ‚  uma  forma  de  otimizar  o   uso   do 
        computador,  atrav‚s  da  execu‡âo simultƒnea de programas  e  de 
        atividades  de E/S,  fazendo com que a UCP trabalhe a maior parte 
        do tempo executando programas do usu rio.
            Um  sistema operacional multiprogramado com tempo  partilhado 
        mant‚m  residentes  em  mem¢ria diversos programas  prontos  para 
        execu‡âo.  Cada programa ‚ executado durante um determinado tempo 
        ( time slice ),  ou at‚ que tenha que esperar pelo atendimento de
        alguma  opera‡âo do sistema operacional (tipicamente opera‡ùes de 
        entrada e sa¡da), passando a UCP … execu‡âo de outra tarefa. Ap¢s 
        a realiza‡âo dessa tarefa, o sistema operacional pode continuar a 
        execu‡âo  do programa interrompido,  ou escalar um novo  programa 
        para execu‡âo.
             Pol¡ticas de escala‡âo de programas e de tarefas do  sistema 
        operacional  podem  ser  baseadas em an lises do  desempenho  dos 
        programas,  no tamanho e tempo previsto para suas  execu‡ùes,  na 
        ordem de entrada no sistema,  em prioridades pr‚-determinadas, ou 
        em outros m‚todos de avalia‡âo que garantam tempos razo veis para 
        as suas execu‡ùes.
             O    armazenamento   simultƒneo   de   diversos   programas, 
        entretanto, exige formas de gerenciamento de mem¢ria.
             T‚cnicas de compartilhamento permitem que mais programas  do 
        que  poderiam ser fisicamente armazenados em mem¢ria possam estar 
        em execu‡âo ao mesmo tempo.



                                        1





             Uma unidade de armazenamento externo ( disco,  tambor, fita, 
        etc  )  ‚  utilizada pelo sistema operacional  como  uma  mem¢ria 
        secund ria onde sâo armazenados todos os programas completos.
             O  sistema  operacional faz um  particionamento  da  mem¢ria 
        principal,  dividindo-a em peda‡os de tamanho fixo ( p ginas ) ou 
        variados,  que  sâo compartilhados no armazenamento dos programas 
        em execu‡âo.
             Sistemas  operacionais  que fazem uma  divisâo  dinƒmica  da 
        mem¢ria  principal  transferem  um programa  inteiro  da  mem¢ria 
        secund ria  para  a  principal sempre que este programa  for  ser 
        executado.  O  programa  ‚ alocado em um espa‡o  onde  ele  caiba 
        sobrando o menor ou maior espa‡o poss¡vel, dependendo da pol¡tica 
        implementada. 
             Nos  sistemas  que  utilizam  pagina‡âo,   os  peda‡os   dos 
        programas  sâo trazidos para a mem¢ria principal … medida em  que 
        sâo necess rios para a continua‡âo das suas execu‡ùes.
             A  transferˆncia de um programa ( inteiro ou em partes )  da 
        mem¢ria principal para a secund ria,  ‚ feita quando ele nâo est  
        sendo executado e o espa‡o que estava sendo utilizado para o  seu 
        armazenamento ‚ necess rio para a execu‡âo de outro programa.
             Os   crit‚rios  utilizados  para  escolha  das  p ginas   de 
        programas  que  serâo substitu¡das podem ser baseados  em  filas, 
        onde  a  ordem  de aloca‡âo indica a ordem  de  substitui‡âo;  em 
        crit‚rios  de utiliza‡âo,  eliminando da mem¢ria as  p ginas  que 
        foram  utilizadas  pela £ltima vez h  mais tempo ( Least Recently 
        Used - LRU ), ou outros m‚todos. 
             Ponteiros  sâo  mantidos  pelo sistema  operacional  para  a 
        identifica‡âo  do endere‡o relativo de cada programa na  mem¢ria. 
        No caso de sistemas que utilizam pagina‡âo, uma Tabela de P ginas 
        ‚   armazenada  para  identificar  a  presen‡a  das  p ginas  dos 
        programas na mem¢ria e o endere‡o de onde elas se encontram. 
             Com  a  finalidade  de nâo comprometer o tempo  da  UCP  nas 
        opera‡ùes  de  entrada  e sa¡da e  explorar  a  possibilidade  de 
        paralelismo   no  funcionamento  destes  dispositivos,   sistemas 
        operacionais  utilizam-se  de sistemas de 'SPOOL'  e  buffers  na 
        mem¢ria.
             A   existˆncia  de  canais  de  controle  independentes  nos 
        dispositivos de E/S permite a utiliza‡…o de buffers na realiza‡âo 
        de operacoes de entrada e sa¡da de dados. 
             Um canal ‚ um sistema computacional dedicado, utilizado para 
        o controle das opera‡ùes de E/S.
             O  canal  de  entrada  ‚ ativado para a leitura  sempre  que 
        houver  dados no dispositivo de entrada ( terminais,  leitora  de 
        cartùes,  fitas,  etc ).  A sua opera‡âo ‚ iniciada pela UCP, mas 
        nâo  necessita  de supervisâo para ser executada. 
        Enquanto  existirem buffers dispon¡veis para o preenchimento  com 
        os dados de entrada,  o canal de entrada pode operar,  avisando a 
        UCP,  atrav‚s  de  uma  interrup‡âo,  sempre que  um  buffer  for 
        completamente preenchido e necessita de tratamento.
             Para a realiza‡âo de opera‡ùes de sa¡da de dados,  o sistema 
        operacional  insere  os  dados em buffers e ativa a  opera‡âo  do 
        canal de sa¡da. O canal de sa¡da ‚ capaz de imprimir os dados sem 
        o controle da UCP, gerando uma interrup‡âo, assim que a impressâo 
        for completada,  liberando o buffer para reutiliza‡âo. 
             Por serem controladas por canais independentes, as opera‡ùes 
        de  E/S  podem  ser  realizadas paralelamente  …s  atividades  de 
        controle da UCP na execu‡âo de outras tarefas.



                                        2





             O sistema de SPOOL ( 'Simultaneous Peripherals Operation  On 
        Line'  ) introduz a utiliza‡âo do disco na execu‡âo das opera‡ùes 
        de E/S, armazenando nele os dados que serâo lidos pelos programas 
        e  os  dados  que  estes  irâo  imprimir.  
             Atrav‚s deste sistema,  a UCP,  respons vel pelo controle da 
        transferˆncia dos dados do dispositivo de entrada para a  mem¢ria 
        e dos dados de sa¡da da mem¢ria para o dispositivo de sa¡da,  nâo 
        tem que esperar pelas condi‡ùes de opera‡âo desses  dispositivos, 
        quando precisa ler ou imprimir dados.      
             Dados  de  entrada  sâo lidos do dispositivo  de  entrada  e 
        armazenados  no disco,  em uma  rea cujo endere‡o ‚ mantido  pelo 
        sitema  operacional,  para  utiliza‡âo  pelo programa  a  que  se 
        destina,  quando  este executar uma opera‡âo de leitura de dados. 
        Da mesma forma,  os dados de impressâo sâo gravados em  disco,  e 
        impressos quando o programa terminar sua execu‡âo.   
             Utilizando  buffers  e o sistema de  'Spooling',  o  sistema 
        operacional evita que a UCP tenha que aguardar pela opera‡âo  dos 
        canais  de E/S,  que operam em velocidades relativamente  baixas, 
        comparadas … da UCP. 
             A  existˆncia  de  um sistema  de  interrup‡ùes  permite  ao 
        sistema  operacional  compartilhar a utiliza‡âo da UCP  entre  os 
        diversos  programas residentes e tarefas de controle,  alocando-a 
        para a execu‡âo dessas atividades,  e retomando o controle quando 
        interrup‡ùes  forem  geradas.  As interrup‡ùes indicam  tamb‚m  a 
        situa‡âo da opera‡âo dos canais de E/S.
             Para poder alternar a UCP na execu‡âo de diversos programas, 
        o sistema operacional armazena as informa‡ùes relevantes sobre um 
        programa interrompido,  podendo restaur -las quando for retomar a 
        sua execu‡âo.
             Um programa ‚ representado no sistema operacional atrav‚s de 
        um  Bloco de Controle de Programa ( BCP ),  mantido desde  a  sua 
        entrada  no  sistema  at‚ o final de sua execu‡âo.  
             O  BCP  ‚ uma estrutura de dados  que  armazena  informa‡ùes 
        sobre um programa, incluindo o estado atual da sua  execu‡âo, uma 
        identifica‡âo  particular  a esse programa,  a sua prioridade  de 
        execu‡âo,  ponteiros para os recursos e  reas de mem¢ria e  disco 
        que  ele  est  alocando,  o endere‡o da pr¢xima  instru‡âo  desse 
        programa  que  ser   realizada,  informa‡ùes sobre seu  tempo  de 
        execu‡âo,   e   uma   rea  onde  sâo  salvos  os  conte£dos   dos 
        registradores.
             
             Sistemas de aloca‡âo de recursos, tratamento de situa‡ùes de 
        'deadlock',  controle de  concorrˆncia,  e sistemas de prote‡âo a 
        recursos  e  dados  nas unidades  de  armazenamento,  sâo  outras 
        caracter¡sticas de sistemas operacionais multiprogramados.















                                        3





             Descri‡âo do Sistema Operacional Simplificado

             O Sistema Operacional Simplificado ‚ um sistema  operacional 
        multiprogramado  com  execu‡âo de programas de usu rio  em  tempo 
        partilhado  que opera atrav‚s de compartilhamento da UCP entre os 
        seus  diversos processos concorrentes e os programas de  usu rios 
        provenientes de terminais.
             O  sistema  operacional  est  estruturado de  acordo  com  a 
        figura 1,  contendo sete processos concorrentes,  que atuam sobre 
        os perif‚ricos,  buffers, disco, mem¢ria, e outros recursos, como 
        blocos de contole de programas, vari veis de controle, etc.
             Um  conjunto de processos simples e um conjunto de processos 
        especiais compùem os m¢dulos de programas do sistema  operacional 
        simulado.
             Possuindo  maior prioridade de execu‡âo entre os eventos que 
        concorrem  pela  utiliza‡âo  da UCP,  os  processos  simples  sâo 
        respons veis pelo controle da utiliza‡âo dos recursos do sistema.
             O  conjunto de processos simples ‚ formado  pelos  seguintes 
        processos concorrentes : 
             
             1 - Leitura
             2 - Spool de entrada
             3 - Spool de sa¡da
             4 - Impressâo
             5 - Loader
             6 - E/S Usu rio
             7 - Pagina‡âo

             Os  processos  de  1 a 4 constituem o  Spooling  do  sistema 
        operacional. 

             - Leitura :  preenche buffers de entrada com o conte£do  das 
        p ginas  de  informa‡âo  ( programas e dados )  provenientes  dos 
        usu rios de um terminal.
               executado sempre que existem dados para  serem  lidos,  a 
        leitora nâo est  sendo ocupada e existem buffers dispon¡veis.

             - Spool  de entrada :  ‚ respons vel pela interpreta‡âo  das 
        p ginas  de  informa‡ùes lidas dos buffers  de  entrada,  e  pela 
        coloca‡âo dos programas e dados no disco,  bem como pela abertura 
        de espa‡o para impressâo, tamb‚m no disco.
             Ser   executado quando houver buffers preenchidos com  dados 
        para leitura,  espa‡o livre em disco, BCP's dispon¡veis e o disco 
        nâo estiver sendo utilizado.  

             - Loader  (  carregamento de programas ) :  tem a fun‡âo  de 
        alocar um n£mero m¡nimo de p ginas de mem¢ria, e realizar a carga 
        das p ginas necess rias do disco, de forma a permitir o in¡cio da 
        execu‡âo do programa.
             Quando existirem programas residentes em disco que ainda nâo 
        foram carregados na mem¢ria,  existir espa‡o em mem¢ria e o disco 
        nâo estiver sendo acessado, este processo poder  ser executado. 

             - Pagina‡âo  :  processo encarregado de alocar uma p gina de 
        mem¢ria  dispon¡vel,  para permitir a continua‡âo de um programa, 
        sempre  que  o sistema detectar falta de p gina  durante   a  sua 
        execu‡âo.  Caso  a p gina em falta seja de c¢digo do programa,  o 
        seu conte£do ‚ buscado no disco e carregado na p gina de  mem¢ria 


                                        4





        alocada.  Se  nâo houver mais p ginas dispon¡veis,  o processo de 
        pagina‡âo dever  escolher uma p gina para ser  retirada,  criando 
        espa‡o. 
             O  processo de pagina‡âo proporciona ao sistema  operacional 
        um  sistema de mem¢ria virtual no armazenamento dos programas  em 
        execu‡âo. 
             Est   em  condi‡âo  de ser executado sempre  que  o  sistema 
        operacional  detectar  a ausˆncia de uma p gina  de  programa  em 
        mem¢ria e o disco nâo estiver sendo utilizado.

             - Entrada  e  Sa¡da  de  dados de programas  de  usu rios  : 
        permite  trazer  o conte£do de p ginas de dados do disco  para  a 
        mem¢ria,  ou  remeter  para  o  disco  as  p ginas  de  impressâo 
        previamente preparadas na mem¢ria.
             Para  ser  realizado ‚ preciso que o disco nâo esteja  sendo 
        utilizado  por  nenhum  outro processo,  e  haja  solicita‡âo  de 
        leitura ou escrita por algum programa de usu rio.

             - Spool de sa¡da :  ‚ encarregado da sa¡da de um programa do 
        sistema.  Carrega  o  conte£do das p ginas do disco  (  programa, 
        dados, resultados ) em buffers para impressâo.
             Terminada  a execu‡âo de um programa,  com sucesso  ou  nâo, 
        existindo   buffers   dispon¡veis  e  o  disco  nâo  estando   em 
        utiliza‡âo, este processo ser  executado. 

             - Impressâo :  sua tarefa ‚ comandar a impressâo do conte£do 
        dos  buffers de impressâo,  sempre que houver  buffer  preenchido 
        para  impressâo  e  o  dispositivo de  sa¡da  nâo  estiver  sendo 
        utilizado. 

             Os   processos   denominados   de   escalador,   espera   de 
        interrup‡âo,   e  tratamento  de  interrup‡âo  sâo  os  processos 
        especiais  do  sistema  operacional,   que  proporcionam  o   seu 
        funcionamento.

             Escalador :  ‚ respons vel pela verifica‡âo de quais eventos 
        estâo  em  condi‡ùes  de serem executados,  e pela  aloca‡âo  dos 
        recursos necess rios para que eles ocorram.  Quando nâo existirem 
        mais  processos  simples  em  condi‡âo  de  serem  executados,  o 
        escalador tentar  escolher um programa de usu rio para execu‡âo.
            
             Espera  de  Interrup‡âo :  ativado quando nâo  h   processos 
        simples   ou  programas  de  usu rios  em  condi‡ùes   de   serem 
        executados,  o  processo  de espera representa a situa‡âo onde  o 
        sistema  operacional  aguarda somente o t‚rmino  da  opera‡âo  de 
        algum canal de E/S que, ao terminar, ir  gerar uma interrup‡âo.

             Tratamento  de Interrup‡âo :  fornece ao S.O.  condi‡ùes  de 
        retomar o controle dos recursos do sistema.  Possui,  por isso, a 
        maior prioridade de execu‡âo atribu¡da pelo sistema  operacional. 
          respons vel  pela  an lise das necessidades dos  programas  de 
        usu rios pelo posicionamento dos BCP's nas filas correspondentes, 
        e  pelo  controle  do 'status' dos canais de  E/S  e  disco,  que 
        habilitam ou bloqueiam a execu‡âo dos processos simples.






                                        5






        Figura  1 :  Estrutura‡âo do sistema operacional e seus processos 
                     concorrentes

























































                                        6





             O  Sistema Operacional Simplificado corresponde ao  seguinte 
        algoritmo :

             repeat
               EXECUTA_PROCESSOS_SIMPLES;
               if not VAZIA ( FILA_DE_PROGRAMAS_EXECUTøVEIS ) 
                  then begin
                         ESCALA_PROGRAMA_DE_USUøRIO;
                         HARDWARE
                       end;
               if not INTERRUP€éO
                  then ESPERA_INTERRUP€éO;  { BUSY WAIT }
               TRATA_INTERRUP€éO
             until FALSE;  { REPEAT FOREVER }    


             Descritor de Programa : BCP

             Os   programas  sâo  representados  no  sistema  operacional 
        atrav‚s de Blocos de Controle de Programa ( BCP ), com o seguinte 
        formato : 
                  ÚÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ¿ 
                  ³     Identificador do JOB        ³ 
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³   Endere‡o da Tab P ginas       ³
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³             ACC                 ³ 
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³             CP                  ³ 
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³            TIMER                ³
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³             TS                  ³ 
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³  FP (nro da p gina em falta)    ³ 
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´
                  ³ Tipo p g em falta (Cod ou Dado) ³
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´      
                  ³   End do programa no disco      ³
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´     
                  ³     Tamanho do programa         ³ 
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³   End  rea de dados no disco    ³ 
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³  Apontador corrente dos dados   ³
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³   End  rea impressâo no disco   ³ 
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³ Apontador corrente da impressâo ³ 
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³C¢digo de Condi‡âo de interrup‡âo³
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³                                 ³
                  ÷      { ørea de trabalho }       ÷
                  ³                                 ³
                  ÃÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
                  ³     Liga‡âo para outro BCP      ³
                  ÀÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÙ


                                        7






                           Figura 2 : Fluxo dos BCP's


























































                                        8





             Filas de Programas
             
             Na   rea  de dados do S.O.  sâo criadas filas de  Blocos  de 
        Controle  de Programas ( BCP's ),  que cont‚m os descritores  dos 
        programas nos diversos estados de transi‡âo durante a execu‡âo no 
        sistema operacional.
             As filas exitentes sâo as seguintes : 

             Fila 0 : Fila dos BCP's dispon¡veis
             Fila 1 : Programa em processo de entrada ( Spool in )
             Fila 2 : Programas residentes em disco
             Fila 3 : Programas prontos para execu‡âo
             Fila 4 : Programa sendo executado
             Fila 5 : Programas suspensos aguardando opera‡ùes de E/S
             Fila 6 : Programas suspensos por falta de p ginas
             Fila 7 : Programas acabados
             Fila 8 : Programa em estado de sa¡da

             Outras filas podem ainda ser utilizadas para a implementa‡âo 
        de  sistemas  de espera com prioridade,  para  programas  que  j  
        entraram  no sistema e estâo aguardando a opera‡âo do Loader,  ou 
        filas de programas suspensos por situa‡ùes diversas.

             Transi‡âo de estados dos programas

             Para  ser executado,  um programa ser  lido,  armazenado  em 
        disco, e carregado na mem¢ria do computador. Uma vez residente em 
        mem¢ria,  passar   entâo a ser interpretado e  executado,  at‚  o 
        t‚rmino  normal  de  sua execu‡âo ou at‚ que  alguma  interrup‡âo 
        fatal  ocorra.  Terminada sua execu‡âo,  com sucesso  ou  nâo,  o 
        programa  passar  … fase de sa¡da e impressâo do seu c¢digo e dos 
        resultados das suas opera‡ùes.
             O  processo de Leitura ‚ respons vel pela leitura dos  dados 
        do  dispositivo de entrada e pelo seu armazenamento  em  buffers. 
        Quando o processo de Spool In encontrar um buffer com informa‡ùes 
        que  indicam o in¡cio de um novo programa,  ele ir  alocar um BCP 
        dispon¡vel e coloc -lo na fila 1. 
             Conseguindo  interpretar corretamente os dados  do  programa 
        contidos  nos buffers de leitura e preencher os dados do seu BCP, 
        o  Spool In passar  entâo esse BCP da fila 1 para a fila  2,  dos 
        programas residentes em disco.
             O processo Loader ser  respons vel pela cria‡âo da tabela de 
        p ginas do programa na fila 2, pelo  carregamento da sua primeira 
        p gina  de  c¢digo na mem¢ria,  e pela transferˆncia do seus  BCP 
        para a fila 3, dos programas prontos para execu‡âo.
             Quando, no S O, o escalador escolher um programa para ocupar 
        a   UCP,   ser   necess rio  carregar  os  registradores  com  as 
        informa‡ùes   referentes  ao  estado  de  execu‡âo  do   programa 
        escalado.
             Um  programa  em  execu‡âo  poder   ser  interrompido  pelos 
        seguintes motivos :

             - O  programa  requer  a execu‡âo de uma  opera‡âo  de  E/S, 
        e  gera  uma  interrup‡âo.  Ao tratar a  interrup‡âo,  o  sistema 
        operacional  colocar  o BCP na fila 5,  dos programas  aguardando 
        E/S. 
             - O  peda‡o  do programa que cont‚m a pr¢xima instru‡âo  que 
        dever   ser executada nâo est  presente na mem¢ria,  gerando  uma 


                                        9





        interrup‡âo  por falta de p gina.  O tratamento  de  interrup‡ùes 
        ir   transferir  o BCP para a fila 6,  dos  programas  aguardando 
        pagina‡âo.
             - Uma  interrup‡âo na execu‡âo do programa ‚ gerada,  devido 
        ao tempo de execu‡âo,  t‚rmino normal de execu‡âo,  ou ocorrˆncia 
        de  situa‡ùes  que causariam um erro fatal (prote‡âo de  mem¢ria, 
        c¢digo   de   opera‡âo  inv lido,   ou  overflow   em   opera‡ùes 
        matem ticas).  O tratamento de interrup‡âo do sistema operacional 
        ser   respons vel  pela transferˆncia do BCP do programa  para  a 
        fila 7, dos programas terminados, que aguardam sa¡da do sistema.

             OBS : Nas filas 1, 4 e 8 poder  haver somente um programa de 
        cada  vez,  visto  que s¢ poder  existir um programa em  fase  de 
        entrada,  um programa sendo executado, e um programa em estado de 
        sa¡da sendo atendidos pelo sistema operacional.  Nas demais filas 
        ‚   poss¡vel  a  existˆncia  de  mais  de  um  BCP's   aguardando 
        tratamento.

             Organiza‡âo dos programas no disco

             Funcionando  como  uma mem¢ria secund ria  de  armazenamento 
        externo, o disco ‚ utilizado para conter os programas em execu‡âo 
        no sistema operacional. 
             Existem trˆs  reas que um programa precisa alocar em disco :

             - ørea  de  Programa  :  para  armazenamento  do  c¢digo  do 
        programa.
             - ørea de Dados :  p ginas de dados, lidos do dispositivo de 
        entrada, utilizados pelas opera‡ùes de leitura do programa.
             - ørea de Impressâo : espa‡o vazio que precisa ser reservado 
        para as opera‡ùes de impressâo de dados do programa.

             Para  a manipula‡âo dessas  reas ‚ necess rio que o  sistema 
        operacional  mantenha ponteiros que indicam o endere‡o da  p gina 
        corrente de dados, que ser  lida por um programa, e o endere‡o de 
        onde  ser  impressa a pr¢xima p gina indicada por  uma  instru‡âo 
        de impressâo dos programas de usu rios.

             Filas de Buffers de E/S

             O S O possui 8 buffers,  do tamanho das p ginas de mem¢ria e 
        disco, que sâo utilizados pelo Spooling do sistema operacional na 
        realiza‡âo das opera‡ùes de E/S.
             Trˆs filas de buffers sâo utilizadas pelo sistema :  fila de 
        buffers   aguardando  Spool  In,   fila  de  buffers   aguardando 
        Impressâo, e fila de buffers livres.
             No  in¡cio  da  opera‡âo do  sistema  operacional  todos  os 
        buffers  estâo dispon¡veis,  na Fila de Buffers Livres.
             O processo de Leitura aloca buffers livres,  para  preencher 
        com  os dados lidos dos dispositivos de entrada,  e os insere  na 
        fila de buffers aguardando Spool In.
             Buffers  na  fila  para  Spool  In  sâo  interpretados  pelo 
        processo Spool In e liberados para reutiliza‡âo.
             O  processo  de  Spool Out ‚ respons vel pela  sa¡da  de  um 
        programa  do  sistema operacional,  colocando os dados que  serâo 
        impressos  em buffers dispon¡veis,  inseridos na fila de  buffers 
        para impressâo.



                                       10





             A  impressâo  dos  buffers  ‚  comandada  pelo  processo  de 
        Impressâo,  que  envia  os  dados para o dispositivo de  sa¡da  e 
        devolve  os  buffers  para  a  fila  de  buffers   livres,   para 
        reutiliza‡âo. 

             Problemas de Deadlock na aloca‡âo de buffers

             Uma das poss¡veis situa‡ùes de deadlock previstas e que deve 
        ser  evitada  pelo sistema operacional ‚ a  aloca‡âo  de  buffers 
        pelos processos de Spooling.
             Em determinado instante,  o disco poder  ficar completamente 
        cheio, impedindo a a‡âo do processo de Spool In de carregar novos 
        programas dos buffers no disco.
             Se,   neste  instante,   todos  os  buffers  estiverem  sido 
        preenchidos  com  dados  de entrada,  ocorrer   uma  situa‡âo  de 
        deadlock, pois :

             - Spool  In  nâo  pode  atuar,  e  por  isso  mat‚m  buffers 
        preenchidos bloqueados, pois precisa de espa‡o em disco.

             - Spool Out nâo opera,  mesmo quando programas terminam suas 
        execu‡ùes,  porque  precisa  preencher  buffers com os  dados  de 
        sa¡da,  e  estes estâo bloqueados pelo Spool  In.  Portanto,  nâo 
        libera espa‡o em disco.

             Uma solu‡âo para este problema ‚ nunca permitir que todos os 
        buffers  sejam preenchidos para Spool In  simultaneamente.  Desta 
        forma,  garante-se que o Spool Out poder  atuar, liberando espa‡o 
        em disco para o Spool In.































                                       11






        Figura 3 : diagrama de acesso aos recursos do sistema operacional


























































                                       12





             Paralelismo de Execu‡âo    

             Processamento   paralelo   ‚   uma   forma   eficiente    de 
        processamento de informa‡âo que enfatiza a explora‡âo de  eventos 
        concorrentes no processo computacional,  onde a ocorrˆncia desses 
        eventos  concorrentes  pode  dar-se durante o  mesmo  per¡odo  de 
        tempo,  durante  o mesmo instante de tempo ou durante espa‡os  de 
        tempos sobrepostos.
             Em  um ambiente com um £nico processador,  o paralelismo  de 
        execu‡âo explora as seguintes caracter¡sticas :

             - sobreposi‡âo  de opera‡ùes da UCP com opera‡ùes de entrada 
        e  sa¡da  que podem ser controladas por canais  de  processamento 
        aut“nomo nos dispositivos perif‚ricos.

             - uso   de   multiprograma‡âo  e   tempo   partilhado,   com 
        intercala‡âo da UCP na execu‡âo de processos e programas.

             - balanceamento dos ¡ndices de desempenho dos subsistemas do 
        ambiente com o objetivo de eliminar gargalos.


             Processos Simples

             As opera‡ùes de E/S do sistema, a pagina‡âo dos programas na 
        mem¢ria  e  as instru‡ùes de E/S dos  programas,  sâo  a‡ùes  que 
        utilizam os canais de E/S no Sistema Operacional Simplificado,  e 
        podem ocorrer paralelamente … execu‡âo de programas pela UCP.
             Embora  possam ser executadas de maneira concorrente,  essas 
        opera‡ùes necessitam da supervisâo da UCP para ocorrerem.
             A  UCP  ‚ encarregada de verificar quando essas a‡ùes  devem 
        ser  executadas,  de  iniciar  suas  execu‡ùes  e  de  tratar  os 
        resultados das suas opera‡ùes. 
             Com  a finalidade de transformar o controle dessas opera‡ùes 
        em   processos  que,   assim  como  os  programas  de   usu rios, 
        concorrem   pela  utiliza‡âo  da  UCP,   o  Sistema   Operacional 
        Simplificado implementou os Processos Simples.
             Desta  forma,  os  Processos Simples sâo  procedimentos  que 
        controlam  a utiliza‡âo dos recursos envolvidos em  opera‡ùes  de 
        E/S e armazenamento de dados e programas.

             Um  Processo  Simples pode  estar  ativo,  concorrendo  pela 
        utiliza‡âo da UCP, ou inativo. Sua ativa‡âo ‚ feita sempre que as 
        condi‡ùes  necess rias  para  que  ele  ocorra  sâo  satisfeitas, 
        indicando  a necessidade da atua‡âo da UCP no controle de  alguma 
        opera‡âo de transferˆncia de dados ou programa.

             A  seguir,  sâo relacionadas as condi‡ùes necess rias para a 
        realiza‡âo dos processos.

        Leitura :  - existem dados no dispositivo de entrada
                   - existe buffer dispon¡vel
                   - o canal de leitura nâo est  sendo utilizado

        Spool In : - existe buffer na fila de buffers p/ Spool In
                   - existe espa‡o dispon¡vel em disco
                   - existe BCP dispon¡vel ou em estado de Spool In
                   - o canal de controle do disco nâo est  em uso


                                       13





        Loader      - existe espa‡o na mem¢ria ( pelo menos 2  p ginas  : 
                      uma para a Tabela de P ginas e uma para a  primeira 
                      p gina de c¢digo do programa )
                   - existe  BCP  na  fila dos  programas  residentes  em 
                     disco, aguardando carregamento na mem¢ria.
                   - o canal de controle do disco nâo est  em uso


        Pagina‡âo  - existe BCP na fila de programas aguardando pagina‡âo
                   - o canal de controle do disco nâo est  em uso


        E/Susu rio  - existe  BCP  na  fila  de  programas  aguardando  a 
                      realiza‡âo de opera‡ùes de E/S
                    - o canal de controle do disco nâo est  em uso


        Spool  Out - existe  BCP na fila de programas que  j   terminaram
                     suas execu‡ùes
                   - existe buffer dispon¡vel
                   - o canal de controle do disco nâo est  em uso


        Impressâo  - existe buffer na fila de buffers para impressâo
                   - o canal de controle do dispositivo de sa¡da nâo est 
                     sendo utilizado


             A UCP ‚ capaz de identificar quais condi‡ùes sâo satisfeitas 
        para a ativa‡âo dos Processos Simples. 
             Quando  for  executado,  um  Processo Simples ir   ativar  a 
        opera‡âo  de  um  canal de  controle  de  perif‚rico,  requerendo 
        leitura  ou  escrita  em um  dispositivo.  Enquanto  espera  pelo 
        t‚rmino  da opera‡âo iniciada,  a UCP nâo tem mais  tarefas  para 
        realizar  nesse processo e pode entâo ser alocada para o controle 
        de outras tarefas.
             Ao completar a leitura ou escrita que estava  executando,  o 
        canal gera uma interrup‡âo, indicando … UCP que os dados j  foram 
        lidos  e  podem  ser tratados,  ou j  foram  escritos,  e  que  o 
        dispositivo est  pronto para reutiliza‡âo. O Processo Simples que 
        havia sido suspenso volta a ser executado,  e faz o tratamento da 
        situa‡âo.

             Para  efeito de facilitar a verifica‡âo de  quais  condi‡ùes 
        sâo satisfeitas para a realiza‡âo de cada Processo Simples ‚ £til 
        a  implementa‡âo  de uma tabela que indique a  rela‡âo  entre  os 
        recursos e os processos.













                                       14






        Figura 4 :  Organiza‡âo geral dos processos e recursos do so e do             
        hardware

























































                                       15





             Tratamento de Interrup‡ùes

             Num  sistema computacional,  uma interrup‡âo ‚ um evento que 
        altera a seqˆncia de execu‡âo de instru‡ùes por um processador.
             Uma  interrup‡âo  ‚ gerada pelo hardware  do  computador  e, 
        quando ocorre, causa a execu‡âo dos seguintes passsos :

             - o  controle  do  processador ‚ retornado  para  o  sistema 
        operacional;
             - o  sistema  operacional  salva o estado  do  processo  que 
        estava sendo executado;
             - a  interrup‡âo ‚ analisada e o sistema operacional passa a 
        executar a rotina de tratamento correspondente.

             No   Sistema  Operacional  Simplificado  o   tratamento   de 
        interrup‡ùes  funciona de acordo com o esquema da figura 5 e pode 
        ser representado pelo seguinte algoritmo :

        if not NULO ( PROGRAMA_EM_EXECU€éO );
          then begin
                 SALVA_CONTEXTO ( PROGRAMA_EM_EXECU€éO );
                  
                 if INTERRUP€éO in CONJ_INT_DE_PROGRAMA
                   then begin
                          MOVIMENTA_BCP_PARA_A_FILA_CORRESPONDENTE;
                            
                          if FIM_DE_PROGRAMA
                            then LIBERA_PøG_DE_MEMçRIA;
                            
                          ZERA_INT ( INTERRUP€éO );
                          ZERA_INT ( INTERRUP€ïES_DE_PROGRAMA );
                        end
                      
                   else if INTERRUP€éO in CONJ_INT_DE_PERIFRICOS
                          then begin
                                 if TEMPO_DE_EXECU€éO_PROG > LIMITE
                                   then INSERE ( PROGRAMA_EM_EXECU€éO, 
                                                 INæCIO_FILA_PRONTOS )
                                    else begin
                                           PROGRAMA_EM_EXECU€éO := 
                                                       FATIA_DE_TEMPO;
                                                
                                           INSERE ( PROGRAMA_EM_EXECU€éO,
                                                    FIM_FILA_PRONTOS );
                                         end;
                                    
                                 ZERA_INT ( INTERRUP€éO );
                                 LIBERA_PERIFRICO;
                                 ATIVA_PROCESSO_SIMPLES_SUSPENSO;
                               end;
                 end
               
            else begin      
                   ZERA_INT ( INTERRUP€éO );
                   LIBERA_PERIFRICO;
                   ATIVA_PROCESSO_SIMPLES_SUSPENSO;
                 end;                        



                                       16






             figura 5 : tratamento de interrup‡ùes


























































                                       17





             Ao  fazer o tratamento de uma interrup‡âo de  perif‚rico,  o 
        sistema  operacional ‚ capaz de identificar qual Processo Simples 
        havia comandado a sua opera‡âo e deve ser reativado. 
             O   tratador  de  interrup‡âo  libera  o   perif‚rico   para 
        reutiliza‡âo, mas ‚ necess rio que o Processo Simples que iniciou 
        a  sua  opera‡âo  seja  reativado  para  tratar  outros  recursos 
        envolvidos,  como  buffers  ou BCP's que devem ser  liberados  ou 
        transferidos  para outras filas existentes,  ou dados  que  foram 
        lidos e devem ser tratados.

             Na  implementa‡âo  do Sistema Operacional Simplificado  pode 
        ser  utilizado  um  vetor que  indique  quais  Processos Simples, 
        suspensos enquanto aguardavam pela opera‡âo de perif‚ricos, podem 
        ser   reativados   depois  do  tratamento  de   interrup‡ùes   de 
        perif‚ricos.

             Vetor de Condi‡âo de Processos Simples - Segunda parte

              ÚÄÄÄÄÄÄÂÄÄÄÄÄÄÄÂÄÄÄÄÄÄÂÄÄÄÄÄÂÄÄÄÄÄÄÄÂÄÄÄÄÄÄÄÄÂÄÄÄÄÄÄ¿   
              ³ Leit ³ Sp In ³ Load ³ Pag ³ E/SUs ³ Sp Out ³ Impr ³                    
              ÀÄÄÄÄÄÄÁÄÄÄÄÄÄÄÁÄÄÄÄÄÄÁÄÄÄÄÄÁÄÄÄÄÄÄÄÁÄÄÄÄÄÄÄÄÁÄÄÄÄÄÄÙ
               (0/1)   (0/1)  (0/1)  (0/1)  (0/1)    (0/1)   (0/1)

             Cada  elemento  do  vetor ‚ assinalado  pelo  tratamento  de 
        interrup‡âo e zerado pelo escalador do sistema, ap¢s a escolha do
        processo  simples  que  ser   reativado para  o  t‚rmino  de  sua 
        execu‡âo.

































                                       18





             Hardware 

             O hardware do Computador Simplificado ( CS  ),  implementado 
        por  software  atrav‚s de procedimentos e  estruturas  de  dados, 
        simula  um  computador,  contendo  os recursos  necess rios  para 
        sustentar multiprograma‡âo ( Figura 6 ).
             Seus componentes incluem :

             - uma unidade central de processamento ( UCP ).
             - mem¢ria principal de acesso r pido.
             - uma unidade de armazenamento externo ( disco ).
             - registradores espec¡ficos e de uso geral
             - contador do tempo para execu‡âo de programas ( TIMER ).
             - contador  da fatia de tempo da UCP para a execu‡âo de cada 
        programa ( TIME SLICE ).
             - rel¢gio ( CLOCK ).
             - unidades  de  entrada  e sa¡da de  dados  controladas  por 
        canais aut“nomos.
             - vetor de interrup‡ùes

             Constru¡do  com a finalidade de proporcionar um ambiente que 
        restringisse os detalhes da implementa‡âo do sistema  operacional 
        somente  …s suas caracter¡sticas funcionais,  o hardware simulado 
        abstrai detalhes de baixo n¡vel na sua constru‡âo.
             Desta   forma,   a   unidade  b sica  do  seu   sistema   de 
        armazenamento  (  'palavra'  ),  ‚ especificada  atrav‚s  de  uma 
        estrutura de dados.
             Uma  palavra do CS ‚ um registro contendo trˆs  campos  para 
        valores inteiros :
                          ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
             Palavra :    ³ C1 ³ C2 ³ C3 ³  
                          ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ

             Ao  armazenar  uma palavra de instru‡âo,  os campos  de  uma 
        palavra terâo os seguintes significados :

             C1  :  C¢digo da Opera‡âo 
             C2  :  P gina referida pela instru‡âo
             C3  :  Deslocamento dentro da p gina referida ( palavra )

             Quando  representar  um dado,  somente o primeiro  campo  da 
         palavra ser  relevante, armazenando o valor do dado :

             C1  :  Valor do dado armazenado
             C2  :            -               ( Irrelevante ) 
             C3  :            -               ( Irrelevante )

             Para facilidade de desenvolvimento do sistema simulado,  foi 
        definida  uma  mem¢ria do usu rio,  composta por 256  palavras  e 
        sujeita   a  controles  e  manipula‡âo  por  parte   do   sistema 
        operacional.  Para  a implementa‡âo de um sistema de pagina‡âo  e 
        mem¢ria virtual entretanto,  o sistema operacional ir  estrutur -
        la em blocos de 8 palavras, formando 32 p ginas.







                                       19






                 Figura 6 : organiza‡âo do hardware 


























































                                       20





             Desta  forma,  um endere‡o qualquer v lido XYZ se  refere  … 
        p gina XY e palavra Z, dentro da p gina.

        end absoluto     ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿             Ä¿ desloc dentro 
        ( decimal )   00 ³ C1 ³ C2 ³ C3 ³ 00 Ä¿        ³ de uma p gina 
                         ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ     ³        ³
                           :    :    :        ³ P g 0  ³
                         ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿     ³        ³
                      07 ³ C1 ³ C2 ³ C3 ³ 07 ÄÙ        ³
                         ÃÄÄÄÄÅÄÄÄÄÅÄÄÄÄ´              ³ 
                      08 ³ C1 ³ C2 ³ C3 ³ 00           ³ 
                         ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ              ³ 32 P ginas
                           :    :    :                 ³
                         ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿              ³
                     249 ³ C1 ³ C2 ³ C3 ³ 00           ³
                         ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ    Ä¿        ³
                           :    :    :        ³        ³
                         ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿     ³P g 31  ³
                     255 ³ C1 ³ C2 ³ C3 ³ 07 ÄÙ        ³
                         ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ             ÄÙ

             Com  a finalidade de permitir que mais programas possam  ser 
        posicionados na mem¢ria simultaneamente para execu‡âo,  o sistema 
        operacional implementa um sistema de endere‡amento relativo,  com 
        mem¢ria compartilhada atrav‚s de pagina‡âo.
             Esse  sistema  de pagina‡âo faz com que os  programas  sejam 
        tratados  por  partes,  de modo que seus c¢digos  nâo  necessitam 
        estar   completamente  carregados  em  mem¢ria  durante  as  suas  
        execu‡ùes, e nem estejam alocados de maneira seqencial, ocupando 
        espa‡os cont¡guos na mem¢ria.
             Os programas sâo divididos em p ginas,  do mesmo tamanho que 
        as p ginas de mem¢ria,  que sâo carregadas em espa‡os dispon¡veis 
        da mem¢ria ou sobrepondo outros peda‡os de programa,  … medida em 
        que   sâo  necess rias  para  a  continuidade  da  execu‡âo   dos 
        programas. 
             Para  poder identificar a presen‡a das p ginas dos programas 
        na  mem¢ria e a sua eventual localiza‡âo,  o sistema  operacional 
        monta entâo  uma Tabela de P ginas, para cada programa, instalada 
        em uma p gina comum de mem¢ria.
             Cada palavra da Tabela de P ginas representa a presen‡a e  o 
        endere‡o efetivo de uma p gina do programa do usu rio na mem¢ria, 
        de acordo com os seguintes campos :

         C1 : Indica presen‡a ou ausˆncia de uma p g do prog na mem¢ria 
         C2 : Endere‡o efetivo da p gina na mem¢ria (se estiver presente)
         C3 :          ( nâo utilizado )

                              Tabela de P ginas       
                          Ú  ÚÄÄÄÄÄÂÄÄÄÄÄÂÄÄÄÄÄ¿      
                          ³  ³ 0/1 ³0..31³  -  ³ 0 : P gina 0 do programa
                          ³  ÃÄÄÄÄÄÅÄÄÄÄÄÅÄÄÄÄÄ´
        P gina de mem¢ria ³  ³ 0/1 ³0..31³  -  ³ 1 : P gina 1 do programa
           ( 0..31 )      ³  ÀÄÄÄÄÄÁÄÄÄÄÄÁÄÄÄÄÄÙ         ³ Programa
                          ³     |     |     |            
                          ³     |     |     |            
                          ³  ÚÄÄÄÄÄÂÄÄÄÄÄÂÄÄÄÄÄ¿         ³ Rascunho
                          ³  ³ 0/1 ³0..31³  -  ³ 7 : P gina 0 de rascunho
                          À  ÀÄÄÄÄÄÁÄÄÄÄÄÁÄÄÄÄÄÙ     


                                       21





             Desta  forma,  para  obter  o endere‡o efetivo  de  onde  se 
        encontra uma palavra de instru‡âo ou de dados,  de um programa  o 
        sistema operacional segue o seguinte procedimento :

             - Identifica  a  p gina de mem¢ria que cont‚m  a  Tabela  de 
        P ginas do programa.
             - Pesquisa nessa p gina,  na palavra correspondente … p gina 
        buscada, a presen‡a e o endere‡o efetivo da p gina.

             O sistema operacional mant‚m uma Tabela de P ginas para cada 
        programa  em execu‡âo.  Por ser instalada em uma p gina comum  de 
        mem¢ria,  entretanto,  o  tamanho dos programas ‚ limitado a,  no 
        m ximo, 8 p ginas, incluindo c¢digo e p ginas de rascunho.
             A  Tabela  de  P ginas  (  TP  )  representa  a  presen‡a  e 
        localiza‡âo  tanto  das p ginas de c¢digo quanto das  p ginas  de 
        rascunho reservadas.
             A   representa‡âo  das  p ginas  de  c¢digo  apresenta   uma 
        correspondˆncia  direta entre o n£mero da linha da TP e o  n£mero 
        da p gina.  Desta forma,  a presen‡a e localiza‡âo da p gina 0 do 
        programa do usu rio ‚ indicada pela linha 0 da sua TP, a p gina 1 
        pela linha 1 e assim sucessivamente.
             Para a representa‡âo das p ginas de rascunho,  entretanto, a 
        correspondˆncia  ocorre  de  maneira invertida :  a p gina  0  de 
        rascunho ‚ representada pela linha 7 da TP, a p gina 1 pela linha 
        6,  e  assim  por  diante,  no sentido contr rio  …s  linhas  que 
        representam as p ginas de c¢digo.
             Para o c lculo da posi‡âo da TP que indica a localiza‡âo  de 
        uma  p gina  de  rascunho  a expressâo  (7 - Nro  Pag)  pode  ser 
        utilizada. Assim : P gina 0  --> 7-0 = 7
                           P gina 2  --> 7-2 = 5, etc.

             A Unidade Central de Processamento do CS foi projetada com o 
        intuito  de  prover suporte de hardware necess rio … execu‡âo  de 
        v rios  programas com tempo partilhado e pagina‡âo na mem¢ria  do 
        usu rio.
             Os principais registradores da UCP sâo :

             ACC ( Acumulador ) : Um registrador, para valores  inteiros, 
        para finalidades gerais.
                    ÚÄÄÄÄÄÄÄÄÄÄÄÄÄÄ¿   
             ACC    ³              ³  
                    ÀÄÄÄÄÄÄÄÄÄÄÄÄÄÄÙ        

             CP ( Contador de Programa ) :  Um registrador de dois campos 
        para valores inteiros,  que fazem referˆncia … p gina e … palavra 
        da pr¢xima instru‡âo de programa a ser executada.  
                    ÚÄÄÄÄÄÄÂÄÄÄÄÄÄÄ¿   
             CP     ³ Pag  ³ Desl  ³  
                    ÀÄÄÄÄÄÄÁÄÄÄÄÄÄÄÙ     

             TP  (  Tabela  de P ginas ) :  Um registrador que  cont‚m  o 
        endere‡o  da Tabela de P ginas de um programa na mem¢ria (0..31), 
        o tamanho do programa em p ginas ( 0..7 ),  e o n£mero de p ginas 
        de rascunho reservadas.
                    ÚÄÄÄÄÄÄÂÄÄÄÄÄÄÂÄÄÄÄÄÄ¿   
             TP     ³ Tam  ³ Rasc ³ Pag  ³  
                    ÀÄÄÄÄÄÄÁÄÄÄÄÄÄÁÄÄÄÄÄÄÙ     



                                       22





             FP ( Falta P gina ) :  Um registrador para um campo de valor 
        inteiro que armazena o n£mero da p gina em falta no programa  que 
        estava sendo executado.
                    ÚÄÄÄÄÄÄÄÄÄÄÄÄÄÄ¿   
             FP     ³              ³  
                    ÀÄÄÄÄÄÄÄÄÄÄÄÄÄÄÙ     

             CK ( Clock ) : rel¢gio da UCP ( valor inteiro ).
                    ÚÄÄÄÄÄÄÄÄÄÄÄÄÄÄ¿   
             CK     ³              ³  
                    ÀÄÄÄÄÄÄÄÄÄÄÄÄÄÄÙ     

             TIMER  :  Registrador  para um campo de valor inteiro que  ‚ 
        inicializado com o tempo previsto para a execu‡âo de um  programa 
        e ‚ decrementado … medida em que ele ‚ executado.  
                     ÚÄÄÄÄÄÄÄÄÄÄÄÄÄÄ¿   
             TIMER   ³              ³  
                     ÀÄÄÄÄÄÄÄÄÄÄÄÄÄÄÙ     

             TS  (  TIME SLICE ) :  Contador da Fatia de Tempo  atribu¡da 
        pelo sistema operacional a um programa, para utiliza‡âo da UCP na 
        sua execu‡âo.
                     ÚÄÄÄÄÄÄÄÄÄÄÄÄÄÄ¿   
             TS      ³              ³  
                     ÀÄÄÄÄÄÄÄÄÄÄÄÄÄÄÙ     

             A  unidade  central  de processamento opera  atrav‚s  de  um 
        conjunto  simplificado  de instru‡ùes de m quina  que  permite  a 
        elabora‡âo  de  programas de usu rio,  envolvendo manipula‡âo  de 
        posi‡ùes de mem¢ria,  opera‡ùes aritm‚ticas, controle de desvio e 
        parada de programas,  e opera‡ùes de E/S.
             As instru‡ùes dividem-se em dois grupos principais :  as que 
        fazem  referˆncia  …   rea de c¢digo ( instru‡ùes  de  desvio  de 
        execu‡âo e fim de programa ) e as que manipulam a  rea  reservada 
        para rascunho ( demais instru‡ùes ).

             As seguintes opera‡ùes sâo implementadas :

             HLT : Indica o fim de processamento de um programa.
                            ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
             Instru‡âo :    ³  0 ³  - ³ -  ³  
                            ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ

             RD  XY  0  :  Lˆ  a  p gina  corrente da  rea  de  dados  do 
        programa  no disco e carrega o seu conte£do na p gina XY da   rea 
        de rascunho do programa. 
                            ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
             Instru‡âo :    ³  1 ³ XY ³ 0  ³  
                            ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ
             
             PRN  XY 0 :  Imprime,  na  rea de impressâo do disco alocada 
        pelo programa,  o conte£do da p gina XY da  rea de rascunho desse 
        programa.
                            ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
             Instru‡âo :    ³  2 ³ XY ³ 0  ³  
                            ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ




                                       23





             LD XYZ : Carrega no acumulador ( ACC ) o conte£do da palavra 
        Z  da p gina XY da  rea de rascunho do programa sendo  executado. 
        No  caso  do sistema simulado,  a opera‡âo carrega no  acumulador 
        somente o conte£do do primeiro campo da palavra de dados. 
                            ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
             Instru‡âo :    ³  3 ³ XY ³ Z  ³  
                            ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ

             STR XYZ :  Armazena o conte£do do acumulador na palavra Z da 
        p gina  XY da  rea de rascunho do programa.  Atribui o  valor  do 
        primeiro campo da palavra.            
                            ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
             Instru‡âo :    ³  4 ³ XY ³ Z  ³  
                            ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ

             SUB  XYZ :  Atribui ao acumulador o valor correspondente  ao 
        valor  que  este  continha,  subtra¡do  do  valor  armazenado  no 
        primeiro  campo da palavra Z da p gina XY da  rea de rascunho  do 
        programa do usu rio.
                            ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
             Instru‡âo :    ³  5 ³ XY ³ Z  ³  
                            ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ

             ADD  XYZ  :  Idem … subtra‡âo,  atribuindo ao  acumulador  o 
        resultado da soma ao inv‚s da subtra‡âo.
                            ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
             Instru‡âo :    ³  6 ³ XY ³ Z  ³  
                            ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ

             JMP XYZ :  Atribui um novo valor para o Contador de Programa 
        do programa em execu‡âo, que passa a ser executado a partir dessa 
        posi‡âo. 
                CP.PøG  = XY
                CP.DESL = Z
                            ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
             Instru‡âo :    ³  7 ³ XY ³ Z  ³  
                            ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ

             JNG  XYZ  :  O  conte£do do acumulador  ‚  checado  e,  caso 
        contenha  um valor negativo,  o valor de XYZ ‚ atribu¡do  ao  CP. 
        Caso  o  acumulador nâo seja negativo,  o programa  continua  sua 
        execu‡âo  a partir da pr¢xima instru‡âo em rela‡âo ao endere‡o em 
        que se encontra.
                           Se ACC < 0 
                              entâo ( CP.PøG  = XY
                                      CP.DESL = Z )
                            ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
             Instru‡âo :    ³  8 ³ XY ³ Z  ³  
                            ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ

             O CS cont‚m ainda um registrador de interrup‡ùes que indicam 
        anomalias   ou  sinais  de  alerta  gerados  pelo   hardware   em 
        determinadas condi‡ùes.
             O  registrador de interrup‡ùes ‚ implementado atrav‚s de  um 
        vetor de 12 posi‡ùes com campos que podem assumir os valores 0 ou 
        1.  O  valor 1 em um elemento desse vetor representa a ocorrˆncia 
        da  interrup‡âo  a  que  corresponde.  O valor  0  indica  a  nâo 
        ocorrˆncia de uma interrup‡âo.


                                       24





             Vetor de Interrup‡ùes

               ÚÄÄÄ¿   
             0 ³0/1³ Prote‡âo de Mem¢ria
               ÃÄÄÄ´
             1 ³0/1³ C¢digo de opera‡âo inv lido
               ÃÄÄÄ´   
             2 ³0/1³ Overflow
               ÃÄÄÄ´
             3 ³0/1³ Falta de p gina
               ÃÄÄÄ´   
             4 ³0/1³ Timer
               ÃÄÄÄ´
             5 ³0/1³ TS
               ÃÄÄÄ´   
             6 ³0/1³ Leia
               ÃÄÄÄ´
             7 ³0/1³ Imprima
               ÃÄÄÄ´   
             8 ³0/1³ Pare
               ÃÄÄÄ´
             9 ³0/1³ Canal 1 ( Leitora )
               ÃÄÄÄ´   
            10 ³0/1³ Canal 2 ( Impressora )
               ÃÄÄÄ´
            11 ³0/1³ Canal 3 ( Disco )
               ÃÄÄÄ´
            12 ³0/1³ Interrup‡âo Externa
               ÀÄÄÄÙ

             Os  elementos de 0 a 3 do vetor correspondem a  interrup‡ùes 
        de programa,  que sâo geradas em decorrˆncia das suas execu‡ùes.
             O  valor  1  no elemento 0 do vetor indica  que  o  programa 
        tentou  acessar uma posi‡âo de mem¢ria fora da sua  rea de c¢digo 
        ou de rascunho ou tentou ler ou imprimir dados no disco numa  rea 
        fora do espa‡o que havia alocado.
             O  elemento  1  do  vetor recebe o valor  1  sempre  que  um 
        programa   tentar  executar  uma  opera‡âo  cujo  c¢digo  nâo   ‚ 
        reconhecido pelo sistema operacional.
             Se,  durante a opera‡âo de uma instru‡âo aritm‚tica,  houver 
        overflow no valor armazenado no acumulador, o elemento 2 do vetor 
        de interrup‡ùes receber  o valor 1.
             Caso,  no  c lculo  do  endere‡o efetivo de uma  posi‡âo  de 
        mem¢ria  referenciada  por  um programa,  sua tabela  de  p ginas 
        indique  que  a  p gina  nâo  est   presente  na   mem¢ria,   uma 
        interrup‡âo por falta de p gina ‚ gerada, atribuindo-se o valor 1 
        ao elemento 3 do vetor.
             TIMER  e  TS sâo interrup‡ùes de tempo e sâo geradas  quando 
        esses registradores assumem o valor 0.
             Leia, Imprima e Pare sâo interrup‡ùes do sistema e indicam a 
        necessidade de realiz‡ùes de a‡ùes do sistema operacional.
             As  interrup‡ùes  dos  canais de  controle  dos  perif‚ricos 
        indicam ao sistema operacional o estado da Leitora, da Impressora 
        e  do  Disco,  e  sâo  ativadas  sempre  que  estes  dispositivos 
        completam a realiza‡âo de uma opera‡âo de Entrada/Sa¡da.
             Interrup‡ùes  externas,  geradas  pelo escalador ou  por  um 
        usu rio  do sistema,  podem ser geradas e sâo identificadas  pelo 
        elemento 12 do vetor de interrup‡ùes.


                                       25






                  Figura 7 - Hardware com vetor de interrup‡ùes 


























































                                       26





             Em  qualquer condi‡âo de interrup‡âo,  se houver um programa 
        em  execu‡âo,  ele  ‚  interrompido  logo ap¢s  a  realiza‡âo  da 
        instru‡âo que estava sendo tratada e o controle ‚ desviado para a 
        rotina de tratamento de interrup‡ùes do sistema  operacional.  As 
        informa‡ùes referentes … situa‡âo dos registradores do hardware e 
        do  estado da execu‡âo do programa sâo salvos no seu BCP e  podem 
        ser restauradas quando ele voltar a ser executado.
             As interrup‡ùes por prote‡âo de mem¢ria,  c¢digo de opera‡âo 
        inv lido,   overflow  e  timer  sâo  consideradas  fatais  e  sua 
        ocorrˆncia  durante  a execu‡âo de um programa  causa  o  t‚rmino 
        for‡ado de sua exece‡âo e a sua sa¡da do sistema. 

             Hardware simulado

             A  simula‡âo  do hardware leva em conta o  funcionamento  da 
        UCP,   realizando   busca  e  execu‡âo   de  instru‡ùes,    e   o 
        funcionamento   dos  perif‚ricos,   executando   suas   opera‡ùes 
        principais.  Durante a simula‡âo, sâo verificadas as condi‡ùes de 
        interrup‡âo  e  atualizado o tempo definido para a  execu‡âo  dos 
        diversos  m¢dulos do sistema.  A simula‡âo do hardware ocorre  de 
        acordo com o algoritmo colocado a seguir.

             repeat

               BUSCA_INSTRU€éO;  { FETCH }
               if not INTERRUP€éO
                  then begin
                         EXECUTA_INSTRU€éO;
                         SIMULA_PERIFRICOS
                       end;

             until INTERRUP€éO; 


             Simula‡âo dos perif‚ricos

             O Computador Simplificado suporta um dispositivo de  entrada 
        de  programas dos usu rios,  uma impressora e um disco ou tambor, 
        cada um ligado ao seu respectivo canal de controle.
             Um registrador de comando,  contendo trˆs campos, representa 
        o estado de opera‡âo dos canais de E/S.

                  ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿   
            RC :  ³Leit³Impr³Disc³  
                  ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ
          ÚÄÄÄÄ¿   
        0 ³ 0/1³ Leitora     - 0 : Leitora dispon¡vel; 1 : em opera‡âo
          ÃÄÄÄÄ´
        1 ³ 0/1³ Impressora  - 0 : Impressora dispon¡vel; 1 : em opera‡âo
          ÃÄÄÄÄ´
        2 ³1..5³ Disco       - 0 : Disco dispon¡vel
          ÀÄÄÄÄÙ               1 : Disco sendo utilizado para Spool In
                               2 : Disco sendo utilizado para Spool Out
                               3 : Disco sendo utilizado pelo Loader
                               4 : Disco sendo utilizado pela Pagina‡âo
                               5 : Disco sendo utilizado para E/S




                                       27






             A  simula‡âo  dos  perif‚ricos ocorre  de  maneira  bastante 
        simplificada, uma vez que sâo considerados somente a execu‡âo das 
        opera‡ùes e o tempo estabelecido para isto.

             Ao  iniciar  sua  opera‡âo ( ativa‡âo  do  perif‚rico  ),  a 
        vari vel  associada  ao perif‚rico ‚ atualizada com  o  valor  do 
        tempo padrâo gasto na opera‡âo do dispositivo e,  ap¢s o decorrer 
        desse  tempo,  que pode ser utilizado para execu‡âo de atividades 
        da  UCP e opera‡âo de outros canais,  uma interrup‡âo  ‚  gerada, 
        indicando que a opera‡âo foi desempenhada.      

             Um  registrador  de  trˆs  campos  para  valores   inteiros, 
        associados aos canais de E/S, ‚ utilizado para simular o tempo de 
        opera‡âo dos perif‚ricos.  

                   ÚÄÄÄÄÂÄÄÄÄÂÄÄÄÄ¿
             T :   ³Leit³Impr³Disc³  
                   ÀÄÄÄÄÁÄÄÄÄÁÄÄÄÄÙ

             Especifica‡ùes dos perif‚ricos :

        ÚÄÄÄÄÄÄÄÄÄÄÄÂÄÄÄÄÄÄÄÂÄÄÄÄÄÄÄÄÄÄÂÄÄÄÄÄÄÄÄÄÂÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ¿
        ³Perif‚rico ³ Canal ³ Registro ³ Tamanho ³ Vel (Tempo Opera‡âo) ³
        ÃÄÄÄÄÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´
        ³Leitora    ³   1   ³ 1 p gina ³    "    ³     10 unidades      ³
        ÃÄÄÄÄÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´
        ³Impressora ³   2   ³ 1 p gina ³    "    ³     10 unidades      ³
        ÃÄÄÄÄÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÄÄÅÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ´ 
        ³Disco      ³   3   ³ 1 p gina ³ 256 p g ³      3 unidades      ³ 
        ÀÄÄÄÄÄÄÄÄÄÄÄÁÄÄÄÄÄÄÄÁÄÄÄÄÄÄÄÄÄÄÁÄÄÄÄÄÄÄÄÄÁÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÙ





























                                       28





             Organiza‡âo dos programas de usu rio - CS / SOS

             Para efeito de se verificar a organiza‡âo de um programa  de 
        usu rio  ‚  importante  que se  observe  algumas  caracter¡sticas 
        b sicas do sistema de armazenamento do sistema operacional : 

             - uma  palavra  ‚  formada  por  trˆs  campos  para  valores 
        inteiros e pode armazenar uma instru‡âo ou um dado
             - uma p gina ‚ composta de 8 palavras
             - o  espa‡o de mem¢ria destinado aos programas  de  usu rios 
        cont‚m 32 p ginas
             - para  cada programa ‚ mantida uma tabela de  p ginas,  que 
        ocupa uma p gina comum de mem¢ria
             - as  instru‡ùes em geral referem-se a palavras,  exceto  as  
        instru‡ùes  LEIA  e  IMPRIMA  que fazem referˆncia a  p ginas.
             - qualquer  endere‡o referenciado por uma instru‡âo ou  pelo 
        contador de programa ( CP ) ‚ sempre relativo a uma p gina dentro 
        da  rea de c¢digo ou da  rea de rascunho do programa do  usu rio, 
        e nâo a uma posi‡âo efetiva na mem¢ria. Para encontrar o endere‡o 
        efetivo  a  que  se  refere  a  instru‡âo  ou  o  CP,  o  sistema 
        operacional deve consultar a tabela de p ginas desse programa.
             - para  a representa‡âo das p ginas de c¢digo do programa  a 
        correspondˆncia  entre  as  linhas  da  Tabela  de  P ginas  e  a 
        numera‡âo  das p ginas ‚ direta.  Na representa‡âo das p ginas de 
        rascunho a correspondˆncia se d  na forma invertida, ou seja, 7 - 
        o n£mero da p gina indicada pela instru‡âo.
             - Cada palavra da tabela cont‚m informa‡âo sobre a  presen‡a 
        ou  nâo  da  p gina  correspondente na  mem¢ria  e,  caso  esteja 
        presente, o endere‡o de onde ela se encontra.

             Desta  maneira,  poderia-se  pensar que o tamanho m ximo  do 
        programa de usu rio capaz de ser submetido ao sistema seria de 64 
        instru‡ùes ( 8 p ginas ).  Ocorre por‚m que, para a realiza‡âo de 
        entrada e sa¡da atrav‚s das instru‡ùes LEIA PøG e IMPRIMA PøG,  o 
        programa  deve  prever p ginas para leitura e para  impressâo  de 
        dados, reduzindo portanto o tamanho m ximo do programa.
             Assim,  se  for suficiente para o usu rio trabalhar com  uma 
        p gina de dados e uma p gina de impressâo,  executando instru‡ùes 
        que  manipulem  as  palavras dessas p ginas,  o  programa  ficar  
        limitado  a  6 p ginas ( 48 instru‡ùes ).  
             Poderâo  aparecer  casos onde uma £nica p gina  satisfaz  …s 
        necessidades de E/S,  sendo que a montagem da p gina de impressâo 
        ‚ feita sobre a p gina de dados,  que nâo tem mais utiliza‡âo, ou 
        casos  onde  sâo necess rias mais de uma p gina para  leitura  ou 
        para  impressâo,  quando os dados manipulados sâo em n£mero maior 
        que  a  capacidade de armazenamento de uma p gina,  ou  quando  a 
        gera‡âo  de dados para impressâo ocorre em posi‡ùes  seqenciais, 
        exigindo uma  rea maior que uma p gina.
             Deve-se  considerar que o programa dever  prover uma  rea de 
        trabalho  onde  ele  possa armazenar  os  valores  intermedi rios 
        gerados e utilizados pelo programa.
             Desta forma :

         Tam m x do programa =   64 
                               - nro de palavras da  rea de trabalho 
                               - ( 8 * nro p g simultƒneas de leitura ) 
                               - ( 8 * nro p g simultƒneas de impressâo )



                                       29





             Essas limita‡ùes no tamanho do programa do usu rio se  devem 
        … simplicidade do tratamento da Tabela de P ginas.
             O espa‡o para a  rea de trabalho pode ser reservado  atrav‚s 
        da  aloca‡âo  de p ginas de rascunho  utilizando-se  comandos  da 
        Linguagem de Controle de Programas do sistema operacional.


             Linguagem de Controle de Programa

             O  sistema  operacional trabalha sob o comando de linhas  de 
        controle  preparadas  pelos  usu rios,  que  podem  configurar  o 
        sistema e pedir a execu‡âo de programas, passando automaticamente 
        de programa para programa com um m¡nimo de tempo e interven‡âo de 
        operadores.
             Atrav‚s  da  Linguagem  de Controle de Programas, o  sistema 
        operacional   controla  e  direciona  as  opera‡ùes  de  E/S  dos 
        programas,  controla  o armazenamento e a aloca‡âo de espa‡os  em 
        disco,  determina  as  prioridades de execu‡âo  dos  programas  e 
        dispùe sobre a configura‡âo do sistema.

             A Linguagem de Controle de Programas do Sistema  Operacional 
        Simplificado  possui  a  seguinte   sintaxe  para  as  linhas  de  
        controle :

             * Job  { In¡cio de um novo programa }
               Identifica‡âo do programa
               Tempo previsto para execu‡âo
               Tamanho do programa
               N£mero de p ginas de rascunho
               N£mero de p ginas de impressâo    

             * Prog  { In¡cio das linhas de c¢digo }

               Linhas de programa  { Instru‡ùes }
                 
           [ * Dado  { In¡cio das linhas de dados }

               Linhas de dados  ]  { Dados }
           
             * Fim



             A  interpreta‡âo  das  linhas de controle ‚  executada  pelo 
        processo  de  Spool  de Entrada do sistema  operacional  e  opera 
        segundo o aut“mato de transi‡âo de estados ilustrado na figura 8. 














                                       30






              figura 8 : Spool de entrada - aut“mato de interpreta‡âo das 
                                            linhas de controle

























































                                       31





