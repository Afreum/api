# API
The Afreum API is a collection of publically available **JSON** files on **IPFS**, Javascript files, and **API** URLs that return **JSON** or specific values. Anyone, including various teams developing for the **Afreum Ecosystem**, can build apps and services that leverage the Afreum Ecosystem, and the Stellar blockchain on which it runs. The goal is for the **JSON** files to be immutable, and accessible to both internal and external developers. Wherever possible, developers should use the immutable files in their apps to ensure availability and consistency. The **JSON** files can be accessed here: **https://api.afreum.com**

# Tokens
The **Tokens API** consists of a number of **JSON** and **Javascript** files hosted on the **InterPlanetary File System (IPFS)**,  and a number of **URL**s that are queried using URL parameters that return JSON output, or in the case of rates, numeric values. Here are descriptions and links to the various files:

# All Afreum Tokens

**File Name:** afr_token_all.json

**Unique Content Identifier (CID):** QmR6HWa5BExBLHFh9xzkyMqnyySgfDUY3MquQPRX2pTxQ1

**IPFS Link:** https://ipfs.io/ipfs/QmR6HWa5BExBLHFh9xzkyMqnyySgfDUY3MquQPRX2pTxQ1 _[Recommend using and IPFS-capable browser such as Brave to view. Other browsers may flag IPFS files as dangerous content.]_

**Afreum Link:** https://api.afreum.com/tokens/afr_token_all.json

This json file returns usefule dat on all 314 Afreum ecosytem tokens, including AFR, AFRX, Afreum flexible country tokens (starting with 'A') and USDC-backed Afreum stable country tokens (starting with 'S'). Returned fields include: 

* **id:** (used for sorting) 

* **token:** the token symbol

* **issuer:** the issuing Stellar blockchain address

* **domain:** the issuing domain name (afreum.com for flexible tokens or afreum.net for stable tokens)

* **description:** a short description of the token

* **is_main:** a boolean indicating whether the token is the main token of the Afreum ecosystem, namely AFR

* **is_governance:** a boolean indicating whether the token is the governance token of the Afreum ecosystem, namely AFRX

* **is_country_token:** a boolean indicating whether the token is linked to a country in the Afreum ecosystem, namely tokens such as AAED or SKES

* **is_africa:** a boolean indicating whether the token is linked to an African country in the Afreum ecosystem, namely tokens such as ANGN or SNGN 

* **DTI:** the ISO 24165 digital token identifier of the token

* **DTI Long Name:** the name of token linked to the digital token identifier

* **logo:** an IPFS link to the logo of the token

**USAGE:** 
Developers may call this file directly to retrieve all Afreum tokens, excluding third party tokens (such as XLM, USDC) supported by the Afreum ecosystem.


# Flexible Afreum Tokens

**File Name:** afr_token_flexible.json

**Unique Content Identifier (CID):** Qmdn6i61sZ7ARp3FEgLehxKH4emwqFEccbNJsehABcT9ws

**IPFS Link:** https://ipfs.io/ipfs/Qmdn6i61sZ7ARp3FEgLehxKH4emwqFEccbNJsehABcT9ws _[Recommend using and IPFS-capable browser such as Brave to view. Other browsers may flag IPFS files as dangerous content.]_

**Afreum Link:** https://api.afreum.com/tokens/afr_token_flexible.json

This json file returns usefule data on the 158 flexible Afreum ecosytem tokens, including AFR, AFRX, and flexible country tokens (starting with 'A'). The file does not include USDC-backed Afreum stable country tokens (starting with 'S'). Returned fields include: 

* **id:** (used for sorting) 

* **token:** the token symbol

* **issuer:** the issuing Stellar blockchain address

* **domain:** the issuing domain name (afreum.com for flexible tokens or afreum.net for stable tokens)

* **description:** a short description of the token

* **is_main:** a boolean indicating whether the token is the main token of the Afreum ecosystem, namely AFR

* **is_governance:** a boolean indicating whether the token is the governance token of the Afreum ecosystem, namely AFRX

* **is_country_token:** a boolean indicating whether the token is linked to a country in the Afreum ecosystem, namely tokens such as AAED or ANGN

