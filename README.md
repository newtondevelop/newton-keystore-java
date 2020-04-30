
# Newton keystore java 

Newton keystore java is newton SDK for Java and Android which is forked from [bitcoinj](https://github.com/bitcoinj/bitcoinj).

## Getting started

Add the relevant dependency to your project:

### Maven
Java 8:

```
<dependency>
  <groupId>org.newtondeveloper</groupId>
  <artifactId>newpay-keystore</artifactId>
  <version>0.0.1</version>
  <type>pom</type>
</dependency>
```

### Gradle
Java 8:
```
implementation 'org.newtondeveloper:newpay-keystore:0.0.1'
```

## Difference between bitcoinj

Changed [Bitcoin seed](https://github.com/bitcoinj/bitcoinj/blob/master/core/src/main/java/org/bitcoinj/crypto/HDKeyDerivation.java#L65) to [Nist256p1 seed](https://github.com/newtondevelop/newton-keystore-java/blob/master/core/src/main/java/org/bitcoinj/crypto/HDKeyDerivation.java#L65).
