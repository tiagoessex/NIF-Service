
Version: 0.0.1

# Description
* Given a NIF number, the service returns a json with a myriad of information about the entity connected with that nif.
* **Only portuguese NIFs** 


# Requirements
* Python 3.7.x


# Fields
* name
* morada
* codigo postal
* extensão codigo postal
* cidade
* data inicio de actividade
* actividade
* estado (activo?)
* cae
* email
* telefone
* website
* fax
* natureza (LDA, ...)
* capital
* denominacao do capital (£, €, $, ...)
* distrito
* concelho
* freguesia
* url racius
* url alias
* url portugalio


# Example

```python

import nifservice

try:
	result = getNifInfo(nif='xxxxxxxxxx', key='xxxxxxxxxxxxxxxxxxxx')
	print (result)
except Exception as e:
	print (e)

```

# Notes: 
* 1000 API calls per month, 100 / dia, 10 / hora, 1 / minuto, 1
* for more, credit is required: 0.01€ / credit
