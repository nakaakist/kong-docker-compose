FROM kong:2.0
USER root
RUN luarocks install kong-oidc && luarocks install kong-spec-expose
ENV KONG_PLUGINS=bundled,oidc,kong-spec-expose
USER kong