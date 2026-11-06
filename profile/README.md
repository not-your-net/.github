<p align="center">
  <a href="https://www.not-your.net">
    <img src="https://www.not-your.net/brand/logo.png" alt="Not Your Network" height="96">
  </a>
</p>

<h1 align="center">Not Your Network</h1>

<p align="center">
  Selbst gehostete Infrastruktur, Web-Projekte und Homelab – gebaut, betrieben und dokumentiert bei <b>not-your.net</b>.
</p>

<p align="center">
  <a href="https://www.not-your.net">Website</a> ·
  <a href="https://portal.not-your.net">Portal</a> ·
  <a href="https://www.not-your.net/projects">Projekte</a> ·
  <a href="https://www.not-your.net/contact">Kontakt</a>
</p>

---

## Worum es geht

Not Your Network ist ein Ort für IT-Projekte, die nicht in der Cloud eines anderen laufen, sondern auf eigener Hardware: eigener Mailserver, eigenes Login, eigene Website, eigenes Netzwerk. Alles hier ist selbst gehostet und wird von Grund auf selbst aufgebaut.

## Projekte

| Repository | Beschreibung | Technik |
|---|---|---|
| [**www.not-your.net**](https://github.com/not-your-net/www.not-your.net) | Website mit Portfolio, Projektseiten, Snake-Spiel mit Bestenliste und Shop für E-Mail-Adressen | React · Vite · Express · MySQL · Stripe |
| [**portal**](https://github.com/not-your-net/portal) | Self-Service-Portal: Anmeldung per LDAP, Passwort ändern, E-Mail-Aliase verwalten | PHP 8.2 · LDAP · Mailcow-API · MariaDB |
| [**design**](https://github.com/not-your-net/design) | Gemeinsames Design (Farben, Komponenten, Logo, das Llama) für Website und Portal, eingebunden per `git subtree` | CSS · JavaScript |
| [**nyn-pterodactyl-panel**](https://github.com/not-your-net/nyn-pterodactyl-panel) | Angepasster Fork des Pterodactyl Panels für Gameserver | PHP · React · Docker |

## Infrastruktur

- **Netzwerk:** pfSense als Firewall und VPN-Gateway, getrennte Netze für LAN und Management
- **Server:** Proxmox-Homelab mit Containern und VMs
- **Mail:** eigener Mailserver auf Basis von Mailcow für `@not-your.net`-Adressen
- **Identität:** zentraler LDAP-Verzeichnisdienst für Portal und VPN
- **Dienste:** Gameserver, Media-Server, Automatisierung und mehr

## Mitmachen

Fehler gefunden oder eine Idee? Gern ein Issue im passenden Repository eröffnen oder über die [Kontaktseite](https://www.not-your.net/contact) melden.

<p align="center"><sub>Made with ☕ and a llama · <a href="https://www.not-your.net">not-your.net</a></sub></p>
