# API
The Afreum API is a collection of publically available **JSON** files stored on **IPFS**, HTML and Javascript files , and **API** endpoints that return **JSON** or specific values. Anyone, including various teams developing for the **Afreum Ecosystem**, can build apps and services that leverage the Afreum Ecosystem, and the Stellar blockchain on which it runs. The goal is for the **JSON** files to be immutable, and accessible to both internal and external developers. Wherever possible, developers should use the IPFS hosted immutable files in their apps to ensure availability and consistency, but additional functionality may be available via the API endpoints. A general rule of thumb is to use **IPFS Links** to develop around a fixed dataset or to use the **Afreum Link** if you want your app to inherit future Afreum updates to the datasets. Files hosted on IPFS can be accessed here: **https://api.afreum.com**

# Tokens
The **Tokens API** consists of a number of **JSON** files, as well **HTML** files  that read **Javascript** files to output data. Files hosted on the **InterPlanetary File System (IPFS)**. There are also a number of **URL** endpoints that are queried using URL parameters and return JSON output, or in the case of rates, numeric values. Here are descriptions and links to the various static JSON files:

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

**IPFS Link:** https://ipfs.io/ipfs/Qmdn6i61sZ7ARp3FEgLehxKH4emwqFEccbNJsehABcT9ws _[Recommend using an IPFS-capable browser such as Brave to view. Other browsers may flag IPFS files as dangerous content.]_

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

**IPFS Link:** https://ipfs.io/ipfs/Qma66ovk8HGqsjv8R1Jod6aTr7bSfM5UFgqr3LsAR4QGFR _[Recommend using an IPFS-capable browser such as Brave to view. Other browsers may flag IPFS files as dangerous content.]_

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

**IPFS Link:** https://ipfs.io/ipfs/QmcPSLBnyiukw6go2VwTPtiXCHW9eYuGi6ezRstJuDhfiF _[Recommend using an IPFS-capable browser such as Brave to view. Other browsers may flag IPFS files as dangerous content.]_

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

**IPFS Link:** https://ipfs.io/ipfs/QmRzh5BLr78GcfnWdZ9MkUDf9jCZ1R2XsxFmJbPcsLhbsc _[Recommend using an IPFS-capable browser such as Brave to view. Other browsers may flag IPFS files as dangerous content.]_

**Afreum Link:** https://api.afreum.com/tokens/afr_token_external.json

This json file returns useful data on third-party non-Stellar assets supported by Afreum Ecosytem. These include whitelisted tokens such as XLM (externally quoted), BTC, ETH, ADA, LTC, DASH, BUSD, USDT and USDC. It is important to note that with the exception of XLM, all other tokens exist on chains other than Stellar. Returned fields include: 

* **id:** (used for sorting) 

* **token:** the token symbol

* **logo:** an IPFS link to the logo of the token

**USAGE:** 
Developers may call this file directly to retrieve all third-party tokens (external to Stellar with the exception of XLM) supported by the Afreum Ecosystem.


# IMMUTABLE SCRIPTS: JAVASCRIPT

Afreum also provides a number of immutable **HTML** files that call immutable **Javascript** files hosted on **IPFS**. Developers can "fetch" these HTML files on the client/server side to retrieve token, geolocation, rates, and other other data. Alternatively, developers can embed the **<script>** tags in the HTML files directly in their own pages and filter output based on URL parameters. The scripts generally write results to the Javascript console, and developers can utilize the variables in their own code. The following scripts are available:



**Token Scripts**

* Retrieve all Afreum tokens issued on Stellar, including AFR, AFRX, flexible country tokens and stable country tokens, filterable by URL parameters:

_Afreum Link:_

**DATA SOURCE:** https://api.afreum.com/tokens/afr_token_all.json

_**<script type="text/javascript" src="https://api.afreum.com/tokens/tokens_all.js">**_

**HTML:** https://api.afreum.com/tokens/tokens_all.html (**URL PARAMS:** id,token,issuer,domain,is_main,is_governance,is_country_token,is_africa,is_stable,DTI)

_IPFS Link:_

**DATA SOURCE:** https://ipfs.io/ipfs/QmR6HWa5BExBLHFh9xzkyMqnyySgfDUY3MquQPRX2pTxQ1

_**<script type="text/javascript" src="https://ipfs.io/ipfs/Qmeh8Ttexz5oZrjnPbh5qvhipm93Yiw7swrvEUDLzpBrMH">**_

