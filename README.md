# woff2-compiled-tests
Compiled, generated version of https://github.com/w3c/woff2-tests for standalone use.

Spares user cloning woff2-tests and installing it's dependencies.

To use the tests:

* Install fonts from UserAgent/FontsToInstall locally
 * If you do not, tests that should print PASS when a font is rejected will instead print FAIL 
* Open index file for test case in browser, eg UserAgent/Tests/xhtml1/testcaseindex.xht, from the filesystem
 * Each root directory here represents a test suite
 * Each test suite has a testcaseindex.xht

# References
https://github.com/w3c/woff2-tests contains the code to generate these tests
http://www.w3.org/Fonts/WG/wiki/Main_Page contains the test specifications
