# rpi-rtl8812au

A tool to build the Realtek RTL8812AU driver for micro dual-band USB wireless adapters on your Raspberry Pi.

## Supported Devices

According to [WikiDev.com](https://wikidevi.com/wiki/Special:Ask?title=Special%3AAsk&q=%5B%5BChip1+model::RTL8811AU%5D%5D&po=%3FInterface%0D%0A%3FForm+factor=FF%0D%0A%3FInterface+connector+type=USB+conn.%0D%0A%3FFCC+ID%0D%0A%3FManuf%0D%0A%3FManuf+product+model=Manuf.+mdl%0D%0A%3FVendor+ID%0D%0A%3FDevice+ID%0D%0A%3FChip1+model%0D%0A%3FSupported+802dot11+protocols=PHY+modes%0D%0A%3FMIMO+config%0D%0A%3FOUI%0D%0A%3FEstimated+year+of+release=Est.+year&eq=yes&p%5Bformat%5D=broadtable&order%5B0%5D=ASC&sort_num=&order_num=ASC&p%5Blimit%5D=500&p%5Boffset%5D=&p%5Blink%5D=all&p%5Bsort%5D=&p%5Bheaders%5D=show&p%5Bmainlabel%5D=&p%5Bintro%5D=&p%5Boutro%5D=&p%5Bsearchlabel%5D=%E2%80%A6+further+results&p%5Bdefault%5D=&p%5Bclass%5D=sortable+wikitable+smwtable):

* ASUS WN4509L
* Acer UWA4
* Amped Wireless UA230A
* Buffalo WI-U2-433DM
* CC&C WL-8211-V1
* D-Link DWA-171 rev A1
* D-Link DWA-172 rev A1
* EDUP EP-AC1607
* Edimax EW-7811UAC
* Edimax EW-7811USC
* Edimax EW-7811UTC
* Edimax EW-7811UTC 7392 A812
* Hawking HD65U		
* HiRO H50334		
* Iconnect AWUS036ACS
* Lite-On WN4509L	
* Manhattan 525602
* Meross MWA255
* Netgear A6100
* Nexxt Solutions Lynx 600-AC (AULUB605U1)
* Panasonic AJ-WM50P
* Patriot AC600
* Premiertek PT-8811AU		
* Rosewill RNX-AC600NUB
* SZHUASHI HS600AC
* Shen Zhen Xin Hua Tian Technology 5B06
* Shenzhen Xunman Technology Co M-600Y
* TP-LINK Archer T2U Nano
* TRENDnet TEW-804UB

## Dependencies

```bash
sudo apt-get install wget git make gcc
```

## Execution

```bash
./rpi-rtl8812au
```

## Credits

* [Ole Petter Bang](https://github.com/gnab) for creating and maintaining a [rtl8812au fork](https://github.com/gnab/rtl8812au) for newer versions of Linux.
