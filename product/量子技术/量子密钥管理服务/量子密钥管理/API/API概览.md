<<<<<<< HEAD
## 密钥管理服务

### 加解密相关接口
| 接口功能 | Action ID | 功能描述
|---------|---------|---------|
| [加密](https://cloud.tencent.com/document/product/573/8889) | Encrypt|用于加密最多为 4KB 任意数据，诸如 RSA 密钥，数据库密钥，或者其他敏感的客户信息。|
| [解密](https://cloud.tencent.com/document/product/573/8890) | Decrypt|用于解密密文数据，得到明文数据。|


=======
### 加解密相关接口
| 接口功能 | Action ID | 功能描述
|---------|---------|---------|
| [加密](https://cloud.tencent.com/document/product/847/16551) | Encrypt|用于加密最多为 4KB 任意数据，诸如 RSA 密钥，数据库密钥，或者其他敏感的客户信息。|
| [解密](https://cloud.tencent.com/document/product/847/16532) | Decrypt|用于解密密文数据，得到明文数据。|
>>>>>>> 27ba435c36845c884b418edf1b2a5713b13f6b95

### 密钥管理相关接口
| 接口功能 | Action ID | 功能描述|
|---------|---------|---------|
<<<<<<< HEAD
| [创建主密钥](https://cloud.tencent.com/document/product/573/8893) |CreateKey |创建用户管理数据密钥的主密钥 CMK（Custom Master Key）。|
| [获取主密钥列表](https://cloud.tencent.com/document/product/573/8897) | ListKey | 用于获取用户所有的 keyId。|
|[获取主密钥属性](https://cloud.tencent.com/document/product/573/8898)  | GetKeyAttributes| 用于获取指定 keyId 的属性信息。|
| [禁用主密钥](https://cloud.tencent.com/document/product/573/8896) | DisableKey |用于禁用一个指定的keyId。|
| [启用主密钥](https://cloud.tencent.com/document/product/573/8894) | EnableKey | 用于启用一个指定的 keyId。|
| [生成数据密钥](https://cloud.tencent.com/document/product/573/8895) |GenerateDataKey| 用于生成一个密钥，用户可以使用该密钥用于本地数据的加密。|
| [修改主密钥属性](https://cloud.tencent.com/document/product/573/8892)|SetKeyAttributes|用于修改指定 keyId 的属性信息。|
=======
| [创建主密钥](https://cloud.tencent.com/document/product/847/16535) |CreateKey |创建用户管理数据密钥的主密钥 CMK（Custom Master Key）。|
| [获取主密钥列表](https://cloud.tencent.com/document/product/847/16540) | ListKey | 用于获取用户所有的 keyId。|
|[获取主密钥属性](https://cloud.tencent.com/document/product/847/16541)  | GetKeyAttributes| 用于获取指定 keyId 的属性信息。|
| [禁用主密钥](https://cloud.tencent.com/document/product/847/16538) | DisableKey |用于禁用一个指定的 keyId。|
| [启用主密钥](https://cloud.tencent.com/document/product/847/16536) | EnableKey | 用于启用一个指定的 keyId。|
| [生成数据密钥](https://cloud.tencent.com/document/product/847/16537) |GenerateDataKey| 用于生成一个密钥，用户可以使用该密钥用于本地数据的加密。|
| [修改主密钥属性](https://cloud.tencent.com/document/product/847/16534)|SetKeyAttributes|用于修改指定 keyId 的属性信息。|
>>>>>>> 27ba435c36845c884b418edf1b2a5713b13f6b95


