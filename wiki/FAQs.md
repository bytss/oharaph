## Table of contents

- **General**
  - [Does the app/server log VPN data?](#q-does-the-appserver-log-vpn-data)
  - [What is difference between free & paid servers?](#q-what-is-difference-between-free--paid-servers)
  - [Why some of the servers does not work, connect?](#q-why-some-of-the-servers-does-not-work-connect)
  - [Difference between F-droid & Google Play versions](#q-difference-between-f-droid--google-play-versions)

### Q. Does the app/server log VPN data?

The app doesn't log any data that's the reason why it is made open-sourced so enthusiast people can see if I'm not doing something I'm not supposed to do.

Talking about VPN servers, from what I saw OpenVPN servers do not log any data & are created & served in sessions which means after x days whole session is deleted completely. That's why you will see a notification "Refreshing VPN servers" by Gear VPN which is internally it is refetching the expired servers with the new one.

So in short, no your data is not stored & log anywhere. You are safe to browse!

### Q. What is difference between free & paid servers?

If you read the privacy policy, Gear VPN uses servers served by the OpenVPN community which means at the current time the servers are fetched from vpngate.net & vpnbook.com.

The main difference in paid server is the sorting algorithm I use to find the best servers from all of them. It includes calculation based on bandwidth, latency, session time, speed to find the best servers from all of them.

So in short, the paid server is nothing but the best free servers from all of them.

### Q. Why some of the servers does not work, connect?

Also, read this answer if you are getting "Authentication Failed" message.

If you read the privacy policy, Gear VPN uses servers served by the OpenVPN community with the ability to import a custom one through "Import configuration" button.

These servers are not verified on the app side (this is possible but would take additionally 30s for each to check if host exists). What I mean is these servers are flaky, sometimes they connect sometimes they don't. The certainty of them working is not identifiable that's why they are kept.

If anytime one of these doesn't work eg: "United States" you should always try "United States" from different IP.

### Q. Difference between F-droid & Google Play versions

There is nothing to be really honest. The thing is in Google Play version I can add Google related services which are useful for the app.

Don't confuse it with any privacy issues, the only Google services I use are **Crashlytics & Analytics** which is a crash reporting & analytics service which gives me a report of all the stacktrace of app crashes & how many users (number) are using my app. The other one I use in In-app-purchase service which is used to carry out subscriptions inside the app (since F-droid doesn't allow paid/subscription based app).

So in reality, there is no privacy issue. I cannot track or use your data in any way possible that's the reason why the app is open-sourced so you can take look to see If I'm not doing some fishy things.

Since it is difficult for me to maintain both F-droid & Google Play versions, the updates are only sent to Google Play versions. So it is better that you should migrate to use Google Play version. In the near days I might remove the app from F-droid!