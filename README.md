# Currency Converter Tool
***
CCT is a lightweight and powerful tool that uses Google Finance API to perform currency conversions directly from the console.
***
## Dependencies
***
CCT need curl.h library to operate. You can install it from [this link](https://curl.haxx.se/download.html "cURL").
***
## Installation
***
Install cct is simple. Open the console and locate yourself within the 'Currency Converter Tool' folder

Run:
```sh
$ chmod +x install.sh
```
```sh
$ sh install.sh
```
and go!

The installation script compiles CCT and generates an exact copy in the /bin/ directory.

Thus, CCT becomes a Linux command as any.

***
## Available commands
***
##### Arguments
```sh
$ cct cct <amount_to_convert> <currency_origin> <currency_destination>
```
__Examples__

	cct 20 usd eur (convert dollar to euro)
	
	cct 5 ARS usd (convert argentine peso to dollar)

__NOTE:__  Supported words are lowercase or uppercase.
##### Help command
```sh
$ cct --help
```
##### Info command
```sh
$ cct --info
```
## Supported currencies
	"AED" - United Arab Emirates Dirham (AED)
	"AFN" - Afghan Afghani (AFN)
	"ALL" - Albanian Lek (ALL)
	"AMD" - Armenian Dram (AMD)
	"ANG" - Netherlands Antillean Guilder (ANG)
	"AOA" - Angolan Kwanza (AOA)
	"ARS" - Argentine Peso (ARS)
	"AUD" - Australian Dollar (A$)
	"AWG" - Aruban Florin (AWG)
	"AZN" - Azerbaijani Manat (AZN)
	"BAM" - Bosnia-Herzegovina Convertible Mark (BAM)
	"BBD" - Barbadian Dollar (BBD)
	"BDT" - Bangladeshi Taka (BDT)
	"BGN" - Bulgarian Lev (BGN)
	"BHD" - Bahraini Dinar (BHD)
	"BIF" - Burundian Franc (BIF)
	"BMD" - Bermudan Dollar (BMD)
	"BND" - Brunei Dollar (BND)
	"BOB" - Bolivian Boliviano (BOB)
	"BRL" - Brazilian Real (R$)
	"BSD" - Bahamian Dollar (BSD)
	"BTC" - Bitcoin (฿)
	"BTN" - Bhutanese Ngultrum (BTN)
	"BWP" - Botswanan Pula (BWP)
	"BYR" - Belarusian Ruble (BYR)
	"BZD" - Belize Dollar (BZD)
	"CAD" - Canadian Dollar (CA$)
	"CDF" - Congolese Franc (CDF)
	"CHF" - Swiss Franc (CHF)
	"CLF" - Chilean Unit of Account (UF) (CLF)
	"CLP" - Chilean Peso (CLP)
	"CNH" - CNH (CNH)
	"CNY" - Chinese Yuan (CN¥)
	"COP" - Colombian Peso (COP)
	"CRC" - Costa Rican Colón (CRC)
	"CUP" - Cuban Peso (CUP)
	"CVE" - Cape Verdean Escudo (CVE)
	"CZK" - Czech Republic Koruna (CZK)
	"DEM" - German Mark (DEM)
	"DJF" - Djiboutian Franc (DJF)
	"DKK" - Danish Krone (DKK)
	"DOP" - Dominican Peso (DOP)
	"DZD" - Algerian Dinar (DZD)
	"EGP" - Egyptian Pound (EGP)
	"ERN" - Eritrean Nakfa (ERN)
	"ETB" - Ethiopian Birr (ETB)
	"EUR" - Euro (€)
	"FIM" - Finnish Markka (FIM)
	"FJD" - Fijian Dollar (FJD)
	"FKP" - Falkland Islands Pound (FKP)
	"FRF" - French Franc (FRF)
	"GBP" - British Pound (£)
	"GEL" - Georgian Lari (GEL)
	"GHS" - Ghanaian Cedi (GHS)
	"GIP" - Gibraltar Pound (GIP)
	"GMD" - Gambian Dalasi (GMD)
	"GNF" - Guinean Franc (GNF)
	"GTQ" - Guatemalan Quetzal (GTQ)
	"GYD" - Guyanaese Dollar (GYD)
	"HKD" - Hong Kong Dollar (HK$)
	"HNL" - Honduran Lempira (HNL)
	"HRK" - Croatian Kuna (HRK)
	"HTG" - Haitian Gourde (HTG)
	"HUF" - Hungarian Forint (HUF)
	"IDR" - Indonesian Rupiah (IDR)
	"IEP" - Irish Pound (IEP)
	"ILS" - Israeli New Sheqel (₪)
	"INR" - Indian Rupee (Rs.)
	"IQD" - Iraqi Dinar (IQD)
	"IRR" - Iranian Rial (IRR)
	"ISK" - Icelandic Króna (ISK)
	"ITL" - Italian Lira (ITL)
	"JMD" - Jamaican Dollar (JMD)
	"JOD" - Jordanian Dinar (JOD)
	"JPY" - Japanese Yen (¥)
	"KES" - Kenyan Shilling (KES)
	"KGS" - Kyrgystani Som (KGS)
	"KHR" - Cambodian Riel (KHR)
	"KMF" - Comorian Franc (KMF)
	"KPW" - North Korean Won (KPW)
	"KRW" - South Korean Won (₩)
	"KWD" - Kuwaiti Dinar (KWD)
	"KYD" - Cayman Islands Dollar (KYD)
	"KZT" - Kazakhstani Tenge (KZT)
	"LAK" - Laotian Kip (LAK)
	"LBP" - Lebanese Pound (LBP)
	"LKR" - Sri Lankan Rupee (LKR)
	"LRD" - Liberian Dollar (LRD)
	"LSL" - Lesotho Loti (LSL)
	"LTL" - Lithuanian Litas (LTL)
	"LVL" - Latvian Lats (LVL)
	"LYD" - Libyan Dinar (LYD)
	"MAD" - Moroccan Dirham (MAD)
	"MDL" - Moldovan Leu (MDL)
	"MGA" - Malagasy Ariary (MGA)
	"MKD" - Macedonian Denar (MKD)
	"MMK" - Myanmar Kyat (MMK)
	"MNT" - Mongolian Tugrik (MNT)
	"MOP" - Macanese Pataca (MOP)
	"MRO" - Mauritanian Ouguiya (MRO)
	"MUR" - Mauritian Rupee (MUR)
	"MVR" - Maldivian Rufiyaa (MVR)
	"MWK" - Malawian Kwacha (MWK)
	"MXN" - Mexican Peso (MX$)
	"MYR" - Malaysian Ringgit (MYR)
	"MZN" - Mozambican Metical (MZN)
	"NAD" - Namibian Dollar (NAD)
	"NGN" - Nigerian Naira (NGN)
	"NIO" - Nicaraguan Córdoba (NIO)
	"NOK" - Norwegian Krone (NOK)
	"NPR" - Nepalese Rupee (NPR)
	"NZD" - New Zealand Dollar (NZ$)
	"OMR" - Omani Rial (OMR)
	"PAB" - Panamanian Balboa (PAB)
	"PEN" - Peruvian Nuevo Sol (PEN)
	"PGK" - Papua New Guinean Kina (PGK)
	"PHP" - Philippine Peso (Php)
	"PKG" - PKG (PKG)
	"PKR" - Pakistani Rupee (PKR)
	"PLN" - Polish Zloty (PLN)
	"PYG" - Paraguayan Guarani (PYG)
	"QAR" - Qatari Rial (QAR)
	"RON" - Romanian Leu (RON)
	"RSD" - Serbian Dinar (RSD)
	"RUB" - Russian Ruble (RUB)
	"RWF" - Rwandan Franc (RWF)
	"SAR" - Saudi Riyal (SAR)
	"SBD" - Solomon Islands Dollar (SBD)
	"SCR" - Seychellois Rupee (SCR)
	"SDG" - Sudanese Pound (SDG)
	"SEK" - Swedish Krona (SEK)
	"SGD" - Singapore Dollar (SGD)
	"SHP" - St. Helena Pound (SHP)
	"SKK" - Slovak Koruna (SKK)
	"SLL" - Sierra Leonean Leone (SLL)
	"SOS" - Somali Shilling (SOS)
	"SRD" - Surinamese Dollar (SRD)
	"STD" - São Tomé & Príncipe Dobra (STD)
	"SVC" - Salvadoran Colón (SVC)
	"SYP" - Syrian Pound (SYP)
	"SZL" - Swazi Lilangeni (SZL)
	"THB" - Thai Baht (THB)
	"TJS" - Tajikistani Somoni (TJS)
	"TMT" - Turkmenistani Manat (TMT)
	"TND" - Tunisian Dinar (TND)
	"TOP" - Tongan Pa´anga (TOP)
	"TRY" - Turkish Lira (TRY)
	"TTD" - Trinidad & Tobago Dollar (TTD)
	"TWD" - New Taiwan Dollar (NT$)
	"TZS" - Tanzanian Shilling (TZS)
	"UAH" - Ukrainian Hryvnia (UAH)
	"UGX" - Ugandan Shilling (UGX)
	"USD" - US Dollar ($)
	"UYU" - Uruguayan Peso (UYU)
	"UZS" - Uzbekistani Som (UZS)
	"VEF" - Venezuelan Bolívar (VEF)
	"VND" - Vietnamese Dong (&#8363;)
	"VUV" - Vanuatu Vatu (VUV)
	"WST" - Samoan Tala (WST)
	"XAF" - Central African CFA Franc (FCFA)
	"XCD" - East Caribbean Dollar (EC$)
	"XDR" - Special Drawing Rights (XDR)
	"XOF" - West African CFA Franc (CFA)
	"XPF" - CFP Franc (CFPF)
	"YER" - Yemeni Rial (YER)
	"ZAR" - South African Rand (ZAR)
	"ZMK" - Zambian Kwacha (1968-2012) (ZMK)
	"ZMW" - Zambian Kwacha (ZMW)
	"ZWL" - Zimbabwean Dollar (2009) (ZWL)

***
## License
***

This program is _"free as in free speech, not free beer"_.

For this reason, CCT used the GPLv3 license.

__Please, fork this project and contact me for any bugs or recommendation.__

### Versions
Current version: 1.0

