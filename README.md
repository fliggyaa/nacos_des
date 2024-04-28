# nacos_des
A nacos background configuration file decryption program

This tool is used to decrypt the configuration file when it is encrypted when we enter the nacos background. Currently, it only supports the default algorithm. If the current algorithm cannot be decrypted, please contact the author for a version upgrade.

### usage

The key is obtained by searching the password field in jasypt:encryptor:. The ciphertext is the ciphertext we want to obtain. The decryption method is obtained by searching the algorithm. If it is empty, it is the default method. Currently, only the default method is supported. If other Please add the method in time.

<img width="800" alt="image" src="https://github.com/fliggyaa/nacos_des/assets/82925172/4312a596-fc67-43ac-b0e1-b0c09249b8de">
