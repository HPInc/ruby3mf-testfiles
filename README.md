# Ruby3mf-testfiles

A collection of valid and invalid 3mf files for testing 3mf readers, writers, and validators.


# To create or edit 3mf files, do something like this:

```
cd spec/test_files/failing_cases
unzip test_case_14.zip -d test_case_14
rm test_case_14.zip
# edit files within folders
cd test_case_14
zip -r ../test_case_14.zip *
cd ..
rm -rf test_case_14

```

