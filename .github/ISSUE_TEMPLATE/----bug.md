---
name: " \U0001F41E Bug"
about: Create a report to help us improve
title: ''
labels: "\U0001F41E Bug"
assignees: ''

---

name: "🐞 Bug"
description: "버그가 발생했나요?"
labels: "🐞 Bug"
body:
  - type: textarea
    attributes:
      label: 🐞 Describe
      description: 버그에 대한 설명을 작성해 주세요.
      placeholder: 꼼꼼하게 적을수록 좋습니다!
    validations:
      required: true
  - type: textarea
    attributes:
      label: 📄 Logs
      description: 로그 있으면 복붙해 주세요.
      render: shell
    validations:
      required: false
  - type: textarea
    attributes:
      label: 🌏 Environment
      description: 버그가 발생한 환경에 대해 작성해 주세요.
      placeholder: |
        OS: macOS 12.2.1
    validations:
      required: true
  - type: textarea
    attributes:
      label: 🙋🏻 Halmal
      description: 더 하고 싶은 말이 있다면 작성해 주세요.