# nativequeryResults
Classe de anotation para armazenas resultados de select , stored e etc sem necessidade de ENTITY

## anotation for map resultset without entity class
 * pass 1:
 - import the class's into your project
 * pass2:
 - import a commons into your pom.xml
 ```bash
 	<dependency>
			<groupId>commons-beanutils</groupId>
			<artifactId>commons-beanutils</artifactId>
			<version>1.9.3</version>
		</dependency>
```
* pass 3:
  > add the anotation @nativequeryresultentity into your class
   > add the anotation @nativequeryresultcolumn into yours vars
    > map yours @nativequeryresultcolumn with ordered resultset from query
   ### ex:
   ```bash
    @nativequeryresultcolumn(index=0) for the first result returned from de query......
```
