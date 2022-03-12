# jib-maven-plugin-example
https://github.com/GoogleContainerTools/jib
<br/>
# pom.xml
           <plugin>
                <groupId>com.google.cloud.tools</groupId>
                <artifactId>jib-maven-plugin</artifactId>
                <version>3.2.0</version>
                <configuration>
                    <from>
                        <image>openjdk:8</image>
                    </from>
                    <to>
                        <image>ozgur44/${project.artifactId}:${project.version}</image>
                        <auth>
                            <username>docker id</username>
                            <password>docker password</password>
                        </auth>
                    </to>
                    <container>
                        <ports>
                            <port>8080</port>
                        </ports>
                    </container>
                </configuration>
            </plugin>
