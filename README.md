This patch against GTK+ v.2.24.28 that enables single click in file chooser dialog. Based on [patch]( https://bugzilla.gnome.org/attachment.cgi?id=232189&action=diff) that was proposed to the upstream years ago but hasn't been accepted for no reason.

To enable single click add `SingleClickActivate=true` to `~/.config/gtk-2.0/gtkfilechooser.ini`.
