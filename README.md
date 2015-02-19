# issue-test
Create stub issues as ease as possible.

## Using web form
* HTTP pettition **must** be a POST
* Required params **can** be form params or url encoded params (such GET)

### Required params
* utf8:✓
* authenticity_token:foo token
* issue[title]: foo issue


## Using ghi
https://github.com/stephencelis/ghi

 $ ./ghi config ghi-repo varhub/issue-test
 $ ./ghi config --auth varhub
 $ fail... (No GitHub repo.)
