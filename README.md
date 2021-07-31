# Home Server / Services 建置筆記

## 簡介

參考多個 Home Server 建置專案，將專案中所建置之服務依據功能分類，並加上簡易說明，做為個人建置之參考。

## 軟體服務功能分類

| 服務名稱 | 分類 | 功能描述 | 連結 |
| :------- | :--- | :------- | :--- |
| AdGuard Home | 廣告封鎖 / 反追蹤 | 知名擋廣告、反追蹤服務| [容器專案頁面](https://hub.docker.com/r/adguard/adguardhome)<br />[GitHub](https://github.com/AdguardTeam/AdGuardHome) |
| calibre-web | 電子書相關 | 電子書管理服務 | [容器專案頁面](https://github.com/linuxserver/docker-calibre-web/pkgs/container/calibre-web)<br />[GitHub](https://github.com/janeczku/calibre-web) |
| kobodl | 電子書相關 | [樂天電子書城](kobo.com) 電子書下載服務 | [容器專案頁面](https://hub.docker.com/r/subdavis/kobodl)<br />[GitHub](https://github.com/subdavis/kobo-book-downloader) |
| changedetection.io | 監控相關 | 監視網頁變動服務 | [容器專案頁面](https://hub.docker.com/r/dgtlmoon/changedetection.io)<br />[GitHub](https://github.com/dgtlmoon/changedetection.io) |
| Portainer | 監控相關 | 容器管理服務 | [容器專案頁面](https://hub.docker.com/r/portainer/portainer-ce)<br />[GitHub](https://github.com/portainer/portainer) |
| Traefik | 網路相關 | HTTP [反向代理](https://zh.wikipedia.org/wiki/%E5%8F%8D%E5%90%91%E4%BB%A3%E7%90%86) 服務 | [容器專案頁面](https://hub.docker.com/_/traefik)<br />[GitHub](https://github.com/traefik/traefik) |
| Traefik Forward Auth | 網路相關 | Traefik 認證轉送服務 | [容器專案頁面](https://hub.docker.com/r/thomseddon/traefik-forward-auth)<br />[GitHub](https://github.com/thomseddon/traefik-forward-auth) |
| traefik-cloudflare-companion | 網路相關         | 自動於 CloudFlare 創建 [CNAME DNS 記錄](https://support.dnsimple.com/articles/differences-a-cname-records/) 服務 | [容器專案頁面](https://hub.docker.com/r/tiredofit/traefik-cloudflare-companion/)<br />[GitHub](https://github.com/tiredofit/docker-traefik-cloudflare-companion) |
| CloudFlare DDNS | 網路相關         | CloudFlare 動態 DNS 服務                                     | [容器專案頁面](https://hub.docker.com/r/oznu/cloudflare-ddns/)<br />[GitHub](https://github.com/oznu/docker-cloudflare-ddns) |
| Unifi-controller | 網路相關 | UniFi 軟體控制器 | [容器專案頁面](https://github.com/linuxserver/docker-unifi-controller/pkgs/container/unifi-controller) |
| WireGuard | 網路相關 | 虛擬私人網路（VPN）服務 | [容器專案頁面](https://github.com/linuxserver/docker-wireguard/pkgs/container/wireguard) |
| Drone | DevOps 相關 | 持續整合（Continuous Integration） / 持續交付 （Continuous Delivery）服務 | [容器專案頁面](https://hub.docker.com/r/drone/drone)<br />[GitHub](https://github.com/drone/drone)<br />[容器專案頁面 - Runner](https://hub.docker.com/r/drone/drone-runner-docker)<br />[GitHub - Runner](https://github.com/drone-runners/drone-runner-docker) |
| Watchtower | DevOps 相關 | 容器更新服務 | [容器專案頁面](https://hub.docker.com/r/containrrr/watchtower)<br />[GitHub](https://github.com/containrrr/watchtower) |
| Duplicati | 檔案相關 | 檔案備份服務 | [容器專案頁面](https://github.com/linuxserver/docker-duplicati/pkgs/container/duplicati)<br />[GitHub](https://github.com/duplicati/duplicati) |
| MinIO | 檔案相關 | 檔案儲存服務 | [容器專案頁面](https://hub.docker.com/r/minio/minio)<br />[GitHub](https://github.com/minio/minio) |
| ProjectSend | 檔案相關 | 檔案分享服務 | [容器專案頁面](https://github.com/linuxserver/docker-projectsend/pkgs/container/projectsend)<br />[GitHub](https://github.com/projectsend/projectsend) |
| Seafile | 檔案相關 | 檔案同步及分享服務 | [GitHub](https://github.com/haiwen/seafile) |
| Samba | 檔案相關 | 區域網路內檔案分享服務 | [容器專案頁面](https://hub.docker.com/r/dperson/samba/dockerfile)<br />[GitHub](https://github.com/dperson/samba) |
| Jackett | 下載相關 | 代理查詢服務 | [容器專案頁面](https://github.com/linuxserver/docker-jackett/pkgs/container/jackett)<br />[GitHub](https://github.com/Jackett/Jackett) |
| Transmission | 下載相關 | BitTorrent 下載服務 | [容器專案頁面](https://hub.docker.com/r/haugene/transmission-openvpn)<br />[容器專案頁面 - Proxy](https://hub.docker.com/r/haugene/transmission-openvpn-proxy/)<br />[GitHub](https://github.com/haugene/docker-transmission-openvpn) |
| Radarr | 影音相關 / 下載相關 | 電影管理服務 | [容器專案頁面](https://github.com/linuxserver/docker-radarr/pkgs/container/radarr)<br />[GitHub](https://github.com/Radarr/Radarr) |
| Plex | 影音相關 | 多媒體管理服務 | [容器專案頁面](https://hub.docker.com/r/plexinc/pms-docker/)<br />[GitHub](https://github.com/plexinc/pms-docker) |

## 參考資料

- [subdavis/selfhosted: rootless docker compose + traefik](https://github.com/subdavis/selfhosted)
