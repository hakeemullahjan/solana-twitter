solana-test-validator --reset
solana-keygen recover
solana address -k target/deploy/solana_twitter-keypair.json
anchor test
anchor run test
anchor run my-custom-script
solana rent 4000 (4kb)
