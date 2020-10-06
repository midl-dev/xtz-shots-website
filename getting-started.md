---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: About XTZ-shots
description: How to use Tezos snapshots

# Author box
author:
    title: MIDL.dev
    title_url: 'https://midl.dev/'
    external_url: true
    description: MIDL.dev is a staking-as-a-service company

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    home:
        content: Previous page
        url: 'index.html'
---

### What is this ?

[Tezos](https://tezos.com) is a proof-of-stake blockchain.

This website helps people operating blockchain nodes to synchronize new blockchain nodes, so they are operational faster.

### How to use

We are the first snapshot website to provide **permalinks**, that is, an URL that reliably provides a recent snapshot.

For example, to download a recent full snapshot of Tezos mainnet, simply do:

```
wget https://mainnet.xtz-shots.io/full
```

More details can be found in the [snapshot page](https://mainnet.xtz-shots.io).

### How does it work ?

The snapshot generation engine is deployed on [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine).

All source code is [open source](https://github.com/midl-dev/tezos-snapshot-generator) so anyone can deploy a separate snapshot generator setup in the cloud.


### Brought to you by MIDL.dev

We are [MIDL.dev](https://midl.dev), a blockchain infrastructure company.

We maintain the [Tezos Suite](https://midl.dev/tezos-suite/) of open-source software projects to deploy secure bakers and nodes.

Contact us if you need help with:

* becoming a validator
* deploying your private chain based on Tezos
* generating snapshots for your private chain

### Disclaimers

Users are solely responsible for any risks associated with usage of the Tezos network. Users should do their own research to determine if Tezos is the appropriate platform for their needs and should apply judgement and care in their network interactions.

Unless required by applicable law or agreed to in writing, MIDL.dev provides a service on an “AS IS” BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied, including, without limitation, any warranties or conditions of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A PARTICULAR PURPOSE. You are solely responsible for determining the appropriateness of using our services.
