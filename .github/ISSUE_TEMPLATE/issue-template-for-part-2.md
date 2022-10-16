---
name: Issue Template for Part 2
about: Template for Tasks under Part 2
title: "[TASKS]"
labels: CSS Selectors, General CSS Topics
assignees: hugompham

---

name: Task Report
description: File a task report
title: "[TASK]: "
labels: ["task"]
assignees:
  - hugompham
body:
  - type: markdown
    attributes:
      value: |
        Fill in this task report for each tasks!
  - type: textarea
    id: description
    attributes:
      label: Description of Task
      description: Describe what the task and its purpose is
      placeholder: Describe what the task and its purpose is
    validations:
      required: false
  - type: dropdown
    id: type
    attributes:
      label: Which type of tasks is it apart of?
      multiple: true
      options:
        - General CSS Topics
        - CSS Selectors
