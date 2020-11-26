# mzLabelEditor
A tool to add labels on mass spectrum peaks and store together metadata and annotations in a formatted text file. Labels are manually set or can be got from a model spectrum (theoretical or reference).

## Requirement

Java 8

## Run

type in console/terminal:
java -jar mzLabelEditor-3.0-comparator.jar

##  Theoretical spectrum
External ressources to produce theoretical spectrum from candidate structure as formatted text file readable by mzLabelEditor

* oligosaccharide: see [oligator](https://github.com/vlollier/oligator) project
* peptide: pept2msms command line tool `java -jar pept2msms-1.0-SNAPSHOT.jar -h`

