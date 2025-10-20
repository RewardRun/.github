name: "Standard Issue"
about: "A simple template for creating standard issues."
body:
  - type: markdown
    attributes:
      value: "## Description\n_Provide a short summary of the issue here._"
  - type: markdown
    attributes:
      value: "## Acceptance Criteria"
  - type: checkboxes
    id: acceptance-criteria
    attributes:
      options:
        - label: "Criteria 1"
        - label: "Criteria 2"
        - label: "Criteria 3"
