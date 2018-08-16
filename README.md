# zklistboxbug
Run mvn jetty:run and the bug will appear.

```
java.lang.ClassCastException: org.zkoss.zul.Listfoot cannot be cast to org.zkoss.zul.Listitem
```

It is not possible to reproduce the bug in a http://zkfiddle.org/ with the same ZUL file and ZK 8.0.5 selected as version.

