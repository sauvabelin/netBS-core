# NetBS - Core

This repository holds the core part for the NetBS Stack. Please don't install it from here, prefer cloning the
NetBS repository, which uses this repository as submodule and comes already pre-configured.

## Why submodules ?

Because at the time I write those lines, the NetBS is used by both la BS des familles and la TDGL, and maintaining two
complete stacks became annoying to say the least. Dividing it into submodules allows me to start 2 projects based on
NetBS repository, build separate applications in src/ and when I have to update something in the core part, I simply
pull the submodule.

## Why not publish bundles on packagist?
Because I takes time, I do it in my free time and the NetBS won't ever gain enough visibility to see any benefit of
putting it on packagist.

## Which Symfony version is this for?
Updated to Symfony 5.2
