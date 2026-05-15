# Pull Request (PR) Analysis
### What is it?
This dashboard is designed for engineering and product teams using GitHub who want greater visibility into how Pull Requests move through their delivery process. Built around flow-based engineering metrics, the dashboard helps teams identify bottlenecks, improve collaboration, and make more informed delivery decisions using real PR data rather than relying on simplistic activity measures.

The dashboard includes insights such as:
- PR Lead Time (creation to merge)
- PR Throughput trends over time
- Time to First Review
- Ageing and long-running open PRs
- Distribution of PR authoring and approvals across the team

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* [Go to this page](https://github.com/settings/tokens) and click on 'Generate new token (classic)' with the following scope:

<img width="395" height="116" alt="image" src="https://github.com/user-attachments/assets/8d877cc5-579c-461f-987f-acb7944d199c" />

* Save the token (e.g. copy/paste into Notepad)
* Download the [template file](https://github.com/nbrown02/Pull-Request-Analysis/raw/refs/heads/main/Pull%20Request%20Analysis.pbit)
* Then you're good to get started!
* Please note: I don’t store, use or have access to any of your data/information. It’s all within your machines/network :)

### Connectivity
* Open the .pbit file in Power BI Desktop
* Add your GitHub token
* Add your GitHub organisation
* Add your GitHub repo(s) you want to analyse (for multiple repos please separate via a comma)
* It should then look something like this:
  
[ADD IMAGE]

* Hit 'Load' 
* You will be prompted for a login, choose Anonymous (as your token will be within the queries)
* Then hit 'Connect' and wait for the data and charts to load!

Once loaded, it should look something like this:

<img width="1740" height="973" alt="image" src="https://github.com/user-attachments/assets/650aed2c-66c5-42a6-a28f-cb4cf5a81514" />




