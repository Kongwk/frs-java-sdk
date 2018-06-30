if you don't want to use frs-java-client-1.0.0-jar-with-dependencies.jar, you can use frs-java-client-1.0.0.jar and java-sdk-core-2.0.1.jar and add other necessary dependencies to your pom.xml.

Here are the necessary dependencies:

    <dependencies>
     
        <dependency>
            <groupId>com.huawei</groupId>
            <artifactId>java-sdk-core</artifactId>
            <version>2.0.1</version>
            <scope>system</scope>
            <systemPath>${project.basedir}/lib/java-sdk-core-2.0.1.jar</systemPath>
        </dependency>

	<dependency>
            <groupId>com.huawei.frs</groupId>
            <artifactId>frs-java-client</artifactId>
            <version>1.0.0</version>
            <scope>system</scope>
            <systemPath>${project.basedir}/lib/frs-java-client-1.0.0.jar</systemPath>
        </dependency>

        <dependency>
            <groupId>org.apache.httpcomponents</groupId>
            <artifactId>httpclient</artifactId>
            <version>4.5.2</version>
        </dependency>

        <dependency>
            <groupId>org.apache.httpcomponents</groupId>
            <artifactId>httpcore</artifactId>
            <version>4.4.1</version>
        </dependency>

        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>3.8.1</version>
            <scope>test</scope>
        </dependency>

        <dependency>
            <groupId>commons-io</groupId>
            <artifactId>commons-io</artifactId>
            <version>2.4</version>
        </dependency>

        <dependency>
            <groupId>com.alibaba</groupId>
            <artifactId>fastjson</artifactId>
            <version>1.2.41</version>
        </dependency>

        <dependency>
            <groupId>com.fasterxml.jackson.core</groupId>
            <artifactId>jackson-core</artifactId>
            <version>2.8.4</version>
        </dependency>

        <dependency>
            <groupId>com.fasterxml.jackson.core</groupId>
            <artifactId>jackson-databind</artifactId>
            <version>2.8.4</version>
        </dependency>

        <dependency>
            <groupId>joda-time</groupId>
            <artifactId>joda-time</artifactId>
            <version>2.9.7</version>
        </dependency>

        <dependency>
            <groupId>log4j</groupId>
            <artifactId>log4j</artifactId>
            <version>1.2.17</version>
        </dependency>

    </dependencies>