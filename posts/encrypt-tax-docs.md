% sable cantus

# Encrypt Your Tax Docs BEFORE You Send Them!

It's that time. We all are doing our taxes online now. Some of us need some help and that usually ends up with digitally sending tax documents.

*Do not ever, under any circumstance, email a document that has your SSN, home address, phone number, bank information, etc. unencrypted. That is a good way to lose all of your money and even your identity.*

I use two free services to send my encrypted documents out: AESCrypt and Dropbox.

### Step 1: Install AESCrypt

Get AESCrypt installed on your computer. Go [here](https://www.aescrypt.com) and install for your platform.

### Step 2: Zip up all of those files

You want to send one encrypted blob of data. Put all of your files into a single folder and zip that up. On the Mac, select the file and go to File >> Compress “Sensitive Docs”.

### Step 3: Encrypt

Follow the directions for your platform to encrypt your zip file. On the Mac, drag the file onto the dock icon and enter a strong password when prompted.

I suggest using a secure password generator like the one over at [GRC.com](https://www.grc.com/passwords.htm). You can also use Lastpass or whatever you use (even the commandline) to manage your passwords. Make a note of that password though. You can keep a copy of the password in TextEdit or NVAlt – the documents are already on your computer.

Steve Gibson recommended, on the [Security Now Podcast](https://www.grc.com/sn/sn-599.htm), to use a long string of numbers that can easily be read over the phone such as, “32 67 89 14 75 12 99”, etc.

### Step 4: Drop it in Dropbox*
Using DropBox makes sharing files easy. Put the encrypted file into your dropbox folder and click Share Link.

You can send them the file directly through the DropBox website or get the link and send it separately.

### Step 5: Send the Password via a Separate Method
If you send an email with a link to your encrypted document, it doesn’t make sense to put the password into that email. Additionally, you might not want to send the password from your account to that same account. Try to send the password over iMessage, Signal, or another instant messenger, or to a secondary email address the person has.

### Step 6: The Takedown
Once the recipient has confirmed that they have the documents and have decrypted them on their own machine you will remove the encrypted documents from DropBox. Sure they are safe, but there is no reason to keep that online.

*Sable*

<hr />

*You can use any temporary online storage solution you have access to in order to send the file, but sending via email attachment will ensure that your encrypted file is available permanently for offline attacks*

*Use openssl from the cli: <code>openssl rand -base64 12</code>
