# Awesome-Enterprise-Video-Platform

# Awesome-Enterprise-Video-Platform



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Video Content Management, Live Streaming, Enterprise Broadcasting & Video CMS*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Video Platforms**. These tools help organizations host, manage, deliver, and stream video content for corporate communications, training, virtual events, and knowledge sharing across distributed workforces.



**Examples** include Microsoft Stream, Vimeo Enterprise, Kaltura, Panopto, Brightcove, Vidyard, Wistia, Qumu, Loom, and Dacast (the category leaders).



**Open-source emphasis**: The open-source enterprise video ecosystem is **mature and production-proven**. **Kaltura Community Edition** provides a comprehensive enterprise-grade video platform with live streaming, hosting, transcoding, and monetization capabilities . **MediaCMS** offers a modern, fully featured YouTube-like video CMS built with Python/Django and React, supporting adaptive transcoding, Whisper transcription, and granular access controls . **PeerTube** delivers a decentralized video platform with 600,000+ videos across 1,000+ interconnected instances . **Hovod** provides a self-hosted Mux alternative with HLS transcoding, S3-compatible storage, and AI processing .



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global enterprise video platform market is estimated at **~$8B in 2026**, growing toward **~$20B by 2032**. The sector is **highly fragmented** — Frost & Sullivan identifies **more than 50 long-standing providers, agile innovators, and specialized players**, with companies like Brightcove, Kaltura, Panopto, Vbrick, VIDIZMO, and Vimeo competing across the full video lifecycle . **Microsoft** leads through deep integration of video within its productivity ecosystem, enabling seamless communication across enterprise workflows . **Zoom** is recognized for ease of deployment and large-scale virtual event capabilities . **IBM** differentiates through AI-driven video analytics integrated with Watson . No single vendor holds a winner-take-all position.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Microsoft Stream](https://www.microsoft.com/en-us/microsoft-365/microsoft-stream)** | **Microsoft's enterprise video service (now integrated into SharePoint and Teams).** Video hosting, live events, and AI-powered transcription within Microsoft 365. | **Included with Microsoft 365** (E1/E3/E5) at no additional cost. **Microsoft 365 Business Basic**: **$6/user/month** . | **Included with Microsoft 365** subscription. Requires active M365 license. | **~$281B revenue (Microsoft FY2025)** |

| **[Vimeo Enterprise](https://vimeo.com/enterprise)** | **Professional video hosting and streaming platform.** Enterprise-grade security, analytics, and live streaming. | **Custom enterprise pricing** — quote required. **Vimeo Standard**: **$12/month** (annual). | **Free tier**: **500 MB storage**, 5 GB bandwidth/week. **30-day trial** for premium features. | **Private (~$6B valuation est.)** |

| **[Kaltura](https://corp.kaltura.com/)** | **Comprehensive enterprise video platform.** Live streaming, video hosting, transcoding, monetization, and distribution services. | **Custom enterprise pricing** — quote required. | **Free trial** available on request. **Open-source Community Edition** available. | **Public (KLTR), ~$200M+ revenue est.** |

| **[Panopto](https://www.panopto.com/)** | **Video platform for education and enterprise.** Video recording, live webcasting, content management, and search inside video. | **Custom enterprise pricing** — quote required. **Starting at $49/month** (Software Advice) . | **Free trial** available. **No perpetual free tier**. | **Private (~$200M+ revenue est.)** |

| **[Brightcove](https://www.brightcove.com/)** | **Enterprise video platform.** Live streaming, video hosting, monetization, and distribution. | **Custom enterprise pricing** — quote required. | **Free trial** available. **No perpetual free tier**. | **Public (BCOV), ~$200M+ revenue est.** |

| **[Vidyard](https://www.vidyard.com/)** | **Video marketing and sales platform.** Video hosting, analytics, and personalized video. | **Free tier** available. **Pro**: **$19/month**. **Team**: **$300/month**. | **Free tier**: **5 videos**, 10 minutes/video, 200 views/month . | **Private (~$100M+ raised)** |

| **[Wistia](https://wistia.com/)** | **Video hosting for business.** Marketing analytics, lead generation, and video SEO. | **Free tier** available. **Pro**: **$19/month**. | **Free tier**: **3 videos**, 10 minutes/video, 200 views/month . | **Private (~$100M+ revenue est.)** |

| **[Qumu](https://www.qumu.com/)** | **Enterprise video platform.** Live and on-demand video for internal communications and training. | **Custom enterprise pricing** — quote required. | **Free trial** available. **No perpetual free tier**. | **Private (~$50M+ revenue est.)** |

| **[Loom](https://www.loom.com/)** | **Async video messaging platform.** Screen and camera recording with instant sharing. | **Business**: **$12.50/user/month** (annual). **Business + AI**: **$18/user/month**. | **Free tier**: **25 videos**, 5 minutes/video, 25 viewer limit. **14-day trial** for Business . | **Private (~$1.5B valuation est.)** |

| **[Dacast](https://www.dacast.com/)** | **Live streaming and video hosting platform.** White-label, monetization, and analytics. | **Annual plans start at $2,400/year** ($200/month). **Monthly**: **$79/month** . | **14-day free trial** available . **No perpetual free tier**. | **Private (Dacast)** |



## 🔓 Open-Source GitHub Projects



| Repo | Description | Stars |

|------|-------------|-------|

| **[Kaltura Community Edition](https://github.com/kaltura/server)** — **The flagship open-source enterprise video platform.** Comprehensive suite covering live streaming, video hosting, transcoding, monetization, and distribution . **Open-source version of the commercial Kaltura platform** — designed as a FOSS, powerful, cost-effective alternative to proprietary video management applications . **AGPL-3.0**. | [![Stars](https://img.shields.io/github/stars/kaltura/server?style=social&color=white)](https://github.com/kaltura/server/stargazers) | ~404 |

| **[MediaCMS](https://github.com/mediacms-io/mediacms)** — **Modern, fully featured open-source video and media CMS.** Written in **Python/Django + React** with REST API . **Feature-rich**: video player with resolution switching and playback speed, access control (public/private/group), **automatic Whisper transcription**, multilingual subtitles, in-browser video editing and chapter division, playlist creation, user registration options (public/invitation/closed), resolutions from **144p to 1080p**, multiple compression formats (**h264, h265, vp9**), adaptive quality adjustment, social sharing buttons, embed codes, keyword prediction search, and responsive design . **Docker deployment** with `docker compose -f docker-compose.yaml -f docker-compose.full.yaml up -d` . **AGPL-3.0**. | [![Stars](https://img.shields.io/github/stars/mediacms-io/mediacms?style=social&color=white)](https://github.com/mediacms-io/mediacms/stargazers) | ~2,000 |

| **[PeerTube](https://github.com/Chocobozzz/PeerTube)** — **Decentralized video platform for true digital freedom.** Free, open-source alternative to YouTube with **600,000+ videos across 1,000+ interconnected platforms**, no ads, no tracking . Federation allows instances to share content. **AGPL-3.0**. | [![Stars](https://img.shields.io/github/stars/Chocobozzz/PeerTube?style=social&color=white)](https://github.com/Chocobozzz/PeerTube/stargazers) | ~15,000 |

| **[Hovod](https://github.com/synapsr/hovod)** — **Open-source, self-hosted alternative to Mux.** **Upload & import** via drag-drop or presigned S3 URLs. **Adaptive HLS transcoding** from **360p to 4K (H.264)** with hardware-adaptive FFmpeg workers. **S3-compatible storage** (AWS S3, Cloudflare R2, Backblaze B2, MinIO). **Built-in dashboard** (React SPA) with video management, analytics, embeddable player. **AI processing**: Whisper transcription, auto-generated subtitles & chapters (optional, supports local models). **Analytics**: real-time views, watch time, retention curves, quality/device stats. **Multi-tenancy**: organizations, roles (owner/admin/member), API keys. **Single container** includes API, Worker, Dashboard, embedded MariaDB & Redis — only requirement is S3-compatible storage . | [![Stars](https://img.shields.io/github/stars/synapsr/hovod?style=social&color=white)](https://github.com/synapsr/hovod/stargazers) | ~300 |

| **[Owncast](https://github.com/owncast/owncast)** — **Self-hosted live video streaming and chat server.** Point your live stream at a server you personally control and regain ownership over your content. **Twitch-like interface with built-in chat**. **MIT License** . | [![Stars](https://img.shields.io/github/stars/owncast/owncast?style=social&color=white)](https://github.com/owncast/owncast/stargazers) | ~9,000 |

| **[AVideo (YouPHPTube)](https://github.com/WWBN/AVideo)** — **Open-source, self-hosted video sharing website platform (formerly YouPHPTube).** Supports user accounts, video uploads, streaming, and plugins for features like live broadcasting and advertisement. **PHP-based** . | [![Stars](https://img.shields.io/github/stars/WWBN/AVideo?style=social&color=white)](https://github.com/WWBN/AVideo/stargazers) | ~2,100 |

| **[OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)** — **Real-time streaming server with sub-second latency support.** Offers **WebRTC and Low Latency DASH/HLS** for interactive live streaming. **C++ based** . | [![Stars](https://img.shields.io/github/stars/AirenSoft/OvenMediaEngine?style=social&color=white)](https://github.com/AirenSoft/OvenMediaEngine/stargazers) | ~3,200 |

| **[MediaMTX](https://github.com/bluenviron/mediamtx)** — **Free, open-source media server supporting real-time video streaming, RTSP, RTMP, HLS, and WebRTC.** Enables management and streaming of video from various sources, including RTSP cameras, with low-latency performance. **Go-based** . | [![Stars](https://img.shields.io/github/stars/bluenviron/mediamtx?style=social&color=white)](https://github.com/bluenviron/mediamtx/stargazers) | ~19,000 |

| **[Jellyfin](https://github.com/jellyfin/jellyfin)** — **Open-source media server and client solution.** Streaming of video (and other media) to a variety of devices as a self-hosted alternative to Plex. **GPL-2.0** . | [![Stars](https://img.shields.io/github/stars/jellyfin/jellyfin?style=social&color=white)](https://github.com/jellyfin/jellyfin/stargazers) | ~38,000 |



**Additional open-source options worth exploring:**



| Repo | Description |

|------|-------------|

| **[Opencast](https://github.com/opencast/opencast)** — Open-source solution for automated video capture and distribution at scale. Widely used in higher education . |

| **[MistServer](https://github.com/DDVTech/MistServer)** — Open-source streaming media server supporting multiple protocols (HLS, RTMP, WebRTC, etc.). Focuses on easy setup and compatibility . |

| **[Janus WebRTC Server](https://github.com/meetecho/janus-gateway)** — Open-source, general-purpose WebRTC server (SFU and gateway). Modular, supports video conferencing, streaming, and SIP/RTSP/WebRTC interop . |

| **[SRS (Simple Realtime Server)](https://github.com/ossrs/srs)** — Simple, high-efficiency, real-time video server supporting RTMP, WebRTC, HLS, HTTP-FLV, SRT, and GB28181. **MIT License** . |

| **[Video.js](https://github.com/videojs/video.js)** — Open-source HTML5 video player built with JavaScript and CSS. Cross-browser compatibility, plugins, and responsive design . |

| **[hls.js](https://github.com/video-dev/hls.js)** — JavaScript player library enabling HLS playback in web browsers using Media Source Extensions. Adaptive bitrate streaming engine with low-latency and DRM support . |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Enterprise video platforms handle sensitive organizational content and potentially confidential communications; ensure proper access controls, encryption, and compliance with data protection regulations.

- **Open-source reality**: The open-source ecosystem for enterprise video platforms is **mature and production-proven**. **Kaltura Community Edition** provides a comprehensive FOSS alternative to proprietary video management applications . **MediaCMS** delivers a modern, fully featured YouTube-like CMS with automatic transcription and adaptive transcoding . **PeerTube** powers a decentralized network of 1,000+ interconnected video platforms . **Hovod** provides a self-hosted Mux alternative with HLS transcoding and AI processing . However, **commercial platforms** (Microsoft Stream, Vimeo Enterprise, Kaltura, Panopto, Brightcove) provide **managed infrastructure, enterprise SLAs, and integrated analytics** that open-source alternatives require significant operational investment to match. The open-source path is **genuinely viable** for organizations with strong engineering capacity seeking data sovereignty and cost control.

- **Market fragmentation**: Frost & Sullivan notes the global EVP market features **more than 50 long-standing providers**, with differentiation based on video lifecycle support, live/on-demand capabilities, security, and third-party integrations .



---



**Made for L&D managers, internal communications teams, IT administrators, and enterprise video engineers.**

Let's make enterprise video platforms more open, transparent, and accessible.
