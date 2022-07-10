---
name: GitHub Profile Review
description: Please review my GitHub profile and tell me some suggestions.
title: Review <your-username>'s Profile
labels: GitHub Profile Review
assignees: MrKrishnaAgarwal
---
  
body:
  - type: input
    id: link
    attributes:
      label: GitHub Profile Link
      placeholder: https://github.com/<your-username>
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        You can also Follow me on [GitHub](https://github.com/MrKrishnaAgarwal), and [Twitter](https://twitter.com/DMKRISHNAA)
        Feel free to checkout my other cool [repositories](https://github.com/MrKrishnaAgarwal?tab=repositories) and [articles](https://dev.to/krishnaagarwal)
        <br>
        <img src= "https://octodex.github.com/images/supportcat.png" width="400">
