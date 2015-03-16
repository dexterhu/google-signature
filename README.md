node-google-signature
====================
Generate a HMAC-SHA1 signature for "Google Maps API for Business" in node.js



Generate a signature from a private key and a string:


     var signature = require('node-google-signature');

     var key    = '-2qtbstr8='       // safe for the web modified base64 format
     var string = '/maps/api/etc..'  // The URL string to sign

     signature.generate(key, string, function(hash){
            console.log(hash) // { signature : 'me50L1BneaefWlbvb_XpsaIclo' }
     })



### URL Signing Debugger

https://m4b-url-signer.appspot.com/
=======
# google-signature
