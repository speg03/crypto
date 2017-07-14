# crypto

CLI tool to encrypt/decrypt the specified file.

## Generate encrypt key

```
$ export ENCRYPT_KEY=$(./crypto keygen)
```

## Encryption

```
$ ./crypto encrypt --key=${ENCRYPT_KEY} /path/to/file
```

## Decryption

```
$ ./crypto decrypt --key=${ENCRYPT_KEY} /path/to/file.encrypted
```
