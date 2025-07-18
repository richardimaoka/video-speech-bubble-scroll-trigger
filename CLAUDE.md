# Claude Code Instructions

## Development Workflow

Follow this cycle when working on this project:

1. User requests file edits with a prompt
2. Understand the prompt and make the requested file edits
3. Automatically ask if a git commit should be made (without waiting for user to request it)
4. Wait for the next file edit request and repeat the cycle

This ensures consistent version control practices and keeps the user informed about commit opportunities after each set of changes.