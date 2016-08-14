FROM fullstackml/rstats-spark:latest
MAINTAINER Dmitry Petrov <dmitry@fullstackml.com>

LABEL com.fullstackml = "true" \
      com.fullstackml.function = "sparklyr" \
      com.fullstackml.version = "0.01"

RUN R -e 'install.packages("devtools")' && \
    R -e 'devtools::install_github("rstudio/sparklyr")'
