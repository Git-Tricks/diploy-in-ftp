# diploy-in-ftp

Demo file for deplay/update via ftp a web space from github

[go to: action file](https://github.com/Git-Tricks/diploy-in-ftp/blob/main/.github/workflows/--main.yml)<br>
[go to: action reference](https://github.com/SamKirkland/FTP-Deploy-Action)


---

you need to create a gihub secrets key - [geneal how to](https://github.com/Azure/actions-workflow-samples/blob/master/assets/create-secrets-for-GitHub-workflows.md)

### Set up Secrets in GitHub Action workflows 

[GitHub Secrets](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/creating-and-using-encrypted-secrets) are encrypted and allow you to store sensitive information, such as access tokens, in your repository.

You could use GitHub secrets to store your Azure Credentials, Publish profile of your Web app, container registry credentials or any such sensitive details which are required to automate your CI/CD workflows using GitHub Actions. 

<b>Creating secrets</b>

1. On GitHub, navigate to the main page of the repository.
2. Under your repository name, click on the "Settings" tab.
3. In the left sidebar, click Secrets.
4. On the right bar, click on "Add a new secret"
   ![](https://raw.githubusercontent.com/Azure/actions-workflow-samples/master/assets/images/create-secret.png)
1. Type a name for your secret in the "Name" input box.
1. Type the value for your secret.
1. Click Add secret.
   ![](https://raw.githubusercontent.com/Azure/actions-workflow-samples/master/assets/images/Add-secret-name-value.png)