**HTML:** https://ipfs.io/ipfs/QmUkxHeLFpcckFMPkk9ZDZvmDmxiwrakbe8Az1WnS8V5EX (**URL PARAMS:** id,token,issuer,domain,is_main,is_governance,is_country_token,is_africa,is_stable,DTI)



* Retrieve all flexible Afreum tokens issued on Stellar, including AFR, AFRX, and flexible country tokens, filterable by URL parameters:

_Afreum Link:_

**DATA SOURCE:** https://api.afreum.com/tokens/afr_token_flexible.json

_**<script type="text/javascript" src="https://api.afreum.com/tokens/tokens_flexible.js">**_

**HTML:** https://api.afreum.com/tokens/tokens_flexible.html (**URL PARAMS:** id,token,issuer,domain,is_main,is_governance,is_country_token,is_africa,DTI)

_IPFS Link:_

**DATA SOURCE:** https://ipfs.io/ipfs/Qmdn6i61sZ7ARp3FEgLehxKH4emwqFEccbNJsehABcT9ws

_**<script type="text/javascript" src="https://ipfs.io/ipfs/QmS8diNTQYxuf9brPnArHcvoBC3erXCyBf1usJfF2eGdMt">**_

**HTML:** https://ipfs.io/ipfs/QmWyf6F2A4QZX2dtKsWLuiojuSHPiDS6XVLd54FQuYEXaU (**URL PARAMS:** id,token,issuer,domain,is_main,is_governance,is_country_token,is_africa,DTI)



* Retrieve all stable Afreum tokens issued on Stellar, including SNGN, SKES, and SZAR, filterable by URL parameters:

_Afreum Link:_

**DATA SOURCE:** https://api.afreum.com/tokens/afr_token_stable.json

_**<script type="text/javascript" src="https://api.afreum.com/tokens/tokens_stable.js">**_

**HTML:** https://api.afreum.com/tokens/tokens_stable.html (**URL PARAMS:** id,token,issuer,domain,is_africa,DTI)

_IPFS Link:_

**DATA SOURCE:** https://api.afreum.com/tokens/afr_token_stable.json

_**<script type="text/javascript" src="https://ipfs.io/ipfs/QmU2y1WSqKcw3B5YZPqXoqi5HxrdBWHKtKgrX39bV5Nyva">**_

**HTML:** https://ipfs.io/ipfs/Qmd4F6hUFHT23EMPAmh1rTTpK4muRG8ys4RcSeKdN3haAM (**URL PARAMS:** id,token,issuer,domain,is_africa,DTI)



* Retrieve all non-Afreum tokens issued on Stellar, and supported by the Afreum Ecosystem, filterable by URL parameters:

_Afreum Link:_

**DATA SOURCE:** https://api.afreum.com/tokens/tokens_other.html 

_**<script type="text/javascript" src="https://api.afreum.com/tokens/tokens_other.js"></script>**_

**HTML:** https://api.afreum.com/tokens/tokens_other.html (**URL PARAMS:** id,token,issuer,domain,is_native,is_africa,is_country_token,DTI)

_IPFS Link:_

**DATA SOURCE:** https://ipfs.io/ipfs/QmcPSLBnyiukw6go2VwTPtiXCHW9eYuGi6ezRstJuDhfiF

_**<script type="text/javascript" src="https://ipfs.io/ipfs/QmXDSnzqL2LcXJYNopqeKX4w2noZRhgkpX6m64MaWMv988"></script>**_

**HTML:** https://api.afreum.com/tokens/tokens_other.html (**URL PARAMS:** id,token,issuer,domain,is_native,is_africa,is_country_token,DTI)




* Retrieve all external coins, plus XLM, supported by the Afreum Ecosystem, filterable by URL parameters:

_Afreum Link:_

**DATA SOURCE:** https://api.afreum.com/tokens/tokens_external.html

_**<script type="text/javascript" src="https://api.afreum.com/tokens/tokens_external.js"></script>**_

**HTML:** https://api.afreum.com/tokens/tokens_external.html (**URL PARAMS:** id,token)

_IPFS Link:_

**DATA SOURCE:** https://ipfs.io/ipfs/QmRzh5BLr78GcfnWdZ9MkUDf9jCZ1R2XsxFmJbPcsLhbsc

_**<script type="text/javascript" src="https://ipfs.io/ipfs/QmZt22xgJJvsVuF8qStFvao7dCQLwXc6XgX1R4VvBv3Uaj"></script>**_

