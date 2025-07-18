# Challenge Name: Cookie Monster Secret Recipe

**Category:** Web Explotation

**Difficulty:** Easy

**Date Started:** July 18, 2025

**Date Completed:** July 18, 2025

**Writeup Published:** July 18, 2025

**Directions:** 
Cookie Monster has hidden his top-secret cookie recipe somewhere on his website. As an aspiring cookie detective, your mission is to uncover this delectable secret. Can you outsmart Cookie Monster and find the hidden recipe?
You can access the Cookie Monster [here](http://verbal-sleep.picoctf.net:50164/), and good luck

 # Initial Observation: 
It has a nice theme: Cookie Monster; Something I used to watch a lot when I was younger

The challenge hints toward ["cookies"](https://www.kaspersky.com/resource-center/definitions/cookies?srsltid=AfmBOopGCH3AOcnD9E1YDg7KKTwu35q1KYrzMFzlK_SMZyH66K1CHBKu) 

I have to use the ["web inspector"](https://wpengine.com/resources/how-to-inspect-a-website/) to find the cookie; most likely within the site's cookies

 # Strategy (During the Challenge):
1. Open the website
2. Use "web inspector" to look around the site
3. Find where the site's cookies are stored
4. Hopefully, find the flag

 # Tools Used:

 ChatGPT: To research what cookies are and how to access them through the "web inspector
 
 [Base64 Decoder/Encoder](https://www.base64decode.org/) 
                    

# Solution (What I Did During the Challenge): 
My strategy was mostly correct:
1. Open the website
2. Open the "web inspector"
3. Find "applications" tab: (It's at the top)
4. Find the "cookies" tab
5. Type in something random into the username and password.
6. You will see another "cookies" tab open
7. Inside it, you will see a ["Base64 code"](https://wpengine.com/resources/how-to-inspect-a-website/)
8. Use the decoder, and you will receive the flag
<img width="1616" height="1025" alt="Screenshot 2025-07-18 223737" src="https://github.com/user-attachments/assets/f8c5515e-0519-46a0-9f8a-72f60ed5eff3" />


# Flag: 

After you find the "cookies" tab, enter a random username and password

Open the second "cookies" page

Use a Base64 decoder to decode the code

You will receive your flag. 

# Mistakes I made:

I did not research how to use the web inspector at first.

I forgot the characteristics of a Base64 code.

 
   
# What I Learned:

I learned the hallmark of a "Base64 code"

I learned how to fully use a "web inspector" 

I learned about cookies ( My definition: They store data) 

I learned that I need to research concepts if I don't know them, since that's the only way to solve these challenges.

