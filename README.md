# khalilDraoui.github.io

Personal portfolio of **Khalil Draoui**, a cybersecurity engineering student (eJPT · CCNA Security · Cisco CyberOps), built as an interactive Kali Linux desktop.

🔗 **Live:** https://khalildraoui.github.io

## Deep links
| Link | Opens |
|---|---|
| `/#soc` | SOC console: healthcare threat-hunting lab with incident replay |
| `/#ci` | DevSecOps pipeline: security-gated Jenkins build |
| `/#cap` | Firewall lab: live packet capture with zone rules |
| `/#pdf` | Resume |
| `/#mail` | Compose an email |

## Deploy (GitHub Pages)
1. Create a public repo named exactly `khalilDraoui.github.io`.
2. Upload `index.html`, `Khalil_Draoui_Resume.pdf` and this README to the root.
3. Go to **Settings → Pages**, set the source to **Deploy from a branch**, then pick `main` / `/ (root)`.

There's no build step: it's one self-contained HTML file.

## Editing content
Everything lives in `index.html`:
- File contents (`SOC_MD`, `LOG_AMSYS`, `EDU`, `TOOLS`, `PLAN`, …) are constants near the top of the `<script>`.
- Terminal commands are in the `CMD` object.
- The boot screen plays once per browser session. Use the power button (top right) to replay it.
