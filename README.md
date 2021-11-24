# Authentication-Template (website name: Whisper)

This is whisper app, where users can log in using local, google or facebook login to 
  view other people's secrets without knowing who they actually are..
  
In the user's cookies, only local login's get their passwords hashed and saved in mongoDB using 
  passport-local-mongoose module, while the rest dont get their info saved except for their accound id, 
  which is used to only to keep them logged in before they log out or the session expires.
  
To close and run this app, you must:
- run "npm init"
- add .env file for your own variables:
    oauth client_id and client_secret, 
    facebook_client_id, facebook_client_secret, 
    mongoDB url, and hashing secret
