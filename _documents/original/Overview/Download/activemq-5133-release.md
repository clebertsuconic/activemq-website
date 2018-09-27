Apache ActiveMQ ™ -- ActiveMQ 5.13.3 Release 

[Overview](overview.md) > [Download](OverviewOverview/Overview/download.md) > [ActiveMQ 5.13.3 Release](Overview/DownloadOverview/Download/Overview/Download/activemq-5133-release.md)


![](/images/activemq-5.x-box-reflection.png)

ActiveMQ 5.13.3 Release
-----------------------

Apache ActiveMQ 5.13.3 includes over 25 resolved[ issues](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12311210&version=12335045) and improvements.

### Getting the Binary Distributions

Description

Download Link

_Verify_

Windows Distribution

[apache-activemq-5.13.3-bin.zip](https://archive.apache.org/dist/activemq/5.13.3/apache-activemq-5.13.3-bin.zip)

[ASC](https://archive.apache.org/dist/activemq/5.13.3/apache-activemq-5.13.3-bin.zip.asc), [MD5](https://archive.apache.org/dist/activemq/5.13.3/apache-activemq-5.13.3-bin.zip.md5), [SHA1](https://archive.apache.org/dist/activemq/5.13.3/apache-activemq-5.13.3-bin.zip.sha1)

Unix/Linux/Cygwin Distribution

[apache-activemq-5.13.3-bin.tar.gz](https://archive.apache.org/dist/activemq/5.13.3/apache-activemq-5.13.3-bin.tar.gz)

[ASC](https://archive.apache.org/dist/activemq/5.13.3/apache-activemq-5.13.3-bin.tar.gz.asc), [MD5](https://archive.apache.org/dist/activemq/5.13.3/apache-activemq-5.13.3-bin.tar.gz.md5), [SHA1](https://archive.apache.org/dist/activemq/5.13.3/apache-activemq-5.13.3-bin.tar.gz.sha1)

Verify the Integrity of Downloads
---------------------------------

It is essential that you verify the integrity of the downloaded files using the PGP or MD5 signatures. The PGP signatures can be verified using PGP or GPG. Begin by following these steps:

1.  Download the [KEYS](http://www.apache.org/dist/activemq/KEYS)
2.  Download the asc signature file for the relevant distribution
3.  Verify the signatures using the following commands, depending on your use of PGP or GPG:
    
    $ pgpk -a KEYS
    $ pgpv apache-activemq-<version>-bin.tar.gz.asc
    
    or
    
    $ pgp -ka KEYS
    $ pgp apache-activemq-<version>-bin.tar.gz.asc
    
    or
    
    $ gpg --import KEYS
    $ gpg --verify apache-activemq-<version>-bin.tar.gz.asc
    

(Where <version> is replaced with the actual version, e.g., 5.1.0, 5.2.0, etc.).

Alternatively, you can verify the MD5 signature on the files. A Unix program called `md5` or `md5sum` is included in most Linux and Unix distributions. It is also available as part of [GNU Textutils](http://www.gnu.org/software/textutils/textutils.html). Windows users can utilize any of the following md5 programs:

*   [md5](http://www.fourmilab.ch/md5/)
*   [md5sums](http://www.pc-tools.net/win32/md5sums/)
*   [SlavaSoft FSUM](http://www.slavasoft.com/fsum/)

Getting the Binaries using Maven 3
----------------------------------

To use this release in your maven project, the simplest dependency that you can use in your [Maven POM](http://maven.apache.org/guides/introduction/introduction-to-the-pom.html) is:

<dependency>
  <groupId>org.apache.activemq</groupId>
  <artifactId>activemq-all</artifactId>
  <version>5.13.3</version>
</dependency>

If you need more fine grained control of your dependencies (activemq-all is an uber jar) pick and choose from the various components activemq-client, activemq-broker, activemq-xx-store etc.

Getting the Source Code
-----------------------

### Source Distributions

Description

Download Link

Verify

Source Release

[activemq-parent-5.13.3-source-release.zip](https://archive.apache.org/dist/activemq/5.13.3/activemq-parent-5.13.3-source-release.zip)

[ASC](https://archive.apache.org/dist/activemq/5.13.3/activemq-parent-5.13.3-source-release.zip.asc), [MD5](https://archive.apache.org/dist/activemq/5.13.3/activemq-parent-5.13.3-source-release.zip.md5), [SHA1](https://archive.apache.org/dist/activemq/5.13.3/activemq-parent-5.13.3-source-release.zip.sha1)

### Git Tag

[https://git-wip-us.apache.org/repos/asf?p=activemq.git;a=tag;h=refs/tags/activemq-5.13.3](https://git-wip-us.apache.org/repos/asf?p=activemq.git;a=tag;h=refs/tags/activemq-5.13.3)

Change Log
----------

For a more detailed view of new features and bug fixes, see the [release notes](https://issues.apache.org/jira/secure/ReleaseNote.jspa?projectId=12311210&version=12335045)

This release affects applications using ObjectMessages. Please refer to [http://activemq.apache.orgFeatures/Message Features/objectmessage.md](http://activemq.apache.orgFeatures/Message Features/objectmessage.md) and .jira-issue { padding: 0 0 0 2px; line-height: 20px; } .jira-issue img { padding-right: 5px; } .jira-issue .aui-lozenge { line-height: 18px; vertical-align: top; } .jira-issue .icon { background-position: left center; background-repeat: no-repeat; display: inline-block; font-size: 0; max-height: 16px; text-align: left; text-indent: -9999em; vertical-align: text-bottom; } [AMQ-6013](https://issues.apache.org/jira/browse/AMQ-6013?src=confmacro) for more information.

Also see the previous [ActiveMQ 5.13.2 Release](Overview/DownloadOverview/Download/Overview/Download/activemq-5132-release.md)
