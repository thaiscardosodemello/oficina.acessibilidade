<img height="200px" src="https://raw.githubusercontent.com/thaiscardosodemello/oficina.acessibilidade/refs/heads/main/assets/oficina-de-acessibilidade.png" alt="Oficina de Acessibilidade"/>

<h1 align="center" style="border-bottom: none!important;padding-bottom:0px!important;">Oficina de Acessibilidade</h1>
<h3 align="center">Abner Joia</h3>

<br>
<p>Este repositório tem como objetivo apresentar e aplicar os conceitos de acessibilidade na web, capacitando desenvolvedores a criar experiências web inclusivas para todos os usuários, independentemente de suas habilidades. A oficina busca fornecer um guia prático sobre como melhorar a acessibilidade de aplicações web, com foco em boas práticas, diretrizes e implementações técnicas.</p>

<p>Acesso a apresentação <a href="https://github.com/thaiscardosodemello/poo.exercicios/tree/master/src/main/java/com/poolista1">🔗</a></p>

<h2>Objetivos da Oficina</h2>
<ul>
    <li><strong>Construção de HTML estruturado:</strong> Ensinar como utilizar tags semânticas do HTML5 para melhorar a acessibilidade.</li>
    <li><strong>Navegação via teclado (TAB):</strong> Garantir que a navegação do site seja intuitiva e acessível através do teclado.</li>
    <li><strong>Uso de texto alternativo:</strong> Aprender a aplicar textos alternativos para imagens, ícones e outros elementos visuais.</li>
    <li><strong>Atributos WAI-ARIA:</strong> Uso de atributos adicionais para melhorar a acessibilidade em aplicativos web complexos e interativos.</li>
    <li><strong>Ajuste de contraste e fontes:</strong> Garantir que o contraste entre o texto e o fundo seja adequado e permitir que o tamanho das fontes seja ajustável.</li>
    <li><strong>Atalhos de navegação:</strong> Implementar atalhos de navegação por teclado para melhorar a experiência do usuário.</li>
</ul>

<h2>O que foi abordado na oficina?</h2>

<h3>1. Uso de Tags HTML Semânticas</h3>
<ul>
    <li>Como utilizar tags HTML5 de forma estruturada e semântica (ex: <code>&lt;header&gt;</code>, <code>&lt;footer&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;nav&gt;</code>, <code>&lt;article&gt;</code>, <code>&lt;section&gt;</code>, etc.).</li>
    <li>Evitar o uso excessivo de <code>&lt;div&gt;</code> e outras tags genéricas, priorizando o uso de tags que representem o significado do conteúdo.</li>
</ul>

<h3>2. Atributos de Acessibilidade</h3>
<ul>
    <li><strong>alt</strong>: Texto alternativo para imagens e elementos gráficos.</li>
    <li><strong>aria-label</strong>: Descrição de elementos que não possuem texto visível, como botões ou links.</li>
    <li><strong>aria-pressed</strong>: Indicação de estado de botões booleanos (ex: Ativado/Desativado).</li>
</ul>

<h3>3. Navegação com o Teclado</h3>
<ul>
    <li>Como garantir que a navegação seja possível apenas com o teclado, utilizando o <code>tabIndex</code> corretamente.</li>
    <li>Implementação de atalhos de navegação usando <code>accessKey</code> para facilitar o acesso a seções principais do site.</li>
</ul>

<h3>4. Contraste de Cores</h3>
<ul>
    <li>Como garantir um contraste adequado entre texto e fundo para usuários com baixa visão.</li>
    <li>Ferramentas para verificar as taxas de contraste (ex: calculadora de contraste).</li>
</ul>

<h3>5. Formulários Acessíveis</h3>
<ul>
    <li>Relacionamento entre <code>&lt;input&gt;</code> e <code>&lt;label&gt;</code> usando os atributos <code>htmlFor</code> e <code>id</code>.</li>
    <li>Uso de <code>&lt;fieldset&gt;</code> e <code>&lt;legend&gt;</code> para agrupar e descrever elementos de formulário.</li>
</ul>

<h3>6. WAI-ARIA (Web Accessibility Initiative – Accessible Rich Internet Applications)</h3>
<ul>
    <li>Como usar atributos WAI-ARIA (<code>role</code>, <code>states</code>, <code>properties</code>) para melhorar a acessibilidade de aplicativos interativos.</li>
    <li>Exemplos de como aplicar <code>role</code>, <code>aria-label</code>, <code>aria-live</code>, entre outros.</li>
</ul>

<h2>Ferramentas e Recursos</h2>
<ul>
    <li><strong>Leitores de tela</strong>: Ferramentas como o <a href="https://chrome.google.com/webstore/detail/screen-reader/kgejglhpjiefppelpmljglcjbhoiplfn">Leitor de tela do Chrome</a> ajudam a testar a acessibilidade para deficientes visuais.</li>
    <li><strong>Access Monitor</strong>: <a href="https://accessmonitor.acessibilidade.gov.pt/">Ferramenta para análise de acessibilidade</a> que verifica se o site atende aos critérios da WCAG.</li>
    <li><strong>V-Libras</strong>: Ferramenta de tradução para Língua Brasileira de Sinais (Libras). <a href="https://vlibras.gov.br/doc/widget/installation/webpageintegration.html">Documentação V-Libras</a>.</li>
</ul>

<h2>Referências</h2>
<ul>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/Accessibility/What_is_accessibility">MDN Web Docs - Acessibilidade</a></li>
    <li><a href="https://www.w3.org/TR/WCAG21/">Diretrizes WCAG - W3C</a></li>
    <li><a href="https://vlibras.gov.br/doc/widget/installation/webpageintegration.html">V-Libras - Documentação</a></li>
    <li><a href="https://github.com/AbJoia/oficina-acessibilidade-desafio">Desafio de Acessibilidade - GitHub</a></li>
    <li><a href="https://www.w3.org/TR/wai-aria/">WAI-ARIA - W3C</a></li>
    <li><a href="https://www.acessibilidade.gov.br/">Acessibilidade.gov.br</a></li>
    <li><a href="https://accessmonitor.acessibilidade.gov.pt/">Access Monitor</a></li>
    <li><a href="https://reactnative.dev/docs/accessibility">React Native Acessibilidade</a></li>
    <li><a href="https://emag.governoeletronico.gov.br/">EMAG - Governo Eletrônico</a></li>
    <li><a href="https://www.normas.com.br/visualizar/projeto-nbr/48953/projeto-abnt-nbr-17060-acessibilidade-em-aplicativos-de-dispositivos-moveis-requisitos">NBR 17060 - Acessibilidade em Aplicativos Móveis</a></li>
</ul>
