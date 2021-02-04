# Primeiros passos tratamento fotográfico - Avmakers
> INIT - 3/2/21 - 16:37
#### Inteface Photoshop
- A primeira barra que fica a logomarca se chama barra de menus. São agrupamentos de funções. Lá você encontra
    File -> Funções para manipulaçao do arquivo.
    Edit -> Edição de camadas.
    Image -> Gerenciamento de cor e de imagem.
    Layer -> Funções de camadas (duplicar, mesclar etc...).
    Type -> Funções relacionadas à tipografia.
    Select -> Manipulação de seleção.
    Filter -> Efeitos Especiais.
    3D -> Modo mais avançado.
    View ->  Manipulação da visualização do software.
    Window -> Abrir e fechar paineis/janelas.
- Logo abaixo fica a barra de ferramentas, que mostra todas as opções relacionadas a ferramenta selecionada.
- No centro do software, fica a imagem que você está manipulando.
- À esquerda do centro, fica as ferramentas propriamente ditas. Clique em uma delas e a barra de ferramantas mostrará as opções relacionada a ferramenta selecionada.
- À direita são paineis, que são grupos de opções, são aglomerados de funções.

#### Modos e controles da visualização da imagem
- Clique no menu 'View' -> 'Screen Mode'. Há três opções. A melhor é 'Ful screen with Menu Bar'. Torna os paineis pequenos menus flutuantes. A tecla 'F' alterna entre essas opções.
- 'Tab' esconde todas as ferramentas e paineis.
- Clique 'Window' -> 'Navigator' para exibir um painel que tem a mesma função daquela barra lateral de visualização inteira do VSCode, funcionando, inclusive, para clicar e chegar no ponto que você deseja, exatamente como no vscode.

#### Histórico
- 'Window' -> 'History' exibirá o histórico.
- O número de passos salvos lá e limitado. Para mudar, você clica em 'Edit -> Preferences -> Performance' e terá um painel de opções, entre elas, o número de safes points'.
- Você pode registar uma espécie de "commit" clicando no símbolo de câmera fotográfica que fica no rodapé desse painel. Isso se chama Snapshot.
- Após o Snapshot, fazer modificações limpa o histórico subsequente (isso se você fez um snapshot no meio do histórico, obviamente).
- Ao lado do símbolo do snapshot tem uma opção com símbolo de '+' que te permite duplicar o documento naquele ponto do histórico em que você está.
- Se você abrir e fechar o documento, o histórico some, porque ele é salvo na memória ram, e a memória ram é volátil.
- É possível definir um autosave. Clique 'Edit -> Preferences -> File Handling'. Você terá um painel com todas as oções que precisa.

#### Diagramação e dimensões
- Se você usar centrimentos ou uma unidade de medida para definir o tamanho do documento, presumo que você vai imprimir. Você deve também alterar a resolução de conversão logo abaixo das opções de largura e altura. O photoshop deixa presetado em 72. Geralmente, para impressão você deve setar para 300, mas é melhor consultar a gráfica antes.
- A opção 'Relative' do 'Image -> Canvas Size' faz com que o valor informado seja incrimentado e não substitutívo. É igual ao += do javscript.

#### Guias e regua
- Pres 'Ctrl + R' ou Clq 'View -> Rules'.
- CLq e arraste a regua para criar uma guia. Pres 'Shit' para ativar precisão da guia, fazendo com que ela percorra a régua em números inteiros.
- Clq 'View -> New Guide' para te poupar do trabalho de arrastar. Você só precisará informar a unidade de medida é a orientação (vertical ou horizontal).
- Pres 'Ctrl + ;' para visualizar ou esconder as guias.
- Clq 'View -> New Guide Layout' você encontra presets de guias, a possibilidade de salvar suas guias e/ou importar guias. Também pode criar inúmeras colunas e/ou linhas guias definindo o espaço entre elas e as margens.
- Cliq 'View -> Show -> Grid' para facilitar a diagramação e encaixe de coisas no layout.
- Clq 'Edit -> Preferences -> Guides, Grids & Slices' para personalizar essas funções.
- Clq 'View -> Show -> Smart Guides' para exibir aquelas linhas roxinhas da hora pra carai.
- Clq 'View -> Snap' para fazer seus objetos grudarem em outro objetos quando você está arrastando. Legal pra carai tbm. 'View -> Snap To' pra definir no que você permite ele grudar.

#### Importar e modificar o tamanho de uma imagem
- 'File -> Place Embedded' para abrir incorporado. Isso significa que o PS criará uma cópia da imagem pra ele mesmo. Modificar o arquivo original não alterará seu projeto.
- 'File -> Place Linked' faz exatamente como no Premiere. Qualquer modificação no documento original reflete no seu documento.

#### Crop
- Tem alguns métodos interessantes dentro da barra de ferramentas do crop.
    Proporções -> O primeiro select te traz presets de proporções e também a custom, que você define informando as medidas. Clq 'Clear' para voltar para o modo de seleção de corte pelo mouse.
    Maletinha -> Serve para você traçar uma linha no sentido que você quer ajustar a orientação da imagem.
    Guias -> Tem presets de guias para te ajudar no corte, pra você encaixar elementos visualmente.
    Settings -> Mostra opções do preview do corte.
            'Show cropped area' -> Mostra ou não a area que vai ser cortada.
            'Opacity' -> A area a ser cortada pode ficar mais clara ou escura, você decide.
            'Enable Crop Shield' -> Você só vai ver a linha de transformação, igual ao select. Não dá pra mais escurecer a área a ser cortada.
    'Delete Cropped Pixels' -> Se true, aquilo que você cortar é apagado do documento. Se false, o que foi cortado se mantém no documento, mas não visível, possibilitando o redimensionado do crop.
    'Content-Aware' -> Você já sabe o que isso faz. Mas é interessante que ele mostrou o exemplo de aumentar a área do crop além do tamanho da imagem e fazer o crop já preencher o que falta com o content-aware'.

