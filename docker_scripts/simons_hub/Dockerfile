FROM aaronwatters1/jp-gene-viz

MAINTAINER Aaron Watters <awatters@simonsfoundation.org>

USER $NB_USER

RUN git clone https://github.com/simonsfoundation/jp_svg_canvas.git
RUN git clone https://github.com/simonsfoundation/1702_DC_lineageNets.git
RUN git clone https://github.com/simonsfoundation/DCquantAtacNetworks.git
RUN git clone https://github.com/simonsfoundation/Tr1_batfKO.git
#RUN git clone https://github.com/dayanne-castro/breast_cancer_network_binder.git
RUN git clone https://github.com/simonsfoundation/regulatory_network_examples.git
RUN  git clone https://github.com/nickdeveaux/jp_gene_viz_atac_dc_networks.git
COPY index.ipynb .
RUN echo "c.NotebookApp.iopub_data_rate_limit=1e22" >> $HOME/.jupyter/jupyter_notebook_config.py
