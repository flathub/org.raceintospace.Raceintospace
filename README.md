# Race into Space on Flathub

Flathub is the central place for building and hosting Flatpak builds.
[Race into Space](https://www.raceintospace.org/) is open-sourced old game,
emulating the first human landing on the Moon competition.
Builds [distribution independent packages](https://flathub.org/apps/details/org.raceintospace.Raceintospace) for the game.

Using the Flathub repository
----------------------------

To install applications that are hosted on Flathub, use the following:
```
flatpak remote-add flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install flathub org.raceintospace.Raceintospace
```

To install applications from the beta branch, use the following:
```
flatpak remote-add flathub-beta https://flathub.org/beta-repo/flathub-beta.flatpakrepo
flatpak install flathub-beta org.raceintospace.Raceintospace
```

For more information and more applications see https://flathub.org

Contributing to Flathub
-----------------------

For information on creating packages or reporting issues please see the [contributing page](/CONTRIBUTING.md).

***Note:*** *this repository is not for reporting issues related to the flathub.org website itself or contributing to its development. For that, go to https://github.com/flathub/linux-store-frontend*
