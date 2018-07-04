

Per usar en JBOSS 5.x s'ha d'usar la seg�ent despend�ncia:

<dependency>
  <groupId>org.fundaciobit.plugins</groupId>
  <artifactId>plugin-validatesignature-afirmacxf</artifactId>
  <version>1.0.1</version>

  <exclusions> 
    <exclusion>  
      <groupId>xerces</groupId>
      <artifactId>xercesImpl</artifactId>
    </exclusion>

    <exclusion>  
      <groupId>com.sun.xml.bind</groupId>
      <artifactId>jaxb-impl</artifactId>
    </exclusion>

    <exclusion>  
      <groupId>xalan</groupId>
      <artifactId>xalan</artifactId>
    </exclusion>

    <exclusion>  
      <groupId>org.slf4j</groupId>
      <artifactId>log4j-over-slf4j</artifactId>
    </exclusion>

    <exclusion>  
      <groupId>org.slf4j</groupId>
      <artifactId>jcl-over-slf4j</artifactId>
    </exclusion>

    <exclusion>  
      <groupId>org.apache.ws.security</groupId>
      <artifactId>wss4j</artifactId>
    </exclusion>
        
    <exclusion>  
      <groupId>org.apache.santuario</groupId>
      <artifactId>xmlsec</artifactId>
    </exclusion>
  </exclusions> 
</dependency>
