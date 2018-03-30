#### Getting cURL to work with Let’s Encrypt: "unable to get local issuer certificate error"

```
sudo curl https://letsencrypt.org/certs/isrgrootx1.pem.txt -o /usr/local/share/ca-certificates/isrgrootx1.crt
sudo curl https://letsencrypt.org/certs/letsencryptauthorityx1.pem.txt -o /usr/local/share/ca-certificates/letsencryptauthorityx1.crt
sudo curl https://letsencrypt.org/certs/letsencryptauthorityx2.pem.txt -o /usr/local/share/ca-certificates/letsencryptauthorityx2.crt
sudo curl https://letsencrypt.org/certs/lets-encrypt-x1-cross-signed.pem.txt -o /usr/local/share/ca-certificates/letsencryptx1.crt
sudo curl https://letsencrypt.org/certs/lets-encrypt-x2-cross-signed.pem.txt -o /usr/local/share/ca-certificates/letsencryptx2.crt
sudo curl https://letsencrypt.org/certs/lets-encrypt-x3-cross-signed.pem.txt -o /usr/local/share/ca-certificates/letsencryptx3.crt
sudo curl https://letsencrypt.org/certs/lets-encrypt-x4-cross-signed.pem.txt -o /usr/local/share/ca-certificates/letsencryptx4.crt
sudo dpkg-reconfigure ca-certificates
```

Source: https://blog.rac.me.uk/2016/05/04/techy-getting-curl-to-work-with-lets-encrypt-unable-to-get-local-issuer-certificate-error/comment-page-1/
