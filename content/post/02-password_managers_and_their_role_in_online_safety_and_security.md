+++
author = "Sajid Mahmood"
title = "Password Managers and their Role in Online Safety and Security"
date = "2022-06-11"
description = "Your guide to online safety, and password hygiene"
thumbnail = "images/passwordmanagert.png"
tags = [
    "password manager",
    "Cybersecurity",
]
draft = false
+++

# Table of Contents

1.  [ What are Password Managers?](#org0282a61)
2.  [ What Problem they Solve?](#org77ab2d7)
3.  [ Features of Password Managers](#orgf5f3152)
4.  [ Proprietary Password Managers](#org2b44579)
    1.  [ LastPass:](#org3e10c3f)
    2.  [ 1Password:](#org75d500d)
    3.  [ Dashlane:](#org0c07622)
5.  [ FOSS Password Managers](#orgd0c1daf)
    1.  [ KeePass:](#orga70bc55)
    2.  [ Padloc:](#org1e010a7)
    3.  [ Bitwarden:](#org7b53484)
    4.  [ Some honorable mentions:](#org0cf9e0c)
6.  [ Why to use FOSS Password Managers?](#org490b037)
7.  [ Bitwarden: A Short Intro](#orgc79e182)
8.  [ Bitwarden: Premium Features](#orgace83e5)
9.  [ Bitwarden in Action](#orgc475718)
10. [ Conclusion](#orgcaaf61b)



<a id="org0282a61"></a>

Checkout the video as well:

{{< youtube MH5NQLb11mY >}}

# 1) What are Password Managers?

A computer program which acts as a wallet for storing, managing passwords as well as offer the feature to generate strong and complicated passwords for applications and services.

<center><div style="max-width:800px; max-height:600px">
  <img src="/images/passwordmanager.png">
</div></center>


<a id="org77ab2d7"></a>

# 2) What Problem they Solve?

As a human being, we have a tendency to forget things. Due to this reason people lean towards using bad passwords, or use single password for every service or application they use. Password Managers not only resolve this issue, but over that, they offer multiple other features as well which will be discussed later on.


<a id="orgf5f3152"></a>

# 3) Features of Password Managers

Here are some features common to most of the Password Managers either they are Free and Open Source or proprietary:

-   You don&rsquo;t have to remember all the passwords.
-   Most of them can auto generate highly secure passwords, depending upon your need, you can tweak the password generation with switches to make them highly secure and unguessable.
-   You can add your family members to your account, so they can inherit your account in the case of any emergency.
-   They save time by autofilling the password field with your email or username for that site or service.
-   Almost every Password Manager offer cross-platform solutions, so you can use them whenever you want, like, on Mobile Phone(Android, iOS), OSes(Linux, Windows or Mac) or browsers(Brave, Firefox, Chrome, Edge or Safari)
-   They protect your identity by giving you choice of password segmentation across different applications or services in case of data breaches.
-   They have a master password, which acts as a master key to all your information stored in the Password Managers.
-   Apart from that, to provide extra security to your wallet, they offer 2FA or MFA.
-   These passwords are stored in the encrypted databases secured with the master password.
-   Some Open Source Password Managers offer self-hosted solutions for your passwords, but how secure the self-hosted solutions will be, is also debatable depending upon the person&rsquo;s skills and knowledge who is deploying that server.
-   Most of the Password Managers offer saving your credit/debit cards to the wallet and make your online shopping experience seamless.
    
    > Note: Self-hosted Password storing solutions are out of the scope of this blog, we may discuss them later on when we&rsquo;ll talk about advanced methods of Password storage.


<a id="org2b44579"></a>

# 4) Proprietary Password Managers

Following are some proprietary Password Managers, we won&rsquo;t discuss them in details but do cover some of their key features:


<a id="org3e10c3f"></a>

## 1) LastPass:

LastPass offers freemium services, with limited access to the features for their free tier users, but offer great deal of services to the premium members. It is a bit costly compared to what we have in free as well in the form of Padloc or Bitwarden. A [critical vulnerability](https://www.zdnet.com/article/lastpass-bug-leaks-credentials-from-previous-site/) was reported in 2019. According to [Forbes](https://www.forbes.com/sites/thomasbrewster/2019/04/10/what-happened-when-the-dea-demanded-passwords-from-lastpass/?sh=7b25ed387ebe), Drug Enforcement Administration(DEA) demand to access a criminal password record was rejected by LastPass due to zero knowledge encryption in place for customers.

<center><div style="max-width:119px; max-height:119px">
  <img src="/images/lastpass.png" /><a href="  https://www.lastpass.com/">LastPass.com</a>
</div></center>

<a id="org75d500d"></a>

## 2) 1Password:

1Password do use some FOSS software for their services, but their app itself is proprietary. They have only premium version with limited trial period. Their premium version is also a bit costly. A plus point for them is their positive attitude and support about Open Source.

<center><div style="max-width:119px; max-height:119px">
  <img src="/images/1password.jpeg" /><a href="  https://1password.com/">1Password.com</a>
</div></center>

<a id="org0c07622"></a>

## 3) Dashlane:

Dashlane offers limited free version with app support for all major OSes. The negative for me is lack of Linux client. The premium version is also a bit costlier than other proprietary premium offerings discussed above. It also doesn't offer password sync for free tier users.

<center><div style="max-width:119px; max-height:119px">
  <img src="/images/dashlane.png" /><a href="  https://www.dashlane.com/">Dashlane.com</a>
</div></center>

<a id="orgd0c1daf"></a>

# 5) FOSS Password Managers

Following are some Open Source offerings:


<a id="orga70bc55"></a>

## 1) KeePass:

It is primarily designed for Windows, but KeePassX can run on Linux as well. It is an offline Password Manager that can also be run from a USB stick. Some unofficial clients are also available for almost every Operating System. If you like minimalist Program with GNU philosophy of doing one thing great, you can consider this option.

<center><div style="max-width:119px; max-height:119px">
  <img src="/images/keepass.jpeg" /><a href="  https://keepass.info/">KeePass.Info</a>
</div></center>

<a id="org1e010a7"></a>

## 2) Padloc:

Padloc is relatively a new entry in the Password Managers realm. It offers clients for all most every OS. It offers cloud-based services. It as a freemium model. Depending on your needs you can choose either of them. Its free offering includes ability to save upto 50 passwords for sync up-to 2 devices, but premium version offers unlimited password storage with 1GB encrypted file storage and synchronisation across multiple devices.

<center><div style="max-width:119px; max-height:119px">
  <img src="/images/padlock.png" /><a href="  https://padloc.app/">Padloc.App</a>
</div></center>


<a id="org7b53484"></a>

## 3) Bitwarden:

Bitwarden is my favorite with plethora of features. Its free version offers almost everything, with exception of TOTP and encrypted file sharing, and security reports etc. But amazing thing is, its premium version is also dirt-cheap for 10$ per year. We discuss Bitwarden in details in the later part of the blog.

<center><div style="max-width:119px; max-height:119px">
  <img src="/images/bitwarden.png" /><a href="  https://bitwarden.com/">BitWarden.com</a>
</div></center>

<a id="org0cf9e0c"></a>

## 4) Some honorable mentions:

-   Firefox built-in password manager is also pretty good, but it doesn&rsquo;t include any client other than built-in integration with Firefox.

-   Brave also offer password manager which can sync across different Brave-browsers using the internal sync facility as it doesn&rsquo;t offer any cloud-based synchronisation.


<a id="org490b037"></a>

# 6) Why to use FOSS Password Managers?

Pros of using Free and Open Source Password Managers.

-   They have audit-able source code, which makes them more secure than their proprietary counterparts as more eyes on the code means less bugs, theoretically.
-   Security flaws and Zero-Days can be found quickly and patched within no time.
-   No hidden trackers or back-doors.
-   Free in terms of freedom as well as their premium features are also dirt-cheap compared to proprietary Password Managers.
    
    > Disclaimer: These pros only apply to those FOSS programs which are well-reputed and used by large number of people. But if you use some unknown software whose users are only you and the developer, realistically chances are, you&rsquo;re at more risk than using a proprietary well-known counterpart.


<a id="orgc79e182"></a>

# 7) Bitwarden: A Short Intro

It&rsquo;s arguably the best Password Manager in every category with zero knowledge encryption. It has a free tier offering with almost every feature you can think of. Some of them are:

-   Open Source
-   Sync across unlimited devices.
-   Store Unlimited Passwords, credit/debit cards, notes etc.
-   Free sharing for 2 Users
-   Encrypted Text sharing to safely share your logins with loved ones.
-   Basic two-step login.
-   Encrypted offline backups with cloud offerings too.
-   Ability to self-host your passwords.
-   Username and password generator.
-   Email alias integration
-   Always free
    etc.


<a id="orgace83e5"></a>

# 8) Bitwarden: Premium Features

Bitwarden offers a premium version with some added features, in dirt cheap price with less than $1 per month.

-   Advanced 2FA, YubiKey integration, FIDO2, Duo for password authentication to your account.
-   Encrypted file attachments up to 1 GB
-   Vault Health Reports
-   Priority Customer Support
-   Bitwarden Authenticator for TOTP support.

Website: <https://bitwarden.com/>

> What is TOTP and its importance for online safety and security will be discussed in coming blog/video.


<a id="orgc475718"></a>

# 9) Bitwarden in Action

To see Bitwarden in action, checkout the linked video.


<a id="orgcaaf61b"></a>

# 9) Conclusion

Password Managers can relieve your stress of remembering hundreds of passwords by heart, but at the same time, you should be careful in selecting your Password Manager of choice, by looking at their track record and also being conscious about their encryption methodology, specially if they are offering cloud-based solutions.

