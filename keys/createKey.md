user@QN8H:~/prj/cryptographyExercises/keys$ gpg --full-generate-key
gpg (GnuPG) 2.2.19; Copyright (C) 2019 Free Software Foundation, Inc.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Please select what kind of key you want:
(1) RSA and RSA (default)
(2) DSA and Elgamal
(3) DSA (sign only)
(4) RSA (sign only)
(14) Existing key from card
Your selection? 4
RSA keys may be between 1024 and 4096 bits long.
What keysize do you want? (3072) 4096
Requested keysize is 4096 bits
Please specify how long the key should be valid.
0 = key does not expire
`<n>` = key expires in n days
`<n>`w = key expires in n weeks
`<n>`m = key expires in n months
`<n>`y = key expires in n years
Key is valid for? (0) 7
Key expires at Fri 12 Jan 2024 12:50:15 PM CST
Is this correct? (y/N) y

GnuPG needs to construct a user ID to identify your key.

Real name: JackYang
Email address: jackyanghelobo@vip.qq.com
Comment: 演示密码 1 实验
You are using the 'utf-8' character set.
You selected this USER-ID:
"JackYang (演示密码 1 实验) <jackyanghelobo@vip.qq.com>"

Change (N)ame, (C)omment, (E)mail or (O)kay/(Q)uit? O
We need to generate a lot of random bytes. It is a good idea to perform
some other action (type on the keyboard, move the mouse, utilize the
disks) during the prime generation; this gives the random number
generator a better chance to gain enough entropy.
gpg: key 00D60F2E7E881D27 marked as ultimately trusted
gpg: revocation certificate stored as '/home/user/.gnupg/openpgp-revocs.d/AE40834CA3768273441C8CE500D60F2E7E881D27.rev'
public and secret key created and signed.

Note that this key cannot be used for encryption. You may want to use
the command "--edit-key" to generate a subkey for this purpose.
pub rsa4096 2024-01-05 [SC] [expires: 2024-01-12] 吊销日期AE40834CA3768273441C8CE500D60F2E7E881D27
uid JackYang (演示密码 1 实验) <jackyanghelobo@vip.qq.com>
