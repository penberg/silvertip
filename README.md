Silvertip
=========

Silvertip is a networking library, which aims to be easy to use, while hiding
the complexities of the Java NIO API. While similar libraries exist, they are
either hard to use, discontinued, or part of a bigger application framework
that offer an API for using different transports.

Installation
------------

Silvertip is made available through Typesafe's maven repository. If you're
using Apache Ivy, update the resolver chain in your 'ivysettings.xml':

    <resolvers>
      <chain name="main">
        <ibiblio name="typesafe-releases"
          root="http://repo.typesafe.com/typesafe/releases/"
          m2compatible="true"/>
      </chain>
    </resolvers>

and declare a dependency to Silvertip by updating 'ivy.xml':

    <dependencies>
      <dependency org="silvertip" name="silvertip" rev="0.2.1"/>
    </dependencies>

If you're using sbt, amend your 'build.sbt' with:

    resolvers += "typesafe-releases" at "http://repo.typesafe.com/typesafe/releases"

    libraryDependencies += "silvertip" % "silvertip" % "0.2.1"