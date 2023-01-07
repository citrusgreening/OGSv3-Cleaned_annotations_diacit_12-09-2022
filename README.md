# OGSv3-Cleaned_annotations_diacit_12-09-2022
- Parse out Apollo files to find curated genes and genome corrections
- Create the final OGSv3 GFF and fasta files

Removing Apollo models without gene names
Checklist:
	* description in mRNA 
	* Name in mRNA with Dcitr ID to replace
	* No special characters in description
	* Change iso/isoform to RA/RB/RC format in mRNA name (gene name should NOT include isoform information)
	* description = Move extra text in name over here. Change all special symbols like % and ' to percent and prime

![image](https://user-images.githubusercontent.com/1084749/209436874-688f5895-65d8-48bc-8643-0438c2c6b251.png)

<br>

*Citation*
<br>
Diaci v3.0: Chromosome-level assembly, de novo transcriptome and manual annotation of Diaphorina citri, insect vector of Huanglongbing
Teresa D. Shippy, Prashant S. Hosmani, Mirella Flores-Gonzalez, Marina Mann, Sherry Miller, Matthew T. Weirauch, Chad Vosburg, Crissy Massimino, Will Tank, Lucas de Oliveira, Chang Chen, Stephanie Hoyt, Rebekah Adams, Samuel Adkins, Samuel T. Bailey, Xiaoting Chen, Nina Davis, Yesmarie DeLaFlor, Michelle Espino, Kylie Gervais, Rebecca Grace, Douglas Harper, Denisse L. Hasan, Maria Hoang, Rachel Holcomb, Margaryta R. Jernigan, Melissa Kemp, Bailey Kennedy, Kyle Kercher, Stefan Klaessan, Angela Kruse, Sophia Licata, Andrea Lu, Ron Masse, Anuja Mathew, Sarah Michels, Elizabeth Michels, Alan Neiman, Seantel Norman, Jordan Norus, Yasmin Ortiz, Naftali Panitz, Thomson Paris, Kitty M. R. Perentesis, Michael Perry, Max Reynolds, Madison M. Sena, Blessy Tamayo, Amanda Thate, Sara Vandervoort, Jessica Ventura, Nicholas Weis, Tanner Wise, Robert G. Shatters Jr., Michelle Heck, Joshua B. Benoit, Wayne B. Hunter, Lukas A. Mueller, Susan J. Brown, Tom D’Elia, Surya Saha
bioRxiv 869685; doi: https://doi.org/10.1101/869685
