
### Genotyping variants using svviz

https://github.com/nspies/svviz2

### environment
```
module load system/Python-3.6.3
module load bioinfo/bwa-0.7.17
module load bioinfo/trf-v4.09
module load system/R-3.6.2
python3 -m venv svvizenv
source svvizenv/bin/activate
pip install Cython
pip install numpy
pip install pysam
pip install rpy2
pip install -U git+git://github.com/nspies/svviz2.git
