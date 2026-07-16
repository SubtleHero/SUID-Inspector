# SUID-Inspector

There have been many times (too many haha) during labs and certification practice where I missed an obvious privilege escalation path simply because I overlooked an unusual SUID binary or forgot to check one against GTFOBins.

I created SUID-Inspector to remove that guesswork.

Given a list of discovered SUID executables, SUID-Inspector analyzes each binary against a list of common SUID binaries and the GTFOBins database, highlighting those that may provide a path to privilege escalation. Instead of manually checking every SUID binary, the tool quickly identifies binaries with known GTFOBins entries while drawing attention to unusual or unexpected SUID executables that deserve further investigation.

Whether you're preparing for certifications like the OSCP, completing CTFs, or performing real-world penetration tests, SUID-Inspector is designed to make SUID enumeration faster, more efficient, and less prone to human error.
