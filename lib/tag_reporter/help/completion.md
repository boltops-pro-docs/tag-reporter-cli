<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-pro/tag-reporter-cli/blob/master/lib/tag_reporter/help/completion.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

## Examples

    tag-reporter completion

Prints words for TAB auto-completion.

    tag-reporter completion
    tag-reporter completion hello
    tag-reporter completion hello name

To enable, TAB auto-completion add the following to your profile:

    eval $(tag-reporter completion_script)

Auto-completion example usage:

    tag-reporter [TAB]
    tag-reporter hello [TAB]
    tag-reporter hello name [TAB]
    tag-reporter hello name --[TAB]
