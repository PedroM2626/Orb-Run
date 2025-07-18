Orb Run

Orb Run é um jogo de terror em terceira pessoa desenvolvido na Unreal Engine. Você controla um personagem que deve coletar orbes misteriosas espalhadas em um único mapa sombrio que vai ficando cada vez mais escuro conforme você coleta os orbs. Enquanto isso, um monstro caça você usando NavMesh para navegação, ficando cada vez mais rápido a cada orbe coletado; quando restam 0 orbs, a saída se abre e o monstro entra em modo furioso.

📜 Descrição

Orb Run combina suspense, exploração e sobrevivência em um único mapa que escurece progressivamente com base no número de orbes restantes. Cada orbe coletado reduz a iluminação ambiente, aumentando a tensão. O monstro utiliza NavMesh Navigation para perseguir o jogador e sua velocidade escala conforme orbs são coletados. Após eliminar todas as orbes, a porta de saída se destranca, mas o monstro atinge sua velocidade máxima em fúria final.

🎮 Principais Funcionalidades

Atmosfera Dinâmica: Iluminação diminui a cada orbe coletado.

IA com NavMesh: Monstro usa NavMesh para patrulhar e perseguir de forma inteligente.

Velocidade Escalonada do Monstro: A cada orbe coletado, o monstro acelera.

Momento de Fúria: Ao restar 0 orbs, a saída abre e o monstro fica em modo furioso, maximizando velocidade e agressividade.

Sistema de Dificuldade Ajustável: Três níveis (Fácil, Médio, Difícil) que alteram:

Quantidade de orbes (10, 15, 20)

Velocidade inicial do monstro

Taxa de escurecimento do mapa

Colecionáveis: Orbes que revelam mapas de áreas secretas no HUD.

Puzzles Leves: Obstáculos que requerem interação para destrancar caminhos.

🚀 Como Rodar o Jogo

Pré-requisitos:

Unreal Engine 5.5+

8 GB de RAM

GPU compatível com DirectX 11 ou superior

Clone o repositório:

git clone https://github.com/PedroM2626/orb-run.git
cd orb-run

Compilar projeto:

Abra OrbRun.uproject na Unreal Engine.

Aguarde build de shaders e assets.

Executar:

Clique em Play no editor ou gere um Build para Windows/macOS.

⌨️ Controles

W/A/S/D: Mover-se

Shift (segurar): Correr

E: Interagir / coletar orbe

F: Ligar/Desligar lanterna

Esc: Abrir menu de pausa


🛠️ Ferramentas Utilizadas

Unreal Engine 5.5

Blender (modelagem 3D)

Audacity (edição de áudio)

Git (controle de versão)

NavMesh (sistema de navegação da UE)

🧩 Mecânicas Extras

Várias mecânicas — completas e em estágio de teste — foram desenvolvidas mas não integradas à versão final do jogo. Os códigos e as cenas de teste estão disponíveis no repositório para exploração e estudo.

💾 Download Completo do Projeto

Para baixar todos os assets e cenas completas, acesse: https://mega.nz/folder/v0AQWQAI#77jjVemhdrh6_UNwpDCvdw

🤝 Contribuições

Contribuições são bem-vindas! Abra Issues para bugs e Pull Requests para melhorias. Apenas os códigos e blueprints estão no GitHub; o download completo encontra-se no link acima.

Bom jogo e cuidado com o que espreita nas sombras!

