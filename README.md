
# Desafio Final Imersão Dados

![imagem](https://github.com/vqrca/imersao-dados-desafio-final/blob/main/image2.jpg)

---

**Um pouco sobre mim**

Sou bióloga e tenho Doutorado em Biotecnologia pela Universidade de Mogi das Cruzes. Atuo na área de Microbiologia, com ênfase em Biologia Molecular e Genômica. Possuo conhecimentos sólidos das técnicas comumente empregadas em genômica estrutural e genômica funcional. Atualmente, sou Pesquisadora Colaboradora no programa de Biossistemas da Universidade Federal do ABC.

---

**Onde encontrar meu trabalho?**

[LinkedIn](https://www.linkedin.com/in/valqu%C3%ADria-alencar-786a8911b/)

[ResearchGate](https://www.researchgate.net/profile/Valquiria-Alencar)

[Currículo lattes](http://lattes.cnpq.br/7742338443535710)

---

**Projeto**

Drug discovery - Análise de dados e predição de mecanismos de ação 


**Descrição**

Esse projeto foi inspirado em um desafio do *Laboratory Innovation Science at Harvard*, que disponibilizou os dados em uma competição no *Kaggle*.
O monitoramento da expressão gênica por meio de abordagens de transcriptômica (perfil de RNA) tornou-se uma ferramenta extremamente relevante em esforços para compreender processos biológicos complexos. A análise de resultados provenientes deste tipo de abordagem permite a seleção de potenciais alvos de medicamentos e o perfil da expressão gênica provavelmente desempenhará um papel cada vez mais importante na descoberta de medicamentos.

A descoberta de medicamentos evoluiu da identificação de substâncias ativas em medicamentos tradicionais para a busca direta por novos medicamentos utilizando os alvos moleculares específicos e seus mecanismos de ação *(Mechanisms of Action - MoA)*. 
Portanto, esse projeto permitirá a predição de mecanismos de ação das drogas contidas no dataset que combina a expressão gênica e os dados de viabilidade celular. 



**Ojetivo do projeto**

- Avaliar a ação de drogas em relação aos valores expressão gênica de diversos genes 

- Determinar os mecanismos de ação das drogas

**Estrutura dos dados**

Neste desafio, temos dados dois arquivos .csv (*dados_experimentos* e *dados_resultados*), que estão estruturados da seguinte forma:

*dados_experimentos*

- IDs de cada experimento;
- A informação se houve tratamento com alguma droga ou se a amostra é um controle. Lembrando que todo desenho experimental precisa conter amostras chamadas controles, onde não houve tratamento, para ser possível analisar apenas uma variável: a ação da droga;
- Tempo do experimento: 24, 48 ou 72 horas;
- Dosagem das drogas:  denominadas como D1 ou D2;
- Colunas com todos genes analisados e seus respectivos valores de expressão: g-0 até g-771;
- Colunas com diferentes células testadas e seus respectivos valores de viabilidade celular: c-0 até c-99.
 
*dados_resultados*

- IDs de cada experimento;
- Colunas contendo o mecanismo de ação para determinados alvos, que podem ativar ou bloquear receptores celulares.

**Referências utilizadas para a conclusão do projeto**

Bates, S. The role of gene expression profiling in drug discovery. Current Opinion in Pharmacology, 2011, 11(5), 549–556. https://doi.org/10.1016/j.coph.2011.06.009 

Corsello *et al.* Discovering the anticancer potential of non-oncology drugs by systematic viability profiling, Nature Cancer, 2020, https://doi.org/10.1038/s43018-019-0018-6

Davis, R. L. Mechanism of Action and Target Identification: A Matter of Timing in Drug Discovery. Science, 2020, 23(9), 101487. https://doi.org/10.1016/j.isci.2020.101487

Subramanian *et al.* A Next Generation Connectivity Map: L1000 Platform and the First 1,000,000 Profiles, Cell, 2017, https://doi.org/10.1016/j.cell.2017.10.049

