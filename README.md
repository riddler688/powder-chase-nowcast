# powder-chase-nowcast

Hilfs-Workflow für Powder Chase: holt alle 15 Minuten den GeoSphere-Nowcast (Regenradar, Neuschnee der nächsten Stunden)
und lädt ihn auf den Webspace. Öffentlich, weil Standard-Runner in öffentlichen Repos keine Workflow-Minuten kosten.

Hier liegt kein Code: Der Workflow holt die Skripte zur Laufzeit aus dem privaten Haupt-Repo.

Secrets: `MAIN_REPO_TOKEN` (fine-grained, nur Haupt-Repo, Contents: read), `FTP_HOST`, `FTP_USER`, `FTP_PASSWORD`,
optional `FTP_DIR`, `GEOSPHERE_RELAY`, `GEOSPHERE_RELAY_KEY`.

Fremde Pull Requests werden nicht angenommen.
