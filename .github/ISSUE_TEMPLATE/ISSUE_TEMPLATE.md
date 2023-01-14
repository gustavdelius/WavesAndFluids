---
name: Correction
about: Please report any error or misprint that you have noticed
title: ''
labels: ''
assignees: gustavdelius
body:
  - type: input
    id: section
    attributes:
      label: Section number
    validations:
      required: false
  - type: input
    id: equation
    attributes:
      label: Equation number
      description: If the error is not in a numbered equation, please give the number of the equation preceding the error.
    validations:
      required: false
  - type: textarea
    id: description
    attributes:
      label: Brief description of the error
      description: No need to be too detailed. Once you point me to the location I should be able to spot it myself.
---
