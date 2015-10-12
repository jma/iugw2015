# Invenio User Group Workshop 2015

RERO presentation and workshop notes for <https://indico.cern.ch/event/441770/>

## The New RERO Statistics Services

### Installation

As the `helvetica` fonts are used you need to install all package matching `URW "` using `Tex Live Utility`.

Create pdf by running:

	pdflatex invenio_user_2015_maj

### Abstract

More and more RERO professionals are asking for statistics on the use of the
RERO DOC server. They want to know, for a certain period, what are the most
consulted records, which files are more uploaded, which collections are more
popular, etc. They also want to customize results by selecting multiple
filters, such as: what are the document types most seen for the University of
Fribourg from January to March 2014 in Economics.

Using recent tools such as Elasticsearch, AngularJS, Highcharts, etc.,
we decided to develop a new specific interface using the server
logs and the Invenio API. One of the most challenging aspect was how to filter
internet bots (crawlers, robots), especially those appearing as humans.

## Presentation day I

# Welcome & Overview of the workshop (Jean-Yves LE MEUR)

- en retard pour cette présentation

 
# Invenio software overview (Tibor SIMKO)

- presentation de Invenio 3.0
- use of Docker + Puppet <https://puppetlabs.com/>


# Invenio @ CDS (Ludmila MARIAN)

- run legacy + CDS-overlay
- deploy with fabrik??
- 2 load balancers
- 1 database + redis, I DB slave
- 5 worker nodes
- 1 SOLAR
- 1 builder
- use puppet
- 24 nodes + nfs caching
- Neo4J?
- stats: Kibana + Elastic => lumberjack module

# Invenio @ JOIN2 (Alexander WAGNER)

- multiple server and instances (5?)
- 1.0 -> 1.1 (difficult)
- 1.1 -> 1.1.x (easy)

09:45 - 10:05513-1-024, CERN
Samuele KAPLUN
Invenio @ INSPIRE

10:05 - 10:25513-1-024, CERN
Coffee break

10:25 - 10:40513-1-024, CERN
Alexander NIETZOLD
Invenio @ TIND

10:40 - 11:00513-1-024, CERN
Invenio @ UNIDEP

11:00 - 11:20513-1-024, CERN
Genis MUSULMANBEKOV
Invenio @ JINR

11:20 - 11:40513-1-024, CERN
Emmanuel BRÉTONet al.
Invenio@EPFL

11:40 - 12:00513-1-024, CERN
Lunch break

12:00 - 13:30513-1-024, CERN
Jiri KUNCAR
Invenio 2: architecture

13:30 - 13:45513-1-024, CERN
Jiri KUNCAR
Hands on: Invenio 2 technology

13:45 - 15:30513-1-024, CERN
Coffee break

15:30 - 15:50513-1-024, CERN
Harris TZOVANAKIS
Configuring IIIF for images

15:50 - 16:20513-1-024, CERN
Tibor SIMKO
Hands-on: play with Invenio 2 technology

16:20 - 18:00513-1-024, CERN
Tue 13/10
09:0010:0011:0012:0013:0014:0015:0016:0017:0018:0019:0020:0021:0022:00
Lars Holm NIELSEN
Zenodo

09:00 - 09:20IT Amphitheatre, CERN
Eamonn James MAGUIRE
HepData

09:20 - 09:40IT Amphitheatre, CERN
Mr. Nicolas HARRAUDEAU
B2Share

09:40 - 10:00IT Amphitheatre, CERN
Patricia Sigrid HERTERICH
CERN (Open) Data Services

10:00 - 10:20IT Amphitheatre, CERN
Coffee break

10:20 - 10:40IT Amphitheatre, CERN
Mr. Audun BJORKOYet al.
Invenio 2 instances with image viewer, maps & timeline feature, and IIIF

10:40 - 11:05IT Amphitheatre, CERN
Esteban GABANCHO
cdslabs

