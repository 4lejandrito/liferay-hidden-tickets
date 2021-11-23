# Liferay Hidden Tickets

List all the tickets that added a feature flag within the given git range. Use with caution.

## Installation

Move the `lht` script to your $PATH.

## Usage

Just run `lht <start> <end>` in the liferay-portal(-ee) repo root and wait for the ticket names to be listed. It's important that you're on the master branch and it is up to date.

**Example (in liferay-portal-ee):**
```bash
lht 7.4.13-ga1 HEAD
```
