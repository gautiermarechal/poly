---
title: "Cryptography and its implication in the past, in the present, and in the future"
date: 2021-03-24T23:36:38+02:00
cover:
  image: "/images/cryptography-implications/cryprography-0.jpeg"
  alt: "Cryptography"
  caption: "Antique keys"
  relative: false
categories:
  - Cryptography
  - Bitcoin
  - Computer Science
  - Science
---

Human success on the planet has been made possible thanks to our ability to communicate in the purpose of solving complex problems as groups. However, some groups have not always agreed together, causing multiple conflicts that shaped our history. Cryptography has shown itself as a tool to make communication between two parties secret to any other partie. This tool has been way more important than we think, and we will explore how it shaped history in the past, in the present and in the future. In a world where huge entities and governments are more and more present in individuals’ daily lives, securing data with cryptography will be an essential tool to have in hand.

Cryptography has existed for thousands of years.

The first form of cryptography has been observed in ancient Egypt on tomb walls in 1900 BC. Unusual symbols were carved on the tomb of Knumotep II to confuse the reader and enhance mystery.

Moreover, in 5 BC, spartans created a cryptographic device called a Scytale. The tool was a stick wrapped with a piece of leather carrying the message. It was readable only when wrapped on this particular diameter cylinder allowing letters to align. The recipient of the message needed the exact same diameter Scytale to decrypt the message.

![Spartan Scytale](/images/cryptography-implications/cryptography-1.png "Spartan Scytale")

Another great example is the Caesar cipher, named after the emperor who created this technique to secretly communicate in an era of treachery. The technique is known as substitution, consisting of each letter being replaced with another that only the recipient knows.

