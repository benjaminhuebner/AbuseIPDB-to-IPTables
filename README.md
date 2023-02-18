# AbuseIPDB-to-IPTables
A simple script that helps to block suspicious IP addresses from the [AbuseIPDB](https://abuseipdb.com) with iptables

## Usage
If you haven't already done so, you have to install the curl command

```bash
apt install curl
```
In the script, replace __yourKey__ with your APIv2 key (you can also adjust the other values as needed). <br>
If you don't have an APIv2 key yet, you can easily create one in your [AbuseIPDB](https://abuseipdb.com) account settings.

```bash
_countMinimum=15               # raw report count
_maxAgeInDays=60               # determines how far back in time we go to fetch reports counted for the countMinimum parameter
_confidenceMinimum=90           # confidence of abuse score
_apiv2Key=yourKey               # abuseipdb.com APIv2 Key
```