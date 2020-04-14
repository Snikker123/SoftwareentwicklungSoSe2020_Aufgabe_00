# SoftwareentwicklungSoSe2020_Aufgabe_00
Implementiert eine Einstiegsübung für die Arbeit mit GitHub auf der Basis von Markdown-Dokumenten

## Idee der Übung
Anhand einer Fingerübung sollen Sie die gemeinsame Arbeit in einem Projekt üben. Dazu finden Sie im Repository eine Datei [CSharpBasics.txt](https://github.com/ComputerScienceLecturesTUBAF/SoftwareentwicklungSoSe2020_Aufgabe_00/blob/master/CSharpBasics.txt). Überführen Sie diese in ein neues Markdown-Dokument, das mit den entsprechenden Syntaxelementen die notwendige Strukturierung und Formatierung erfährt. Integrieren Sie danach eine GitHub Action, die aus dem Dokument ein pdf generiert. Als Vorlage dafür können Sie die Implementierung der Skriptgenerierung für die Vorlesungsunterlagen verwenden.

## Aufgaben
1. Erzeugen Sie ein Issue `Rechtschreibpruefung`
2. Erzeugen Sie ein Issue `Dokument in Markdown übertragen`
3. Erzeugen Sie ein Issue `Action ergaenzen` Ordnen Sie für alle Issues entsprechende Verantwortlichkeiten und eine Deadline zu!
4. Eröffnen Sie einen neuen Feature-Branch `PruefungSprache`
5. Der Verantwortliche wirft alle Rechtschreibfehler aus den Dokumenten und sorgt für eine verbesserte Lesebarkeit durch harte Zeilenumbrüche. Bitte lassen Sie den "KAUDERWELSCH" Eintrag im Text bestehen.
6. Bitten Sie Ihren Mitstreiter um ein Review. "Zufällig" findet er den oben genannten Eintrag und macht Sie per Issue Diskussion und Permalink drauf aufmerksam. Sie korrigieren den Fehler und mergen das Ergebnis mit dem master-Branch. Schließen Sie das Issue nach einem finalen Kommentar!
7. Erzeugen Sie einen Feature-Branch `Markdownbereitstellung`
8. Stellen Sie die Dokumente auf eine Markdownsyntax um. Dabei sind Ihrer Kreativität keine Grenzen gesetzt :-) "Simulieren" Sie weitere Aktivitäten und Commits, in dem Sie zum Beispiel Grafiken einfügen.
9. Mergen Sie den Branch mit "master", Schließen Sie die Issues, referenzieren Sie diese in Ihren Commits.
10. Erzeugen Sie einen Feature-Branch `pdf Generation`
11. Integrieren Sie eine GitHub Action, die aus den Dokumenten die zugehörigen pdfs (nutzen Sie dafür das pandoc tool und ein entsprechendes Plugin) erzeugt. Lesen Sie dazu die Dokumentation der GitHub-Actions und nutzen Sie unsere Action für die Script-Generierung als Basis. 
