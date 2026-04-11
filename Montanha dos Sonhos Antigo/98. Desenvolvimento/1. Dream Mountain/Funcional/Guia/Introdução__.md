# O que é Dream Mountain?

É um **RPG de Mesa** baseado em um universo fictício sobre uma **Montanha que realiza desejos**. A proposta é de um jogo onde há várias modalidades como histórias, lutas, aventuras, enigmas e entre outros, com foco na diversidade de estratégias, estilos de jogo e personagens.

O jogo é feito para poder incentivar qualquer pessoa a jogar a sua própria maneira, dando recursos para isso, seja habilidades estranhas para personagens exóticos ou itens sérios para fichas mais bem construídas.

Um dos focos principais de cada campanha é a história, sendo apenas um recurso narrativo para juntar e direcionar o grupo de jogadores, mas os mesmos podem fazer objetivos secundários ou explorar áreas que nem fazem parte do enredo principal.

# Como jogar?

Existem alguns requisitos básicos para poder jogar:

* Baixar e instalar o **Obsidian**
* Um bom editor de texto (Visual Studio Code, Sublime Text, ou o próprio Obsidian).

Essas ferramentas servem para facilitar a organização da ficha e das anotações da campanha.

Também é necessário criar um personagem (que será mais detalhado nos próximos tópicos) e entender como funciona os turnos, principalmente a diferença entre **Plano de Interpretação** e **Plano de Combate**.

# Plano de Interpretação

Inicialmente os personagens começam no **Plano de Interpretação**, um modo de jogo onde diálogos e tomadas de decisões são o ponto chave.

Nesse modo os jogadores tem liberdade para poder realizar qualquer **Ação**, sem restrições como turnos ou tempo (raramente tendo turnos para todos poderem jogar igualmente, ou tempo se nada estiver progredindo).

Nesse plano os jogadores podem usar qualquer item ou habilidade, desde as **Interpretativas** até as de **Combate**.

As **Ações Interpretativas** podem ser qualquer uma baseadas na **Imaginação do Jogador**, porém sempre essas ações são englobadas em alguns tipos, que podem ser consultados em [[Interpretação__]] para mais detalhes. Essas ações podem ter variações criativas, dependendo de como um **Jogador** consegue convencer a **Mesa** e o **Mestre**. Por exemplo em um cenário onde alguém precisa pular um buraco:

* Um **Jogador** pode tentar convencer a todos que atravessou aquele obstáculo graças ao seu nível de **Exercício**.
* Um **Jogador** também pode tentar convencer a todos que atravessou aquele mesmo obstáculo graças ao seu nível de **Mobilidade**.

Qualquer **Ação** realizada que seja do **Plano de Combate** ou caso algum evento indesejado ocorra, esse plano pode ser quebrado e todo o grupo inteiro é movido para o **Plano de Combate**.

# Plano de Combate

Diferente do **Plano de Interpretação**, o **Plano de Combate** possui mais **Regras** além de mais importância nos [[98. Desenvolvimento/1. Dream Mountain/Funcional/Sistema/Mecânicas/Atributos__]].

A **Primeira Regra** é que: existem uma ordem de turnos, baseado no **Atributo** de **Velocidade** dos **Jogadores**, do mais rápido para o mais lento, depois o turno dos **Oponentes**, também seguindo a mesma ordem.

**Segunda Regra**: cada turno de um **Jogador**, **NPC** ou **Monstro** possui três **Ações Controladas** em que sua ordem pode ser decidida livremente por seu **Usuário**.

* **Movimento**: pode se mover pelo tabuleiro em "casas" igual ao seu **Atributo** de **Velocidade** (as casas do tabuleiro correspondem a 1 metro quadrado).
* **Ataque Básico**: causa **Dano Físico** em um **Alvo** igual ao seu **Atributo** de **Ataque**, em um **Alcance** de 1 metro caso esteja **Desequipado** ou **Corpo a Corpo**.
* **Principal**: pode usar uma **Habilidade** ou **Item**.

Existe uma observação, assim como quem está jogando pode decidir passar o **Turno**, ele também pode decidir só realizar **Ações** que quiser.

**Terceira Regra**: Além das **Ações Controladas** existem duas **Fases** que não são controladas.

* **Início de turno**: onde os **Efeitos**, sejas **Positivos** ou **Negativos**, ocorrem.
* **Fim de turno**: onde todos os **Efeitos** são reduzidos em **1** cada, o que também reduz a sua duração (ao zerar).

**Última Regra**: no fim do **Combate**, seja por um lado vitorioso ou uma interrupção, todos voltam para o **Plano de Interpretação**. 

**Observação**: Embora o turno siga essa estrutura base, algumas habilidades e talentos podem mudar a ordem ou a quantidade de ações disponíveis.

# Criação de Personagem

