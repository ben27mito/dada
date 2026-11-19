# Ilhas de Papel V6

Jogo multiplayer por turnos. Execute `npm install` e `npm start`. No Render: Root Directory `ilhas-multiplayer`, Build Command `npm install`, Start Command `npm start`.

## V6
- Clique em ilha livre para colonizar (é necessário transporte depois da primeira ilha).
- Clique em ilha inimiga para iniciar duelo. Cada jogador ataca alternadamente; dano básico = dado × 10. Tanques e artilharia aumentam dano; blindagem, medicina e fortificação reduzem perdas. Ao zerar tropas defensoras, ilha muda de dono. Jogador sem tropas e sem ilhas é eliminado.
- Novas pesquisas: artilharia, blindagem, medicina, logística, radar, fortificação, satélite, engenharia. Computador e satélite aumentam as escolhas na pesquisa. Tecnologias passivas ativam na pesquisa, sem fabricação.
- Fábrica de pesquisa não existe. Existem apenas fábrica de minério e fábrica de fábricas.

**Limitações atuais:** a guerra usa exércitos globais por país (não tropas separadas por ilha); navios, aviões e pontes funcionam como pré-requisito de transporte, sem simulação espacial de rotas. Estado das salas é mantido na memória do servidor, não em banco de dados; reinícios do Render apagam partidas e não há reconexão automática. As regras de equilíbrio podem ser alteradas em versões futuras.
