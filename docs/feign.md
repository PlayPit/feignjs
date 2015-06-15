# feign

Declarative Rest Client Api.



* * *

### feign.builder(promise) 

creates a feign-builder to build up a rest-client.

**Parameters**

**promise**: `boolean`, promise or callback api-style



### feign.client(feignClient) 

sets the client to be used for ajax-requests. 

**Parameters**

**feignClient**: `object`, a client that translates a feign-request to some thirdparty library



### feign.requestInterceptor(requestInterceptor) 

adds a request interceptor that will be called with the [request](#request), so it can be altered or logged

**Parameters**

**requestInterceptor**: `object`, an interceptor



### feign.target(apiDescription, baseUrl) 

crates the client based on the given api-description and baseUrl

**Parameters**

**apiDescription**: `object`, crates the client based on the given api-description and baseUrl

**baseUrl**: `string`, crates the client based on the given api-description and baseUrl




* * *







**Overview:** Internal types:
{
  baseUrl: 'http://localhost/',
  options: {method: 'GET', uri: '/bla'},
  parameters: {}
};
{
  raw: {},
  body: ...
};

