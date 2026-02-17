<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sistema de Correu Electrònic - Components i Protocols</title>
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
      background-color: #f9f9f9;
      color: #333;
    }
    h1, h2, h3 {
      color: #2c3e50;
    }
    h1 {
      text-align: center;
      border-bottom: 2px solid #3498db;
      padding-bottom: 10px;
    }
    section {
      margin-bottom: 40px;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    .component {
      margin-bottom: 30px;
    }
    ul {
      padding-left: 25px;
    }
    .highlight {
      background-color: #e8f4fd;
      padding: 2px 6px;
      border-radius: 4px;
    }
    code {
      background: #eee;
      padding: 2px 5px;
      border-radius: 4px;
      font-family: Consolas, monospace;
    }
  </style>
</head>
<body>

  <h1>Sistema de Correu Electrònic</h1>
  <p style="text-align:center; color:#555;">Components principals, protocols i opcions de configuració</p>

  <section>
    <h2>1. MUA (Mail User Agent)</h2>
    <p>És l'agent amb què interactua l'usuari final. És el client de correu; no mou correu entre servidors, només envia al MTA i rep de la bústia (MDA).</p>
    
    <p><strong>Tasques:</strong></p>
    <ul>
      <li>Redactar i enviar correus.</li>
      <li>Llegir, organitzar i filtrar missatges.</li>
      <li>Accedir a la bústia remota mitjançant IMAP o POP3.</li>
    </ul>

    <p><strong>Exemples:</strong></p>
    <ul>
      <li>Aplicacions d'escriptori: Thunderbird, Outlook.</li>
      <li>Aplicacions web: Gmail Web, Outlook Web.</li>
      <li>Aplicacions mòbils: iOS Mail, Gmail app.</li>
    </ul>
  </section>

  <section>
    <h2>2. MTA (Mail Transfer Agent)</h2>
    <p>És un programa que corre en el servidor, encarregat de transmetre correu entre servidors. És el «carter» del sistema de correu.</p>
    
    <p><strong>Tasques:</strong></p>
    <ul>
      <li>Rebre missatges d'un MUA (SMTP).</li>
      <li>Enviar missatges a uns altres MTA segons el destí (SMTP).</li>
      <li>Col·locar missatges en la cua de lliurament si el servidor de destí no està disponible.</li>
      <li>Consultar DNS (MX) per decidir a quin servidor enviar el correu.</li>
    </ul>

    <p><strong>Exemples:</strong> Postfix, Sendmail, Exim, Microsoft Exchange.</p>
  </section>

  <section>
    <h2>3. MDA (Mail Delivery Agent)</h2>
    <p>També un programa en el servidor, encarregat de lliurar el missatge a la bústia de l'usuari final, aplicant filtres o regles si és necessari.</p>
    
    <p><strong>Tasques:</strong></p>
    <ul>
      <li>Rebre missatges del MTA local.</li>
      <li>Aplicar regles de filtrat (p. ex., Spam, regles de classificació).</li>
      <li>Guardar el correu en el format de bústia usada (Maildir, mbox, base de dades).</li>
    </ul>

    <p><strong>Exemples:</strong> Dovecot LDA, Procmail, Maildrop.</p>
  </section>

  <section>
    <h2>C) Protocols de correu</h2>
    <p>SMTP, POP i IMAP són independents de la plataforma i permeten comunicació entre sistemes operatius i clients diferents.</p>

    <h3>1. SMTP</h3>
    <p>Estàndard d'Internet per a l'intercanvi de correu electrònic. Transporta el correu sortint des de l'usuari remitent fins al servidor MTA final.</p>
    <p><strong>Ports:</strong> 25 (entre MTAs), 587 o 465 (clients autenticats).</p>
    <p><strong>Flux bàsic de connexió:</strong></p>
    <ol>
      <li>L’emissor obre connexió TCP amb el servidor de destí</li>
      <li>El receptor contesta amb 220 service SMTP</li>
      <li>L’emissor s’identifica amb HELO</li>
      <li>El receptor respon amb 250 OK o 421 Service Not Available</li>
    </ol>
    <p>Després continuen comandes com: <code>MAIL FROM</code>, <code>RCPT TO</code>, <code>DATA</code>.</p>

    <h3>2. POP3</h3>
    <p>Permet descarregar missatges al client i normalment esborrar-los del servidor. No manté sincronització.</p>
    <p><strong>Ports:</strong> 110 (sense xifrar), 995 (amb SSL/TLS).</p>
    <p><strong>Fases:</strong> Connexió → Autenticació → Transacció → Actualització.</p>

    <h3>3. IMAP</h3>
    <p>Permet accedir i gestionar missatges directament al servidor, mantenint sincronització entre dispositius.</p>
    <p><strong>Característiques principals:</strong></p>
    <ul>
      <li>Accés des de qualsevol màquina amb sincronització</li>
      <li>Manipulació remota de bústies</li>
      <li>Compatible amb MIME (adjunts)</li>
      <li>Connexions simultànies des de diversos clients</li>
    </ul>
  </section>

  <section>
    <h2>D) Clients de correu</h2>
    <p>Tipus principals:</p>
    <ul>
      <li><strong>Client instal·lat a l’ordinador:</strong> descarrega correu localment (ex. Thunderbird).</li>
      <li><strong>Client via web:</strong> accés des del navegador (ex. Gmail, Outlook.com).</li>
      <li><strong>Client en el servidor:</strong> gestionen bústies i enrutament (Postfix, Dovecot, Exchange).</li>
    </ul>

    <h3>Opcions per configurar un servei de correu a l'empresa</h3>
    <ol>
      <li>Utilitzar servei públic (Gmail, Hotmail/Outlook) → tot gestionat pel proveïdor.</li>
      <li>Client web autogestionat (SquirrelMail, Horde…) apuntant a servidor extern (possible però limitat).</li>
      <li>Servidor de correu intern (Postfix + Dovecot o Exchange) amb domini propi, registres MX/SPF i tallafocs recomanat.</li>
    </ol>
  </section>

</body>
</html>
