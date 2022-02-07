FROM jupyter/scipy-notebook

USER root

RUN conda install --yes --name root psycopg2 \
                scikit-learn

RUN pip install -U scikit-learn

USER jovyan