**HTML:** https://cid.ipfs.tech/#Qme5LdapgKqLHUvZvtcVubUnywyFYbZydqL6UF3JvLJaJ2 (**URL PARAMS:** id,token)




**Geolocation Scripts**

Afreum is a global ecosystem so we also provide immutable **JSON**, **Javascript** and **HTML** files, providing useful geo data on countries, provinces, cities and so on. The following are useful scripts for this purpose:

* Retrieve all **Continents** supported by Afreum Ecosystem, filterable by URL parameters:

_Afreum Link:_

**DATA SOURCE:** https://api.afreum.com/geo/afr_continent.json

_**<script type="text/javascript" src="https://api.afreum.com/geo/continents.js"></script>**_

**HTML:** https://api.afreum.com/geo/continents.html (**URL PARAMS:** objectId,code)

_IPFS Link:_

**DATA SOURCE:** https://ipfs.io/ipfs/QmeFU4y1wx3SqGEdLmW6ybY7p4d5y4MeTxEuqeJtYo9Ptg

_**<script type="text/javascript" src="https://ipfs.io/ipfs/QmVDAFsbC8jHKqfQaDD9CAYSXC2zAx6PSfLE3rp2HdXYqQ"></script>**_

**HTML:** https://ipfs.io/ipfs/QmdDK5bongkUbKhktE9qCoVH7PZC7ZCxfvLo9RcWEDwuEQ (**URL PARAMS:** objectId,code)



* Retrieve all **Countries** supported by Afreum Ecosystem, filterable by URL parameters:

_Afreum Link:_

**DATA SOURCE:** https://api.afreum.com/geo/afr_country.json

_**<script type="text/javascript" src="https://api.afreum.com/geo/countries.js"></script>**_

**HTML:** https://api.afreum.com/geo/countries.html (**URL PARAMS:** id,iso_2,iso_3,objectid,contobjectid,is_africa)

_IPFS Link:_

**DATA SOURCE:** https://ipfs.io/ipfs/QmQyooayWaQepHBJrEVyjd3iqr1qCZ6AaAVGVnrjSam4ym

_**<script type="text/javascript" src="https://ipfs.io/ipfs/QmY98JvWQ6jQaa7ZEks9USmJi52KvSSkwkJfL1CFJtkRat"></script>**_

**HTML:** https://ipfs.io/ipfs/QmRz3kmzK8tcTatkT2gsxmi34PCiSbLFViNnhDuG9sUhvy (**URL PARAMS:** id,iso_2,iso_3,objectid,contobjectid,is_africa)



* Retrieve all **Provinces** supported by Afreum Ecosystem, filterable by URL parameters:

_Afreum Link:_

**DATA SOURCE:** https://api.afreum.com/geo/afr_state_province.json

_**<script type="text/javascript" src="https://api.afreum.com/geo/provinces.js"></script>**_

**HTML:** https://api.afreum.com/geo/provinces.html (**URL PARAMS:** Country_Code, objectId)

_IPFS Link:_

**DATA SOURCE:** https://ipfs.io/ipfs/QmYpFDg3t8UydEZYqvYBuqvkMXnXwQN9cQ8y7J1xb2CVkz

_**<script type="text/javascript" src="https://ipfs.io/ipfs/QmfTaKFXJrQLFKvznUYBPBnNQHPC9MsfGA16Ti9XNdGXW3"></script>**_

**HTML:** https://ipfs.io/ipfs/QmdbLKX3yxjAJJuz2xD7kNSRVz4tdm3mo6tQ344FvRK21L (**URL PARAMS:** Country_Code, objectId)



* Retrieve all **Cities** supported by Afreum Ecosystem, filterable by URL parameters. Due to the size of the Cities JSON file, it is recommended that the data files are downloaded to a server and imported into a database such as Mongo DB.

_Afreum Link:_

**DATA SOURCE:** https://api.afreum.com/geo/afr_city.json

_IPFS Link:_

**DATA SOURCE:** https://ipfs.io/ipfs/QmaGaJL1hqjv48KegSfDZkxZ5VjFmsXkiokzdiRdnigQiv 




**Exchange Rate Scripts**

