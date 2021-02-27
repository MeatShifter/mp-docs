# SSH

[MPOS](/README.md) uses [OpenSSH](https://openssh.com) by default.
There are
[others](https://wiki.archlinux.org/index.php/Secure_Shell) out there.
You should choose one that works best for you and your
[OS](https://www.google.com/search?safe=active&rlz=1C1CHBF_enUS941US941&sxsrf=ALeKk0049_i8z16eT0lmr6x1nw7y9c2Pgw%3A1614282704470&ei=0P83YICXHJSq5NoPrImH-AY&q=operating+system&oq=operating+system&gs_lcp=Cgdnd3Mtd2l6EAMyBAgjECcyCggAEIcCELEDEBQyBQgAELEDMgIIADICCC4yAggAMgUIABCxAzICCAAyAggAMgIIADoHCCMQsAMQJzoHCAAQsAMQQzoECAAQQzoHCCMQ6gIQJzoICAAQsQMQgwE6CwguELEDEMcBEKMCOgUIABCRAjoHCAAQsQMQQzoICC4QsQMQgwE6BwgAEIcCEBRQl5MEWL_FBGDTyQRoAnACeACAAYcBiAHBC5IBBDE2LjOYAQCgAQGqAQdnd3Mtd2l6sAEKyAEKwAEB&sclient=gws-wiz&ved=0ahUKEwiAv6rZ54XvAhUUFVkFHazEAW8Q4dUDCA0&uact=5).

## Login with SSH

*NOTE -  [Common variables](/variables.md) are used for easy adaptation see MPOS [Documenatation](/README.md)*

Open your preferred [terminal](mpos.netlify.app/docs/terminal) and execute the following.

    $ ssh $USER@$HOST

You can create a file at

    ~/.ssh/config

to store host config for easier login. For instance, normally we would

    $ ssh username@hostaname.com

with the config file, we can now simply

    $ ssh host

You can find an example config [here](https://mpos.netlify.app/ssh-config.md)

## SSH Keys

To create your ssh keys if they haven't been already.

### Linux

    ssh-keygen -b 4096

### Windows

    ssh-keygen -b4096 -A

---

###### References

[Archlinux](https://wiki.archlinux.org/index.php/OpenSSH#Client_usage)
| [OpenSSH](https://www.openssh.com/)
| [Google](https://www.google.com/search?safe=active&rlz=1C1CHBF_enUS941US941&sxsrf=ALeKk01wzABEXLXZ6J9BTlv_ObKrJZeoRw%3A1614282698105&ei=yv83YIbsBY3j5NoPhc-SgAg&q=ssh&oq=ssh&gs_lcp=Cgdnd3Mtd2l6EAMyBAgjECcyBAgjECcyBAgjECcyBAgAEEMyCggAEIcCELEDEBQyBwgAELEDEEMyCggAEIcCELEDEBQyBwgAELEDEEMyBQgAELEDMgIIADoHCCMQsAMQJzoHCAAQRxCwAzoGCAAQFhAeOgcIABCHAhAUOggILhDHARCvAToICAAQsQMQgwFQ7xhYjyhgmCxoAXACeACAAWWIAY0HkgEEMTEuMZgBAKABAaoBB2d3cy13aXrIAQnAAQE&sclient=gws-wiz&ved=0ahUKEwiG-aXW54XvAhWNMVkFHYWnBIAQ4dUDCA0&uact=5)
