# XA-and-XD-HealthCheck
Citrix XenApp and XenDesktop HealthCheck from Sacha Thomet - https://blog.sachathomet.ch/tag/healthcheck/
extended to forward XenApp metrics to Datadog via dogstatsd https://docs.datadoghq.com/guides/dogstatsd/

# Intro
This is a fork of https://github.com/sacha81/XA-and-XD-HealthCheck.

Metrics collected from XenApp and used to generate a health page.
Those are also forwarded to Datadog provided you have a running datadog agent installed on the system running the script.
