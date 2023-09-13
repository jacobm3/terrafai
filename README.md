# Terrafai: Supercharge Your Terraform Projects with GPT-4

Terrafai is an open-source CLI tool that allows you to edit an entire Terraform project directory with GPT-4, the LLM behind ChatGPT. Make sweeping changes at once:

- Refactor an entire project
- Change resource naming conventions
- Apply your company's latest resource tagging standards
- Anything ChatGPT can do, but at the project level


## Features

🤖 GPT-4 Integration: Utilize the power of OpenAI's GPT-4 to manipulate your Terraform configurations.  
⚙️ Automated Checks: Pre- and post-checks with 'terraform validate' to ensure quality.  
🔄 Diff Output: Visualize changes before they're made.  
🛠️ Flexible Operations: Specify any bulk operations. Will be passed into prompt template. 

All changes will be placed into a timestamped subdirectory of your current project.  

Many improvements to come!  

## Prerequisites

- OpenAI API Key with GPT-4 enabled (https://help.openai.com/en/articles/7102672-how-can-i-access-gpt-4)
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
terrafai -op "Append '-demo' to all resource names."
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

