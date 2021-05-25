It has already been fixed by LINE.
# LINEAtAuto
https://www.kotayan.xyz/lineat/2018/08/16/LineAt-AutoRegistration.html

# Motivation
https://www.j-cast.com/2018/08/06335646.html?p=all  
I'm not the author of this bot. I have researched independently since this incident happened.

# Overview
Follow the steps below  
1. Create LINE@ account automatically.
2. Request any thrift functions.
3. Delete LINE@ account.
<img src="https://user-images.githubusercontent.com/16555696/44211704-94535d80-a1a4-11e8-9225-65285cabe045.PNG" width=50%>
For example, you can generate a channel token to access the timeline and use the generated channel token to post to the timeline.  
Obama bot illegally used a function "makeUserAddMyselfAsContact" that can be used by official accounts.

# Requirements
- linepy for LINE@
- CMSToken
- udidHash
# How to get CMSToken and udidHash
You can use get_cms_token.py.

## iOS
You need jailbroken iOS device  
- cmsToken  
hook LEGYRequestResponseHandler, then cmstoken in header

- udidHash  
I forgot. But it is okay random strings.
## Android
idk
