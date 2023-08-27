# arm_simgle_final
Ultima versão para apresentação do trabalho.

Passo a passo para implementação.
Também servirá de roteiro para a gravação do vídeo solicitado.
Vamos partir do arquivo base fornecido pelo professor.

## 1 - Preparação inicial

Criar um repositório para armazenamento de comments git.
Usei o Github e git clone para diretório no PC.
Foi o VS code como editor deste ponto em diante.

## 2 - Edição do Código

Feitos os commits iniciais
Pré edição para retira do Check Results como condição de teste e parada.


# Implementação do MOV

Vamos seguir a implementação fornecida em vídeo pelo professor.

De modo geral, vamos incluir um mux que será "flagueado" quando a operação for decodificada e fará um by-pass na unidade de memória de dados.

Vamos inserir um sinal MovF em Decoder (// ALU Decoder)

Alterar ALU para poder ter mais opções de operações.
    Obs.: Vamos fazer isso pois já sabemos que teremos que acrescentar pelo  menos mais uma operação depois dessa (XOR).
    Foi lançada a operação XOR.

Durante o vídeo do professor Dr. Raphael Emerick aparece um sinal NoWrite
Ele já foi implementado pois será util em breve.