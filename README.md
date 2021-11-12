# iframe-chrome-glitch

Reproduction code of iframe chrome glitch

[Link to issue](https://bugs.chromium.org/p/chromium/issues/detail?id=1269675)

## What steps will reproduce the problem?

1. Open https://adrigzr.github.io/iframe-chrome-glitch/
2. Click on "Push"
3. Click on "Create iframe"
4. Click on "Navigate to B" inside iframe
5. Click on "Replace"
6. Click on "Remove iframe"
7. Click on "Back"
8. Check location hash

## What is the expected result?

- Hash should be `#/push`

## What happens instead?

- Hash is `#/replace`
