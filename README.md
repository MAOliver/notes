# notes
Things I can't remember off the top of my head because I don't do them enough, but that they come up often enough and I waste time looking them up again.


# Certificate Verification

When trying to look at the cert chain from inside WSL using curl.

https://serverfault.com/questions/661978/displaying-a-remote-ssl-certificate-details-using-cli-tools

> echo | openssl s_client -showcerts -servername gnupg.org -connect gnupg.org:443 2>/dev/null | openssl x509 -inform pem -noout -text
