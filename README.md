# my-artifacts

## Custom maven registry

How to publish to this maven registry ?

- Add this registry to the artifact's maven distribution list
```
<distributionManagement>
   <repository>
     <id>github</id>
     <name>GitHub divyaapaduvalli Apache Maven Packages</name>
     <url>https://maven.pkg.github.com/divyaapaduvalli/my-artifacts</url>
   </repository>
</distributionManagement>
```
- Publish the artifact
```
mvn deploy
```

For authentication and more, refer the following :
- https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-apache-maven-registry
