# base32
Fetching NFT Metadata on Base Python Example:
import requests

url = "https://base-mainnet.infura.io/v3/YOUR_KEY"
resp = requests.post(url, json={"method": "eth_call", ...})
print(resp.json())
Base is growing as an NFT hub.
