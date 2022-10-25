# IP Database
A database of IP address blocks used to detect VPN's, hosting providers, cloud gaming providers and more.

The database is updated automatically daily and is stored in the [MaxMind](https://blog.maxmind.com/2015/09/building-your-own-mmdb-database-for-fun-and-profit) database format.

**If you plan on using this for anything, please consider sponsoring the project.**

# How to use?
You can use one of the clients listed [here](https://dev.maxmind.com/geoip/docs/databases?lang=en#api-clients).

Example Response:
```
{
  "country": "US",
  "isp": "CloudFlare",
  "vpn": 0,
  "cloud_gaming": 0
}
```

# How to add IP blocks?
You can request blocks to be added or removed by opening an issue and providing the IP block and who it belongs to etc.

# Projects using this:
* [YAAntiVPN](https://github.com/Ameliaaaaaaa/YAAntiVPN)

Get yours listed here by opening a pull request!
