# Snaze

# Introdução 
O projeto Snaze é uma re-elaboração do clássico jogo Snake, desenbolvido para a disciplina de LP I.

# Definindo o mapa
Deve-se criar um arquivo txt e chama-lo na hora de compilar. Pode se colocar vários mapas de uma vez no arquivo.
Para cada mapa coloca-se a quantidade de linhas e depois a quantidade de colunas, logo após o mapa(exemplos na pasta "test").    No mapa desenhado pode ter:
        `*` - Ponto inicial do snake(obrigatório em cada mapa);
        `#` - Parede;
        `0` - Caminho livre;
        `.` - Parede invisível.

# Para compilar
Deve-se abrir a pasta Snaze, logo após, abrir a pasta "src", dentro dela, digitar `g++ main.cpp -std=c++11 -o Snaze` para gerar o executável "Snaze", após isso digite `./Snaze local_dos_mapas.txt` para executar com os mapas desejados.

# Regras
Algumas regras do jogo:

Cada vez que o snake anda uma casa, ganha 10
Caso pegue um café ganha 100
Caso morra, perde 500
    
# Autores
Janeto Erick da Costa Lima
 
Júlio César da Costa Morais <juliocsarr10@gmail.com>
