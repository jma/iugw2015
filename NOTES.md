# Invenio User Group Workshop 2015 (Notes)

## Presentation day I

### Welcome & Overview of the workshop (Jean-Yves LE MEUR)

- en retard pour cette présentation

 
### Invenio software overview (Tibor SIMKO)

- presentation de Invenio 3.0
- use of Docker + Puppet <https://puppetlabs.com/>


### Invenio @ CDS (Ludmila MARIAN)

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

### Invenio @ JOIN2 (Alexander WAGNER)

- multiple server and instances (5?)
- 1.0 -> 1.1 (difficult)
- 1.1 -> 1.1.x (easy)
- reimplement AOI-DC
- <http://join2.de>
- github: 29 members 18 librarians 14 teams (one per instance plus others)

### Invenio @ INSPIRE (Samuele KAPLUN

- a lot of ML tools
	- duplicates records
	- advanced record editor (Schema based!) (use of json schema editor)
	- batch record editor
	- extract infos from PDFs (grobid: <https://github.com/kermitt2/grobid>)
- user can propose update, corrections, etc.

	
### Invenio @ TIND (Alexander NIETZOLD)

- 9 instances (mostly 1.2)
- first 2.0 instance
- also Library system (loan rules) Caltech <https://caltech.tind.io>
- GOKb (Global Open Knowledgebase)
- United Nations Dag Hammarskjold Library New York invenio 2.0 in 2016 (10M files, 0.8 cataloged files, 250K deposits/Year)


### Invenio @ UNIDEP



### Invenio @ JINR (Genis MUSULMANBEKOV)

- authorities
- projects
- upgrade to v2.x.x


### Invenio@EPFL (Emmanuel BRÉTONet al.)

- sign Berlin Declaration (2012), RERO ?

### Invenio 2: architecture (Jiri KUNCAR)

- Docker presentation <https://github.com/jirikuncar/iugw2015/tree/tutorial>
- CERN use Docker in production only for a demo instance using docker-compose
- CERN use OpenStack <https://www.openstack.org/>

### Hands on: Invenio 2 technology (Jiri KUNCAR)

- example for celery tasks



### Configuring IIIF for images (Harris TZOVANAKIS)

- <https://github.com/drjova/iugw2015/tree/iiif/demo>
- image rotation, etc. with UUID (universally unique identifier


### Hands-on: play with Invenio 2 technology (Tibor SIMKO)

- docker for Invenio 1.xx with superviser
- <https://github.com/cernopendata/opendata.cern.ch>

## Presentation day II


### Zenodo (Lars Holm NIELSEN)


### HepData (Eamonn James MAGUIRE)

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
