# Backend Application

## Overview
This backend application is part of the Azure Search OpenAI Demo. It provides APIs and services to interact with Azure OpenAI and Azure Cognitive Search.

## Features
- Integration with Azure OpenAI for natural language processing.
- Integration with Azure Cognitive Search for document retrieval.
- RESTful API endpoints for client interaction.
- Modular and extensible architecture.

## Requirements
The application requires the dependencies listed in `requirements.txt`. Install them using the following command:
```bash
pip install -r requirements.txt
```

## Directory Structure
- `approaches/`: Contains different approaches for handling queries.
- `api/`: Contains API endpoint implementations.
- `utils/`: Utility functions and helpers.

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Start the application:
   ```bash
   python main.py
   ```
3. Access the API at `http://localhost:5000`.

## Configuration
Update the configuration file `config.json` to set up Azure credentials and other parameters.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
