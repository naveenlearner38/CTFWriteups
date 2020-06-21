# UGGC

The Link is http://jh2i.com:50018

**Steps:**

1. On website, there is a login form with only unsername field and the message Login as admin has been disabled

2. When we try to log with the username username, the message Sorry, only admin can see the flag. is show

3. When we check cookies, we can see a cookie user with value naveen

4. naveen is just username encrypt with rot 13 algorithm

5. Then, we replace the value of the cookie by nqzva (the rot 13 of admin), refresh the page and the flag is displayed

**Flag:** flag{H4cK_aLL_7H3_C0okI3s}
