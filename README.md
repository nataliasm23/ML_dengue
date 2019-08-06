# ML_dengue
Modelo desenhado para prever dengue dado informações prévias
Dengue
Introdução ao Python
Matheus Lima 20501201
Natália Mesquita 21341077
Paolo Zilioti 21299940
São Paulo , 27 Julho 2019
Histórico da Doença
A dengue é uma doença febril aguda causada por um vírus, sendo um dos principais problemas
de saúde pública no mundo. É transmitida pelo mosquito Aedes aegypti , que se desenvolve em
áreas tropicais e subtropicais.
Segundo o boletim epidemiológico do Ministério da Saúde, divulgado em janeiro de 2018, foram
registrados menos casos prováveis de em 2017, 252.054 casos contra 1.483.623 em 2016.
A Organização Mundial da Saúde (OMS) estima que entre 50 a 100 milhões de pessoas se
infectam anualmente com a dengue em mais de 100 países de todos os continentes, exceto a
Europa. Cerca de 550 mil doentes necessitam de hospitalização e 20 mil morrem em
consequência da dengue.
Existem quatro tipos de dengue, de acordo com os quatro sorotipos: DEN-1, DEN-2, DEN-3 e
DEN-4. Quando uma pessoa tem dengue, tem uma imunidade relativa contra outro sorotipo.
É uma doença potencialmente grave porque pode evoluir para a dengue hemorrágica, a
síndrome do choque da dengue, caracterizadas por sangramento e queda de pressão arterial, o
que eleva o risco de morte. A melhor maneira de combater esse mal é atuando de forma
preventiva, impedindo a reprodução do mosquito.
Sintomas
Os sintomas de dengue iniciam de uma hora para outra e duram entre cinco a sete dias.
Normalmente eles surgem entre três a quinze dias após a picada pelo mosquito infectado. Os
principais sinais são:
● Febre alta com início súbito (entre 39º a 40º C)
● Forte dor de cabeça
● Dor atrás dos olhos, que piora com o movimento dos mesmos
● Manchas e erupções na pele, pelo corpo todo, normalmente com coceiras
● Extremo cansaço
1
● Moleza e dor no corpo
● Muitas dores nos ossos e articulações
● Náuseas e vômitos
● Tontura
● Perda de apetite e paladar.
Prevenção
A vacina contra dengue foi criada para prevenir a manifestação do vírus. Ela possui a
estrutura do vírus vacinal da febre amarela, o que lhe dá mais estabilidade e segurança. A
eficácia na população acima de 9 anos é de, aproximadamente, 66% contra os quatro sorotipos
de vírus da dengue. Isso significa que em um grupo de cem pessoas, 66 evitariam contrair a
doença. Além disso, reduz os casos graves - aqueles que levam ao óbito, como a dengue
hemorrágica - em 93% e os índices de hospitalizações em 80%.
Além da vacina, é importante também tomar os seguintes cuidados:
● Evitar o acumulo de água
● Colocar tela nas janelas
● Colocar areia nos vasos de planta
● Colocar desinfetante nos ralos
● Usar repelente
Como contrair
A dengue não é transmitida de pessoa para pessoa. A transmissão se dá pelo mosquito
que, após um período de 10 a 14 dias contados depois de picar alguém contaminado, pode
transportar o vírus da dengue durante toda a sua vida.
O ciclo de transmissão ocorre do seguinte modo: a fêmea do mosquito deposita seus
ovos em recipientes com água. Ao saírem dos ovos, as larvas vivem na água por cerca de uma
semana. Após este período, transformam-se em mosquitos adultos, prontos para picar as
pessoas. O Aedes aegypti procria em velocidade prodigiosa e o mosquito da dengue adulto vive
em média 45 dias. Uma vez que o indivíduo é picado, demora no geral de três a 15 dias para a
doença se manifestar, sendo mais comum cinco a seis dias.
2
A transmissão da dengue raramente ocorre em temperaturas abaixo de 16° C, sendo que
a mais propícia gira em torno de 30° a 32° C - por isso o mosquito se desenvolve em áreas
tropicais e subtropicais. A fêmea coloca os ovos em condições adequadas (lugar quente e
úmido) e em 48 horas o embrião se desenvolve. É importante lembrar que os ovos que carregam
o embrião do mosquito da dengue podem suportar até um ano a seca e serem transportados por
longas distâncias, grudados nas bordas dos recipientes. Essa é uma das razões para a difícil
erradicação do mosquito. Para passar da fase do ovo até a fase adulta, o inseto demora dez dias,
em média. Os mosquitos acasalam no primeiro ou no segundo dia após se tornarem adultos.
Depois, as fêmeas passam a se alimentar de sangue, que possui as proteínas necessárias para o
desenvolvimento dos ovos.
Além do contato com o mosquito, os fatores elencados abaixo também contribuem com
o risco de contrair a doença:
Vivendo ou viajando em áreas tropicais
Infecção prévia com um vírus da dengue
Quais exames identificam a dengue?
O paciente que desconfia de ter ou não contraído a doença deve realizar tais exames e
verificar se os níveis medidos estão no intervalo de níveis considerados normais pela literatura.
● Testes de coagulação
● Eletrólitos (sódio e potássio)
● Hematócrito
● Enzimas do fígado (TGO, TGP)
● Contagem de plaquetas
● Testes sorológicos (mostram os anticorpos ao vírus da dengue)
● Raio X do tórax para demonstrar efusões pleurais.
3
Para o diagnóstico é necessário considerar tais sintomas e exames para modelar nosso
problema, conforme tabela abaixo:
Exame Pessoa Saudável Pessoa Doente Descrição
Testes de
coagulação (TC)
Negativo Positivo T empo de
coagulação
Eletrólitos (E) >120 mEq/l <=120 mEq/l Quantidade de
sódio no sangue
Hematócrito (H) <=55% >55% Volume de
hemácias no
sangue
TGO <131 UI/dl >131 UI/dl Enzimas do
fígado que
indicam lesão
TGP
<99 UI/dl >99 UI/dl Enzimas do
fígado que
indicam lesão
4
Contagem de
plaquetas (C)
entre 150 e
450 mil
plaquetas
Abaixo de 150
mil
Responsáveis pela
coagulação do
sangue. Os
anticorpos da
dengue podem
destruir as
plaquetas
Testes sorológicos
(TS)
Baixo nível de
anticorpos
Alto nível de
anticorpos
Mostram os
anticorpos ao
vírus da
dengue
Raio X do tórax
(RX)
Sem efusão com efusão Raio X para
demonstrar
efusões
pleurais.
A combinação dos sintomas com os resultados dos exames conclui se o paciente está infectado.
Portanto a tabela de sintomas será utilizada :
Sintoma Pessoa Saudável Pessoa Doente
Febre (F) Sem febre Entre 39º e 40º
5
Dor de cabeça (DC) Sem dor de cabeça Alta
Dor nos olhos (DO) Sem dor Com dor
Mancha na pele (M) Sem mancha Com mancha
Extremo cansaço
(EC)
Sem cansaço Com cansaço
Moleza e dor no
corpo (MC)
Não apresenta Apresenta
Dor no ossos e
articulações (DA)
Não apresenta Apresenta
Náuseas e vômitos
(NV)
Não apresenta Apresenta
Tontura (T) Não apresenta Apresenta
6
Perda de apetite (P) Não apresenta Apresenta
Modelo
Para sucesso sigla S, , bem como o s = 1 fracasso da sigla s = 0
D = [Exame] + [Sintomas]
D = (TC +E + 3*H +2*TGO+ 2*TGP+ 3*C+ TS + 1,5*Rx) +
(F + DC + DO + M + EC + MC + DA+ NV + T + P)
Para definir um Dcritico atribuímos a situação em que a soma dos exames com pesos maiores
que 1 mais 6 sintomas quaisquer. Portanto Dcrítico = 17
D = (TC +E + 3*(H=1) +2*TGO)+ 2*TGP+ 3*C+ TS + 1,5*Rx) + (F + DC + DO + M + EC + MC + DA+ NV
+ T + P)
7
Conclusão
A amostra tem aproximadamente metade dos pacientes com doença e metade sem doença
para fins de treinar bem o modelo de forma balanceada.
Utilizamos os classificadores de árvores de decisão e Naive Bayes da biblioteca e scikit learn
para treinar os dados e avaliamos que o modelo de Árvore de decisões teve um acerto de 95%
enquanto o classificador de Naive Bayes obteve 75%. Portanto o classificador de árvore de
decisão é o mais adequado para o estudo.
Bibliografia
https://www.minhavida.com.br/saude/temas/dengue
8
9
