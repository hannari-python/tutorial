FROM python:3.7-slim
RUN pip install --no-cache-dir notebook==5.*
RUN pip install pydeck==0.4.1
RUN jupyter nbextension install --sys-prefix --symlink --overwrite --py pydeck
RUN jupyter nbextension enable --sys-prefix --py pydeck

RUN pip install jupyter && \
  pip install jupyterlab && \
  pip install requests && \
  pip install pandas && \
  pip install jupyter_server_proxy && \
  pip install jupyter-dash && \
  pip install dash && \
  pip install requests && \
  pip install flask && \
  pip install retrying && \
  pip install ansi2html && \
  pip install geopandas

ENV HOME=/tmp
WORKDIR ${HOME}
COPY ./ .

ARG NB_USER=jovyan
ARG NB_UID=1000
ENV USER ${NB_USER}
ENV NB_UID ${NB_UID}
ENV HOME /home/${NB_USER}

RUN adduser --disabled-password \
    --gecos "Default user" \
    --uid ${NB_UID} \
    ${NB_USER}

USER root
RUN chown -R ${NB_UID} ${HOME}
USER ${NB_USER}
