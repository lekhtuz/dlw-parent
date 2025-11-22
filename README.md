# dlw-parent-bom

# Generate dependency tree
`mvn -B dependency:tree | egrep -e '\+-|\\\-|dlw-parent:pom' > dependency-tree.txt`

## Add the following to pom.xml
```
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```