# lagom-testbed-high-replication-factor

A Lagom Java Hello work dporject to test the impact of a non-deafualt `replication-factor`

The relevant changes wrt to the seed are in [application.conf](https://github.com/ignasi35/lagom-testbed-high-replication-factor/blob/master/hello-impl/src/main/resources/application.conf#L8-L28):

 * passivation timeout reduced to 10s
 * snapshotting period reduce to 1 change
 * `replication-factor` increased to 3 on all keyspaces.
