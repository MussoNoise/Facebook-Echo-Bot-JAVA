#Facebook Messenger Bot Deployed with Google App Engine

Simple Facebook Messenger bot that echoes whatever message it receives.

It was built following Facebook's guide https://developers.facebook.com/docs/messenger-platform, but i used JAVA 7 
instead of Node.js (lenguage of facebook's guide).

Remember to set eclipse compile level to 1.7. (1.8 is not yet support by GAE)

#1 Import project:
- Donwload the project
- Clik to Import--->Existing project into workspace
- right clik on the imported project:
    properties-->Google--->App engine--->Set a project ID (the same of your google app engine project)
-Insert your page token in the right place

#2 Facebook app side:
- Create your app (https://developers.facebook.com/)
- Enable messenger in your app
- Set your webhook:  
   - CallBack URL https://1-dot%yourGAEid.appspot.com/facebookbot
   -verfy test: verify
  -Messenger action: message_reads, messages, messaging_postbacks


