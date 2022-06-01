Hooks can be added using imunify360-agent (not the GUI). For example:

imunify-hooks imunify360-agent hook add --event malware-scanning --path /usr/share/imunify-hooks/hook-scan
imunify-hooks imunify360-agent hook add --event malware-detected --path /usr/share/imunify-hooks/hook-found
