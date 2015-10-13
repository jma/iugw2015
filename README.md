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

## From MarcXML to JSON-LD

See Markdown file

