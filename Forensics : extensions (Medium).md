In this space, I will be narrating my full experience with the extensions challenge.

Here's what we're dealing with this time :

<img width="1439" height="262" alt="image" src="https://github.com/user-attachments/assets/5e69f4b6-1f47-424b-9f5b-dc1a58d4e43e" />
Quite a small description (which scares me more than it makes me feel relieved about the challenge. Never underestimate appearances is what I've learned).

<img width="1351" height="327" alt="image" src="https://github.com/user-attachments/assets/f1eda891-f194-427c-b1ad-b1ce9b04b30e" />
So, immediately what I notice is that this isn't how the file's gonna open. It needs to be converted or opened using some sort of wacky webshell command.
But wait... what is that?

<img width="55" height="34" alt="image" src="https://github.com/user-attachments/assets/e1bbb51f-3e28-49b8-b82c-35cd5328ba1e" />

It says PNG. Of course, I know that PNGs are basically a file type for images. So, now we know for certain that this file has something do with PNGs. So... what if I converted it to one?
But I have no idea how to do it, so let's get this outlier into our handy webshell first.

<img width="1845" height="265" alt="image" src="https://github.com/user-attachments/assets/497c38c3-e2b1-487f-b794-05cb4ca12b34" />
After also making it into an executable just in case, I tried to figure out if there's a tool for changing file types. And that's when another thought came into my mind. It says flag.txt, right? The actual file says flag ONLY outside of our webshell as you can see :

<img width="94" height="28" alt="image" src="https://github.com/user-attachments/assets/b55c2799-a655-42a3-b044-bb07934971be" />

Then, what if we only renamed .txt to .png? Wouldn't a renaming automatically change the file type for us too? But... oh... I don't know how to rename files either.

<img width="929" height="331" alt="image" src="https://github.com/user-attachments/assets/95b8a2fe-04ad-48fb-b279-9eb0fc951ce5" />

Alright, thank you kind sirs! Now, let's test the theory, and...

<img width="478" height="17" alt="image" src="https://github.com/user-attachments/assets/79f023b9-21e1-43b8-b4cf-e4797333efdd" />
<img width="1505" height="535" alt="image" src="https://github.com/user-attachments/assets/0a6d5e38-6f55-4e5e-864a-9947ef722322" />
Nice! (I used a less conventional method here. I converted the binary image into this wall of base64 text using base64 flag.png, and then used a base64 to image converter to see our beautiful flag in the flesh. There are a hundred other methods to view the flag in this challenge, though!)
