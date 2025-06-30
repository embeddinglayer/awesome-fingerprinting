# awesome-fingerprinting
> **Fingerprinting** is a practice in which websites identify a particular browser (and by extension, a particular user) by collecting and combining distinguishing features of the browser and underlying operating system. - [Mozilla](https://developer.mozilla.org/en-US/docs/Glossary/Fingerprinting)
## About

A collection of browser fingerprinting projects, research, and resources. Intended as a way to aggregate research surrounding the subject.
Please read the [contributions](#contribute) section before opening a pull request.

### Index

- [Libraries & Projects](#libraries--projects)
- [Sites](#sites)
- [Research](#research)
- [Fingerprinting](#fingerprinting-evasion)
- [Other](#other)
- [Contribute](#contribute)
## Libraries & Projects

| Library                                                         | Description                                                    |
| --------------------------------------------------------------- | -------------------------------------------------------------- |
| [FingerprintJS](https://github.com/fingerprintjs/fingerprintjs) | FingerprintJS open source library for fingerprinting browsers. |
| [CreepJS](https://github.com/abrahamjuliot/creepjs)             | A compilation of browser fingerprinting research.              |
| [Supercookie](https://github.com/jonasstrehle/supercookie)      | Fingerprinting visitors via favicons                           |
| [TorZilla](https://github.com/arkenfox/TZP)                     | Fingerprinting Gecko based browsers                            |
| [TLS Fingerprinting](https://github.com/salesforce/ja3)         | TLS Fingerprinting                                             |
| [FingerprintJS BotD](https://github.com/fingerprintjs/BotD)     | Bot detection library                                          |
| [Website Fingerprinting Library](https://github.com/Xinhao-Deng/Website-Fingerprinting-Library) | Pytorch-based open-source library for website fingerprinting attacks |
| [ThumbmarkJS](https://github.com/thumbmarkjs/thumbmarkjs)       | Opensource  alternative to FingerprintJS                       |

## Sites

 - [AmIUnique](https://amiunique.org/)
 - [PixelScan](https://pixelscan.net/)
 - [tls.peet.ws](https://tls.peet.ws/)
 - [DeviceAndBrowserInfo](https://deviceandbrowserinfo.com/)
 - [BrowserLeaks](https://browserleaks.com/)
 - [Chrome Extension Fingerprinting](https://fpmon.github.io/fingerprinting-monitor/)
## Research

 - [Blog: Detecting Privacy Badger](https://adtechmadness.wordpress.com/2020/03/27/detecting-privacy-badgers-canvas-fp-detection/) 
 - [Blog: Salesforce TLS Fingerprinting](https://engineering.salesforce.com/tls-fingerprinting-with-ja3-and-ja3s-247362855967/)
 - [Pixel Perfect: Fingerprinting Canvas in HTML5](https://hovav.net/ucsd/dist/canvas.pdf)
 - [Picasso: Lightweight Device Class Fingerprinting](https://dl.acm.org/doi/pdf/10.1145/2994459.2994467)
 - [Fingerprinting Evasive Bots](https://arxiv.org/pdf/2406.07647)
 - [Blog: How anti-fingerprinting extensions tend to make fingerprinting easier](https://palant.info/2020/12/10/how-anti-fingerprinting-extensions-tend-to-make-fingerprinting-easier/)
 - [Blog: Detecting Headless Browsers](https://antoinevastel.com/javascript/2020/02/09/detecting-web-bots.html)
 - [Blog: Detecting Puppeteer through JS Execution](https://antoinevastel.com/javascript/2019/06/10/monitor-js-execution.html)
 - [WebGPU Fingerprinting Attacks](https://arxiv.org/pdf/2401.04349)
 - [Who Touched My Browser Fingerprint](https://yinzhicao.org/fpmeasurement/imc20.pdf)
 - [Quantifying the Fingerprintability of Browser Extensions](https://securitee.org/files/xhound-oakland17.pdf)
 - [Fingerprinting in Style: Detecting Browser Extensions via Injected Style Sheets](https://www.usenix.org/conference/usenixsecurity21/presentation/laperdrix)
 - [Cookieless Monster](http://consideredharmful.info/papers/Paper%20-%20Hot%20Topics%20in%20Computer%20Security%20-%20Cookieless%20Monster.pdf)
 - [Blog: Browser Finerprinting via CSS](https://fingerprint.com/blog/disabling-javascript-wont-stop-fingerprinting/)
 - [Blog: nullpt.rs](https://www.nullpt.rs/)
 - [Blog: http2 Fingerprinting](https://www.trickster.dev/post/understanding-http2-fingerprinting/)
 - [One Million Site Tracking Measurements](https://www.cs.princeton.edu/~arvindn/publications/OpenWPM_1_million_site_tracking_measurement.pdf)
 - [DeepFPD: Browser Fingerprinting Detection via Deep Learning](https://ieeexplore.ieee.org/abstract/document/10431413)
 - [The Devil is in the Details: Detection, Measurement and Lawfulness of Server-Side Tracking on the Web](https://hal.science/hal-04617727v1/document)
 
## Fingerprinting Evasion

| Library                                                                                    | Description                                                                   | Language   |
| ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- | ---------- |
| [FingerprintSuite](https://github.com/apify/fingerprint-suite)                             | Evade browser fingerprinting for headless browsers.                           | Typescript |
| [Undetected Chromedriver](https://github.com/ultrafunkamsterdam/undetected-chromedriver)   | Modified selenium thats intended to bypass common headless browser checks     | Python     |
| [PuppeteerExtra](https://github.com/berstend/puppeteer-extra)                              | Puppeteer extensions to evade common detections                               | Typescript |
| [Puppeteer With Fingerprints](https://github.com/CheshireCaat/puppeteer-with-fingerprints) | Puppeteer library to modify the browser fp                                    | Javascript |
| [FakeBrowser](https://github.com/kkoooqq/fakebrowser)                                      | Headless Browser Anti-detect                                                  | Javascript |
| [JS Shelter](https://github.com/polcak/jsrestrictor)                                       | Extension to restrict the information gathered through browser fingerprinting | Javascript |
| [Privacy Badger](https://github.com/EFForg/privacybadger)                                  | Extension to block basic fingerprinting techniques                            | Javascript |
| [Chameleon](https://github.com/ghostwords/chameleon)                                       | Deprecated: Extension for blocking browser fingerprinting                     | Javascript |
| [uTLS](https://github.com/refraction-networking/utls)                                      | TLS Impersonation Library                                                     | Golang     |
| [TLS Client](https://github.com/bogdanfinn/tls-client)                                     | Built on top of uTLS offers a simpler wrapper with more profiles              | Golang     |
| [Curl Impersonate](https://github.com/lwthiker/curl-impersonate)                           | TLS Impersonation                                                             | Python     |
| [Reqwest Impersonate](https://github.com/0x676e67/reqwest-impersonate)                     | TLS Impersonation                                                             | Rust       |
| [PRIMP](https://github.com/deedy5/primp)                                                   | TLS Impersonation                                                             | Rust       |
| [CamouFox](https://github.com/daijro/camoufox)                                             | Gecko Based Anti-Detect Browser                                               | C++        |

## Other
- [Brave Anti-Fingerprinting Wiki](https://github.com/brave/brave-browser/wiki/Fingerprinting-Protections)
- [Ungoogled Chromium FP Patches](https://github.com/ungoogled-software/ungoogled-chromium/blob/07e4bdd1da038c7a4423637e6e00ffdbe1695581/patches/extra/bromite/flag-fingerprinting-canvas-image-data-noise.patch#L31)
- [Fingerprint Guidance](https://w3c.github.io/fingerprinting-guidance/)
  
## Contribute
Contributions are welcome. Please follow the general format when creating a pull request.
