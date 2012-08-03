Deutsche Bundesgesetze- und verordnungen
========================================

Dieses Git Repository enthält alle Deutschen Bundesgesetze und -verordnungen
im [Markdown-Format](http://daringfireball.net/projects/markdown/). Als Quelle
dienen die XML-Versionen der Gesetze von [www.gesetze-im-
internet.de](http://www.gesetze-im-internet.de/).


Warum Git?
----------

Jeder Bürger kann den aktuellen Stand von Gesetzen sehr einfach online finden.
Allerdings ist die Entstehung, die historische Entwicklung und die
Aktualisierung von Gesetzen nicht einfach und frei nachvollziehbar. Das liegt
daran, dass Gesetze nur in ihrer aktuellsten Version präsentiert werden und
Änderungen an diesen Gesetzen nicht maschinenlesbar vorliegen. Dies soll hier
geändert werden: die aktuellste Version eines Gesetzes wird hier mit Git
versioniert gespeichert. Das erlaubt es, die Mächtigkeit von Git auf Gesetze
und auf den Gesetzgebungsprozess anzuwenden. Das Einpflegen der kompletten
deutschen Gesetzesvergangenheit in Git ist das ferne Ziel.


Warum Markdown?
---------------

Gesetze sind Prosa, sie enthalten keine maschinenlesbare Semantik. Eine
Auszeichnungssprache wie XML verringert die Menschenlesbarkeit, erschwert die
maschinelle Erkennung von Unterschieden und beinhaltet viel überflüssige
Syntax.

Markdown ist eine intuitive Formatierung von Text, die ohne zusätzliche
Programme für Menschen les- und schreibbar ist. Das passt zu Gesetzestexten,
die nur minimale Formatierung benötigen. Weiterhin lässt sich Markdown in
andere Formate wie HTML konvertieren und ist damit maschinen-formatierbar.


Pull Requests
-------------

Pull Requests können gerne geöffnet werden. Natürlich werden nur solche
gemergt, die tatsächlich vom Bundestag verabschiedet wurden und Gesetz
geworden sind.

Dennoch sind Änderungsvorschläge an Gesetzen von Parteien oder aus der
Zivilgesellschaft als Pull Request nützlich. Die Änderungen lassen sich
einfacher im Kontext verstehen, können direkt am Gesetz diskutiert und
nachvollziehbar verändert werden.

Referentenentwürfe, wenn öffentlich verfügbar, werden vom Fork der
[Bundesregierung](https://github.com/bundesregierung/) als Pull Request an
dieses Repository gestellt.


Fehler und Bitte um Mithilfe
----------------------------

Es wird kein Anspruch auf Korrektheit erhoben. Bitte verlassen Sie sich nur
auf offizielle Quellen.

Die XML-Quelle ist nicht fehlerfrei und die Konvertierung von XML nach
Markdown ist es auch nicht. Das liegt daran, dass die Gesetze im XML-Format
das Markup auch für stilistische Auszeichnungen statt nur für semantische
Auszeichnungen nutzen. Dies erschwert eine Konvertierung und führt zu
fehlerhaftem Markdown. Da fehlerhaftes Markdown immer noch gut lesbar ist,
führt dies erst bei einer Weiterverarbeitung zu Problemen.

Commits richten sich nach Möglichkeit nach den Veröffentlichungen im
Bundesgesetzblatt. Das funktioniert nicht immer problemlos und erfordert
menschliche Unterstützung. Werkzeuge, die das committen des aktuellen Standes
einfacher machen, müssen gebaut, verbessert und genutzt werden. Mithilfe ist
erwünscht.

Um die Fähigkeiten von Git optimal zu nutzen, wird es nötig sein Commits, die
Gesetzesänderungen einbringen, von Commits, die z.B. Korrekturen an der Syntax
vornehmen oder die README verändern zu unterscheiden. Hier wird um Mithilfe
bei der Ausarbeitung eines Git-Workflows für dieses Repostiory gebeten.


Rechtliches
-----------

Gesetze sind amtliche Werke und unterliegen nicht dem Urheberrecht.


Kontakt
-------

Twitter: [@bundesgit](https://twitter.com/bundesgit)
