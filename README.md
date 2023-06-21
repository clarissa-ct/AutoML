INTRODUÇÃO AO AUTOML: ARTIGOS RELEVANTES

Neste documento do GitHub, você encontrará uma coletânea de links para artigos relacionados ao AutoML (Aprendizado de Máquina Automatizado). O AutoML tem se destacado como uma abordagem promissora para simplificar e agilizar o processo de desenvolvimento de modelos de aprendizado de máquina. Ele capacita usuários com diferentes níveis de conhecimento técnico a aproveitar os benefícios do aprendizado de máquina sem exigir um profundo conhecimento em ciência de dados ou programação.

Os artigos selecionados abrangem diversos aspectos do AutoML, incluindo conceitos fundamentais, técnicas e ferramentas relevantes. Essa variedade de recursos visa fornecer uma visão ampla sobre o tema e permitir que você aprofunde seu conhecimento em áreas específicas, conforme necessário. 

1° Seção - VISÃO GERAL DO AUTOML

Nessa seção os artigos abordam assuntos referentes à introdução ao AutoML, como seus princípios básicos, sua finalidade e como ele se enquadra no contexto de aprendizagem de máquina. Os artigos citados abaixo são recomendados para quem está começando a explorar o assunto. 


-  AUTOMATED MACHINE LEARNING: STATE-OF-THE-ART AND OPEN CHALLENGES

link: https://arxiv.org/abs/1906.02287

Resumo:

Este artigo é sobre a automatização do processo de construção de modelos de aprendizado de máquina de alta qualidade. Atualmente, o uso de técnicas e algoritmos de aprendizado de máquina é predominante em vários campos, como finanças, publicidade, sistemas de recomendação e análise de comportamento do usuário. No entanto, construir efetivamente esses modelos é um processo complexo e demorado que requer experimentação com diferentes algoritmos e técnicas, além de ajustar os hiperparâmetros de acordo.

Ao automatizar o processo de construção de modelos de aprendizado de máquina, é possível lidar com a grande quantidade de dados disponíveis atualmente e permitir que usuários sem conhecimento especializado usem essas técnicas de maneira eficaz. Isso permite aplicações mais amplas e acessíveis de aprendizado de máquina em setores e domínios.

Frameworks abordados nesse artigo:

1- AutoWeka

2- AutoSklearn

3- TPOT

4- SmartML

5- Auto-MEKAGGP

6- Recipe

7- MLPlan

8- Hyperopt-sklearn

9- Autostacker

10- VDS

11- AlphaD3M

12- OBOE

13- PMF


- AUTOML IN THE WILD: OBSTACLES, WORKAROUNDS, AND EXPECTATIONS

link: https://dl.acm.org/doi/abs/10.1145/3544548.3581082

Resumo:

Este artigo tem como objetivo analisar como os usuários adotam e utilizam soluções de machine learning automatizado (AutoML) em situações do mundo real. A pesquisa foi realizada por meio de entrevistas com usuários do AutoML, que exploraram as limitações que encontraram, as estratégias que adotaram para lidar com elas, o impacto dessas limitações e soluções alternativas ao usar o AutoML.

Os resultados mostram que os usuários desempenham um papel ativo na superação de desafios relacionados à personalização, transparência e privacidade no AutoML. Eles tomam decisões cuidadosas sobre quando e como aplicar o AutoML em diferentes situações. Com base nessas descobertas, são propostas implicações de design para o desenvolvimento de futuras soluções de AutoML.

Esse artigo não aborda frameworks específicos.


- THE AUTOML JUNGLE-AN OVERVIEW 

link: https://oparu.uni-ulm.de/xmlui/handle/123456789/38670

Resumo: 

Este artigo apresenta uma visão abrangente de vários frameworks e ferramentas que foram implementados para automatizar o pipeline de aprendizagem de máquina. O objetivo deste trabalho é explicar os fundamentos da aprendizagem de máquina, o método de funcionamento do AutoML e fornecer uma visão geral dos frameworks e ferramentas atuais, suas vantagens e desvantagens.

Frameworks abordados nesse artigo:

1-  Scikit-learn

2-  Auto_ml

3- Tree-Based Pipeline Optimization Tool (TPOT)

4- AlphaD3M 

5- Hyperopt-Sklearn

6- H2O

