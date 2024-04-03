# Phishing Process

EDIT:
As of 04/03/2024 15:35, it appears BlueVPS has responded to my abuse complaint. They have disabled the server.

The phishing attack starts by sending the victim an invite to the discord server. The invite link I received was 'discord.com/invite/sbunity'.
![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/003ebea9-b905-4a7e-a16c-e4e7e57f2fda)

Upon entering the server, there is a prompt for 'verification'. 

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/6c30e1ec-8e06-4775-85f8-2cd2173dcac5)

Clicking the button for the 'verification' prompts the victim to enter their Minecraft username along with the email associated with it.

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/97fd40b4-dde3-40a9-b732-26118613b0dc)

For this report, I created a Microsoft account with the email 'phishing:dot:oversold195:at:passinbox:dot:com'. In the logs below, you can see that it was created at the time of writing the report, and solely for demonstrating the account takeover by the phishing campaign.
![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/49ce940d-1bc4-4c90-be39-91020322dd6b)

Now we will submit the new Microsoft account's email into the 'verification' prompt.

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/41a79533-06c1-4954-95b8-44d2e3f1e85b)

Immediately, the victim will get another prompt from the discord server.

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/e9beff2a-a01d-4285-a462-13d08dc01c3c)

The victim will click 'send code'.

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/f901e855-5241-460e-ad87-a8d72949cb21)

The victim will now click 'confirm'.

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/ee77e630-ff2d-47d2-99a4-c09bdd1d19e1)

The victim will now enter the code from this email into the prompt.

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/f8369a17-3a60-4934-9e8b-ecf759b01d0c)

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/571e4227-4296-4083-8fa0-d65c2d6af5aa)

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/bee8264f-94e5-4133-94fc-2c6912b58913)

As you can see, the attackers took over the account immediately after submitting the verification code.
![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/275e7b20-169d-401d-8d93-8cc031a5cae6)

# Information regarding attackers (Discord)

The discord server ID is 1161810785190821970.

The verification bot's username is Hypixel Verification#4837.
![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/04de9117-749d-4a7a-a570-7a4cafb7bf48)

braceanimated81376 and healkey49434_31685 are admins in the discord server 1161810785190821970.

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/42d22c91-fe98-4ba2-b733-df735bc9c792)
![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/62c20187-7ddd-4255-a14c-4870b9d0f41f)

elexmr and tyla420 are moderators in 1161810785190821970.

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/385a6f08-f9cf-4d8d-8bbf-2ad28227e622)
![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/6210d71d-2fd1-4059-a2a8-63804467e7c1)

Generally, most users that appear part of the server seem to have an account created in or after October 2023.
There is one user, joe2130 that has an account creation date of Jan 19, 2022.

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/6178946e-d8a0-4090-a433-9abbec524358)

# Information regarding attackers (Domain)

The attackers add an email to the victim's Microsoft account as part of the account takeover. The email domain consistently is **oldward.fun**.

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/e90ef6e3-b4ed-4041-83ea-29ead28ea159)

The [whois data for the domain oldward.fun](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/blob/main/oldward.fun%20whois.txt) suggests that the registrant is located in Paris, France. It is unclear if the registrant provided accurate WHOIS information. It appears that the domain is registered through MONOVM.COM. The nameservers use Cloudflare.

Entering oldward.fun into urlscan.io (https://urlscan.io/domain/oldward.fun) indicates that two other domains, which appear to be phishing related, are connected to it. These domains are **skyauth.fun** and **node.pixelcst.de**.

https://urlscan.io/result/032746f3-4477-4e19-8ee3-a71c220fbdfc/
https://urlscan.io/result/c226b21a-9030-4347-b1de-7be513709932/

WHOIS info for **skyauth.fun** indicates an email address for **janeretta1@gmail.com**. Interestingly, the contact name for the domain is **Ward IsCool**. Clearly the owner of skyauth.fun is the owner of oldward.fun. Skyauth.fun was also registered through MONOVM.COM.

# Information regarding attackers (IP Address)

The following IP addresses were noted to be used by the attackers:
* 2a10:1fc0:1::d5da:b027
* 77.72.85.66

These IP addresses belong to BlueVPS (AS62005).

IP Information:

![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/9d10b282-82ae-4098-8153-dc56c30a532d)
![image](https://github.com/laserlamp109/Skyblock-Unity-Discord-Phishing/assets/165952486/f0cb152d-17bb-4cac-b7c5-fd0d1a8f340b)

The IP address **77.72.85.66** appears to run a mail server. 
https://web.archive.org/web/20240403205520/https://www.shodan.io/host/77.72.85.66

# Other

The emails I received from Microsoft along with the WHOIS data for skyauth.fun and oldward.fun will be added into this repository.
