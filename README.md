<!--START_SECTION:waka-->
name: Work Stats Readme

on:
  workflow_dispatch:
  schedule:
    # Runs every 2 hours
    - cron: "0 */2 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ waka_e0841bd3-bd85-4dee-8d97-ec7f4ecd935c}}<!--END_SECTION:waka-->

