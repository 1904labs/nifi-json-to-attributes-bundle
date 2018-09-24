# nifi-json-to-attributes-bundle

NiFi processor to transform JSON values to Attributes

## Deploy Bundle

Clone this repository

```shell
git clone https://github.com/1904labs/nifi-json-to-attributes-bundle
```

Build the bundle

```shell
cd nifi-json-to-attributes-bundle
mvn clean install
```

Copy Nar file to $NIFI_HOME/lib

```shell
cp nifi-json-to-attributes-bundle/target/nifi-json-to-attributes-nar-$version.nar $NIFI_HOME/lib/
```

Start/Restart Nifi

```shell
$NIFI_HOME/bin/nifi.sh start
```


### TODO
