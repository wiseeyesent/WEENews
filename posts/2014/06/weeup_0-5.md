<html><body><p>EDIT: Current release is v0.7a. Work on this project is halted at the moment as the Java Virtual Machine itself is consuming too much memory for feasible use on my VPS. The project will need to be restarted using Perl, C++ or another alternative with lower over-head. Possbilities also include a web interface since it's going to be rebuilt anyways.

EDIT: v0.5c is now out with support for File Downloads &amp; Uploads

WEEUp v0.5 has been released. Find the Git Repo here: <a title="WEEUp v0.5 Repo" href="https://github.com/wiseeyesent/WEEUp" target="_blank">https://github.com/wiseeyesent/WEEUp</a>

This is an encrypted File Uploader. Currently using SKIP protocol to instantiate a shared DES encryption key. It comes in 2 parts, the server, WEEUpD, and the client WEEUp. The server is not directly interactive and must be connected to with the client in order for any operations to be performed. Each can be run out of an entirely unique directory. Currently, the server will create a passwd file containing all registered usernames and their password hashes, as well as a new directory for each user that is created. Files uploaded by the client are automatically stored in the user's directory.

The server is designed to be multi-threaded to support multiple concurrent connections. However, due to the memory limits of my VPS and the memory consumption of Java, I have been unable to fully test this. Additionally, no testing has been performed upon anything other than CentOS. It should run equally well in similar *nix systems, but I have not verified this. Ideally, it should also run on Windows &amp; Mac OSX with Java 7 or higher, but this has yet to be tested either.

At this time, the program logs all statements to standard output, so the display can become rather convoluted very quickly. Future versions will incorporate logging to a separate file as well as the verbosity level to use for logging. Additionally, I plan to incorporate a feature for emailing the session logs upon quitting as well as options for selecting different encryption ciphers, key lengths, and initial parameters.

Please let me know if you have any requests or bugs. You can contact me by email or through the Git Repo.</p></body></html>
