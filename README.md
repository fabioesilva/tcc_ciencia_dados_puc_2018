<h3><center>TRABALHO DE CONCLUSÃO DE CURSO</center><br></h3>
<p>
No trabalho de (Moraes et al., 2011) uma das conclusões aponta “interações estatisticamente significantes entre a área de localização do domicílio e as seguintes variáveis: sexo, cor/raça, morbidade autorreferida, posse de bens básicos e percentual de domicílios adequados quanto a qualidade de moradia”. O trabalho de (Melo et al., 2019), aponta que a acurácia do auto relato é relevante para pesquisas feitas no contexto municipal do Acre. Já o trabalho (Tavares et al., 2019) aponta que “a presença de duas ou mais morbidades e a associação com variáveis so- cioeconômicas e de saúde demonstram a necessidade de ações de monitoramento e controle desses fatores entre idosos nessa condição”. Por fim, o trabalho de (Galdino, 2019) discorre sobre a relevância de analisar as condições crônicas que consome a maior parte dos recursos destinados ao tratamento destas doenças. 
</p>
<p>
A conclusão do parágrafo anterior é que as informações autorreferidas são relevantes para avaliação do cenário de custo da saúde e o trabalho de Galdino, apesar de objetivar especifcamente as internações, possui correlação com as morbidades autorreferidas. O alinhamento através do agrupamento dos capítulos do CID 10 talvez permita identificar variáveis importantes sobre o custo e sobre a prevenção das doenças evitando a quadros agudos. A ressalva é que apensar da aparente correlação entre os dados, a premissa clínica deve ser considerada e o presente trabalho foca apenas na correlação entre os dados.
A partir dessas considerações, utilizando a técnica dos 5-Ws, o presente trabalho responde as seguintes questões:
</p>
<p>
(Why?) Por que esse problema é importante? 
Porque avaliar as morbidades autorreferidas permite traçar um panorama sobre condicionantes de saúde de uma população. Além disso, cruzar morbidades autorreferidas com o custo de morbidades através pode elucidar importantes variáveis de observações para o PSF.
</p>
<p>
(Who?) De quem são os dados analisados? 
Os dados de custo das morbidades por internações são de origem do SUS. E os dados de morbidades autorreferidas foram gerados a partir do modelo de informação do PSF
</p>
<p>
(What?): Quais os objetivos com essa análise?
Traçar um panorama das informações e suas correlações e avaliar o modelo de dados proposto pelo Sistema Único de Saúde (SUS) para o Programa de saúde da família (PSF) e identificar variáveis que sejam relevantes para a criação de modelos de Machine Learn (ML).
</p>
<p>
(When?): Qual o período está sendo analisado? 
Os dados de custo das morbidades por internações são de origem do SUS são do período de 2016 a 2017. E os dados de morbidades autorreferidas foram gerados a partir do modelo de informação do PSF é uma base de desenvolvimento e a data de coleta não é relevante 


   
<h3>Processamento/Tratamento de Dados</h3><br>
<p>
A ferramenta escolhida para o processamento de dados foi o python (Python, n.d.) na versão jupyter/datascience-notebook:latest, disponível em (Docker Hub, n.d.). Os fontes do projeto foram publicados no controlador de versão github. Para facilitar a montagem do ambiente, foi utilizada a estratégia de container através da ferramenta Docker disponível em (Docker, n.d.). Explicando de forma simplificada, o Docker cria um ambiente operacional com os requisitos específicos e mínimos para execução de um determinado ambiente. A estrutura do projeto tem as seguintes pastas:
</p>    

* **dataset:** contém os datasets utilizados disponível em https://drive.google.com/drive/folders/10AvFcaHCenNWJMeaXLyNpiQ9H6NWczae?usp=sharing
* **docker_jupyter:** contém os arquivos de configuração do ambiente;
* **fontes:** contém os arquivos de codificação;

<p>
Para criar o mesmo ambiente utilizado no projeto é preciso instalar o Docker; no Windows deve-se instalar o Docker Desktop e no Linux baixar e instalar o Docker em acordo com a distribuição. Com o Docker instalado, deve-se acessar a pasta docker_jupyter do projeto e executar o comando “docker-compose up -d --build”. Após o término da montagem do ambiente executada pelo comando de build, basta abrir o browser e digitar a ULR http://127.0.0.1:8888/ para executar o Jupyter.
</p>
