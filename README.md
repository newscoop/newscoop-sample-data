newscoop-sample-data
====================

Separating the sample data included with Newscoop into its own repository and packages.

Check the size of the package with:

	du -sx --exclude DEBIAN newscoop-sample-data

Build with:

	fakeroot dpkg-deb --build newscoop-sample-data/

Test with:

	lintian newscoop-sample-data.deb
