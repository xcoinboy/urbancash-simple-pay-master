# Urbancash-simple-pay
Simle Payment Gateway via Urbancash masternodes' Decentralized API

It can check payment via any Urbancash masternode starting of version v.2.3.234.
Required JSON RPC methods: `get_transaction_hashes_by_payment_id` and `check_tx_with_view_key`. 

## How to use
Just open page in browser and enter your public address, private view key, masternode URL and so on in Settings.

Enter or generate Payment ID, amount and create Payment Request. Show QR code to payer or copy payment URI and send it to him.

Gateway uses Payment ID to search for transactions, therefore without it payment will not be confirmed.
