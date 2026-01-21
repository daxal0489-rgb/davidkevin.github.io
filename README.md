# davidkevin.github.io<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Portfolio – Projet Infrastructure Linux</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      background: #f9f9f9;
      color: #222;
      line-height: 1.6;
    }
    h1, h2 {
      color: #003366;
    }
    .section {
      background: white;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    ul {
      margin-left: 20px;
    }
    .badge {
      display: inline-block;
      background: #003366;
      color: white;
      padding: 5px 10px;
      margin: 5px 5px 5px 0;
      border-radius: 5px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <h1>Portfolio – Projet Infrastructure Systèmes & Réseaux</h1>
  <p><strong>Profil :</strong> Technicien Systèmes et Réseaux (TSSR)</p>

  <div class="section">
    <h2>📌 Projet : Mise en place d'une infrastructure Linux (DHCP + DNS)</h2>
    <p>
      Ce projet a été réalisé dans le cadre de ma formation.  
      L’objectif était de concevoir et déployer une infrastructure réseau fonctionnelle sous Linux
      permettant la distribution automatique des adresses IP et la résolution de noms.
    </p>
  </div>

  <div class="section">
    <h2>🎯 Objectif du projet</h2>
    <ul>
      <li>Installer un serveur Linux</li>
      <li>Mettre en place un service DHCP fonctionnel</li>
      <li>Déployer un serveur DNS interne avec Bind9</li>
      <li>Permettre aux clients Linux et Windows d’accéder au réseau et à Internet</li>
      <li>Mettre en œuvre un routage avec NAT</li>
    </ul>
  </div>

  <div class="section">
    <h2>🖥️ Environnement technique</h2>
    <ul>
      <li>Ubuntu Server 24.04 LTS</li>
      <li>Linux Desktop (client)</li>
      <li>Windows 10 (client)</li>
      <li>VMware Workstation</li>
      <li>Bind9 (DNS)</li>
      <li>isc-dhcp-server (DHCP)</li>
      <li>Netplan</li>
      <li>iptables + iptables-persistent</li>
    </ul>
  </div>

  <div class="section">
    <h2>🌐 Architecture réseau</h2>
    <ul>
      <li>Serveur : lx01 (Ubuntu Server)</li>
      <li>Clients : lx02 (Linux Desktop), Win10</li>
      <li>Deux réseaux configurés :</li>
      <ul>
        <li>VMnet8 (NAT) : 192.168.100.0/24</li>
        <li>VMnet2 (LAN interne) : 192.168.10.0/24</li>
      </ul>
      <li>Le serveur joue le rôle de passerelle entre les deux réseaux</li>
    </ul>
  </div>

  <div class="section">
    <h2>⚙️ Réalisations techniques</h2>
    <ul>
      <li>Configuration IP statique avec Netplan</li>
      <li>Mise en place du routage IP (ip_forward)</li>
      <li>Configuration NAT avec iptables (MASQUERADE)</li>
      <li>Installation et configuration du serveur DHCP</li>
      <li>Déploiement d’un domaine interne (Boot.local)</li>
      <li>Configuration du serveur DNS Bind9 avec zones directe et inverse</li>
      <li>Tests fonctionnels avec ping et résolution de noms</li>
    </ul>
  </div>

  <div class="section">
    <h2>✅ Résultats obtenus</h2>
    <ul>
      <li>Les clients reçoivent automatiquement une adresse IP via DHCP</li>
      <li>La résolution DNS interne fonctionne correctement</li>
      <li>Les postes clients accèdent à Internet via le serveur</li>
      <li>L’infrastructure est stable et fonctionnelle après redémarrage</li>
    </ul>
  </div>

  <div class="section">
    <h2>🧠 Compétences démontrées</h2>
    <span class="badge">Linux</span>
    <span class="badge">Réseaux TCP/IP</span>
    <span class="badge">DHCP</span>
    <span class="badge">DNS</span>
    <span class="badge">Bind9</span>
    <span class="badge">iptables</span>
    <span class="badge">Netplan</span>
    <span class="badge">Virtualisation</span>
    <span class="badge">Diagnostic réseau</span>
  </div>

  <div class="section">
    <h2>📫 Contact</h2>
    <p>
      Tu peux ajouter ici :
      <ul>
        <li>Email professionnel</li>
        <li>LinkedIn</li>
        <li>GitHub</li>
      </ul>
    </p>
  </div>

</body>
</html>
