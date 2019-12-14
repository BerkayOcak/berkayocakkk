# esx_busjob

## Requirements

* Auto mode
  

* [esx_service](https://github.com/ESX-Org/esx_service)
  


* Player management (billing and boss actions)
  

* [esx_society](https://github.com/ESX-Org/esx_society)
  

* [esx_billing](https://github.com/ESX-Org/esx_billing)

## Download & Installation

### Using 

[fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx esx-org/esx_busjob
```



### Using Git
```
cd resources
git clone https://github.com/ESX-Org/esx_busjob [esx]/esx_busjob
```



### Manually
- Download https://github.com/ESX-Org/esx_busjob/archive/master.zip
- 

Put it in the `[esx]` directory

## Installation
- Import `esx_busjob.sql` in your database
- 

If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`
- 

Add this to your `server.cfg`:
```
start esx_busjob
```

# Legal
### License 
esx_busjob

 Copyright 

Developer is Berkay Ocak
