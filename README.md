> # MAXON Cinebench 23.200 
> ![image](https://community.chocolatey.org/content/packageimages/cinebench.23.200.png)

> Cinebench is a real-world cross-platform test suite that evaluates your computer's hardware capabilities. Improvements to Cinebench Release 23 reflect the overall advancements to CPU and rendering technology in recent years, providing a more accurate measurement of Cinema 4D's ability to take advantage of multiple CPU cores and modern processor features available to the average user. Best of all: It's free.

## All Checks are Passing

✓ Validation Testing Passed

✓ Verification Testing Passed

✓ Scan Testing Successful: No detections found in any package files

Deployment Method: Individual Install, Upgrade, & Uninstall

To install MAXON Cinebench, run the following command from the command line or from PowerShell:

`choco install cinebench`

To upgrade MAXON Cinebench, run the following command from the command line or from PowerShell:

`choco upgrade cinebench`

To uninstall MAXON Cinebench, run the following command from the command line or from PowerShell:

`choco uninstall cinebench`

> Private CDN cached downloads available for licensed customers. Never experience 404 breakages again! [Learn more...](https://docs.chocolatey.org/en-us/features/private-cdn)

> This package was approved by moderator mwallner on 05 Feb 2021.

> Cinebench is the perfect tool to compare CPU and graphics performance across various systems and platforms.

Only compatible with 64-bit Operating Systems.

## Files
`tools\chocolateyInstall.ps1`
~~~
$packageName = 'cinebench'
$url = 'http://http.maxon.net/pub/cinebench/CinebenchR23.zip'
$md5Hash = 'ab936936b97c7b54a05fda185f846bf8'

$installDir = $env:chocolateyPackageFolder

Install-ChocolateyZipPackage -PackageName "$packageName" -Url "$url" -UnzipLocation "$installDir" -checksum $md5Hash
Install-ChocolateyDesktopLink -TargetFilePath "$installDir\Cinebench.exe"
~~~

## Virus Scan Results
[Log in](https://community.chocolatey.org/users/account/LogOn) or click on link to see number of positives.

* [cinebench.23.200.nupkg (1cd9a03d5fd1)](https://www.virustotal.com/gui/file/1cd9a03d5fd1313350483b56aa312ff5401a8f2ac01e4397125ecbcd3d8b7517/detection/f-1cd9a03d5fd1313350483b56aa312ff5401a8f2ac01e4397125ecbcd3d8b7517-1612261649) - ## / 63

* [CinebenchR23.zip (fff6d34b8f69)](https://www.virustotal.com/gui/file/fff6d34b8f696de64a534fc9f0788ec1e9f1bda880a88aed92df8b96d1797c42/detection/f-fff6d34b8f696de64a534fc9f0788ec1e9f1bda880a88aed92df8b96d1797c42-1612159571) - ## / 54

> In cases where actual malware is found, the packages are subject to removal. Software sometimes has false positives. Moderators do not necessarily validate the safety of the underlying software, only that a package retrieves software from the official distribution point and/or validate embedded software against official distribution point (where distribution rights allow redistribution).
Chocolatey Pro provides [runtime protection](https://docs.chocolatey.org/en-us/features/virus-check) from possible malware.

## Version History

|Add to Builder [?](https://docs.chocolatey.org/en-us/community-repository/script-builder)|Version Downloads|Last Updated|Status|
|-----------------|-----------------|-----------------|-----------------|
|[MAXON Cinebench 23.200](https://community.chocolatey.org/api/v2/package/cinebench/23.200)|7066|Monday, February 1, 2021|Approved|
|[MAXON Cinebench 20.0.0.1](https://community.chocolatey.org/packages/cinebench/20.0.0.1)|4917|Tuesday, October 1, 2019|Approved|
|[MAXON Cinebench 20.0](https://community.chocolatey.org/packages/cinebench/20.0)|1218|Tuesday, June 18, 2019|Approved|
|[MAXON CINEBENCH 15.038](https://community.chocolatey.org/packages/cinebench/15.038)|2599|Monday, January 30, 2017|Approved|
|[MAXON CINEBENCH 15.0.0.20140816](https://community.chocolatey.org/packages/cinebench/15.0.0.20140816)|718|Friday, August 15, 2014|Unknown|
|[MAXON CINEBENCH 15.0](https://community.chocolatey.org/packages/cinebench/15.0)|547|Thursday, August 14, 2014|Unknown|

## Copyright
Copyright MAXON Computer GmbH, MAXON Computer Inc., MAXON Computer Ltd.

## Release Notes

* Cinebench R23 now supports Apple’s M1-powered computing systems.
* Cinebench is now based on the latest Release 23 code using updated compilers, and has a minimum runtime activated by default (previously hidden in preferences).
* Cinebench R23 provides improved benchmark accuracy for current and next generation CPUs to test if a machine runs stable on a high CPU load, if the cooling solution of a desktop or notebook is sufficient for longer running tasks to deliver the full potential of the CPU, and if a machine is able to handle demanding [real-life 3D tasks.](https://www.maxon.net/en/article/maxon-announces-cinema-4d-r23)

## Dependencies
This package has no dependencies.

## Discussion for the MAXON Cinebench Package

### Ground Rules:
* This discussion is only about MAXON Cinebench and the MAXON Cinebench package. If you have feedback for Chocolatey, please contact the [Google Group](https://groups.google.com/group/chocolatey).
* This discussion will carry over multiple versions. If you have a comment about a particular version, please note that in your comments.
* The maintainers of this Chocolatey Package will be notified about new comments that are posted to this Disqus thread, however, it is NOT a guarantee that you will get a response. If you do not hear back from the maintainers after posting a message below, please follow up by using the link on the left side of this page or follow this link to [contact maintainers](https://community.chocolatey.org/packages/cinebench/ContactOwners). If you still hear nothing back, please follow the [package triage process](https://docs.chocolatey.org/en-us/community-repository/users/package-triage-process).
* Tell us what you love about the package or MAXON Cinebench, or tell us what needs improvement.
* Share your experiences with the package, or extra configuration or gotchas that you've found.
