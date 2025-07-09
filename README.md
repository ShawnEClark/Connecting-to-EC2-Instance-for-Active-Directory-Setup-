# Connecting-to-EC2-Instance-for-Active-Directory-Setup-

### Link to Loom

<https://loom.com/share/5eed58b284bb414389deef0687ed5118>
 

**1. Verify EC2 Instance Status** [0:06](https://loom.com/share/5eed58b284bb414389deef0687ed5118?t=6)

![generated-image-at-00:00:06](https://loom.com/i/d4a44882f6c840dc9acce98dc2a8392e?workflows_screenshot=true)

- Check that the EC2 instance is operational.
- Confirm that the instance state is 'running'.
- Ensure that all health checks have passed (3 of 3).

 

**2. Connect to the EC2 Instance** [0:25](https://loom.com/share/5eed58b284bb414389deef0687ed5118?t=25)

![generated-image-at-00:00:25](https://loom.com/i/3ac93b4b38904e11ac6c6736d6288bd9?workflows_screenshot=true)

- Click on the 'Connect' button for the EC2 instance.
- Choose the Remote Desktop Protocol (RDP) option.

 

**3. Prepare RDP Connection** [0:41](https://loom.com/share/5eed58b284bb414389deef0687ed5118?t=41)

![generated-image-at-00:00:41](https://loom.com/i/e8bb881355a349b4ba9b8985f11d1ede?workflows_screenshot=true)

- Download the RDP desktop file if not already done.
- Retrieve the password for the instance.

 

**4. Decrypt Password** [1:08](https://loom.com/share/5eed58b284bb414389deef0687ed5118?t=68)

![generated-image-at-00:01:08](https://loom.com/i/43217e257df8476cab43e626413c9b6d?workflows_screenshot=true)

- Use the key pair created earlier to decrypt the password.
- You can either upload the private key file or paste it directly.
- For this guide, we will paste the private key.

 

**5. Connect to the Instance** [1:34](https://loom.com/share/5eed58b284bb414389deef0687ed5118?t=94)

![generated-image-at-00:01:34](https://loom.com/i/e9849a8990cb45d39fa7ae669142ade5?workflows_screenshot=true)

- Copy the decrypted password.
- Re-download the RDP file if necessary and paste the password when prompted.

 

**6. Finalize Connection** [2:12](https://loom.com/share/5eed58b284bb414389deef0687ed5118?t=132)

![generated-image-at-00:02:12](https://loom.com/i/3171912a5141435fb8d0f76cf9af27d0?workflows_screenshot=true)

- Click 'Connect' to access the EC2 instance.
- Minimize the loading screen as the connection is established.

 

**7. Ready to Use Active Directory** [2:41](https://loom.com/share/5eed58b284bb414389deef0687ed5118?t=161)

![generated-image-at-00:02:41](https://loom.com/i/e6500f660981457b8b35cc23d7d5fb65?workflows_screenshot=true)

- Confirm that you are connected to the Windows virtual machine.
- Proceed to set up Active Directory on the instance.