Afreum provides immutable **Javascript** files that facilitate the calculation of exchange rates between all tokens and fiat currencies supported by the Afreum Ecosystem. Please note that these scripts use Stellar Horizon APIs and/or third party exchange rate APIs. Afreum makes no warranties as to the accuracy or consistency of the exchange rates returned by these scripts. It is the responsibility of the developer to check the accuracy of the exchange rates, and to implement the appropriate error checks to ensure smooth operation of their apps. In some cases, developers are required to obtain their own API keys from third party exchange rate providers to use the scripts and in limited scenarios an API ACCESS KEY may be required. **IMPORTANT:** Rates returned are for UI display only. For actual production transactions, please use the universal exchange rates endpoints listed below under **API QUERY LINKS: EXCHANGE RATES**


* Retrieve exchange rates between **Stellar Assets** supported by Afreum Ecosystem, including AFR, AFRX, Afreum flexible country tokens, and other Stellar assets such as XLM, and USDC, filterable by URL parameters:

_Afreum Link:_

_**<script type="text/javascript" src="https://api.afreum.com/rates/rates_stellar.js"></script>**_

**HTML:** https://api.afreum.com/rates/rates_stellar.html

_IPFS Link:_

_**<script type="text/javascript" src="https://ipfs.io/ipfs/QmR59DjjqtQjkMB9UPtTMtrfZJgPzQ1nWqP2swEf39nVee"></script>**_

**HTML:** https://ipfs.io/ipfs/QmUdrEJ9LxQ67J2qGdr5BdMWX7CCQa7eejKWWKLPXNbKqu


_**URL Parameters:**_

**base_asset_code:** The Stellar asset code of the base asset (token) for which you want to retrieve an exchange rate in the counter asset.

**base_asset_type:** The Stellar blockchain asset type of the base asset. Usually 'credit_alphanum4' for non-XLM assets and 'native' for XLM.

**base_asset_issuer** The Stellar blockchain address of the base asset issuer or 'native' if base asset is XLM.

**counter_asset_code:** The Stellar asset code of the counter asset (token) in which you want to retrieve an exchange rate for the base asset.

**counter_asset_type:** The Stellar blockchain asset type of the counter asset. Usually 'credit_alphanum4' for non-XLM assets and 'native' for XLM.

**counter_asset_issuer** The Stellar blockchain address of the counter asset issuer or 'native' if counter asset is XLM.

_**Reference:**_

**Supported assets:** https://api.afreum.com/tokens/afr_token_flexible.json; https://api.afreum.com/tokens/afr_token_other.json  


===


* Retrieve exchange rates in **USD**, or another fiat currency, for all **Afreum Stable Country Tokens** (which are the same rates as the underlying fiat) supported by Afreum Ecosystem, filterable by URL parameters:

_Afreum Link:_

_**<script type="text/javascript" src="https://api.afreum.com/rates/rates_stable.js"></script>**_

**HTML:** https://api.afreum.com/rates/rates_stable.html

_IPFS Link:_

_**<script type="text/javascript" src="https://ipfs.io/ipfs/QmPGwYewB1gn9A5QCwmsANeCmYFYL4spJUmykumpQ24688"></script>**_

**HTML:** https://ipfs.io/ipfs/QmRtAhjimWZnCN74zN5g3AH9eF3P73LyS3xQzsfNAp2ShB


_**URL Parameters:**_

**api_key:** Get a free or paid API key from  **https://exchangerate-api.com/**.

**base_currency:** The fiat currency in which to calculate the exchange rate of the stable token. E.g. USD, EUR or HKD.

**stable_token** The stable token for which to calculate the exchange rate in fiat currency. E.g. SUSD, SEUR or SHKD.

_**Reference:**_

**Supported assets:** https://api.afreum.com/tokens/afr_token_stable.json; All fiat currencies.


===


* Retrieve exchange rates in **USD**, or another fiat currency, for all **Fiat Currencies** supported by Afreum Ecosystem, filterable by URL parameters:

_Afreum Link:_

_**<script type="text/javascript" src="https://api.afreum.com/rates/rates_fiat.js" data-api_key="9b14c10ebd44327b48c36b3d" data-base_currency="USD"  data-counter_currency="GBP"></script>**_

**HTML:** https://api.afreum.com/rates/rates_fiat.html

_IPFS Link:_

_**<script type="text/javascript" src="https://ipfs.io/ipfs/Qmc46qNPGApaMp3LRgPBg5yNJshT4CcK7GQUz5m7uswSmt"></script>**_

**HTML:** https://ipfs.io/ipfs/QmcqDawfrS6RagApEEH8ZHZZUrwRTDarJq9XU3AdMAHQfV


