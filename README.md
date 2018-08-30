# Metronome for LIFX 
Pulses LIFX lights to the beat of songs being currently played on Spotify with two different colors that are varied with every song
# What You Need
- Spotify account
- LIFX light(s)
- Spotify client id
- Spotify client secret
- LIFX access token

# Set Up
1. Get LIFX access token
- Visit https://cloud.lifx.com/sign_in
![alt text](https://discourse-cdn-sjc2.com/standard17/uploads/lifx/optimized/1X/f27580c296f07b32152239c037bf9c964f05444a_1_690x394.gif) 

2. Get Spotify client id and client secret
- Visit https://developer.spotify.com/dashboard/

- Create an app 

![alt text](https://github.com/codycoogan/metronomeforlifx/blob/master/images/spotclient.gif)

- Here are your credentials
![alt text](https://github.com/codycoogan/metronomeforlifx/blob/master/images/spotblurred_g.jpg)

- Press edit settings, then once in the Spotify project settings add https://www.google.ca/ as the redirect URI (PIC?)


3. Fill out metronomeconfig.txt 
- Open metronomeconfig.txt
![alt text](https://github.com/codycoogan/metronomeforlifx/blob/master/images/configsc.png)
- Paste your LIFX token and your Spotify client id and secret in the respective spots in the file
- Save the file


4. Install requirements.txt
- After downloading requirements.txt open terminal or command prompt
- Go to the directory where this project is saved in
- Run: pip install -r requirements.txt    in the command line


5. Sign in to Spotify in Metronome for Lifx app
- Run metronomeforlifx.py in terminal/command prompt
- Sign in to Spotify account when prompted in browser
- If sign in was successfull, copy the URL of the page that you were redirected to after signing in (google.ca/...). If sign in is unsuccessfull re-run the program and attempt to sign in again
- Paste this URL into prompt in command line
GIF HERE??

# Troubleshooting
- Make sure LIFX lights are on and online
- Make sure metronomeconfig.txt is filled out with valid information
- Make sure metronomeconfig.txt, requirements.txt, and metronomeforlifx.py are all in the same directory on your computer
- Make sure a valid Spotify song is playing on the same account you signed in to



TEST NEW RANDOM AND SUBMIT NEW FILEG

