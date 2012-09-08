Deutsche Bundesgesetze und -verordnungen
========================================

Dieses Git Repository enthält alle Deutschen Bundesgesetze und -verordnungen
im [Markdown-Format](http://daringfireball.net/projects/markdown/). Als Quelle
dienen die XML-Versionen der Gesetze von
[www.gesetze-im-internet.de](http://www.gesetze-im-internet.de/).


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

Offizielle Gesetzesentwürfe, wenn öffentlich verfügbar, werden vom Fork der
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
Bundesgesetzblatt und im Amtlichen Teil des Bundesanzeigers. Das funktioniert
nicht immer problemlos und erfordert menschliche Unterstützung.
Werkzeuge, die die Aktualisierung vereinfachen finden sich im
[gesetze-tools repository](https://github.com/bundestag/gesetze-tools).
Mithilfe ist erwünscht.

Um die Fähigkeiten von Git optimal zu nutzen, wird es nötig sein Commits, die
Gesetzesänderungen einbringen, von Commits, die z.B. Korrekturen an der Syntax
vornehmen oder die README verändern zu unterscheiden. Hier wird um Mithilfe
bei der [Ausarbeitung eines Git-Workflows](https://github.com/bundestag/gesetze/wiki/Git-Workflow)
für dieses Repostiory gebeten.


Rechtliches
-----------

Gesetze sind amtliche Werke und unterliegen nicht dem Urheberrecht.


Kontakt
-------

Twitter: [@bundesgit](https://twitter.com/bundesgit)


--------
(english version)

German Federal Laws and Regulations
===================================

This Git repository contains all German federal laws and regulations in
[Markdown format](http://daringfireball.net/projects/markdown/). The source
is the XML version of the laws from
[www.gesetze-im-internet.de](http://www.gesetze-im-internet.de/).


Why Git?
----------

All German citizens can easily find an up-to-date version of their laws online.
However, the legislation process, the historic evolution and the updates to laws
are not easily and freely trackable. The reason is that laws are only published
in their most recent version and changes to laws are not available in a
machine-readable format.
This should change: the current state of laws will be stored in this repository
under Git version control. This allows the power of Git to be applied to the
legislation process. Integrating the whole history of German law changes in Git
is the ambitious goal.


Why Markdown?
-------------

Laws are prose, they do not contain machine-readable semantics.
A complex markup language like XML reduces the human-readability,
makes detection of differences harder and contains lots of
unnecessary syntax.

Markdown is an intuitive formatting of text, that is readable and
writable by humans without the need of additional tools. That fits
the nature of laws that only need minimal formatting. Furthermore,
Markdown is machine-formattable and can be converted to other formats
like HTML.


Pull Requests
-------------

You are encouraged to open pull request. Of course only valid legislation
voted on by the Bundestag will be merged.

However, law change proposals as pull requests coming from parties or
NGOs can be useful to understand context, discuss changes directly where
they will happen and keep changes accountable.

Official change proposals from our government will be opened as pull
requests from the fork of the [Bundesregierung](https://github.com/bundesregierung/)
as they become publicy available.


Mistakes and call for help
--------------------------

There is no guarantee on correctness. Please only trust official sources.

The source XML is not without mistakes and neither is the conversion to
Markdown. That's because the source XML uses markup for style and not only
for semantics. This makes conversion harder and comes down to faulty
Markdown. However, faulty Markdown is still very readable and will only
cause problems when processed further.

Commits will be based on published changes (Bundesgesetzblatt and Bundesanzeiger).
That doesn't work without problems and requires human interaction.
Tools that make updates easier can be found in the
[gesetze-tools repository](https://github.com/bundestag/gesetze-tools).
Help needed.

In order to make the most out of Git we need to distinguish between law change
commits and commits that fix e.g. syntax mistakes.
Please help shape a [Git Workflow](https://github.com/bundestag/gesetze/wiki/Git-Workflow)
for this repository.


Legal Stuff
-----------

All laws are offical works and are not under copyright law.


Contact
-------

Twitter: [@bundesgit](https://twitter.com/bundesgit)