7- Auto-sklearn 

8- Amazon SageMaker Autopilot


- BENCHMARK AND SURVEY OF AUTOMATED MACHINE LEARNING FRAMEWORKS

link: https://arxiv.org/abs/1904.12054

Resumo:

Este artigo combina pesquisa e avaliação de estruturas de aprendizado de máquina automatizado (AutoML) e seu desempenho em conjuntos de dados do mundo real. O objetivo principal é analisar os métodos atuais do AutoML e comparar diferentes estruturas populares.

Além disso, avaliamos as estruturas AutoML selecionadas usando 137 conjuntos de dados derivados de conjuntos de referência estabelecidos. Essa avaliação permite comparar o desempenho dos frameworks em termos de eficácia e eficiência na construção de modelos de aprendizado de máquina.

Frameworks abordados nesse artigo:

1- Dummy

2- Random Forest

3- TPOT

4- hpsklearn

5- auto-sklearn

6- Random Search

7- ATM

8- H2O AutoML


- AUTOML: A SURVEY OF THE STATE-OF-THE-ART

link: https://www.sciencedirect.com/science/article/abs/pii/S0950705120307516

Resumo:

Este artigo apresenta uma revisão abrangente e atualizada do aprendizado de máquina automatizado (AutoML) de última geração, com foco especial em técnicas de aprendizado profundo (DL). Ele explora como usar o AutoML para criar sistemas de aprendizado profundo sem depender muito da experiência humana.

Este artigo aborda as diferentes etapas do pipeline DL, como preparação de dados, engenharia de recursos, otimização de hiperparâmetros e extração de arquitetura neural (NAS). Em particular, ele se concentra especificamente em NAS, um tópico importante no AutoML.

Além disso, o artigo também resume o desempenho dos algoritmos NAS em conjuntos de dados populares, como CIFAR-10 e ImageNet.
Finalmente, algumas questões não resolvidas e desafios relacionados aos métodos AutoML existentes são discutidos, com o objetivo de orientar pesquisas futuras neste campo.

Esse artigo não aborda frameworks específicos.


2ª Seção - ABORDAGEM BAYESIANA NA OBTENÇÃO DE PESOS PARA ESCALARIZAÇÃO EM OTIMIZAÇÃO MULTIOBJETIVO

Nesta seção, você verá artigos relacionados à abordagem bayesiana na obtenção dos pesos da função de escalarização, que é uma técnica promissora na otimização multiobjetivo. Essa abordagem utiliza métodos estatísticos baseados em processos de aprendizagem para inferir os pesos adequados, considerando a incerteza e as preferências do tomador de decisão.


- A BAYESIAN APPROACH TO CONSTRAINED SINGLEAND MULTI-OBJECTIVE OPTIMIZATION 

link: https://link.springer.com/article/10.1007/s10898-016-0427-3 


Este artigo aborda o problema da otimização sem derivadas (mono ou multiobjetivo) sujeita a múltiplas restrições de desigualdade. Tanto as funções objetivo quanto as funções de restrição são assumidas como suaves, não lineares e custosas para avaliar. Como consequência, o número de avaliações que podem ser utilizadas para realizar a otimização é muito limitado, como em problemas complexos de otimização de design industrial. O método proposto para superar essa dificuldade tem suas raízes tanto na literatura de otimização bayesiana quanto na de otimização multiobjetivo. Mais especificamente, é utilizada uma regra de dominação estendida para lidar com objetivos e restrições de forma unificada, e é proposto um critério de amostragem correspondente de melhoria esperada do hiper-volume. Esse novo critério é naturalmente adaptado para a busca de um ponto viável quando nenhum está disponível e reduz-se a critérios de amostragem bayesianos existentes - o critério clássico de Melhoria Esperada (EI) e algumas de suas extensões para restrições/multiobjetivo - assim que pelo menos um ponto viável estiver disponível. O cálculo e a otimização do critério são realizados utilizando técnicas de Monte Carlo sequenciais. Em particular, é utilizado um algoritmo semelhante ao método de simulação de subconjuntos, bem conhecido no campo de confiabilidade estrutural, para estimar o critério. O método, chamado BMOO (para Bayesian Multi-Objective Optimization), é comparado a algoritmos de ponta para otimização com restrições mono e multiobjetivo.


