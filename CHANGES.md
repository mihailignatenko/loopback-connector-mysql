2014-12-05, Version 1.4.9
=========================

 * Add a test case for autoupdate (Raymond Feng)

 * Create 'NOT NULL' constraint for required or id properties (Raymond Feng)

 * Better handle discovery of nullable columns (Raymond Feng)


2014-11-27, Version 1.4.8
=========================

 * fix(initialization): bug fix for setting limit on number of connections in connection pool (cpentra1)

 * Add contribution guidelines (Ryan Graham)


2014-09-11, Version 1.4.7
=========================

 * Enhance error reporting for automigrate/autoupdate (Raymond Feng)


2014-09-10, Version 1.4.6
=========================

 * Bump version (Raymond Feng)

 * Use table name instead of model name (Raymond Feng)

 * Use async and make sure errors are passed to callback (Raymond Feng)


2014-08-25, Version 1.4.5
=========================

 * Bump version (Raymond Feng)

 * Make sure the deferred query will be invoked only once (Raymond Feng)


2014-08-20, Version 1.4.4
=========================

 * Bump version (Raymond Feng)

 * Add ping() (Raymond Feng)


2014-08-20, Version 1.4.3
=========================

 * Bump version (Raymond Feng)

 * Fix MySQL conversion for embedded model instance (Raymond Feng)

 * Fix the createDatabase option (Raymond Feng)


2014-08-15, Version 1.4.2
=========================

 * Bump version (Raymond Feng)

 * Allow properties to pass through mysql driver (Raymond Feng)

 * Fix the default length for strings to avoid row size overflow (Raymond Feng)


2014-06-27, Version 1.4.1
=========================

 * Bump version (Raymond Feng)

 * Fix the test cases as now inq/nin is checked for array values (Raymond Feng)

 * Update link to doc (Rand McKinney)


2014-06-23, Version 1.4.0
=========================

 * Bump version (Raymond Feng)

 * cannot read property of undefined fixed (Johnny Bill)

 * Fix comparison for null and boolean values (Raymond Feng)

 * Map object/json to TEXT (Raymond Feng)


2014-06-04, Version 1.3.0
=========================

 * Remove peer dependency on datasource-juggler (Miroslav Bajtoš)


2014-06-02, Version 1.2.3
=========================

 * Bump version (Raymond Feng)

 * Fix sql injection and add test cases (Raymond Feng)


2014-05-29, Version 1.2.2
=========================

 * Bump version (Raymond Feng)

 * Fix the varchar length (Raymond Feng)

 * Add like/nlike support (Raymond Feng)

 * Fix object/json type mapping (Raymond Feng)


2014-05-16, Version 1.2.1
=========================

 * Bump versions (Raymond Feng)

 * Fix buildWhere (Raymond Feng)

 * Add support for logical operators (AND/OR) (Raymond Feng)

 * updateOrCreate assumes numeric primary key(s) (Scott Anderson)


2014-04-08, Version 1.2.0
=========================

 * Bump version (Raymond Feng)

 * Remove the commented out code (Raymond Feng)

 * Fix the query for discovery with current user (Raymond Feng)

 * Fix the table generation for string ids (Raymond Feng)

 * Update deps (Raymond Feng)

 * Use NULL for undefined (Raymond Feng)

 * Prevent inserting undefined values (Marat Dyatko)

 * Update to dual MIT/StrongLoop license (Raymond Feng)

 * Fix merge issue (Raymond Feng)

 * Reformat code (Raymond Feng)

 * Update discovery.js (Samer Aldefai)

 * Fix link to docs. (Rand McKinney)

 * Replaced most content with link to docs. (Rand McKinney)

 * Move mocha args to test/mocha.opts (Ryan Graham)

 * Make 'npm test' more useful to CI (Ryan Graham)

 * Prevent extra files from going into npm (Ryan Graham)


2013-12-06, Version 1.1.1
=========================

 * Bump version (Raymond Feng)

 * Update deps (Raymond Feng)

 * Add the test for loopback-datasource-juggler PR-48 (Raymond Feng)

 * Fix the orderBy (Raymond Feng)


2013-11-27, Version 1.1.0
=========================

 * Bump version (Raymond Feng)

 * Refactor the runQuery logic into a function (Raymond Feng)

 * Improve the connector based on review feedbacks (Raymond Feng)

 * Allow connectionLmit to be set (Raymond Feng)

 * Use connection pool for MySQL (Raymond Feng)

 * Update docs.json (Rand McKinney)

 * Fix the regression caused by juggler (Raymond Feng)


2013-11-20, Version 1.0.2
=========================

 * Remove blanket (Raymond Feng)

 * Bump version and update deps (Raymond Feng)

 * Append error to the message (Raymond Feng)

 * Add NOTICE and update READE (Raymond Feng)

 * Update README.md (Rand McKinney)

 * Update the internal github dependency (Raymond Feng)


2013-10-28, Version 1.0.0
=========================

 * First release!
