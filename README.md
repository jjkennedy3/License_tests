# License_tests
Test repository for licenses

The initial commit created a repository with a `README.md` file and a `LICENSE` file.

The `LICENSE` file was corretly detected as a `MIT License`. 

Next step is to add a `license-header.txt` file to see if licensee breaks.
 - Expected results are that the license will revert to `Other`
 
 ### Results:
 When the `license-header.txt` file was added the displayed license type displayed as `view license`.
 This is the correct behavior according to the [licensee documentation](https://github.com/licensee/licensee/blob/master/docs/what-we-look-at.md)
 
 
