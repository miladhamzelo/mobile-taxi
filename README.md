# mobile-taxi

Building the source code.

Clone the repository
1. git clone https://github.com/victormwenda/mobile-taxi.git

Open the created directory
2. cd mobile-taxi

Pull all the submmodules for the project
3. git submodule update --init --recursive

#Building the app code
  1. Driver
      cd mobile/driver
      gradle clean build assembleDebug
      
  2. Rider
      cd mobile/rider
      gradle clean build assembleDebug
  
#Publishing the website
1. cd web
2. Push the code using FTP to your server
3. Install your website (Provide the weburl, FCM API KEY, Google Maps API KEY, Database Server details)
4. Delete the isntall directory on your server.