![Caesar Cipher](/images/cryptography-implications/cryptography-2.png#center "Caesar Cipher")

There are multiple other historic examples of cryptography used in the ancient world, that allowed interactions to remain secret between two parties.

During history, cryptography was often used by the governing monarchs or emperors to communicate internally. The communications encryptions were often dedicated for military planning or any religious piece of writings. Julius Caesar used his famous cipher to organize strategies with his generals. The Greek Magical Papyri from 100 BCE contained rituals, hymns and spells written in a special language with ancient greek that was impossible to read for a normal reader. Creating encrypted messages was meant to keep communication secrets within groups, and form exclusivity for members of the group. The ciphers were only known by these members.

However, in the 700s, Al-Khali, an arab philologist wrote the first documentation of a cryptographic techniques standard called Book of Cryptographic Messages. This was the first time a formal documentation of techniques existed. This gave a new approach vision to cryptography. The science continued to be nourished in the 800s, when Al-Kindi invented frequency analysis, the measure of letters frequency in the arab language. This was the first ever known cryptography breaking technique ever invented and marked the start of the field. However, we would not see any major advances until WW2.

![Generic Frequency Analysis Table](/images/cryptography-implications/cryptography-3.png#center "Generic Frequency Analysis Table")

During WW2, Germans created and used the famous rotor machine called Enigma. The machine was basically made of a keyboard, a lampboard and a set of rotors in between. Typing a letter on the keyboard would lighten a different letter on the lampboard. This substitution was made possible via specific wiring controlled by the rotor, that would change the connections depending on the configuration that the user could change manually. This allowed the machine to operate a polyalphabetic substitution, meaning that each letter could be replaced by different letters. The alphabet was replaceable by multiple alphabets. All the functioning was electromechanical.

![Enigma Machine used by Nazis during WW2](/images/cryptography-implications/cryptography-4.png#center "Enigma Machine used by Nazis during WW2")

This machine was a major technological advancement at the time, and so was its breaking by the British with Ultra. Germans communicated military information via morse codes on radio that was written initially with Enigma. Communications were unbreakable and allowed Germans to take advantage of the field. When the British broke the machine, Allies took back the advantage to win and end the war. According to estimates, the war was shortened by two to four years with the breaking.

All the previous cryptographic techniques or machines were mainly using lexicography and hardware. With the arrival of computing, the same principle of hiding messages had been translated to software.

Modern cryptography makes use of mathematics to encrypt data into an unreadable data. The message sent is encrypted into a set of unreadable characters, via a complex mathematical algorithm.

There are two main types of cryptography techniques nowadays: symmetric-key and asymmetric-key (or public-key cryptography).

## Symmetric Key

Symmetric key cryptography is when the sender and the receiver share the same key encrypt and decrypt the message. If Alice sends a message to Bob, the message will be encrypted with Alice’s key and Bob will use this same key to decrypt the message. Symmetric keys are implemented as three different methods: block ciphers, stream ciphers and hash functions.

![Symmetric Key Cryptographic Method Schema](/images/cryptography-implications/cryptography-5.png#center "Symmetric Key Cryptographic Method Schema")

To make it simple, block ciphers are encryption of fixed-length f blocks of texts and stream ciphers are encrypting each single character by combining them to digits in the key stream.

![Block Cipher Schema](/images/cryptography-implications/cryptography-6.png#center "Block Cipher Schema")

![Stream Cipher Schema](/images/cryptography-implications/cryptography-7.png#center "Stream Cipher Schema")

Both are dictated by a deterministic algorithm.

A deterministic algorithm is an algorithm that, given an input, will always produce the same output with that specific input.

Finally, hash functions are one way functions that will encrypt a message input into a fixed array output of digits. Hash functions are not reversible and the only way to find the input is to brute force the function and match all the results with the fixed array we have. However, the number of possibilities is enormous. This is what makes hash functions a powerful tool.

![Hash Function Schema](/images/cryptography-implications/cryptography-8.png#center "Hash Function Schema")

The main problem with symmetric key cryptography is to exchange the key between the sender and the recipient. This allows for security breach as usually nowadays, cryptography is operated on the internet and the two parties cannot meet in secret to exchange the key. This is where asymmetric cryptography comes into play.

## Asymmetric Key

In 1976, researchers highlighted the security issue of having one single key for encryption and decryption and proposed a system of a public key and private key pair. An encrypted communication would use a public-key to encrypt the message, and a private key to decrypt it. The public key can be distributed freely whereas the private key must remain secret. Both keys are mathematically related but this relation is complex and requires a difficult problem solving.

The main advance in this method is that the receiver who uses the public key to decrypt the message, in reality verifies that the message has been created by someone who possesses the corresponding private key.

![Asymmetric Key Schema](/images/cryptography-implications/cryptography-9.png#center "Asymmetric Key Schema")

Let’s say, Alice and Bob both have key pairs. Alice knows Bob’s public key and the contrary is also true. If Alice encrypts a message with Bob’s public key and sends it to Bob, Bob will be able to use his private key to verify that the message has been sent and encrypted by Alice with Bob’s public key. Therefore, the communication is completely secure and both parties do not need to exchange anything privately. Everything is based on verification. If a third party, named John intercepts the message, he will know Bob’s public key but won’t be able to verify the message with its private key. Because a pair of keys are mathematically related, John’s private key does not correspond to Bob’s public key. He would need Bob’s private key to decrypt the message.
This cryptography solution based on verification has been a groundbreaking advance in the field, but also in history in general.

As stated above, cryptography has always been used in history by large instances as military forces and governments. With the arrival of computing and the internet, the power is incrementally shifting from vertical to horizontal. Individuals nowadays have way more power than before compared with high instances as governments. The equality of opportunities has significantly increased with the internet, opening a large set of path alternatives for people.

Thanks to the internet people are more free, but still large entities control a large amount of internet users. Huge companies as Google, Facebook or Amazon possess private data of their users, breaking the decentralized model cryptography has to offer. However, this is subject to change. People’s trust toward these giants is shifting, as the awareness of the situation is increasing. Scandals as Cambridge Analytica highlight the excess of power these instances possess.

The internet has become a panopticon. A panopticon was a type of architecture used in prisons, designed by the philosopher Jeremy Bentham. The concept was that a single guard was placed in the middle of a circular room, allowing all the prisoners to be possibly observed by the guard. It was physically impossible for the guard to monitor all the inmates. The main idea was that the inmates would feel constantly observed, not knowing where the guard would look at a certain point in time. They would constantly act as they were being watched. This is exactly the same feeling the internet is giving to people. A psychological war is constantly engaged in our private activities on the web.

![Panopticon Prison](/images/cryptography-implications/cryptography-10.png#center "Panopticon Prison")

The model of huge internet companies might start shifting. As an example, the app Signal to communicate privately marks the arrival of a new model: an open-source NGO, relied entirely on donations and verification of peer-reviewers. Reviewers who are people like you and me, verify that the Signal cryptographic protocols used to encrypt message communications are correct and trusty. This model starts to grab the attention of many users. In January 2021, 20 million users shifted from Whatsapp to Signal after Facebook announced it would be able to access Whatsapp data.

This model of power is also (mostly) present in Bitcoin. Created in 2009, Bitcoin fundamentals rely mostly on cryptography. Asymmetric key cryptography is used in Bitcoin, allowing users to privately transact, stopping any third party as a government or a company to interfere in the process. It is the first time in history that individuals have this power in their hands. All thanks to mathematics and cryptography.

If a communication tool and a currency become completely sovereign, distinct from a centralized instance, what is the limit? This model can be applicable to any other online tool with cryptography being the main pillar of this revolutionary system.
