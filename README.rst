Dockerized notebooks
====================

Why?
----

Because *FY* ^_^ ! 

How to use it? This way!

.. code-block::

   export COMPOSE_CONVERT_WINDOWS_PATHS=1 # wee? if you are not on linux.

   docker-compose up -d


Which notebooks are included?
-----------------------------

Poked around things and turns out that the easiest way to study math is `jupyter/datascience-notebook <https://hub.docker.com/r/jupyter/datascience-notebook/>`_

Works awesome with `docker-machine <https://docs.docker.com/machine/>`_.

But there are many others!

+---+------------------------------+---------------------------+---------------------------+------+
| # | Name                         | Why?                      | Size    | Auth            | Root?|
+---+------------------------------+---------------------------+---------+-----------------+------+
| 1 | jupyter/datascience-notebook | python, math, tools       | 6.648Gb | Token           | Yes  |
+---+------------------------------+---------------------------+---------+-----------------+------+
| 2 | jupyter/pyspark-notebook     | python, spark, clustering | 4.764Gb | Token           | Yes  |
+---+------------------------------+---------------------------+---------+-----------------+------+
| 3 | continuumio/anaconda         | do you like python?       | 2.245Gb | Token           | Yes  |
+---+------------------------------+---------------------------+---------+-----------------+------+
| 4 | gcr.io/tensorflow/tensorflow | tensorflow, python        | 1.029Gb | Token           | Yes  |
+---+------------------------------+---------------------------+---------+-----------------+------+
| 5 | rocker/rstudio               | RStudio, web              | 989.5Gb | rstudio:rstudio | No   |
+---+------------------------------+---------------------------+---------+-----------------+------+
