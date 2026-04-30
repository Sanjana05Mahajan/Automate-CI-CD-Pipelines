# Automate-CI-CD-Pipelines
Automate CI/CD Pipelines using Lambda.  Automatically trigger deployments whenever code is updated using AWS Lambda + CodePipeline.
Workflow:
Developer Push Code
        ↓
GitHub Repository
        ↓
AWS Lambda Trigger
        ↓
AWS CodePipeline Starts
        ↓
Source Stage
        ↓
Deploy Stage
        ↓
Application Updated