11:05 - 11:30IT Amphitheatre, CERN
Javier MARTIN MONTULL
inspirelabs

11:30 - 11:55IT Amphitheatre, CERN
Lunch break

12:00 - 13:00513-1-024, CERN
AD Site Visit

12:00 - 13:0093-R-031, CERN
AD Site Visit

13:00 - 14:0093-R-031, CERN
Lunch break

13:00 - 14:00CERN
Alexander WAGNER
DoJSON Module

14:00 - 14:30Salle Bohr, CERN
Sebastian WITOWSKI
Hands-on: prepare data model on your Invenio 2 instance

14:30 - 15:40Salle Bohr, CERN
Coffee break

15:40 - 16:00513-1-024, CERN
Esteban GABANCHO
Map past data to the new model

16:00 - 16:30Salle Bohr, CERN
Ludmila MARIAN
Albums in Invenio 2

16:30 - 16:50Salle Bohr, CERN
Esteban GABANCHO
Hands-on: load your data into your Invenio 2 instance

16:50 - 18:00Salle Bohr, CERN
Social Outing

19:00 - 22:00La Grange aux Vins, Saint Genis Pouilly
Wed 14/10
09:0010:0011:0012:0013:0014:0015:0016:0017:0018:00
Kenneth HOLEet al.
Adds-on to legacy for ILS, by Tind.io: loan rules, bibedit, Z39.50

09:00 - 09:20Salle Anderson, CERN
Martin VESPER
Book circulation

09:20 - 09:35Salle Anderson, CERN
Dimitri SEMITSOGLOU TSIAPOS
New checker module: BibCheck & MultiEdit in one tool

09:35 - 10:00Salle Anderson, CERN
David Albert ZERULLA
Obelix, the read-recommendation system for Invenio

10:00 - 10:20Salle Anderson, CERN
Sebastian WITOWSKI
Authoring and Invenio: investigations

10:20 - 10:25Salle Anderson, CERN
Coffee break

10:25 - 10:45Salle Anderson, CERN
Jan Age LAVIK
Holding pen and workflow @ Inspire

10:45 - 11:05Salle Anderson, CERN
Jacopo NOTARSTEFANO
Machine Learning Reference extraction using Grobid

11:05 - 11:25Salle Anderson, CERN
Nikos KASIOUMIS
People Authority @ CDS

11:25 - 11:45Salle Anderson, CERN
Gilles LOUPPE
Disambiguation of Authors with Beard

11:45 - 12:00Salle Anderson, CERN
Lunch Break (& group photo)

12:00 - 13:30513-1-024, CERN
Javier MARTIN MONTULL
Customize Deposit module

13:30 - 14:00IT Amphitheatre, CERN
Jan Age LAVIKet al.
Hands-on: customize your invenio instance

14:00 - 15:10IT Amphitheatre, CERN
Coffee break

15:40 - 16:00513-1-024, CERN
Create a new module in Invenio 2
Lars Holm Nielsen16:00 - 18:00513-1-024, CERN

Thu 15/10
09:0010:0011:0012:00
Tim SMITH
Copyright & Content

09:00 - 09:20513-1-024, CERN
Johnny MARIÉTHOZ
The new RERO Statistics services

09:20 - 09:45513-1-024, CERN
Nikos KASIOUMIS
Getting ready for ten years of statistics

09:45 - 10:10513-1-024, CERN
Coffee break

10:10 - 10:30513-1-024, CERN
David MAZUR
Technology Transfer at CERN

10:30 - 10:50513-1-024, CERN
Tibor SIMKO
Best practices for contributing to Invenio

10:50 - 11:10513-1-024, CERN
Jean-Yves LE MEUR
Workshop Summary

11:10 - 11:25513-1-024, CERN
Frederic HEMMER
Perspectives, from CERN IT Department Head

11:25 - 11:40513-1-024, CERN
Data Center Visit

11:45 - 12:45 Data Centre Visit Point, CERN