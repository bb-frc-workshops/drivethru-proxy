# drivethru-proxy

Simple redirecting TCP proxy for drivethru. 

## Usage

Clone this repo, and then run:

```
$ npm install -g ./
```

To use, you can now run

```
$ drivethru-proxy 9001 <raspberry pi IP address> 9001
```

All calls to the local drivethru instance will now get routed to whatever IP address you specify
