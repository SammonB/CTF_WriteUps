Difficulty: Easy
Points: 150

Description:
We have discovered what we believe is a North Torbian public website and have suspicions there is a secret internal-only site hidden there as well. Figure out how to connect to the hidden site and find the flag!

I opened the link to the site I was being directed to, which was just a simple message. I noticed that it mentioned something about suspicious digital certificates, so I used firefox to view
the certificate of the site, which revealed an alternate domain name
I couldn't access the domain just by typing it in the URL bar, and I didn't know where to go from there. After using a hint, it mentioned something about host-header injection, which gave me the idea to use burpSuite
After opening the page in the burpsuite browser, I turned on intercepting and reloaded the page.
In the intercepted packet for loading the webpage, I noticed there was a header section for "host"
I simply removed the original host that was there and replaced it with the alternate one, then after sending the packet through, I was brought to the secret page with the flag.
