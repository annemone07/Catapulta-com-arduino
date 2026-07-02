//PT-BR//

Esse projeto foi desenvolvido por alunos de graduação do primeiro período em Engenharia da Computação do CIn - UFPE. Abaixo estão alguns comentários e observações para aqueles que se interessarem em replicar o projeto.


//PEÇAS//
As peças da montagem já estão nos arquivos para impressão/corte à laser. Todas as peças de impressão foram feitas com PLA e preenchimento de giroide. Todas as peças, exceto a barra lateral, foram impressas com densidade de 15%. Já a barra lateral foi impressa com densidade 20% e "em pé" para aumentar a resistência mecânica. Diversas partes foram lixadas em momentos da montagem, sendo recomendado o seu uso para facilitar o encaixe e a movimentação mecânica(podendo ser feito de modo manual ou com micro retifica). A alavanca foi cortada em acrílico com espessura de 3mm.

//ENCAIXES//
Para os parafusos que não são dos servos, foi utilizado a base de M3. É recomendado, para a fixação das partes que vão diretamente nos servos(alavanca do elástico e base superior) o uso de cola super bonder, utilizando os buracos como referência. A alavanca possui 4 buracos, distando 5, 4, 3 e 2 cm do centro da mesma, a depender da voltagem de operação e elástico utilizado, sendo relevante realizar tais análises de antemão para não perder alguma peça. Existe um buraco para fixação do cilindro na catapulta, porém não se tornou necessário na execução feita, servindo como ponto de referência para o alinhamento. Partes que eventualmente estejam mal presas podem ser melhor fixadas utilizando super bonder. O elástico utilizado não possuí especificações bem determinadas, sendo relevante o teste e busca de opções.

//COMPONENTES//

2x Botão

2x Micro Servo motor 9g SG90

1x Micro Servo motor MG90

1x LCD I2C

1x Switch

1x Potenciômetro

//OBSERVAÇÕES IMPORTANTES//
Podem existir pequenas variações no tamanho dos servos a depender do fabricante. Caso ache relevante e possua o conhecimento, é válido alterar as medidas dos encaixes para evitar o uso de colas ou retrabalho. É recomendado o uso de uma fonte externa entre 5-5.5V para alimentar os servos, pois conexões diretas no arduino podem causar problemas de operação. LCD pode ser conectado na saída de 5V do arduino diretamente





//EN//

This project was developed by first semester graduates of Computer Engineering at CIn - UFPE. Listed below are some comments and observations for those who want to replicate the project.

//PARTS//
The parts are already on the file called "partes". Everything done by 3D printing was made with PLA and gyroid filling. All of the 3D printed pieces, but the side bar("barra lateral"), had 15% density filling. The side bar had 20% filling and was printed in the same orientation as it is placed in the assembly, because it guarantees more mechanical endurance. Many parts were sanded during the assembly, being a recommendation to make things fit better and the movement cleaner(the sanding can be done manually or using a rotary tool). The lever("alavanca") was cut in acrylic with 3mm of thickness.

//ASSEMBLY//
For the screws that do not fit in the servos, was used M3. It is recommended, when fixing the parts that go directly in the servos(the lever and superior base) the use of super bonder glue, using the holes as reference. The lever has 4 holes, distancing 5, 4, 3 and 2 cm from the center, depending of the voltage used in the servo system and the elastic, being relevant test things before permanently fixing the things. There is a hole in the catapult's cylinder to fix, but it did not make it self necessary, just being used as an reference to align. Parts that might be loose, can be better fixed using super bonder glue. The elastic does not have any specifications, being indicated testing and options.


//COMPONETS//

2x Buttons

2x Micro Servo motor 9g SG90

1x Micro Servo motor MG90

1x LCD I2C

1x Switch

1x Potentiometer

//IMPORTANT OBSERVATIONS//
There may be slightly divergences on the servo sizes depending of the manufacturer. If you find relevance and have the knowledge, it is valid to change the fitting sizes, trying to avoid glue or rework. It is recommended the use of an external power source, between 5-5.5V to feed the servos, because direct connections might cause operational issues. The LCD can be powered directly in the 5V output of the arduino

//CIRCUITO(CIRCUIT)//


![Circuito esquemático](https://github.com/annemone07/projeto-IC/blob/main/esquema%20circuito.png)
