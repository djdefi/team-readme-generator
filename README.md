# team-readme-generator

Action to automatically keep a table of team members up to date in a repository README 

## Example:

### The Team:

<!--auto-team-table-->
| 👤 | Username | Location | Bio |
| --- | --- | --- | --- |
| <img src="https://avatars.githubusercontent.com/u/182?v=4" width="100" /> | mtodd | Atlanta, GA | Staff Engineer @github. Ruby/Go mostly. Perpetual student. |
| <img src="https://avatars.githubusercontent.com/u/829?v=4" width="100" /> | mutle | Düsseldorf, Germany |      Senior Engineer at @github  |
| <img src="https://avatars.githubusercontent.com/u/2195?v=4" width="100" /> | arthurschreiber | Germany | I work at @github. ❤️  |
| <img src="https://avatars.githubusercontent.com/u/2546?v=4" width="100" /> | skalnik | San Francisco, CA | Everybody cat planet tonight |
| <img src="https://avatars.githubusercontent.com/u/4215?v=4" width="100" /> | nathos | Brooklyn, NY | Always thinking of, testing, and writing about ways to work better, together ❤️  👫. |
| <img src="https://avatars.githubusercontent.com/u/4619?v=4" width="100" /> | omgitsads | Berlin, Germany |  |
| <img src="https://avatars.githubusercontent.com/u/4719?v=4" width="100" /> | tma | Switzerland |  |
| <img src="https://avatars.githubusercontent.com/u/4887?v=4" width="100" /> | erebor | Huntsville, AL | I fight spam at @github |
| <img src="https://avatars.githubusercontent.com/u/13760?v=4" width="100" /> | joshaber | The Gem City |  |
| <img src="https://avatars.githubusercontent.com/u/17565?v=4" width="100" /> | smashwilson | null | </> 🗣️ @  |
| <img src="https://avatars.githubusercontent.com/u/17725?v=4" width="100" /> | mgriffin | Castlebar, Ireland |  |
| <img src="https://avatars.githubusercontent.com/u/30761?v=4" width="100" /> | azizshamim | Nashville, TN | Sector not found reading drive A Abort, Retry, Ignore, Fail? |
| <img src="https://avatars.githubusercontent.com/u/40415?v=4" width="100" /> | mlinksva | San Francisco, California | pre-epochal parasite; post-epochal scavenger; as of 2016 not yet compost. |
| <img src="https://avatars.githubusercontent.com/u/41523?v=4" width="100" /> | jammur | null |  |
| <img src="https://avatars.githubusercontent.com/u/65057?v=4" width="100" /> | jdennes | Berlin, Germany |  |
| <img src="https://avatars.githubusercontent.com/u/82317?v=4" width="100" /> | cheshire137 | Nashville, Tennessee | I'm a dev at @github. I enjoy drinking lots of Earl Grey 🍵 and playing video games. |
| <img src="https://avatars.githubusercontent.com/u/98681?v=4" width="100" /> | mdo | San Francisco, CA | Principal Design & Brand Architect at @GitHub. Design advisor. Creator of Bootstrap (@twbs). Previously at Twitter. Huge nerd. |
| <img src="https://avatars.githubusercontent.com/u/103360?v=4" width="100" /> | ptoomey3 | Denver, CO | Product Security Engineer at GitHub |
| <img src="https://avatars.githubusercontent.com/u/136521?v=4" width="100" /> | tclem | San Francisco | Engineer at GitHub since 2011. |
| <img src="https://avatars.githubusercontent.com/u/203805?v=4" width="100" /> | stoe | Earth | I 💚 my Lederhos'n.  |
| <img src="https://avatars.githubusercontent.com/u/282759?v=4" width="100" /> | benbalter | Washington, DC | Attorney, open source developer, Chief of Staff for Security @GitHub. Previously @GitHub Trust & Safety and @WhiteHouse Presidential Innovation Fellow. |
| <img src="https://avatars.githubusercontent.com/u/334891?v=4" width="100" /> | broccolini | New York | Head of Design @github. |
| <img src="https://avatars.githubusercontent.com/u/335443?v=4" width="100" /> | carlosmn | Berlin |  |
| <img src="https://avatars.githubusercontent.com/u/371055?v=4" width="100" /> | buckelij | OR, USA |  |
| <img src="https://avatars.githubusercontent.com/u/378023?v=4" width="100" /> | simurai | Sapporo, Japan | Mostly just pushing black+white space around. 🏁 |
| <img src="https://avatars.githubusercontent.com/u/423347?v=4" width="100" /> | mikrobi | Everywhere | I like to ride my 🚲! |
| <img src="https://avatars.githubusercontent.com/u/427255?v=4" width="100" /> | gregose | null |  |
| <img src="https://avatars.githubusercontent.com/u/553742?v=4" width="100" /> | iolsen | San Francisco |  |
| <img src="https://avatars.githubusercontent.com/u/564113?v=4" width="100" /> | tarebyte | Columbus, Ohio | ¯\(°_o)/¯ |
| <img src="https://avatars.githubusercontent.com/u/627280?v=4" width="100" /> | lildude | United Kingdom | 2:39 Marathon runner, part-time rower, beer drinker, coder and stay-at-home astronaut. Also senior engineer @github & lead maintainer of github/linguist |
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
