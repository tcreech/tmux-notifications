tmux-notifications
==================

Dead simple tmux notification system that I have been using for a while now. Badly written. Probably could just use sh instead of zsh.

Processes can call tmux-notify "an example notification" to queue up a notification. The included sample snippets (see tmux.conf) arrange for tmux to show a pending notification count in the status bar, and show/clear them with a keybinding.

Example uses: email notifications, jabber message notifications, ad-hoc "job finished" type notifications, etc

