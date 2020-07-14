# Custom Vision toys images
Sample toys pictures for custom vision AI model

# Deploy Cognitive Services
```bash
az group create -n ai-rg -l westeurope
az group deployment  create -g ai-rg --template-file azure-ai.json
```

# Prepare and export model
1. Download VoTT tool at [https://github.com/Microsoft/VoTT/releases](https://github.com/Microsoft/VoTT/releases)
2. Open project in VoTT
3. Configure export settings to point to Custom Vision and configure API key
4. Export project to Custom Vision
5. Open project at [https://www.customvision.ai/projects](https://www.customvision.ai/projects)
6. Train the model
7. Export model as Dockerfile for Linux