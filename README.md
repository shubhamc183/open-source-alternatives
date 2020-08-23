# Open Source Alternatives

This repo lists the top open-source alternatives for some of the most common paid software.

## slack

|            FEATURES            |                 RIOT + MATRIX                 |                                               ZULIP                                               |           Mattermost           |             RocketChat            |
|:------------------------------:|:---------------------------------------------:|:-------------------------------------------------------------------------------------------------:|:------------------------------:|:---------------------------------:|
| Text Message                   | YES                                           | Yes                                                                                               | YES                            | YES                               |
| Voice Call                     | YES + Jitsi integration                       | 3rd party integrations                                                                            | YES(Zoom Integration)          | Jitsi integration                 |
| Video Call                     | YES + Jitsi integration                       | Yes(Zoom Integration)                                                                             | YES(Zoom Integration)          | Jitsi integration                 |
| Screen Share                   | NO, only in Jitsi                             | 3rd party integrations                                                                            | YES(Zoom Integration)          | Jitsi integration                 |
| Public/Private Group/channels  |                                               | Yes                                                                                               | YES                            | YES                               |
| File sharing                   | YES                                           | Yes                                                                                               | YES                            | YES                               |
| Setting Status(Online/Away)    | NO                                            | YES                                                                                               | YES                            | YES                               |
| Reliable Push Notification     |                                               | Recommends to use GCM and APNS                                                                    |                                |                                   |
| Website App                    | YES                                           | Yes                                                                                               | YES                            | YES                               |
| Linux App                      | YES                                           | Yes                                                                                               | YES                            | YES                               |
| MacOs App                      | YES                                           | Yes                                                                                               | YES                            | YES                               |
| Windows App                    | YES, only 64 bit                              | Yes                                                                                               | YES                            | YES                               |
| Android App                    | YES                                           | Yes                                                                                               | YES                            | YES                               |
| IOS App                        | YES                                           | Yes                                                                                               | YES                            | YES                               |
| SSO Integration (OIDC)         | OIDC                                          | LDAP, SAML, Google, Gitlab, Github and python-social lib                                          | LDAP only, no OIDC, only in EE | OIDC                              |
| Encryption (e2e or at rest, ?) |                                               | No end to end encyption.  Messages are stored unencypted in database                              |                                | YES                               |
| Remote Object Storage          |                                               | Yes, S3                                                                                           |                                | YES                               |
| Remote Database                |                                               | Yes, Postgres                                                                                     | YES                            | Only MongoDB                      |
| Architecture                   |                                               |                                                                                                   |                                |                                   |
| Components                     |                                               | Redis, Memcached, Postgres, RabitMQ, Tornado, Nginx, Puppet                                       |                                |                                   |
| H.A                            |                                               | NOT EASY                                                                                          |                                |                                   |
| Integrations                   |                                               |                                                                                                   |                                |                                   |
| Overhead Any?                  |                                               | Docker Setup is experimentalhttps://github.com/zulip/docker-zulip Non-docker setup only on Debain |                                |                                   |
| Thoughts                       | Users have to setup encyption keys everywhere |                                                                                                   |                                |                                   |
| Developments                   |                                               | Only Debain, unless Docker is used which is experimental for now                                  |                                |                                   |

**Personsal Recommendation**: RocketChat.

As communication is the backbone of any organization I'll recommend paid service of RocketChat as pricing is cheap and the difference is negligible compared to cloud resources plus the management overhead.
