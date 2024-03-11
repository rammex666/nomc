# Contributing

Contributions are welcome! Here's how you can help:

- [Contributing code](#code)
- [Reporting issues](#issues)
- [Requesting features](#feature-requests)
- [Translating](#translations)
- [Donating](#donations)

## Code

1. [Fork](https://help.github.com/articles/fork-a-repo/) the repository and
   [clone](https://help.github.com/articles/cloning-a-repository/) your fork.

2. Start coding!
    - Refer to the
      [Lua API](https://github.com/rammex666/nomc.gg/blob/master/doc/lua_api.md), and other
      [documentation](https://github.com/rammex666/nomc.gg/tree/master/doc).
    - Check your code works as expected and document any changes to the Lua API.

3. Commit & [push](https://help.github.com/articles/pushing-to-a-remote/).
    - Commit messages should:
        - Use the present tense.
        - Be descriptive. See the commit messages by core developers for examples.

4. Once you are happy with your changes, submit a pull request.
     - Open the [pull-request form](https://github.com/rammex666/nomc.gg/pull/new/master).
     - Add a description explaining what you've done (or if it's a
       work-in-progress - what you need to do).
     - Make sure to fill out the pull request template.

### A pull-request is considered merge-able when:

1. Fits the whole picture of the project.
2. It works.
3. The code's interfaces are well designed, regardless of other aspects that
   might need more work in the future.
4. It uses protocols and formats which include the required compatibility.

## Issues

If you experience an issue, we would like to know the details - especially when
a stable release is on the way.

1. Do a quick search on GitHub to check if the issue has already been reported.
2. [Open an issue](https://github.com/rammex666/nomc.gg/issues/new) and describe
   the issue you are having - you could include:
     - Error logs (check the bottom of the `debug.txt` file).
     - Screenshots.
     - Ways you have tried to solve the issue, and whether they worked or not.
     - Your NoMC.gg version and the content (games, mods or texture packs) you have installed.
     - Your platform (e.g. Windows 10 or Linux Mint 20.3 Cinamon).

After reporting you should aim to answer questions or clarifications as this
helps pinpoint the cause of the issue (if you don't do this your issue may be
closed after 1 month).

## Feature requests

Feature requests are welcome but need to fits the whole picture of
the project. You should provide a clear explanation with as much detail as
possible.

## Translations, work in progress... (old links from the fork)

The core translations of Minetest are performed using Weblate. You can access
the project page with a list of current languages
[here](https://hosted.weblate.org/projects/minetest/minetest/).

Builtin (the component which contains things like server messages, chat command
descriptions, privilege descriptions) is translated separately; it needs to be
translated by editing a `.tr` text file. See
[Translation](https://dev.minetest.net/Translation) for more information.

## Reviewing pull requests

Pull requests should be reviewed and, if appropriate, checked if they achieve
their intended purpose. You can show that you are in the process of, or will
review the pull request by commenting *"Looks good"* or something similar.

**If the pull-request is not [merge-able](#a-pull-request-is-considered-merge-able-when):**

Submit a comment explaining to the author what they need to change to make the
pull-request merge-able.

- If the author comments or makes changes to the pull-request, it can be
  reviewed again.
- If no response is made from the author within 1 month (when improvements are
  suggested or a question is asked), it can be closed.

**If the pull-request is [merge-able](#a-pull-request-is-considered-merge-able-when):**

Submit a :+1: (+1) or "Looks good" comment to show you believe the pull-request should be merged. "Looks good" comments often signify that the patch might require (more) testing.

- Two core developers must agree to the merge before it is carried out and both should +1 the pull request.
- Who intends to merge the pull-request should follow the commit rules:
    - The title should follow the commit guidelines (title starts with a capital letter, present tense, descriptive).
    - Don't modify history older than 10 minutes.
    - Use rebase, not merge to get linear history:
    - `curl https://github.com/minetest/minetest/pull/1.patch | git am`

## Reviewing issues and feature requests

- If an issue does not get a response from its author within 1 month (when requiring more details), it can be closed.
- When an issue is a duplicate, refer to the first ones and close the later ones.
- Tag issues with the appropriate [labels](https://github.com/rammex666/nomc.gg/labels) for devices, platforms etc.

## Releasing a new version

Availeble on the realese section of the repositories whit Windows, MacOS, Linux distros, Android.
