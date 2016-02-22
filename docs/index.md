# Global





* * *

## Class: Eliter
Make a new instance of Eliter and starts listening port


## Class: Eliter
Make a new instance of Eliter and starts listening port

**config**:  , Get config value
### Eliter.start(port) 

Start listening.

**Parameters**

**port**: `Number`, Port to listen


### Eliter.route(route_string, handler) 

Add new route

**Parameters**

**route_string**: `String | Array`, String of uri or an array contains uris

**handler**: `Generator`, Route handler

**Returns**: `void`

### Eliter.decor(deco) 

Add a decoration.

**Parameters**

**deco**: `function`, function with a `Connection` param

**Returns**: `void`



* * *









