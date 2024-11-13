from --platform=linux/amd64 alpine

run apk add alpine-conf pipewire

run setup-desktop plasma

run echo "exec startplasma-x11" >> ~/.xinitrc

entrypoint export $(dbus-launch) ; udevd -d; xinit