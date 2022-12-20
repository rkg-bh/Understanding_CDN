# Understanding_CDN
![image](https://user-images.githubusercontent.com/114154205/208679738-df6acf48-f0b3-48b9-8af4-4d826afb1c95.png)

## 1.There's some delay in this process(First time request or fresh request), but it does happen immediately(after first request).
 
## Then our user receives the file(first user). Since the file wasn't cashed, the initial request took longer, but she did cause the file to be cached by the CDN now for everyone else(after first user).

## That means that when more people request that same file from their closest CDN edge servers, the file is served immediately, saving you bandwidth costs and making them happier with a faster response
