# Understanding_CDN
![image](https://user-images.githubusercontent.com/114154205/208682282-e939c6fb-03f4-4380-ad7d-4b04d79452ac.png)


##  If the file isn't in the edge server's cache, it will then request it from the origin server

## 1.There's some delay in this process(First time request or fresh request), but it does happen immediately(after first request).
 
## 2. Then our user receives the file(first user). Since the file wasn't cashed, the initial request took longer, but she did cause the file to be cached by the CDN now for everyone else(after first user).

## 3. That means that when more people request that same file from their closest CDN edge servers, the file is served immediately, saving you bandwidth costs and making them happier with a faster response
