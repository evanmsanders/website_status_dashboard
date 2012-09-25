# A simple dashboard to monitor your websites.

This is a very simple little dashboard I wrote a while ago when I needed something to check quickly when websites started going down to let me know whether a problem was localised or not.

## Not Intended for Public Facing Use!

I wrote this for running on my local webserver. It is most likely not secure to put on a public facing website, so if you must do that, please use some form of authentication.

# Setup

Simply copy the files into a folder on your webserver and then add the websites you want to monitor to the <code>websites</code> array in <code>index.html</code>. That's it.

If you would like to tweak the representations of the HTTP codes, you can do that in <code>get_status.php</code>. The corresponding css classes are all declared directly in <code>index.html</code>.
