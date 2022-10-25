## Workflow

The current workflow is 

1. Vocabularies are stored in git as *.csv files
2. The *.csv files are converted to *.xls(x) files locally, but these are not tracked in the repository
3. The *.xls(x) files are converted to .ttl files using the [SKOS-play](https://skos-play.sparna.fr/play/convert) tool
4. .ttl files are added to the repository
5. The .ttl files are validated and loaded into the registry using scripts derived from [https://github.com/GeoscienceAustralia/cgi-vocabs/tree/master/scripts](Geoscience Australia's CGI vocabularies repository)