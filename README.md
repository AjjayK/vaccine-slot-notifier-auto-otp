# vaccine-slot-notifier-manual-otp
 A Discord bot that notifies live Covid vaccine slot availablilty for 18-44 age group
 
 Sincere thanks to @pallupz for his code which enabled to retrieve live data from CoWIN API.
 Link to his repo [covid-vaccine-booking](https://github.com/pallupz/covid-vaccine-booking)
 
 ## Steps to get vaccine notification using discord bot
 1. Create a discord bot. If you don't know this [YouTube video](https://www.youtube.com/watch?v=SPTfmiYiuok) will help you
 2. Download the repo and unzip
 3. Update environment variables in `.env`. Use [this file](/state_and_district_data.csv) to get `district id`
 4. Run the Python program `bot_soul.py`
 5. Send `Start` in your discord channel to run the script
 6. Enter OTP received in your discord channel
 7. When slot appears, bot will send you the details
 
 ## Bot-Commands
 - **Start** - To run the script
 - **Slots** - To know latest vaccine slot availability status 
 
 ### Post Script
 This is the first application I have ever created. xD. Help me improve coding skils
 
 If anyone wishes to improve this bot, let us discuss. My discord user name *SaarapPaambu#0534*
