<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Política de Privacidade — The Nose Journey</title>
<style>
  body{max-width:42rem;margin:0 auto;padding:2rem 1.25rem;font:16px/1.65 system-ui,-apple-system,Segoe UI,sans-serif;color:#1a1a1a;background:#fff}
  h1{font-size:1.6rem;margin-bottom:.25rem}
  h2{font-size:1.15rem;margin-top:2rem}
  .meta{color:#666;font-size:.9rem;margin-top:0}
  code{background:#f4f4f4;padding:.1rem .3rem;border-radius:3px;font-size:.9em}
  ul{padding-left:1.2rem}
  .box{background:#f7f7f7;border-left:3px solid #ccc;padding:.75rem 1rem;margin:1.5rem 0}
  @media(prefers-color-scheme:dark){
    body{background:#111;color:#e8e8e8}code{background:#222}.box{background:#1b1b1b;border-color:#444}.meta{color:#999}
  }
</style>
</head>
<body>

<h1>Política de Privacidade — The Nose Journey</h1>
<p class="meta">Última atualização: 21 de outubro de 2026</p>

<p>Esta política descreve como o aplicativo <strong>The Nose Journey</strong> (pacote
<code>com.furtado.thenosejourney</code>) trata informações. Em resumo: <strong>o jogo não coleta
nenhum dado pessoal e não possui servidor próprio.</strong> Duas coisas saem do seu aparelho: o seu
progresso de jogo, enviado ao <strong>Google Play Jogos</strong> para que você não perca o save ao
trocar de celular; e, a cada anúncio exibido, um identificador de publicidade enviado ao
<strong>Google AdMob</strong> para servir e medir esse anúncio. Nada mais é transmitido.</p>

<h2>1. Dados que coletamos</h2>
<p><strong>Nenhum dado pessoal.</strong> O aplicativo não solicita cadastro, não cria conta
própria, não acessa sua localização, câmera, microfone, contatos nem arquivos.</p>
<p>O desenvolvedor não recebe, não armazena e não tem acesso ao seu nome, e-mail, foto ou
identificador da sua conta Google. O jogo não consulta esses dados em nenhum momento.</p>
<p>O aplicativo exibe anúncios através do <strong>Google AdMob</strong>, descrito na seção 4. Para
isso, o SDK do AdMob lê o <strong>identificador de publicidade</strong> do seu aparelho — não há
serviço de análise, rastreamento de uso ou métricas além do que o próprio AdMob processa para
servir e medir os anúncios.</p>

<h2>2. Dados de jogo salvos no seu aparelho</h2>
<p>Para que o jogo funcione, os dados de progresso ficam gravados no armazenamento local do
aparelho:</p>
<ul>
  <li>recorde de altura e estatísticas de partidas (metros percorridos, pólen coletado, mortes,
      continues, número de partidas);</li>
  <li>moedas, inventário de itens e talentos adquiridos;</li>
  <li>nível, experiência e pontos de talento;</li>
  <li>conquistas desbloqueadas;</li>
  <li>preferências de áudio (volume, som e música ligados ou desligados);</li>
  <li>sinalizadores de tutorial e história já vistos;</li>
  <li>data e hora do último salvamento, usada para decidir qual save é o mais recente.</li>
</ul>
<p>Esses dados não identificam você. São apenas números e preferências do jogo.</p>

<h2>3. Salvamento na nuvem (Google Play Jogos)</h2>
<p>O jogo usa o recurso <strong>Jogos salvos</strong> do Google Play Jogos para guardar uma cópia
do seu progresso vinculada à <strong>sua própria conta Google</strong>. Serve para você recuperar o
jogo depois de reinstalar ou ao trocar de aparelho.</p>

<p><strong>O que é enviado:</strong> exatamente a mesma lista da seção 2, e nada além dela. Junto
vai uma descrição curta do save com o seu recorde (por exemplo, "Recorde 1240 m"), que aparece na
tela de saves do próprio app Google Play Jogos.</p>

<p><strong>Para onde vai:</strong> para a infraestrutura do Google, dentro da área reservada ao
seu jogo na sua conta Google. <strong>Não existe servidor do desenvolvedor.</strong> O
desenvolvedor não consegue ler, copiar ou alterar esse arquivo — o acesso é só seu e do Google.
O tratamento dos dados pelo Google é regido pela
<a href="https://policies.google.com/privacy">Política de Privacidade do Google</a>.</p>

<p><strong>Quando acontece:</strong> o jogo tenta entrar silenciosamente no Google Play Jogos ao
abrir. Se a sua conta já estiver conectada ao Play Jogos no aparelho, a sincronização ocorre
automaticamente: o save da nuvem é baixado na abertura e enviado ao fim de cada partida.</p>

<p><strong>Se você não quiser:</strong> o jogo funciona por completo sem a nuvem. Sem conexão com
o Play Jogos, sem internet, ou com a conta desconectada, tudo continua salvo apenas no aparelho e
nenhuma falha de sincronização interrompe a partida. Para desativar, desconecte sua conta em
<em>app Google Play Jogos → Mais → Configurações</em>, ou revogue o acesso do jogo em
<a href="https://myaccount.google.com/permissions">myaccount.google.com/permissions</a>.</p>

<h2>4. Anúncios (Google AdMob)</h2>
<p>O jogo exibe anúncios fornecidos pelo <strong>Google AdMob</strong>, em três formatos: vídeos
premiados e opcionais (reviver, dobrar moedas, item grátis na loja), anúncio intersticial entre
partidas, e banner fixo em algumas telas de menu.</p>

<p><strong>O que é enviado:</strong> o <strong>identificador de publicidade</strong> do seu
aparelho (um código que o Android já expõe para esse fim, e que você pode resetar ou desativar nas
configurações do aparelho) é enviado ao Google a cada anúncio solicitado, para que o AdMob escolha,
exiba e meça o desempenho do anúncio. Nenhum outro dado do jogo — progresso, moedas, estatísticas —
acompanha essa requisição. O identificador <strong>não</strong> é lido, armazenado ou usado pelo
desenvolvedor em nenhum momento; ele vai direto do seu aparelho para o Google.</p>

<p><strong>Consentimento:</strong> antes de qualquer anúncio ser solicitado, o jogo exibe o
formulário de consentimento da própria Google (UMP — User Messaging Platform) quando exigido pela
sua região, cobrindo tanto o GDPR europeu quanto a LGPD brasileira. Você pode revisar ou alterar
sua escolha de anúncios personalizados a qualquer momento em
<a href="https://adssettings.google.com">adssettings.google.com</a> ou nas configurações de
publicidade do Android.</p>

<p><strong>Se você não quiser:</strong> o jogo inteiro — fases, progressão, loja, conquistas —
funciona sem assistir nenhum anúncio premiado, que é sempre opcional. Interstitial e banner
aparecem automaticamente durante o uso normal do app e não podem ser desativados sem remover o
recurso de anúncios do jogo como um todo (não há, hoje, uma compra de remoção paga em dinheiro
real — a loja usa apenas moeda do próprio jogo).</p>

<p>O tratamento desses dados pelo Google é regido pela
<a href="https://policies.google.com/privacy">Política de Privacidade do Google</a> e pela
<a href="https://support.google.com/admob/answer/6128543">política de privacidade do AdMob</a>.</p>

<h2>5. Como apagar seus dados</h2>
<p><strong>No aparelho:</strong></p>
<ul>
  <li>desinstalar o aplicativo remove todos os dados locais; ou</li>
  <li><em>Configurações do Android → Apps → The Nose Journey → Armazenamento → Limpar dados</em>.</li>
</ul>
<p><strong>Na nuvem:</strong> o save fica na sua conta Google e é você quem o controla.</p>
<ul>
  <li>no app <strong>Google Play Jogos</strong>, abra a biblioteca, selecione The Nose Journey e
      exclua o jogo salvo; ou</li>
  <li>remova o acesso do jogo em
      <a href="https://myaccount.google.com/permissions">myaccount.google.com/permissions</a>.</li>
</ul>
<p>Desinstalar o app <strong>não</strong> apaga por si só a cópia na nuvem — é para isso que ela
existe. Use um dos caminhos acima para remover também o save remoto. Se precisar de ajuda,
escreva para o contato da seção 10.</p>
<p><strong>O que é excluído e o que permanece:</strong> os caminhos acima apagam, de imediato, o
save do jogo (moedas, inventário, talentos, nível, conquistas, estatísticas, recorde,
preferências) — local, na nuvem, ou ambos, conforme o caminho escolhido. Não guardamos nenhuma
cópia própria: não existe servidor do desenvolvedor, então não há dado retido por nós após a
exclusão. A cópia na nuvem fica sob o Google (Google Play Jogos), sujeita à política de retenção
do próprio Google — ver <a href="https://policies.google.com/privacy">Política de Privacidade do
Google</a>. O identificador de publicidade lido pelo AdMob (seção 4) não é armazenado por este
app em nenhum momento; para zerá-lo ou desativar personalização, use as configurações de anúncio
do Android ou <a href="https://adssettings.google.com">adssettings.google.com</a>.</p>

<h2>6. Permissões</h2>
<p>O aplicativo declara apenas a permissão de <strong>Internet</strong>. Ela é usada pelo
salvamento na nuvem (seção 3) e pela exibição de anúncios do AdMob (seção 4). O jogo não faz
nenhuma outra conexão de rede: não há chamadas a servidores próprios do desenvolvedor.</p>

<h2>7. Crianças</h2>
<p>O conteúdo do jogo em si é adequado para todas as idades: não há violência, linguagem
imprópria, conteúdo sexual, chat ou interação entre usuários.</p>
<p>No entanto, o jogo usa o <strong>AdMob padrão</strong> (não a versão certificada para anúncios
direcionados a crianças), que não garante que todo anúncio exibido seja apropriado para um público
infantil. Por isso, seguindo a política do Google Play, este app <strong>não é destinado nem
direcionado a crianças menores de 13 anos</strong>, e não participa do programa Designed for
Families.</p>
<p>O recurso de salvamento na nuvem depende da conta Google do próprio aparelho, cujos requisitos
de idade e supervisão parental são definidos pelo Google — inclusive no Family Link, quando a
conta for gerenciada por responsável.</p>

<h2>8. Compartilhamento com terceiros</h2>
<p>Não vendemos nem alugamos dados a ninguém. Dois terceiros recebem dado, cada um para uma
finalidade específica e descrita nas seções anteriores:</p>
<ul>
  <li><strong>Google Play Jogos</strong> — recebe o seu progresso de jogo (seção 3), só para
      guardar e devolver o seu save. Não é usado para publicidade.</li>
  <li><strong>Google AdMob</strong> — recebe o identificador de publicidade do aparelho (seção 4),
      para servir e medir anúncios. É a única finalidade publicitária deste app.</li>
</ul>

<h2>9. Alterações nesta política</h2>
<p>Esta versão passou a descrever o uso de anúncios (AdMob) a partir de 21 de outubro de 2026. Se
versões futuras do jogo passarem a incluir compras no aplicativo com dinheiro real, esta política
será atualizada <strong>antes</strong> do lançamento dessa versão, e o formulário de Segurança dos
Dados na Google Play será revisto junto. A data de "última atualização" no topo indica a versão
vigente.</p>

<h2>10. Contato</h2>
<p>Dúvidas sobre esta política, pedidos de exclusão de dados ou qualquer outro assunto de
privacidade: <strong>furtado.gamesrr@gmail.com</strong></p>

<div class="box">
<strong>Nota para o desenvolvedor — remover antes de publicar:</strong> substitua o e-mail de
contato acima por um endereço real e monitorado; a Google Play exige canal válido. Confira a data
de "última atualização" no topo na hora de publicar. Esta versão já descreve cloud save (Play
Games) <em>e</em> anúncios (AdMob) — ainda <em>sem</em> compras com dinheiro real. Ao ligar IAP,
revisar as seções 1, 6, 8 e 9 e o formulário de Segurança dos Dados antes do upload.
</div>

</body>
</html>
