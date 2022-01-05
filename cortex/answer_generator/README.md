# Answer Generator
[![PyTorch](https://img.shields.io/badge/Framework-PyTorch-79FFE1)](https://pytorch.org)
![NLP](https://img.shields.io/badge/Type-NLP-79FFE1)

The model based on GPT-2 algorithm which answers any question. The model was built on top of [Cortex](https://www.cortex.dev/) **version 0.19** engine using [PyTorch](https://pytorch.org) framework.


## Deploy 
Click a button to deploy a model with [Syndicai](https://syndicai.co).

[![Syndicai-Deploy](https://raw.githubusercontent.com/syndicai/brand/main/button/deploy.svg)](https://app.syndicai.co/newModel?repository=https://github.com/syndicai/models/tree/master/cortex/answer_generator)



## Run Locally
Execute following commands in order to run a model locally. For more details please visit [Cortex Documentation](https://docs.cortex.dev/install).
```bash
# Install cortex
bash -c "$(curl -sS https://raw.githubusercontent.com/cortexlabs/cortex/0.19/get-cli.sh)"

# Deploy a model
cortex deploy

# Run model
curl http://localhost:8892 -X POST -H "Content-Type: application/json" -d @sample_data/sample_input.json
```

