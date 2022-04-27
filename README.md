# `Síntese de MicroRNA em Pacientes com Aterosclerose`
# `MicroRNA Syntesis in Patients with Atherosclerosis `

## Apresentação
O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação *IA376L - Deep Learning aplicado a Síntese de Sinais*, 
oferecida no primeiro semestre de 2022, na Unicamp, sob supervisão da Profa. Dra. Paula Dornhofer Paro Costa, do Departamento de Engenharia de Computação e Automação (DCA) da Faculdade de Engenharia Elétrica e de Computação (FEEC).

> |Nome  | RA | Especialização|
> |--|--|--|
> | Renan Yamaguti | 262731  | Msc. Eng. de Computação|



## Descrição Resumida do Projeto
> A aterosclerose é uma doença muito comum no Brasil, com sintomas silenciosos e que causa insuficiência cardíaca. Essa doença possui causas comportamentais (como obesidade, pressão alta e sedentarismo) e causas genéticas, hereditárias. Um método de avaliação sendo pesquisado hoje em dia é a análise da relação de microRNA (pequenos treços de RNA que modulam uma via genética) com a formação da placa carotídica. A técnica de extração de microRNA é bem custosa financeiramente, além do falecimento dos pacientes, dificultando a obtenção de novos dados e o acompanhamento desses pacientes. 
> 
> Como uma possível solução para esse problema, esse projeto vai tentar gerar novos pacientes artificiais utilizando GANs e algoritmos baseados em Flow para enriquecer os estudos na área, identificar novos padrões e prever a evolução da doença. Esse modelo generativo vai:
> 
> 1 - receber um número n arbritário de pacientes a ser gerado e algumas variáveis pré definidas (Sexo/idade/hipertensão/etc), retornando assim esse conjunto de n novos pacientes artificiais que contém as mesmas características estatísticas que o grupo anterior;
> 
> 2 - ao receber um número n de anos, prever a evolução da doença nesse paciente.

> VÍDEO

## Metodologia Proposta
> Base de dados: Dados Tabulares colidos no HC da Unicamp em parceria com o Laboratório Cardiovascular da FCM
> 
> Abordagens generativas: GANs e Flow, para gerar novos dados e gerar um dado futuro
> 
> Artigos de referência: Xu, Lei. Synthesizing tabular data using conditional GAN. Diss. Massachusetts Institute of Technology, 2020. + Yale, Andrew, et al. "Generation and evaluation of privacy preserving synthetic health data." Neurocomputing 416 (2020): 244-255. 
> 
> Ferramentas: Python e bibliotecas de Deep learning
> 
> Resultado esperado: Algoritmo generativo que consiga gerar novos pacientes e gerar uma evolução do paciente
> 
> Proposta de Avaliação: Kolmogorov-Smirnov, Chi-squared, Nearest Neighbor Adversarial Accuracy 

## Cronograma
> Proposta de Cronograma: 
> 
> 04/05 - Coleta de dados
> 
> 11/05 - Ocultação e Análise estatística dos dados
> 
> 18/05 - Criação dos primeiros testes de algoritmo
> 
> 25/05 - Algoritmo generador de pacientes
> 
> 01/05 - Algortimo generador de previsão 
> 
> 04/06 - Entrega dos algoritmos
> 
> 06/06 - Apresentação 
> 

## Referências Bibliográficas
> Minin, Eduarda OZ, et al. "Association of Circulating miR-145-5p and miR-let7c and Atherosclerotic Plaques in Hypertensive Patients." Biomolecules 11.12 (2021): 1840.
> 
> Xu, Lei. Synthesizing tabular data using conditional GAN. Diss. Massachusetts Institute of Technology, 2020.
> 
> Lee, Jaewoo, et al. "Differentially Private Normalizing Flows for Synthetic Tabular Data Generation." (2022).
> 
> Yale, Andrew, et al. "Generation and evaluation of privacy preserving synthetic health data." Neurocomputing 416 (2020): 244-255.
