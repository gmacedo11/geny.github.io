
# 🌐 Personal Website – genymacedo.com

This website is powered by **Jekyll + GitHub Pages**, deployed live at:  
🔗 https://genymacedo.com

---

## ✅ Domain & HTTPS Status

- **Domain:** `genymacedo.com`
- **DNS Provider:** GoDaddy
- **SSL Certificate:** Auto-issued via GitHub Pages (Let's Encrypt)
- **HTTPS Redirect:** Enabled after DNS validation

---

## 🔍 Periodic SSL & Security Checks

### SSL Labs  
🔗 [Check SSL](https://www.ssllabs.com/ssltest/)  
Enter `genymacedo.com` and confirm:
- ✅ Valid certificate
- ✅ HTTPS support
- ✅ Grade A or better

### WhyNoPadlock  
🔗 [Check for Mixed Content](https://www.whynopadlock.com)  
Use: `https://genymacedo.com`  
Ensure:
- 🔒 HTTPS is enforced
- ❌ No insecure (HTTP) elements

---

## 📊 Continuous Monitoring (Optional)

🛠 [UptimeRobot](https://uptimerobot.com)
- Set up HTTPS monitor
- Target: `https://genymacedo.com`
- Receive alerts via email if site goes down

---

## ⚙️ DNS Configuration (GoDaddy)

| Type | Name | Value                     | TTL    |
|------|------|---------------------------|--------|
| A    | @    | 185.199.108.153           | 1 Hour |
| A    | @    | 185.199.109.153           | 1 Hour |
| A    | @    | 185.199.110.153           | 1 Hour |
| A    | @    | 185.199.111.153           | 1 Hour |
| CNAME | www | gmacedo11.github.io       | 1 Hour |

> ⚠️ Be sure the repo includes a file named `CNAME` with this content:
> ```
> genymacedo.com
> ```

---

## 🔄 SSL Auto-Renewal Notes

- GitHub Pages auto-renews SSL certificates every 90 days.
- If DNS settings break or CNAME is deleted, HTTPS may stop working.
- You can re-enable HTTPS from **Settings > Pages > Enforce HTTPS**

---

## 🧪 Local Preview

```bash
bundle exec jekyll serve
```

Then open: [http://127.0.0.1:4000](http://127.0.0.1:4000)

---

## 📬 Contact

**Geny Macedo**  
💼 [LinkedIn](https://www.linkedin.com/in/genymacedo/)  
💻 [Website](https://genymacedo.com)  
📫 geny_macedo@outlook.com
