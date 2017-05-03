FROM aaronwatters1/jp-gene-viz

MAINTAINER Aaron Watters <awatters@simonsfoundation.org>

USER $NB_USER

RUN git clone https://github.com/simonsfoundation/jp_svg_canvas.git
RUN git clone https://github.com/simonsfoundation/1702_DC_lineageNets.git
RUN git clone https://github.com/simonsfoundation/DCquantAtacNetworks.git
RUN git clone https://github.com/simonsfoundation/Tr1_batfKO.git
RUN git clone https://github.com/dayanne-castro/breast_cancer_network_binder.git
RUN git clone https://github.com/simonsfoundation/regulatory_network_examples.git
COPY index.ipynb .