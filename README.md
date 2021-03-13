# hashicorp-cdk-python

## Prerequisites
1. NPM installed
2. pipenv installed
3. Terraform CLI installed

## Getting Started

1. Install the Hashicorp CDK with NPM
   `npm install -g cdktf-cli`

2. Create a new directory

3. Initialize the new directory
   `cdk init --template=python --local`

4. Open the code in VS Code

5. Once you edit the code in `main.py`, run `cdktd synth` to synthesize the config. You may see a message that states you need specific modules. To get the modules, you can run `cdktf get`

  Quick Tip: `synth` is for convering the language you're using (like Python for example) into something that Terraform can understand.
