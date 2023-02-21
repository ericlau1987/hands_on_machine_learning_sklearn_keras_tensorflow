# FROM jupyter/scipy-notebook
FROM conda/miniconda3

USER root

RUN conda install --yes --name root psycopg2 \
                scikit-learn

RUN pip install -U scikit-learn==1.0.2

USER jovyan