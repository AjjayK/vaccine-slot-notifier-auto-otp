# vaccine-slot-notifier-auto-otp
 A Discord bot that notifies live Covid vaccine slot availablilty for 18-44 age group. Retrives OTP automatically from mobile using REST services.
 
 Sincere thanks to [@pallupz](https://github.com/pallupz) for his code which enabled to retrieve live data from CoWIN API and [@bombardier-gif](https://github.com/bombardier-gif) for automatic OTP retrieving codes.
 
 Link to the repos 
 [covid-vaccine-booking-manual-otp](https://github.com/pallupz/covid-vaccine-booking)
 
 [covid-vaccine-booking-auto-otp](https://github.com/bombardier-gif/covid-vaccine-booking)
 
 ## Steps to get vaccine notification using discord bot
 1. Create a discord bot. If you don't know this [YouTube video](https://www.youtube.com/watch?v=SPTfmiYiuok) will help you
 2. Download the repo and unzip
 3. Update environment variables in `.env`. Use [this file](/state_and_district_data.csv) to get `district id`
 4. set up OTP retriver. Use the procedure mentioned in this Repo [Steps-to-retrieve-text-REST](https://github.com/bombardier-gif/covid-vaccine-booking#setup-guide-for-android)
 5. Run the Python program `bot_soul.py`
 6. Send `Start` in your discord channel to run the script
 7. When slot appears, bot will send you the details
 8. By default, code is set to retrieve OTP automatically. However, you can switch between manual OTP entry or automatic using bot commands
 
 ## Bot-Commands
 - **Start** - To run the bot and begin data scraping
 - **Slots** - To know latest vaccine slot availability status
 - **OTP manual** - To switch to manual mode for OTP entry
 - **OTP auto** - To switch to automatic OTP entry 
 
 ### Post Script
 This is the first application I have ever created. xD. Help me improve coding skils
 
 If anyone wishes to improve this bot, let us discuss. My discord user name *SaarapPaambu#0534*
