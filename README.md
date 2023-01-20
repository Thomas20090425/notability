# notability
Notability stability Issue Sharing

# Literally how does this crash the app?
![8E93470F-F826-4BB4-B469-6593AEA28CA6](https://user-images.githubusercontent.com/68798885/213586477-41063611-4ce9-4c4f-861f-6dc4aff366b2.png)

As we could see over here, here is a demo of a iPad Pro 5 (12.9 inch) STUGGLING to run the 8GB Crashing pachaging.

Because I cannot put more garbage data in here, because if I do the app will keeps crashing and become unusable! Thats why I put the 8GB as an experimental pachage.

But how does this work? As you can see the 8 dark blocks above, it that is the package data I am talking about, bu why is it? each of those blocks is arond 15MB, The smallest file contains 2 black blocks of garbage data, which is around 30MB it is already enough to crash an iPad 6. iPad 7 or 8 can be a bit trickey since it had 3gb of ram but ipad 6 had 2gb, usually apple likes to leave arounf 20% of ram space to the users, while others are reserved for the system to run, normal app have access to around 15% of the remaining ram, apps runing in jit would have around 25% of the remaining ram, which notability is a normal app thats not running in JIT environment would only have 15% of the remaining storage.

Calculation: 
iPad 6: (2048x0.2x0.15=61.44)

That means the app would only be allowed to allocate 61.44MB of ram in good cases, but notability had rendering feature and because it is made out of plain lines, it also takes up cpu and MORE ram to allow Notability to render!!! that mean it will 100% take more than 61.44MB of ram, eventually it will request more ram usage than iOS would allow, iOS will choose to kill it to keep the OS functioning, this is exactly why the first package can also crash 3gb 
devices.

# Will this destroy my notes?

No it will not, but I'm not responsible for anything if anythingd did happen to either notability or your device.

# where to download

Releases

# Why

I dont know, but notability sucks.

# Which one do I choose

Choose the one that corresponds your iPad's (or iPhone's if you do use Notability on ur phone...) ram! what where to find it?

Google: how much ram does (Device Name) have

Replace "device name" with ur device (Ovbious)

# What if I have iPad Pro 2021 or 2022 with 1 or 2 TB of storage

Yea... F*** off

# Enjoy!
