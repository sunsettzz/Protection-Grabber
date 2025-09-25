# Protection-Grabber 

<p>É evidente que ninguém deseja ser vítima de um 'grabber'. Pensando nisso, preparei um guia simples e direto para quem precisa. Vamos ao ponto: antes de tudo, é importante entender como esse tipo de programa age:</p>

<h2 style="color: #007bff; font-size: 24px;">Como o malware é espalhado:</h2>
<p>Na maioria das vezes, grabbers vêm disfarçados em arquivos piratas, programas de trapaça, spoofers ou até em aplicativos comuns, mas disponibilizados em sites maliciosos.</p>

<h2 style="color: #28a745; font-size: 24px;">Execução:</h2>
<p>Ao abrir ou instalar o arquivo malicioso, ele pode encerrar programas — como Discord, navegadores e outros — para injetar código e capturar tokens, cookies e outros dados.</p>

<h2 style="color: #ffc107; font-size: 24px;">Obtenção do Token:</h2>
<p>O grabber procura extrair os tokens de autenticação salvos no computador da vítima, focando especialmente nas pastas do Discord.</p>

<h2 style="color: #dc3545; font-size: 24px;">Exfiltração de Dados:</h2>
<p>Essas informações costumam ser enviadas para uma central — muitas vezes por meio de uma webhook vinculada a um servidor específico. Embora o Discord tente bloquear essas práticas e derrube muitos desses servidores, várias centrais de controle ainda funcionam no Telegram. O envio dos dados normalmente é feito por protocolos como HTTP ou FTP.</p>

<h2 style="color: #17a2b8; font-size: 24px;">Execução com o Token:</h2>
<p>Com o token obtido, o invasor consegue burlar a verificação de IP (como a confirmação por e-mail de um novo endereço) e fazer login sem precisar de códigos adicionais. Contudo, o token sozinho não permite alterar a senha. Por isso, muitos grabbers também coletam os cookies do navegador para acessar o e-mail da vítima e efetuar a troca da senha.</p>

<h2 style="color: #6f42c1; font-size: 24px;">Como se proteger:</h2>
<ul>
  <li>Evite clicar em links desconhecidos.</li>
  <li>Ative a verificação em duas etapas (2FA).</li>
  <li>Mantenha um antivírus ativo.</li>
  <li>Use extensões que bloqueiem o salvamento automático de cookies.</li>
</ul>

<h2 style="color: #e83e8c; font-size: 24px;">Como funciona a extensão:</h2>
<p>Existem diversos tipos de extensões de gerenciador de senhas, sendo as mais populares o LastPass e o DashLane. Pessoalmente, prefiro o DashLane. O funcionamento é simples: quando você salva uma senha ao fazer login em qualquer site, ela é guardada no banco de dados da extensão (100% confidencial) em vez de ficar armazenada nos cookies do seu computador. Dessa forma, se você for alvo de um grabber, seus cookies estarão intactos.</p>

<h2 style="color: #dc3545; font-size: 24px;">Proteções:</h2>
<ul>
  <li>Extensão recomendada - 🔐 <a href="https://www.dashlane.com" target="_blank">Dashlane</a></li>
  <li>Antivírus recomendado - 🛡️ <a href="https://www.malwarebytes.com" target="_blank">Malwarebytes</a></li>
</ul>

<img src="https://png.pngtree.com/element_origin_min_pic/17/10/08/21c37bf4ecc5e2a3675ae79fa2dce7c8.jpg" alt="Segurança Digital" style="display: block; margin: 20px auto; max-width: 100%; height: auto;">
