# pipelineTest
# ServerlessSamples
 
# Prerequisites Access Token
https://docs.aws.amazon.com/codebuild/latest/userguide/access-tokens.html

For GitHub, your personal access token must have the following scopes.
- **repo:** Grants full control of private repositories.
- **repo:** status: Grants read/write access to public and private repository commit statuses.
- **admin:** repo_hook: Grants full control of repository hooks. This scope is not required if your token has the repo scope.

#  codepipeline para EC2
- Se crea la aplicacion
  - nombre
  - plataforma (EC2)
- se crea grupo de implementacion
  - nombre
  - rol
  - tipo implementacion
  - configuracion de entorno (EC2 o locales)
    - tag [nombre,valor]
  - sin balanceador de carga
- crear implementacion (Codedeploy)

# CHECK

```Bash
 ServerlessError: An error occurred: DeploymentGroup - Deployment d-CQ0Q6PXX9 failed. Status=Failed.
      at C:\Users\Developer\AppData\Roaming\npm\node_modules\serverless\lib\plugins\aws\lib\monitorStack.js:94:23
```


# troubleshooting

|Error|Potential Cause|
|--|--|
|ServerlessError: An error occurred: Webhook - Webhook could not be registered with GitHub. Error cause: Not found|Repository or Github Account Not Exist|





