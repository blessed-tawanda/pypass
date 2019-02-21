# pypass

I'm always learning how to use new Linux tools. It's fun and that's how I pass my time. Recently I decided to learn how to hack someone's email password(there was a motive behind). To do this I wanted to use hydra, it's probably the easiest tool when it comes to passwords in Linux. In order to use hydra, I needed password lists. And I did not want to download password lists online because chances are they wouldn't match somehow. This is a common case especially when there is a possibility  of having native language words in the password(such as native names)  

So how about I look for a password compiler(not sure yet what to call it). An open source program that accepts information about the target and compiles a list of possible passwords. I came across cupp. It's a great program. But the only problem for me was that it produced files with at least 3000 passwords. That's just a lot. I wanted something simpler. I decided to reinvent the wheel, come up with my own script that does the same but in a much simpler way. Something that beginners can understand and use.

Article: https://medium.com/@tsitsimunikwa97/pypass-a-beginner-level-password-compiler-4922b5a7e04f