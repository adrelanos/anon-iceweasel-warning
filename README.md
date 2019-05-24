# Iceweasel Warning for Anonymity Distributions #

Shows a local homepage saying "Do not use this browser for anything other than
downloading Tor Browser, unless you know what you are doing!" in iceweasel.

For better usability/security.

Safe to remove if you know this.
## How to install `anon-iceweasel-warning` using apt-get ##

1\. Add [Whonix's Signing Key](https://www.whonix.org/wiki/Whonix_Signing_Key).

```
sudo apt-key --keyring /etc/apt/trusted.gpg.d/whonix.gpg adv --keyserver hkp://ipv4.pool.sks-keyservers.net:80 --recv-keys 916B8D99C38EAF5E8ADC7A2A8D66066A2EEACCDA
```

3\. Add Whonix's APT repository.

```
echo "deb http://deb.whonix.org buster main contrib non-free" | sudo tee /etc/apt/sources.list.d/whonix.list
```

4\. Update your package lists.

```
sudo apt-get update
```

5\. Install `anon-iceweasel-warning`.

```
sudo apt-get install anon-iceweasel-warning
```

## How to Build deb Package ##

Replace `apparmor-profile-torbrowser` with the actual name of this package with `anon-iceweasel-warning` and see [instructions](https://www.whonix.org/wiki/Dev/Build_Documentation/apparmor-profile-torbrowser).

## Contact ##

* [Free Forum Support](https://forums.whonix.org)
* [Professional Support](https://www.whonix.org/wiki/Professional_Support)

## Donate ##

`anon-iceweasel-warning` requires [donations](https://www.whonix.org/wiki/Donate) to stay alive!
