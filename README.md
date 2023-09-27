# useful Commands
Useful command line one liners and snippets

# OpenSSL
`echo "" | openssl s_client -connect www.example.com:443 -servername "www.example.com" 2>&1`
Get details on https connection provided by server example.com.

`openssl genrsa -out mykey.pem 2048`
Create a 2048 bit rsa private key.

`openssl req -text -in myrequest.csr -noout -verify`
Verify your CSR is mistake free before submission.
