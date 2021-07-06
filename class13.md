# LOCAL STORAGE 
## INTRODUCING HTML5 STORAGE
* is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards.

* The localStorage and sessionStorage properties allow to save key/value pairs in a web browser.


* The localStorage object saves the data without an expiration date. The data will not be deleted when the browser is closed and will be available anytime you screen the page again.

* localStorage is similar to sessionStorage, except that while localStorage data has no expiration time, sessionStorage data gets cleared when the page session ends.

 

* In all current browsers, localStorage seems to return a different object for each file: URL. In other words, each file: URL seems to have its own unique local-storage area. But there are no guarantees about that behavior, so you shouldn’t rely on it because, as mentioned above, the requirements for file: URLs remain undefined. So it’s possible that browsers may change their file: URL handling for localStorage at any time. In fact, some browsers have changed their handling for it over time.
## Syntax

        * window.localStorage
Syntax for SAVING data to localStorage:

localStorage.setItem("key", "value");
Syntax for READING data from localStorage:

    var lastname = localStorage.getItem("key");
Syntax for REMOVING data from localStorage:

    localStorage.removeItem("key");

## USING HTML5 STORAGE
* HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

 *      interface Storage {
             getter any getItem(in DOMString key);
             setter creator void setItem(in DOMString key, in any data);
                  };

* Calling setItem() with a named key that already exists will silently overwrite the previous value. Calling getItem() with a non-existent key will return null rather than throw an exception.

* Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods, you can simply use square brackets.                  

## TRACKING CHANGES TO THE HTML5 STORAGE AREA
* If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.