_**URL Parameters:**_

**api_key:** Get a free or paid API key from  **https://exchangerate-api.com/**.

**base_currency:** The fiat currency for which to calculate the exchange rate. E.g. USD, EUR or HKD.

**counter_currency** The fiat currency in which to calculate the exchange rate. E.g. USD, EUR or HKD.

_**Reference:**_

**Supported assets:** All fiat currency pairs.


===


* Retrieve exchange rates in **USD**, or another fiat currency, for all **Third Party Cryptos**, such as BBTC, ETH, ADA etc. supported by Afreum Ecosystem, filterable by URL parameters:

_Afreum Link:_

_**<script type="text/javascript" src="https://api.afreum.com/rates/rates_crypto.js"></script>**_

**HTML:** https://api.afreum.com/rates/rates_crypto.html

_IPFS Link:_

_**<script type="text/javascript" src="https://ipfs.io/ipfs/QmPgfFJqcSuP8hwdf2xgMKLtTS8BWjFtjrLX2FR9MzGvDc"></script>**_

**HTML:** https://ipfs.io/ipfs/QmQBgkUGvxFxDZCwFYfiZHQpiW8n6jac9QS6S6nx4SCpm8


_**URL Parameters:**_

**api_key:** Get a free or paid API key from **https://coinapi.io/**.

**crypto:** The cryptocurrency for which to calculate the exchange rate. E.g. BTC, ETH or XLM.

**fiat** The fiat currency in which to calculate the exchange rate. E.g. USD, EUR or HKD.

_**Reference:**_

**Supported assets:** https://api.afreum.com/tokens/afr_token_external.json; All fiat currency pairs.


**NOTE:** Use these HTML files and scripts only for development UI display purposes and use the APIs for production. To calculate exchange rates for trasactions please use the universal rates API (which can retrieve rates for ALL pairs) listed below under **API QUERY LINKS: EXCHANGE RATES**. In addition, Afreum uses 7 decimal places for final exchange rates used in Stellar blockchain transactions. Developers should use 7 decimal places for token amounts prior to sending transactions to the Stellar blockchain.

     

# API QUERY LINKS: JSON

In addition to the immutable **IPFS** files that can be called remotely by developers and manipulated locally or on the server, Afreum also hosts a number of endpoints that can be queried via URL parameters to return filtered JSON results. These include:

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

* **sort=[]:** value is how you would like the JSON results to be sorted, in ascending order only. Calling the Provinces Query URL with the url parameter **sort=Subdivision_Name** will return data sorted by the names of the provinces ascending.


**4. Continents Query URL** https://afreum.com/ice/sites/app/api/continents.cfm

**USAGE**
Calling the Continents Query URL directly returns all the continents supported by the Afreum Ecosystem as shown here: **https://api.afreum.com/geo/continent.json**.

URL parameters are: 

* **code=[]:** value is the 2-character code of a specific continent. Calling the Provinces Query URL with the url parameter **code=AF** will return data for Africa.

* **objectid=[]:** value is the objectid of the continent as indicated in the JSON file.

* **fields=[]:** value is a comma-separated list of fields you would like to return in the JSON results. Accepted values can be found here: **https://api.afreum.com/geo/afr_continent.json** .

* **sort=[]:** value is how you would like the JSON results to be sorted, in ascending order only. Calling the Continents Query URL with the url parameter **sort=name** will return data sorted by the names of the continents ascending.


**5. Cities Query URL** https://afreum.com/ice/sites/app/api/cities.cfm

**USAGE**
Calling the Cities Query URL directly without URL parameters does not return any data due to the size of the cities JSON file. Typcially you would query the file **https://api.afreum.com/geo/afr_city.json** (several hundred megabytes) with URL parameters.

URL parameters are: 

* **countryobjectid=[]:** value is the objectid of the country as indicated in the JSON file.

* **objectid=[]:** value is the objectid of a specific country whose provinces you wish to retrieve. 

* **fields=[]:** value is a comma-separated list of fields you would like to return in the JSON results. Accepted values are countryobjectid, and objectid.

* **sort=[]:** value is how you would like the JSON results to be sorted, in ascending order only. Calling the Cities Query URL with the url parameter **sort=name** will return data sorted by the names of the the provinces ascending.



# API QUERY LINKS: EXCHANGE RATES

Please refer to the rates-api repo: **https://github.com/Afreum/api-rates**
