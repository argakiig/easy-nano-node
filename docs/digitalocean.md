# Setup a Nano Node on DigitalOcean

1. Sign up on DigitalOcean [with this link to get 10$ credit for free](https://m.do.co/c/f47f91d0d534)

2. Create a new Droplet

   ![Create Droplet](https://i.imgur.com/KhwfYJQ.png)
   - Select the Docker One-click App
   
     ![Docker App](https://i.imgur.com/ruTU1lU.png)
   - The smallest Droplet is enough, if you want more performance choose a bigger one
   
     ![Droplet](https://i.imgur.com/RFH3iX9.png)
   - Choose a datacenter region that's near to you
   - Additional Options: IPv6
   - Click create and wait till it's ready!

3. You'll get an email with the initial password for the root user and the Droplet IP

4. Connect to your Droplet via SSH
   You can use `ssh root@DROPLET-IP` on Mac/Linux or [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) on Windows ([PuTTY Tutorial](https://kb.site5.com/shell-access-ssh/putty/))

5. You'll be prompted to change your password, choose a strong one

6. Enter the following command to start the setup:
```
bash <(curl -s https://raw.githubusercontent.com/nanotools/easy-nano-node/master/install.sh)
```
7. Done! Please have a look at the [FAQ](faq.md).

## Support

If you find this tool useful show your support by changing your representative or donate to:

    xrb_1ninja7rh37ehfp9utkor5ixmxyg8kme8fnzc4zty145ibch8kf5jwpnzr3r

Thanks a lot!