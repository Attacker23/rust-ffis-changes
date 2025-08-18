# Structure

- repo/
  - files/
    - function_name.csv: Metadata and information about the function (both C and Rust sides).
    - function_name.json: Commit history related to this function(Some of the renames were determined manually).
    - function_name.changes.json: Present only if changes are detected; describes the change patterns.
  - changes_log.txt: Manually verified list of functions that truly changed. Note: the entries under files/ may contain a small number of false positives.
