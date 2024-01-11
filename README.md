## Encoding
- Process of converting data or a given sequence of characters, symbols, alphabets from one format into another format using a scheme that is publicly available
- Ensures data usability by transforming the data
- ASCII, UNICODE, URL, Base64

## Decoding
- Opposite of encoding
- A reversible process, using the same algorithm as encoding
- No key is required to encode and decode data

## Encryption
- Transforms data from one format into another
- Key required to decrypt data
- Maintains data confidentiality by keeping it unreadable to those without the key

### Symmetric Encryption
- Only one key is required to encrypt and decrypt
- Advanced Encryption Standard (AES) uses only 128 bit or 256 bit keys
- Much faster than asymmetric encryption

### Asymmetric Encryption
- Uses a pair of keys to encrypt and decrypt
- Called public and private key
- Data encrypted with private key can be decrypted with public key, and vice versa
- RSA uses 2048 bit to 4096 bit keys

## Hashing
- Transforms arbitrary length data into fixed length using hashing algorithm
- Ensures data integrity
- Same inputs produces same output
- Different inputs cannot produce same output
- Used to generate memory addresses responding to keys in dictionaries, maps, etc.
- SHA-256
