# file-integrity-checker

Project[https://roadmap.sh/projects/file-integrity-checker](https://roadmap.sh/projects/file-integrity-checker)

1. Add file's execute
   ```bash
   chmod +x integrity-check.sh
   ```
2. How work:

   1. This command use onece on start or about first adding new file/dir
   ```bash
   ./integrity-check.sh init <path_to_file_or_dir>
   ```

   2. This command use for always monitoring. She compares current file's hash with that what in .hashes.db
      ```bash
      ./integrity-check.sh check <path_to_file_or_dir>
      ```

   3. This command use for update file's hash in .hashes.db
      ```bash
      ./integrity-check.sh update <path_to_file_or_dir>
      ```
