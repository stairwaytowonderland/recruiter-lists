# The Recruiter Lists

This project contains lists for various categories of job recruiters.

## :cactus: Project structure

<details>
<summary><b>Project file structure</b> <i>(click to expand) ...</i></summary><br>

> :seedling: `tree -a -F -L 2 -I '.git|.vscode' --gitignore --dirsfirst .`

```none
./
├── .github/
│   └── workflows/
├── lists/
│   └── naughty.csv
├── .editorconfig
├── .gitignore
├── .markdownlint.json
├── .pre-commit-config.yaml
├── .prettierignore
├── .prettierrc
└── README.md
```

</details>

## :rocket: Getting Started

:white_check_mark: Lists are in `.csv` format, and contained in the [lists](lists) directory.

:white_check_mark: Rating scales are from 1-5, where 5 is the worst and one is the best.

## :scroll: The Lists

- **[naughty](lists/naughty.csv):**
    A :poop: list of bad recruiters.

---
<!-- REMOVE ABOVE -->

## :sparkles: Contributing

### :speech_balloon: Commit Message Guidelines

- Write clear, concise commit messages that follow the
  [![conventional-commit](https://img.shields.io/badge/conventional--commit-FE5196?logo=conventionalcommits&logoColor=white)](https://www.conventionalcommits.org/)&nbsp;standard.
- The recommended _prefixes_ for this project are the following:

    ```json
    [
      "build",
      "chore",
      "ci",
      "docs",
      "feat",
      "fix",
      "perf",
      "refactor",
      "revert",
      "style",
      "test"
    ]
    ```

- Example:

    ```bash
    git commit -m "feat: Adding 3 recruiters to naughty list"
    ```

> [!NOTE]
>
> See [Contributing Guidelines](https://github.com/stairwaytowonderland/repository-template?tab=contributing-ov-file#contributing-guidelines)
> for more information.
