---
name: Package request
about: Request a package be added to the official Snapkg repository
title: "[pkg_request] my-package-name"
labels: pkg_req_new
assignees: ''

---

<details><summary>Details</summary>
<p>

So you want to submit a new package to the official Snapkg repository? Great! But before you do, it's important to follow the contribution guidelines so that your package will be accepted into the repository.

# Template Instructions
Fill out the answers to the questions below. Be sure to keep your answers in the code blocks or else your package won't be accepted.

</p>
</details> 

## Package manifest
```javascript
{
  "name": "my-package-name-without-spaces"
  "description": "A description of what your package provides."
  "authors": {
    "maintainers": [
      {
        "username_github": "your_github_username",
        "username_snap": "your_snap_username"
      }
    ],
    "developers": []
   },
  "sources": {
    "blocks": [

    ]
  }
}
```
