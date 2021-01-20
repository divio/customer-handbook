Setting up an SSH key
=====================

Divio uses a secured shell or SSH to securely authenticate the remote servers and services it interacts with.  
Hence, to be able to connect to the Divio platform, you need to set up an SSH key. 

Before setting up a new SSH key, you may want to check if you have already set up SSH keys. Open your terminal and list them if they exist. ::

  ls -al ~/.ssh

.. note::
 At the moment, Divio supports the RSA and ECDSA, but not the ED25519.


Generating an SSH Key
----------------------

If you have not done it yet, open a `GitHub account <https://github.com/>`_.
To generate a new SSH private and public key pair, open your terminal and 
paste the following text, substituting the email used for GitHub account.

For RSA ::

  ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

For ECDSA ::

  ssh-keygen -t ecdsa -b 521 -C "your_email@example.com"

If you wish to keep the default private/public key filenames, press enter when prompted. 
Enter a strong `passphrase` which will be used to encrypt the private key. 

Copy the public key, for example for RSA ::

  pbcopy < ~/.ssh/id_rsa.pub

and add it to the SSH Keys in the `Divio Control Panel <https://control.divio.com/account/ssh-keys/>`_. 

To verify if the SSH is properly added, paste the following text in your terminal and you should be able to see 
*No interactive access*. ::

  ssh -T git@git.divio.com  


To learn more on how you can setup private and public SSH key, we recommend you to 
`GitHub's excellent guide on setting up SSH Keys <https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh>`_.
