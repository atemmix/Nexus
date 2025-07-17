# Nexus Template for Marzban
Nexus is a Marzban template with a modern design

> [!NOTE]
> At the moment, the Nexus Template is only available in `Russian`. <br>
> More languages will be added soon ( `EN`, `BE`, `UA` ).

![Nexus Template for Marzban](https://github.com/atemmix/Nexus/blob/main/screenshots/1.png)
[See more screenshots](https://github.com/atemmix/Nexus/tree/main/screenshots)

> This theme uses icons from the Iconify library — Solar Icons & Emoji One (Colored).<br>
Icons are licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

## Install

Upload the template file to the server:
``` bash
sudo wget -O /var/lib/marzban/templates/subscription/index.html https://raw.githubusercontent.com/atemmix/Nexus/main/subscription/index.html
```

Edit the Marzban `.env` file and add the following lines:
``` bash
CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"
SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"
```

Apply the changes by restarting Marzban:
``` bash
marzban restart
```

## Personalization

| Name                      | Value                                                                           |
|---------------------------|---------------------------------------------------------------------------------|
| Country Icon              | Use two-letter country codes at the beginning of the protocol name to display the flags: <br><br> `AD`- Andorra, `AE`- United Arab Emirates, `AF`- Afghanistan, `AG`- Antigua and Barbuda,<br>`AI`- Anguilla, `AL`- Albania, `AM`- Armenia, `AO`- Angola, `AQ`- Antarctica,<br>`AR`- Argentina, `AS`- American Samoa, `AT`- Austria, `AU`- Australia, `AW`- Aruba,<br>`AX`- Åland Islands, `AZ`- Azerbaijan, `BA`- Bosnia and Herzegovina, `BB`- Barbados,<br>`BD`- Bangladesh, `BE`- Belgium, `BF`- Burkina Faso, `BG`- Bulgaria, `BH`- Bahrain,<br>`BI`- Burundi, `BJ`- Benin, `BL`- Saint Barthélemy, `BM`- Bermuda, `BN`- Brunei,<br>`BO`- Bolivia, `BQ`- Caribbean Netherlands, `BR`- Brazil, `BS`- Bahamas, `BT`- Bhutan,<br>`BV`- Bouvet Island, `BW`- Botswana, `BY`- Belarus, `BZ`- Belize, `CA`- Canada,<br>`CC`- Cocos Islands, `CD`- DR Congo, `CF`- Central African Republic, `CG`- Congo,<br>`CH`- Switzerland, `CI`- Ivory Coast, `CK`- Cook Islands, `CL`- Chile, `CM`- Cameroon,<br>`CN`- China, `CO`- Colombia, `CR`- Costa Rica, `CU`- Cuba, `CV`- Cape Verde,<br>`CW`- Curaçao, `CX`- Christmas Island, `CY`- Cyprus, `CZ`- Czechia, `DE`- Germany,<br>`DJ`- Djibouti, `DK`- Denmark, `DM`- Dominica, `DO`- Dominican Republic, `DZ`- Algeria,<br>`EC`- Ecuador, `EE`- Estonia, `EG`- Egypt, `EH`- Western Sahara, `ER`- Eritrea,<br>`ES`- Spain, `ET`- Ethiopia, `FI`- Finland, `FJ`- Fiji, `FK`- Falkland Islands,<br>`FM`- Micronesia, `FO`- Faroe Islands, `FR`- France, `GA`- Gabon, `GB`- United Kingdom,<br>`GD`- Grenada, `GE`- Georgia, `GF`- French Guiana, `GG`- Guernsey, `GH`- Ghana,<br>`GI`- Gibraltar, `GL`- Greenland, `GM`- Gambia, `GN`- Guinea, `GP`- Guadeloupe,<br>`GQ`- Equatorial Guinea, `GR`- Greece, `GS`- South Georgia, `GT`- Guatemala,<br>`GU`- Guam, `GW`- Guinea-Bissau, `GY`- Guyana, `HK`- Hong Kong, `HM`- Heard Island,<br>`HN`- Honduras, `HR`- Croatia, `HT`- Haiti, `HU`- Hungary, `ID`- Indonesia,<br>`IE`- Ireland, `IL`- Israel, `IM`- Isle of Man, `IN`- India, `IO`- British Indian Ocean Territory,<br>`IQ`- Iraq, `IR`- Iran, `IS`- Iceland, `IT`- Italy, `JE`- Jersey, `JM`- Jamaica,<br>`JO`- Jordan, `JP`- Japan, `KE`- Kenya, `KG`- Kyrgyzstan, `KH`- Cambodia,<br>`KI`- Kiribati, `KM`- Comoros, `KN`- Saint Kitts and Nevis, `KP`- North Korea,<br>`KR`- South Korea, `KW`- Kuwait, `KY`- Cayman Islands, `KZ`- Kazakhstan, `LA`- Laos,<br>`LB`- Lebanon, `LC`- Saint Lucia, `LI`- Liechtenstein, `LK`- Sri Lanka, `LR`- Liberia,<br>`LS`- Lesotho, `LT`- Lithuania, `LU`- Luxembourg, `LV`- Latvia, `LY`- Libya,<br>`MA`- Morocco, `MC`- Monaco, `MD`- Moldova, `ME`- Montenegro, `MF`- Saint Martin,<br>`MG`- Madagascar, `MH`- Marshall Islands, `MK`- North Macedonia, `ML`- Mali,<br>`MM`- Myanmar, `MN`- Mongolia, `MO`- Macau, `MP`- Northern Mariana Islands,<br>`MQ`- Martinique, `MR`- Mauritania, `MS`- Montserrat, `MT`- Malta, `MU`- Mauritius,<br>`MV`- Maldives, `MW`- Malawi, `MX`- Mexico, `MY`- Malaysia, `MZ`- Mozambique,<br>`NA`- Namibia, `NC`- New Caledonia, `NE`- Niger, `NF`- Norfolk Island, `NG`- Nigeria,<br>`NI`- Nicaragua, `NL`- Netherlands, `NO`- Norway, `NP`- Nepal, `NR`- Nauru,<br>`NU`- Niue, `NZ`- New Zealand, `OM`- Oman, `PA`- Panama, `PE`- Peru,<br>`PF`- French Polynesia, `PG`- Papua New Guinea, `PH`- Philippines, `PK`- Pakistan,<br>`PL`- Poland, `PM`- Saint Pierre and Miquelon, `PN`- Pitcairn Islands, `PR`- Puerto Rico,<br>`PS`- Palestine, `PT`- Portugal, `PW`- Palau, `PY`- Paraguay, `QA`- Qatar,<br>`RE`- Réunion, `RO`- Romania, `RS`- Serbia, `RU`- Russia, `RW`- Rwanda,<br>`SA`- Saudi Arabia, `SB`- Solomon Islands, `SC`- Seychelles, `SD`- Sudan,<br>`SE`- Sweden, `SG`- Singapore, `SH`- Saint Helena, `SI`- Slovenia, `SJ`- Svalbard and Jan Mayen,<br>`SK`- Slovakia, `SL`- Sierra Leone, `SM`- San Marino, `SN`- Senegal, `SO`- Somalia,<br>`SR`- Suriname, `SS`- South Sudan, `ST`- São Tomé and Príncipe, `SV`- El Salvador,<br>`SX`- Sint Maarten, `SY`- Syria, `SZ`- Eswatini, `TC`- Turks and Caicos Islands,<br>`TD`- Chad, `TF`- French Southern Territories, `TG`- Togo, `TH`- Thailand,<br>`TJ`- Tajikistan, `TK`- Tokelau, `TL`- Timor-Leste, `TM`- Turkmenistan, `TN`- Tunisia,<br>`TO`- Tonga, `TR`- Turkey, `TT`- Trinidad and Tobago, `TV`- Tuvalu, `TW`- Taiwan,<br>`TZ`- Tanzania, `UA`- Ukraine, `UG`- Uganda, `UK`- United Kingdom, `UM`- US Minor Outlying Islands,<br>`US`- United States, `UY`- Uruguay, `UZ`- Uzbekistan, `VA`- Vatican City,<br>`VC`- Saint Vincent and the Grenadines, `VE`- Venezuela, `VG`- British Virgin Islands,<br>`VI`- US Virgin Islands, `VN`- Vietnam, `VU`- Vanuatu, `WF`- Wallis and Futuna,<br>`WS`- Samoa, `YE`- Yemen, `YT`- Mayotte, `ZA`- South Africa, `ZM`- Zambia, `ZW`- Zimbabwe |
| Client Links             | Replace placeholders with actual links: <br><br> `#WindowsHiddify`, `#WindowsV2rayN`, `#WindowsNekoRay`<br>`#macOSV2rayTUN`, `#macOSHiddify`, `#macOSV2rayU`<br>`#AndroidV2rayTUN`, `#AndroidHiddify`, `#AndroidV2rayNG`<br>`#iOSV2rayTUN`, `#iOSHiddify`, `#iOSStreisand`, `#iOSShadowrocket`<br>`#LinuxHiddify`, `#LinuxQv2ray` |
| Support Links             | Replace placeholders with actual links: <br><br> `#VKlink`, `#Discordlink`, `#Telegramlink` |
