Ms1Project - Spring Boot MockMvc Unit Testing

Requirements:
- JDK 17 or later
- STS4 / Eclipse with Spring Tools and Maven support

Import into STS4:
1. Extract Ms1Project.zip.
2. Open STS4.
3. Select File > Import.
4. Select Maven > Existing Maven Projects, then Next.
5. Browse to the extracted Ms1Project folder.
6. Select the pom.xml and click Finish.
7. Wait for Maven dependencies to download.

Run the test:
1. Open src/test/java/com/example/demo/Ms1ControllerTest.java.
2. Right-click the file.
3. Select Run As > JUnit Test.
4. The JUnit view should show 1 test, 0 failures, 0 errors (green bar).

Endpoint:
GET /ms1/add?a=-5&b=5

Expected response:
MS 1.1 - Additon = 0
