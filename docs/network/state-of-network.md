import FeedbackComponent from "@site/src/pages/feedback.md";

# Lit Networks

You can set your Lit Network in the LitNodeClient config of the Lit SDK, by passing the network name to the `litNetwork` parameter.

| Name     | Supported Algorithms | Supported Features               | ETA            | Description                                                                                                                                                             | Status                                        |
| -------- | -------------------- | -------------------------------- | -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| Jalapeno | BLS                  | Encryption                       | Live Now       | Centralized alpha network. Persistent, so keys will not be deleted.                                                                                                     | https://jalapeno-status.litprotocol.com/      |
| Serrano  | BLS, ECDSA           | Encryption, Signing, Lit Actions | Live Now       | Deprecated centralized test network. Persistent. Will be turned off someday, but not before July 2024 and we will give ample notice when we pick a date to turn it off. | https://serrano-status.litprotocol.com/       |
| Cayenne  | BLS, ECDSA           | Encryption, Signing, Lit Actions | September 2023 | Centralized test network. Not persistent, keys will be deleted.                                                                                                         | Beta: https://cayenne-status.litprotocol.com/ |
| Manzano  | ECDSA                | Signing                          | November 2023  | Decentralized test network. No persistency guarantees, but will try to keep keys if possible.                                                                           | Coming Soon                                   |
| Habanero | ECDSA                | Encryption, Signing, Lit Actions | December 2023  | Decentralized main network. Persistent, so keys will not be deleted.                                                                                                    | Coming Soon                                   |

<FeedbackComponent/>
