# crypto

CLI tool to encrypt/decrypt the specified file.

## Requirements

* Python 3.x

```
$ pip install -r requirements.txt
```

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
