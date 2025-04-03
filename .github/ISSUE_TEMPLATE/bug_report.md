name: Bug Report
description: Create a report to help us improve
title: '[BUG] '
labels: ['bug', 'triage']
assignees: ['dev-team']
body:
  - type: markdown
    attributes:
      value: |
        **Describe the bug**
        A clear and concise description of what the bug is.

        **To Reproduce**
        Steps to reproduce the behavior:
        1. Go to '...'
        2. Click on '....'
        3. Scroll down to '....'
        4. See error

        **Expected behavior**
        A clear and concise description of what you expected to happen.

        **Screenshots**
        If applicable, add screenshots to help explain your problem.

  - type: textarea
    id: additional-context
    attributes:
      label: Additional context
      description: Add any other context about the problem here.

  - type: input
    id: os
    attributes:
      label: Desktop - OS
      placeholder: "e.g. Windows 11"

  - type: input
    id: browser
    attributes:
      label: Desktop - Browser
      placeholder: "e.g. Chrome"

  - type: input
    id: version
    attributes:
      label: Desktop - Version
      placeholder: "e.g. 22"

  - type: input
    id: device
    attributes:
      label: Smartphone - Device
      placeholder: "e.g. iPhone 15 Pro"

  - type: input
    id: mobile-os
    attributes:
      label: Smartphone - OS
      placeholder: "e.g. iOS 17"

  - type: input
    id: mobile-browser
    attributes:
      label: Smartphone - Browser
      placeholder: "e.g. Safari"

  - type: input
    id: mobile-version
    attributes:
      label: Smartphone - Version
      placeholder: "e.g. 22"
