# flags
some websites that hide flags for my club's CTF challenge... if you are currently doing this challenge, nice job finding this

I will probably need some kind of engine to serve all of these pages separatly from one machine... maybe NginX :/
# inspect.html 

 This is the first website I'm working on, it is pretty simple, where the goal is to get someone to inspect the 
elements, and see that the "password" that they need is stored in plaintext there, which will redirect to 
a page with the flag on it. this is a pretty simple one, just to start things out.

#key.txt

This is an encripted key, encrypted with the command : `openssl aes-256-cbc -a -salt -in key.txt -out key.txt.enc`
you can decript it with the opposite `openssl aes-256-cbc -d -a -in key.txt.enc -out **anyfilename**`

the password, which will be supplied with the challenge  is cdccrules!

# planned : 

Here are some of the other challenges I have planned 
----------------------------------------------------

flag hidden in the website with white font ( super easy) 

encrypted phrase, and key to decrypt it 

some other password that must be cracked somehow ( ceasars shift )

password that is easily crackable ( like something from the first 20 lines of rockyou.txt ) 

website with hidden page ( unlisted but can be found by spidering the page) 

site with a database, that is XSS vulnerable




