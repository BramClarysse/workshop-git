## Generating a ssh-key pair

1. open **git bash**

2. run `ssh-keygen -t ed25519`

3. when asked to prvide a passphrase just press enter

4. when asked to re-enter the passphrase, again just press enter

5. when asked where to store the key, it SHOULD say `C:\Users\<username>\.ssh\...`, press enter again

## Retrieving the public key

1. open windows explorer and navigate to `C:\Users\<username>\.ssh\id_ed25519.pub`

2. open the `id_ed25519.pub` file.

3. copy the content of te file.

## Register the key on GitHub

1. Log in to GitHub

2. Click on your profile in the top rigth corner

3. Navigate to `Settings`

4. Under `Access` navigate to  `SSH and GPG keys`

5. Give your name a key to be registered as. (`school-laptop-<name>`)

6. Paste public key in the input box labled `Key`

7. `Add SSH key`