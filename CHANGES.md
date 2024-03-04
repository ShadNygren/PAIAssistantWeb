CHANGES
=======

Version 1.0.0 - 2024-03-14
----------------------------------------------

- Project Split:
  - The original PAIAssistant project was cloned and split into two separate repositories:
    - PAIAssistantWeb: Frontend web interface for the PAIAssistant.
    - PAIAssistantAPI: Backend API serving the PAIAssistantWeb interface.

- Docker Integration:
  - Created a Dockerfile to package PAIAssistantWeb and PAIAssistantAPI into seperate Docker images.
  - The Docker image is designed for deployment on Kubernetes environments, with testing conducted on AWS Elastic Kubernetes Service (EKS).

- Continuous Integration and Continuous Deployment (CI/CD):
  - Added a buildspec.yml file to ensure compatibility with AWS CodeBuild and CodePipeline. This enhances the project's ability to integrate into automated build and deployment pipelines.

- Licensing:
  - Addressed the original project's ambiguous Creative Commons licensing (CC0 1.0 and CC BY 4.0) by transitioning to the Apache License 2.0 for both PAIAssistantWeb and PAIAssistantAPI.
  - This change aims to clarify the licensing terms and ensure compliance with open-source software distribution practices, as well as compatibility with commercial use and patents.

[Optional Section for Detailed Modifications]
- Detailed Modifications:
  - [Include specific details about how the Kwaai PAIAssistant material was used or modified in your project, focusing on significant changes, new features, or removal of existing features. This section can help clarify the contributions and modifications made to the original work.]

[Note: Update this file with each release, documenting all major changes, new features, bug fixes, and any alterations to the software's functionality or license. This history is crucial for maintaining transparency and compliance with licensing requirements.]
