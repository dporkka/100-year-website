# 100-Year Website

A minimal, dependency-free static website designed to last a century without maintenance.  
All files are self-contained: no databases, no external fonts, no CDNs.

---

## 🚀 Live Deployment

[![Live Site](https://img.shields.io/badge/Live%20Site-Visit-blue?style=for-the-badge&logo=github)](https://<your-username>.github.io/<repo-name>/)

---

## 📦 Permanent Archives

[![GitHub Release](https://img.shields.io/github/v/release/<your-username>/<repo-name>?label=Latest%20Archive&style=for-the-badge&logo=github)](https://github.com/<your-username>/<repo-name>/releases/latest)

[![Wayback Machine](https://img.shields.io/badge/Wayback%20Machine-Snapshot-red?style=for-the-badge&logo=internetarchive)](https://web.archive.org/web/*/https://<your-username>.github.io/<repo-name>/)

[![IPFS](https://img.shields.io/badge/IPFS-View-green?style=for-the-badge&logo=ipfs)](https://ipfs.io/ipfs/<latest-cid>)

[![Arweave](https://img.shields.io/badge/Arweave-Permanent-orange?style=for-the-badge&logo=arweave)](https://arweave.net/<latest-txid>)

![Last Archived](https://img.shields.io/badge/Last%20Archived-<last-archived>-blue?style=for-the-badge)

---

## 📘 How This Works

- Every push to `main` auto-builds:
  - `.zip` archive (GitHub Release)
  - `.warc` web archive
  - SHA256 checksum file
- Archives are uploaded to:
  - GitHub Releases
  - Internet Archive (Wayback Machine)
  - IPFS (via web3.storage)
  - Arweave (permanent blockchain storage)

---

## 🧭 Notes
- Replace `<your-username>` and `<repo-name>` above.  
- The `IPFS` and `Arweave` badges will update each time you push.  
- The `Last Archived` badge updates automatically in CI/CD.