## gpg
gpg（GnuPG）2.2.19
libgcrypt 1.8.5
版权所有（C）2019 自由软件基金会，股份有限公司。
GPLv3+：GNU GPL 版本 3 或更高版本<https://gnu.org/licenses/gpl.html>
这是免费软件：你可以自由更改和重新分发它。
在法律允许的范围内，不提供任何担保。

---
> 主页：/Home/User/.gnupg
> 支持的算法：
> Pubkey公钥：RSA、ELG、DSA、ECDH、ECDSA、EDDSA
> Cipher：IDEA，3DES，CAST5，BLOWFISH，AES，AES192，AES256，TWOFISH,CAMELLIA128, CAMELLIA192, CAMELLIA256
> Hash：SHA1、RIPEMD160、SHA256、SHA384、SHA512、SHA224
> Compression：Uncompressed 未压缩、ZIP、ZLIB、BZIP2
>
> 语法：gpg[选项][文件]
> 签名、检查、加密或解密
> 默认操作取决于输入数据
---
> 命令如下：
> -s, --sign make a signature 签名
> --clear-sign make a clear text signature 明文签名
> -b, --detach-sign make a detached signature 分离签名制作分离签名
> -e, --encrypt encrypt data 加密加密数据
> -c, --symmetric encryption only with symmetric cipher 仅使用对称密码进行对称加密
> -d, --decrypt decrypt data (default) 解密解密数据（默认）
> --verify verify a signature 验证验证签名
> -k, --list-keys list keys 列表键列表键
> --list-signatures list keys and signatures 列表签名列表密钥和签名
> --check-signatures list and check key signatures 检查签名列表和检查密钥签名
> --fingerprint list keys and fingerprints 指纹列表密钥和指纹
> -K, --list-secret-keys list secret keys 列出密钥列表密钥
> --generate-key generate a new key pair 生成密钥生成新的密钥对
> --quick-generate-key quickly generate a new key pair 快速生成密钥快速生成新的密钥对
> --quick-add-uid quickly add a new user-id 快速添加 uid 快速添加新的用户 id
> --quick-revoke-uid quickly revoke a user-id 快速撤销 uid 快速撤销用户 id
> --quick-set-expire quickly set a new expiration date 快速设置过期快速设置新的过期日期
> --full-generate-key full featured key pair generation 全生成密钥全功能密钥对生成
> --generate-revocation generate a revocation certificate 生成吊销生成吊销证书
> --delete-keys remove keys from the public keyring 删除密钥从公钥环中删除密钥
> --delete-secret-keys remove keys from the secret keyring 删除密钥从密钥环中删除密钥
> --quick-sign-key quickly sign a key 快速签名密钥快速签名密钥
> --quick-lsign-key quickly sign a key locally 快速 lsign 密钥在本地快速签名密钥
> --sign-key sign a key 签名密钥签名密钥
> --lsign-key sign a key locally 密钥在本地对密钥进行签名
> --edit-key sign or edit a key 编辑密钥符号或编辑密钥
> --change-passphrase change a passphrase 更改密码短语更改密码短语
> --export export keys 导出导出导出密钥
> --send-keys export keys to a keyserver 发送密钥将密钥导出到密钥服务器
> --receive-keys import keys from a keyserver 接收密钥从密钥服务器导入密钥
> --search-keys search for keys on a keyserver 搜索关键字在关键字服务器上搜索关键字
> --refresh-keys update all keys from a keyserver 刷新密钥更新密钥服务器中的所有密钥
> --import import/merge keys 导入导入/合并键
> --card-status print the card status 卡片状态打印卡片状态
> --edit-card change data on a card 编辑卡片上的卡片更改数据
> --change-pin change a card's PIN 更改 pin 更改卡的 pin
> --update-trustdb update the trust database 更新信任数据库更新信任数据库
> --print-md print message digests 打印 md 打印消息摘要
> --server run in server mode 服务器在服务器模式下运行
> --tofu-policy VALUE set the TOFU policy for a key 豆腐策略 VALUE 为密钥设置 tofu 策略
---
> 选项：
> -a, --armor create ascii armored output 装甲制造装甲输出轴
> -r, --recipient USER-ID encrypt for USER-ID 为 USER-ID 加密的收件人 USER-ID
> -u, --local-user USER-ID use USER-ID to sign or decrypt 本地用户 user-ID 使用 user-ID 进行签名或解密
> -z N set compress level to N (0 disables) 将压缩级别设置为 N（0 禁用）
> --textmode use canonical text mode 文本模式使用规范文本模式
> -o, --output FILE write output to FILE 输出 FILE 将输出写入 FILE
> -v, --verbose verbose 详细详细
> -n, --dry-run do not make any changes 试运行—不做任何更改
> -i, --interactive prompt before overwriting 覆盖前的交互式提示
> --openpgp use strict OpenPGP behavior openpgp 使用严格的 openpgp 行为
---
> (See the man page for a complete listing of all commands and options)
> （有关所有命令和选项的完整列表，请参阅手册页）
> 示例：
> -se -r Bob [file] sign and encrypt for user Bob Bob[文件]为用户 Bob 签名和加密
> --clear-sign [file] make a clear text signature 明文签名
> --detach-sign [file] make a detached signature 分离签名[文件]制作分离的签名
> --list-keys [names] show keys 列表键[名称]显示键
> --fingerprint [names] show fingerprints 指纹[姓名]显示指纹
> 请向报告错误<https://bugs.gnupg.org>.
