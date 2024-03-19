# Reconhecimento Facial e Transformação de Imagens em Dados no Azure ML


Repositório do guia passo a passo desenvolvido para o desafio de Reconhecimento Facial e Conversão de Imagens em Dados no Microsoft Azure ML, realizado durante o bootcamp Microsoft Azure AI Fundamentals.

O objetivo primordial aqui consiste em extrair texto de imagens de maneira rápida e eficaz, sem a necessidade de habilidades de programação, aproveitando os recursos tecnológicos disponíveis para o reconhecimento e extração de texto de qualquer imagem, independentemente do idioma, em apenas alguns segundos.

Para alcançar esse objetivo, farei uso da visão computacional fornecida pelo Azure AI para detectar e interpretar textos incorporados em três tipos diferentes de imagens. Este método é comumente conhecido como Reconhecimento Óptico de Caracteres (OCR).

O processo será conduzido utilizando os recursos de Inteligência Artificial disponíveis no Azure, incluindo os serviços do Azure Vision Studio, a fim de explorar as possibilidades com OCR.



## 📚 Referências:
Microsoft Azure - [Soluções](https://azure.microsoft.com/pt-br/#solutions)

Read text in Vision Studio - [Microsoft Learn](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)

(OCR) Reconhecimento Óptico de Caracteres - [Microsoft Learn](https://learn.microsoft.com/pt-br/azure/azure-video-indexer/ocr)

API da Visão de IA do Azure - [Documentação](https://learn.microsoft.com/pt-br/azure/ai-services/computer-vision/)


## 🔧 Preparando o ambiente
Para enfrentar o desafio de Reconhecimento Facial e Transformação de Imagens em Dados no Microsoft Azure ML, é fundamental preparar o ambiente adequado. Isso requer uma conta configurada no portal Azure, onde será possível acessar uma interface web intuitiva para gerenciar recursos de forma eficiente. Uma vez feito esse paso vamos para a próxima etapa 🌐


## 🧩 Configurando recurso
Iniciei criando um novo recurso necessário. A configuração correta dos recursos no Azure era essencial para garantir seu funcionamento adequado, segurança, escalabilidade e otimização de custos.

Cada recurso do Azure possuí uma série de configurações que podem ser ajustadas de acordo com as necessidades e objetivos de cada negócio.

Para o meu desafio, cliquei em "Criar um recurso". Em seguida, naveguei pelo menu esquerdo, selecionando "IA + Machine Learning" e cliquei em "Criar" na opção "Serviços Cognitivos".

Depois disso, a página "Criar Serviços Cognitivos" foi carregada.

Em seguida configuerei exatamente como estava na documentação da Microsoft. ☁️


## 🗺️ Acessando o Vision Studio
Feita a devida configuração do recurso é hora de acessar o novo Azure AI - Vision Studio, essa poderosa ferramenta permite explorar, criar e integrar recursos de visão computacional do Azure em aplicativos, sem a necessidade de programação.

As possibilidades vão desde Reconhecimento de Produto por Análise de Imagem 4.0, Tokens de acesso limitado por Detecção Facil até SDK de Análise de Imagem da Visão de IA.

Para esse desafio usaremos o Reconhecimento Óptico de Caracteres, ao acessar o portal, clique em Ver todos recursos.


Na página que se abre selecione o recurso que já foi criado anteriormente e clicar no botão Select as default resource.



## 🤖 Acessando o OCR do Azure AI
Feita as configurações de recurso, do Vision Studio e o entendimento das imagens que serão usadas para input do Reconhecimento Óptico de Caracteres do Azure AI é hora de colocar a mão na massa.

Na página inicial do Vision Studio, selecione a opção Optical character recognition, após isso clique em Extract text from images como mostra o print:

![print05](https://github.com/matheusantunes-silva/Reconhecimento-Facial-e-Transforma-o-de-Imagens-em-Dados-no-Azure-ML/assets/156004284/7622770b-c7ad-4ff2-aded-b08dd8cb52ac)



Na página que se abre, habilite o Try it out e em seguida clique em Browse for a file, para selecionar a imagem que deseja usar. Como mostrado no exemplo:

![print06](https://github.com/matheusantunes-silva/Reconhecimento-Facial-e-Transforma-o-de-Imagens-em-Dados-no-Azure-ML/assets/156004284/222eac36-22c1-498a-a318-a9540fc9ad02)


🔹Logo após a imagem selecionada ser carregada, a identificação e extração de texto acontece instantaneamente.


## 🔎 Analisando os outputs
A ideia aqui foi apresentar diferentes cenários e necessidades frente a essa ferramenta que facilita a incorporação de recursos de visão computacional em IA para os mais variados segmentos.

Leitura facial
![Captura de tela 2024-03-19 153519](https://github.com/matheusantunes-silva/Reconhecimento-Facial-e-Transforma-o-de-Imagens-em-Dados-no-Azure-ML/assets/156004284/86fbe136-c205-40a2-8816-9d33e6b4888f)




Leitura de texto
![Captura de tela 2024-03-19 153609](https://github.com/matheusantunes-silva/Reconhecimento-Facial-e-Transforma-o-de-Imagens-em-Dados-no-Azure-ML/assets/156004284/e0c6c8fd-d3f2-49d1-8de7-d856844292ef)



Leitura de escrita a mão e texto
![Captura de tela 2024-03-19 153712](https://github.com/matheusantunes-silva/Reconhecimento-Facial-e-Transforma-o-de-Imagens-em-Dados-no-Azure-ML/assets/156004284/8be64af9-808a-41bc-9a5e-e617029b83f6)



## 🧠 Conclusão
O Azure OCR representa um avanço significativo na inteligência artificial, permitindo a extração precisa e rápida de texto de imagens e documentos. Com uma gama de opções de implantação e suporte para mais de 50 idiomas, incluindo texto manuscrito e impresso, sua adaptabilidade é impressionante.

Ao integrar-se a outros serviços de IA do Azure, como o Document Intelligence, o OCR oferece insights adicionais, ampliando seu valor além da mera extração de texto.

Sua flexibilidade é evidente na capacidade de processar dados de entrada de diferentes complexidades e tamanhos, oferecendo opções síncronas e assíncronas para otimizar o tempo de resposta e o consumo de recursos.

Além disso, sua capacidade de adaptação a diversas condições de imagem, juntamente com a escolha entre serviços em nuvem ou contêineres locais, destaca-se como uma solução versátil e escalável para empresas que buscam eficiência e economia de tempo.

Em suma, o Azure OCR é uma ferramenta indispensável para automatizar o processamento de documentos, agilizar o acesso e análise de informações, e oferecer flexibilidade de implantação para atender às diversas necessidades empresariais.




