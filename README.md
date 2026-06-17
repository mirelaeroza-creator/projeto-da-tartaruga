# 🐢 O Delivery da Tartaruga: Festejando a Conexão Campo-Cidade 🚜🌆

> **Projeto desenvolvido para o Programa Agrinho** > Um jogo 2D interativo de aventura, diálogo e agilidade que celebra a importância da relação entre o ambiente rural e urbano, mostrando como o conhecimento, a tecnologia e os alimentos integram esses dois mundos.

---

## 🎯 Objetivo do Jogo

O objetivo central do jogo é **fazer a conexão perfeita entre o campo e a cidade**, mostrando de forma prática e divertida como esses dois ambientes dependem e cooperam um com o outro. 

Para vencer o jogo, o jogador precisa cumprir três metas principais:
* **Meta da História:** Levar os produtos frescos do campo e as novas tecnologias agrícolas com segurança até a praça central da cidade, garantindo que a grande festa de celebração aconteça.
* **Meta de Aprendizado:** Interagir com os personagens ao longo do caminho por meio dos diálogos para compreender a importância do trabalho rural, da sustentabilidade e de como a cidade valoriza o que é produzido no interior.
* **Meta de Desafio:** Mover o sprite da tartaruga na tela para desviar dos obstáculos bidimensionais (desde cercas na fazenda até o trânsito pesado do centro urbano) e coletar os itens necessários antes que o tempo acabe.

---

## 📖 Sobre o Projeto e História

Em **O Delivery da Tartaruga**, você acompanha a jornada de uma tartaruga sábia e produtora rural em um mundo **2D clássico**. Ela foi convidada de honra para a grande festa da conexão na cidade, mas não pode ir de mãos vazias! Sua missão é cruzar diferentes regiões coletando alimentos frescos e tecnologias sustentáveis, conversando com moradores do campo e da cidade para entender suas necessidades e garantir que a festa seja um sucesso.

O jogo une elementos de **coleta de itens**, **desvio de obstáculos em formato 2D** e **balões de diálogos interativos**, criando uma experiência rica em conteúdo, história e jogabilidade.

---

## 🎬 Fluxo do Jogo: Do Início ao Fim

### 🏁 1. A Tela Inicial e Introdução
* **Menu Principal 2D:** Interface limpa com botões estilizados para *Iniciar Jogo*, *Instruções* e *Créditos*.
* **O Prólogo (Sistema de Diálogo):** Antes do jogo começar, a tela abre uma caixa de diálogo na parte inferior, apresentando a missão da tartaruga com ilustrações dos personagens. Ela arruma sua mochila e se prepara para a longa viagem.

### 🗺️ 2. Fases e Progressão (Um Jogo Longo em 2D)
Para criar uma experiência duradoura, o jogo é dividido em **4 fases distintas em rolagem bidimensional**, cada uma representando uma etapa da conexão campo-cidade:

* **Fase 1: A Fazenda Sustentável (Ambiente Rural 2D)** * *Cenário:* Pixel art ou ilustrações de plantações, árvores e riachos.  
  * *Missão:* Mover a tartaruga na tela para coletar frutas e verduras direto do pé.  
  * *Obstáculos:* Cercas, poças de lama e pequenos animais da fazenda.  

* **Fase 2: A Cooperativa e a Rodovia (A Transição)** * *Cenário:* Uma estrada que corta cenários naturais e começa a exibir os primeiros postes de luz e galpões.  
  * *Missão:* Coletar caixas de ferramentas tecnológicas (sensores agrícolas e drones) cedidas pela cooperativa.  
  * *Obstáculos:* Cones de trânsito, buracos na pista e galhos caídos.  

* **Fase 3: A Periferia e as Hortas Comunitárias (Entrando na Cidade)** * *Cenário:* Ruas mais calmas, transição de casas para prédios baixos e ciclovias.  
  * *Missão:* Conversar com os moradores e ajudar a abastecer as hortas urbanas com as sementes trazidas do campo.  
  * *Obstáculos:* Bicicletas, skates e bueiros abertos.  

* **Fase 4: O Centro Urbano e a Grande Festa (Ambiente Urbano 2D)** * *Cenário:* Grandes prédios iluminados, faixas de pedestre e muito movimento.  
  * *Missão:* Desviar do trânsito pesado para entregar tudo na praça central antes do cronômetro zerar.  
  * *Obstáculos:* Carros em movimento, hidrantes e pedestres correndo.

---

## 📈 Sistema de Dificuldade Dinâmica

O jogo desafia o jogador à medida que ele avança no mapa bidimensional:
* **Velocidade Crescente:** A rolagem do cenário ou a velocidade dos obstáculos aumenta a cada nova fase, exigindo reflexos mais rápidos (afinal, o ritmo da cidade é muito mais acelerado!).
* **Obstáculos Móveis:** Nas fases finais, os carros e pedestres se movem em direções imprevisíveis na tela 2D.
* **Gerenciamento de Tempo:** O relógio corre! Conversar com os personagens certos no caminho pode render "bônus de tempo", enquanto bater em obstáculos faz a tartaruga ficar atordoada (ficar piscando na tela) por alguns segundos.

---

## 💬 Sistema de Diálogos e Conscientização

O jogo conta com caixas de texto estilo RPG que travam a ação momentaneamente para contar a história e educar o jogador. Exemplos de encontros no caminho:
* **No Campo (Dona Abelha):** *"Olá, Dona Tartaruga! Leve este mel orgânico para a cidade. Ele mostra como cuidamos da polinização aqui na fazenda!"*
* **Na Transição (Caminhoneiro Zé):** *"A estrada está movimentada hoje, tartaruga! Mas graças à tecnologia, rastreamos a carga para os alimentos chegarem fresquinhos na cidade."*
* **Na Cidade (Chef Sofia):** *"Que bom que você chegou com os produtos do campo! Sem o seu trabalho no interior, nossa festa e nossos restaurantes não existiriam!"*

---

## 2.1 🎮 Controles

* **Setas do Teclado / W, A, S, D:** Movimentam o sprite 2D da tartaruga pelas direções da tela.
* **Barra de Espaço / Tecla Enter:** Avança as linhas de diálogo e interage com os personagens (NPCs).
* **Tecla P:** Pausa o jogo e abre o menu de pausa.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura das telas e elemento `<canvas>` (onde o mundo 2D é desenhado e renderizado).
* **CSS3:** Estilização das caixas de diálogo sobrepostas, fontes do jogo e paleta de cores temática do Agrinho.
* **JavaScript (Vanilla):** Motor de física 2D (detecção de colisão), movimentação do personagem, gerador de obstáculos aleatórios e lógica da árvore de diálogos.
* **GitHub Pages:** Hospedagem e publicação do site do projeto de forma gratuita e acessível.

---

## 🚀 Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
