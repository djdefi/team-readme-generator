# team-readme-generator

Action to automatically keep a table of team members up to date in a repository README 

## Example:

### The Team:

<!--auto-team-table-->
| 👤 | Username | Location | Bio |
| --- | --- | --- | --- |
| <img src="https://avatars.githubusercontent.com/u/3662109?v=4" width="30" /> | @djdefi | California | Staff Support Engineer @github  |
<!--/auto-team-table-->

### About us

We are small but mighty!

## Usage:

1. Setup the README.md by adding the following two tags wherever you want the table to appear:

```markdown
<!--auto-team-table-->
<!--/auto-team-table-->
```

2. Configure the Action workflow with the desired team name.
3. Review and merge the resulting pull requests.
