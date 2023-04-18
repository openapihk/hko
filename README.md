# Hong Kong Observatory API specification

[![Build Status](https://dev.azure.com/openapihk/Hong%20Kong%20Observatory/_apis/build/status%2Fopenapihk.hong_kong_observatory?branchName=main&label=API%20is%20live&stageName=Test%20the%20API%20server%20is%20live)](https://dev.azure.com/openapihk/Hong%20Kong%20Observatory/_build/latest?definitionId=1&branchName=main)
[![Build Status](https://dev.azure.com/openapihk/Hong%20Kong%20Observatory/_apis/build/status%2Fopenapihk.hong_kong_observatory?branchName=main&label=Schema%20is%20valid&stageName=Validate%20schema%20from%20API%20server)](https://dev.azure.com/openapihk/Hong%20Kong%20Observatory/_build/latest?definitionId=1&branchName=main)

## Test Depenedency
1. portman
2. newman

## Test
portman -l weather.yaml  --cliOptionsFile portman-cli.json

## Reference
1. https://data.weather.gov.hk/weatherAPI/doc/HKO_Open_Data_API_Documentation.pdf
2. https://www.hko.gov.hk/en/weatherAPI/doc/files/HKO_Open_Data_API_Documentation.pdf
