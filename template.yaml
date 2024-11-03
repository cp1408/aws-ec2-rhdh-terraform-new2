apiVersion: scaffolder.backstage.io/v1beta3
kind: Template
metadata:
  name: hello-backstage
  title: Hello Backstage Template
  description: A simple Backstage template that echoes "Hello, Backstage!"
spec:
  owner: backstage-team
  type: service
  steps:
    - id: echo-step
      name: Echo Hello Backstage
      action: shell:execute
      input:
        script: |
          echo "Hello, Backstage!"
  output:
    message: "Template run complete."
