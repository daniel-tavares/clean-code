# clean-code

## Código Ruim
  
### Caracteristicas do código ruim

  -  Classes muito longas
  -  Métodos muito longos
  -  Nomes de variáveis que seguem o padrão proprio e não um padrão mais legível.
  -  Ausência de testes unitários
  -  Métodos e atributos não agrupados e espalhados pela classe.
  ....
  
  
### Antipadrões
   É uma maneira não eficiente de fazer algo. 
   
   - **Grande bola de lama (Big boll of mud):** um sistema sem uma estrutura reconhecível.
   
   - **Ancora de barco (Boat anchor):** código dentro do sistema que não estão mais sendo mais utilizados. (comentários, depreciados..)
   
   -  **Programando por Exceção(Coding By Exception):** programação cheia de if...else inserido no código onde para cada situação é incluido um novo if...else. Quanto mais if..else mais dificil o teste.
   
   
   - **Culto a programação:(Cult programming)** quando você aprende algo e quer implementar em todos os lugares sem entender o real motivo e quando utilizar.
   
   - **Fluxo de lava (Lava Flow):** Manter código indesejável, pois a sua remoção é imprevisivel e poderá ter consequências gravíssimas; 
  
  - **Números mágicos e Strings Magicas(Magic Number e Magic String):** incluir comparações com numero ou strings inexplicáveis.
  
  - **Loops-switch-case:** utilizar switch com loops(for,while...) interno.
  
  - **Codigo Lspaguete(Spaghetti Code):** Sistemas que possuem estruturas pouco conhecidas(Há um mal uso das estruturas de código).
  
  - **Código Lasanha(Lasangna Code):** Sistemas com muitas camadas.


## Código Limpo
   É um código com alta coesão(responsabilidade separadas) e baixo acoplamento(vinculo entre as funcionalidades).

### Principios do código limpo

- **Regra do escoteiro:** Mantenha sempre o ambiente do sistema melhor do que você emcontrou. Pare de cavar "buraco".

- **KISS(Keep It Simple Stupid):** Deixar o código o mais simples e organizado, sem complexidade adicional necessária.

- **DRY (DONT' REPEAT YOUR SELF):** Não vou repetir eu mesmo, ou seja, não repita metodos, variáveis ou qualquer trecho de código repetido.

- **YAGNI(You Ain't Gonna Need It):** Se você não tem certeza que vai precisar de uma funcionalidade, remova ou não faça. Faça somente o que precisa ser feito. "Boia no deserto".

-**SoC (Separation of Concerns):** Separe as responsabilidades. "Na geladeira não pode conter produtos de higiene";






