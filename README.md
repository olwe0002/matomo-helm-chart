Helm chart to deploy [Matomo](https://matomo.org/) on Kubernetes, based on the [Matomo docker image by Bitnami](https://github.com/bitnami/bitnami-docker-matomo).

Matomo needs a [MariaDB](https://mariadb.org/) database. This chart uses the [Maria DB helm chart by Bitnami](https://github.com/bitnami/charts/tree/master/bitnami/mariadb) to deploy the database.