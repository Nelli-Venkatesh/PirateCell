# PirateCell
# C# Library which is used for cryptographic Functions 



import the PirateCell.dll or download it using the Nuget package manager console.
Install-Package PirateCell

Functions in this library:

chiper._SALT("string")
returns random SALT value of string 

chiper._SHA_1("string")
returns SHA1 hash value of string

chiper._SHA_1_WITH_SALT("string","salt")
returns SHA1 hash value added with salt

chiper._SHA_256("string")
returns SHA256 hash value of string

chiper._SHA_256_WITH_SALT("strings","salt")
returns SHA256 hash value added with salt

chiper._SHA_512("string")
returns SHA512 hash value of string

chiper._SHA_512_WITH_SALT("string","salt")
returns SHA512 hash value added with salt

chiper._Encrypt("string","key_value","iv_value")
returns encrypted value using AES CBC encryption

chiper._Decrypt("encrypted_string","key_value","iv_value")
returns decrypted value of the string
