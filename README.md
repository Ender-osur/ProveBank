# ProveBank
Este proyecto está basando en una replica más económica de la Nelvis III de Nationals Instruments usando una IoT y una esp32.


Cuenta con las siguientes funcionalidades:
1 Amperímetro
1 Voltímetro
1 Generador de funciones
1 Osciloscopio
1 Medidor de continuidad

La configuración de cada una de esas funcionalidades se hizo mediante código usando micropython como lenguaje para desarrollar en la tarjeta de desarrollo esp32. 

Los datos recopilados por los pines de las esp32 se envían a una página web mediante mqtt, haciendo uso de bases de datos relacionales para también almancenar las lecturas. 
