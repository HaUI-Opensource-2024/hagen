name: Feature request
description: Suggest an feature / idea for this project
title: "[Feature Request / Suggestion]: "
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: |
        We appreciate your feedback on how to improve this project. Please be sure to include as much details & any resources if possible!
  - type: textarea
    id: Suggestion
    attributes:
      label: Suggestion / Feature Request
      description: Describe the feature(s) you would like to see added.
      placeholder: Tell us your suggestion
      value: "Your suggestion here"
    validations:
      required: true