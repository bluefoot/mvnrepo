# mvnrepo
Maven repository to host some of the java libraries developed here. The repository is hosted in the mvn-repo branch. Thanks to [emmby](https://stackoverflow.com/a/14013645) for helping setting this up.

## Usage

    <repositories>
      <repository>
        <id>bluefoot-mvn-repo</id>
        <url>https://raw.github.com/bluefoot/mvnrepo/mvn-repo/</url>
        <snapshots>
          <enabled>true</enabled>
          <updatePolicy>always</updatePolicy>
        </snapshots>
      </repository>
    </repositories>
