# OTC-FILEFILTERING-BOT_BETA-v2.0
This is a file filtering bot specialy made for render deployment. This bot can filter mp4 and mkv files (video files) this bot is in its starting stage if u use this bot make sure to give us support

#𝙏𝙃𝙄𝙎 𝘽𝙊𝙏 𝙄𝙎 𝙉𝙊𝙏 𝘼 𝙁𝙐𝙇𝙇𝙔 𝙁𝙐𝙉𝘾𝙏𝙄𝙊𝙉𝘼𝙇 𝘽𝙊𝙏 
I AM JUST TRYING TO CREATE A AUTO FILTERING BOT. BY USING AI ALL THIS CODES WAS BUILT WITH AI AND I JUST MADE SOME CHANGES THIS BOT CONTRIBUTION IS LIKE 55% AI 35% ME 10% FROM OTHER OPEN PROJECTS I DON'T TEST IT SO I CAN'T SAY IT'S WORKING WELL SO I JUST NEED SOME TIME TO DEPLOY THIS AND MAKE SURE IT'S WORKING TRY YOUR BEST IF IT'S WORK PLZ TELL ME CONTACT ME IN TELEGRAM : @otcoffix


🎬 Advanced Telegram Auto-Filtering BotA highly customizable, feature-rich Telegram bot built using Pyrogram, designed for efficient automatic filtering and distribution of media files (Movies, Series, etc.) across channels.This bot features dynamic inline filtering (Quality, Language, S/E), multi-image support using TMDB, and URL monetization via a link shortener service.✨ Key FeaturesFully Customizable: All messages, captions, and templates are defined in info.py.Dynamic Filtering: Automatically parses filenames and offers inline buttons to filter results by:Quality (2160p, 1080p, 720p, WEB-DL, etc.)Language (Hindi, English, Dual Audio, etc.)Season and Episode (S01E01)Rich Media Results: Fetches and sends multiple posters/screenshots using the TMDB API to accompany search results.Link Monetization: Integrates with an external link shortener API to wrap file links, providing monetization opportunities.Secure Infrastructure: Configurable Admin ID, separate channels for Logs and Files, and dedicated Request Group.🚀 Deployment and Setup1. RequirementsPython 3.8+A Telegram API ID and HASH.A Telegram Bot Token.A Database connection string (e.g., MongoDB).A TMDB API Key (Optional, for posters).A Link Shortener API Key (Optional, for monetization).2. ConfigurationClone the repository and modify the required files:git clone [https://github.com/YourUsername/Advanced-Auto-Filter-Bot.git](https://github.com/YourUsername/Advanced-Auto-Filter-Bot.git)
cd Advanced-Auto-Filter-Bot
Edit the info.py file to set all your keys, IDs, and custom messages:# info.py
API_ID = 1234567 
API_HASH = "YOUR_API_HASH"
BOT_TOKEN = "YOUR_BOT_TOKEN"
ADMIN_ID = 1234567890 
DATABASE_URL = "YOUR_DATABASE_CONNECTION_STRING_HERE"
LOG_CHANNEL = -100xxxxxxxxxx 
FILES_CHANNEL = -100xxxxxxxxxx
# ... and other TMDB/Link Shortener configurations
3. Install Dependencies and RunInstall the required Python packages:pip install -r requirements.txt
Start the bot:python3 main.py
4. For Heroku DeploymentIf deploying to Heroku or similar platforms, ensure you set the necessary environment variables and use the provided Procfile.⚙️ Project Structure├── .
├── main.py
├── info.py
├── requirements.txt
├── Procfile
├── logging.conf
└── plugins/
    ├── __init__.py
    ├── autofilter.py
    └── link_shortener.py
Credit: Base code architecture derived from @VJ_Bots template.
