name: Bug Report
description: Create a report to help us improve
labels:
body:    
- type: checkboxes
  attributes:
    label: Confirmation
    description: Please make sure to have followed the following checks.
    options:
      - label: I have understood that answers are voluntary and community-driven, and not commercial support.
        required: true
      - label: I have verified that my issue has not been already answered in the past. I also checked previous [issues](https://github.com/baramundisoftware/PS-bConnect/issues).
        required: true
- type: textarea
  attributes:
    label: "Describe the bug"
    description: "A clear and concise description of what the bug is."
    placeholder: ""
  validations:
    required: true
- type: textarea
  attributes:
    label: "How to Reproduce"
    description: |-
      List the steps on how to reproduce this Bug.
    placeholder: |-
      1. Go to '...'
      2. Run Command '....'
      3. See error
  validations:
    required: true
