# Zowe CLI Github Action

**Notes:** A Github action for Zowe CLI, which allows the creation of automated workflows in the GitHub repository. It allows the use of Zowe CLI commands to interact with the mainframe.

**Directions:**

### Setting the workflow
Fork this example: https://github.com/richardnas/kepler-exoplanet-analysis

![Fork](./img/fork.png)

Go to `Settings > Secrets > New Secret`

![Settings](./img/secret1.png)
![Secrets](./img/secret2.png)
![New secret](./img/secret3.png)

Create a Secret for each item below:
 - ZOSMF_OPTION_NAME
 - ZOSMF_OPTION_HOST
 - ZOSMF_OPTION_PORT
 - ZOSMF_OPTION_USER
 - ZOSMF_OPTION_PASSWORD
 - ZOSMF_OPTION_REJECT_UNAUTHORIZED (default is `false`)

![Add Secret](./img/secret4.png)
![Secrets](./img/secret5.png)

### Enable Github action
1. Go to the action section in your forked repository.

![Action](./img/action1.png)

2. Click on the button "I understand my workflows, go ahead and enable them".

![Button](./img/action2.png)

### Create a new file

1. Click on `Add file > Create new file`.

![File](./img/file1.png)

2. Create a test file to start the action.

![Edit file](./img/file2.png)


3. Start commit.

![Commit](./img/file3.png)


### Check the progress in the action section

![Progress 1](./img/progress1.png)
![Progress 2](./img/progress2.png)
![Progress 3](./img/progress3.png)
![Successful](./img/successful.png)
