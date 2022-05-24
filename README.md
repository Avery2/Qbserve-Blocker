# QbserveBlocker

I was unable to find an app that blocks apps based on time-usage. This is an attempt to see what I can do on my own.

I will query a local Qbserve database ~~(updated hourly)~~ (if you use `UserDatabase.sqlite` instead of `Backup.sqlite` it is as often as Qbserve updates) to check the app useage. I still don't know how I will block apps. Ideally I use some other implementation like Self-Control but I might also use the `psutil` library.

<div align="center">
  
  <img width="916" alt="Screen Shot 2022-05-23 at 10 55 35 PM" src="https://user-images.githubusercontent.com/53503018/169959154-23709c2a-d70f-4f19-9c7d-14d18379e753.png">
  <p><em>Backup feature from Qbserve that I am using.</em></p>

</div>
