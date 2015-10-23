# FOS Proposals
## Express your love for Open Source!


This repository serves as an archive of *F*ree and *O*pen *S*ource proposals.
Since [GSoC](https://developers.google.com/open-source/soc/?csw=1) is the only such 
program where I participated myself, the dump is organized as such.
If you have proposals from GSoC/KDE-Soc/any, feel free to send a PR.


## Adding your proposal?

Opening a pull request with links to a Google Doc should suffice.
In case you want to help more, read on.


All proposals need to be in Github flavored markdown format.
If you have a Google Doc, conversion should be pretty straightforward
using [pandoc](http://johnmacfarlane.net/pandoc/README.html)



```
git clone git@github.com:username/fos-proposals.git
git checkout -b username-year
cd GSoC-year
mkdir Organisation-YourName-Title
cd Organisation-yourname-title && mkdir media
```

All images should go to `media`, and be relatively linked in your markdown.
To port a `doc/docx` proposal:

```
cd Organisation-YourName-Title
pandoc -r  docx infile.docx -w markdown_github -o Organisation-YourName-Title.md --extract-media=media
rm infile.docx
git add .
git commit -am “GSoC-Year: Proposal Title”
git push origin username-year
```

Alternatively, you can leverage on [gdocs2md](https://github.com/mangini/gdocs2md)
which in my experience so far gives superior output to `pandoc`.
Suggestions are always welcome.


## Organisation

- GSoC-2013
	- Accepted
		- [Genome-Informatics-SaketChoudhary-eQTL-Pipeline](GSoC-2013/Accepted/Genome-Informatics-SaketChoudhary-eQTL-Pipeline/Genome-Informatics-SaketChoudhary-eQTL-Pipeline.md)
- GSoC-2012
	- Accepted
		- [Connexions-SaketChoudhary-OERPub-API](GSoC-2012/Accepted/Connexions-SaketChoudhary-OERPub-API/Connexions-SaketChoudhary-OERPub-API.md)
- GSoC-2015
	- Accepted
		- [HimanshuMishra-PSF-Implementing-Add-On-System-For-NetworkX](GSoC-2015/Accepted/HimanshuMishra-PSF-Implementing-Add-On-System-For-NetworkX/GSoC-2015-Application-Himanshu-Mishra-Add-on-System-for-NetworkX.md)
		- [Sumith1896-PSF-Implementing-Polynomial-module-in-CSymPy](GSoC-2015/Accepted/Sumith1896-PSF-Implementing-Polynomial-module-in-CSymPy/GSoC-2015-Application-Sumith-Implementing-polynomial-module-in-CSymPy.md)
		- [Pratyaksh-PSF-Sampling-Algorithms-in-pgmpy](GSoC-2015/Accepted/Pratyaksh-PSF-Sampling-Algorithms-in-pgmpy/Pratyaksh-PSF-Sampling-Algorithms-in-pgmpy.md)
		- [SaketC-statsmodels-MixedModels](GSoC-2015/Accepted/SaketC-statsmodels-MixedModels/SaketC-statsmodels-MixedModels.md)
		- [The-Eclipse-Foundation-AnujPahuja-Cloud-Removal](GSoC-2015/Accepted/The-Eclipse-Foundation-AnujPahuja-Cloud-Removal/GSoC - GeoTrellis.md)
	- Proposed
		- [Mozilla-ManishG-FormSupportServo](GSoC-2015/Proposed/Mozilla-ManishG-FormSupportServo/Mozilla-ManishG-FormSupportServo.md)
- GSoC-2014
	- Accepted
		- [Mozilla-ManishG-Servo](GSoC-2014/Accepted/Mozilla-ManishG-Servo/Mozilla-ManishG-Servo.md)
		- [KDE-AnujPahuja-KDE-Games-to-KF5](GSoC-2014/Accepted/KDE-AnujPahuja-KDE-Games-to-KF5/GSoC - KDE.md)
		- [BioJS-SaketChoudhary-HumanGV](GSoC-2014/Accepted/BioJS-SaketChoudhary-HumanGV/BioJS-SaketChoudhary-HumanGV.md)




`Proposed` is euphemism.
*Love can often be one-directional.*



