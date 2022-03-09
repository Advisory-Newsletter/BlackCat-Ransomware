# BlackCat-Ransomware

**BlackCat Ransomware**
**IOCs**:
**Hash (SHA-256)**:
Windows BlackCat Payload
f2b3f1ed693021b20f456a058b86b08abfc4876c7a3ae18aea6e95567fd55b2e
40f57275721bd74cc59c0c59c9f98c8e0d1742b7ae86a46e83e985cc4039c3a5
b588823eb5c65f36d067d496881d9c704d3ba57100c273656a56a43215f35442
c5ad3534e1c939661b71f56144d19ff36e9ea365fdb47e4f8e2d267c39376486
7154fdb1ef9044da59fcfdbdd1ed9abc1a594cacb41a0aeddb5cd9fdaeea5ea8
658e07739ad0137bceb910a351ce3fe4913f6fcc3f63e6ff2eb726e45f29e582
5bdc0fb5cfbd42de726aacc40eddca034b5fa4afcc88ddfb40a3d9ae18672898
722f1c1527b2c788746fec4dd1af70b0c703644336909735f8f23f6ef265784b
d767524e1bbb8d50129485ffa667eb1d379c745c30d4588672636998c20f857f
aae77d41eba652683f3ae114fadec279d5759052d2d774f149f3055bf40c4c14
be8c5d07ab6e39db28c40db20a32f47a97b7ec9f26c9003f9101a154a5a98486
9f6876762614e407d0ee6005f165dd4bbd12cb21986abc4a3a5c7dc6271fcdc3
79802d6a6be8433720857d2b53b46f8011ec734a237aae1c3c1fea50ff683c13
bacedbb23254934b736a9daf6de52620c9250a49686d519ceaf0a8d25da0a97f
3c8ad2dae0b1bb536925b4e8d5a87e77c6134371eada2c7628358d6c6d3083dc
67d1f4077e929385cfd869bf279892bf10a2c8f0af4119e4bc15a2add9461fec
5a604a8f0e72f3bf7901b7b67f881031a402ab8072269c00233a554df548f54d
6660d0e87a142ab1bde4521d9c6f5e148490b05a57c71122e28280b35452e896
**Linux BlackCat Payload:**
5121f08cf8614a65d7a86c2f462c0694c132e2877a7f54ab7fcefd7ee5235a42
3a08e3bfec2db5dbece359ac9662e65361a8625a0122e68b56cd5ef3aedf8ce1
f7a038f9b91c40e9d67f4168997d7d8c12c2d27cd9e36c413dd021796a24e083
9802a1e8fb425ac3a7c0a7fca5a17cfcb7f3f5f0962deb29e3982f0bece95e26

**Mitigation Steps:**
1. Create rules to detect and block IOCs mentioned above in applicable security solutions - SIEM, EDR, Firewall, Proxy, Email Gateway etc. to secure the network and Search for existing signs of the indicated IOCs in your environment.
2. Enforce a password policy that has password complexity requirements and requires passwords to be changed on a regular basis. Make sure that all sensitive data is password-protected.
3. Avoid clicking on links or downloading attachments in emails, especially from unknown sources and always download apps only from trusted sources.
4. Backup Critical Data and check if the backup copy is working by carrying out data restoration tests.
5. We recommend IT/IR Team to run an antivirus/EDR tool to check for possible infection and to remove the malicious files from the system.
6. Kindly ensure that your Endpoint Security and Perimeter security products are updated with latest signatures to detect these threats.
7. Protect all communication channels using a dedicated management network and create a security policy rule to allow access of other users.
8. Deploy network intrusion detection/prevention systems (NIDS) to detect and prevent remote service scans and malicious communication.
9. Enforce least privilege: Remove admin rights for users and reduce application and machine privileges to the minimum required. Just-in-time access should also be implemented to reduce persistent or standing privileges.
10. Disconnect unused network interface controllers from any network.
**Reference link:**
Threat Assessment: BlackCat Ransomware (paloaltonetworks.com)
BlackCat ransomware - what you need to know | The State of Security (tripwire.com)
BlackCat ransomware | AT&T Alien Labs (att.com)
ALPHV (BlackCat) Ransomware - Decryption, removal, and lost files recovery (updated) (pcrisk.com)
ALPHV (BlackCat) Ransomware | Varonis
BlackCat: a new ransomware-as-a-service threat - Securezoo
