# emoji-seed
Seed phrase generator that is BIP-39 compliant and uses Emojis


BIP39 seed phrases are made with words from the BIP-39 word list. There are 2048 of them, and each is mapped to a number (between 0 and 2047 inclusive)

There are now more than 3600 emojis. Meaning emojis can be used instead of seed words for a BIP-39 style seed phrase that can be used to generate private keys for cryptography, ethereum or bitcoin wallets, and more.

## In this repo
- Emojis.txt - a list of emojis used here. I tried to choose ones that are more unique, but in order to make a complete list of 2048 emojis, there are some that are similar. 
- Generator.js - a javascript implementation of generating a seed phrase with emojis
- english.txt - the BIP-39 word list

## TO DO
- Front end for generating emojis seed phrases
- python implementation
- give the emoji side by side the word list

## Notes
When using this tool, keep in mind the same emoji with different skin colors or attributes, counts as a different emoji/bit in the seed.
