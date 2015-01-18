# Fedora-WiFiPineapple-script
# Q: Why the need for a new script?
# A: From Fedora 18 there is a new version of iptables in which "-m state --state" has been obsoleted in favour of the new "-m conntrack --ctstate", which means you may get the error "The state match is obsolete. Use conntrack instead."
# Also, since Fedora 15, the first ethernet interface in Fedora was renamed from eth0 to em1. With a quick search and replace I could fix the interface names, with this new(ish) change, I thought an update to the script was necessary.
# To make the script executable just run:
# chmod +x fedora18-wp5.sh
# To run the script run :
# sudo ./fedora18-wp5.sh