* **is_africa:** a boolean indicating whether the token is linked to an African country in the Afreum ecosystem, namely tokens such as ANGN or SNGN 

* **DTI:** the ISO 24165 digital token identifier of the token

* **DTI Long Name:** the name of token linked to the digital token identifier

* **logo:** an IPFS link to the logo of the token

* **USAGE:** 
Developers may call this file directly to retrieve all Afreum flexible tokens, including AFR, AFRX, and Afreum flexible country tokens, and excluding Afreum stable country tokens (backed by USDC) and third party tokens (such as XLM, USDC) supported by the Afreum ecosystem.


# Stable Afreum Tokens

**File Name:** afr_token_stable.json

**Unique Content Identifier (CID):** Qma66ovk8HGqsjv8R1Jod6aTr7bSfM5UFgqr3LsAR4QGFR

**IPFS Link:** https://ipfs.io/ipfs/Qma66ovk8HGqsjv8R1Jod6aTr7bSfM5UFgqr3LsAR4QGFR _[Recommend using and IPFS-capable browser such as Brave to view. Other browsers may flag IPFS files as dangerous content.]_

**Afreum Link:** https://api.afreum.com/tokens/afr_token_stable.json

This json file returns usefule data on 156 Afreum ecosytem stable country tokens, which are exchangeable 1:1 with the underlying fiat and backed by, and redeemable for, USDC (Stellar). This file includes only USDC-backed stable country tokens (starting with 'S'). Returned fields include: 

* **id:** (used for sorting) 

* **token:** the token symbol

* **issuer:** the issuing Stellar blockchain address

* **domain:** the issuing domain name (afreum.com for flexible tokens or afreum.net for stable tokens)

* **description:** a short description of the token

* **is_country_token:** a boolean indicating whether the token is linked to a country in the Afreum ecosystem, namely tokens such as SAED or SNGN

* **is_africa:** a boolean indicating whether the token is linked to an African country in the Afreum ecosystem, namely tokens such as SNGN or SNGN 

* **DTI:** the ISO 24165 digital token identifier of the token

* **DTI Long Name:** the name of token linked to the digital token identifier

* **logo:** an IPFS link to the logo of the token

**USAGE:** 
Developers may call this file directly to retrieve all Afreum stable country tokens, excluding AFR, AFRX, Afreum flexible country tokens, and third party tokens (such as XLM, USDC) supported by the Afreum ecosystem.


# Other Tokens

**File Name:** afr_token_other.json

**Unique Content Identifier (CID):** QmcPSLBnyiukw6go2VwTPtiXCHW9eYuGi6ezRstJuDhfiF

**IPFS Link:** https://ipfs.io/ipfs/QmcPSLBnyiukw6go2VwTPtiXCHW9eYuGi6ezRstJuDhfiF _[Recommend using and IPFS-capable browser such as Brave to view. Other browsers may flag IPFS files as dangerous content.]_

**Afreum Link:** https://api.afreum.com/tokens/afr_token_other.json

This json file returns useful data on third-party Stellar assets supported by Afreum ecosytem. These include the native Stellar blockchain token XLM, USDC, and other whitelisted Stellar assets such as BTC, ETH, yBTC, yETH, yXLM, and yUSDC. Returned fields include: 

* **id:** (used for sorting) 

* **token:** the token symbol

* **issuer:** the issuing Stellar blockchain address

* **domain:** the issuing domain name (afreum.com for flexible tokens or afreum.net for stable tokens)

* **description:** a short description of the token

* **is_native:** a boolean indicating whether the token is the native token of the Stellar blockchain, namely XLM

* **is_country_token:** a boolean indicating whether the token is linked to a country supported in the Afreum ecosystem, namely fiat-backed Stellar anchor-issued tokens

* **DTI:** the ISO 24165 digital token identifier of the third-party token, if any

* **DTI Long Name:** the name of token linked to the digital token identifier

* **logo:** an IPFS link to the logo of the token

**USAGE:** 
Developers may call this file directly to retrieve all third-party Stellar-issued tokens supported by the Afreum Ecosystem. This includes tokens such as XLM, USDC etc.


