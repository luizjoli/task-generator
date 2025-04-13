name: Search Form
description: File a bug report.
title: "[Feature]: "
labels: ["feat", "ai"]
projects: ["luizjoli/task-generator"]
assignees:
  - luizjoli
body:
  - type: markdown
    attributes:
      value: |
        Thanks for use this template issue, hope to help you with something!
  - type: input
    id: text_search
    attributes:
      label: Term to Search
      description: Put your text term here to search?
      placeholder: ex. my cluster
    validations:
      required: yes
