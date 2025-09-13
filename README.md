# Incident Ethics & Evidence Notes Week-4


## My First-Hour Priorities:
In the provided prompt for this week's in class activity, my focus would be:
      - Obtaining the IdP logs that had occured in a set time before and after the attack had occured.
      - Safely obtain the email that was used which triggered the alert
      - examining both the IdP logs and safely read the email in a Read-only window where I can view the contents of it
With these as my focus, I would have gathered the required information that would allow me to begin looking over for the vital information that is needed for investigation. However, The one thing I will simple avoid is gathering more information than is required as it is unnecessary information. Obtaining this information would not only delay the investigation and complicate it, but it would also damage my reputation and ethical code I hold for this position.

## Incident & Evidence Note:
 An automated alert went off which identified that a suspicious email was sent to Sam Rivera, a student at the college. John Smith, the incident manager, has authrozied an inspection of the logs (15 minute window before and after the alert) and the suspicious email. With the evidence obtained, hashed and secured in a repository that is logged, information involving the student's identifiers and credentials were redacted to ensure integrity. Finally, the containment team would be recommended to confirm the spoofing, widen the search for other similar suspicious activities and work on recovery.

## Integrity & Privacy Controls:
To ensure that all evidence is safe, all the collected files upon capture and everytime they're accessed will be hashed in SHA-256 (NIST AU). To which the evidence will then be securely stored in an access watched area with entries detailing who has access the logs and for how long, as required by NIST SC. The redaction policy will remove personal information that is easily identifiable, the internal routing data and credential strings that were not needed for investigation. This ensures that evidence will remain useable and respectful to the individual's privacy while reducing risk of their personal data being exposed, as practiced in the NIST IR policies.

## Evidence Links

- [In class Activity.pdf](In%20class%20Activity-1.pdf)
- [Weekly Reflection Week 4.pdf](Weekly%20Reflection%20Week%204-1.pdf)

## Reflection: 
Overall, I would love to go back and lookover more NIST policies in the future. Something I would use to further improve how I would react to incidents in technology and maintaining security for not only my personal information but also other people's information. There is still the concern of how much information is safe to redact before it becomes useless to use in an investigation? Would it look like the evidence was altered?