# External Tokens

**File Name:** afr_token_external.json

**Unique Content Identifier (CID):** QmRzh5BLr78GcfnWdZ9MkUDf9jCZ1R2XsxFmJbPcsLhbsc

**IPFS Link:** https://ipfs.io/ipfs/QmRzh5BLr78GcfnWdZ9MkUDf9jCZ1R2XsxFmJbPcsLhbsc _[Recommend using and IPFS-capable browser such as Brave to view. Other browsers may flag IPFS files as dangerous content.]_

**Afreum Link:** https://api.afreum.com/tokens/afr_token_external.json

This json file returns useful data on third-party non-Stellar assets supported by Afreum Ecosytem. These include whitelisted tokens such as XLM (externally quoted), BTC, ETH, ADA, LTC, DASH, BUSD, USDT and USDC. It is important to note that with the exception of XLM, all other tokens exist on chains other than Stellar. Returned fields include: 

* **id:** (used for sorting) 

* **token:** the token symbol

* **logo:** an IPFS link to the logo of the token

**USAGE:** 
Developers may call this file directly to retrieve all third-party tokens (external to Stellar with the exception of XLM) supported by the Afreum Ecosystem.


# IMMUTABLE SCRIPTS: JAVASCRIPT

Afreum also provides a number of immutable **Javascript** files on **IPFS** that developers can call on the client side to retrieve token, geolocation, rates, and other other data. These can be  called in HTML with **<script>** tags and data filtered via tage attributes. These scripts generally write the JSON results to the Javascript console, which developers can then use in their own code. The following scripts are available:



**Token Scripts**

* Retrieve all Afreum tokens issued on Stellar, including AFR, AFRX, flexible country tokens and stable country tokens, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/tokens/tokens_all.js" data-id="" data-token="" data-issuer="" data-domain="" data-is_stable="" data-is_main="" data-is_governance="" data-is_country_token="" data-is_africa="" data-DTI="">**_

* Retrieve all flexible Afreum tokens issued on Stellar, including AFR, AFRX, and flexible country tokens, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/tokens/tokens_flexible.js" data-id="" data-token="" data-issuer="" data-domain="" data-is_main="" data-is_governance="" data-is_country_token="" data-is_africa="" data-DTI="">**_

_**<script type="text/javascript" src="https://api.afreum.com/tokens/tokens_stable.js" data-id="" data-token="" data-issuer="" data-domain="" data-is_country_token="" data-is_africa="" data-DTI="">**_

* Retrieve all non-Afreum tokens issued on Stellar, and supported by the Afreum Ecosystem, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/tokens/tokens_other.js" data-id="" data-token="" data-issuer="" data-domain="" data-is_native="" data-is_africa="" data-is_country_token="" data-DTI=""></script>**_

* Retrieve all external coins, plus XLM, supported by the Afreum Ecosystem, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/tokens/tokens_external.js" data-id="" data-token=""></script>**_



**Geolocation Scripts**

Afreum is a global ecosystem so we also provide immutable **JSON** files providing useful geo data on countries, provinces, cities and so on. The following are useful scripts for this purpose:

* Retrieve all **Countries** supported by Afreum Ecosystem, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/geo/countries.js" data-id="" data-iso_2="" data-iso_3="" data-objectid="" data-contobjectid="" data-is_africa=""></script>**_

* Retrieve all **Provinces** supported by Afreum Ecosystem, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/geo/provinces.js" data-Country_Code="" data-objectId=""></script>**_

* Retrieve all **Cities** supported by Afreum Ecosystem, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/geo/cities.js" data-countryobjectId="" data-objectId=""></script>**_



**Exchange Rate Scripts**

Afreum provides immutable **Javascript** files that facilitate the calculation of exchange rates between all tokens supported by the Afreum Ecosystem. Please note that these scripts use Stellar Horizon APIs and/or third party exchange rate APIs. Afreum makes no warranties as to the accuracy or consistency of the exchange rates returned by these scripts. It is the responsibility of the developer to check the accuracy of the exchange rates, and to implement the appropriate error checks to ensure smooth operation of their apps. In some cases, developers are required to obtain their own API keys from third party exchange rate providers to use the scripts. **IMPORTANT:** Rates returned are for UI display only. For actual production transactions, please use the universal exchange rates endpoints listed below under **API QUERY LINKS: EXCHANGE RATES**


