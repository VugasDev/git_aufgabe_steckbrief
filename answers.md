**Was ist der Unterschied zwischen Working Directory, Staging Area und Repository?**

* Working Directory ist der Ordner auf der Festplatte, die Staging Area ist der Zwischenspeicher mit den Änderungen als Commit. Das Repository speichert diese Snapshots dauerhaft als Commit in der Git-Historie.



**Woran erkennst du, ob ein Merge Fast-Forward war?**

* Man erkennt es an der Git-Ausgabe "Fast-forward" beim mergen und daran, dass kein neuer Merge-Commit erstellt wurde.



**Warum kann git merge --ff-only manchmal fehlschlagen?**

* Der Befehl schlägt fehl, wenn die Historie beider Branches divergiert ist, also wenn auf dem Ziel-Branch neue Commits existieren, die auf dem Quell-Branch fehlen.



**Was ist der Vorteil, Änderungen zuerst auf einem Branch wie dev zu machen?**

* Dadurch hält man den Haupt-Branch stehts stabil und produktionsreif. Neue Features und Fixes können so also isoliert entwickelt und getestet werden.



**Mit welchem Befehl siehst du den aktuellen Branch?**

* "git branch --show-current"



**Mit welchen Befehlen machst du Änderungen sichtbar und dauerhaft (Stichworte: Staging \& Commit)?**

* "git add <dateiname>" oder "git add ."
* "git commit -m 'Nachricht'"

