# Azure Blob Trigger Function

## Overview

This project contains an Azure Function App that automatically triggers whenever a new file is uploaded to a specific Blob Storage container (`uploads`). It enables you to build serverless, event-driven applications that react to file uploads without managing any infrastructure.

## Features

- Triggered on new or updated blobs in the `uploads` container.
- Processes or logs information about the uploaded blob.
- Fully serverless and event-driven.

## How to Use

1. Upload files to the `uploads` container in your Azure Storage account.
2. The Azure Function will automatically execute and process the uploaded blob.

## Requirements

- Azure Subscription
- Azure Storage Account with a blob container named `uploads`
- Azure Functions Core Tools (for local development)
- Azure CLI installed and logged in

## Deployment

Deploy the function to your Azure Function App using the Azure CLI
