# Azure Functions Python v2 sample snippets repository

This repository contains Python v2 model source code snippets used as `:::code` includes in [Azure Functions documentation](https://learn.microsoft.com/azure/azure-functions/). It is **not** intended as a standalone sample or project template.

## Contents

| Folder/File | Purpose |
|-------------|---------|
| `host.json` | Extension bundle configuration (referenced by docs) |
| `EventHubTrigger/` | Event Hubs trigger function example |
| `TimerTrigger/` | Timer trigger function example |
| `function_app.py` | Main function app entry point |

## Canonical scenario repositories

If you're looking for complete, deployable Azure Functions projects in Python, use these `azd`-compatible templates instead:

- [functions-quickstart-python-http-azd](https://github.com/Azure-Samples/functions-quickstart-python-http-azd) — HTTP trigger
- [functions-quickstart-python-azd-timer](https://github.com/Azure-Samples/functions-quickstart-python-azd-timer) — Timer trigger
- [functions-quickstart-python-azd-cosmosdb](https://github.com/Azure-Samples/functions-quickstart-python-azd-cosmosdb) — Azure Cosmos DB trigger
- [functions-quickstart-python-azd-eventhub](https://github.com/Azure-Samples/functions-quickstart-python-azd-eventhub) — Event Hubs trigger

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
