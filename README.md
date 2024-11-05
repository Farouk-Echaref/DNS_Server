# DNS_Server

[![progress-banner](https://backend.codecrafters.io/progress/dns-server/c03ac0ca-4e77-4b1a-99ec-d00c77ea701d)](https://app.codecrafters.io/users/codecrafters-bot?r=2qF)

This is a starting point for Python solutions to the
["Build Your Own DNS server" Challenge](https://app.codecrafters.io/courses/dns-server/overview).

In this challenge, you'll build a DNS server that's capable of parsing and
creating DNS packets, responding to DNS queries, handling various record types
and doing recursive resolve. Along the way we'll learn about the DNS protocol,
DNS packet format, root servers, authoritative servers, forwarding servers,
various record types (A, AAAA, CNAME, etc) and more.

**Note**: If you're viewing this repo on GitHub, head over to
[codecrafters.io](https://codecrafters.io) to try the challenge.

# Passing the first stage

The entry point for your `your_program.sh` implementation is in `app/main.py`.
Study and uncomment the relevant code, and push your changes to pass the first
stage:

```sh
git commit -am "pass 1st stage" # any msg
git push origin master
```

Time to move on to the next stage!

# Stage 2 & beyond

Note: This section is for stages 2 and beyond.

1. Ensure you have `python (3.11)` installed locally
1. Run `./your_program.sh` to run your program, which is implemented in
   `app/main.py`.
1. Commit your changes and run `git push origin master` to submit your solution
   to CodeCrafters. Test output will be streamed to your terminal.


## Resources:

* https://opensource.com/article/17/4/build-your-own-name-server
* https://www.youtube.com/playlist?list=PLBOh8f9FoHHhvO5e5HF_6mYvtZegobYX2
* https://datatracker.ietf.org/doc/html/rfc1035#section-3.2.2