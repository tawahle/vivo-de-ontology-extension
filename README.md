vivo-de ist eine Erweiterung der Ontologie [vivo-isf-public](https://github.com/openrif/vivo-isf-ontology) um Klassen und Eigenschaften, die für die Beschreibung der deutschen Universitätslandschaft notwendig sind.

# Anmerkungen zur Übersetzung:

Die Erweiterung ist notwendig, da diverse Institutionen, Forschungseinrichtungen, Förderlinien und Rollen sowie deren Beziehungen untereinander im amerikanischen Uni-System nicht vorkommen. 

* Insofern gibt es für diese auch keine adäquaten englischen Begriffe. Beispiel: Juniorprofessor
* In manchen Fällen gibt es "false friends", also scheinbare Entsprechungen, die aber nicht das gleiche meinen: 
 * _faculty_ ist im Verständnis von VIVO der Lehrkörper, also die Gesamtheit der Lehrenden. Eine Fakultät an einer deutschen Universität ist eine Organisationseinheit zur thematischen Gliederung von Lehrstühlen.
 * _professor_ ist ein Lehrer, ein deutscher Professor hingegen ist (im allgemeinen) ein Inhaber eines Lehrstuhls.

Diskussionen zu Begriffen in der Ontologie werden im [wiki](https://github.com/VIVO-DE/vivo-de-ontology-extension/wiki) und deren Einflüsse auf die Übersetzungsdateien [im einem Glossar](https://github.com/VIVO-DE/VIVO-languages/wiki/Glossar) dokumentiert.

## Für die Erweiterungen gelten folgende Ansetzungsregeln:

* Der Klassenname ist deutsch angegeben, wenn es keine englische Entsprechung gibt. 
* Der Klassenname ist englisch, wenn es eine Entsprechung gibt, die Klasse aber in VIVO-ISF fehlt: z.B. Archiv/Archive, Rechenzentrum/Computing Center
* Labels werden konsequent für beide Sprachen angegeben:
 * Das Label bleibt deutsch und wird mit dem Kürzel (de) versehen, wenn es keine englische Entsprechung gibt. Beispiel: Junior Professor
 * Das Label wird übersetzt, wenn eine dokumentierte Übersetzung vorhanden ist. Beispiel: Sonderforschungsbereich und Collaborative Research Center. 
 * Ist der Begriff auf den ersten Blick sehr allgemein, meint aber eine spezifische Institution, wird er mit einem klärenden Kürzel versehen. Beispiel: Forschergruppe / Research Unit ist ein DFG-Förderprogramm. In manchen Fällen sind diese als eigene Klassen eingeführt, z.B. Graduiertenschulen und DFG-Graduiertenschulen.

# Vorgehen und Stand der Entwicklung

* Die neu eingeführten Klassen sind durch Vererbung bereits vorhandener Klassen in die Ontologie eingefügt.
* Die Klassen wurden im VIVO-Editor angelegt, um sofort die Sichtbarkeit und Verwendbarkeit in VIVO überprüfen zu können.

# Installation:

* Site Admin -> Add/Remove RDF data 
 * "Or upload a file from your computer": Datei auswählen
 * "add mixed RDF (instances and/or ontology)" anwählen
 * Submit

# Weiteres:

* Erläuterungen zu den Klassen werden im Wiki dokumentiert: https://github.com/VIVO-DE/vivo-de-ontology-extension/wiki
* Eine Übersetzung der VIVO-Oberfläche befindet sich hier: https://github.com/VIVO-DE/Vitro-languages und https://github.com/VIVO-DE/VIVO-languages
* Beispieldaten (in Vorbereitung)

# Autoren: 

* Kilian Schmidtner (Referat Forschung und Wissenschaftlicher Nachwuchs, Europa-Universität Viadrina Frankfurt (Oder))
* Stefan Wolff (Technische Universität Dresden, Sächsische Landes- und Universitätsbibliothek)

# Siehe auch

* Elena Liventsova: [Mapping und Erweiterung der Ontologie des Forschungsinformationssystems VIVO.](https://serwiss.bib.hs-hannover.de/frontdoor/index/index/docId/803)


