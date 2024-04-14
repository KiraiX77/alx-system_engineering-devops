Postmortem Report: Service Disruption on March 15, 2023

    Synopsis:
Our web application suffered a disruption on January 15, 2021, lasting roughly 2 hours due to a server malfunction, rendering the application inaccessible to users. The outage had a considerable impact, preventing users from accessing crucial features during this period.

    Timeline:
1:00 PM - Detection of server malfunction leading to user inaccessibility. 1:15 PM - Issue escalated to development team for investigation. 1:30 PM - Development team identifies hardware failure on one server as the culprit. 1:45 PM - Attempts made to restore service by relocating application to another server encounter complications due to its intricacy. 2:30 PM - Successful migration of application to a new server, restoring service to users. 3:00 PM - Postmortem analysis conducted to dissect the incident and formulate preventative measures.

    Cause:
The primary cause of the outage stemmed from a hard drive failure on one of the servers hosting the application, resulting in server unresponsiveness and user inability to access the application.

    Impact:
The outage had a significant impact, depriving users of essential application functionalities, causing frustration, inconvenience, and potentially leading to financial losses for the company.

    Mitigation:
To minimize the outage's impact, the development team promptly migrated the application to a new server. However, the complexity of the application posed challenges during the migration process, complicating the relocation without encountering further issues.
