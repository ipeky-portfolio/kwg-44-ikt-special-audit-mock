# Bericht: Feststellungen mit hohem Risiko (High-Risk Supervisory Findings)

Dieser Bericht detailliert die kritischsten Abweichungen, die während der IKT-Sonderprüfung nach §44 KWG identifiziert wurden. Diese Feststellungen erfordern eine sofortige Maßnahmenplanung und Umsetzung.



## 1. Feststellung: Fehlende getestete Ausstiegsstrategien (Missing Tested Exit Strategies)

* **Beschreibung:** Für kritische Cloud-Dienstleister existieren zwar vertragliche Ausstiegsklauseln, jedoch keine dokumentierten und **geprüften (getesteten)** Ausstiegsstrategien. Die Fähigkeit, kritische Daten zu migrieren oder den Betrieb kurzfristig auf einen anderen Anbieter oder On-Premise zu verlagern, ist nicht nachgewiesen.
* **Regulatorischer Bezug:** MaRisk AT 9, BAIT Kap. 6.
* **Risiko:** Hohes **Vendor Lock-in** Risiko. Bei Ausfall oder Insolvenz des Cloud-Providers ist der Geschäftsbetrieb akut gefährdet.



## 2. Feststellung: Unzureichende DR-Testabdeckung (Insufficient DR Testing Coverage)

* **Beschreibung:** Die Notfalltests (Disaster Recovery Tests) decken nicht alle kritischen Systeme ab. Es wurden nur Teilkomponenten getestet. Szenarien wie der Totalausfall des primären Rechenzentrums (RZ) oder ein weitreichender Ransomware-Angriff wurden nicht simuliert.
* **Regulatorischer Bezug:** MaRisk AT 7.3, BAIT Kap. 5.
* **Risiko:** Nicht erkannte Schwachstellen in den Notfallplänen. Die Wiederherstellung (RTO/RPO) im Ernstfall ist nicht gewährleistet.
