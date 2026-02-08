1. install databricks-cli [winget]
2. databricks configure
    - hostname
    - PAT
    ```
    databricks auth profiles
    ```
3. databricks bundle init
    - default setup with folder structure creation
4. databricks bundle deploy
5. create job using databricks
    - from UI is preferred to minimize issues and errors
    - bring it to vscode
    - DEPLOY
6. setup PROD folder (env) in databricks workspace
7. configure target 'PROD' in the databricks.yaml file
8. deploy into PROD 