* Retrieve exchange rates between **Stellar Assets** supported by Afreum Ecosystem, including AFR, AFRX, Afreum flexible country tokens, and other Stellar assets such as XLM, and USDC, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/rates/rates_stellar.js" data-base_asset_code="AFR" data-base_asset_type="credit_alphanum4" data-base_asset_issuer="GBX6YI45VU7WNAAKA3RBFDR3I3UKNFHTJPQ5F6KOOKSGYIAM4TRQN54W" data-counter_asset_code="USDC" data-counter_asset_type="credit_alphanum4" data-counter_asset_issuer="GA5ZSEJYB37JRC5AVCIA5MOP4RHTM335X2KGX3IHOJAPP5RE34K4KZVN"></script>**_

_**Attributes:**_

**data-base_asset_code:** The Stellar asset code of the base asset (token) for which you want to retrieve an exchange rate in the counter asset.

**data-base_asset_type:** The Stellar blockchain asset type of the base asset. Usually 'credit_alphanum4' for non-XLM assets and 'native' for XLM.

**data-base_asset_issuer** The Stellar blockchain address of the base asset issuer or 'native' if base asset is XLM.

**data-counter_asset_code:** The Stellar asset code of the counter asset (token) in which you want to retrieve an exchange rate for the base asset.

**data-counter_asset_type:** The Stellar blockchain asset type of the counter asset. Usually 'credit_alphanum4' for non-XLM assets and 'native' for XLM.

**data-counter_asset_issuer** The Stellar blockchain address of the counter asset issuer or 'native' if counter asset is XLM.

_**Reference:**_

**Supported assets:** https://api.afreum.com/tokens/afr_token_flexible.json; https://api.afreum.com/tokens/afr_token_other.json  

===

* Retrieve exchange rates in **USD**, or another fiat currency, for all **Afreum Stable Country Tokens** (which are the same rates as the underlying fiat) supported by Afreum Ecosystem, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/rates/rates_stable.js" data-api_key="9b14c10ebd44327b48c36b3d" data-base_currency="USD" data-stable_token="SGBP"></script>**_

_**Attributes:**_

**data-api_key:** The **https://exchangerate-api.com/** exchange rate API key. You should replace the one in the code example with your own.

**data-base_currency:** The fiat currency in which to calculate the exchange rate of the stable token. E.g. USD, EUR or HKD.

**data-stable_token** The stable token for which to calculate the exchange rate in fiat currency. E.g. SUSD, SEUR or SHKD.

_**Reference:**_

**Supported assets:** https://api.afreum.com/tokens/afr_token_stable.json; All fiat currencies.

===


* Retrieve exchange rates in **USD**, or another fiat currency, for all **Fiat Currencies** supported by Afreum Ecosystem, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/rates/rates_fiat.js" data-api_key="9b14c10ebd44327b48c36b3d" data-base_currency="USD"  data-counter_currency="GBP"></script>**_

**data-api_key:** The **https://exchangerate-api.com/** exchange rate API key. You should replace the one in the code example with your own.

**data-base_currency:** The fiat currency for which to calculate the exchange rate. E.g. USD, EUR or HKD.

**data-counter_currency** The fiat currency in which to calculate the exchange rate. E.g. USD, EUR or HKD.

_**Reference:**_

**Supported assets:** All fiat currency pairs.

===

* Retrieve exchange rates in **USD**, or another fiat currency, for all **Third Party Cryptos**, such as BBTC, ETH, ADA etc. supported by Afreum Ecosystem, filtered by the script attributes:

_**<script type="text/javascript" src="https://api.afreum.com/rates/rates_crypto.js" data-api_key="A2B6169C-7B45-4C23-9FCB-1493EB9BB9A8" data-crypto="BTC" data-currency="USD"></script>**_

