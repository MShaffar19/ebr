A set of Maven plugins that simplifies and automates working
with Eclipse Bundle Recipies via Maven.

wiki: [http://wiki.eclipse.org/EBR](http://wiki.eclipse.org/EBR)

mailing list: [https://dev.eclipse.org/mailman/listinfo/ebr-dev](https://dev.eclipse.org/mailman/listinfo/ebr-dev)

bugzilla: [https://bugs.eclipse.org](https://bugs.eclipse.org/bugs/buglist.cgi?list_id=6321580&classification=Eclipse%20Foundation&query_format=advanced&bug_status=UNCONFIRMED&bug_status=NEW&bug_status=ASSIGNED&bug_status=REOPENED&product=CBI)

Using the plugins
=================

Add the EBR repository to your Maven &lt;pluginRepositories&gt; section

    https://repo.eclipse.org/content/repositories/ebr-releases/

Release Process
===============

Internat note: we are not using the release plug-in.
Instead we just set version manually and use Jenkins to build and deploy.

    mvn versions:set -DnewVersion=....
