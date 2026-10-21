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
  @media(prefers-color-scheme:dark){
    body{background:#111;color:#e8e8e8}code{background:#222}.meta{color:#999}
  }
</style>
</head>
<body>

<h1>Política de Privacidade — The Nose Journey</h1>
<p class="meta">Última atualização: 21 de outubro de 2026</p>

<p>Esta política descreve como o aplicativo <strong>The Nose Journey</strong> (pacote
<code>com.furtado.thenosejourney</code>) trata informações. Em resumo: o jogo não pede cadastro e
não possui servidor do desenvolvedor. Dois serviços do Google processam informações quando você
joga: o <strong>Google Play Jogos</strong>, que guarda o seu progresso na sua conta Google para
você não perder o save ao trocar de celular; e o <strong>Google AdMob</strong>, que coleta
automaticamente o identificador de publicidade e dados técnicos do aparelho para exibir e medir
anúncios. Esses dados vão direto do seu aparelho para o Google; o desenvolvedor não os recebe.</p>

<h2>1. Dados que tratamos</h2>
<p>O aplicativo não solicita cadastro, não cria conta própria, não acessa sua localização,
câmera, microfone, contatos nem arquivos. O desenvolvedor não recebe nem tem acesso ao seu nome,
e-mail, foto ou identificador da sua conta Google, e o jogo não consulta esses dados em nenhum
momento.</p>
<p><strong>Dados coletados automaticamente pelo Google AdMob</strong> por meio do SDK de anúncios
incluído no jogo (detalhes na seção 4): endereço IP, identificadores do aparelho (inclusive o
identificador de publicidade), informações do aparelho e do sistema (como modelo, versão do Android
e idioma), interações com os anúncios e dados de diagnóstico e desempenho do SDK. Alguns desses
dados, como o identificador de publicidade e o endereço IP, podem ser considerados dados pessoais
pela legislação brasileira (LGPD). A lista completa e atualizada é mantida pelo Google em
<a href="https://developers.google.com/admob/android/privacy/play-data-disclosure">developers.google.com/admob/android/privacy/play-data-disclosure</a>.</p>
<p><strong>Dados enviados ao Google Play Jogos:</strong> o progresso do jogo descrito na seção 2,
para o salvamento na nuvem (seção 3).</p>
<p>O jogo não possui serviço próprio de análise, rastreamento de uso ou métricas.</p>

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
do seu progresso vinculada à <strong>sua própria conta Google</strong>. Serve para recuperar o
jogo depois de reinstalar ou ao trocar de aparelho.</p>

<p><strong>O que é enviado:</strong> a mesma lista da seção 2. Junto vai uma descrição curta do
save com o seu recorde (por exemplo, "Recorde 1240 m"), que aparece na tela de saves do próprio
app Google Play Jogos.</p>

<p><strong>Para onde vai:</strong> para a infraestrutura do Google, dentro da área reservada ao
jogo na sua conta Google. Não existe servidor do desenvolvedor. O tratamento dos dados pelo Google
é regido pela
<a href="https://policies.google.com/privacy">Política de Privacidade do Google</a>.</p>

<p><strong>Quando acontece:</strong> o jogo tenta entrar silenciosamente no Google Play Jogos ao
abrir. Se a sua conta já estiver conectada ao Play Jogos no aparelho, a sincronização ocorre
automaticamente: o save da nuvem é baixado na abertura e enviado ao fim de cada partida.</p>

<p><strong>Sem a nuvem:</strong> o jogo funciona sem o Play Jogos. Sem conexão, sem internet, ou
com a conta desconectada, tudo fica salvo apenas no aparelho. Para desativar, desconecte sua conta
em <em>app Google Play Jogos → Mais → Configurações</em>, ou revogue o acesso do jogo em
<a href="https://myaccount.google.com/permissions">myaccount.google.com/permissions</a>.</p>

<h2>4. Anúncios (Google AdMob)</h2>
<p>O jogo exibe anúncios fornecidos pelo <strong>Google AdMob</strong>, em três formatos: vídeos
premiados e opcionais (reviver, dobrar moedas, item grátis na loja), anúncio intersticial entre
partidas, e banner fixo em algumas telas de menu.</p>

<p><strong>O que é enviado:</strong> a cada anúncio solicitado, o SDK do AdMob envia ao Google o
identificador de publicidade do seu aparelho (um código que o Android expõe para esse fim, e que
você pode resetar ou desativar nas configurações do aparelho) e os dados técnicos listados na
seção 1, para que o AdMob escolha, exiba e meça o desempenho do anúncio. Nenhum dado do jogo —
progresso, moedas, estatísticas — acompanha essa requisição. Esses dados vão direto do seu aparelho
para o Google.</p>

<p><strong>Consentimento:</strong> nas regiões em que a lei exige, como o Espaço Econômico Europeu
e o Reino Unido, o jogo exibe o formulário de consentimento da própria Google (UMP — User
Messaging Platform) antes de solicitar anúncios. Em qualquer região, você pode revisar ou alterar
suas escolhas de anúncios personalizados em
<a href="https://adssettings.google.com">adssettings.google.com</a> ou nas configurações de
publicidade do Android.</p>

<p><strong>Anúncios premiados e demais formatos:</strong> os vídeos premiados são sempre
opcionais, e o jogo funciona sem assisti-los. O intersticial e o banner aparecem automaticamente
durante o uso normal do app. Hoje não existe compra de remoção de anúncios paga em dinheiro real —
a loja usa apenas moeda do próprio jogo.</p>

<p>O tratamento desses dados pelo Google é regido pela
<a href="https://policies.google.com/privacy">Política de Privacidade do Google</a> e pela
<a href="https://support.google.com/admob/answer/6128543">política de privacidade do AdMob</a>.</p>

<h2>5. Para que os dados são usados</h2>
<ul>
  <li><strong>Dados de jogo (seções 2 e 3):</strong> fazer o jogo funcionar e permitir que você
      recupere o seu progresso pelo Google Play Jogos.</li>
  <li><strong>Dados do AdMob (seções 1 e 4):</strong> exibir e medir anúncios.</li>
</ul>

<h2>6. Processamento fora do Brasil</h2>
<p>O Google processa os dados descritos nesta política em servidores localizados em vários países,
inclusive fora do Brasil, conforme as políticas do próprio Google indicadas nas seções 3 e 4.</p>

<h2>7. Seus controles</h2>
<p>Como o jogo não possui servidor do desenvolvedor, os controles sobre os seus dados ficam nos
serviços do Google e do Android:</p>
<ul>
  <li>save na nuvem: app Google Play Jogos e
      <a href="https://myaccount.google.com/permissions">myaccount.google.com/permissions</a>
      (seção 3);</li>
  <li>anúncios e identificador de publicidade: configurações de anúncios do Android e
      <a href="https://adssettings.google.com">adssettings.google.com</a> (seção 4);</li>
  <li>dados locais: configurações do Android, conforme a seção 8.</li>
</ul>

<h2>8. Como apagar seus dados</h2>
<p><strong>No aparelho:</strong></p>
<ul>
  <li>desinstalar o aplicativo remove todos os dados locais; ou</li>
  <li><em>Configurações do Android → Apps → The Nose Journey → Armazenamento → Limpar dados</em>.</li>
</ul>
<p><strong>Na nuvem:</strong> o save fica na sua conta Google.</p>
<ul>
  <li>no app <strong>Google Play Jogos</strong>, abra a biblioteca, selecione The Nose Journey e
      exclua o jogo salvo; ou</li>
  <li>remova o acesso do jogo em
      <a href="https://myaccount.google.com/permissions">myaccount.google.com/permissions</a>.</li>
</ul>
<p>Desinstalar o app não apaga por si só a cópia na nuvem; use um dos caminhos acima para removê-la
também. A cópia na nuvem fica sob o Google (Google Play Jogos), sujeita à política de retenção do
próprio Google — ver <a href="https://policies.google.com/privacy">Política de Privacidade do
Google</a>. Os dados coletados pelo AdMob (seção 4) são processados pelo Google; para zerar o
identificador de publicidade ou desativar a personalização, use as configurações de anúncio do
Android ou <a href="https://adssettings.google.com">adssettings.google.com</a>.</p>

<h2>9. Permissões</h2>
<p>O aplicativo e o SDK de anúncios incluído nele declaram as seguintes permissões do Android:</p>
<ul>
  <li><strong>Internet</strong> (<code>INTERNET</code>) — usada pelo salvamento na nuvem (seção 3) e
      pela exibição de anúncios (seção 4);</li>
  <li><strong>Estado da rede</strong> (<code>ACCESS_NETWORK_STATE</code>) — usada pelo SDK de
      anúncios para verificar se há conexão antes de carregar um anúncio;</li>
  <li><strong>ID de publicidade</strong> (<code>AD_ID</code>) — permite ao SDK de anúncios ler o
      identificador de publicidade do aparelho (seção 4), em versões do Android que exigem essa
      permissão.</li>
</ul>

<h2>10. Crianças</h2>
<p>O conteúdo do jogo em si não contém violência, linguagem imprópria, conteúdo sexual, chat ou
interação entre usuários.</p>
<p>O jogo usa o AdMob padrão (não a versão certificada para anúncios direcionados a crianças).
Por isso, seguindo a política do Google Play, este app <strong>não é destinado nem direcionado a
crianças menores de 13 anos</strong> e não participa do programa Designed for Families.</p>
<p>O recurso de salvamento na nuvem depende da conta Google do próprio aparelho, cujos requisitos
de idade e supervisão parental são definidos pelo Google, inclusive no Family Link.</p>

<h2>11. Serviços de terceiros</h2>
<p>O desenvolvedor não recebe dados dos usuários. Dois serviços do Google tratam dados, cada um
para a finalidade descrita nesta política, e o tratamento feito por eles é regido pelas políticas
do próprio Google:</p>
<ul>
  <li><strong>Google Play Jogos</strong> — guarda e devolve o seu progresso de jogo (seção 3). Não
      é usado para publicidade.</li>
  <li><strong>Google AdMob</strong> — recebe o identificador de publicidade e os dados técnicos do
      aparelho (seções 1 e 4) para servir e medir anúncios.</li>
</ul>

<h2>12. Alterações nesta política</h2>
<p>Esta política pode ser alterada a qualquer momento, por exemplo quando o jogo passar a incluir
novos recursos ou serviços. A data de "última atualização" no topo indica a versão vigente.</p>

<h2>13. Contato</h2>
<p>Dúvidas sobre esta política: <strong>furtado.gamesrr@gmail.com</strong></p>

</body>
</html>
