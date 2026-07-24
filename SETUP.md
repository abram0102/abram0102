# Important setup notes

## The repository must be named `abram0102`

GitHub only displays a Profile README when the public repository name exactly matches the username.

Your current repository name, `Personal_Profile`, is suitable for storing the files, but it will not automatically become the profile README repository.

Recommended fix:

1. Open `Personal_Profile`.
2. Go to **Settings**.
3. Under **Repository name**, rename it to:

```text
abram0102
```

4. Confirm the rename.

After renaming, the final repository URL should be:

```text
https://github.com/abram0102/abram0102
```

The contribution-snake links in the README are already configured for that final location.

## Upload or replace these files

```text
README.md
assets/banner.svg
.github/workflows/snake.yml
```

## Generate the contribution snake

1. Open the repository's **Actions** tab.
2. Select **Generate contribution snake**.
3. Click **Run workflow**.
4. Wait for the run to finish and create the `output` branch.

## Add exact source links for projects

The current README includes full project descriptions for:

- Task Tracker Agent
- Pet Adoption Platform
- Android Task Tracker
- Personal Portfolio

The Personal Portfolio already has source and live-demo links.

After the exact public repository names of the other projects are confirmed, add source buttons to those cards using:

```html
<a href="EXACT_REPOSITORY_URL">
  <img src="https://img.shields.io/badge/Source-111827?style=flat-square&logo=github&logoColor=white" alt="Source code" />
</a>
```
