###Introduction

Before sequencing, artifacts could be maked every step at the experiment, these artifacts were maked by palindromic structure in the genome. The scripts will search artifacts in given regions at different experimental treatments. 

ArtifactsFinderIVS.py can find IVS (inverted repeat sequences) artifacts, ArtifactsFinderPS.py can find PS (palindromic sequences) artifacts.

###Useage

	python3 ArtifactsFinderIVS.py -g genome -b bed

	python3 ArtifactsFinderPS.py -g genome -b bed
	

Note : The genome is the hg19 or hg38 sequences. The bed is in 0-base format. If your region is too long, you can use bedReform.py reform it.
