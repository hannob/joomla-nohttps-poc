# joomla-nohttps-poc
Proof of concept to install backdoor via unencrypted Joomla update

# background

The Joomla CMS before version 3.5 used an insecure update process over HTTP.

This is a proof of concept. If you redirect requests to update.joomla.org to an
HTTP host containing the files in this repo it will show an update to a fictious
version 3.5.99. This 3.5.99 update will install a trivial PHP backdoor.
