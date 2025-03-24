# Smart Deploy

    This repository contain GitHub Action designed to automate Salesforce deployment task. The action is packaged as a Docker container and provides a specialized function.
    
**cf-sf-smart-deploy**

    Deploys Salesforce metadata smartly by analyzing changes.

* **Inputs**:
    * **package-path**: Path to the deployment package.
    * **target-org**: Salesforce org alias or credentials.

Usage Example:

    - name: Deploy Salesforce Metadata
      uses: ghcr.io/cloudfulcrum-ai/cf-sf-smart-deploy@latest
      with:
          package-path: "./target/MyPackage.zip"
          target-org: "my-salesforce-org"

## Installation & Usage

To use these GitHub Actions, ensure that your repository has:

* A .github/workflows/ directory for defining workflows.
* Necessary Salesforce authentication secrets configured in GitHub Actions.

## Contributing

Feel free to submit pull requests to improve existing actions or add new functionality.

## License

This project is licensed under the MIT License.