- BAYESIAN OPTIMIZATION FOR MULTI-OBJECTIVE OPTIMIZATION AND MULTI-POINT SEARCH

link: https://arxiv.org/abs/1905.02370 


Este artigo aborda o tema da otimização bayesiana, que é um método eficaz para otimizar funções objetivo desconhecidas com altos custos de avaliação. Normalmente, os algoritmos de otimização bayesiana selecionam um ponto por iteração para funções objetivo únicas. No entanto, nos últimos anos, foram propostas abordagens de otimização bayesiana para otimização multiobjetivo ou busca de vários pontos por iteração. No entanto, até o momento, não se conhece uma abordagem bayesiana de otimização que possa lidar com ambos os casos simultaneamente, de forma não heurística. Neste artigo, é proposto um algoritmo de otimização bayesiana que pode lidar com a otimização multiobjetivo e a busca de múltiplos pontos ao mesmo tempo. Primeiramente, é definida uma função de aquisição que considera tanto a otimização multiobjetivo quanto a busca de múltiplos pontos. É difícil maximizar analiticamente essa função de aquisição, pois o custo computacional é proibitivo, mesmo quando são realizados cálculos aproximados, como a aproximação por amostragem. Portanto, é proposto um método preciso e computacionalmente eficiente para estimar o gradiente da função de aquisição, e é desenvolvido um algoritmo para a otimização bayesiana com otimização multiobjetivo e busca de múltiplos pontos. Experimentos numéricos mostram que o desempenho do método proposto é comparável ou superior ao de métodos heurísticos existentes.


- AN ADAPTIVE BAYESIAN APPROACH TO SURROGATE-ASSISTED EVOLUTIONARY MULTI-OBJECTIVE OPTIMIZATION

link: https://www.sciencedirect.com/science/article/pii/S0020025520300591 


Este artigo aborda o uso de modelos substitutos para resolver problemas de otimização multiobjetivo (MOPs) com alta carga computacional. O algoritmo de otimização global eficiente (EGO), uma abordagem bayesiana para otimização assistida por modelos substitutos, tem se tornado muito popular na otimização evolutiva assistida por modelos substitutos. Neste artigo, é proposta uma abordagem bayesiana adaptativa para algoritmo evolutivo assistido por modelos substitutos para resolver MOPs com alto custo computacional. A ideia principal é ajustar o hiperparâmetro na função de aquisição de acordo com a dinâmica da busca para determinar quais soluções candidatas devem ser avaliadas usando as caras funções objetivo reais. Além disso, o critério de seleção de amostragem alterna entre uma distância baseada em ângulo e uma distância penalizada por ângulo ao longo da otimização para alcançar um melhor equilíbrio entre exploração e explotação. O desempenho do algoritmo proposto é avaliado em um conjunto de problemas de referência e um problema de otimização de aerofólio usando no máximo 300 avaliações reais de aptidão. Os resultados experimentais mostram que o algoritmo proposto é competitivo em comparação com quatro algoritmos evolutivos multiobjetivo populares


- SCALARIZING FUNCTIONS IN BAYESIAN MULTIOBJECTIVE OPTIMIZATIONS

link: https://arxiv.org/pdf/1904.05760.pdf 


O principal objetivo deste artigo é estudar e revisar o uso de diferentes funções de escalarização no contexto da otimização multiobjetivo bayesiana. As funções de escalarização são amplamente utilizadas para converter um problema de otimização multiobjetivo em um problema de otimização de único objetivo. No entanto, seu uso na resolução de problemas de otimização multiobjetivo (computacionalmente) caros e com muitos objetivos é escasso. Essas funções podem desempenhar um papel crucial na qualidade e no número de avaliações necessárias durante a otimização. Neste artigo, são estudadas e revisadas 15 funções de escalarização diferentes, e são construídos modelos de processo gaussiano (como modelos substitutos, metamodelos ou emuladores) para representá-las. A função de melhoria esperada é utilizada como critério de aquisição para atualizar os modelos. Em particular, são comparadas diferentes funções de escalarização e é analisado o desempenho delas em vários problemas de referência com diferentes números de objetivos a serem otimizados. A revisão e os experimentos com diferentes funções fornecem insights úteis para a seleção e uso de uma função de escalarização em métodos de otimização multiobjetivo bayesiana.
