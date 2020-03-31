# urlshort
It *Shortened the  large Url and generate the short url* which is store in database(MongoDb) by using base encoding/decoding as our bijective function, specifically base58. 
### We will be converting a unique integer ID (which is in base10) to it's equivalent in base58. 

```123456789abcdefghijkmnopqrstuvwxyzABCDEFGHJKLMNPQRSTUVWXYZ```
+ It is just the numbers 1-9, a-z, and A-Z, giving us a total of 58 characters, hence the 58 in base58. We are excluding 0, l, O to avoid confusion when sharing the URL over the phone or copying it manually.

## How to Run

- checkout the branch 
- Install MongoDB
- create db named *url_shortener*

