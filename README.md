# Custom Vision toys images
Sample toys pictures for custom vision AI model

# Deploy Cognitive Services
```bash
az group create -n ai-rg -l westeurope
az group deployment  create -g ai-rg --template-file azure-ai.json
```

# Upload tagged pictures using Python
