# Game-of-india                        pip install ton  

from ton import TonlibClient

client = TonlibClient(config="https://ton.org/config.json")
address = "EQD..."
balance = client.get_account_balance(address)
print(f"Balance: {balance} TON")

