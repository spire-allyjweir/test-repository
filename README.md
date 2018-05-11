# test-repository
Repository for testing the Github APIs.

Add some text to trigger a new version and verify that Concourse is reusing the same container between builds. Which ultimately makes sense, but
can produce surprising results - i.e., we can't rebuild a commit to see whether changes to master will fix a failing build.
