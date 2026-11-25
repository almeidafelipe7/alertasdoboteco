# alertasdoboteco
histórico de versões do app para tv de alertas de fantasy

Alertas do Boteco na TV
25 de nov. de 2026 · @Felipe
Antes de começar
A instalação leva uns 15 minutos e só é feita uma vez. Você vai precisar de:
• A TV ligada na internet, no mesmo Wi-Fi do celular.
• O arquivo do app, alertas-do-boteco.apk (cerca de 100 KB), baixado no celular.
• O app Send Files to TV, que é grátis na Play Store, instalado no celular e na TV. Ele passa o arquivo do celular para a TV pelo Wi-Fi.
O app não mexe no Painel de Boteco e não precisa de conta nova. Ele busca os dados direto no Sleeper. Cada amigo instala na própria TV e coloca o próprio usuário.
Instalar na TCL C6KS
A C6KS usa Google TV, então os passos abaixo valem para ela e para outras TVs com Google TV. Os nomes dos menus podem variar um pouco conforme a versão do sistema.
1.  Ative o modo desenvolvedor. Na TV, abra Configurações, depois Sistema, depois Sobre. Desça até "Build do Android TV OS" e aperte OK sete vezes seguidas. Aparece o aviso "Agora você é um desenvolvedor".
2.  Instale o Send Files to TV na TV. Abra a Play Store na TV, procure "Send Files to TV" e instale.
3.  Libere a instalação pelo Send Files to TV. Em Configurações, abra Apps, depois Segurança e restrições, depois Fontes desconhecidas. Ligue a chave do Send Files to TV.
4.  Mande o arquivo do celular. Instale o Send Files to TV também no celular. Abra o app na TV e no celular. No celular, toque em Send, escolha a TV e depois o arquivo alertas-do-boteco.apk.
5.  Instale na TV. No Send Files to TV da TV, abra a pasta Download e escolha o arquivo. Confirme em Instalar.
6.  Se o Google Play Protect avisar, escolha "Mais detalhes" e depois "Instalar mesmo assim". O aviso aparece porque o app não veio da Play Store.
O app aparece em Apps com o nome Alertas do Boteco. Para deixá-lo na tela inicial, segure OK sobre ele e escolha adicionar aos favoritos.
Primeiro uso
1.  Abra o Alertas do Boteco e digite seu usuário do Sleeper no campo "Usuário do Sleeper". Aperte Salvar. Em alguns segundos as suas ligas aparecem na lista.
2.  Libere a sobreposição. Na caixa vermelha do topo, aperte "Liberar agora". Na tela que abrir, ligue "Mostrar sobre outros apps" para o Alertas do Boteco e volte. A caixa vermelha some quando estiver certo. Se a TV não abrir essa tela, veja "Se der problema".
3.  Teste. Aperte "Testar touchdown". O cartão deve entrar no canto de cima, à direita, com som. Depois abra o YouTube ou um canal e teste de novo pelo celular para ver o cartão por cima da imagem.
Pronto. A partir daí o app fica rodando sozinho. Ele confere o Sleeper a cada 15 segundos quando tem jogo rolando e bem menos vezes fora dos jogos. Com "Ligar junto com a TV" marcado, ele volta sozinho quando a TV for ligada.
Nos primeiros segundos depois de abrir, o app só registra o placar. Lances que já tinham acontecido antes disso não viram alerta.
Controlar pela TV ou pelo celular
As duas formas fazem a mesma coisa e ficam sempre sincronizadas.
O que fazer
Pelo controle remoto
Pelo celular
Mostrar ou ocultar o resumo dos confrontos
Abra o app e aperte Mostrar resumo ou Ocultar resumo
Botões no topo da tela de controle
Escolher as ligas
Marque ou desmarque em "Ligas que mandam alerta"
Chaves ao lado de cada liga
Escolher os tipos (touchdown, jogada longa, virada)
Caixas em "Alertas"
Chaves em "Alertas"
Som ligado ou desligado
Caixa Som
Chave Som
Atraso do alerta
Botão Atraso, cada aperto aumenta
Lista Atraso
Pausar tudo
Desmarque "Alertas ligados"
Desligue "Alertas ligados"
Para abrir o controle no celular, aponte a câmera para o QR code que aparece no app da TV. Ele abre um endereço como http://192.168.0.15:8787. Salve esse endereço nos favoritos ou na tela inicial do celular. O celular precisa estar no mesmo Wi-Fi da TV, e o app precisa ter sido aberto pelo menos uma vez desde que a TV ligou.
Atraso: se a sua transmissão estiver atrasada em relação ao Sleeper, o alerta pode chegar antes da jogada. Comece com 30 segundos e ajuste depois de um ou dois lances.
O que dispara cada alerta:
• Touchdown: qualquer TD de um titular seu (passe, corrida, recepção ou da defesa).
• Jogada longa: corrida ou recepção de 25 jardas ou mais, ou passe de 30 ou mais.
• Virada: seu time estava atrás no confronto e passou à frente.
Os pontos do cartão são calculados com a pontuação de cada liga. Quando o mesmo jogador é titular em mais de uma liga, um só cartão mostra os pontos e o placar de cada uma.
Se der problema
Problema
O que fazer
O botão Liberar agora não abre nada
Algumas TVs escondem essa tela. Faça a liberação uma vez pelo celular, como explicado logo abaixo.
O teste não aparece por cima de outros apps
Confira se a caixa vermelha sumiu no app. Se continuar, libere pelo celular como explicado abaixo.
O celular diz "Não achei a TV"
Confira se o celular está no Wi-Fi de casa, não no 4G, e abra o app na TV uma vez. O endereço pode mudar se o roteador reiniciar. Leia o QR code de novo.
As ligas não aparecem
Confira o usuário do Sleeper (é o nome de usuário, sem @). Só aparecem ligas em andamento nesta temporada.
O alerta chega antes da jogada na TV
Aumente o Atraso.
Os alertas param depois de um tempo
Abra o app uma vez para reiniciar. Se acontecer sempre, me avise.
Liberar a sobreposição pelo celular (só se a TV não tiver a tela):
1.  Na TV, em Configurações, Sistema, Opções do desenvolvedor, ligue "Depuração USB" (em algumas TVs aparece como "Depuração ADB").
2.  No celular Android, instale um app de comandos ADB, como o TvOverlay Remote ou o Remote ADB Shell, e conecte à TV pelo endereço dela.
3.  A TV pergunta se permite a depuração. Aceite.
4.  Envie este comando:
appops set com.botecodofantasy.alertastv SYSTEM_ALERT_WINDOW allow
Isso só é preciso uma vez. Se você reinstalar o app, repita.
Atualizações: a partir da versão 1.1 o app confere sozinho, uma vez por dia e nunca durante os jogos, se saiu versão nova. Quando sai, ele baixa e abre a tela de atualização na TV, e você só confirma em Atualizar. Na primeira vez a TV pode pedir para liberar "Instalar apps desconhecidos" para o Alertas do Boteco. Também dá para procurar na hora pelo botão "Procurar atualização", na TV ou no celular. As configurações ficam guardadas.
