# LOCAL STORAGE FOR WEB APPLICATIONS
> is one of the areas where native client applications have held an advantage over web applications.
>> the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state.These values may be stored in the registry, INI files, XML files, or some other place according to platform convention.

-  HTML5 STORAGE

> **HTML5 Storage** is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons.
>> so ,it’s a way for web pages to store named key/value pairs locally, within the client web browser

*check for HTML5 Storage*
- `function supports_html5_storage() {`
  `try {`
  `  return 'localStorage' in window && window['localStorage'] !== null;`
  `} catch (e) {`
   ` return false;`
 ` }`
`}`

- USING HTML5 STORAGE
**HTML5 Storage is based on named key/value pairs**
1. You store data based on a named key
2. Then you can retrieve that data with the same key. 
3. The named key is a string
4. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.
5. The data is actually stored as a string.
6. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.


- getter / setter : 
> Calling **setItem()** with a named key that already exists will silently overwrite the previous value. Calling **getItem()** with a non-existent key will return null rather than throw an exception.

- There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once)

> `interface Storage {`
  `deleter void removeItem(in DOMString key);`
  `void clear();`
`};`
Calling **removeItem()** with a non-existent key will do nothing.

- STORAGE EVENT OBJECT
1. key *string*
2. oldValue *any*
3. newValue *any*
4. url *string*

