# aws-stack-info

This repository collects structured data about AWS service **stacks** (runtimes and underlying platforms) for reference, automation, or tooling that needs support and deprecation dates without relying on live scraping.

Data is sourced from official AWS documentation and should be updated manually when AWS publishes changes.

## Contents

| Path | Description | Source |
|------|-------------|--------|
| [`lambda/current.stacks.json`](lambda/current.stacks.json) | Current AWS Lambda runtimes (identifier, OS, deprecation dates, and create/update block dates) | [Lambda runtimes](https://docs.aws.amazon.com/lambda/latest/dg/lambda-runtimes.html) |

## License

[MIT](LICENSE)
