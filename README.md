# AndroidLibrary

In your local properties add the following fields:
```
signing.keyId=
signing.password=
signing.key=
ossrhUsername=
ossrhPassword=
sonatypeStagingProfileId=
```

keyId: The last eight digits of the GPG key that we generated earlier.
password: Passphrase of the key pair.
key: base64 encoded format of the private key.
ossrhUsername and ossrhPassword: Details submitted at the time of registration in Sonatype JIRA.
To obtain sonatypeStagingProfileId, head over to https://s01.oss.sonatype.org and log in with the Sonatype credentials. Now click on StagingProfiles in the left panel, select your profile, then look for the ID in the URL. Have a look:
![img.png](img.png)

[Refrence](https://betterprogramming.pub/how-to-create-and-publish-an-android-library-in-mavencentral-92397df94103)