# rubocop_yml
gotoinc rubocop configuration file

The bash script, that runs rubocop only for new and modified files
(initialized git repository is required).
You can create an alias for it to use with ease:
`git ls-files -om --exclude-standard | xargs ls -1 2>/dev/null | xargs rubocop`

