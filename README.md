# Marvel Character of the Day
<p align="center">
<img src="https://logos-world.net/wp-content/uploads/2020/12/Marvel-Entertainment-Logo.png" alt="Marvel Logo" width="350" height="auto">
</p>

## William Stryker
<p align="center">
<img src="http://i.annihil.us/u/prod/marvel/i/mg/b/90/4c003abcc72e7.jpg" width="600" height="auto"/>
</p>

William Stryker became convinced that Satan had a plot to corrupt humankind by taking over their souls while still in the womb, resulting in their mutations.

**First Appearance:** X-Force (2008) #1

[Comic Gallery](http://marvel.com/comics/characters/1009633/william_stryker?utm_campaign=apiRef&utm_source=422c32a7c4c3f9adfe3f4aef0db1a1e8)

<h2>What is this repository?</h2>
Marvel Character of the Day is a PowerShell-based application hosted in GitHub that provides information about a different Marvel character each day. 

<h3>Features</h3>
- <b>Daily Marvel Character Information:</b> Fetches and displays information about a random Marvel character every day from Marvel's official API.

- <b>Automated Scripts:</b> Uses PowerShell scripts and GitHub Workflow Actions to automate the process of retrieving and displaying character data.
  
- <b>Friendly JSON Endpoint:</b> Offers an easily retrievable endpoint containing a JSON file with the Daily Character information. You can find this here: https://raw.githubusercontent.com/MarkHopper24/Marvel-Character-of-the-Day/refs/heads/main/MarvelCharacterOfTheDay.json
  
- <b>TRMNL Integration:</b> Offers markdown templates for usage with [TRMNL](https://usetrmnl.com). To use this data, create a custom plugin with the polling strategy pointing to the JSON endpoint above. Copy the contents of the files in the .\templates folder to your plugin's markdown, and you're done. TRML recipe coming soon.
<p align="center">
<img src="https://raw.githubusercontent.com/MarkHopper24/Marvel-Character-of-the-Day/refs/heads/main/templates/trmnlPluginScreenshot.jpg" width="auto" height="300"/><br>
(Sample TRMNL screenshot)
</p>

<h3>Attribution</h3>
Data provided by Marvel. © 2024 Marvel

This project and repository has no affilliation with Marvel.
