Experimental Sandboxed JonDoBrowser for OS X

Requirements:
  Mac OS 10.9 or newer.
  A willingness to run shell commands from Terminal.

Follow these steps to use the sandbox profiles:

1. Copy this folder ("Sandboxed JonDoBrowser") to a local drive, but do not
   put it in /Applications.
2. Copy the JonDoBrowser app into your "Sandboxed JonDoBrowser" folder.
3. Open Terminal.
4. Run start-tor-with-sandbox and wait for Tor bootstrapping to finish.
5. Run start-browser-with-sandbox.

Known Issues:

You will need to manually kill start-tor-with-sandbox or the tor.real
process after you exit the browser.

The browser has full access to the Tor control port. Ideally, access
would be limited to the things that are necessary for New Identity and
for the circuit display features.

Printing does not work.

The built-in updater will not work.

Files can only be downloaded or saved to ~/Downloads.
