= pgbouncer (1)
Jeff McCormick
April 13, 2017
== NAME
pgbouncer - pgbouncer container image

== DESCRIPTION
The pgbouncer image provides the open source pgbouncer postgres utility.

The container itself consists of:
    - RHEL7 base image
    - bash script that performs the container startup
    - pgbouncer binary packages

Files added to the container during docker build include: /help.1.

== USAGE
See the crunchy docs.


== LABELS
The starter container includes the following LABEL settings:

That atomic command runs the docker command set in this label:

`Name=`

The registry location and name of the image. For example, Name="crunchydata/pgbouncer".

`Version=`

The Red Hat Enterprise Linux version from which the container was built. For example, Version="7.5"

`Release=`

The specific release number of the container. For example, Release="2.1.0"