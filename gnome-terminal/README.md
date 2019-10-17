# Export Gnome Terminal Profile

List profiles

    dconf dump /org/gnome/terminal/legacy/profiles:/

Dump to a file

    dconf dump /org/gnome/terminal/legacy/profiles:/ > profiles.dconf

Restore from file

    dconf load /org/gnome/terminal/legacy/profiles:/ < profiles.dconf

