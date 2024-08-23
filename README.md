# Nice Catch!

## robots.txt

imagine a platform where users can create a public profile which is accessible at root route, i.e if website is `example.com` then the profile should be accessible at `example.com/username` , a vulnerability you can look here could be to register an username `robots.txt`.
[read more](https://hackerone.com/reports/275)

## race condition

before a request is completed, if we make another asynchronous call to the api, it might perform the same task twice, like sending rewards twice XD. [read more](https://hackerone.com/reports/165570)
