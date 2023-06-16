# API
The Afreum API is a collection of publically available files that allow anyone, including the Afreum development team, to build apps and services that leverarge the Afreum Ecosystem, and the Stellar blockchain on which it runs. The goal is for the vast majority of the files to be immutable, and available to anyone who wants to use or share them. 

# Tokens
The Tokens API consists of a number of JSON files hosted on the InterPlanetary File System (IPFS) and a number of URLs that are queried using URL parameters and returning JSON output. Here are descriptions and links to the various files:

# All Afreum Tokens

**File Name:** afr_token_all.json

**Unique Content Identifier (CID):** QmSJWA8ht58PPnZjmLRjLHmChseYNmota7TVA18N6GgQvL

**IPFS Link:** https://ipfs.io/ipfs/QmSJWA8ht58PPnZjmLRjLHmChseYNmota7TVA18N6GgQvL

**Afreum Link:** https://api.afreum.com/tokens/afr_token_all.json

This json file returns usefule data on all 314 Afreum ecosytem tokens, including AFR, AFRX, Afreum flexible country tokens (starting with 'A') and USDC-backed Afreum stable country tokens (starting with 'S'). Returned fields include: 

**id:** (used for sorting) 

**token:** the token symbol

**issuer:** the issuing Stellar blockchain address

**domain:** the issuing domain name (afreum.com for flexible tokens or afreum.net for stable tokens)

**description:** a short description of the token

**is_main:** a boolean indicating whether the token is the main token of the Afreum ecosystem, namely AFR

**is_governance:** a boolean indicating whether the token is the governance token of the Afreum ecosystem, namely AFRX

**is_country_token:** a boolean indicating whether the token is linked to a country in the Afreum ecosystem, namely tokens such as AAED or SKES

**is_africa:** a boolean indicating whether the token is linked to an African country in the Afreum ecosystem, namely tokens such as ANGN or SNGN 

**DTI:** the ISO 24165 digital token identifier of the token

**DTI Long Name:** the name of token linked to the digital token identifier

**logo:** an IPFS link to the logo of the token

**USAGE:** 
Developers may call this file directly to retrieve all Afreum tokens, excluding third party tokens (such as XLM, USDC) supported by the Afreum ecosystem.


# Flexible Afreum Tokens

**File Name:** afr_token_flexible.json

**Unique Content Identifier (CID):** Qmdn6i61sZ7ARp3FEgLehxKH4emwqFEccbNJsehABcT9ws

**IPFS Link:** https://ipfs.io/ipfs/Qmdn6i61sZ7ARp3FEgLehxKH4emwqFEccbNJsehABcT9ws

**Afreum Link:** https://api.afreum.com/tokens/afr_token_flexible.json

This json file returns usefule data on 158 Afreum ecosytem tokens, including AFR, AFRX, and flexible country tokens (starting with 'A'). The file does not include USDC-backed stable country tokens (starting with 'S'). Returned fields include: 

**id:** (used for sorting) 

**token:** the token symbol

**issuer:** the issuing Stellar blockchain address

**domain:** the issuing domain name (afreum.com for flexible tokens or afreum.net for stable tokens)

**description:** a short description of the token

**is_main:** a boolean indicating whether the token is the main token of the Afreum ecosystem, namely AFR

**is_governance:** a boolean indicating whether the token is the governance token of the Afreum ecosystem, namely AFRX

**is_country_token:** a boolean indicating whether the token is linked to a country in the Afreum ecosystem, namely tokens such as AAED or ANGN

**is_africa:** a boolean indicating whether the token is linked to an African country in the Afreum ecosystem, namely tokens such as ANGN or SNGN 

**DTI:** the ISO 24165 digital token identifier of the token

**DTI Long Name:** the name of token linked to the digital token identifier

**logo:** an IPFS link to the logo of the token

**USAGE:** 
Developers may call this file directly to retrieve all Afreum flexible tokens, including AFR, AFRX, and Afreum flexible country tokens, and excluding Afreum stable country tokens (backed by USDC) and third party tokens (such as XLM, USDC) supported by the Afreum ecosystem.


# Stable Afreum Tokens

**File Name:** afr_token_stable.json

**Unique Content Identifier (CID):** Qma66ovk8HGqsjv8R1Jod6aTr7bSfM5UFgqr3LsAR4QGFR

**IPFS Link:** https://ipfs.io/ipfs/Qma66ovk8HGqsjv8R1Jod6aTr7bSfM5UFgqr3LsAR4QGFR

**Afreum Link:** https://api.afreum.com/tokens/afr_token_stable.json

This json file returns usefule data on 156 Afreum ecosytem stable country tokens, which are backed by, and redeemable for, USDC. This file includes only USDC-backed stable country tokens (starting with 'S'). Returned fields include: 

**id:** (used for sorting) 

**token:** the token symbol

**issuer:** the issuing Stellar blockchain address

**domain:** the issuing domain name (afreum.com for flexible tokens or afreum.net for stable tokens)

**description:** a short description of the token

**is_country_token:** a boolean indicating whether the token is linked to a country in the Afreum ecosystem, namely tokens such as SAED or SNGN

**is_africa:** a boolean indicating whether the token is linked to an African country in the Afreum ecosystem, namely tokens such as SNGN or SNGN 

**DTI:** the ISO 24165 digital token identifier of the token

**DTI Long Name:** the name of token linked to the digital token identifier

**logo:** an IPFS link to the logo of the token

