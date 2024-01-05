temp.txt 明文

gpg --sign 明文签名->加密->签名 得到 temp.txt.gpg
gpg --clear-sign 明文没有进行签名->加密->签名 temp.txt.asc 不能保证明文1安全性
gpg --detached 分离签名 只生成1签名文件 1人员检验
gpg --verify 校验以上文件签名是否正确
gpg --encrypt 加密数据
gpg --decrypt 解密数据

gpg --import [filename] 导入证书
gpg --gen-revoke [keyid] 吊销密钥 生成吊销证书
gpg --delete-secret-keys [keyid] 删除私钥
gpg --delete-keys [keyid] 删除公钥
