# vpntv-webconfig
Configuration web-interface for VPNTV project

<img src="https://raw.githubusercontent.com/d3vilh/vpntv-webconfig/main/images/Webinstall-01.png" alt="VPNTV webconfig main page" width="500" border="1"/>


To build the webinstall binary:
```shell
go build -o webinstall main.go
```

To compress new binary with upx:
```shell
sudo apt-get install upx-ucl
upx --best webinstall
upx -t webinstall
```


<a href="https://www.buymeacoffee.com/d3vilh" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="51" width="217"></a>
