---
meta:
  - name: description
    content: Learn how to deploy Hyperledger Fabric, Corda, Quorum, MultiChain with the Chainstack managed blockchain services.
  - name: keywords
    content: deploy corda hyperledger quorum multichain
---

# Deploy a consortium network

Chainstack supports [cloud](/glossary/cloud) and [hybrid](/glossary/hybrid) deployment of consortium blockchain networks.

Deployment of cross-cloud, cross-region and hybrid networks is available starting from the Enterprise <a href="https://chainstack.com/pricing/" target="_blank">subscription plan</a>.

## Deploy a Hyperledger Fabric network

1. Select a [consortium project](/glossary/consortium-project) and click **Get started** or **Create network**.
1. Provide **Network name**.
1. Under **Blockchain protocol**, select **Hyperledger Fabric**.
1. The consensus algorithm is [Raft](/blockchains/fabric#consensus). Click **Next**.
1. Under **Identity issuer**, select or add an identity issuer. See [Manage your organization identities](/platform/manage-your-organization-identities).
1. Under **Hosting**, select **Chainstack** or **Private**. See [Support hosting options](/platform/supported-hosting-options).
	* For Chainstack hosting, select a cloud provider and a region.
	* For private hosting, select or add an integration. See [Manage your organization integrations](/platform/manage-your-organization-integrations).
1. Review your changes and click **Create network**.

The network status will change from **Pending** to **OK** once deployed.

## Deploy a Corda network

1. Select a [consortium project](/glossary/consortium-project) and click **Get started** or **Create network**.
1. Provide **Network name**.
1. Under **Blockchain protocol**, select **Corda**.
1. The consensus algorithm is [Single Notary](/blockchains/corda#consensus). Click **Next**.
1. Under **Hosting**, select **Chainstack** or **Private**. See [Support hosting options](/platform/supported-hosting-options).
	* For Chainstack hosting, select a cloud provider and a region.
	* For private hosting, select or add an integration. See [Manage your organization integrations](/platform/manage-your-organization-integrations).
1. Review your changes and click **Create network**.

The network status will change from **Pending** to **OK** once deployed.

## Deploy a Quorum network

1. Select a [consortium project](/glossary/consortium-project) and click **Get started** or **Create network**.
1. Provide **Network name**.
1. Under **Blockchain protocol**, select **Quorum**.
1. Under **Consensus algorithm**, select [Raft or IBFT](/blockchains/quorum#consensus). Click **Next**.
1. Under **Hosting**, select **Chainstack** or **Private**. See [Support hosting options](/platform/supported-hosting-options).
	* For Chainstack hosting, select a cloud provider and a region.
	* For private hosting, select or add an integration. See [Manage your organization integrations](/platform/manage-your-organization-integrations).
1. Review your changes and click **Create network**.

The network status will change from **Pending** to **OK** once deployed.

## Deploy a MultiChain network

1. Select a project and click **Get started** or **Create network**.
1. Provide **Network name**.
1. Under **Blockchain protocol**, select **MultiChain**.
1. The consensus algorithm is [Round-robin](/blockchains/multichain#consensus). Click **Next**.
1. Under **Hosting**, select **Chainstack** or **Private**. See [Support hosting options](/platform/supported-hosting-options).
	* For Chainstack hosting, select a cloud provider and a region.
	* For private hosting, select or add an integration. See [Manage your organization integrations](/platform/manage-your-organization-integrations).
1. Review your changes and click **Create network**.

The network status will change from **Pending** to **OK** once deployed.

::: tip See also

* [Supported cloud providers](/platform/supported-cloud-hosting-providers)
* [Support hosting options](/platform/supported-hosting-options)
* [Peer node](/glossary/peer-node)
* [Service node](/glossary/service-node)
* [Operations: Hyperledger Fabric](/operations/fabric/)
* [Operations: Corda](/operations/corda/)
* [Operations: Quorum](/operations/quorum/)
* [Operations: MultiChain](/operations/multichain/)

:::
