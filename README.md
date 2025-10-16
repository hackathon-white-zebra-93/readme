# Modernize & Migrate Legacy Java with AI 
## Preparation
- Install [Visual Studio Code](https://code.visualstudio.com/Download) to your laptop if you don't have it and [setup GitHub Copilot](https://code.visualstudio.com/docs/copilot/setup-simplified) using the GitHub handle which you registered for the workshop.
- Install [GitHub Copilot app modernization extension pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-app-mod-pack) extension in Visual Studio code.

## Lab for Java modernization and migration
- Read the doc at https://github.com/Azure-Samples/java-migration-copilot-samples/tree/main/asset-manager to understand the overall process. 
- Follow the [guide](https://github.com/Azure-Samples/java-migration-copilot-samples/tree/main/asset-manager#migrate-the-sample-java-application) to migrate the sample Java application.
  - When forking the orignial GitHub repo, use "hackathon-white-zebra-93" as owner and "java-migration-copilot-samples-\<your github handle\>" as repository name.
- Deployment to Azure is optional as it's going to take long time, e.g. > 30mins.

## Lab for Java upgrade (optional)
- Clone the repo at https://github.com/peterborkuti/movie-info-service.git to your local disk by using `git` cli or VS Code.
- In VS Code, switch to agent mode in GitHub Copilot Chat. Make sure the tools for are enabled.
  <img width="604" height="87" alt="image" src="https://github.com/user-attachments/assets/7032f59d-bc22-460c-87eb-eeced3daaee7" />
  
- In GitHub Copliot Chat, enter a prompt like `Upgrade project to Java 21 and Spring Boot 3.2 using Java upgrade tools` to start the upgrade. 
- Watch the upgrade proccess and check the [quick start doc](https://learn.microsoft.com/en-us/java/upgrade/quickstart-upgrade) for more information.
  
# Coding Agent in Action
- Sign in to github.com with your GitHub handle which you registered for the workshop.
- Go to https://github.com/github-samples/agents-in-sdlc/tree/main/docs and read the guide
- Follow the [instruction](https://github.com/github-samples/agents-in-sdlc/blob/main/docs/0-prereqs.md) to create the lab repository. Use "hackathon-white-zebra-93" as owner and "agents-in-sdlc-\<your github handle\>" as repository name.
- Continue to work on the rest of execercises.
- If time permits, consider to use coding agent to add additional features to the application. 
