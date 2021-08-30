`solve_bs` is analogous to CraptEV1 `solve` and works on .txt files using the bitsliced crypto-1 cracker

    $ ./solve_bs craptev1-v1.1/0xcafec0de.txt 0xcafec0de

`solve_piwi` uses CraptEV1 on .bin files as gathered by piwi's PM3 code

    $ ./solve_piwi 0xcafec0de.bin

`solve_piwi_bs` does the same but uses the bitsliced cracker

    $ ./solve_piwi_bs 0xcafec0de.bin

`libnfc_crypto1_crack` uses libnfc to demonstrate the CraptEV1 code using the bitsliced cracker

    $ ./libnfc_crypto1_crack 000000000000 0 A 4 A
