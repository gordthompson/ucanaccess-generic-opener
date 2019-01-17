# ucanaccess-generic-opener

The simplest form of an "opener" class that allows [UCanAccess](http://ucanaccess.sourceforge.net/site.html) to open protected Access database files via [Jackcess Encrypt](https://jackcessencrypt.sourceforge.io/).

Sample JDBC connection URL:

```java
String connUrl = "jdbc:ucanaccess://C:/Users/Public/test/uls_test/protected.mdb" +
        ";jackcessOpener=com.gordthompson.ucanaccess.crypto.CryptCodecOpener";
```
