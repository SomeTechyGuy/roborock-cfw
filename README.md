# This is a fork of Valetudo because I hate Code of Conducts so I removed it.

Valetudo is a cloud replacement for vacuum robots enabling local-only operation. It is not a custom firmware.<br/>
Here's a diagram illustrating the core operation principle:

[<img src="https://github.com/Hypfer/valetudo/raw/master/docs/_pages/general/img/operation_principle.png" height=450>](https://github.com/Hypfer/valetudo/raw/master/docs/_pages/general/img/operation_principle.png)

You can think of it as a (quoting a user) "brain parasite" for the vendor firmware.

This comes with pro's and con's, with the main pro being that we get to benefit from the hundreds of thousands of hours of
R&D the vendors put into their firmwares, but without the cloud and account requirements.

As such, it protects your data through not sharing it with anyone by being fully local, saves you from in-app ads, upselling, sudden subscriptions
and all the other fun enshittification tactics and playbooks.

Valetudo aims to be a generic abstraction, providing a responsive webinterface that allows control of the robot.
It can be used on phones, tablets as well as your desktop computer.

To integrate with other systems, it provides a REST-interface with inbuilt Swagger UI as documentation.
Additionally, it integrates with Home Assistant and other smarthome systems using MQTT.

Being a generic abstraction, Valetudo won't be a "feature-complete" reimplementation of the vendor apps, as that would also
mean inheriting all of their technical debt.
It does however support everything you need to have a proper, modern, cloud-free robot vacuum.

While being published under the Apache-2.0 license and clearly being FOSS, the governance and development model Valetudo operates under
is to be understood as that of "Freeware with source available". It is evidently much more than that when it comes to the freedoms provided by true FOSS,
but it is not the FOSS that only knows "community-driven" you might be used to from corporate co-option and come to expect when you read "FOSS".

For more information, check out the [newcomer guide](https://valetudo.cloud/pages/general/newcomer-guide.html),
the [getting started guide](https://valetudo.cloud/pages/general/getting-started.html) 
and also the docs in general at [https://valetudo.cloud](https://valetudo.cloud)

There, you will find a list of [supported robots](https://valetudo.cloud/pages/general/supported-robots.html).

## Screenshots

### Phone/Mobile
<img src="https://user-images.githubusercontent.com/974410/211155741-d6430660-a6b2-48ab-8ddc-2217328444de.png" width=360> <img src="https://github.com/user-attachments/assets/eaad6fe0-dd1e-4f56-b6f9-f65954aecac7" width=360>

<img src="https://user-images.githubusercontent.com/974410/211155650-7cac266c-ffeb-432d-8656-5241a5d6f227.png" width=360> <img src="https://user-images.githubusercontent.com/974410/211155656-d43ee25e-1ae6-432f-95ff-1a39d294828d.png" width=360>

### Tablet/Desktop

![image](https://github.com/user-attachments/assets/dc18723f-b15f-4500-907b-bad6d7dd1a4f)

![image](https://user-images.githubusercontent.com/974410/211155836-9199616a-efde-4238-91c4-24158ba67677.png)

![image](https://user-images.githubusercontent.com/974410/211155860-9926b126-d1fe-41b1-8c83-1af21bf8caf2.png)

![image](https://user-images.githubusercontent.com/974410/211155880-ff184776-86fe-4c2f-9556-4d556cfa12f4.png)



