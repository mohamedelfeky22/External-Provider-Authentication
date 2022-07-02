
 Project's title: External Provider Authentication.
 Project's description:Example for making a sign up with other providers (Google-Facebook-Microsoft).
 To install and run the project:
 • Make sure that you use the following version of dotnet-hosting-5.0.0
 • Clone the repository
 • For google authentication go to https://console.cloud.google.com/apis and register new app and get client Id && client secret
 • For facebook authentication go to https://developers.facebook.com/apps/ and register new app and get AppId &&AppSecret
 • For microsoft authentication go to https://go.microsoft.com/fwlink/?link... and register new app and get client Id && client secret
 •Go to authentication section in appsetting.json and change the following :
    "Google": {
      "ClientId": "AddYourOwn",
      "ClientSecret": "AddYourOwn"
    },
    "Facebook": {
      "AppId": "AddYourOwn",
      "AppSecret": "AddYourOwn"
    },
    "Microsoft": {
      "ClientId": "AddYourOwn",
      "ClientSecret": "AddYourOwn"
    }