O personagem pode ser criado sobrescrevendo ou clonando a [[Ficha Base__]], para colocar as informações sobre seu personagem.

**Personagem**: onde há informações básicas como **Nome**, **Apelido** e **História**, é um espaço totalmente livre para criatividade do jogador. Uma dessas informações é muito relevante, no caso as [[Raças Jogáveis__]], que podem mudar drasticamente o estilo de jogo tanto na **Interpretação** quanto o **Combate**.

**Atributos**: onde há informações relevantes tanto para **Interpretação** quanto para **Combate**. Todos os personagens começam no **Nível** 1. O primeiro passo é distribuir pontos de **Atributo Primário**, assim ganhando os seus valores como **Vida** e **Mana**. O que cada um dos **Atributos** fazem pode ser consultado em [[98. Desenvolvimento/1. Dream Mountain/Funcional/Sistema/Mecânicas/Atributos__]]. São 10 pontos iniciais para distribuir, mas cada **Atributo Primário** já possui 2 pontos base, além de não poderem passar de um máximo de 10 na criação de **Ficha**.

**Itens**: um personagem novo tem direito a alguns **Itens** de **Nível 0**, sendo a sua escolha 2 [[Ferramentas__]], 3 [[Equipamentos__]] e 5 [[Consumíveis__]]. Além disso **Jogadores** tem um inventário de apenas de 5 espaços de **Item**, onde ficam **Armas** e **Equipamentos** desequipados, e também onde seus **Consumíveis** irão automaticamente. O inventário pode ser expandido com **Mochilas**.

**Habilidades e Talentos**: primeiro você escolha um dos [[Conhecimentos__]]. todas as **Habilidades** e **Talentos** da sua **Classe** ficam nessa sessão. Novos personagens sempre tem tudo de **Nível** 0 do seu **Conhecimento** inicial, porém podem escolher apenas 1 **Habilidade** ou **Talento** de **Nível** 1 para ter além dessas.

Para qualquer dúvida há a [[Ficha Exemplo__]], sendo um personagem funcional e genérico, podendo ser usado como referência na criação ou como o seu próprio **Personagem**.

# Progressão

Os **Jogadores** vão sempre evoluir 1 **Nível** ao derrotar um **Chefe** de mesmo **Nível** deles, ou 2 **Níveis** caso esse **Oponente** seja de **Nível** mais elevado.

**Ao subir de Nível**: o **Jogador** recebe mais 5 pontos de **Atributo Primário** para distribuir, além de pontos de **Conhecimento** que podem gastar para aprender **Habilidades** e **Talentos**. Os pontos de **Conhecimento** recebidos são sempre igual ao seu **Nível**, assim como custo "compra" de uma **Habilidade** ou **Talento** é também do **Nível** dela. É possível economizar pontos ao subir de **Nível**, porém só podem ser gastos em **Habilidades** e **Talentos** com **Nível** semelhante ou inferior ao seu.

**Além do Nível**: grandes feitos na **Interpretação** podem resultar em aumentos permanentes em **Atributos**, ou até mesmo a subida de **Nível**. Alguns eventos **Interpretativos** podem ter o mesmo peso que uma luta de **Chefe**.

**Recompensas Maiores**: um **Chefe** derrotado sempre concede 5 **Itens** arremessando **1d20** para cada um deles. A falha **Crítica** resulta em um **Item** de 1 **Nível** abaixo dele. Acerto **Crítico** resulta em um **Item** de 1 **Nível** acima dele. Valores normais são sempre um **Item** do mesmo **Nível** do **Chefe**. Essas jogadas de **Dados** não podem ser influenciadas (a não ser que seja um efeito muito especifico para esse caso).

**Recompensas Médias**: **Inimigos** de **Elite** podem assim como um **Chefe** conceder **Itens** de 1 **Nível** superior no **Crítico**, porem só dão 1 **Item** por derrota, além de só tiverem **Saque** com jogadas de 15 no **d20** para cima. Essas jogadas de **Dados** não podem ser influenciadas (a não ser que seja um efeito muito especifico para esse caso).

**Recompensas Menores**: **Inimigos** normais podem conceder **Itens** do mesmo **Nível** deles apenas com um **Crítico**. Erro **Crítico** faz com que todos os **Saques** de **Inimigos** normais não possam ser mais gerados nessa **Vitória**. Essas jogadas de **Dados** podem ser influenciados por peculiaridades, como por exemplo **Efeitos** e **Atributos Secundários**

**Aleatoriedade da Recompensa**: é decidido em **1d6** se o **Item** será uma **Ferramenta** (1-2), **Consumível** (3-4) ou **Equipamento** (5-6). No caso de **Consumível** a recompensa é sempre quadruplicada, ou dobrada caso seja um de **Nível** 8 e única se de **Nível** 9.