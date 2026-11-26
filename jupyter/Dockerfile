FROM quay.io/jupyter/scipy-notebook:2026-11-23

COPY --chown=${NB_UID}:${NB_GID} requirements.txt /tmp/requirements.txt

RUN pip install --no-cache-dir -r /tmp/requirements.txt \
    && rm /tmp/requirements.txt