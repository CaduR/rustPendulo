<strong> Projeto estudo RUST - Pendulo </strong>

Meu primeiro projeto desenvolvido em Rust. 

O objetivo foi criar uma simulação de um pêndulo utilizando a biblioteca de gráficos 2D Speedy2d, explorando os fundamentos da linguagem e conceitos de cinemática.

<strong> MEMORIA </strong> - O Rust não possui Garbage Collector. Aprendi que a linguagem utiliza um sistema de "posse" (Ownership).

<strong> Referências (&) </strong>: Usei para permitir que o método de desenho e de cálculo acessassem os vetores de posição sem "tomar posse" deles, evitando que os dados fossem deletados da memória antes da hora.

<strong> Mutabilidade (&mut) </strong>: Essencial para permitir que a posição do pêndulo fosse alterada a cada frame dentro do loop de atualização.

<strong> Organização </strong> - Vector: Criado dentro de um módulo próprio (mod vector) para lidar com matemática de coordenadas x e y.Pendulum: Uma estrutura que agrupa todas as propriedades físicas (ângulo, gravidade, massa, comprimento).Encadeamento de Métodos: Implementei o retorno de &mut Self em funções como .set() para permitir chamadas mais limpas.

<strong> Como rodar o projeto: </strong>
Certifique-se de ter o Rust instalado (rustup).
Clone este repositório.
No terminal, execute:
cargo run

<img width="400" height="255" alt="pendulo" src="https://github.com/user-attachments/assets/743fec8b-34cc-43ca-9490-f601854584b6" />


