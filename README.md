## JWT/OAuth2 - SpringBoot Security

### JWT token implementation


### Generate Private Key:
```$ openssl genrsa -out jwt.pem 2048```

```$ openssl rsa -in jwt.pem```



### Generate Public Key:
```$ openssl rsa -in jwt.pem -pubout ```


#
* Curtsy Web tutorial:
    https://www.tutorialspoint.com/spring_boot/spring_boot_oauth2_with_jwt.htm 
