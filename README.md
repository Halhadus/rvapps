# ReVanced Apps Builder
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/revanced_apks_web)
[![Build Modules](https://github.com/aditya-shri/rvapps/actions/workflows/build.yml/badge.svg)](https://github.com/revanced-apks/build-apps/actions/workflows/build.yml)
[![CI](https://github.com/aditya-shri/rvapps/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/aditya-shri/rvapps/actions/workflows/ci.yml)

Extensive ReVanced builder  

Get the [latest CI release](https://github.com/aditya-shri/rvapps/releases).

<details><summary><big>Features</big></summary>
<ul>
 <li>Support all present and future ReVanced and <a href="https://github.com/inotia00/revanced-patches">ReVanced Extended</a> apps</li>
 <li> Updated daily with the latest versions of apps and patches</li>
 <li> Optimize APKs and modules for size</li>
 <li> Modules</li>
    <ul>
     <li> recompile invalidated odex for faster usage</li>
     <li> do not break safetynet or trigger root detections</li>
     <li> handle installation of the correct version of the stock app and all that</li>
    </ul>
</ul>
Note that the <a href="../../actions/workflows/ci.yml">CI workflow</a> is scheduled to build the modules and APKs everyday using GitHub Actions if there is a change in ReVanced patches. You may want to disable it.
</details>

## To include/exclude patches or patch other apps

 * Star the repo :eyes:
 * Clone/Fork the repo
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)

## Building Locally

```console
$ git clone https://github.com/aditya-shri/rvapps
$ cd rvapps
$ ./build.sh
```

