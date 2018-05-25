# JDJ-Repository
Repositório de bibliotecas

## Adicione em seu pom.xml
        <repository>
                <id>JDJMvn</id>
                <name>JDJ Repository</name>
                <url>"https://github.com/JDJ-Softwares/JDJ-Repository/tree/master/repository"</url>
                <snapshots>
                    <enabled>true</enabled>
                    <updatePolicy>always</updatePolicy>
                </snapshots>
                <releases>
                    <enabled>true</enabled>
                    <updatePolicy>daily</updatePolicy>
                </releases>
        </repository>
