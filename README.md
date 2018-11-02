Rolling release of (usually) STSs  OpenJDK
OpenJDK have release cadence of 6 months. but 3/4 of them are Short Term Supported for 6 months only. This package is designed to harbore them. Currently it is build on openJDK 10. LTSs (next is 11) will go as separate packages. 

JDK11 is last release of Java platform. It is bringing many cool improvements - http://openjdk.java.net/projects/jdk/11/ and is landing to your Fedora. Where it will be maintained for f27 and newer. Unluckily, this package is STS (short term support) version. Between individual LTS will be always several STS. Again, please See announcement: http://mail.openjdk.java.net/pipermail/discuss/2017-September/004281.html and See java SIG plans: https://jvanek.fedorapeople.org/devconf/2018/changesInjavaReleaseProcess.pdf . So this is rolling release of all STSs to come. Its fate during the release of fresh LTS is yet to be decided. You will always be allowed to install Used LTS in fedora build root, alongside with latest STS via alternatives. 


See announcement: http://mail.openjdk.java.net/pipermail/discuss/2017-September/004281.html
See java SIG plans: https://jvanek.fedorapeople.org/devconf/2018/changesInjavaReleaseProcess.pdf

https://bugzilla.redhat.com/show_bug.cgi?id=1557371#c0
https://fedoraproject.org/wiki/Changes/java-openjdk-10
https://fedoraproject.org/wiki/Changes/java-11-openjdk-TechPreview
