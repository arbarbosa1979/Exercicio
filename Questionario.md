1 - O que é clone?

Git clone é um dos muitos comandos do Git. Ele tem como principal proposta clonar todos os arquivos de repositório remoto para um repositório local. Por padrão, todo o histórico de commits, branches e merges são copiados também. Esse comando é muito útil para quando precisamos de uma nova cópia do projeto ou simplesmente porque queremos conferir alguns arquivos.

Para simplificar, um repositório remoto hoje em dia provavelmente está alocado em algum site famoso de Git, como o Github, GitLab e Bitbucket, etc. Sendo assim, se o repositório for público, qualquer um que esteja interessado pode clonar algum dos milhares de projetos dessas plataformas.

2 - o que é commit?

Um commit é um conjunto de alterações que você fez em um projeto. Ele marca uma versão do seu código. Um commit guarda as alterações feitas nos arquivos, quem fez essas alterações e uma mensagem que resume essa alteração. 

Além disso, cada commit tem um hash único SHA1 que pode ser usado para acompanhar todas as alterações feitas no passado e inclusive pode ser usado para voltar em alguma alteração específica ou em algum ponto no tempo específico do seu código.

3 - O que é um repositório?

Um repositório, ou repo, é um diretório onde você armazena os arquivos do seu projeto, que podem ser códigos, imagens, áudios, vídeos ou qualquer coisa relacionada a esse projeto. Ele pode ficar armazenado no seu computador, um repositório local, ou também ser armazenado em alguns serviços como GitHub, BitBucket ou GitLab, ou seja, um repositório remoto.

4 - O que é pull?

O comando git pull é usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais. Fazer o merge de alterações upstream remotas no repositório local é algo comum em fluxos de trabalho de colaboração baseados em Git. O comando git pull é a combinação de dois outros comandos, o git fetch, seguido do git merge. No primeiro estágio da operação, o git pull executa o comando git fetch, que abrange a ramificação local para qual a HEAD aponta. Quando o conteúdo é baixado, o git pull insere o fluxo de trabalho de merge. O commit de merge é criado e a HEAD é atualizada para apontar o novo commit.

5 - O que é um VCS?

O controle de versão, também conhecido como controle de fonte, é a prática de rastrear e gerenciar as alterações em um código de software. Os sistemas de controle de versão são ferramentas de software que ajudam as equipes de software a gerenciar as alterações ao código-fonte ao longo do tempo. Como os ambientes de desenvolvimento aceleraram, os sistemas de controle de versão ajudam as equipes de software a trabalhar de forma mais rápida e inteligente. Eles são ainda mais úteis para as equipes de DevOps, pois as auxiliam a reduzir o tempo de desenvolvimento e aumentar as implementações bem-sucedidas.

O software de controle de versão mantém registro de todas as modificações no código em um tipo especial de banco de dados. Se um erro for cometido, os desenvolvedores podem voltar no tempo e comparar versões anteriores do código para ajudar a corrigir o erro enquanto diminuem interrupções para todos os membros da equipe.

6 - O que é push?

O push é um comando que possibilita que as alterações da sua máquina local sejam enviadas para uma máquina remota. Mas, vamos entender isso melhor:

Imagine que você está desenvolvendo um projeto com uma equipe. O projeto que vocês estão trabalhando está no GitHub, mas você vai desenvolvê-lo no seu computador. Como fazer para “enviar” seu desenvolvimento para o GitHub?

Para enviar suas alterações, você usará o comando git push. Antes dele, evidentemente, temos alguns outros comandos, mas é o git push que pegará tudo o que você fez e colocará em um local onde qualquer pessoa colaboradora possa ver e pegar suas alterações.

7 - O que é merge?

Merge é o comando que unifica algum histórico bifurcado. Resumindo, o Git merge permite que você pegue as linhas criadas a partir do Git branch e faça uma integração para a ramificação principal. É importante notar que o comando git branch cria uma nova ramificação a partir da branch que o desenvolvedor está situado.

Ainda, vale ressaltar que a mesclagem é sempre feita com o auxílio do comando Git checkout, isso porque a alteração vai ser feita apenas na branch principal e a nova ramificação não sofre alteração. Exemplificando, fazemos a troca de branches com o Git checkout e, logo em seguida, fazemos a mesclagem da nova bifurcação para a ramificação principal.

8 - O que é branch?

Quase todo Sistema de Controle de Versionamento tem alguma forma de suporte a ramificações (Branches). Ramificação significa que você diverge da linha principal de desenvolvimento e continua a trabalhar sem alterar essa linha principal. Em muitas ferramentas versionamento, este é um processo um tanto difícil, geralmente exigindo que você crie uma nova cópia do diretório do código-fonte, o que pode demorar muito em projetos maiores.

Uma ramificação no git é um ponteiro para as alterações feitas nos arquivos do projeto. É útil em situações nas quais você deseja adicionar um novo recurso ou corrigir um erro, gerando uma nova ramificação garantindo que o código instável não seja mesclado nos arquivos do projeto principal. Depois de concluir a atualização dos códigos da ramificação, você pode mesclar a ramificação com a principal, geralmente chamada de master.
