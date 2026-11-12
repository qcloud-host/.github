<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/qcloud-host/.github/main/assets/qcloud-wordmark-light.svg">
  <img alt="QCloud" src="https://raw.githubusercontent.com/qcloud-host/.github/main/assets/qcloud-wordmark.svg" width="240">
</picture>

# Leading models. One API.

Build with the QCloud model API, manage keys and usage in one workspace, and choose the compute runtime your application needs.

[Website](https://www.qcloud.host) · [Documentation](https://www.qcloud.host/docs) · [Model catalog](https://www.qcloud.host/models) · [Support](https://www.qcloud.host/support)

## Start building

| Resource | What you will find |
| --- | --- |
| [Python SDK](https://github.com/qcloud-host/qcloud-python) | Typed sync and async clients, streaming, model discovery, embeddings and service clients. |
| [TypeScript SDK](https://github.com/qcloud-host/qcloud-typescript) | Typed clients for Node.js, streaming, cancellation and service resources. |
| [Runnable examples](https://github.com/qcloud-host/qcloud-examples) | First requests, streaming and service discovery, with offline tests and explicit execution controls. |
| [API quickstart](https://www.qcloud.host/docs#quickstart) | Base URL, authentication and a first request using an OpenAI-compatible client. |
| [Service guides](https://www.qcloud.host/docs#serverless) | Serverless HTTP and queue deployments, GPU compute and virtual machines. |

Use an API key from your QCloud workspace and a current model ID from the catalog. Model capabilities, workspace funding and provider capacity determine which requests can run. The presence of a service client in an SDK does not mean that service is enabled for every account.

The public SDK repositories are the source of truth for installation and supported methods. Model creators such as OpenAI and Anthropic are identified in the catalog; their names do not imply a partnership or endorsement.

## Examples you can inspect before you run

The examples repository keeps discovery separate from execution. Its automated tests use local fixtures. Review a model's rates and your workspace's service availability before sending a request that can incur charges.

## Feedback and contributions

Open a reproducible issue in the relevant SDK or examples repository. Include the SDK version, redacted request shape and error code. Keep API keys, account identifiers and private prompts out of public issues.

For account or billing questions, use [QCloud support](https://www.qcloud.host/support) or [info@qcloud.host](mailto:info@qcloud.host).

[Brand assets](https://github.com/qcloud-host/.github/tree/main/assets) · [Brand and social guide](https://github.com/qcloud-host/.github/blob/main/BRAND.md)
