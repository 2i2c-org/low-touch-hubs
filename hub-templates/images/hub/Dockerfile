# Should match the hub image used by version of chart in hub/requirements.yaml
# If that changes, this should be changed too!
FROM jupyterhub/k8s-hub:0.11.1-n298.hd9d7403b

ENV CONFIGURATOR_VERSION d597dc223247fa6c0878379df46aa078b2fecd19

RUN pip install --no-cache git+https://github.com/yuvipanda/jupyterhub-configurator@${CONFIGURATOR_VERSION}