#### Tipos de camadas e funções em uma camada
- Tipos de camadas:
    Camada Tradicional -> É só a imagem mesmo, nenhum atributo especial.
    Camada de Objeto Inteligente -> Ainda não consegui entender o que é isso.
    Camadas de Ajustes de Cor -> Tem várias espécies de ajustes de cor.
    Camada de Vetor -> Não sei explicar tecnicamente, mas são objetos criados pelo próprio photoshop para integrar a imagem.
    Camadas de Texto -> Mesma coisa que vetor.
- Tem uma barra no painel de camadas que tem uma lupa. Ali indica que você pode buscar uma camada pelo tipo dela. Ao lado da lupa já tem presets com símbolos desses tipos. Os 5 listados acima são os principais e por isso possuem esses símbolos ai pronto para serem clicados.
- 'Shift + Clq' em cima da camada para desabilitá-la rapidamente.

#### Marquee (recorte quadradro ou redondo)
- Na barra de ferramentas, verifique o que está selecionado entre os 4 ícones existentes, que são os modos de interpolação.
    1 -> Desenha um recorte novo.
    2 -> Soma a um recorte já existente.
    3 -> Sobrepoe o antigo recorte onde ele conflitarem.
    4 -> Recorta somente onde o antigo e o novo recorte sobreporem.
- Feather define o desfoque em volta da máscara.
- Selecionando uma área e, ao invés de apertar ctrl+x, aplicar uma máscara o resultado será a exibição de somente a área selecionada.
- O ícone de corrente entre a camada da imagem e a camada da máscara significa que onde você mover imagem, a máscara vai junto e vice-versa.

#### Laços
- Possui os mesmos 4 modos de interpolação do Marquee.
- No primeiro laço, basta clicar e arrastar que quando você soltar a ferramente completo sua seleção automaticamente.
- Com a seleção realizada, você pode utilizar o método Fill 'Edit -> Fill'. Você sabe como usar isso, sempre usou kkk. Vai abrir um painel com várias opções do com o que você quer preencher aquela seleção. Deixa em 'Content-aware / sensível ao conteúdo' e o resto das opções deixa do jeito que está.
- Tem várias opções no menu Select, como selecionar tudo, selecionar inverso, deselecionar.

#### Seleção rápida
- Tem dois, a varinha e o pincel.
- A barra de ferramentas do pincel já tem 3 ícones de cara indicando que ele pode criar uma selação nova, adicionar ou remover a uma selação.
- Criada selação, pres 'Shift' para trocar entre modos de adicionar ou remover a seleção.
- Lembre-se de ajustar o tamanho do pincel.
- A varinha possui selação baseada em cor, isso significa que se você tiver luzes constantes, ela irá funcionar lindamente. Ela possui também as 4 modos de interpolação.
- 'Sample Size' é a área de amostragem. É ai que você define qual o tamanho da área que a varinha vai pegar de amostragem de cor. Logo a frente dessa opção, você pode aumentar o nível de tolerância da varinha. Quanto maior o nível de tolerância, maior vai ser o repertório de cor aceitas pela varinha.
- 'Anti-aliase' fará com que as bordas tenham uma pequena suavização de cor.
- 'Contiguous' significa que a varinha vai pegar os pixels até ele chegar em uma barreira. Supondo que você quer pegar azul e tem uma linha preta no meio de um banner azul, na hora que você clicar em um dos lados, só o lado clicado irá ser selecionado, caso isso esteja ligado. Se não, ele vai selecionar os dois lados, todos os azuis serão selecionados.
- Se você clicar e a selação for meio conservadora, você pode simplesmente aumentar a tolerância e tentar uma nova seleção. 
- Se você gostou da seleção, mais tem um pedaço que você também queria que fosse incluído e não foi, você pode mudar o modo de interpolação para somar, aumentar/diminuir a tolerância para o próximo clique e clicar...
- Se o método acima não é a melhor opção por que é só um pedacinho mesmo que você quer que entre, você pode simplesmente trocar a ferramente de seleção por outra, como a selação rápida, só pra ir empurrando aos poucos aquela parte da seleção.
- Você pode querer ter só o objeto que não foi selecionado, por exemplo, você quer trocar o céu de uma foto com uma casa no centro. Você pode selecionar o céu e então inverter a seleção e aplica uma máscara dai você tem a selação da casa. Sempre parta da pergunta "Qual é o objeto mais fácil de selecionar?". Vá no mais fácil e inverta a seleção.
- Se ainda assim, ficar algumas imperfeições no objeto que você quer, pres 'alt' e clique na mascará. Ela ficará tela cheia. Dai você pega o pincel e corrige a máscara. Isso você sabe fazer muito bem.

#### Seleção de intervalo
- Clq 'Select -> Color Range'. A primeira barra é algums opções de amostragem. O foda dessa ferramente é a possibilidade de você apenas clicar naquela áreazinha de previu para ele obter a amostragem e então apenas ir subindo e descendo o avanço da máscara, aumentando e diminuindo a tolerância de modo mundo mais fácil e com preview imediato, que pode ser configurado como você quiser.
- Esse color range tem opções de preview incríveis, você vai amar utilizar isso. Utilize!