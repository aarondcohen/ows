	GET  /account
	POST /account
#	POST /account/activate
#	POST /account/verify
	DEL  /account/:account_key
	GET  /account/:account_key
	POST /account/:account_key/deactivate
	POST /account/:account_key/reactivate
	GET  /account/:account_key/credential
	DEL  /account/:account_key/credential/:credential_type
	PUT  /account/:account_key/credential/:credential_type
	GET  /account/:account_key/identity
	DEL  /account/:account_key/identity/:identity_type
	PUT  /account/:account_key/identity/:identity_type
