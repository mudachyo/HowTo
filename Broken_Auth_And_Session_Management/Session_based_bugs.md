# Session Based Bugs

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Old Session Does Not Expire:
* Steps:
```
      1.create your account
      2.open two browser eg.,chrome and firefox
      3.Login in one browser eg.chrome
      4.In other browser(firefox) login either change your password or reset your password
      5.After successfully changed or reset go to other browser refresh the page if you are still logged in
```      
Than this is an old session does not expire bug
      
      
### Session Hijacking(Intended Behavior)
* Steps:
```
    1.Create your account
    2.Login your account
    3.Use cookie editor extension in browser
    4.Copy all the target cookies
    5.Logout your account
    6.Paste that cookies in cookie editor extension
    7.Refresh page if you are logged in than this is a session hijacking
```  
`Impact:` If attacker get cookies of victim it will leads to account takeover.
 
 
### Password reset link token does not expire(Insecure Configurability)
* Steps:
```
      1.Create your account on target
      2.request a forget password link
      3.Don't use that link
      4.Instead logged in with your old password and change your email to other
      5.Now use that password link sents to old email and check if you are able to change your password if yes than there is the title bug.
 ```    
      
  Happy Hacking:)
  
  Resources:Google,Youtube.

# Authors
* [https://twitter.com/Virdoex_hunter](https://twitter.com/Virdoex_hunter)
