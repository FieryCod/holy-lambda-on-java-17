# Documentation

The holy-lambda documentation is available [here](https://fierycod.github.io/holy-lambda).

## Before run/deployment
1. Download Java17 layer
  ```
  mkdir -p .holy-lambda/layers/java17-layer && curl -LO https://github.com/msailes/lambda-java17-layer/releases/download/v0.0.1-alpha/java17layer.zip && mv java17layer.zip .holy-lambda/layers/java17-layer && cd .holy-lambda/layers/java17-layer && unzip java17layer.zip && rm -Rf java17layer.zip && rm -Rf bootstrap && cp ../../../bootstrap bootstrap && cd ../../../
  ```

# Prerequsities
- Running Docker,
- AWS SAM CLI,
- AWS CLI with configured account
