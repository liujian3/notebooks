FROM jupyterhub/jupyterhub
#USER root
RUN python3 -m pip install --no-cache --upgrade setuptools pip wheel
RUN python3 -m pip install --no-cache jupyterhub-ldapauthenticator dockerspawner jupyterhub-idle-culler
#USER $NB_UID
