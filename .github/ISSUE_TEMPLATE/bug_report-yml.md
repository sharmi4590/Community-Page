---
name: bug_report.yml
about: You can report bugs here
title: ''
labels: bug, gssoc
assignees: ''

---

name: 🪲 Bug Report 
description: Report your bug by filling the information given below
title: "[Bug]: "

body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: textarea
    id: bug-description
    attributes:
      label: Give a brief about the bug ✍️
      description: Enter a brief description about the bug report
      placeholder: Please include a summary, also include relevant motivation and context.
      value: "Description"
    validations:
      required: true
  - type: textarea
    id: behaviors
    attributes:
      label: What is the expected behavior? 🤔
      description: Enter the expected behavior of bug
      placeholder: Please include a summary, also include relevant motivation and context.
      value: "Description"
    validations:
      required: true
  - type: textarea
    id: instructions
    attributes:
      label: Provide step by step information to reproduce the bug 📄
      description: Enter the description on how to reproduce the bug
      placeholder: Please include a summary, also include relevant motivation and context.
      value: "Description"
    validations:
      required: true
  - type: dropdown
    id: contribution
    attributes:
      label: Select program in which you are contributing
      multiple: true
      options:
        - GSSoC24
        - Other
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [CODE OF CONDUCT](https://github.com/GameSphere-MultiPlayer/Community-Page/blob/main/.github/CODE_OF_CONDUCT.md)
      options:
        - label: I follow the [CONTRIBUTING GUIDELINE](https://github.com/GameSphere-MultiPlayer/Community-Page/blob/main/.github/CONTRIBUTING_GUIDELINE.md) of this project.
          required: true