# Security Policy

## Supported Versions

The Strimzi project provides security vulnerability fixes on its components as part of a new patch version of the current minor release and/or on the next minor release, from the `main` branch. The choice about having a new patch version, making the fix only on the next minor release or both depends on the severity of the vulnerability.
For example, if the latest version of the cluster operator is 0.28.0, a vulnerability fix can be part of a 0.28.1 and/or 0.29.0.
The same applies to the other Strimzi components like the Kafka bridge, Kafka OAuth and so on.
Regarding the Apache Kafka security vulnerabilities, their fix follow the release process in the upstream Apache Kafka community.
A list of fixed CVEs is provided [here](https://kafka.apache.org/cve-list).

## Reporting a Vulnerability

Security is important for us. 
Security vulnerabilities or suspected security vulnerabilities should be reported to Strimzi maintainers privately, to minimize attacks against current users of Strimzi before they are fixed. 
Reported vulnerabilities will be investigated and patched on the next patch (or minor) release as soon as possible.

**IMPORTANT: Please do not file public issues on GitHub for security vulnerabilities**

To report a vulnerability or a security-related issue, please email the private mailing list [cncf-strimzi-maintainers@lists.cncf.io](mailto:cncf-strimzi-maintainers@lists.cncf.io) with the details of the vulnerability.
Do not report non-security-impacting issues through this channel.
Use GitHub issues instead.