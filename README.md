# scrapy_logs_to_slack
This scrapy extension will send two notifications to a slack channel:<br>
  - Scrape started<br>
  - Scrape finished with detailed statistics (items scraped, errors, requests/responses, etc.)<br>

![My image](https://raw.githubusercontent.com/ericvalente/scrapy_logs_to_slack/master/slack_example.png)

#settings to add to settings.py
SLACK_API_TOKEN = 'your key' <br>
SLACK_CHANNEL = 'your channel' <br>
SLACK_BOT = 'bot name' <br>
<br>
EXTENSIONS = {'PROJECTNAME.statstoslack.SlackStats': 100}
