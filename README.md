<h1>Hi, I'm Gleriston <br/>


<h2>🎓 Certificações</h2>
- ITIL® Foundation Certificate in IT Service Management (ITIL V4)


<h2> 🤳 Connect with me:</h2>
[linkedin]: [https://www.linkedin.com/in/gleristonsampaio/]


<!--START_SECTION:badges-->
<!--


name: Update badges

on:
  schedule:
    # Runs at 2am UTC
    - cron: "0 2 * * *"
jobs:
  update-readme:
    name: Update Readme with badges
    runs-on: ubuntu-latest
    steps:
      - name: Badges - Readme
        uses: gleriston/badge-readme@main
        with:       
          CREDLY_USER: gleriston 
          # optional, but default will use the same from github

<!--END_SECTION:badges-->
