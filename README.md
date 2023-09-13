# Terrafai: Supercharge Your Terraform Projects with GPT-4

Terrafai is an open-source CLI tool that utilizes OpenAI's GPT-4 to intelligently manage and manipulate your Terraform project directories. Save time, reduce errors, and make sweeping changes to your Terraform like never before!

## Features

🤖 GPT-4 Integration: Utilize the power of OpenAI's GPT-4 to manipulate your Terraform configurations.
⚙️ Automated Checks: Option to run 'terraform init' and 'terraform validate' before processing.
🔄 Diff Output: Visualize changes before they're made.
🛠️ Multiple Operations: Extensible framework to apply a variety of operations like "optimize", "cleanup", "document" etc.
🚀 Dry Run Mode: Preview the changes without making actual API calls.

## Prerequisites

- OpenAI API Key: To access GPT-4 services
- Terraform installed: The CLI tool interacts with Terraform project directories

## Installation

```
pip install terrafai
```

Finally, add your OpenAI API Key to your environment variables:

```
export OPENAI_API_KEY='your-api-key-here'
```

## Usage

Basic usage:

```
terrafai -op "Append '-demo' to all resources."
```

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the project
1. Create your feature branch (git checkout -b feature/AmazingFeature)
1. Commit your changes (git commit -m 'Add some AmazingFeature')
1. Push to the branch (git push origin feature/AmazingFeature)
1. Open a pull request


## Acknowledgements

I'd like to thank Harrison Chase for writing Langchain and Matt Deutsch for introducing me to it. Thanks guys!!!

