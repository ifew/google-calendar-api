# Sample PHP integrate Google Calendar API for create and List Event

## Prerequisites
- PHP 5.4 or greater with the command-line interface (CLI) and JSON extension installed
- The Composer dependency management tool
- A Google Cloud Platform project with the API enabled.

## 1. Create Project in Google Cloud Platform
1. Create Google Project at [Google API Console](https://console.developers.google.com/)
2. Enable API & Service as "Google Calendar API"
3. Create Credentials as "OAuth Client ID" and Application Type as "TV and Limited Input"
4. Download JSON file as "credentials.json" in this root folder

## 2. Install Dependency Code
1. Pull this repository
2. Run ```composer require google/apiclient:^2.0```

## Run code for list event in your calendar
1. Run ```php list.php```
2. If you run first time, you need consent to use App on web browser. you will see this message like this
```
Open the following link in your browser:
https://accounts.google.com/o/oauth2/auth?response_type=code&access_type=offline&client_id=xxx.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&state&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcalendar&prompt=select_account%20consent
```
2.1. open that link and consent, after that you will get Verification Code and please copy/paste to your console like this
```
Enter verification code: 4/1AX4XfWxxxxxxxxxxxxxxxxUA-xxxxxxxxxxxxxxxxxxxxxn8XfIQ
```

## Run create event
1. Run ```php create.php```
2. If you run first time, you need consent to use App on web browser. you will see this message like this
```
Open the following link in your browser:
https://accounts.google.com/o/oauth2/auth?response_type=code&access_type=offline&client_id=xxx.apps.googleusercontent.com&redirect_uri=urn%3Aietf%3Awg%3Aoauth%3A2.0%3Aoob&state&scope=https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcalendar&prompt=select_account%20consent
```
2.1. open that link and consent, after that you will get Verification Code and please copy/paste to your console like this
```
Enter verification code: 4/1AX4XfWxxxxxxxxxxxxxxxxUA-xxxxxxxxxxxxxxxxxxxxxn8XfIQ
```