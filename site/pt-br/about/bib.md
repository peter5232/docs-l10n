# Documentação Oficial TensorFlow

Esse artigo reconhece os documentos oficiais sobre o TensorFlow.

## Aprendizado-de-Máquina de Alta Escalabilidade em Sistemas Heterogêneos Distribuídos.

<a class="" href="https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45166.pdf">Acesse esse Artigo em inglês.</a>

**Resumo:** TensorFlow é uma interface para expressão de algoritmos de aprendizado de máquina e sua implementação para execução desses algoritmos. Uma computação expressada usando o TensorFlow pode ser executada com pouco ou nenhuma alteração em uma ampla variedade de sistemas heterogêneos, desde de dispositivos móveis como telefones e tablets até sistemas distribuídos de larga escala com centenas de máquinas e milhares de dispositivos computacionais como placas gráficas GPU. O sistema é flexível e pode ser usado para expressar uma ampla variedade de algoritmos, incluindo os de treinamento e inferência para modelos de redes neurais profundas, e tem sido utilizado para condução de pesquisa e para implementação de sistemas de aprendizado de máquina em produção em mais de uma dúzia de áreas das ciências da computação e outros campos, que incluem reconhecimento de fala, visão computacional, robótica, recuperação de informação, processamento de linguagem natural, extração de informação geográfica e descoberta computacional de drogas farmacológicas. Essa documentação descreve a interface do TensorFlow e a implementação da interface que construímos na Google. A API do TensorFlow e a implementação de referência estão disponibilizadas como pacote de código-aberto sob a licença Apache 2.0 de Novembro, 2015 e está disponível no www.tensorflow.org.

### No formato BibTeX

Se você utiliza o TensorFlow na sua pesquisa acadêmica e quer citar o sistema TensorFlow, nós sugerimos que cite esse documento.

<pre>@misc{tensorflow2015-whitepaper,<br>title={ {TensorFlow}: Large-Scale Machine Learning on Heterogeneous Systems},<br>url={https://www.tensorflow.org/},<br>note={Software available from tensorflow.org},<br>author={<br>    Mart\'{\i}n~Abadi and<br>    Ashish~Agarwal and<br>    Paul~Barham and<br>    Eugene~Brevdo and<br>    Zhifeng~Chen and<br>    Craig~Citro and<br>    Greg~S.~Corrado and<br>    Andy~Davis and<br>    Jeffrey~Dean and<br>    Matthieu~Devin and<br>    Sanjay~Ghemawat and<br>    Ian~Goodfellow and<br>    Andrew~Harp and<br>    Geoffrey~Irving and<br>    Michael~Isard and<br>    Yangqing Jia and<br>    Rafal~Jozefowicz and<br>    Lukasz~Kaiser and<br>    Manjunath~Kudlur and<br>    Josh~Levenberg and<br>    Dandelion~Man\'{e} and<br>    Rajat~Monga and<br>    Sherry~Moore and<br>    Derek~Murray and<br>    Chris~Olah and<br>    Mike~Schuster and<br>    Jonathon~Shlens and<br>    Benoit~Steiner and<br>    Ilya~Sutskever and<br>    Kunal~Talwar and<br>    Paul~Tucker and<br>    Vincent~Vanhoucke and<br>    Vijay~Vasudevan and<br>    Fernanda~Vi\'{e}gas and<br>    Oriol~Vinyals and<br>    Pete~Warden and<br>    Martin~Wattenberg and<br>    Martin~Wicke and<br>    Yuan~Yu and<br>    Xiaoqiang~Zheng},<br>  year={2015},<br>}</pre>

Ou em sua forma textual:

<pre>Martín Abadi, Ashish Agarwal, Paul Barham, Eugene Brevdo,<br>Zhifeng Chen, Craig Citro, Greg S. Corrado, Andy Davis,<br>Jeffrey Dean, Matthieu Devin, Sanjay Ghemawat, Ian Goodfellow,<br>Andrew Harp, Geoffrey Irving, Michael Isard, Rafal Jozefowicz, Yangqing Jia,<br>Lukasz Kaiser, Manjunath Kudlur, Josh Levenberg, Dan Mané, Mike Schuster,<br>Rajat Monga, Sherry Moore, Derek Murray, Chris Olah, Jonathon Shlens,<br>Benoit Steiner, Ilya Sutskever, Kunal Talwar, Paul Tucker,<br>Vincent Vanhoucke, Vijay Vasudevan, Fernanda Viégas,<br>Oriol Vinyals, Pete Warden, Martin Wattenberg, Martin Wicke,<br>Yuan Yu, and Xiaoqiang Zheng.<br>TensorFlow: Large-scale machine learning on heterogeneous systems,<br>2015. Software available from tensorflow.org.</pre>

## TensorFlow: Um sistema para Aprendizado de Máquina de Larga Escala

<a class="" href="https://www.usenix.org/system/files/conference/osdi16/osdi16-abadi.pdf">Acesse esse Artigo em inglês.</a>

**Resumo:** TensorFlow é um sistema de aprendizado de máquina que opera em larga escala e em ambiente heterogêneos. TensorFlow utiliza grafos com fluxos de dados para representar computacionalmente, um estado compartilhado e as operações que alteram esse estado. O TensorFlow mapeia os nós de grafo de fluxo de dados através de muitas máquinas em grupo e com máquinas em múltiplos dispositivos computacionais, incluindo CPUs com muitos núcleos, placas de vídeos comuns e projetos customizados ASICs, conhecidos por Tensor Processing Units (TPUs). Essa arquitetura dá flexibilidade para o desenvolvedor da aplicação: considerando que nas arquiteturas de “servidores parametrizados” anteriores o gerenciamento de estado compartilhado seja nativo do sistema, TensorFlow permite que desenvolvedores experimentem novas otimizações e algoritmos de treinamento. TensorFlow oferece uma variedade de aplicações com foco no treinamento e inferência com redes neurais profundas. Vários serviços da Google utilizam o TensorFlow em produção, nós temos implementado o como projeto de código aberto e tem se tornado vastamente utilizado para pesquisa com aprendizado de máquina. Nesse artigo, nós descrevemos o modelo de fluxo de dados do TensorFlow e demonstramos o convincente desempenho que o TensorFlow alcança em diversos aplicações no mundo real.