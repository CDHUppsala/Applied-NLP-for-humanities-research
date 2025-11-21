# Applied NLP for humanities research
This GitHub repository holds text processing scripts for the Huminfra handbook chapter [Applied NLP for humanities research](https://dspace.ut.ee/items/1cb2596b-ab14-4cdb-954c-4136ea52f9e3).

The repository contains scripts to lemmatize Swedish texts using pefselab as well as scripts for analyzing literary style.

## Lemmatisation with efselab
We here showcase how [pefselab](https://github.com/skogsgren/pefselab) is used for lemmatising our example data.

Follow [pefselab's'](https://github.com/skogsgren/pefselab) instructions. Also, make sure you have a new enough version of Python.

To run the code here, you also need nltk. (With e.g., conda: `conda install anaconda::nltk`).

You first need to run `create_pefselab_pipeline.py` once, to create the NLP pipeline. Then you can run the script for lemmatisation `lemmatise_motions.py`.

The script expects one folder with ".txt"-files (the first argument to the script) as well as the name of the folder where the lemmatised files are to be positioned. (See `run_lemmatise_motions.sh` for an exampel of how to run the script.)

## Reference

Gijs Aangenendt, Maria Skeppstedt & Karl Berglund. 2025. Applied NLP for humanities research. In Gerlof Bouma, Dana Dannélls, Dimitrios Kokkinakis & Elena Volodina (eds.), _Huminfra handbook: Empowering digital and experimental humanities_ (NEALT Proceedings Series 59), 77–111. University of Tartu Library. DOI: [10.58009/aere-perennius0173](https://doi.org/10.58009/aere-perennius0173)
