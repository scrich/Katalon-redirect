# Katalon-redirect
Simple redirection detection. Requires a datafile

Datafile is just a csv with two columns:
dRequestedUrl,dExpectedUrl

Then list the requested and expected urls.

You will probably need to map the data columns in the test suite, after connecting to the new datasource.
The test datasource is now a local file within the folder structure, in a folder called Source Data.
