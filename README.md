# docker-pandoc-for-snakemake

[pandoc/core](https://hub.docker.com/r/pandoc/core) does not have bash, which makes it unsuitable for snakemake.
This image fixes that by installing bash and unsetting the default pandoc ENTRYPOINT.