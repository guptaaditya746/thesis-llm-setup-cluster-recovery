# Backup manifest

Sanitized source snapshot of the LLM setup project. Its previous Git history is omitted because `.env.example` included a populated master-key field; sensitive values have been blanked in this snapshot. The original repository and its 35 commits remain unchanged on the cluster.

Excluded local data and generated artifacts:

- `tests/A7/`: untracked test artifacts present in the source directory.
- `.env` files, local credentials, logs, model/cache directories, and build outputs covered by `.gitignore`.

Copy any needed local artifacts to separate storage before account deletion.
