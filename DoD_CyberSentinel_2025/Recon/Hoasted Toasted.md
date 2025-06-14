Difficulty: Easy
Points: 150

Description:
We have discovered what we believe is a North Torbian public website and have suspicions there is a secret internal-only site hidden there as well. Figure out how to connect to the hidden site and find the flag!

I opened the link to the site I was being directed to, which was just a simple message. I noticed that it mentioned something about suspicious digital certificates, so I used firefox to view
the certificate of the site, which revealed an alternate domain name
I couldn't access the domain just by typing it in the URL bar, and I didn't know where to go from there. After using a hint, it mentioned something about host-header injection, which gave me the idea to use burpSuite
I opened the page in burpSuite, turned intercepting on, reloaded the page, and in the host header section, changed it to the alternate domain, which brought me to the secret site with the flag.
