# Super-POM with common settings for FBK projects

In order to use this super-POM in your project, add the following snippet in your project `pom.xml`, property replacing `VERSION` with the version of the super-POM you want to import (in case of multi-module project, add the snippet to the parent `pom.xml` file):

   ```
       <parent>
           <groupId>eu.fbk.parent</groupId>
           <artifactId>parent</artifactId>
           <version>VERSION</version>
       </parent>
   ```

Optionally, copy all the directories and files in the `src` folder under the `src` folder of ypur project. These files provide common settings for Checkstyle, PMD, Eclipse, and site-related plugins (e.g., XREF).
