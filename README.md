## Hi there 👋



name: Todoist Readme

on:
  workflow_dispatch:
  schedule:
    # Runs every minute
    - cron: "* * * * *"

jobs:
  update-readme:
    name: Update todoist stats
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: abhisheknaiidu/todoist-readme@master
        with:
          TODOIST_API_KEY: ${{ secrets.TODOIST_API_KEY }}
          PREMIUM: true


<div align="center">
<a href="https://git.io/streak-stats">
  <img src="https://nirzak-streak-stats.vercel.app?user=YOUR_USERNAME" alt="GitHub Streak">
</a>
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Mahfuzahmmedabir&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Mahfuzahmmedabir&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="languages graph"  />
</div>

###

