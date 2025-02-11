# ldapconsole

<p align="center">
  The ldapconsole script allows you to perform custom LDAP requests to a Windows domain.
  <br>
  <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/p0dalirius/ldapconsole">
  <a href="https://twitter.com/intent/follow?screen_name=podalirius_" title="Follow"><img src="https://img.shields.io/twitter/follow/podalirius_?label=Podalirius&style=social"></a>
  <a href="https://www.youtube.com/c/Podalirius_?sub_confirmation=1" title="Subscribe"><img alt="YouTube Channel Subscribers" src="https://img.shields.io/youtube/channel/subscribers/UCF_x5O7CSfr82AfNVTKOv_A?style=social"></a>
  <br>
</p>

![](./.github/example.png)

## Features

 - [x] Authenticate with password
 - [x] Authenticate with LM:NT hashes
 - [x] Authenticate with kerberos ticket

## Examples

```sh
$ ./ldapconsole.py -u 'user1' -p 'Admin123!' -d 'LAB.local' --dc-ip 192.168.2.1
```

You can get a list of useful LDAP queries for Windows Active Directory pentesting:

 - https://podalirius.net/en/articles/useful-ldap-queries-for-windows-active-directory-pentesting/

## Contributing

Pull requests are welcome. Feel free to open an issue if you want to add other features.
