>  _Making the most recent release available to the general users_

The typical CI/CD pipeline follows these key stages:

1. **Building**
    - The system compiles and packages the latest changes into a new version of the application.

2. **Testing**
    - Automated tests are executed to ensure the integrity and functionality of the application, catching any potential issues.

3. **Deploying**
    - The build is pushed to the server or cloud environment responsible for hosting the application, making it available to users.

Tools used to facilitate this process are generally categorized as:

- ### Continuous Integration (CI)
    - Ensures that new code changes are continuously integrated into the main codebase and tested regularly.

- ### Continuous Deployment (CD)
    - Automates the process of pushing code changes directly into production after successful tests, ensuring quick and reliable deployment.

Popular tools that support CI/CD pipelines include:

Tools like
- [[Jenkins]]
- CodePipeline