**USAGE:** 
Developers may call this file directly to retrieve all Afreum stable country tokens, excluding AFR, AFRX, Afreum flexible country tokens, and third party tokens (such as XLM, USDC) supported by the Afreum ecosystem.


# Other Tokens

**File Name:** afr_token_other.json

**Unique Content Identifier (CID):** QmWT69RfRc3n184sS56qEpvuR6Jqp2bgh8VqZmt2HvYGx6

**IPFS Link:** https://ipfs.io/ipfs/QmWT69RfRc3n184sS56qEpvuR6Jqp2bgh8VqZmt2HvYGx6

**Afreum Link:** https://api.afreum.com/tokens/afr_token_other.json

This json file returns usefule data on third-party tokens supported by Afreum ecosytem. These include the native Stellar blockchain token XLM, USDC, and other tokens. Returned fields include: 

**id:** (used for sorting) 

**token:** the token symbol

**issuer:** the issuing Stellar blockchain address

**domain:** the issuing domain name (afreum.com for flexible tokens or afreum.net for stable tokens)

**description:** a short description of the token

**is_native:** a boolean indicating whether the token is the native token of the Stellar blockchain, namely XLM

**is_country_token:** a boolean indicating whether the token is linked to a country supported in the Afreum ecosystem, namely fiat-backed Stellar anchor-issued tokens

**DTI:** the ISO 24165 digital token identifier of the third-party token, if any

**DTI Long Name:** the name of token linked to the digital token identifier

**logo:** an IPFS link to the logo of the token

**USAGE:** 
Developers may call this file directly to retrieve all third-party issued tokens supported by the Afreum Ecosystem. This includes tokens such as XLM, USDC etc.


# JSON QUERY LINKS

In addition to these files that can be called remotely by developers and manipulated locally, Afreum also hosts a number of URLs that can be queried via URL parameters to return filtered JSON results. These include:

**Token Query URL** https://afreum.com/ice/sites/app/api/tokens.cfm

**USAGE**
Calling the Token Query URL directly returns all the tokens listed in afr_token_all.json (as shown here: https://ipfs.io/ipfs/QmSJWA8ht58PPnZjmLRjLHmChseYNmota7TVA18N6GgQvL), namely the flexible Afreum tokens, including AFR, AFRX and flexible country tokens such as ANGN.

URL parameters are: 

**json=[]:** value is one of the json filenames without the .json extension, namely **afr_token_all, afr_token_flexible, afr_token_stable, afr_token_other**
Calling the Token Query URL with the url parameter **json=** will return all the tokens listed in that JSON file. E.g. **https://afreum.com/ice/sites/app/api/tokens.cfm?json=afr_token_stable** (without the .json extension) will return all Afreum stable country tokens, which are backed by USDC.

**token=[]:** value is a comma-separated list of valid Afreum tokens, or supported third party tokens
Calling the Token Query URL with the url parameter **token=ANGN,AKES** will return data for the tokens in your comma-separated list.


**issuer=[]:** value is the 56 character Stellar address of the token issuer. 
Calling the Token Query URL with the url parameter **issuer=GBX6YI45VU7WNAAKA3RBFDR3I3UKNFHTJPQ5F6KOOKSGYIAM4TRQN54W** will return data for the tokens issued by that issuer, in this case the AFR token.

**domain=[]:** value is the domain name of the token issuer. For Afreum tokens these are **afreum.com or afreum.net**
Calling the Token Query URL with the url parameter **domain=afreum.com** will return data for the tokens issued by that domain.

**fields=[]:** value is a comma-separated list of fields you would like to return in the JSON results. Accepted values are **id,token,issuer,domain,description,is_main,is_governance,is_country_token,is_africa,DTI,DTI_Long_Name,logo**
Calling the Token Query URL with the url parameter **fields=token,issuer,domain,logo** will return data containing only the JSON fields specified in your comma separated list.

**sort=[]:** value is how you would like the JSON results to be sorted, in ascending order only. Accepted values are **id (default),token,is_main,is_native** Calling the Token Query URL with the url parameter **sort=token** will return data sorted by the field specified ascending.

**is_africa=[]:** value is a boolean (either 1 or 0, 1 will return all African country tokens and 0 will return all non-African country tokens)
Calling the Token Query URL with the url parameter **is_africa=1** will return data for the African country tokens.

**is_main=[]:** value is a boolean (either 1 or 0, 1 will return the AFR token, 0 will return non-AFR tokens; only useful for querying afr_token_all.json and afr_token_flexible.json)
Calling the Token Query URL with the url parameter **is_main=1** will return data for the AFR token.

**is_governance=[]:** value is a boolean (either 1 or 0, 1 will return the AFRX token, 0 will return non-AFRX tokens; only useful for querying afr_token_all.json and afr_token_flexible.json)
Calling the Token Query URL with the url parameter **is_governance=1** will return data for the AFRX token.

**is_country_token=[]:** value is a boolean (either 1 or 0, 1 will return country tokens, 0 will return non-country tokens such as AFR and AFRX)
Calling the Token Query URL with the url parameter **is_country_token=1** will return data for the Afreum country tokens. These tokens may be Afreum flexible tokens, Afreum stable tokens, or third party tokens.

**is_native=[]:** value is a boolean (either 1 or 0, 1 will return the XLM token, 0 will return non-XLM tokens; only useful for querying afr_token_other.json)
Calling the Token Query URL with the url parameter **is_native=1** will return data for the XLM token.