**data-api_key:** The **https://coinapi.io/** crypto exchange rate API key. You should replace the one in the code example with your own.

**data-crypto:** The cryptocurrency for which to calculate the exchange rate. E.g. BTC, ETH or XLM.

**data-currency** The fiat currency in which to calculate the exchange rate. E.g. USD, EUR or HKD.

_**Reference:**_

**Supported assets:** https://api.afreum.com/tokens/afr_token_stable.json; All fiat currency pairs.


**NOTE:** Use these scripts only for UI display purposes. To calculate exchange rates for trasactions please use the universal rates APIs listed below under **API QUERY LINKS: EXCHANGE RATES**. In addition, Afreum uses 7 decimal places for final exchange rates used in Stellar blockchain transactions. Developers should use 7 decimal places for exchange rates and token amounts prior to sending transactions to the Stellar blockchain.

     

# API QUERY LINKS: JSON

In addition to the immutable **IPFS JSON** files that can be called remotely by developers and manipulated locally or on the server, Afreum also hosts a number of URLs that can be queried via URL parameters to return filtered JSON results. These include:

**1. Token Query URL** https://afreum.com/ice/sites/app/api/tokens.cfm

**USAGE**
Calling the Token Query URL directly returns all the tokens listed in afr_token_all.json (as shown here: https://ipfs.io/ipfs/QmSJWA8ht58PPnZjmLRjLHmChseYNmota7TVA18N6GgQvL), namely the flexible Afreum tokens, including AFR, AFRX and flexible country tokens such as ANGN.

URL parameters are: 

* **json=[]:** value is one of the json filenames without the .json extension, namely **afr_token_all, afr_token_flexible, afr_token_stable, afr_token_other**
Calling the Token Query URL with the url parameter **json=** will return all the tokens listed in that JSON file. E.g. **https://afreum.com/ice/sites/app/api/tokens.cfm?json=afr_token_stable** (without the .json extension) will return all Afreum stable country tokens, which are backed by USDC.

* **token=[]:** value is a comma-separated list of valid Afreum tokens, or supported third party tokens
Calling the Token Query URL with the url parameter **token=ANGN,AKES** will return data for the tokens in your comma-separated list.

* **issuer=[]:** value is the 56 character Stellar address of the token issuer. 
Calling the Token Query URL with the url parameter **issuer=GBX6YI45VU7WNAAKA3RBFDR3I3UKNFHTJPQ5F6KOOKSGYIAM4TRQN54W** will return data for the tokens issued by that issuer, in this case the AFR token.

* **domain=[]:** value is the domain name of the token issuer. For Afreum tokens these are **afreum.com or afreum.net**
Calling the Token Query URL with the url parameter **domain=afreum.com** will return data for the tokens issued by that domain.

* **fields=[]:** value is a comma-separated list of fields you would like to return in the JSON results. Accepted values are **id,token,issuer,domain,description,is_main,is_governance,is_country_token,is_africa,DTI,DTI_Long_Name,logo**
Calling the Token Query URL with the url parameter **fields=token,issuer,domain,logo** will return data containing only the JSON fields specified in your comma separated list.

* **sort=[]:** value is how you would like the JSON results to be sorted, in ascending order only. Accepted values are **id (default),token,is_main,is_native** Calling the Token Query URL with the url parameter **sort=token** will return data sorted by the field specified ascending.

* **is_africa=[]:** value is a boolean (either 1 or 0, 1 will return all African country tokens and 0 will return all non-African country tokens)
Calling the Token Query URL with the url parameter **is_africa=1** will return data for the African country tokens.

* **is_main=[]:** value is a boolean (either 1 or 0, 1 will return the AFR token, 0 will return non-AFR tokens; only useful for querying afr_token_all.json and afr_token_flexible.json)
Calling the Token Query URL with the url parameter **is_main=1** will return data for the AFR token.

* **is_governance=[]:** value is a boolean (either 1 or 0, 1 will return the AFRX token, 0 will return non-AFRX tokens; only useful for querying afr_token_all.json and afr_token_flexible.json)
Calling the Token Query URL with the url parameter **is_governance=1** will return data for the AFRX token.

* **is_country_token=[]:** value is a boolean (either 1 or 0, 1 will return country tokens, 0 will return non-country tokens such as AFR and AFRX)
Calling the Token Query URL with the url parameter **is_country_token=1** will return data for the Afreum country tokens. These tokens may be Afreum flexible tokens, Afreum stable tokens, or third party tokens.

* **is_native=[]:** value is a boolean (either 1 or 0, 1 will return the XLM token, 0 will return non-XLM tokens; only useful for querying afr_token_other.json)
Calling the Token Query URL with the url parameter **is_native=1** will return data for the XLM token.


**2. Countries Query URL** https://afreum.com/ice/sites/app/api/countries.cfm

**USAGE**
Calling the Countries Query URL directly returns all the countries supported by the Afreum Ecosystem as shown here: **https://api.afreum.com/geo/afr_country.json**.

URL parameters are: 

* **id=[]:** value is the id of the country as indicated in the JSON file.

* **iso_2=[]:** value is the ISO 2 country code of a specific country. Calling the Countries Query URL with the url parameter **iso_2=CN** will return data for China.

* **iso_3=[]:** value is the ISO 3 country code of a specific country. Calling the Countries Query URL with the url parameter **iso_3=CHN** will return data for China.

* **objectid=[]:** value is the objectid of the country as indicated in the JSON file.

* **contobjectid=[]:** value is the continent objectid of the country as indicated in the JSON file.

* **is_africa=[]:** value is a boolean indicating whether to retrieve only African countries.
Calling the Countries Query URL with the url parameter **is_africa=1** will return data for African countries.

* **fields=[]:** value is a comma-separated list of fields you would like to return in the JSON results. Accepted values can be found here: **https://api.afreum.com/geo/afr_country.json** .

* **sort=[]:** value is how you would like the JSON results to be sorted, in ascending order only. Calling the Countries Query URL with the url parameter **sort=name** will return data sorted by the field specified ascending.


**3. Provinces Query URL** https://afreum.com/ice/sites/app/api/provinces.cfm

**USAGE**
Calling the Provinces Query URL directly returns all the provinces supported by the Afreum Ecosystem as shown here: **https://api.afreum.com/geo/afr_state_province.json**.

URL parameters are: 

* **id=[]:** value is the id of the country as indicated in the JSON file.

* **country_code=[]:** value is the ISO 2 country code of a specific country. Calling the Provinces Query URL with the url parameter **country_code=CN** will return data for China.

* **iso_3=[]:** value is the ISO 3 country code of a specific country. Calling the Countries Query URL with the url parameter **iso_3=CHN** will return data for all the provinces in China.

* **objectid=[]:** value is the objectid of the province as indicated in the JSON file.

* **fields=[]:** value is a comma-separated list of fields you would like to return in the JSON results. Accepted values can be found here: **https://api.afreum.com/geo/afr_state_province.json** .

* **sort=[]:** value is how you would like the JSON results to be sorted, in ascending order only. Calling the Provinces Query URL with the url parameter **sort=Subdivision_Name** will return data sorted by the names of the the provinces ascending.


**4. Cities Query URL** https://afreum.com/ice/sites/app/api/cities.cfm

**USAGE**
Calling the Cities Query URL directly without URL parameters does not return any data due to the size of the cities JSON file. Typcially you would query the file **https://api.afreum.com/geo/afr_city.json** (several hundred megabytes) with URL parameters.

URL parameters are: 

* **countryobjectid=[]:** value is the objectid of the country as indicated in the JSON file.

* **objectid=[]:** value is the objectid of a specific country whose provinces you wish to retrieve. 

* **fields=[]:** value is a comma-separated list of fields you would like to return in the JSON results. Accepted values are countryobjectid, and objectid.

* **sort=[]:** value is how you would like the JSON results to be sorted, in ascending order only. Calling the Cities Query URL with the url parameter **sort=name** will return data sorted by the names of the the provinces ascending.



# API QUERY LINKS: EXCHANGE RATES

Please refer to the rates-api repo:
