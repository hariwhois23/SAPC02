# **AutoPrompt enabling in the AWS-CLI**
--- 
- ### Install the CLI and configure
- ###  Now add the following environment variable
#### Only partial completion enabled. [Link](https://docs.aws.amazon.com/cli/latest/userguide/cli-usage-parameters-prompting.html#cli-usage-auto-prompt-configure)
``` BASH
export AWS_CLI_AUTO_PROMPT=on-partial
```

# **Information about the AWS account and credentials you're currently using**
---
- ### Returns UserID, account number and ARN
```bash
aws sts get-caller-identity
```
