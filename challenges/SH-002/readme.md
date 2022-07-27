[![logo](https://securehats2022cth.blob.core.windows.net/pictures/sh-banners.png?sv=2021-06-08&ss=bfqt&srt=sco&sp=rlt&se=2025-07-18T03:43:38Z&st=2022-07-17T19:43:38Z&spr=https,http&sig=uZOVgsqNJsd%2FgnWbQ2sXECumbHEMnUJ8tyBGDitCmzo%3D)](https://securehats2022cth.blob.core.windows.net/pictures/sh-banners.png?sv=2021-06-08&ss=bfqt&srt=sco&sp=rlt&se=2025-07-18T03:43:38Z&st=2022-07-17T19:43:38Z&spr=https,http&sig=uZOVgsqNJsd%2FgnWbQ2sXECumbHEMnUJ8tyBGDitCmzo%3D)

# Capture The Hat SH-002

In this challenge the user will get `read` access to a resource group in Microsoft Azure and needs to retrieve several _flags_ that are hidden within the provided resources. After provisioning the environment, the credentials of a unqiue account are shown together with a storage account. <br />

![image](https://user-images.githubusercontent.com/40334679/181022219-dbf75935-bb16-4ad9-843d-4f14a67b67e9.png)

Although the user only has `read` permissions to the resource group and `Storage Account Contributor` permissions to the _Storage Account_, this should be enough to exploit the FunctionApp permissions.

### architecture

![image](https://user-images.githubusercontent.com/40334679/181019379-4c2392cd-012b-4144-9179-017ba7398366.png)
> architecture created with bicep visualizer

## Azure Function Apps

> Note: The hidden flags in this challenge are required will give access to the next challege which can be found on the homepage of this project.

### Post your answers

After completion of the challenge you need to post your answers in this Microsoft Forms [link](https://forms.office.com/r/ELVPnKEGKH).<br />
This will help me keeping track of the usage of the challenges and create a scoreboard for all participants.

Good luck!

## Writeups

I love to contribute and learn from others, and writeups are an awesome way of learning new things or gain insights in different approaches.<br />
So feel free to contribute and create a writeup of your solution.

> NOTE: Creating writeups are great! But please don't spoil the learning path of others by providing the answers. 

## Contributions

If you have an idea for a new challenge, please let me know by opening an issue. [link](https://github.com/SecureHats/secure-hacks/issues/new)

## Support

Running into any issues or need some help on the challenge?<br />Send a tweet to [@dijkmanrogier](https://twitter.com/dijkmanrogier) using the tag #SecureHats

<br />
If you like this project feel free to support me by buying a coffee.<br /><br />
<a href="https://www.buymeacoffee.com/DijkmanRogier" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
