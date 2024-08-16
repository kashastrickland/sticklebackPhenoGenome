# sticklebackPhenoGenome
Phenotypic and meta data for "Microevolutionary change in wild stickleback: using integrative time-series data to infer responses to selection"

"phenotypedata.csv": All phenotypic data generated in this study and needed to replicate analyses of phenotypic change through time. Note that not all fish have all data associated with them, and therefore the total sample sizes for each phenotype are slightly different. These missing data were caused by, for instance, gill rakers breaking upon dissection, staining not working and guts having been dissected previously. This dataset includes the following variables:
  fish_id; unique identifier for the fish
  year; the calendar year in which the fish was caught
  station; unique identifier for the site of capture
  length; total length of the fish in mm
  sex; sex of the fish
  gut_length; total length of the gut in mm
  SP1; length of the first dorsal spine in mm
  SP2; length of the second dorsal spine in mm
  PS; length of the pelvic spine in mm
  plates; number of armour plates
  grn; number of long gill rakers
  grg; width of the gap between the second and third gill rakers in mm
  grl2; length of the second gill raker in mm
  grl3; length of the third gill raker in mm

"genomicsMetaData.csv": meta data for fish for which we sequenced the whole genomes. Raw reads can be found at ENA accession number ###. This file includes:
  "fish_id"; unique identifier for the fish which is needed to link genomic data to phenotypic data
  "labID"; name for sample used in sequencing
  "Year"; year in which the fish was caught
  "Station"; unique identifier for the site of capture
