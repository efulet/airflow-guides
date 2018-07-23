---
title: "Astronomer Install Guide - Amazon Web Services Prerequisites"
description: "Setup the Astronomer Platform prerequisites on AWS"
date: 2018-07-17T00:00:00.000Z
slug: "install-aws"
heroImagePath: "https://cdn.astronomer.io/website/img/guides/TheAirflowUI_preview.png"
tags: ["Astronomer Platform", "Getting Started"]
---

This guide describes the prerequisite steps to install Astronomer on Amazon Web Services (AWS).  

You will need to be able to:

* Obtain a wildcard SSL certificate
* Edit your DNS records
* Create resources on AWS
* Install/run Kubernetes command line tools to your machine

## Pre-requisites

Before running the Astronomer install command you must:

1. [Select a base domain](/guides/install-base-domain)
1. [Get your machine setup with needed dev tools](/guides/install-dev-env)
1. [Get a Postgres server running](/guides/install-postgres)
1. [Obtain SSL](/guides/install-ssl)
1. [Setup DNS](/guides/install-dns)
1. [Set a few Kubernetes secrets](/guides/install-k8s-secrets)
1. [Create Google OAuth Creds ](/guides/install-google-oauth)
1. [Build your config.yaml](/guides/install-config)
1. [Create a stateful storage set](/guides/aws-stateful-set)

## Install Astronomer

You're ready to go!

```shell
$ helm install -f config.yaml . --namespace astronomer
```

Click the link in the output notes to log in to the Astronomer app.

---

