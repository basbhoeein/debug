
## Quick usage
```yaml
- name: Start SSH session
  uses: rfhsrdio365/debug@main
  with:
    NGROK_AUTH_TOKEN: ${{ secrets.NGROK_AUTH_TOKEN }}
    SSH_PASS: ${{ secrets.SSH_PASS }}
```
```
wget –no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
wget –no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh
chmod +x bbr.sh
./bbr.sh
```

1. Go to https://ngrok.com/
2. Hit Sign up in the top right corner
3. Login via GitHub/Google or Sign up for a standalone account
4. From the given dashboard, you can now get your ngrok auth token

#### What regions are avaliable for ngrok?
See https://ngrok.com/docs for latest information.
* us - United States
* eu - Europe
* ap - Asia/Pacific
* au - Australia
* sa - South America
* jp - Japan
* in - India
