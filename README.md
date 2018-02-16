# ModernCryptoLib
Python cryptography library
```
[-] N = Rsa modulus
[-] E = Rsa exponent
[-] C = Cipher text

[*] Import MAP
RSA->Attacks->utillities-->egcd(a,b)
RSA->Attacks->utillities-->modinv(a,m)
RSA->Attacks->utillities-->mulinv(a,b)
RSA->Attacks->utillities-->powinv(x,n)
RSA->Attacks->utillities-->is_perfect_square(n)
RSA->Attacks->utillities-->isqrt(n)
RSA->Attacks->utillities-->rational_to_contfrac (x, y)
RSA->Attacks->utillities-->convergents_from_contfrac(frac)    
RSA->Attacks->utillities-->contfrac_to_rational (frac)
RSA->Attacks->Hasted-->hasted(n1,n2,n3,chipher_text_1,chipher_text_2,chipher_text_3)
RSA->Attacks->Wiener-->wiener(n,e)
RSA->Attacks->Fermat-->fermat(n,limit)
RSA->Attacks->side_channel-->Gen_sideChannel_payload(n,c,e)
RSA->Attacks->side_channel-->Reverse_sideChannel_payload(payload)
RSA->Attacks->Common_modulus-->common_modulus(chipher_text_1, chipher_text_2, e1, e2, n)
RSA->convert-->bytes_to_number(data_bytes)
RSA->convert-->base64_to_number(b64_string)
RSA->convert-->number_to_text(number)
RSA->fileParser(path):
RSA->export-->public_key(n,e)
RSA->export-->private_key(n,e,d,p,q)
```

