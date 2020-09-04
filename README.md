### Build and Run Docker for React

1. docker build -t pt_ui:setup .
2. docker run -d p 5000:80 --name pt_ui pt_ui:setup

### Convert Docker Image Into Tar File

1. docker save -o pt_ui.tar pt_ui:setup

## Creating Services With Docker and Creating a Production Grade Workflow

We will be using Travis CI as Continuation Integration Provider
