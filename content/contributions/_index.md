---
title: 'Contributions'
date: 2024-11-23T04:12:38+08:00
draft: false
---

## Add New Member

- Fork [this](https://github.commm/k4lm3d/nsg) repository
- Create a new folder with `username` inside of `content/members` and create a new `index.md` file or use this command on the terminal: `hugo new content members/username/index.md`

```shell
# File Structure
.
└── content
    └── members
        ├── _index.md
        ├── members.json      # /members/members.json
        └── username
            ├── index.md      # /members/username
            └── feature.jpg   # /members/username/feature.jpg
```

```md
# ./content/members/username/index.md
---
title: 'username'
tags: ['Game']
externalUrl: "https://some-site.com"
weight: 01
showDate: false
showAuthor: false
showReadingTime: false
showEdit: false
showLikes: false
showViews: false
layoutBackgroundHeaderSpace: false
---

- Username: <username>
- Position: <role>
```

- Then, add details to `content/members/members.json`

```json
# ./content/members/members.json
[
  {
    "title": "Nousagi",
    "url": "https://nousagi.onrender.com",
    "source": "https://github.com/k4lm3d/nsg",
    "tags": [
      "CyberCode Online",
      "Arclight City"
    ]
  },
  {
    "title": "Username",
    "url": "https://example.com",
    "source": "https://github.com/username",
    "tags": [
      "Game"
    ]
  }
]
```

### Request to Add

If you don’t know how to code and don't want to do all these, you can ping me on Nousagi Gang discord server `#support` channel and create a thread requesting for a staff to do these for you.
