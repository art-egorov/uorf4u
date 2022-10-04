
<img  src="img/uorf4u_logo.png" width="300"/>

## Description

uorf4u is a bioinformatics tool for conserved upstream ORFs annotation.    

**Programming languages:** Python3   
**OS:** MacOS, Linux  
**Python dependencies:** biopython, configs, argparse, pandas, statistics, logomaker, matplotlib, reportlab.  
**R dependencies:** ggmsa, ggplot2, optparse  
**OS-level dependencies:** muscle, maft   
**License:** [WTFPL](http://www.wtfpl.net)  
**Version:** 0.5.0 (October 2022)


### Data analysis pipeline:

<img  src="img/uorf4u_pipeline.png" width="400"/>


## Installation


- The most stable release of uorf4u can be installed directly from pypi:

```
python3 -m pip install uorf4u
```

- The development version is available at github :

```
git clone https://github.com/art-egorov/uorf4u.git
cd uorf4u
python3 -m pip install --upgrade pip
python3 -m pip install wheel
python3 setup.py sdist bdist_wheel
python3 -m pip install -e .
```


## Reference

If you find uorf4u useful, please cite:


Artyom A. Egorov, Gemma C. Atkinson **uorf4u: ...,** *---, [doi]()*


## Contact

Please contact us by e-mail _artem**dot**egorov**AT**med**dot**lu**dot**se_ or use Issues to report any technical problems.  


## Authors

uorf4u is developed by Artyom Egorov at [The Atkinson Lab](https://atkinson-lab.com), Department of Experimental Medical Science, Lund University, Sweden. We are open for suggestions to extend and improve uorf4u functionality. Please don't hesitate to share your ideas or feature requests.
