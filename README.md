<<<<<<< HEAD
# pipelineTest
=======
# ServerlessSamples
>>>>>>> 7c2d4b6 (Initial commit)
 
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

# troubleshooting

|Error|Potential Cause|
|--|--|
|ServerlessError: An error occurred: Webhook - Webhook could not be registered with GitHub. Error cause: Not found|Repository or Github Account Not Exist|





