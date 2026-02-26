Resolves #

## What Changed

Brief summary of what this PR does and why.

## How It Works

Describe the approach taken. What files were changed and why? Call out any non-obvious decisions.

## Testing Instructions

Steps for a reviewer to verify this works:

1. ...
2. ...
3. ...

## Test Coverage

- [ ] Unit tests added/updated in `tests/wpunit/`
- [ ] E2E test reproduces the bug (for bug fixes) — test fails before fix, passes after
- [ ] Happy path covered
- [ ] Edge cases covered
- [ ] All existing tests still pass (`vendor/bin/codecept run wpunit` or `vendor/bin/phpunit`)

**If no tests:** explain why tests aren't applicable for this change.

## Screenshots

If this changes any UI, add before/after screenshots.

## Pre-merge Checklist

- [ ] Acceptance criteria from the linked issue are met
- [ ] Code follows [WordPress coding standards](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/php/) (tabs, Yoda conditions, escaping/sanitization)
- [ ] Self-reviewed the diff
- [ ] No new PHP warnings, notices, or deprecations
- [ ] Tested on PHP 7.4 and 8.x (if touching compatibility-sensitive code)
- [ ] Review requested from @polevaultweb
