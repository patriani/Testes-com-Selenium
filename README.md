# Testes-com-Selenium
<h4><i>Scripts</i> de teste funcional utilizando Partições de Equivalência sobre o projeto em: https://github.com/patriani/AnalisandoNumeros</h4>
<h2>Tutorial IDE</h2>
<p>Para começar a usar o Selenium a IDE é uma ótima opção. Suere-se o seguinte passo a passo para primeiro contato:</p>
<ol>
<li>Verifique se o seu navegador oferece o <i>plugin</i>: "Selenium IDE";</li>
  <ol><li>Caso não tenha, adote o <i>Firefox</i> ou <i>Chrome</i>.</li></ol>
<li>Adicione o <i>plugin</i>;</li>
<li>Escolha uma página <i>Web</i>;</li>
<li>Inicie pelo recurso de gravação;</li>
<li>Nomeie o projeto para salvá-lo futuramente;</li>
<li>Insira a <i>url</i> da página <i>web</i> escolhida;</li>
<li>Inicie a opção de gravação (<i>pop-up</i>);</li>
<li>Interaja com o navegador recém aberto pela ferramente para gerar <i>script</i>.</li>
</ol>
<p>Neste ponto será possível acessar recursos em tempo de execução como excluir ou incluir comandos no <i>script</i>. Após encerrar a gravação é possível <a href='https://www.tutorialandexample.com/selenium-ide-commands'>adicionar comandos</a>. Alguns comandos como leitura de avisos (<i>alerts</i>) não podem ser capturadas pelo recurso de gravação.</p>
<p>O conjunto de comandos fornecidos para execução na IDE é limitado se comparado ao alcance de ações possíveis na abordagem <i>Webdriver</i>. Para conhecer melhor sobre o <i>Webdriver</i> e <i>Grid</i> então leia o relatório deste repositório e/ou a <a href = 'https://www.selenium.dev/selenium-ide/docs/en/introduction/getting-started'>documentação</a> da Selenium. Para essas abordagens é possível exportar o script, naturalmente com extensão ".SIDE", para as linguagens de programação disponíveis.</p>
<p>NOTA: Para elaboração dos testes o cenário foi: Sistema Operacional Windows e Browser Chrome.</p>

<h2>Caso haja interesse em replicar os testes documentados no relatório siga as instruções abaixo:</h2>
<p>NOTA: passo a passo considerando SO Windows e <a href = 'https://www.apachefriends.org/pt_br/download.html'>Xampp</a> como provedor de servidor local.</p>
<ol>
  <li><a href = 'https://github.com/patriani/AnalisandoNumeros'>Baixe</a> os arquivos e insira-os na pasta htdocs do Xampp;</li>
  <li>Baixe ou copie os casos de teste deste repositório(arquivos ".SIDE");</li>
  <li>Inicie o Xampp (pelo console ou atalho de início;)</li>
  <li>Verifique o acesso ao projeto por: http://127.0.0.1//AnalisandoNumeros-master/index.html;</li>
  <li>Abra a extensão, previamente adicionada ao navegador;</li>
  <li>Escolha um nome para o projeto e insira a url do <u>item 4</u> como base;</li>
  <li>Certifique-se de que o <i>script</i> correto foi selecionado e inicie o teste.</li>
<ol>
   
