# Security Policy

## Reporting a Vulnerability

Security is important for us. 
Security vulnerabilities or suspected security vulnerabilities should be reported to Strimzi maintainers privately, to minimize attacks against current users of Strimzi before they are fixed. 
Reported vulnerabilities will be investigated and patched on the next patch (or minor) release as soon as possible.

**IMPORTANT: Please do not file public issues on GitHub for security vulnerabilities**

To report a vulnerability or a security-related issue, please email the private mailing list [cncf-strimzi-maintainers@lists.cncf.io](mailto:cncf-strimzi-maintainers@lists.cncf.io) with the details of the vulnerability.
Do not report non-security-impacting issues through this channel.
Use GitHub issues instead.

## Supported Versions

Depending on the severity of the CVE or other vulnerability, on any Strimzi component, the project provides the fix either as a patch release of the current minor release or in the next minor release.
For example, if the latest version of the cluster operator is 99.98.0, a vulnerability fix can be part of a 99.98.1 and/or 99.99.0.

Regarding the Apache Kafka security vulnerabilities, Strimzi uses Apache Kafka binaries as provided by the Apache Kafka project.
Any CVE in Apache Kafka and its dependencies need to be first fixed and released in Apache Kafka itself and then used by Strimzi.