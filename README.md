sample usage that only includes dependencies of known Pentaho groupIds:

```
$ mvn org.apache.maven.plugins:maven-dependency-plugin:2.11-SNAPSHOT:tree \
  -DoutputFile=deps3.graphml \
  -DoutputType=graphml \
  -Dincludes=pentaho,pentaho-kettle,org.pentaho,com.pentaho,pentaho-reporting-engine
```
