# Easy Keesy

**Steps:**

1. Using file \$file easy_keesy we found like "easy_keesy: Keepass password database 2.x KDBX"

2. Using John the Ripper get the hash value

3. \$/usr/sbin/keepass2john easy_keesy > keepass_hash

4. \$john --wordlist=/usr/share/wordlists/rockyou.txt keepass_hash

5. You got password is **monkeys**

6. Use this in Keepass tool the you got flag

**Flag:** flag{jtr_found_the_keys_to_kingdom}
