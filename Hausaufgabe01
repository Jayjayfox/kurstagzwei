Entzippen: unzip -a google-websearch-copyright-removals.zip

Kopfzeile anschauen: csvcut -n domains.csv
  1: Request ID
  2: Domain
  3: URLs removed
  4: URLs that were not in Google's search index
  5: URLs for which we took no action
  6: URLs pending review
  7: From Abuser

Zählen: grep "\.ch" domains.csv | wc -l
  711533

.csv nur mit .ch-Domains erstellen: grep "\.ch" domains.csv > ch_domains.csv

Linien zählen im ch_domains.csv: wc -l ch_domains.csvcut

Häufigste .ch-Domain: csvstat ch_domains.ch
Resultat: uploadable.ch (79874x), kickass-torrents.ch (59193x), torrentz.ch (45167x), torrentdownload.ch (32359x), extratorrent.ch (30620x)
