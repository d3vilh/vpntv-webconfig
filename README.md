# vpntv-webconfig
Configuration web-interface for VPNTV project


![Webinstall picture 1](/images/Webinstall-01.png)


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