FROM jupyter/scipy-notebook

MAINTAINER Aaron Watters <awatters@simonsfoundation.org>

USER $NB_USER

# see https://github.com/aadm/avo_explorer/blob/master/Dockerfile

COPY requirements.txt .
RUN pip2 install -r requirements.txt
RUN git clone https://github.com/simonsfoundation/jp_gene_viz.git
