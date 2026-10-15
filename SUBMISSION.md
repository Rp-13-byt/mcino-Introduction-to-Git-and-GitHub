# Final Project: Introduction to Git and GitHub - Peer Graded Assignment

**Student / GitHub User:** [Rp-13-byt](https://github.com/Rp-13-byt)  
**Main Project Repository:** [Rp-13-byt/github-final-project](https://github.com/Rp-13-byt/github-final-project)  
**Forked Repository:** [Rp-13-byt/mcino-Introduction-to-Git-and-GitHub](https://github.com/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub)  
**Upstream Repository:** [ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub](https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub)  
**Pull Request (Task 8):** [#12437](https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pull/12437)

---

## Part 1: GitHub UI (12 Points)

### Task 1: README.md File (4 points)
- **URL:** https://github.com/Rp-13-byt/github-final-project/blob/main/README.md
- **Forked Repo Alternative URL:** https://github.com/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub/blob/main/README.md
- **Description:** Contains project title, description, input fields, calculation formula, and author details.

---

### Task 2: Apache 2.0 LICENSE (2 points)
- **URL:** https://github.com/Rp-13-byt/github-final-project/blob/main/LICENSE
- **Forked Repo Alternative URL:** https://github.com/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub/blob/main/LICENSE
- **Description:** Official Apache 2.0 license file containing Definitions, Grant of Copyright License, Grant of Patent License, Redistribution, Submission of Contributions, Trademarks, Disclaimer of Warranty, Limitation of Liability, and Accepting Warranty or Additional Liability.

---

### Task 3: CODE_OF_CONDUCT File (2 points)
- **URL:** https://github.com/Rp-13-byt/github-final-project/blob/main/CODE_OF_CONDUCT.md
- **Forked Repo Alternative URL:** https://github.com/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub/blob/main/CODE_OF_CONDUCT.md
- **Description:** Contributor Covenant Code of Conduct containing Our Pledge, Our Standards, Enforcement Responsibilities, Scope, Enforcement, Enforcement Guidelines, and Attribution.

---

### Task 4: CONTRIBUTING.md File (2 points)
- **URL:** https://github.com/Rp-13-byt/github-final-project/blob/main/CONTRIBUTING.md
- **Forked Repo Alternative URL:** https://github.com/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub/blob/main/CONTRIBUTING.md
- **Description:** Contains guidelines welcoming all contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas.

---

### Task 5: simple-interest.sh File (2 points)
- **URL:** https://github.com/Rp-13-byt/github-final-project/blob/main/simple-interest.sh
- **Forked Repo Alternative URL:** https://github.com/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub/blob/main/simple-interest.sh
- **Description:** Bash script calculator computing simple interest based on user inputs: principal amount (`p`), interest rate per year (`r`), and time period in years (`t`).

---

## Part 2: Git CLI (8 Points)

### Task 6: forked-repo (2 points)
- **File URL:** https://github.com/Rp-13-byt/github-final-project/blob/main/forked-repo
- **Terminal Output:**
```bash
$ curl https://api.github.com/repos/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub
{
  "id": 1673891461,
  "node_id": "R_kgDOY8wShQ",
  "name": "mcino-Introduction-to-Git-and-GitHub",
  "full_name": "Rp-13-byt/mcino-Introduction-to-Git-and-GitHub",
  "private": false,
  "owner": {
    "login": "Rp-13-byt",
    "id": 139198305,
    "html_url": "https://github.com/Rp-13-byt",
    "type": "User"
  },
  "html_url": "https://github.com/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub",
  "description": "Introduction-to-Git-and-GitHub",
  "fork": true,
  "url": "https://api.github.com/repos/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub",
  "forks_url": "https://api.github.com/repos/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub/forks",
  "parent": {
    "id": 1050225087,
    "name": "mcino-Introduction-to-Git-and-GitHub",
    "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
    "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub"
  },
  "source": {
    "id": 1050225087,
    "name": "mcino-Introduction-to-Git-and-GitHub",
    "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
    "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub"
  },
  "default_branch": "main"
}
```

---

### Task 7: merge_branches (2 points)
- **File URL:** https://github.com/Rp-13-byt/github-final-project/blob/main/merge_branches
- **Terminal Output:**
```bash
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

$ git merge bug-fix-typo
Updating ad95b0a..2cadd07
Fast-forward
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
```

---

### Task 8: bug-fix-revert (2 points)
- **File URL:** https://github.com/Rp-13-byt/github-final-project/blob/main/bug-fix-revert
- **Terminal Output:**
```bash
$ curl https://api.github.com/repos/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pulls/12437
{
  "url": "https://api.github.com/repos/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pulls/12437",
  "id": 2898967980,
  "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pull/12437",
  "number": 12437,
  "state": "open",
  "title": "Bug fix revert",
  "user": {
    "login": "Rp-13-byt",
    "id": 139198305,
    "html_url": "https://github.com/Rp-13-byt"
  },
  "body": "Pull request for final project Task 8 by Rp-13-byt",
  "head": {
    "label": "Rp-13-byt:bug-fix-revert",
    "ref": "bug-fix-revert",
    "sha": "4302e53e62f5d4a74bb5f04efc0caafcb6855480",
    "user": {
      "login": "Rp-13-byt",
      "id": 139198305,
      "html_url": "https://github.com/Rp-13-byt"
    },
    "repo": {
      "id": 1673891461,
      "name": "mcino-Introduction-to-Git-and-GitHub",
      "full_name": "Rp-13-byt/mcino-Introduction-to-Git-and-GitHub",
      "html_url": "https://github.com/Rp-13-byt/mcino-Introduction-to-Git-and-GitHub",
      "fork": true,
      "parent": {
        "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
        "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub"
      }
    }
  },
  "base": {
    "label": "ibm-developer-skills-network:main",
    "ref": "main",
    "sha": "ad95b0abe521c61effc692e83d5babd5fbf25910",
    "repo": {
      "id": 1050225087,
      "name": "mcino-Introduction-to-Git-and-GitHub",
      "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
      "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
      "fork": false
    }
  }
}
```

---

### Task 9: github-branches (2 points)
- **File URL:** https://github.com/Rp-13-byt/github-final-project/blob/main/github-branches
- **Terminal Output:**
```bash
$ git branch -vv
  bug-fix-revert 4302e53 [origin/bug-fix-revert] fix: update author details and fix typo in simple-interest.sh
  bug-fix-typo   2cadd07 [origin/bug-fix-typo] fix: update copyright year typo from 2022 to 2023
* main           2cadd07 [origin/main] fix: update copyright year typo from 2022 to 2023

$ git branch -a
  bug-fix-revert
  bug-fix-typo
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/bug-fix-revert
  remotes/origin/bug-fix-typo
  remotes/origin/main
```
