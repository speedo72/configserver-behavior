This Repo is to demonstrate behavior change across spring boot versions

I created this project in intellij ide with java17. You could also build gradle projects individually and run jars.

To enable please run config server application in behavior/server folder.

I am really just comparing spring boot config server setup across spring version 2.5.2 and spring version 2.6.6.
Spring cloud is at version 3.0.6 in spring 2.5.2 folders (/behavior/client-2.5.2*) and is at version 3.1.1 in spring 2.6.6 folders (/behavior/client-2.6.6*).

So client-2.5.2-case1 and client-2.6.6-case1 display the same behavior.

However client-2.5.2-case2 and client-2.6.6-case2 display different behavior.
Reason is client-2.6.6-case2 is not picking up ConfigClientProperties. Am just trying to understand why. 

Hope this sample helps. Thanks again

