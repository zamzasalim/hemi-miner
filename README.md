<p style="font-size:14px" align="right">
<a href="https://t.me/airdropasc" target="_blank">Join our telegram <img src="https://user-images.githubusercontent.com/50621007/183283867-56b4d69f-bc6e-4939-b00a-72aa019d1aea.png" width="30"/></a>
</p>

<p align="center">
  <img height="300" height="auto" src="https://user-images.githubusercontent.com/109174478/209359981-dc19b4bf-854d-4a2a-b803-2547a7fa43f2.jpg">
</p>

# HEMI-MINER INCENTIVE TESTNET NODE
- Backed [Binance](https://x.com/hemi_xyz/status/1836392405328638427)
- Official [Docs](https://docs.hemi.xyz/how-to-tutorials/using-hemi/pop-mining/setup-part-1)
### Spek VPS Minimum
|  Hardware/VPS |  Minimum |
| ------------ | ------------ |
| CPU  | 4 or more physical CPU cores  |
| RAM | At least 6GB of memory (RAM) |
| Penyimpanan  | At least 300GB of SSD disk storage |
| Internet | At least 10mbps network bandwidth |
### Auto Install Node
```
bash <(curl -s https://data.zamzasalim.xyz/file/uploads/hemi-miner.sh)
```
### Backup Wallet & Save Address
```
cat $HOME/hemi/popm-address.json
```
### Claim Faucet
- Join [Discord](https://discord.gg/hemixyz)
- Claim use pubkey hash
### After Get Faucet, Restart you node
```
sudo systemctl restart hemi-miner
```
### Check Logs Node
```
journalctl -u hemi-miner.service -f
```
### Monitoring Node
- Go to Website : [Here](https://pop-miner.hemi.xyz/manage)
- Submit your privatekey
- Done
### Delete Node (if node already ended)
```
sudo systemctl stop hemi-miner && \
sudo systemctl disable hemi-miner && \
sudo rm -rf hemi && \
sudo rm /etc/systemd/system/hemi-miner.service && \
sudo systemctl daemon-reload
```
### Cek Status Node : [Here](https://testnet.popstats.hemi.network/)
