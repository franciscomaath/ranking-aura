# **ResenhaScore365**  
**O Gerenciador de Aura Oficial da Resenha**

O **ResenhaScore365** é uma plataforma completa para gerenciar campeonatos de FIFA, PES ou qualquer outro jogo, transformando a zoeira em dados. Chega de "eu acho que ganho mais", agora os números não mentem.  

Este sistema nasceu da necessidade de registrar os resultados históricos da **Copa do Brasil no EA FC 24** e da **Resenha League 2025**, e hoje serve como o **ranking oficial de "Aura"** do nosso grupo.

---

## ✨ **Principais Funcionalidades**

- **Ranking de Aura:**  
  Um sistema baseado no método científico Elo, que mede a força real de cada jogador. Vencer um oponente mais forte te dá mais pontos. Perder para um "azarão" custa caro.

- **Múltiplos Torneios:**  
  Crie e gerencie vários campeonatos (ex: "Mundial", "Copa Cerveja") de forma separada e organizada.

- **Ranking Geral e por Torneio:**  
  Acompanhe a classificação geral que consolida todos os resultados, e também o desempenho específico em cada competição.

- **Cálculo de Aura Avançado:**  
  A variação de aura considera:
  - Resultado da partida
  - Diferença de aura entre os jogadores
  - Placar da partida (goleadas dão bônus)
  - Peso de cada fase do torneio (final vale mais que fase de grupos)

- **Histórico Completo:**  
  Veja todas as partidas, com placares e a variação de aura de cada jogador no confronto.

- **Portabilidade Total:**  
  Salve todo o estado do sistema (jogadores, torneios, partidas) em um único arquivo `.json` para backup ou compartilhar com os amigos.

---

## 🚀 **Como Usar**

1. **Baixe o Arquivo:**  
   Salve o arquivo `.html` da pasta ResenhaScore365 no seu computador. O arquivo index.html na raiz do projeto refere-se apenas a uma versão somente leitura, para expor os dados do nosso grupo.

2. **Abra no Navegador:**  
   Clique duas vezes no arquivo para abrir no seu navegador de preferência (Chrome, Firefox, etc.).

3. **Pronto!**  
   O sistema já está funcionando. Você pode criar torneios, adicionar jogadores e registrar partidas. Todos os dados ficam salvos no seu navegador.

4. **Para Sincronizar:**  
   Use os botões **"Exportar Dados"** para salvar um backup e **"Importar Dados"** para carregar o progresso em outro PC ou receber atualizações de amigos.

---

## 🤔 **Como Funciona a Aura?**

A **"Aura"** é a nossa versão do rating Elo, representando o poder de luta de cada jogador.

- **Ponto de Partida:** Todo jogador começa com **1000 de aura**.  
- **A Batalha:** O vencedor sempre "rouba" aura do perdedor.  

### **A Lógica:**
- **Vitória normal:** vale 1 ponto no cálculo.  
- **Empate:** vale 0.5 ponto para cada; o jogador com menos aura sempre sai ganhando alguns pontinhos.  
- **Vitória nos pênaltis:** o vencedor leva 0.75 e o perdedor 0.25 dos pontos em jogo.  

### **Bônus:**
- **Bônus de goleada:**  
  - Vencer por 2 gols: bônus de 1.2x na aura  
  - Vencer por 3 ou mais gols: bônus de 1.3x  
- **Bônus de fase:**  
  O admin pode criar fases (ex: "final") com multiplicador de até 1.5x, tornando os jogos decisivos ainda mais valiosos.

---

Feito na base do ódio e da resenha em **São Luís, Maranhão**.
