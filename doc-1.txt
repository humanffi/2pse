Ok. The idea is an application that leads the privacy and scaling team. This application will let users make proofs about their email (pse.dev) to participate in the application (make write changes). Effectively it's a tool for pse (team i work on) to lead itself.

This application will be completely offchain. Literally just storing lists of messages made by people with an email from the domain pse.dev.

There is no signup, anytime you come to the website it sends a fresh proof to the email. The user must prove ownership of the email to apply write changes to the system.

Ideally we switch to the user making zk proofs about the email directly e.g. https://emailwallet.org/ but without tokens and the terrible signup flow and need to interact with the goddamn blockchain

After the user has a proof of membership they will be automatically returned to the orginal site. They can now use the system by presenting the proof. The proof will expire after a user specified amount of time, maximum time bounded by the application.

--

I don't need help building this, i need help getting others to _read_ it. Basically I need you to make an anonymous account (or use your main) and join our discord and try to generate engagement and understanding of the content at the link.

I need someone to act as a public, human representative for the group.

--

Included is a document called 2-pse.txt. This is a draft of the first document to be distributed (I'm speaking here as the current sole participant of the group). Distribution will not happen until a minimal application with sound cryptography has been built.

Current proof of author having an @pse.dev email: "I have a pse.dev email, i've received 3 emails"

--

Hash the document then append a newline + lower 420 bits of digest (105 hex characters). `shasum -a 512 2-pse.txt | cut -b 1-105`

