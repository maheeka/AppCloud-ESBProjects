# ContainerAPI

This API will return the services (APIs and Proxy Services) in an ESB instance.

Sample response : 

{
	"urls": {
		"apis": [{
			"name": "ContainerAPI",
			"context": "/container/endpoints"
		}, {
			"name": "PlainAPI",
			"context": "/plain"
		}, {
			"name": "SalesforceAccountAPI",
			"context": "/account"
		}, {
			"name": "Test",
			"context": "/test"
		}],
		"proxies": [{
			"name": "SalesforceProxy",
			"wsdl": ["http://maheekas-macbook-pro-5.local:8290/services/SalesforceProxy?wsdl2", "http://maheekas-macbook-pro-5.local:8290/services/SalesforceProxy?wsdl"]
		}, {
			"name": "AuthProxy",
			"wsdl": ["http://maheekas-macbook-pro-5.local:8290/services/AuthProxy?wsdl2", "http://maheekas-macbook-pro-5.local:8290/services/AuthProxy?wsdl"]
		}]
	}
}
