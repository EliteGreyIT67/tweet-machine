<h1 align=center>𝙏 𝙒 𝙀 𝙀 𝙏 - 𝙈 𝘼 𝘾 𝙃 𝙄 𝙉 𝙀
</h1>
  <p align="center">
  
  
  
<img  align="center" src="https://user-images.githubusercontent.com/72292872/195614901-91f724c7-83c6-4e37-83e2-b68687f465d4.png" alt="TM">


     Twitter OSINT Tool ,  which retrieves the deleted tweets and replies of any Twitter user (Even if Its suspended) 

   
 [![https://imgur.com/EDcF0de.png](https://imgur.com/EDcF0del.png)](https://imgur.com/EDcF0del.png)
 
 <details><summary>Purpose </summary>
 <b>we can retrieve all tweets and replies (even if the account has been suspended)</b>
 </details>
</p>

##### BUILT WITH: 

- <img src="https://img.shields.io/badge/gnu%20bash-%234EAA25.svg?&style=for-the-badge&logo=gnu%20bash&logoColor=white" />

##### TOOLS USED :

- <img src="https://img.shields.io/badge/arch%20linux-%231793D1.svg?&style=for-the-badge&logo=arch%20linux&logoColor=white" />
- <img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />
- <img src="https://img.shields.io/badge/windows%20terminal-%234D4D4D.svg?&style=for-the-badge&logo=windows%20terminal&logoColor=white" />

#### [+] INSTALLATION : 
Bash:
```
git clone https://github.com/0xcyberpj/tweet-machine.git && cd tweet-machine
chmod +x twettmachine.sh
./tweetmachine.sh -u <username> -d <directory but not important>
Eg:
Tweet-Machine@Pj >> ./tweetmachine.sh -u cyberpj1 -d /tmp
Tweet-Machine@Pj >>./tweetmachine.sh -u cyberpj1

```
Python:
```
git clone https://github.com/0xcyberpj/tweet-machine.git && cd tweet-machine
chmod +x tweetmachine.py
pip3 install requests 
./tweetmachine.py -u <username> -d <directory but not important>
Eg:
Tweet-Machine@Pj >> ./tweetmachine.py -u cyberpj1 -d /tmp
Tweet-Machine@Pj >>./tweetmachine.py -u cyberpj1

```

**[+] Total Output Files**

```
1.cyberpj1.txt  
cyberpj1.txt - Contains tweets and Replies Direct link

2.cyberpj1.txt.webarchive - Contains tweet Link with wayback 
This Link can be valid if Direct link show `not found`

3.cyberpj1.txt-timeline.txt  - This File Contains the Timeline of Every tweet!
```

### [+] Result: 

![image](https://user-images.githubusercontent.com/72292872/209679080-58f45d19-f4b6-4b30-96e6-0960400b5489.png)

![image](https://user-images.githubusercontent.com/72292872/209679111-9a8ae3d8-67bf-4517-bab8-d571318c4700.png)

![image](https://user-images.githubusercontent.com/72292872/209679349-c6cb53e9-9e12-41d4-88eb-e68cbe73d630.png)



## [+] Real Scenario : 

1. What can i Do with This result?

> - So the user  `madangowri03` Twitter account was suspended,Using This Tool We Retrieve Each and Every Tweet and Replies Made by Him!

![image](https://user-images.githubusercontent.com/72292872/151909602-60d1e4b4-b356-4713-87fb-bd67038dd7b5.png)

**Wayback Result :**

[![https://imgur.com/a58Oekm.png](https://imgur.com/a58Oekml.png)](https://imgur.com/a58Oekml.png)

**Here We Go**
```
┌──(p4ul㉿j0ker)-[/opt/Tweet-Machie]
└─$  bash tweetmachine.sh -u  madangowri03 . 


┌──(p4ul㉿j0ker)-[/opt/Tweet-Machie]
└─$ head madangowri03.txt.webarchive
https://web.archive.org/web/0/https://twitter.com/madangowri03/status/1385829419093151744
https://web.archive.org/web/0/https://twitter.com/madangowri03/status/1385829654754304000
https://web.archive.org/web/0/https://twitter.com/madangowri03/status/1385864438058676234
https://web.archive.org/web/0/https://twitter.com/madangowri03/status/1385864505385578498
https://web.archive.org/web/0/https://twitter.com/madangowri03/status/1385864553888583683
https://web.archive.org/web/0/https://twitter.com/madangowri03/status/1386013567871164416
https://web.archive.org/web/0/https://twitter.com/madangowri03/status/1386177747697868804
https://web.archive.org/web/0/https://twitter.com/madangowri03/status/1386178947692457984
```
![image](https://user-images.githubusercontent.com/72292872/151910703-bf5a6fe3-dce3-4729-82bd-2734d51afa97.png)

**We have discovered that the account of user `madangowri03` has been suspended, and we have used this tool to retrieve each and every tweet and response that he made!**

`These Links won't Expire`

Autors:

[P4UL](https://github.com/0xcyberpj)

[R4VANAN](https://github.com/r4vanan)

----
<details><summary>PS:</summary>

 <pre>Even if You dont know the Username ,you  can simple type <b>madangowri</b> it will fetch all the past and current twitter profile links</pre>
<pre>It Can Be Used in CTFs and SOCMINT </pre>
  </details>

  
<h2 align=center >Ⓣⓗⓐⓝⓚ Ⓨⓞⓤ
</h2>
