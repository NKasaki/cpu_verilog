# This should be the title

## This should be one of the subtitle...

This is the test doc for starting a repo locally.
But since I haven't use git for so freaking long, I forget that you cannot just "start a repo totally locally". You have to interact with the Github whereby the front-end way...

upd: "rm" is not used for renaming the file!

upd from Aug.14:
You can log on to Github via ssh or HTTPS.
In each HTTPS request, you have to type the username and the password, which is tedious. So git provide you with a local "password manager" to manage the password for you.
The drawback for this is that it seems that you can only have one account at one time on one computer. If you want to log in as another user via HTTPS, you will have to delete the credentials and type in your password one more time.

But, you can also use the ssh way, as all I tried to set up this morning. The ssh way is also a kind of authentication, but more tedious when set up. You generate a keypair locally, and then save the public key in Github's server. Then you need to use "ssh-add" to config the private key as your key.
What is important is that you need pay attention to the link when you add a remote or cloning. The difference between ssh and HTTPS is different links when push/pull/clone.

I'm thinking of a feasble way support two account at the same time. Can I just use one account via ssh and another via the traditional username-password-HTTPS way?

