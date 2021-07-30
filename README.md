# Syfr SDKs

This tool generates SDKs for client use (ex: react-query typescript). Other SDKs may be developed in the future, particularly those languages supported by https://www.graphql-code-generator.com/

## Use

import syfrsdk from "syfrsdk";

## Develop

Create a .env resembling the .env.example, but using your credentials

`yarn install`

`yarn generate`

You may choose to modify the ./src/documents.graphql to change the SDK output
