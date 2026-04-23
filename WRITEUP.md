# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

Für die Bereitstellung der CMS-App würde ich Azure App Service statt einer virtuellen Maschine wählen. Für dieses Projekt ist App Service aus meiner Sicht die bessere Lösung, weil die Einrichtung einfacher ist und deutlich weniger Wartung anfällt. Ich muss mich nicht selbst um das Betriebssystem, Updates oder die Serverkonfiguration kümmern, was den gesamten Deployment-Prozess viel unkomplizierter macht.

Auch bei Kosten, Skalierbarkeit und Verfügbarkeit passt App Service besser zu einer kleinen Webanwendung wie dieser. Eine VM würde hier eher zusätzlichen Aufwand verursachen, ohne dass ich davon wirklich profitiere. Da es sich um eine eher einfache CMS-App handelt, ist die verwaltete Lösung für mich die praktischere Wahl.

### Assess app changes that would change your decision.

Anders würde ich mich nur entscheiden, wenn sich die Anforderungen der Anwendung deutlich ändern würden. Wenn ich zum Beispiel spezielle Software auf Betriebssystemebene installieren müsste, eine sehr individuelle Serverkonfiguration bräuchte oder insgesamt mehr Kontrolle über die Umgebung notwendig wäre, dann könnte eine VM sinnvoller sein. Für diese Aufgabe finde ich App Service aber passender.
