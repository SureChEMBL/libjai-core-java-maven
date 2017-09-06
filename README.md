libjai-core-java-maven Debian package

Official libjai-core-java Debian package installs .jar-s only into `/usr/share/java`, but not into local Maven repo (/usr/share/maven-repo).

The current package simply depends on libjair-core-java and creates necessary symlinks and .pom files in Debian local Maven repo. So, for example, javax.media:jai_core:debian gets available from the local Maven repo if libjai-core-jave-maven is installed.
